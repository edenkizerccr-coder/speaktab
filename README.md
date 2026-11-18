# SpeakTab

SpeakTab lets you read Guitar Pro files, plain-text tablature, chord charts and scores with a keyboard, screen reader or Braille display. Follow a part by beat or measure and play a passage. Windows exports readings as text or Markdown. Android exports a readable text file. The Composer lets you write and edit music. Music Braille output is experimental.

In SpeakTab for Windows 1.0.74, press Ctrl+O in the Reader or Composer to open your music. You can also choose File > Open (Alt+F, then O). The file list opens on All files, so you can open a Guitar Pro tab, another score, a PDF, a scan, a saved reading or an editable SpeakTab project without changing the file type.

## Current downloads

### Windows 1.0.74

- [Complete Windows ZIP](https://github.com/edenkizerccr-coder/speaktab/releases/download/v1.0.74/SpeakTab-Windows.zip)
- [Windows user manual in Word](https://github.com/edenkizerccr-coder/speaktab/releases/download/v1.0.74/SpeakTab.User.Manual.docx) and [RTF](https://github.com/edenkizerccr-coder/speaktab/releases/download/v1.0.74/SpeakTab.User.Manual.rtf)
- [Windows keyboard shortcuts in Word](https://github.com/edenkizerccr-coder/speaktab/releases/download/v1.0.74/SpeakTab.Windows.Keyboard.Shortcuts.docx) and [RTF](https://github.com/edenkizerccr-coder/speaktab/releases/download/v1.0.74/SpeakTab.Windows.Keyboard.Shortcuts.rtf)
- [Windows Quick Start in Word](https://github.com/edenkizerccr-coder/speaktab/releases/download/v1.0.74/SpeakTab.Quick.Start.docx) and [RTF](https://github.com/edenkizerccr-coder/speaktab/releases/download/v1.0.74/SpeakTab.Quick.Start.rtf)
- [Composition lessons in Word](https://github.com/edenkizerccr-coder/speaktab/releases/download/v1.0.74/SpeakTab.Composition.Lessons.docx) and [RTF](https://github.com/edenkizerccr-coder/speaktab/releases/download/v1.0.74/SpeakTab.Composition.Lessons.rtf)
- [Introductory Braille music lessons in Word](https://github.com/edenkizerccr-coder/speaktab/releases/download/v1.0.74/SpeakTab.Braille.Music.Lessons.docx) and [RTF](https://github.com/edenkizerccr-coder/speaktab/releases/download/v1.0.74/SpeakTab.Braille.Music.Lessons.rtf)

**Updating from Windows 1.0.67 or earlier:** Download the complete ZIP, extract it to a new folder, and open SpeakTab.exe there. Keep the previous folder until you have found your personal Saved Readings and My Music. The older update checker cannot find the new public 1.x tag. From 1.0.68 onward, use Help > Check for updates for future releases. Settings > Saved readings > Choose saved readings folder (Alt+S, then S, then F) can point to an existing folder.

**Already using Windows 1.0.68 through 1.0.73?** Help > Check for updates (Alt+H, then E) can find 1.0.74 and verify the complete ZIP before installation. Save your work first.

### SpeakTab Android 0.6.11 beta 4 for Android 15 or later

- [Main Android beta installer](https://github.com/edenkizerccr-coder/speaktab/releases/download/android-v0.6.11-beta4/SpeakTab-0.6.11-beta4.apk)
- [Android user guide in Word](https://github.com/edenkizerccr-coder/speaktab/releases/download/android-v0.6.11-beta4/SpeakTab.Android.User.Guide.0.6.11-beta4.docx) and [RTF](https://github.com/edenkizerccr-coder/speaktab/releases/download/android-v0.6.11-beta4/SpeakTab.Android.User.Guide.0.6.11-beta4.rtf)
- [Android keyboard reference in Word](https://github.com/edenkizerccr-coder/speaktab/releases/download/android-v0.6.11-beta4/SpeakTab.Android.Keystrokes.0.6.11-beta4.docx) and [RTF](https://github.com/edenkizerccr-coder/speaktab/releases/download/android-v0.6.11-beta4/SpeakTab.Android.Keystrokes.0.6.11-beta4.rtf)

This is the main Android download for a BrailleSense 7 running Android 15. The installed app is named SpeakTab. Its main score reading is navigable musical text. Braille music output for supported MusicXML is experimental and should be checked against the source score. The beta updates existing main Android installations in place; the older separate Braille music test app remains separate.

### Android 0.6.9 compatibility beta for Android 12 through 14

- [Compatibility installer](https://github.com/edenkizerccr-coder/speaktab/releases/download/v1.0.69/SpeakTab-Android-0.6.9-beta1.apk)
- [Compatibility guide in Word](https://github.com/edenkizerccr-coder/speaktab/releases/download/v1.0.69/SpeakTab.Android.User.Guide.0.6.9-beta1.docx) and [RTF](https://github.com/edenkizerccr-coder/speaktab/releases/download/v1.0.69/SpeakTab.Android.User.Guide.0.6.9-beta1.rtf)
- [Compatibility keystrokes in Word](https://github.com/edenkizerccr-coder/speaktab/releases/download/v1.0.69/SpeakTab.Android.Keystrokes.0.6.9-beta1.docx) and [RTF](https://github.com/edenkizerccr-coder/speaktab/releases/download/v1.0.69/SpeakTab.Android.Keystrokes.0.6.9-beta1.rtf)

The compatibility beta still needs hands-on testing on Android 12 through 14 devices.

## Start reading on Windows

Press **Ctrl+O** to open a score and **Ctrl+2** to return focus to its notes and chords. Left and Right Arrow move by written position, including fractional beats and rests; **Ctrl+Page Up** and **Ctrl+Page Down** move by measure. **Tab** opens full Beat attributes; **Shift+Tab** returns to the score. **F11** reports your location without moving, and **Ctrl+3** focuses the current explanation. **Ctrl+P** starts, pauses or resumes playback, and **Ctrl+Shift+P** stops. Settings > Playback and practice > Follow playback (**Alt+S, then P, then F**) tracks the written score by beat and Braille by measure. The Windows manual explains each control and keyboard route in task order.

For supported MusicXML percussion, **Ctrl+Shift+I** opens Score information with the supplied meter, played instrument names, written tempo or its absence, possible right/left text to inspect or the absence of readable right/left labels, and available tuplet, playing-mark and repeat information. The beat reading keeps the actual written hits and markings. SpeakTab does not invent a sticking pattern or change a source meter.

ChatGPT-assisted PDF and existing-score repair requests now identify every actual part, including mixed drum and pitched parts, before conversion. They check written meter, tempo, rhythms, voices, tuplets, marks and repeats, then explicit percussion R/L labels and played sounds, fretted strings and tuning, keyboard voices and pedal, or vocal lyric alignment where relevant. Uncertain details are reported by page, measure, part and feature for review against the original instead of being guessed. To open a PDF, press **Ctrl+O**. In PDF choices, **Alt+A** opens in-app repair and **Alt+W** prepares the website prompts. **Alt+C** opens the ChatGPT menu. From the Reader, **Ctrl+Shift+R** opens the website prompt tool directly. For an existing score, use **Ctrl+O**, then **File > PDF and score repair > Repair with AI** (**Alt+F, then 9, then R**). Recovery is not guaranteed.

**F1** explains the focused control. **Ctrl+Alt+P** opens Find a command, and **Ctrl+Shift+U** opens the in-app User guide. Help > Keyboard > Complete keyboard reference opens with **Alt+H, then K, then C**. **Ctrl+Shift+H** opens 41 read-only Guided tutorials; a separate button opens 20 checked practice exercises. **Alt+H, then 8** opens the introductory Braille music course with 22 read-only lessons and 23 checked entry exercises. Optional shortcut customization belongs in **Settings > Keyboard** (**Alt+S, then K, then M**).

## Written questions and spoken controls

The **ChatGPT** menu (**Alt+C**) contains written-question actions: **F5** focuses the question, **Enter** sends it, and **F6** focuses the full answer. You can ask how SpeakTab works as well as questions about the open reading. Its account, model and speech settings are under **Settings > ChatGPT** (**Alt+S, then C**). The separate live **AI teacher** menu (**Alt+A**) uses **F8** to start and **F9** to stop. Its API key, Remember choice, voice and microphone are in one Save or Cancel dialog under **Settings > AI teacher** (**Alt+S, then A**). Local **Voice control** (**Alt+V**) uses spoken app commands; its setup is under **Settings > Voice control** (**Alt+S, then V**). **Help > Voice control phrases** (**Alt+H, then X** or **Ctrl+Shift+X**) lists the accepted phrases.

## Files, sound and limits

The complete Windows ZIP includes the Airfont 380 Final General MIDI SoundFont and its attribution. It also has an embedded built-in sound library. Recall Score is not required; the separate Airfont download is for people who want the bank file by itself. In Settings > Playback and practice, Instrument sound for this reading (Alt+S, then P, then S) follows the score's instrument when set to Automatic. Use automatic SoundFont (Alt+S, then P, then R, then U) chooses the included Airfont bank. Use built-in sounds (Alt+S, then P, then R, then S) enables SoundFont acoustic guitar (Alt+S, then P, then B, then S) and Original acoustic guitar (Alt+S, then P, then B, then O). Enhanced acoustic guitar sound in the playback dialog (Alt+S, then P, then S) adds stereo room sound to compatible built-in guitar playback. PDF recognition and conversion require musical review. The introductory Braille lessons do not claim complete formal Music Braille Code transcription. Software checks do not replace direct testing with a screen reader, Braille display, Android device, speaker or microphone.

- [Windows source ZIP](https://github.com/edenkizerccr-coder/speaktab/releases/download/v1.0.74/SpeakTab-Source.zip)
- [Airfont 380 Final SoundFont](https://github.com/edenkizerccr-coder/speaktab/releases/download/v1.0.74/Airfont_380_final.sf2)
- [SpeakTab website](https://speaktab.pages.dev/)
- [Release notes and all downloads](https://github.com/edenkizerccr-coder/speaktab/releases/tag/v1.0.74)

Thanks to Chris (Chessel85), creator of [Recall Score](https://github.com/Chessel85/RecallScore), for ideas behind pitch-focused reading, direct MIDI playback and web TAB import. Airfont 380 Final is by Milton Paredes of mpj factory studios; its attribution is included with the Windows download. For a problem, tell the developer your app version, file or exercise, keys pressed, expected result and actual result. [Contact the developer](https://speaktab.pages.dev/contact.html).
