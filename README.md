# SpeakTab

SpeakTab is a Windows music reader and practice companion for blind and low-vision musicians. Explore supported guitar and piano music with a keyboard, screen reader or free voice commands. Read notes and chords, hear a practice preview, slow down and loop a passage, and save places and practice reminders.

## Version 10.14.51

**[Download the complete Windows app](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab-Windows.zip)**

Version51 makes full explanations a complete current-position view, simplifies position navigation, and clears existing saved loops immediately without a separate Save. Version50 remains available in [earlier releases](https://github.com/edenkizerccr-coder/speaktab/releases/tag/v10.14.50).

## Start and read

Extract the complete app ZIP with its runtime, licences and native guides, then run SpeakTab.exe. Ctrl+O opens music; F2 finds it. Supported import routes include Guitar Pro, MusicXML, MuseScore, PDF, text tablature and chord charts, with format-specific limits.

Ctrl+2 focuses the score. Left/Right moves to the previous/next note or chord position. Several positions may occur within one beat. Up/Down inspects simultaneous notes or strings. Ctrl+PageUp/PageDown moves by measure; Ctrl+G jumps to a measure. The duplicate Alt+Shift+PageUp/PageDown commands have been removed.

F3 opens full current-position context: supplied simultaneous notes, earlier notes still sounding, rests in progress, lyrics, playing marks and the most recent written chord reminder where available. Continuing sounds are described only when written timing is established. Ordinary navigation stays quiet about continuing notes. Ctrl+3 opens the chosen explanation style; concise focuses on current musical facts, while full includes ongoing context. Compact string-fret pairs remain a separate option. F3 does not change your selected style.

Ctrl+P plays; Ctrl+Shift+P stops. Ctrl+Shift+0 clears the current and existing saved loop immediately, without saving unrelated edits. A newly created loop is retained only when explicitly saved with Ctrl+S. Failure to clear an unavailable saved file is reported and can be retried.

## Guides

**[Version51 changes and current controls in Word](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.51.Changes.and.Current.Controls.docx)** | **[Changes in text](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.51.Changes.and.Current.Controls.txt)**

The [full manual in Word](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.User.Manual.docx) and [Quick Start](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab.Quick.Start.docx) remain the reviewed version50 base editions. Read the51 supplement first: it supersedes their changed loop-clearing, full-explanation and duplicate beat-shortcut instructions. Current native help and keyboard references cover51. Expanded documents are companion downloads and are included in the complete source handoff.

## Verification and limits

The main release gate and all82 focused checks passed. The actual Chopin reading was checked at representative positions: full-context generation took at most3ms in that local probe. These are software checks, not physical51 screen-reader/audio acceptance or a guarantee for every score/device. The user accepted50 navigation and authorized51 publication. An occasional empty staff label remains a minor known issue.

Source pitches, timing, ties, audio banks and voice implementations are preserved. Named ornaments are described without being expanded into performed notes. Complex score jumps, PDF recognition and expressive playback have documented limits. Main local reading and practice do not require paid AI; optional connected AI needs separate working access. Future vocal-score and wider instrument work and the possible SpeakScore name are planning items rather than universal support claims.

Use [SpeakTab-Source.zip](https://github.com/edenkizerccr-coder/speaktab/releases/latest/download/SpeakTab-Source.zip) for the complete developer handoff. GitHub-generated source archives are not the complete build package.
