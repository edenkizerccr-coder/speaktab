# SpeakTab

SpeakTab is a Windows music reader and practice companion for keyboard, screen-reader and Braille users. Open supported scores, move through an accessible reading, hear local practice previews, slow down, loop passages and keep practice notes. Connected AI is optional.

## Download version 10.14.62

- [Complete Windows application](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab-Windows.zip)
- [Current Word user manual](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.User.Manual.docx)
- [One-page Quick Start](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.Quick.Start.docx)
- [Testing steps](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.Testing.Steps.docx)
- [Complete source handoff](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab-Source.zip)
- [Release notes and all downloads](https://github.com/edenkizerccr-coder/speaktab/releases/tag/v10.14.62)

Extract the complete application ZIP into its own folder and run SpeakTab.exe. Keep the runtime, fixtures, licences and native guides together. Windows with .NET Framework 4.8 is required. Existing users can use the in-app updater. The current Word manuals and text/HTML alternatives are companion downloads and are included in the complete source handoff. GitHub-generated source archives contain the repository snapshot instead.

## Written strums and current documentation

Version62 preserves explicitly written Guitar Pro upstroke/downstroke and brush/arpeggio marks in the selected score row, F3 details, written-patterns view and saved readings. Marked guitar chords play with a short low-to-high spread for downstrokes and high-to-low for upstrokes. This approximates direction using the existing samples; timing, ties, loop limits and repeats are retained. Unmarked chords remain unchanged; no alternating pattern is invented.

Read the [62 changes and known limitation](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.62.Changes.and.Known.Limit.txt). The reviewed65-page manual, Quick Start, testing steps and3-page podcast remain version60 references for unchanged controls, with the62 supplement covering these additions. They have not been relabelled as newly reviewed62 editions.

## Known optional live teacher limitation

The live AI teacher can reject dense or long passages with an instruction-token-limit error. The user encountered this with Chopin; this issue is not fixed in62 and is being investigated separately. The recording setup also prevented complete live microphone acceptance. A smaller excerpt may help but is not a guaranteed workaround. Local score reading, playback, loops and bookmarks do not need AI. The user accepted the other tests and authorized publication with this limitation documented.

## Menus and practice shortcuts

With a score open, press and release **Alt**, then **Down** to open a menu. Left/Right move through menus; Escape returns to the score. Left/Right alone in the score follow musical time.

**Ctrl+Shift+1** sets loop start; **Ctrl+Shift+2** sets the end and enables repeat. **Ctrl+Shift+0** clears the current and existing saved loop fields immediately. **Ctrl+Shift+9** opens a measure range and **Ctrl+Shift+L** loops the current measure. Save a new loop with Ctrl+S. Ctrl+P plays; Ctrl+Shift+P stops.

**Ctrl+B** adds a bookmark. **Alt+Shift+1** through **9**, and **Alt+Shift+0** for bookmark 10, jump to bookmarks. Ctrl+Alt+number still jumps to practice notes. The user reports the local tests worked apart from the optional live teacher limitation described above.

[Podcast blurb and things to try](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.Podcast.Blurb.and.Test.Steps.10.14.60.docx) provides a short opening score review and current test steps.

## Simpler ChatGPT controls and quieter reading

**F5** focuses Ask ChatGPT. Type a question and press **Enter** to send it once. **F6** focuses the complete answer from its beginning. F5 returns to the question without resending. F4 connects ChatGPT when needed; Ctrl+2 returns to the score.

**F12** silences enabled app voices and automatic playback announcements; press it again to resume. Music and microphone connections continue. **F9** ends the AI teacher lesson and stops its microphone. **Ctrl+Alt+L** toggles the separate free command microphone. Opening or leaving idle chat does not start listening. Routine teacher progress stays quiet, and chat labels are shorter.

Ctrl+1 reveals source or score summary; Ctrl+2 returns to the score and hides it. Navigate > Reader status provides status on demand. Help > Welcome to SpeakTab reopens the startup introduction; Help > Guided tutorials offers fourteen local lessons. The current full manual, Quick Start, testing steps and keyboard references cover version 60.

## Read and practise

Ctrl+O opens music; Ctrl+D opens included practice music; F2 finds sources. Ctrl+2 focuses the score. Right/Left follows musical time; Up/Down inspects simultaneous notes or strings. Ctrl+PageDown/PageUp changes measure and Ctrl+G jumps to a written measure number.

F3 opens full current-position information, including available simultaneous and continuing notes, rests, lyrics, marks and last-written-chord context. It preserves the selected concise or compact style. Ordinary navigation avoids repeatedly naming ongoing untied notes. Ctrl+Shift+I opens supplied key, meter, capo, tuning, part and tempo. Escape returns to the selected row. Missing source facts are identified rather than guessed.

Ctrl+T selects supported readable parts. MusicXML/MuseScore can include recognized instruments and SATB parts, with retained printed lyrics. Local previews include supported instrument sounds and drum kits; vocal previews are wordless. Playback is one selected part at a time. Supplied ornament names do not imply that every ornament is expanded into performed notes.

Ctrl+P plays and Ctrl+Shift+P stops. Practice > Loop a measure range sets a passage with optional gradual speed increases. Ctrl+S explicitly saves a new reading or loop. Practice > Clear loop immediately clears saved loop fields. Bookmarks, practice notes, saved-reading navigation and reading exports support continued practice.

Supported sources include Guitar Pro, MusicXML, MuseScore, suitable PDFs, text tabs and chord charts. Source structure determines available pitches, timing, staff/voice labels, strings, frets, lyrics and techniques. PDF/OCR and uncertain imports need comparison with the original. Guitar Pro part selection currently supports six-string guitar parts. Textual UEB BRF export is prose braille, not music-braille transcription.

## Repair a bad score in your own ChatGPT window

File > Repair score in ChatGPT window lets you choose the original and describe the problem. The prepared request already explains SpeakTab and its MusicXML or text requirements. Explicitly choose Copy request and open ChatGPT, paste the request, attach the original there and download the returned copy. Open returned file imports it for checking. Compare notes, rhythm, lyrics and coverage against the original. Opening the repair tool does not automatically upload or send files.

## Verification and privacy

The main release gate and all100 focused checks passed for the published executable. Complete packages, the source manifest, updater extraction and saved-key privacy checks passed. The user confirmed Enter sends, F5 returns to the question, F6 reads the answer, F12 silences speech and the interface is cleaner. This scoped evidence does not establish universal screen-reader, microphone, musical or audio accuracy.

No AI account is needed for ordinary reading and local practice. Connected AI/teacher features require separate access and may incur provider charges. Optional ChatGPT read-aloud uses local Windows voice. Startup and tutorial audio begin only when requested. F1 explains the focused control and Ctrl+Alt+P finds commands.

Private songs, saved readings, settings, credentials and diagnostic dumps are excluded from downloads. Previous public releases and assets remain available. Embedded preparation notes retain their earlier local-test status; the release records the later publication. Sung lyrics, Finale support and a possible rename remain future work.

