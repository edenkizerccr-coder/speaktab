# SpeakTab

SpeakTab is a Windows music reader and practice companion for keyboard, screen-reader and Braille users. Read supported scores, choose a musical part, hear local practice previews, slow down, loop passages and keep practice notes. Optional connected AI is separate from local reading.

## Download version 10.14.54

- [Complete Windows application](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab-Windows.zip)
- [54 changes and current controls](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.54.Changes.and.Current.Controls.txt)
- [Word user manual, version 53 reference](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.User.Manual.docx)
- [Quick Start, version 53 reference](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.Quick.Start.docx)
- [Complete source handoff](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab-Source.zip)
- [Release notes and all downloads](https://github.com/edenkizerccr-coder/speaktab/releases/tag/v10.14.54)

Extract the complete app ZIP into its own folder and run SpeakTab.exe. Keep its runtime, fixtures, licences and guides together. Windows with .NET Framework 4.8 is required. No separate MuseScore, Guitar Pro, Finale or player installation is needed to read supported files. Free microphone commands additionally require Windows English speech recognition and microphone permission. Optional AI requires separate setup and may incur provider charges.

## Parts, lyrics and sound

Ctrl+T chooses readable MusicXML and MuseScore parts, including separate SATB voices. Supplied staves, voices, pitches, timing and lyrics follow the chosen part. Ordinary navigation reads printed lyric syllables; F3 supplies the complete word when source syllable boundaries establish it. Incomplete words are not guessed. Text tabs and chord sheets may contain lyrics without note-aligned word context.

Recognized parts use matching local practice sounds, including harp, wordless choir and assigned drum kits. Unknown assignments are not silently played as guitar. Playback is one selected part at a time; lyrics are not sung. Piano pedal preview and expressive performance remain approximations.

## Microphones and replies

Ctrl+Alt+L toggles the free reader microphone and explicitly announces on/off. Returning to the score keeps listening active. F9 or Voice > Stop voice and microphone stops the separate AI lesson.

Turn off Speak command replies with Windows voice in reader microphone settings, or Speak answers in AI voice settings, for screen-reader-only text. Starting conversation preserves that choice. Live output can be muted while input and the written transcript remain available; local muting does not eliminate provider usage or charges. These options do not change screen-reader settings.

## Read and practise

Ctrl+O opens music; F2 finds supported sources. Ctrl+2 focuses the score. Right/Left move through source positions; Ctrl+PageDown/PageUp move by measure. Up/Down inspects supplied simultaneous notes, staves or strings. F3 opens full current-position details. Ctrl+Shift+I opens supplied score information; Escape returns to your place.

Ctrl+P plays; Ctrl+Shift+P stops. Ctrl+S saves a reading and a newly selected loop. Ctrl+Shift+0 clears the current and saved loop immediately. Ctrl+1 reviews source information, Ctrl+4 opens tuning, F1 opens help and Ctrl+Alt+P finds app commands.

Supported sources include Guitar Pro, MusicXML, MuseScore, suitable PDFs, text tabs and chord charts. Guitar Pro part selection supports six-string tracks. PDF/OCR and uncertain imports need comparison with the original. Textual UEB BRF export is prose braille, not music-braille transcription.

## Reference and verification

Read the 54 supplement first. Retained version 53 Word manual/Quick Start and older supplements remain references for unchanged controls; they have not been relabelled as 54 editions. Native embedded preparation notes may retain earlier development status. Use SpeakTab-Source.zip for complete source; GitHub-generated source archives contain the small repository snapshot.

The main release gate and all 87 focused software checks passed. The user reports the local microphone toggle, lyric reading and part choice work. The user also confirms that Tab reaches the explanation after a short update delay. These scoped results do not establish universal score, device or audio accuracy. Complex score jumps, complete expressive playback, ensemble performance, sung lyrics and Finale import are not promised. Private music, readings, settings and diagnostic dumps are excluded from release packages.
