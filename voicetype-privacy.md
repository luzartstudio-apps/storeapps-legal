# Saywell — Privacy Policy

_Last updated: October 22, 2026_

Saywell ("the app") is a Windows app that lets you type with your voice in any app. Speech recognition runs on your computer.

**What we collect:** nothing. The app does not collect, store on our side, transmit or sell personal information. It has no account system, no analytics, no telemetry and no advertising. No audio and no text you dictate is ever sent to us or to anyone else.

**Your voice:** the app uses your microphone only while you hold the talk key or while hands-free dictation is on. The recorded audio is kept in memory (RAM) only while it is being turned into text, and is then discarded. Audio is never written to disk and never uploaded.

**Your text and history:** the text you dictate is inserted into the app you are typing in. A copy of each dictation, with the time and the name of the app it went to, is kept in History so you can find it or paste it again. History, your personal dictionary, your snippets and your settings are stored only on your PC, in `%LocalAppData%\StoreApps\VoiceType`. You can turn History off, delete single entries or everything at once, and choose how long History is kept (7 days in the free version). Dictionary words and snippets can be deleted at any time. Uninstalling the app removes all of this data.

**Keyboard:** the app watches the keyboard only to detect the talk key you chose and the Esc key (Esc is used to cancel, and only while a recording is running). Other keystrokes are passed through untouched; they are never recorded, stored or sent anywhere.

**Clipboard:** to insert text, the app saves what is on your clipboard, places the dictated text on the clipboard, sends Ctrl+V and then puts your previous clipboard content back. The dictated text is marked so that Windows does not add it to your clipboard history. If text cannot be pasted (for example into a window running as administrator), it is left on the clipboard and the app tells you to press Ctrl+V.

**Password fields and the app you are typing in:** the app uses Windows UI Automation only to read whether the focused field is a password field, and never types into password fields. It does not read the content of your windows or fields, and it does not change any Windows settings. It reads the name of the app you are typing in, and whether it runs as administrator, only to choose the right text style and insertion method.

**Network:** the app connects to the internet only to:
- download the speech model you choose (57–547 MB) from huggingface.co, using fixed (pinned) addresses. Hugging Face and its content delivery network see your IP address, as with any file download. Each model is checked against a fixed SHA-256 fingerprint. After the download, speech recognition works fully offline;
- let the Microsoft Store check your license for the optional "Pro" upgrade.

**AI:** text is produced on your device by an AI speech recognition model (OpenAI Whisper weights run by whisper.cpp) and may contain mistakes. This version does not use generative AI: it only writes down what you say. The app never sends your voice or your text to any AI service.

**Local data:** besides the data above, the app stores the downloaded speech models and a small diagnostic log in the same folder. The log never contains audio, dictated text or keystrokes. You can delete downloaded models in the app.

**Purchases:** the optional "Pro" upgrade is handled entirely by the Microsoft Store under Microsoft's privacy statement (https://privacy.microsoft.com/privacystatement); we never see your payment details.

**Children:** the app does not knowingly collect information from anyone, including children.

**Changes:** if this policy changes, the updated version will be published at this address with a new date.

**Contact:** luzartstudio.apps.support@gmail.com
