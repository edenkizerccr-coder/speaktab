# SpeakTab

**SpeakTab — an accessible tab and score reader.**

Read supported instrument parts using a keyboard, screen reader or Braille display. Explore notes, chords, lyrics and written markings; hear local practice previews, slow down, loop passages and keep practice notes. AI help is optional.

## Download version 10.14.70

- [Complete Windows application](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab-Windows.zip)
- [Current changes and controls](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.70.Changes.and.Current.Controls.txt)
- [Word user manual for version 70](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.User.Manual.docx)
- [Quick Start](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.Quick.Start.docx)
- [Testing steps](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.Testing.Steps.docx)
- [Complete source handoff](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab-Source.zip)
- [Release notes and all downloads](https://github.com/edenkizerccr-coder/speaktab/releases/tag/v10.14.70)

Extract the complete application ZIP into its own folder and run SpeakTab.exe. Keep the runtime, fixtures, licences and guides together. Windows with .NET Framework 4.8 is required. Existing users can use the in-app updater. The complete source handoff includes the source, runtime dependencies and documentation; GitHub-generated source archives are only the repository snapshot.

## New since public 62

Written ChatGPT now receives the attached companion chord/lyric chart alongside the main score. It can compare supplied chords, lyrics and written picking instructions with the tab. Add it through File > Companion chord or lyric sheet > Add reference file, then Ctrl+S to keep it with the reading. Existing saved companions work after reopening. F5 focuses the written question, Enter sends, and F6 reads the answer. Replacing/removing the reference changes the next prompt. The two arrangements remain separate: compare key, capo, tuning and section before relating them. Written context includes up to 32,000 companion characters, with up to 20,000 recovered source characters first; omissions are marked. A smaller excerpt may be needed. Written answers cannot retrieve omitted pages or use the teacher's action tools.

Text, Markdown and HTML exports keep each beat and its details on one logical line. Long lines may wrap. The reader's vertical note/detail layout is retained. Practice > Compact string-fret pairs (Alt+Shift+F) gives pairs such as 5-0 for supplied fretted-part data; turn it off for expanded wording before saving/exporting. Staff-only parts keep pitch names. F3 retains full wording. Textual BRF exports compact prose with 40-cell/25-line wrapping, not braille music notation. Existing exported files are not rewritten.

Readable original PDF chord sheets retain improved chord placement and complete lyric phrases. Chord-word cues avoid repeating empty/held lyrics; supplied picking prose remains available without invented exact timing. Inferred chord practice counts are not sung timing. Image tab and staff-only recognition remain separate supported workflows, and partial chart excerpts are not full staff transcriptions.

Supplied unpitched percussion keeps drum names without false pitched key names. Pitched instruments retain written pitch. Full explanations no longer repeatedly label suggested fingering as standard tuning; Ctrl+4 and Ctrl+Shift+I still provide on-demand tuning and score information. Original written retuning instructions remain.

General app descriptions and teaching labels refer to music, tabs, scores and the selected instrument. Guitar terms remain for guitar strings/frets/tuning/capo, guitar techniques and named Guitar Pro/Ultimate Guitar services. This wording change does not add new importer or instrument capabilities.

## Optional AI and live-teacher limits

Initial live-teacher score instructions and fresh-purpose text are bounded. Measure tools provide cursor-based pages, with software checks reconstructing dense Chopin measure data completely. This addresses the oversized-request path investigated after 62; renewed live-provider acceptance of that reported instruction-token failure is not claimed. Written companion inclusion is also verified at the outgoing-context level without a paid provider call. Microphone/device behavior and AI answer quality require actual use.

Ordinary reading and local practice do not need an AI account. Connected AI requires separate access and may incur provider charges. Optional written-answer read-aloud uses local Windows voice. F8 starts the configured teacher; F9 stops the lesson and microphone. Ctrl+Alt+L controls the separate free command microphone. F12 silences/resumes enabled speech without stopping music or changing microphones. Opening an idle chat does not start listening.

## Read and practise

Ctrl+O opens Guitar Pro, MusicXML, MuseScore, suitable PDF, text tab or chord-chart files. F2 finds music. Guitar Pro part selection currently supports six-string guitar parts; supported MusicXML/MuseScore scores can supply other instruments and SATB parts. Ctrl+T selects a readable part from the original score. Available pitch, rhythm, staff, voice, string, fret, lyric and technique detail depends on the source. PDF and uncertain imports need comparison with the original.

Ctrl+2 focuses the score. Left/Right follows musical time; Up/Down inspects simultaneous notes, strings or lyric rows. Ctrl+PageDown/PageUp changes measure; Ctrl+G jumps to a written measure. F3 opens full current-position details. Untied held notes avoid repetitive attack announcements. Ctrl+Shift+I gives supplied key, meter, capo, tuning, part and tempo.

Ctrl+P plays and Ctrl+Shift+P stops. Playback covers one selected part at a time, supported instrument sounds and drum kits; vocal previews are wordless. Supplied ornament names are not a promise of fully realized ornament performance. Written Guitar Pro stroke marks retain their reading and approximate directional playback; unmarked patterns are not invented.

Practice > Loop a measure range includes optional gradual speed increases. Ctrl+Shift+1/2 set loop endpoints; Ctrl+Shift+0 clears; Ctrl+Shift+9 opens the range chooser; Ctrl+Shift+L loops the current measure. Ctrl+S saves new readings and loops. Ctrl+B adds a bookmark; Alt+Shift+1 through 9 and 0 jump to numbered bookmarks. Practice notes and exports support continued study.

Press and release Alt, then Down to enter menus; Left/Right moves through menus and Escape returns to the score. Left/Right alone in the score follows musical time. F1 explains the focused control; Ctrl+Alt+P finds commands. Help > Welcome to SpeakTab and Guided tutorials provide local help. File > Repair score in ChatGPT window prepares a request for the user to copy and attach their original; opening that tool does not upload the file.

## Documentation, verification and privacy

The native User guide and [70 supplement](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.70.Changes.and.Current.Controls.txt) describe the current additions. The 65-page Word/text/HTML manual is updated and visually reviewed for version 70, including inclusive instrument wording, part selection, companions and exports. Quick Start, testing steps and the [three-page version 60 podcast](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.Podcast.Blurb.and.Test.Steps.10.14.60.docx) remain references for unchanged controls. Older supplements are historical.

The main gate and 109 focused software checks cover the final executable, including written companion context, compact exports, save/reopen and instrument wording. Real-score comparisons cover selected violin, harp, triangle, timpani and an original drum fixture. The user confirmed compact exports and authorized publication. These checks do not establish universal score, instrument, physical Braille/screen-reader, audio, microphone or live-service accuracy. Source manifest, updater extraction and package privacy checks are required before publication.

Private music, saved readings, settings, credentials, local teacher-tab downloads and diagnostic dumps are excluded. Previous public releases and their assets remain available. Full source regression tests include local real-file audits that require separately obtained reference fixtures; compile-only builds do not require those personal test files. Sung lyrics and Finale support remain future work.
