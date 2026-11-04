# SpeakTab

**SpeakTab 1.0.7 for Windows — accessible scores for reading, practice and natural-language composition.**

SpeakTab is a Windows music reader and composer built with accessibility from the ground up. Read, practise and write supported instrumental and vocal music, including standard notation and tablature. MusicXML, MuseScore, Guitar Pro, text tablature and chord charts come into a consistent textual reading experience; PDF scores and scans have experimental recognition and assisted recovery. Musical information is arranged as positions you can navigate with a keyboard, screen reader or refreshable Braille display. You can open an existing score directly in the reader without first entering a composition screen. Braille access uses ordinary musical descriptions; SpeakTab does not produce formal Braille music notation.

The developer reads Braille fluently, but Braille music has always been a struggle. Wonderful applications already help musicians read and write Braille music. SpeakTab grew from a personal wish for an easy-to-read way to explore scores of different types without going through a composition screen or a complicated interface. Its ordinary textual descriptions offer another way to read and practise music, including for people who do not read Braille music code.

Windows includes a dedicated four-string Bass instrument, Bass and piano and Voice and bass templates, sounding-pitch or string/fret entry, four-line TAB export and a complete bass lesson. Five- and six-string bass, automatic bass-line generation and dedicated slap/pop authoring are not available.

In Full Explanation (F3), SpeakTab can suggest a likely English word from separate Guitar Pro syllables. Ctrl+2 keeps the supplied syllables on their beats. Ordinary reading skips repeated dynamic announcements and quiet tied continuations.

## Natural-language composition

Some musicians find the note-entry syntax in music software difficult to learn or remember. SpeakTab offers supported natural-language composition: describe notes, chords, rests, lengths and lyrics in musical words, review a proposed result, then accept it. Direct supported phrases work locally; optional connected ChatGPT interpretation can handle broader descriptions and still requires review. Precise named selectors remain available. The composer creates supported parts for piano, guitar, four-string bass, ukulele, solo voice, violin, viola, cello, harp, unpitched percussion and timpani, including SATB, barbershop and string-quartet templates. Save a working project including unfinished entry and export MusicXML. It edits SpeakTab projects rather than arbitrary downloaded scores. Begin with Before the composing lessons and tasks 15 through 22; tasks 31 through 34, 36, 37 and 38 cover further instruments and lyrics.

The Windows composer also supports guitar bends and releases, slides, trills, vibrato, and tempo ramps. Guitar playback follows supported instrument programs and pitch changes.

## Take your readings with you

Save text and Markdown readings to take with you for on-the-go reading on a compatible device or reader. Both manuals now give step-by-step instructions for transferring readings between SpeakTab for Windows and SpeakTab for Android. The libraries do not synchronize automatically. Windows saved-reading text opens in Android for reading; import the original supported score for playback. Android readable exports preserve the text and optionally comments, but do not restore a complete Windows arrangement or map comments to its positions. You can also export HTML or textual BRF, or exchange matching practice comments through Markdown. Keep a portable reading alongside your practice materials so you can revisit the music away from your Windows computer.

## Working alongside other music tools

MuseScore, GOODFEEL and specialist Braille-music applications offer valuable ways to read and write music. MuseScore also opens multiple file formats and has accessibility tools. SpeakTab was built with accessibility from the ground up around navigable musical descriptions, keyboard access, screen-reader text and textual Braille. Its purpose is to bring supported score formats into a consistent reading and practice experience, with a separate natural-language composing route when you want to write music. The comparison below explains overlaps and different approaches so you can choose tools that suit your music and access needs.

MuseScore documents its own [accessibility tools](https://musescore.org/en/accessibility) and [file-format support](https://musescore.org/en/handbook/4/file-formats). Multiple-format import is a SpeakTab capability shared with other music applications; the distinction is SpeakTab's integrated textual reading and practice approach.

The corrected Windows manual teaches opening and reading guitar files before advanced composition, retains F3 for the full explanation, and places expression instructions in the composer reference. The complete Windows package includes the same corrected manual. The Windows executable and every Windows command are unchanged.

## Windows downloads

- [Complete Windows app](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab-Windows.zip)
- [Word user manual](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.User.Manual.Readings.docx)
- [Word Quick Start](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.Quick.Start.docx)
- [Complete source](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab-Source.zip)

Extract the complete Windows ZIP and run SpeakTab.exe. Keep the included runtime, instrument sounds, licences and guides together. Windows and .NET Framework 4.8 are required. Existing installations can check for updates. Save your work before updating and keep your previous copy. Internal build 10.14.95 preserves compatibility with earlier Windows updaters; the app displays SpeakTab 1.0.7.

## Scope and available tools

The reader handles supported standard notation, tablature, chord charts and instrumental or vocal parts. Exact available detail depends on the source. Guitar Pro import supports six-string guitar parts. MusicXML and MuseScore support broader supplied parts, including piano, voice and strings. You can move by musical position and measure, inspect full details, hear local practice previews, change speed, loop passages and keep notes and bookmarks.

Local reading, playback, practice, direct supported composition and Windows Voice control do not require an AI account. Optional written questions, broader composition interpretation, connected score recovery and the conversational teacher use their own connections and may have provider charges. PDF recognition and AI recovery are experimental and require review. Braille output is ordinary musical descriptions in Braille, not formal Braille music notation. The separate Android app has fewer features and cannot open PDFs directly.

## Original practice examples

Sixteen original examples include piano, guitar, solo voice, voice with piano, violin, harp, SATB, barbershop, ukulele, violin with harp, viola, cello, string quartet, drum kit and timpani. Open MusicXML to read and hear the music; open the matching .speaktabscore project to change it in the composer. Matching PDFs are references or optional recognition experiments. The sample-only CC0 licence permits using, copying and changing these exercises.

## Release history

This 1.0.7 release continues the existing Windows application. Earlier releases, including 10.14.87, remain available with their original assets. The app offers 38 guided tasks and 176 steps, including a complete four-string bass exercise. Software checks do not certify every score's musical accuracy or every screen reader and audio device.

## Further development

The developer is open to further development and welcomes collaboration. Help from a developer with iOS experience would be especially welcome to explore bringing SpeakTab to iPhone and iPad. An iOS version is not currently available. The complete Windows source and build instructions are available from the existing GitHub releases. Developers can use the repository issues to discuss ideas and collaboration.

## SpeakTab for Android 0.4.6

Requires Android 15 or later. Version 0.4.6 adds clearer supplied guitar techniques and changed dynamics, Full explanation of this beat, supplied lyrics, cautious English lyric-word suggestions, and navigation by supplied chord changes or markings. Existing one-step shortcuts retain their assignments. Only missing Android reading actions also use Control+Z followed by another Control chord; named controls provide the same actions. Windows commands remain unchanged.

Seven optional Learn by doing lessons teach reading, listening, loops, practice notes, first-note entry, piano chords and violin phrases beside the real controls. Each uses its own original practice work and saves progress. Simpler Reading groups and basic note entry keep the first actions easy to find. Written bow direction, finger/string marks, lever-harp directions and optional seven-pedal harp diagrams are now available; these markings do not simulate technique or retune the entered pitches.

SpeakTab for Android provides accessible reading by measure and beat, instrument-sample playback, practice loops, notes, bookmarks and named passages. Compose supported pitched music with fields or musical phrases, review changes and export MusicXML. Control shortcuts and local spoken commands provide direct routes to common tasks. Control+K opens help for the screen you are using, with one shortcut and action per line. While reading, Control+N writes or edits a practice note. In Composer, Control+E enters musical notes, chords or rests. Control+Shift+B goes to the beginning of the music; Control+Shift+E goes to the end. No Alt shortcuts are assigned.

- [Android APK](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.95/SpeakTab-Android-0.4.6.apk)
- [Android User Guide in Word](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.95/SpeakTab.Android.User.Guide.0.4.6.docx)
- [Android User Guide in RTF](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.95/SpeakTab.Android.User.Guide.0.4.6.rtf)
- [Android keystrokes in Word](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.95/SpeakTab.Android.Keystrokes.0.4.6.docx)
- [Android source](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.95/SpeakTab-Android-Source-0.4.6.zip)
- [Android keystrokes in RTF](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.95/SpeakTab.Android.Keystrokes.0.4.6.rtf)

Install over the existing SpeakTab Practice app as an update. Earlier reading, navigation and completed typed answers have been used on BrailleSense 7. The new composer, looper, samples, keys and voice features still need hands-on checking; BrailleSense 6 and phones have not been tested. The Android composer uses a separate project format and has fewer features than the Windows composer. MusicXML exchanges applied music.

Optional written questions, connected composition interpretation and AI Teacher have their own connections. They are additional features; the app opens with its music tools.

The Android guide teaches Android independently, with all local voice-command phrases, supported composer phrases, instrument examples and limits. The Android Word and RTF guides each have 48 pages, and the Android shortcut references each have three pages. Both guides introduce the controls and complete tasks before relying on them. Broader connected AI interpretation has no finite list of accepted English sentences.


## Optional Android 12 or later beta

SpeakTab 0.4.6 beta 1 permits Android 12 and later, including Android 15. **This is an untested beta: it has not been tested on a physical Android 12 device or BrailleSense 6 because the developer has no device running an older Android version.** Device compatibility, Braille and keyboard access, audio and microphone operation remain unverified. The current 0.4.6 Android 15 release above remains available separately.

The same app features are retained; this is one APK for Android 12 and later, rather than a reduced-feature edition. The compatibility changes use the interfaces available on each Android version. The existing software checks and 48 added guitar-reading and shortcut checks pass, which does not establish physical device compatibility or guarantee no regressions.

- [Android 12 or later beta APK](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.95/SpeakTab-Android-0.4.6-beta1.apk)
- [Beta guide in Word](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.95/SpeakTab.Android.User.Guide.0.4.6-beta1.docx)
- [Beta guide in RTF](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.95/SpeakTab.Android.User.Guide.0.4.6-beta1.rtf)
- [Beta shortcut reference in Word](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.95/SpeakTab.Android.Keystrokes.0.4.6-beta1.docx)
- [Beta source](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.95/SpeakTab-Android-Source-0.4.6-beta1.zip)
- [Beta shortcut reference in RTF](https://github.com/edenkizerccr-coder/speaktab/releases/download/v10.14.95/SpeakTab.Android.Keystrokes.0.4.6-beta1.rtf)

Keep exported backups before testing. Install as Update without uninstalling. The higher beta version code means returning to 0.4.6 is not an ordinary Android update; uninstalling to force a rollback removes local app data.
