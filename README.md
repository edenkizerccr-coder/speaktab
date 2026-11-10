# SpeakTab

Read, hear, practise and compose music.

## Choose your download

GitHub calls this set of downloads `v10.14.118`. The headings below show the version you install on each device.

### Windows 1.0.30

- [Download SpeakTab 1.0.30 for Windows (ZIP)](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.118/SpeakTab-Windows.zip)
- [Windows user manual (Word)](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.118/SpeakTab.User.Manual.docx)
- [Windows user manual (RTF)](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.118/SpeakTab.User.Manual.rtf)
- [Composition lessons (Word)](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.118/SpeakTab.Composition.Lessons.docx)

### Android 0.6.1 for Android 15 or later

- [Download the standard Android 0.6.1 installer (APK)](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.118/SpeakTab-Android-0.6.1.apk)
- [Standard Android user guide (Word)](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.118/SpeakTab.Android.User.Guide.0.6.1.docx)
- [Standard Android user guide (RTF)](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.118/SpeakTab.Android.User.Guide.0.6.1.rtf)
- [Standard Android keyboard reference (Word)](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.118/SpeakTab.Android.Keystrokes.0.6.1.docx)

Choose this version for a BrailleSense 7 running Android 15.

### Android 0.6.1-beta1 for Android 12 or later

- [Download the Android 12 compatibility beta (APK)](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.118/SpeakTab-Android-0.6.1-beta1.apk)
- [Compatibility beta user guide (Word)](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.118/SpeakTab.Android.User.Guide.0.6.1-beta1.docx)
- [Compatibility beta user guide (RTF)](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.118/SpeakTab.Android.User.Guide.0.6.1-beta1.rtf)
- [Compatibility beta keyboard reference (Word)](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.118/SpeakTab.Android.Keystrokes.0.6.1-beta1.docx)

### Source files

- [Complete Windows source (ZIP)](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.118/SpeakTab-Source.zip)

[SpeakTab website](https://speaktab.pages.dev/)

## What's new

- Windows and Android accept full-word descriptions, named note-entry controls and optional quick entry. Try `quick m1 b1 C4q E4e re G4h` for a passage with mixed note lengths and a rest.
- Windows keeps sequential entry feedback brief. The Reader can review a pitch, fret, rest or tie correction and save a separate uncompressed partwise MusicXML copy.
- Android can import practice from a freshly saved Windows text reading into the matching playable MusicXML or Guitar Pro score. Open the original and the same part first. In Reading, use F3 and Enter on **Practice tools**, then **Import Windows practice into this score**. Choose the saved text and review the match before applying. Matching notes, bookmarks and the saved place appear in the playable reading. A matching loop appears under **Saved practice passages**.

## Testing for this release

- Software checks passed in Windows and both Android editions. MusicXML and Guitar Pro transfer checks used actual Windows saved readings and confirmed that playback was retained after reopening on Android.
- Hands-on checks for this build with JAWS and a BrailleSense are pending.

## Reading and practice

Supported score formats include MusicXML, MuseScore, Guitar Pro and textual music. PDF recognition and repair remain experimental and require musical review. Navigate supplied beats, measures, parts, lyrics, chords and markings; use supported practice playback, loops and saved reminders. Vocal parts present note names and octaves without guitar fingering labels. Missing lyric text is not invented. Existing Windows shortcuts and Android Control commands are preserved.

## Composition

Precise selectors and documented local phrases work without an AI account or interpretation charge. Enter notes, simultaneous chords, independent staff/voice rhythms, rests, lyrics, directions and all standard point dynamics. Numeric lengths such as 1.5 beats work for piano and guitar. The local catalog includes 23 guitar shapes and 14 explicit-root piano chord qualities. Enter natural/artificial harmonics with explicit base and touching fret, or adjacent hammer-on, pull-off and slide notes. Review before Apply. Save an editable project and export applied MusicXML. Projects are separate from arbitrary imported scores.

Windows supports Piano, Guitar, Bass, Ukulele, Voice, Violin, Viola, Cello, Harp, Percussion and Timpani. Android also supports those composing instrument types, including named percussion and pitched timpani. Both apps offer supported passage expressions; Android adds reviewed measure tools, slight/wide vibrato playback and real Guitar Pro companion export with a MusicXML master. Read the current manuals for exact forms and limits.

Optional ChatGPT interpretation requires a deliberately selected connection/model. Windows F4 loads/connects models, F5 focuses a pending composer answer and F6 reads its reply. Android uses named controls through F3 and Enter. Questions, replies and unfinished answers are retained; model proposals still need review and Apply. Local entry errors do not trigger automatic online interpretation. Provider features may have separate charges.

## Building and verification

Use the included Build instructions and checks. Public packages preserve runtime and licence material. Do not include personal scores, settings, tokens, signing keys or private diagnostics. Software checks do not replace hands-on device, screen-reader and physical-audio assessment. See Release Notes and the package manifests for the current build and checks.
