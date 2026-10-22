# SpeakTab

SpeakTab is a free Windows app for blind and low-vision musicians to read and practice guitar tablature, chord charts and supported scores. It preserves original music and offers keyboard navigation, text for screen readers and Braille, spoken information and guitar playback.

## Download and installation

**Current release: 10.14.16.** Open the [latest release](https://github.com/edenkizerccr-coder/speaktab/releases/latest) and expand Assets.

- Musicians and testers: download **SpeakTab-Windows.zip**, extract everything into a new folder, and run **SpeakTab.exe**. Keep the runtime, licenses and guides together, and retain your previous/recovery copy.
- Developers: download **SpeakTab-Source.zip** for the complete source handoff, dependencies, original fixtures, build instructions and manifest. GitHub's generated source archives do not contain that complete handoff.
- Separate guides, release notes, testing records and checksums are attached.

**10.14.11 and earlier need one manual installation of the complete current Windows ZIP.** Their updater safety lists can reject newer guide files. Versions 10.14.12 and later include the corrected list and an **Open official downloads** fallback. Replacing only the executable is not a complete update.

## New in 10.14.16

**Instrument-aware reading:** guitar strings, frets and tuning remain guitar information. Supported piano notation retains supplied staff/voice, clef and rest metadata, including in saved readings. Instrument identity follows the reading; two staves or a file extension alone do not make a score piano. Staff numbers alone do not establish hands.

**Quieter movement:** the part is identified in the opening heading, without repeating its name at every step. **Practice > Import summary and uncertainties** gives the instrument and exact part on demand. Eden's latest retest found no extra wording, and she approved this version for release.

Piano details can describe simultaneous written notes and earlier notes still held while another staff moves. Navigation follows the shared timeline: Left/Right moves through time; Up/Down inspects notes at the same time. Independent staff-following commands are not implemented. Playback remains sampled guitar sound.

The live teacher now receives complete selected-measure context and bounded pages for longer requests. Instructions require finishing a requested breakdown without repeated continue questions; live compliance still needs further testing.

## Retained practice and teacher features

**Optional gradual practice speed:** set a practice loop, then choose **Practice > Gradual practice speed**. Set starting and target percentages (25–200), increase size (1–50 percentage points), and complete loop repetitions per increase (1–100). Example: 60% to 100%, five points after every three loops. It is off by default and holds at the target. Stop resets the repetition counter and keeps current speed. Manual speed changes turn automatic increases off. Opening another reading or changing parts turns the plan off. Cancel preserves settings; plans are session-only. **Practice > Turn off gradual practice speed** stops increases while keeping the current speed.

The live teacher can explain setup, apply explicitly requested gradual-speed values, report or disable the plan, or guide manual increases when you say you are ready. She cannot assess readiness from speech recognition.

Teacher instructions cover **piano and guitar**, following your selected instrument and arrangement. Piano guidance covers notes, octaves, rhythm, chords, hand coordination, fingering and pedal suggestions, distinguished from supplied score markings. Playback remains the existing sampled guitar sound.

For unfamiliar techniques, including lap-style guitar and lap steel, the live teacher is instructed to research music-related sources before simply referring you elsewhere. Research uses the existing API connection and credits; failures and uncertainty must be disclosed. Live and regular answer instructions discourage repeated explanations and generic closing questions. Actual conversational behavior still needs testing.

**Escape from Ctrl+3 details** returns to the score without moving position. Full explanations starts with a short summary and adds a Details section where available; concise omits the longer section, so the first lines can match. The manual and tutorial explain this.

Includes the 10.14.13 tuning, accessible speed/bookmark status, loop review, tempo explanation, voice help and reviewed practice-note fixes. Imported tuning can still occasionally require confirming/reselecting the part before Ctrl+4; its intermittent focus cause is unresolved.

## Reading, practice and keyboard access

Open supported text tab, chord charts, Guitar Pro, MusicXML, MuseScore or PDF files; PDF recognition is experimental. Source information stays available. Navigate beats, measures, chord changes, sections and simultaneous supplied strings/notes. Save a complete text reading to reopen without the original, or export an HTML report with headings. Practice includes playback, speed controls, loops, count-in, bookmarks and personal notes.

- **Ctrl+1/2/3:** source, score, current explanation. **Ctrl+4:** tuning.
- With score focus: **Left/Right** moves note groups, **Up/Down** inspects simultaneous notes, **Ctrl+Left/Right** moves measures, **Alt+Left/Right** moves chord changes. **Ctrl+PageUp/PageDown** moves measures; **Ctrl+G** selects a measure number.
- **Ctrl+P:** play. **Ctrl+Shift+P:** stop. **Ctrl+Shift+PageDown/PageUp:** slower/faster by 10%. **Ctrl+Shift+5:** normal speed.
- **Ctrl+Shift+L:** loop current measure. **Ctrl+Shift+9:** loop range. **Ctrl+Shift+1/2:** selected-beat loop boundaries. **Ctrl+Shift+0:** clear loop. Use number-row keys.
- **Ctrl+B:** bookmark. **Ctrl+Shift+J:** return to latest bookmark. **Ctrl+Shift+Y:** practice note. **Alt+Shift+Q/F:** concise/compact reading.
- **Ctrl+Alt+P:** command palette. Search a menu action, current shortcut or contextual key. **Help > Guided tutorials** includes fourteen lessons and optional local read-aloud.

The 32 added shortcuts are editable defaults. Established basic keys stay assigned. **Help > Customize keyboard shortcuts** lets you find an action, choose a combination, Assign, and Save and close. Clear removes an optional assignment persistently; Restore optional defaults restores the defaults after saving. Cancel/Escape discards edits. Menus and the palette show current assignments. Test keys with your screen reader; JAWS, NVDA and Windows can intercept them.

## Voice and optional AI

Offline reading, menus, guides, tutorials, Windows speech and fixed microphone commands do not require paid AI. AI answers, cloud speech and live teaching use the existing provider/account and credit routes.

- **Free reader microphone:** **Voice > Exact microphone phrases**, then Start listening. **Ctrl+Alt+L** toggles it. It uses Windows default input, English speech recognition and microphone permission. Replies can be text or local Windows speech. Listed fixed commands are separate from open-ended AI questions.
- **Regular guide answers:** in Voice settings, turn Live guitar teacher off, check Use Windows voice and enable Speak answers. **F5** asks, **F7** replays, **F8** starts spoken conversation, **F9** stops it. Offline answers cover the reading; open-ended AI needs a connected provider. Optional cloud speech uses a separate voice API key and credits.
- **Live teacher:** Windows voice off, Live guitar teacher on; select Lesson microphone and AI voice, with an OpenAI voice API key and credit. **F8** starts and **F9** ends the lesson. It uses a separate live model.

The live teacher can consult complete shipped guides, fourteen tutorials, current menu routes and assigned keys. Requested supported navigation, playback, looping, bookmarking, practice notes and gradual-speed actions keep the existing conversation active. How-to questions request guidance, not automatic action. File/part/save/account/update tasks use normal controls. Practice notes open for your Save/Cancel review and preserve existing notes.

Test voice checks spoken output, not microphone recognition. Save voice setup retains supported choices. Guitar audio and JAWS speech are separate. Text-only app replies can avoid overlapping voices.

## Testing, updates and limitations

The root release gate and **25 focused probes passed**, including full-measure pagination, instrument/staff provenance, quieter navigation, gradual-speed bounds, completed-loop counting, target caps, Cancel, manual override, stop/reset, reading changes, AI actions and Escape focus. Both complete packages passed source/executable/document, manifest, runtime/license and privacy checks. The production updater extracted the actual complete tester ZIP and its executable hash matched.

Eden reports that her recent imported music has worked, a piano score was correctly identified, and the latest navigation wording is working without extra speech. Earlier confirmed JAWS navigation, speed announcements, loops, bookmarks, save/reopen, voice-help clarity and practice-note Save/Cancel results are retained. These are results for tested files and workflows, not exhaustive format coverage. Search needs broader testing across songs/providers. NVDA has not yet been tested; NVDA testers are welcome. Additional Braille/hardware setups, perceived audio/microphone behavior and live AI musical/instruction compliance need continued targeted testing. PDF/OCR remains experimental. Compare readings and suggestions with their source. Regular API voice reliability and the intermittent tuning focus issue remain limitations.

SpeakTab checks for newer stable releases at startup; **Help > Check for updates** checks manually. Downloading and installation require confirmation. The updater verifies packages and retains recovery. A real 10.14.1-to-10.14.2 update succeeded on retry; its first failure remains undiagnosed. Google Drive full release ZIP replacement remains manual.

## Contributing and feedback

Developers may download the handoff and send proposed changes to Eden for review. Downloading grants no repository write access. Eden approves changes entering the main version.

**Help > Prepare feature test report** starts with Not tested results. Copy or save the reviewed report, or prepare an email draft to edenkizer0718@gmail.com and review/send it yourself. Nothing is sent automatically. GitHub is optional.
