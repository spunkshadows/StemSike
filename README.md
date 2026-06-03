# reacoaxer

**A :inlineEntity{type="inline_entity" conversation="092948bf4bc8ab8c328b3b1deafab51437ed" name="Reaper"} (Rapid Environment for Audio Production, Engineering, and Recording) DAW extension by :inlineEntity{type="inline_entity" conversation="092948bf4bc8ab8c328b3b1deafab51437ed" name="Cockos&#32;Incorporated"} that analyzes live audio stems in real-time, generating intuitive, musician-friendly performance cues and adaptive feedback.**

Designed for live performers and workshop facilitators, `reacoaxer` acts as an intelligent companion, "coaxing" optimal performance from your WAV stems through subtle, context-aware suggestions.

## ✨ Features

*   **Real-Time Stem Analysis**: Monitors live audio input with low-latency Lua scripting. :inlineCitations{data="&#91;&#123;&quot;url&quot;&#58;&quot;https&#58;//www.azstoke.jp/en/post/reaper-complete-guide-from-reaper-introduction-to-reascript-creation&quot;,&quot;favicon&quot;&#58;&quot;https&#58;//imgs.search.brave.com/DbigKOtaVY5cFJ5ElbYaN5UABnrcEiHFMFcwVJstb1I/rs&#58;fit&#58;32&#58;32&#58;1&#58;0/g&#58;ce/aHR0cDovL2Zhdmlj/b25zLnNlYXJjaC5i/cmF2ZS5jb20vaWNv/bnMvOTI0YjhjODE2/YmFkZWZmNDQ3NWI0/Y2FmMjNkNzZmZjBh/YjQ5YjE2YjhlZTJh/MTQwZjgwNmQ2OTMz/N2MwZTlmNi93d3cu/YXpzdG9rZS5qcC8&quot;,&quot;title&quot;&#58;&quot;Reaper&#32;Complete&#32;Guide&#32;-&#32;From&#32;Reaper&#32;introduction&#32;to&#32;Reascript&#32;...&quot;,&quot;snippet&quot;&#58;&quot;…dows&#92;n&#92;nMac&#92;n&#92;nChange&#32;the&#32;look&#32;of&#32;Reaper&#92;n&#92;nReaper&#32;licensing&#92;n&#92;n-Biggest&#32;advantage-ReaScript&#32;setup&#32;&#91;AZSTOKE&#32;shortest&#32;script&#32;enhancement&#93;&#92;n&#92;nWhat&#32;is&#32;Reascript?&#92;n&#92;nReascript&#32;language&#32;type&#92;n&#92;nWhat&#32;is&#32;ReaScript&#32;API?&#92;n&#92;nWhat&#32;you&#32;can&#32;do&#32;with&#32;“BRONZE”&#92;n&#92;nHow&#32;to&#32;join&#32;“BRONZE”&#92;n&#92;nInstalling&#32;“BRONZE”…&quot;&#125;&#93;"}
*   **Musician-Friendly Cues**: Translates complex audio data into actionable performance prompts (visual or OSC).
*   **Adaptive Feedback**: Adjusts suggestions dynamically based on stem behavior and performance context. :inlineCitations{data="&#91;&#123;&quot;url&quot;&#58;&quot;https&#58;//www.azstoke.jp/en/post/reaper-complete-guide-from-reaper-introduction-to-reascript-creation&quot;,&quot;favicon&quot;&#58;&quot;https&#58;//imgs.search.brave.com/DbigKOtaVY5cFJ5ElbYaN5UABnrcEiHFMFcwVJstb1I/rs&#58;fit&#58;32&#58;32&#58;1&#58;0/g&#58;ce/aHR0cDovL2Zhdmlj/b25zLnNlYXJjaC5i/cmF2ZS5jb20vaWNv/bnMvOTI0YjhjODE2/YmFkZWZmNDQ3NWI0/Y2FmMjNkNzZmZjBh/YjQ5YjE2YjhlZTJh/MTQwZjgwNmQ2OTMz/N2MwZTlmNi93d3cu/YXpzdG9rZS5qcC8&quot;,&quot;title&quot;&#58;&quot;Reaper&#32;Complete&#32;Guide&#32;-&#32;From&#32;Reaper&#32;introduction&#32;to&#32;Reascript&#32;...&quot;,&quot;snippet&quot;&#58;&quot;top&#32;of&#32;page&#92;n&#92;nClose&#92;n&#92;nClose&#92;n&#92;nClose&#92;n&#92;nReaper&#32;Complete&#32;Guide&#32;-&#32;From&#32;Reaper&#32;introduction&#32;to&#32;Reascript&#32;creation&#32;-&#92;n&#92;nFeb&#32;23,&#32;2024&#92;n&#92;n17&#32;min&#32;read&#92;n&#92;nUpdated&#58;&#32;Jul&#32;9,&#32;2025&#92;n&#92;nWe&#32;will&#32;publish&#32;information&#32;for&#32;those&#32;who&#32;are&#32;considering&#32;introducing&#32;Reaper.&#32;The&#32;content&#32;is&#32;ac…&quot;&#125;&#93;"}
*   **Live Workshop Ready**: Ideal for stage-show workshops, interactive installations, and ENM play parties requiring audio cues.

## 🚀 Installation

### Via ReaPack (Recommended)
1.  Open **Reaper** → **Extensions** → **ReaPack** → **Import repositories**.
2.  Add the URL: `https://github.com/spunkshadows/reaspunk/raw/main/index.xml` (once you create your index file).
3.  Click **OK** → **Synchronize**.
4.  Search for `reacoaxer` and install.

### Manual Installation
1.  Download the latest `.lua` script from the [Releases](../../releases) page.
2.  Place the file in your Reaper Scripts directory:
    *   **Windows**: `%APPDATA%\REAPER\Scripts\`
    *   **macOS**: `~/Library/Application Support/REAPER/Scripts/`
    *   **Linux**: `~/.config/REAPER/Scripts/`
3.  Restart Reaper (or run **Actions** → **Reload extension scripts**). :inlineCitations{data="&#91;&#123;&quot;url&quot;&#58;&quot;https&#58;//www.azstoke.jp/en/post/reaper-complete-guide-from-reaper-introduction-to-reascript-creation&quot;,&quot;favicon&quot;&#58;&quot;https&#58;//imgs.search.brave.com/DbigKOtaVY5cFJ5ElbYaN5UABnrcEiHFMFcwVJstb1I/rs&#58;fit&#58;32&#58;32&#58;1&#58;0/g&#58;ce/aHR0cDovL2Zhdmlj/b25zLnNlYXJjaC5i/cmF2ZS5jb20vaWNv/bnMvOTI0YjhjODE2/YmFkZWZmNDQ3NWI0/Y2FmMjNkNzZmZjBh/YjQ5YjE2YjhlZTJh/MTQwZjgwNmQ2OTMz/N2MwZTlmNi93d3cu/YXpzdG9rZS5qcC8&quot;,&quot;title&quot;&#58;&quot;Reaper&#32;Complete&#32;Guide&#32;-&#32;From&#32;Reaper&#32;introduction&#32;to&#32;Reascript&#32;...&quot;,&quot;snippet&quot;&#58;&quot;…characters&#32;from&#32;&#92;&quot;Hello&#32;World&#92;&quot;&#92;n&#92;n-Biggest&#32;advantage-&#91;PYTHON&#93;-&#92;&quot;HelloWorld&#92;&quot;&#32;with&#32;Reascript&#92;n&#92;nUsing&#32;the&#32;REAPDOCK&#32;document&#92;n&#92;nDownload&#32;from&#32;ScriptCode&#92;n&#92;nRun&#32;the&#32;downloaded&#32;file&#92;n&#92;nLet's&#32;change&#32;the&#32;characters&#32;from&#32;&#92;&quot;Hello&#32;World&#92;&quot;&#92;n&#92;nStart&#32;creating&#32;scripts&#32;with&#32;REAPDOCK/APIDOCK&#92;n&#92;n□Lua&#92;n&#92;n&#91;REAPDOCK&#93;&#32;Automatically&#32;cha…&quot;&#125;&#93;"}

## 🎮 Usage

1.  Load your live WAV stems into Reaper tracks.
2.  Run the action: **`reacoaxer: Start live stem coaxing`** (found in the Actions List under `reacoaxer`).
3.  Observe the **Custom Action Bar** or **OSC output** for real-time cues.
4.  Adjust sensitivity in the built-in configuration menu (`reacoaxer: Settings`). :inlineCitations{data="&#91;&#123;&quot;url&quot;&#58;&quot;https&#58;//www.azstoke.jp/en/post/reaper-complete-guide-from-reaper-introduction-to-reascript-creation&quot;,&quot;favicon&quot;&#58;&quot;https&#58;//imgs.search.brave.com/DbigKOtaVY5cFJ5ElbYaN5UABnrcEiHFMFcwVJstb1I/rs&#58;fit&#58;32&#58;32&#58;1&#58;0/g&#58;ce/aHR0cDovL2Zhdmlj/b25zLnNlYXJjaC5i/cmF2ZS5jb20vaWNv/bnMvOTI0YjhjODE2/YmFkZWZmNDQ3NWI0/Y2FmMjNkNzZmZjBh/YjQ5YjE2YjhlZTJh/MTQwZjgwNmQ2OTMz/N2MwZTlmNi93d3cu/YXpzdG9rZS5qcC8&quot;,&quot;title&quot;&#58;&quot;Reaper&#32;Complete&#32;Guide&#32;-&#32;From&#32;Reaper&#32;introduction&#32;to&#32;Reascript&#32;...&quot;,&quot;snippet&quot;&#58;&quot;…be&#32;a&#32;DAW&#32;that&#32;can&#32;be&#32;used&#32;in&#32;professional&#32;settings.&#92;n&#92;nClick&#92;n&#92;nhere&#32;for&#32;the&#32;price&#32;range&#32;page&#32;on&#32;the&#32;Reaper&#32;official&#32;website.&#92;n&#92;n&#36;60&#58;&#32;Discount&#32;license&#92;n&#92;n&#36;225&#58;&#32;Commercial&#32;license&#92;n&#92;nReaper&#32;is&#32;equipped&#32;with&#32;the&#32;standard&#32;features&#32;necessary&#32;for&#32;game&#32;sound,&#32;even&#32;when&#32;used&#32;for&#32;re…&quot;&#125;&#93;"}

### Example Workflow
```lua
-- The script automatically detects transients and harmonic density
-- and suggests timing adjustments via on-screen prompts.   
