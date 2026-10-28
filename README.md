# SpeakTab

SpeakTab 10.14.78 is an accessible Windows tab and score reader with a separate score composer. Use a keyboard, screen reader or Braille display to read supported music, inspect notes and lyrics, hear local practice previews, loop passages and keep practice notes. The composer writes piano, guitar, ukulele, solo voice, violin, viola, cello, harp, drum-kit/unpitched percussion and timpani, including supported ensembles.

## Downloads

- [Complete Windows application](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab-Windows.zip)
- [Latest release and all downloads](https://github.com/edenkizerccr-coder/speaktab/releases/latest)
- [Free sample bundle](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab-Samples.zip)
- [Browse the actual Samples folder](https://github.com/edenkizerccr-coder/speaktab/tree/main/Samples)
- [Full User Manual in Word](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.User.Manual.docx)
- [Full User Manual in HTML](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.User.Manual.html)
- [Quick Start](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.Quick.Start.docx)
- [Complete source handoff](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab-Source.zip)

Extract the complete Windows ZIP and run SpeakTab.exe. Keep its recognition runtime, instrument assets, fixtures, licences, Samples and guides together. Windows with .NET Framework 4.8 is required. The complete source is in SpeakTab-Source.zip; GitHub-generated source archives contain this repository snapshot.

## Read an example or edit your own copy

The 16 short original exercises each have three matching files. **Read the .musicxml file as supplied** in the reader with Ctrl+O, or Ctrl+Shift+F then Try included practice samples. No editing or Apply step is required. Ctrl+T chooses a supplied part; Ctrl+2 focuses the music; F3 opens full details.

**To change the example**, open the composer with Ctrl+Shift+N, choose Open project and its matching .speaktabscore file. Use Save project as to keep a personal copy. You can change notes, lyrics, instruments and measures, review a proposal, then Apply reviewed changes. Save project keeps the working composition; Export MusicXML makes a separate applied score for reading or sharing.

The matching PDF is a printed reference or an optional recognition experiment. Prefer MusicXML to read the supplied notes and rhythm directly. The examples include piano, guitar, solo voice, voice with piano, violin, harp, SATB, barbershop, high-G and low-G ukulele, violin with harp, viola, cello, string quartet, drum kit and timpani. The sample-only CC0 licence permits using, copying and changing these original exercises.

Open project edits SpeakTab compositions. Downloaded MusicXML, MuseScore and PDF scores open in the reader; they do not become arbitrary editable composer projects. A MusicXML export made by SpeakTab can also reopen for composing when its embedded project still matches its music. The separate project is the clearest working copy.

## Instruments in the reader and composer

This comparison refers mainly to supplied MusicXML and MuseScore data. PDF recognition may still be needed for any instrument. Search results alone do not establish support or musical accuracy.

| Instrument | Reader | Composer |
|---|---|---|
| Piano | Supplied pitches, rhythm and upper/lower staves | Two staves, notes, chords and supported expressions |
| Guitar | Six-string Guitar Pro; supplied fretted structured parts; text TAB/charts with stated limits | Six-string staff or TAB, explicit tuning/capo/frets, chords and picking/strum patterns |
| Ukulele | Declared four-string structured parts; supplied tuning and frets | High-G, low-G or custom four-string tuning; staff or TAB and supported patterns |
| Violin | Structured staff notes and retained supported details | Own sound, bow direction and supplied finger/string markings |
| Viola | Structured staff notes; real cases checked in the earlier reader audit | Alto clef, own sound and supported bow/finger/string markings |
| Cello | Structured staff notes; an actual OpenScore Arriaga cello part and original samples checked | Bass or optional part-wide tenor clef, own sound and supported bow/finger/string markings |
| Harp | Supplied notes and both staves | Two staves, own sound and written seven-pedal diagrams |
| Solo voice or voice with accompaniment | Supplied vocal notes and lyric verses | One unaccompanied singer or supported accompaniments; words and syllables beside notes |
| SATB or barbershop | Separately supplied vocal parts and words | Separately named singers with independent notes and lyrics |
| String quartet | Supplied violin, viola and cello parts | Two violins, viola and cello |
| Drum kit / unpitched percussion | Supplied named sounds and timing | Named General MIDI sounds, rests, simultaneous hits and written rhythms |
| Timpani | Supplied pitched percussion notes and timing | Ordinary sounding pitches, bass clef and own practice sound |

Other structured instrument parts may open when the format supplies pitches and rhythm; they do not all have the same verification or a dedicated composer type. The full instrument guide is in the manual and Source guide in score lookup. Cello checks are specific examples, rather than a new broad cello corpus audit.

## Find classical and instrument scores

Ctrl+Shift+F opens Find classical and instrument scores. F2 has the same route. Enter a composer or artist, piece title or catalogue number, and optional instrument keywords.

- **MuseScore:** broad instrumentation and community arrangements, searched on its website. Use your own account there if needed; an account does not make every score exportable.
- **OpenScore songs:** actual catalogue results with MusicXML/MuseScore downloads; varied vocal scorings, often with piano.
- **OpenScore string quartets:** violin, viola and cello scores, with structured files and full or named PDF parts where supplied.
- **IMSLP:** historical editions, instrumental parts and instrumentation browsing, mainly PDFs.
- **Mutopia:** newly typeset classical PDFs; its LilyPond source is not MusicXML.
- **MusicXML example library:** small structured examples with PDFs or images; many are excerpts.
- **CPDL ChoralWiki:** choral/vocal repertoire and voicing categories, including SATB; mainly a website/PDF route.

Source guide explains what each collection is useful for, returning permitted downloads to SpeakTab, and file/recognition limits. OpenScore catalogue downloads were checked with actual files. Automated MuseScore browsing met its security verification page; account downloads were not tested. Website access occurs in your normal browser, without supplying a site password to SpeakTab.

## Reading and guidance changes in 78

Ordinary score reading and text/Markdown/HTML/BRF prose omit repeated staff numbers and known tied continuations. The starting attack gives its tie and combined length. New attacks, written rests, vertical simultaneous-note organization and source music remain. Choose a piano staff for the dedicated staff commands; ordinary arrows and exports still cover the selected part. F3 and deliberate staff queries retain full context.

All 37 tutorials and the full public manual explain actions, expected results and correction. Using tutorials provides separate window help. The public Word guides are User Manual (159 pages), Quick Start and Testing Steps.

## Read and practise

Ctrl+O opens music; Ctrl+T chooses a supplied part. Ctrl+2 focuses musical positions. Left/Right follows musical time; Up/Down inspects simultaneous notes, strings or lyrics. F3 opens full details. Ctrl+Shift+I reports supplied score information. Ctrl+P plays and Ctrl+Shift+P stops. Practice offers loops, bookmarks and comments. Ctrl+S saves a reader arrangement; My readings resumes it.

Alt+Right Arrow moves to the next chord change; Alt+Left Arrow moves to the previous change. They work directly in the main reader without opening a menu and skip held continuations. Alt+Shift+L gives only the full supplied lyrics at the selected position in Reader status; Ctrl+2 returns to the music. Up/Down also reaches supplied lyric rows.

## Write music

Ctrl+Shift+N opens the composer. New score offers the instrument, solo voice and ensemble templates. Solo voice means one singer with no accompaniment. Add part builds other supported combinations. SATB names Soprano, Alto, Tenor and Bass; barbershop names Tenor, Lead, Baritone and Bass. Each singer has independent notes and words. The composer does not harmonize a melody automatically or condense four singers onto two staves.

Ctrl+E opens note selection. Choose the part, named staff, position, note or percussion sound and duration. Enter records a note, chord, hit group or rest and advances by duration when Advance is checked, crossing into the next measure automatically. Tab moves among controls. A position message reports where the next event begins. Add this pitch to chord or Add this percussion sound gathers simultaneous sounds before Enter records the group.

Type an optional lyric beside its new note. Verse 1 is ordinary entry; later verses add lyric lines. Syllable choices and extenders are retained. Ctrl+L edits words on a selected applied note. Copy lyrics to aligned voices is an explicit reviewed action, protects existing words by default and skips different timing. Local vocal playback remains wordless.

Piano and harp have named upper/lower staves. Other parts use one staff. Rhythm line 1 is normal entry; another line is needed only for overlapping rhythms on the same staff. Additional options are hidden until requested, and tuplets are off for ordinary notes. Chord symbol is a written label; choose played tones separately. Supported full phrases and m/b/duration shorthand remain available.

Review several measures together, inspect or hear the proposal, then Apply. Edit selected event replaces music; Undo/Redo restores applied states. Save project keeps applied music and unfinished descriptions, raw lyrics, selected notes or hits, choices, positions and pending review. Open project restores them. Export MusicXML writes applied music and asks before omitting unfinished work.

Violin, viola and cello markings are written choices; they do not calculate positions or synthesize arco, pizzicato or other named techniques. Harp diagrams do not retune notes or certify playability. Drum rolls, flams, rudiments, specialized sticking and timpani pedal changes are not automatically expanded or synthesized. Engraving, arbitrary imported-score editing, editable grace notes and advanced guitar authoring remain unsupported. Written repeats export while composer playback runs through the written measures once.

## Learn the controls

The full manual and 37 guided tasks with 171 steps explain the actual controls, choices, expected results and ways to correct a result. They assume ordinary computer skills and basic musical knowledge, without prior notation-software experience. Examples are optional suggestions.

Next step advances within a task; Next lesson changes subjects. Show whole lesson displays its complete reference. Optional Read displayed text uses local Windows voice. F1 explains relevant controls. The composer’s How to compose opens its full reference. The existing musical reader layout is preserved.

The full reference includes all supported composer phrases and shorthand, the meaning of two beats in different meters, 98 fixed reader voice commands, 44 alternatives and 13 numbered patterns with results. Composer dictation, free reader commands and connected teacher conversation are separate routes.

## Optional connections and accuracy

F4 connects written ChatGPT, F5 focuses its question, Enter sends and F6 reads the answer. Ctrl+Alt+L controls the separate free reader-command microphone. F8 starts the configured connected teacher and F9 stops it. F12 silences app speech without changing microphone state. Connected services may incur charges. Current-file/another-file AI remediation can start automatically with a saved connection; the separate ChatGPT-window handoff requires your paste, attachment and send in the browser.

PDF recognition and AI recovery can omit or misread music. Read coverage, compare the original and retain warnings with provisional output. Importable does not mean complete or correct. Playback effects are practice approximations, and vocal previews are wordless. Physical screen-reader, Braille, microphone, audio and live-model quality need hands-on review. Public packages exclude private music, readings, settings, profiles, credentials and diagnostic dumps. Previous public releases remain available.
