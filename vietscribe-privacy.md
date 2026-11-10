# Ghiwell — Privacy Policy

_Last updated: November 10, 2026_

Ghiwell ("the app") is a Windows app that turns Vietnamese meetings and interviews into text on your PC. It transcribes speech from your microphone, from your PC's audio or from audio and video files you choose, labels the speakers and drafts meeting minutes. Speech recognition, speaker labels and minutes are made on your computer.

**What we collect:** nothing. The app does not collect, store, transmit or sell personal information. It has no account system, no analytics, no telemetry about your meetings and no advertising. We never receive your audio, transcripts, minutes, notes, glossary or files.

**What the app accesses:** only while you record or transcribe a file, and only on your device:
- **Microphone** — in "Meeting room" and "Online meeting on this PC" modes. The app opens the microphone only after you start a recording, and Windows shows that the microphone is in use.
- **Your PC's audio output** — what your speakers or headphones play, captured with Windows audio loopback in "Online meeting on this PC" and "PC audio only" modes, while a recording is running.
- **Files you choose** — audio and video files you drop into the window, pick with "Choose files", add as a folder (Pro) or open with the app. The original file is only read; it is never changed, moved or uploaded.

**All processing happens on your device:** speech recognition, voice detection, speaker separation, number formatting, glossary corrections and the draft minutes all run on your PC's processor, with the models included in the app (and, for other languages, the optional model you download). Action items, conclusions and open questions in the minutes are found with fixed rules, not with generative AI. To tell speakers apart, the app computes "voice vectors" for short pieces of speech. They exist only in memory during one meeting, are discarded once the minutes are drafted and are never written to disk. The app does not remember anyone's voice from one meeting to the next.

**What is stored, and where:** each meeting is kept in your meetings folder — by default inside your Windows user profile (%LocalAppData%), or a folder you choose in Settings. A meeting folder holds meeting.json (title, transcript, speaker names you typed, notes, ★ marks, minutes details and, for an imported file, its file name) and, unless you chose text only, the audio (audio.m4a). While recording or transcribing, the app also writes a temporary audio.wav and, during a recording, a recovery journal (journal.jsonl) and — only when your PC transcribes slower than people speak — a temporary queue of the audio still waiting to be transcribed (asr-backlog.bin), so nothing is lost if the app or the PC stops unexpectedly; the journal and the queue are deleted when the minutes are drafted. In text-only mode the temporary audio is deleted as soon as the minutes are drafted. If a file transcription was interrupted, its decoded audio stays in its meeting folder until you choose "Transcribe again" or "Delete". A search index of all meetings (library.db) lives in the meetings folder. If your meetings folder is inside OneDrive, the app warns you that OneDrive would upload your meetings to the cloud. The app's settings, your glossary, the optional downloaded language model and a small diagnostic log are stored in your Windows user profile (AppData). The log never contains transcript text, notes, meeting titles, speaker names or file names.

**Your controls:**
- **Text only:** turn off "Keep the audio" before recording; only the text is kept.
- **Delete** any meeting; its audio, transcript and notes are removed from your PC.
- **Choose** where meetings are stored, and open that folder from the app.
- **Uninstalling** the app removes its settings, glossary, model, log and the default meetings folder. If you chose your own meetings folder, it is left in place so you keep your meetings; delete it yourself if you no longer need it.

Files you export (Word, text, Markdown, audio) are saved where you choose, and minutes or notices you copy go to the Windows clipboard; what happens to them afterwards is up to you.

**Reporting a transcription problem:** the "Report a transcription problem" item (in the "…" menu of a meeting) opens your own email app with a message addressed to us. Nothing from your meeting is attached or sent automatically; you decide what to write and whether to send it. If you send it, we use the email only to look into the report and reply to you.

**Network:** Vietnamese transcription works fully offline. The app connects to the internet only to:
- download the optional "Other languages" speech model (Pro, about 1 GB) when you ask for it, over HTTPS from a fixed revision on huggingface.co (Hugging Face and its content delivery network see your IP address, as with any file download). The files are checked against fixed SHA-256 fingerprints, and transcription with them then runs offline;
- let the Microsoft Store check your license and the optional "Pro" purchase.

**Recordings of other people:** a meeting recording contains the voices and words of other participants. That content is processed and stored only on your PC and is never shared with us or any third party. Recording laws differ by place, and in many places everyone must agree before a conversation is recorded. It is your responsibility to tell people and get their consent. To help, the app shows a "Before you record" reminder, offers a one-click notice to paste into the meeting chat (also in the tray menu), offers a text-only mode, and always shows in the window title and the tray icon when it is recording. This is not legal advice.

**Purchases:** the optional "Pro" upgrade is handled entirely by the Microsoft Store under Microsoft's privacy statement (https://privacy.microsoft.com/privacystatement); we never see your payment details.

**Children:** the app does not knowingly collect information from anyone, including children.

**Changes:** if this policy changes, the updated version will be published at this address with a new date.

**Contact:** luzartstudio.apps.support@gmail.com
