# SpeakTab

SpeakTab is a free Windows app for reading and practising guitar tablature, chord charts and supported scores. It is designed primarily for blind and low-vision musicians. Sighted musicians can use it too, though their experience may vary. It offers keyboard navigation, accessible text for screen readers and Braille, practice playback, and an optional AI teacher for guitar and piano.

## Download SpeakTab

**Current release: 10.14.43.**

**[Download the latest complete SpeakTab app](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab-Windows.zip)**

This permanent link downloads the app ZIP directly. Choose Extract All into your own SpeakTab folder, keep the extracted runtime, licenses and guides together, and run **SpeakTab.exe** from the extracted folder. Keep your original music and previous/recovery app copy. You need only this Windows ZIP to use the app.

**[Download the complete user manual — Word document](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.User.Manual.docx)**

**[Download the Quick Start — Word document](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.Quick.Start.docx)**

Read these documents offline with your preferred Word-compatible reader, screen reader or Braille device. The 105-page expanded manual has a first-use teacher walkthrough, 13 numbered chapters and five appendices covering menu actions including saved practice-note review, settings, shortcut customization, import-error recovery, remediation, exact reader voice phrases, examples, troubleshooting, feature requests and tests. The quick start is a shorter introduction. Both begin with your own music; the included sample is optional. The main instructions follow File, Navigate, Playback, Practice, ChatGPT, Voice and Help in menu order, with access keys and default shortcuts beside commands. To search for music, use File > Find tabs or chords (F2; menu access Alt+F, then F).

[Manual in plain text](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.User.Manual.txt) | [Quick Start in plain text](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.Quick.Start.txt) | [Keyboard shortcuts by menu](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/Keyboard.Shortcuts.By.Menu.txt) | [Optional HTML manual](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.User.Manual.html)

The expanded Word manual and Quick Start remain the reviewed 10.14.34 editions. Current 10.14.43 navigation instructions are in the packaged native guide and its standalone HTML download. The Word manual includes the version 34 practice-note instructions; the Quick Start covers retained setup and operating routes. Help > User guide opens the packaged in-app guide; download the expanded offline manuals separately using the links above.

[Release notes and all downloads](https://github.com/edenkizerccr-coder/speaktab/releases/latest) | [Complete developer source handoff](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab-Source.zip)

## New in 10.14.43

Ordinary **Left/Right** score navigation now selects a prebuilt native note row whose accessible text stays unchanged. **Up/Down** inspects simultaneous guitar strings or piano notes at the same beat. A piano staff change names the new staff; continuing on that staff does not repeat its name. Measure context returns when entering a measure. Brief note lengths remain, including **0.5 beat** for an eighth note and **0.25 beat** for a sixteenth. **Ctrl+3** opens the complete current explanation.

The prior JAWS repeat was intermittent: one arrow command and one score update could still lead to two spoken lines. Changing JAWS highlighting and delaying the update did not resolve it. The new score rows stay fixed while the selection moves; no JAWS script or setting is installed. Original notes, strings/frets, rests, ties, lyrics, saved music and playback timing remain intact.

Eden physically checked basic navigation in the installed build: with **JAWS**, three guitar Right moves, three piano Right moves and one piano Up/Down move, then about ten more ordinary Left/Right moves, each spoke once. With **NVDA**, two Right moves and one Up/Down move each spoke once. These are the tested paths; broader score, Braille, device, microphone and lesson behavior still benefit from hands-on testing.

The in-app guide was embedded before these physical checks. Its local-test and public-10.14.38 status lines are earlier checkpoints; the result above is the later status.

Since public 10.14.38, **Ctrl+S** saves one named reading file directly in **Saved Readings**. The fixed **Alt+Shift+PageDown/PageUp** keys move to the next/previous beat or note group; **Ctrl+PageDown/PageUp** still moves measures. The expanded Word manual and Quick Start remain the reviewed 10.14.34 editions; use the current packaged/native guide for these newer steps.

## Earlier: 10.14.38

Score reading introduces the measure once: “Measure 1, beat 1,” then “Beat 2,” “Beat 3,” and the supplied decimal subdivisions. Staff names are introduced once per measure rather than before every note or beat. Individual notes and both supplied staves remain available.

Tied durations are included at the original attack. Ordinary navigation and playback position following skip unchanged tie-only continuations, without shortening the actual sound. Rests, lyrics, written directions and uncertain tie origins remain available. The native note list, details and free spoken beat commands now use the same concise current reading. Explicit “where am I” and “which staff” remain available.

Text and HTML exports omit reopening data and duplicated structured-score summaries. Ctrl+S still keeps complete reopenable readings. The settings and announcements say Playback speed. These changes apply across supported scores; original notes, strings/frets, timing, saved data and AI lesson context are retained.


## Retained voice and practice features

- **Hands-free teacher controls:** with the free reader microphone on, say **start teacher** to connect the configured live lesson or **stop teacher** to end it while keeping the local listener available. Use **next measure**, **play** and **stop music** when ready. The unreliable alternate teacher-start phrase was removed following Eden's test.
- **Optional wake word:** **Voice > Reader microphone settings** has **Require SpeakTab wake word**, off by default. Leave it off for ordinary phrases; turn it on for **SpeakTab next measure**, for example. This applies to fixed local commands, not live teacher conversation.
- **Broader live app actions and music teaching:** the live teacher can invoke exact existing native menu commands. Its instructions cover guitar, piano, music theory and Braille music, with music-only research and code references for uncertain rules. Actual model behavior needs continued testing.

Retained guide and practice features:

- **Packaged help:** the app includes its in-app guide, heading chooser, six worked examples and 32 editable defaults. The separately downloadable User Manual above provides the expanded operating instructions and complete references.
- **Combined loop and speed setup:** **Practice > Loop a measure range**, default **Ctrl+Shift+9**, sets the passage and optional speed increases together. Example: 60% to 100%, five percentage points after every three complete loops. Exact partial-beat endpoints can be retained. Cancel preserves both settings; manual speed changes disable automatic increases.
- **Piano staff commands:** **Navigate > Piano staff** chooses a supplied staff, follows its notes across time, reports the chosen staff, or reads that staff's current measure without moving. Free phrases include **go to staff two**, **next note on staff two** and **read staff two**. Optional custom keys are available. Staff labels do not by themselves establish hands.

The usual Left/Right timeline and Up/Down simultaneous-note navigation stay in place. Guitar strings, frets and tuning remain guitar information. The opening title identifies the part; **Practice > Import summary and uncertainties** gives the instrument and exact part again when needed. Playback remains sampled guitar sound.

## Read and practise

Open supported text tab, chord charts, Guitar Pro, MusicXML, MuseScore or PDF files. PDF/OCR is experimental. Keep the original and check imported music and warnings. Ctrl+S saves a named reading file directly in Saved Readings; File > My readings reopens it. Separate text/HTML export is available.

- **Ctrl+O:** open. **Ctrl+1/2/3:** source, score, current explanation. **Ctrl+4:** tuning. Escape from details returns to the score.
- With score focus, **Left/Right** moves through time and **Up/Down** inspects simultaneous supplied notes. Fixed **Alt+Shift+PageUp/PageDown** moves to the previous/next beat or note group. **Ctrl+PageUp/PageDown** moves measures; **Ctrl+G** jumps to a measure number.
- **Ctrl+P:** play. **Ctrl+Shift+P:** stop. **Ctrl+Shift+PageDown/PageUp:** slower/faster. **Ctrl+Shift+5:** normal speed.
- **Ctrl+Shift+L:** loop current measure. **Ctrl+Shift+9:** loop and optional speed settings. **Ctrl+Shift+1/2:** beat loop boundaries. **Ctrl+Shift+0:** clear loop.
- **Ctrl+B:** bookmark. **Ctrl+Shift+J:** return to the latest bookmark. **Ctrl+Shift+Y:** practice note. **Alt+Shift+Q/F:** concise/compact explanations.
- **Ctrl+Alt+P:** command palette with current menu routes and keys. **Help > Guided tutorials** offers fourteen lessons and optional local read-aloud.

The 32 added shortcut defaults can be reassigned, cleared or restored in **Help > Customize keyboard shortcuts**. Fixed shortcuts cannot be reassigned or cleared. Menus and the palette show current assignments; test for conflicts with your screen reader.

## Voice and optional teacher

Offline reading, menus, practice, guides, tutorials and fixed reader microphone commands need no paid AI. **Voice > Exact microphone phrases** lists the local commands. **Ctrl+Alt+L** toggles listening. Windows English recognition, microphone permission and a working default input are needed. Spoken command replies are optional.

The free microphone uses continuous recognition and has no app inactivity timer. Keep the computer awake. Closing the command window keeps the free microphone on. **Stop listening**, device errors, sleep or exiting SpeakTab can stop it; a completely off mic cannot hear a wake request. Singing and speaker audio may trigger commands. The optional prefix reduces that risk only for fixed local commands. Stop the teacher during practice if you want only local commands; an active live teacher still receives musical sound.

Regular AI answers, cloud speech and the live teacher use their existing provider/account routes. **Voice > Which voice mode? Start, stop and setup help** explains the choices. **Ctrl+Alt+O** opens settings; **Ctrl+Alt+I** reads voice status. **F8** starts the selected conversation mode and **F9** stops voice and its microphone.

The teacher can consult the current guide, tutorials, menu routes and assigned keys. Requested supported reading, navigation, playback, loop/speed, bookmark and piano staff actions keep the conversation active. For other requested functions, the live teacher can look up and invoke exact current native menu actions. File choices, settings, sign-in, updates and reviews retain their normal controls; invocation is not proof the operation finished. Regular typed/Windows-voice answers guide rather than execute these tools. Practice notes open for your Save/Cancel review.

Teacher instructions cover piano, guitar, music theory and Braille music, complete requested measure explanations, music-related research and clear separation of source facts from suggestions. Braille music is distinct from ordinary screen-reader Braille text; contracted textual BRF prose export is available, while braille-music import and certified score transcription are not. Research and AI replies can fail. The live teacher uses a separate voice API key/model and credits; a ChatGPT subscription alone does not provide them. Windows voice can read regular answers locally. Check the guide for setup and routing.

## Testing and limitations

The root release gate and **69 focused software checks passed**. The physical JAWS and NVDA results above cover basic score navigation; microphone and device acceptance is separate.

Search needs broader testing. Further screen-reader paths, Braille/device, microphone/audio, piano staff/loop and live teacher tests remain useful. PDF/OCR can misread notes, rhythm or pages. Intermittent imported-tuning focus remains; confirm or reselect the intended part and retry Ctrl+4. Compare readings and suggestions against source music.

## Update or contribute

**10.14.12 and newer:** use **Help > Check for updates > Download and install**. **10.14.11 and earlier:** install the complete current Windows ZIP manually once, because the older updater can reject guide filenames. Never update by replacing only the executable. Keep the recovery copy. Google Drive full release ZIP replacement remains manual.

Developers: use **SpeakTab-Source.zip** for the complete handoff, dependencies, original fixtures, build instructions and manifest. GitHub's generated source archives are not that complete handoff. Packaged prepublication records are preparation checkpoints; the current release page records publication. Send proposed changes to Eden for review; downloading does not grant repository write access.

Use **Help > Report a bug / email Eden**, **Help > Prepare feature test report**, or [open an issue](https://github.com/edenkizerccr-coder/speaktab/issues/new). Reports are reviewed before you send them; nothing is emailed automatically. Remove passwords, API keys and private music.
