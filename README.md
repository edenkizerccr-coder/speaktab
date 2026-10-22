# SpeakTab

SpeakTab is a free Windows app for blind and low-vision musicians to read and practice guitar tablature, chord charts and supported scores. It preserves the original music and offers keyboard navigation, text for screen readers and Braille, spoken information and guitar playback.

## Download

**Update notice for 10.14.12:** install this update manually once. An older updater’s safety list may reject the guide files in the complete package. When 10.14.12 is released, download **SpeakTab-Windows.zip**, extract **everything into a new folder**, and run **SpeakTab.exe** there. Keep your previous/recovery copy; replacing only the executable is not a complete update. Version 10.14.12 fixes the guide-file list for future updates and provides an **Open official downloads** fallback with manual steps if an update fails. The public release is still 10.14.11 while this new build is tested.

Open the [latest release](https://github.com/edenkizerccr-coder/speaktab/releases/latest) and expand Assets.

- Musicians and testers: download SpeakTab-Windows.zip, extract the entire ZIP and run SpeakTab.exe. Keep the recognition runtime, licenses and guides with it.
- Developers: download SpeakTab-Source.zip for the complete source handoff, dependencies, fixtures, build instructions and manifest. GitHub automatic source archives do not contain that complete handoff.
- Separate guides, shortcuts, release notes, testing records and checksums are attached.

## Local 10.14.12 test build: app-aware voice guidance

The public release is currently **10.14.11**. Version **10.14.12** is a local test build awaiting hands-on testing and Eden’s publication approval.

The optional live AI teacher can consult the complete shipped user guide, shortcut sheet, release notes, audit, hands-on checklist, package verification and feature walkthrough, plus all fourteen tutorials. It reads current menu routes and actual assigned keys, including changed or cleared shortcuts. Ask for one app step at a time. Regular typed/spoken answers also receive app knowledge; automatic reader actions are available in live teacher mode.

During the same live conversation, request movement through beats, measures, chords, sections or strings; explanations; practice speed; playback; loops; or bookmarks. The reader uses its existing handlers while retaining the conversation and microphone. Questions such as “How do I loop?” request guidance rather than silently changing the reading. Unsupported file, part, save, settings, account and update steps use the normal controls.

**Offline use stays free:** keyboard access, menus, guides, fourteen tutorials, Windows speech and fixed microphone commands do not require paid AI. The conversational AI and optional cloud voice use the existing account/API credit routes.

**Help > Feature walkthrough** provides an optional testing sequence. **Help > Prepare feature test report** starts with Not tested results. Copy or save a reviewed report, or choose **Email bug or test results to Eden…** to copy it and open an email draft to edenkizer0718@gmail.com. Paste, review and press Send yourself. Nothing is sent automatically; GitHub is optional.

**First installation of 10.14.12 must be manual:** older updaters omit shipped guide filenames from their allowlist. Download and extract the complete new Windows ZIP when it is released. Version 10.14.12 fixes the strict document allowlist for future updates. Keep previous/recovery copies.

The root build and 21 focused probes passed. Actual JAWS/NVDA/Braille, microphone, perceived audio, live AI and musical accuracy remain hands-on checks.

## SpeakTab 10.14.11: direct keyboard access

32 direct shortcuts make frequent actions available without opening menus or searching the palette. Existing score keys remain: Left/Right for notes, Ctrl+Left/Right for measures and Alt+Left/Right for chords, with score focus. Ctrl+2 returns to the score.

- Alt+Shift+Left/Right: previous/next labelled section. Alt+Shift+Up/Down: previous/next string at this beat.
- Alt+Shift+P: position. Alt+Shift+S: beat strings. Alt+Shift+M: measure strings. Alt+Shift+C: chord. Alt+Shift+L: printed lyrics. Alt+Shift+E: beat explanation.
- Ctrl+Shift+N: next played note. Ctrl+Shift+L: loop current measure. Ctrl+Shift+1/2: set inclusive loop start/end. Ctrl+Shift+9: measure-range loop. Ctrl+Shift+0: clear loop. Use number-row keys. Ctrl+P plays; Ctrl+Shift+P stops.
- Ctrl+B: bookmark. Ctrl+Shift+J: return to latest bookmark. Ctrl+Shift+Y: position note. Alt+Shift+Q/F: concise/compact reading.
- Ctrl+Shift+H: tutorials. Ctrl+Shift+U: user guide. Ctrl+Shift+X: exact microphone phrases. Alt+Shift+O: open saved reading.

New keys work in the main reader controls; separate dialogs keep their own keys. Description commands focus readable status text; Ctrl+2 returns to the score. The guide starts with the complete daily-use list. Real JAWS/NVDA/Braille shortcut interception still needs hands-on testing.

## Change or clear a shortcut

The 32 added reader keys are editable defaults. Established basic shortcuts stay assigned. Open **Help > Customize keyboard shortcuts**, find an action, select it, Tab to **New shortcut**, press your chosen combination, choose **Assign**, then **Save and close**. **Clear selected shortcut** removes an optional key and keeps it cleared after restarting. **Restore optional defaults** restores the 32 added defaults after saving. **Cancel** or Escape discards unsaved edits.

Other actions can receive a key when they have none. SpeakTab refuses duplicate app assignments, protected basic/editing keys and Insert/Caps Lock modifier keys. It cannot detect JAWS, NVDA or Windows custom assignments. Test a chosen key with your screen reader and change it if necessary. Settings stay local to your Windows user. Menus and the command palette show current assignments.

The new fourteenth lesson, **Help > Guided tutorials > Assign your own keyboard shortcuts**, walks through choosing, assigning, saving, testing, clearing and restoring defaults. Saved key swaps and explicitly cleared defaults are covered by the automated checks. Real JAWS/NVDA/Braille compatibility remains untested.

## Which mode speaks?

The user guide, Start Here and Help > Guided tutorials > Use the free reader microphone give step-by-step instructions.

- Free fixed commands: Voice > Exact microphone phrases, then Tab to Start listening and press Enter. Check Speak command replies with Windows voice to hear replies; uncheck it for text and your screen reader. Say one listed phrase at a time. Ctrl+Alt+L starts or stops this microphone. It uses the Windows default input and needs English speech recognition and microphone permission, with no AI account or key.
- Tutorial read-aloud: Read lesson aloud speaks the chosen lesson locally; Stop audio interrupts it. No microphone is opened.
- Regular guide answers: in Voice settings turn Live guitar teacher off, check Use Windows voice and turn Speak answers on. F5 asks, F7 replays, F8 starts spoken conversation and F9 stops. Offline answers describe the loaded reading; open-ended AI answers need a connected answer provider. Optional cloud speech uses a separate voice API key and API credit.
- Live AI teacher: Windows voice off, Live guitar teacher on, choose Lesson microphone and AI voice, and supply an OpenAI voice API key with credit. F8 starts; F9 ends the lesson and microphone. This uses a separate live model.

Test voice checks spoken output, not microphone recognition. Save voice setup remembers supported choices. JAWS or NVDA users can choose text-only replies to avoid overlapping voices. Guitar playback is separate instrument audio. The free-microphone lesson includes Windows input, permission and recognizer setup and failure recovery.

## Reading and practice

Ctrl+Alt+P opens the searchable command palette. Navigate has offline descriptions and string/section actions. Practice follows Playback; Alt+R opens it. Loop the current measure, a measure range or selected beats. Ctrl+P plays; Ctrl+Shift+P stops; Practice > Clear loop removes repeat. Fourteen offline tutorials can remain open while you switch to the reader with Alt+Tab.

Ctrl+3 explains the selected position. Inferred text-tab chords and estimated beats are labelled; missing music is not invented. Playback speed and voice speech speed are separate.

## Updates and testing

SpeakTab checks for newer stable releases at startup; Help > Check for updates checks manually. Downloading and installation require confirmation. The updater verifies packages and retains recovery. A real 10.14.1-to-10.14.2 update succeeded on retry; the first failure remains undiagnosed.

The 10.14.11 root build, release gate and twenty focused probes passed. Both complete packages passed integrity, source/executable/document agreement, runtime, license and privacy checks. Physical JAWS, NVDA, Braille, microphone, speech, playback and live AI tests remain pending. Compare musical recognition with the original.

## Contributing and feedback

Developers may download the handoff and send proposed changes to Eden for review. Downloading grants no repository write access. Eden approves changes entering the main version.
