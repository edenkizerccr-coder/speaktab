# SpeakTab

SpeakTab is a free Windows app for reading and practising guitar tablature, chord charts and supported scores. It is designed primarily for blind and low-vision musicians. Sighted musicians can use it too, though their experience may vary. It offers keyboard navigation, accessible text for screen readers and Braille, practice playback, and an optional AI teacher for guitar and piano.

## Download SpeakTab

**Current release: 10.14.33.**

**[Download the latest complete SpeakTab app](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab-Windows.zip)**

This permanent link downloads the app ZIP directly. Choose Extract All, keep the extracted runtime, licenses and guides together, and run **SpeakTab.exe** from the extracted folder. Keep your original music and previous/recovery app copy. You need only this Windows ZIP to use the app.

**[Download the complete user manual — Word document](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.User.Manual.docx)**

**[Download the Quick Start — Word document](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.Quick.Start.docx)**

Read these documents offline with your preferred Word-compatible reader, screen reader or Braille device. The 103-page expanded manual has a first-use teacher walkthrough, 13 numbered chapters and five appendices covering all 154 menu actions, settings, shortcut customization, import-error recovery, remediation, exact reader voice phrases, examples, troubleshooting, feature requests and tests. The quick start is a shorter introduction. Both begin with your own music; the included sample is optional. The main instructions follow File, Navigate, Playback, Practice, ChatGPT, Voice and Help in menu order, with access keys and default shortcuts beside commands. To search for music, use File > Find tabs or chords (F2; menu access Alt+F, then F).

[Manual in plain text](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.User.Manual.txt) | [Quick Start in plain text](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.Quick.Start.txt) | [Keyboard shortcuts by menu](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/Keyboard.Shortcuts.By.Menu.txt) | [Optional HTML manual](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.User.Manual.html)

The expanded Word manual includes the version 33 supplement; the Quick Start covers the retained setup and operating routes. Help > User guide opens the packaged in-app guide; download the expanded offline manuals separately using the links above.

[Release notes and all downloads](https://github.com/edenkizerccr-coder/speaktab/releases/latest) | [Complete developer source handoff](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab-Source.zip)

## New in 10.14.33

## What changed since 10.14.31

- General teaching preferences persist in each student's private profile across pieces, including preferences requested after onboarding. Guitar and piano fields remain separate.
- Optional automatic piece memory keeps recognized lesson conversation locally with the corresponding piece. It starts off for new students. Explicit saved lesson summaries and passage notes remain available.
- Fresh response context supplies current preferences and reading details. Instructions distinguish Continue from Repeat and discourage repeated setup, tuning and assurances while retaining complete requested musical explanations.
- The teacher can search supported local music recursively in named folders and follow a changed folder direction.
- Note events distinguish new attacks and tie starts/continuations. Written MusicXML and Guitar Pro meter is retained for teacher context and newly saved readings. Explicit spoken practice notes save and verify locally.
- Includes 27 built-in teaching topics, 24 free reference routes and twelve original beginner studies. Each student supplies their own authorized course materials.
- The expanded 103-page Word manual adds teacher memory, Ultimate Guitar download guidance, API costs and key privacy. The Quick Start is also available separately.


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

Open supported text tab, chord charts, Guitar Pro, MusicXML, MuseScore or PDF files. PDF/OCR is experimental. Keep the original and check imported music and warnings. Ctrl+S saves one song workspace; File > My readings reopens it. Separate text/HTML export is available.

- **Ctrl+O:** open. **Ctrl+1/2/3:** source, score, current explanation. **Ctrl+4:** tuning. Escape from details returns to the score.
- With score focus, **Left/Right** moves through time and **Up/Down** inspects simultaneous supplied notes. **Ctrl+PageUp/PageDown** moves measures; **Ctrl+G** jumps to a measure number.
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

The root release gate and **61 focused software checks passed**, along with both complete package, source/executable/document, embedded guide, manifest, runtime/license and privacy checks. The production updater extracted the actual complete app ZIP with the expected executable hash. Source-search findings are specific to the songs tested; physical microphone and device acceptance is separate.

Search needs broader testing. **NVDA remains untested; NVDA testers are welcome.** Further physical JAWS/Braille/device, microphone/audio, piano staff/loop and live teacher tests remain useful. PDF/OCR can misread notes, rhythm or pages. Intermittent imported-tuning focus remains; confirm or reselect the intended part and retry Ctrl+4. Compare readings and suggestions against source music.

## Update or contribute

**10.14.12 and newer:** use **Help > Check for updates > Download and install**. **10.14.11 and earlier:** install the complete current Windows ZIP manually once, because the older updater can reject guide filenames. Never update by replacing only the executable. Keep the recovery copy. Google Drive full release ZIP replacement remains manual.

Developers: use **SpeakTab-Source.zip** for the complete handoff, dependencies, original fixtures, build instructions and manifest. GitHub's generated source archives are not that complete handoff. Packaged prepublication records are preparation checkpoints; the current release page records publication. Send proposed changes to Eden for review; downloading does not grant repository write access.

Use **Help > Report a bug / email Eden**, **Help > Prepare feature test report**, or [open an issue](https://github.com/edenkizerccr-coder/speaktab/issues/new). Reports are reviewed before you send them; nothing is emailed automatically. Remove passwords, API keys and private music.
