# SpeakTab

SpeakTab is an accessible Windows music reader and practice companion for guitar and supported piano scores. Explore your music with a keyboard, screen reader, Braille display or free voice commands. Move to a measure, read notes and chords, hear a practice preview, slow down and loop a passage.

Open **Guitar Pro, MusicXML, MuseScore, PDF, text tablature and chord charts**. **Find music (F2)** searches supported sources for tabs, chord charts and score downloads, with browser guidance where needed. Choose optional AI help for explanations, file recovery or guided practice. Main reading, local playback and free voice navigation work without paid AI; voice commands require microphone setup.

## Download and start

**Current release: 10.14.49.**

**[Download the complete Windows app](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab-Windows.zip)**

Extract the complete ZIP into your own SpeakTab folder, keep the included runtime, licences and guides together, and run **SpeakTab.exe**. Keep original music and a previous or recovery app copy. The first ordinary launch offers a skippable welcome introduction; **Help > Welcome to SpeakTab** reopens it. Opening a file directly goes to that file.

**[Quick Start in Word](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.Quick.Start.docx)** · **[Complete manual in Word](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.User.Manual.docx)**

The current10.14.49 Quick Start is two print pages; the full manual is115. All159 menu commands,96 fixed reader phrases and44 alternatives are documented, with current menu letters and saved-note review. Both lead with what SpeakTab does, supported files, music discovery, voice navigation and local practice. Download these companion documents separately; native Help guides are included with the app. Use Word headings or your reader's document navigation to find a topic.

[Quick Start text](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.Quick.Start.txt) · [Manual text](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.User.Manual.txt) · [Manual HTML](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.User.Manual.html) · [Native guide HTML](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.User.Guide.html) · [Keyboard shortcuts by menu](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/Keyboard.Shortcuts.By.Menu.txt)

## Your first few minutes

1. Choose **Try included music**, open your own file with **Ctrl+O**, or use **F2** to find music.
2. Press **Ctrl+2** for the score. **Left/Right** moves through time; **Up/Down** inspects simultaneous notes or strings without editing them. **Ctrl+PageUp/PageDown** moves by measure; **Ctrl+G** jumps to a measure.
3. Press **Ctrl+3** for the full explanation, then **Ctrl+2** to return. **Ctrl+1** lets you compare source information. **Alt+Shift+I** opens the import summary and uncertainties.
4. Press **Ctrl+P** to play and **Ctrl+Shift+P** to stop. Playback settings changes speed and guitar sound; Practice offers loops, bookmarks, notes and count-in.
5. Press **Ctrl+S** to save a named reading directly in Saved Readings. **File > My readings** reopens it. **F1** opens control help and **Ctrl+Alt+P** finds commands.

## Move through music by voice

Set up the **free reader microphone** from Voice. Commands include moving to a numbered measure, reading notes, playing and stopping music. **Voice > Exact microphone phrases** lists the accepted words without starting a microphone. Speech recognition depends on the microphone, language and environment; use the keyboard whenever preferred.

The optional AI teacher and conversation can explain music and help plan practice. They are separate from the free navigation commands. Connected AI, AI file repair and some online voices require separate setup, internet and any provider charges; a subscription does not necessarily include API usage. No account or paid AI is required for the core reading and local practice tools.

## Files and finding music

- **Guitar Pro:** .gp3, .gp4, .gp5, .gpx and .gp. Structured guitar parts can retain tuning, strings, frets, rhythm and techniques. **Ctrl+T** chooses another part from the original score.
- **MusicXML:** .musicxml, .xml and .mxl. **MuseScore:** .mscz and .mscx. These can supply pitches, staves, rhythm, lyrics and other markings.
- **Text tabs and chord charts:** .txt, .tab, .asc, .chord, .chords, .crd, .cho and .pro. Text tab can have estimated rhythm; chord charts provide accompaniment rather than every melody note.
- **PDF:** local reading tries the available text and score information. Scans and unusual notation can need recognition or repair. Compare uncertain imports with the original.
- **Copied webpage music:** copy the actual selectable tab or chord text and use **Ctrl+Shift+V**. A URL, picture or interactive player alone is not copied music.

F2 offers named sources and download guidance. You can also open a teacher's file or a download you are permitted to use. Member-library downloads may require the site's browser and account. SpeakTab does not unlock paid scores or turn every video lesson into a transcription.

## New in 10.14.49

- **Complete documentation refresh:** manual, Quick Start, shortcut references and built-in help now match the current app. Changed menu letters and missing practice-note commands are corrected.
- **Accepted behavior retained:** version49 changes documentation/help/version only; music reading, playback, voice and JAWS navigation code retain version48.

### Reading improvements carried forward from the accepted local update

- **Hold length once:** a note's complete sounding length is given at its first attack. Untied ongoing notes are not repeatedly named as other notes begin. A written tied continuation remains identifiable, and genuine new attacks of the same pitch are still announced.
- **Opening score information:** the supplied time signature and MusicXML key signature appear once on the opening score row. A missing key is not guessed from notes; older readings may need the original MusicXML reopened for a key omitted by an earlier importer.
- **Restored sounds:** steel-string acoustic guitar and the earlier sampled piano replace the intervening local instrument experiments. Existing saved readings use these sounds automatically. Optional guitar stereo processing remains available.
- **Stable navigation:** the native focus/selection correction is retained; selection changes avoid scanning every score row. Saved loops and places are retained, and opening an active saved loop identifies it. Clear a loop with Ctrl+Shift+0, then Ctrl+S to save.
- **Earlier features retained:** the welcome introduction, tutorials, free voice commands, optional AI, music search, supported repeats, Guitar Pro techniques and MusicXML trills, mordents, turns, tremolo and ornament accidentals remain.

## Choose the right tool

SpeakTab is strongest at **accessible, step-by-step reading and focused practice** from supported files. A clear structured score generally gives more detail than a scan.

Use a notation editor to compose, arrange or engrave printed scores; score writing is future work in SpeakTab. Use recording or music-production software for recording, mixing and detailed instrument performance. Use specialist transcription tools and review for embossed braille-music notation. SpeakTab's Braille access follows the screen reader and display, and BRF export is textual UEB prose, not braille music.

## Verification and current limits

The root release gate and **80 focused software checks passed**. Complete app/source packages, required runtime files, licences, native guides, manifests and privacy were checked. Production updater extraction returns the exact tested executable. Existing saved music and settings were hash-checked unchanged during local installation.

The local user accepted the updated JAWS note announcements and reported that the earlier JAWS fixes held. The user also heard and accepted a short Windows spoken-answer test. An additional audit checked complete-answer chunking, replay, speech on/off and cancellation using simulated natural-voice responses. These results do not certify every score, device, Braille setup or external AI/live-voice service. Earlier basic NVDA/JAWS navigation acceptance remains historical evidence.

Ornaments and grace notes can be described without being expanded into performed playback notes. Expressive guitar effects remain approximate. Complex D.C., D.S., Coda and malformed repeats can play linearly. Existing saved readings without repeat metadata may need reopening from a structured original to gain it. PDF/OCR and AI recovery require checking against the source.

Version49 updates documentation, embedded help and the version number. Runtime music, playback, selection and voice source is unchanged from the user-accepted48 implementation. The full manual and Quick Start are current49 editions.

## Developers and feedback

[Complete developer source handoff](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab-Source.zip) · [Release notes and all assets](https://github.com/edenkizerccr-coder/speaktab/releases/latest) · [Report an issue](https://github.com/edenkizerccr-coder/speaktab/issues)

Use SpeakTab-Source.zip for the complete build handoff. GitHub's generated source archives contain the repository snapshot and are not the complete application source package. Retain bundled component and audio credits. No credentials, private music, saved readings or session data are included in release packages. Downloaded ornament-test scores remain local and are not bundled.

