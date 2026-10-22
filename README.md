# SpeakTab

SpeakTab is a free Windows app for blind and low-vision musicians to read and practice guitar tablature, chord charts, and supported music scores. It uses keyboard-accessible controls, text for screen readers and Braille displays, spoken information, and guitar playback while preserving the original music.

## Download

Open the [latest release](https://github.com/edenkizerccr-coder/speaktab/releases/latest) and expand **Assets**.

- **For musicians and testers:** download **SpeakTab-Windows.zip**, extract the entire ZIP, and run **SpeakTab.exe**. Keep the recognition runtime, licenses, and guides with the app.
- **For developers:** download **SpeakTab-Source.zip** for the complete source handoff, build dependencies, original test fixtures, build instructions, and SHA256 manifest. Read its README before building.
- Standalone guides, shortcuts, release notes, testing records, and checksums are also attached.

GitHub's automatic **Source code** archives contain repository files rather than the complete developer handoff. Use **SpeakTab-Source.zip** for the current application source.

## SpeakTab 10.14.9

**Help > Command palette** opens with **Ctrl+Alt+P**. Search by command name, shortcut, or menu path. The palette lists main-menu actions and keys that work only in the score or a dialog, with their actual route and context. Enter or Run activates executable menu actions; context-only keys tell you where to use them. The main menu spans the reader window. **Navigate** has offline description, string and section actions that also work without a microphone. **Practice** is immediately after **Playback** and opens with **Alt+R**. Practice can loop the current complete measure, a measure range, or selected beats. **Ctrl+P** plays, **Ctrl+Shift+P** or **Playback > Stop** stops playback, and **Practice > Clear loop** removes the repeat setting. Escape also stops playback from the score when chat is closed.

**Help > Guided tutorials** offers thirteen offline lessons, including how to find menu commands and loop measures or beats. A tutorial can stay open while you switch to the reader with Alt+Tab. Its optional **Read lesson aloud** and **Stop audio** controls use local Windows speech. **Voice > Exact microphone phrases** opens a focusable list of every accepted fixed voice phrase directly, with listening off when the window is first opened. The free reader microphone also accepts listed alternative commands. It needs no AI account.

The score and **Ctrl+3** explanation can identify a supported chord inferred from repeated text-tab notes; the app leaves a chord unnamed when the notes do not establish one. The explanation omits generated source line and column numbers. Estimated text-tab beat labels use numeric quarter, eighth, and sixteenth positions such as 1, 1.25, 1.5, and 1.75. Guitar playback speed controls are in the Playback menu; voice speech speed is separate. Optional compact string-fret pairs use forms such as 1-0 for string 1 open and 2-3 for string 2 at fret 3.

## Updates and testing

SpeakTab checks for newer stable releases at startup, and **Help > Check for updates** checks manually. Downloading and installation require your confirmation. The updater verifies the ZIP and executable and keeps a recovery copy. A real update from 10.14.1 to 10.14.2 succeeded on retry; the first failure remains undiagnosed.

The 10.14.9 build, release gate, and 19 focused probes passed. Package checks and hashes are recorded before publication. Standard controls are intended for screen readers such as JAWS and NVDA and for Braille displays. Physical JAWS, NVDA, Braille, microphone, Windows speech, and audio-device checks remain to be done. Music recognition can miss or misread notes, octaves, timing, and passages; compare readings with the original.

## Contributing and feedback

You can download the developer package and send proposed changes to Eden for review. Downloading it does not grant write access to this repository, and Eden approves changes entering the main version.

I welcome reports about accessibility, reading, playback, installation, and updates. [Open a GitHub issue](https://github.com/edenkizerccr-coder/speaktab/issues/new) or email edenkizer0718@gmail.com. Include your SpeakTab version, what you tried, what happened, and what you expected. Leave out passwords, API keys, and private music files.
