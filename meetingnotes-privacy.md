# Minutewell — Privacy Policy

_Last updated: October 22, 2026_

Minutewell ("the app") is a Windows app that records your meetings and calls on your PC, turns the speech into a transcript with speech recognition that runs on your computer, and keeps your meeting notes.

**What we collect:** nothing. The app does not collect, store, transmit or sell personal information. It has no account system, no analytics, no telemetry about your meetings and no advertising. We never receive your audio, transcripts, notes or files.

**What the app accesses:** only while you record or import, and only on your device:
- **Microphone** — your side of the conversation ("Me"). The app opens the microphone only after you start a recording, and Windows shows that the microphone is in use.
- **Your PC's audio output** — what your speakers or headphones play, captured with Windows audio loopback while a recording of a call is running ("Others"). In "Microphone only" mode it is not used.
- **Files you import** — audio and video files you drop into the window or pick with "Choose file…". The original file is only read; it is never changed, moved or uploaded.

**All processing happens on your device:** speech recognition, the live transcript, speaker labels, Quick notes (extracted by rules, not by generative AI) and the optional AI summary (a generative AI language model that runs locally on your PC's processor) all run on your PC. The AI summary is made only from the meeting's transcript; its text is stored with that meeting and is never sent anywhere. No audio, transcript, note, title, speaker name or file name is ever sent to us or to any online service.

**What is stored, and where:** each meeting is kept in your library folder — by default inside your Windows user profile (%LocalAppData%), or in a folder you choose in Options. A meeting folder holds the transcript, notes and AI summary, if you created one (meeting.json) and, unless you record text only, the audio (a temporary recording.wav that is compressed to audio.m4a after the meeting; for imported files, a compressed copy of the sound so you can listen again). A search index of all meetings (library.db) lives in the library folder. In text-only mode the audio stays in memory only and is thrown away; nothing to listen to is saved. If you choose a folder that syncs to OneDrive, the app warns you that audio would leave your PC through that service; network folders are not allowed. The app's settings, downloaded speech and AI models and a small diagnostic log are stored in your Windows user profile (AppData). The log never contains transcript text, notes, meeting titles, speaker names or file names.

**Your controls:**
- **Delete audio, keep text** for any meeting.
- **Delete audio older than** 30, 90 or 365 days automatically (Options); text and notes are kept.
- **Delete** a single meeting, or **Delete the whole library** in Options.
- **Text-only mode** keeps no audio at all (on by default in the EU/EEA, the UK and Switzerland).
- **Uninstalling** the app removes its settings, models, log and the default library folder. If you chose your own library folder, it is left in place so you keep your recordings; delete it yourself if you no longer need it.

Files you export (Markdown, text, Word, SRT, audio) are saved where you choose, and notes you copy go to the Windows clipboard; what happens to them afterwards is up to you.

**Reporting an AI summary:** the "Report content" button opens your own email app with a short message addressed to us. Nothing from your meeting is attached or sent automatically; you decide what to write and whether to send it. If you send it, we use the email only to look into the report and reply to you.

**Network:** the app connects to the internet only to:
- download the optional larger speech models (Balanced, about 190 MB, and Accurate, about 574 MB), when you first need them. Models are downloaded over HTTPS from the official whisper.cpp model repository on huggingface.co (Hugging Face and its content delivery network see your IP address, as with any file download) and are checked against a fixed SHA-256 fingerprint. The Fast English model and voice detection are included in the app;
- download the optional AI summary model (Qwen3-1.7B, about 1.1 GB) when you ask for it, over HTTPS from a fixed revision on huggingface.co, checked against a fixed SHA-256 fingerprint. After the download, summaries are made offline;
- let the Microsoft Store check your license and the optional "Pro" purchase.
Recording, transcription and AI summaries work fully offline.

**Recordings of other people:** a meeting recording contains the voices and words of other participants. That content is processed and stored only on your PC and is never shared with us or any third party. Recording laws differ by place, and in many places everyone must agree before a conversation is recorded. It is your responsibility to tell people and get their consent. To help, the app shows a "Before you record" reminder, offers a one-click "Copy notice" sentence to paste into the meeting chat (also in the tray menu), offers a text-only mode, and always shows in the window title and the tray icon when it is recording. This is not legal advice.

**Purchases:** the optional "Pro" upgrade is handled entirely by the Microsoft Store under Microsoft's privacy statement (https://privacy.microsoft.com/privacystatement); we never see your payment details.

**Children:** the app does not knowingly collect information from anyone, including children.

**Changes:** if this policy changes, the updated version will be published at this address with a new date.

**Contact:** luzartstudio.apps.support@gmail.com
