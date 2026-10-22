# SpeakTab

SpeakTab is a free Windows app for blind and low-vision musicians to read and practice guitar tablature, chord charts and supported scores. It preserves the original music and offers keyboard navigation, text for screen readers and Braille, spoken information and guitar playback.

## Download

Open the [latest release](https://github.com/edenkizerccr-coder/speaktab/releases/latest) and expand Assets.

- Musicians and testers: download SpeakTab-Windows.zip, extract the entire ZIP and run SpeakTab.exe. Keep the recognition runtime, licenses and guides with it.
- Developers: download SpeakTab-Source.zip for the complete source handoff, dependencies, fixtures, build instructions and manifest. GitHub automatic source archives do not contain that complete handoff.
- Separate guides, shortcuts, release notes, testing records and checksums are attached.

## SpeakTab 10.14.10: which mode speaks?

The user guide, Start Here and Help > Guided tutorials > Use the free reader microphone give step-by-step instructions.

- Free fixed commands: Voice > Exact microphone phrases, then Tab to Start listening and press Enter. Check Speak command replies with Windows voice to hear replies; uncheck it for text and your screen reader. Say one listed phrase at a time. Ctrl+Alt+L starts or stops this microphone. It uses the Windows default input and needs English speech recognition and microphone permission, with no AI account or key.
- Tutorial read-aloud: Read lesson aloud speaks the chosen lesson locally; Stop audio interrupts it. No microphone is opened.
- Regular guide answers: in Voice settings turn Live guitar teacher off, check Use Windows voice and turn Speak answers on. F5 asks, F7 replays, F8 starts spoken conversation and F9 stops. Offline answers describe the loaded reading; open-ended AI answers need a connected answer provider. Optional cloud speech uses a separate voice API key and API credit.
- Live AI teacher: Windows voice off, Live guitar teacher on, choose Lesson microphone and AI voice, and supply an OpenAI voice API key with credit. F8 starts; F9 ends the lesson and microphone. This uses a separate live model.

Test voice checks spoken output, not microphone recognition. Save voice setup remembers supported choices. JAWS or NVDA users can choose text-only replies to avoid overlapping voices. Guitar playback is separate instrument audio. The free-microphone lesson includes Windows input, permission and recognizer setup and failure recovery.

## Reading and practice

Ctrl+Alt+P opens the searchable command palette. Navigate has offline descriptions and string/section actions. Practice follows Playback; Alt+R opens it. Loop the current measure, a measure range or selected beats. Ctrl+P plays; Ctrl+Shift+P stops; Practice > Clear loop removes repeat. Thirteen offline tutorials can remain open while you switch to the reader with Alt+Tab.

Ctrl+3 explains the selected position. Inferred text-tab chords and estimated beats are labelled; missing music is not invented. Playback speed and voice speech speed are separate.

## Updates and testing

SpeakTab checks for newer stable releases at startup; Help > Check for updates checks manually. Downloading and installation require confirmation. The updater verifies packages and retains recovery. A real 10.14.1-to-10.14.2 update succeeded on retry; the first failure remains undiagnosed.

The 10.14.10 root build, release gate and nineteen focused probes passed. Both complete packages passed integrity, source/executable/document agreement, runtime, license and privacy checks. Physical JAWS, NVDA, Braille, microphone, speech, playback and live AI tests remain pending. Compare musical recognition with the original.

## Contributing and feedback

Developers may download the handoff and send proposed changes to Eden for review. Downloading grants no repository write access. Eden approves changes entering the main version.
