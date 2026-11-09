# Keytide — Privacy Policy

_Last updated: November 9, 2026_

Keytide ("the app") is a Windows app that shows two-factor authentication (2FA) codes for your online accounts, like an authenticator app on a phone.

**What we collect:** nothing. The app does not collect, transmit or sell personal information. It has no account system, no analytics and no advertising, and it never connects to the internet. Your accounts are not synced to any cloud by the app.

**Your accounts and keys:** the accounts you add (the website or service name, your account name, the secret setup key, and optional folder names) are stored only on this PC, in an encrypted file in your Windows user profile (AppData). The file is encrypted with AES-256-GCM. By default, its key is protected by Windows for your user account (DPAPI). If you set a master password (Pro), the key is protected by your password instead (PBKDF2-SHA256, 600,000 rounds); the password itself is never stored. We cannot read your accounts and cannot recover a forgotten master password.

**QR codes and screen scanning:** when you open or drop an image, paste from the clipboard or (Pro) scan your screen, the app reads the image only in memory to find a setup QR code. Screen images are not saved, not sent anywhere and are discarded right after reading.

**Clipboard:** when you click a code, it is copied to the clipboard and marked so that Windows does not keep it in clipboard history or sync it to other devices. If the clipboard still holds that code after 30 seconds, the app clears it. The app reads the clipboard only when you choose to paste.

**Backups:** backup files are created only when you ask for them, or (Pro) automatically in a folder you choose. They are encrypted with a password you choose. For automatic backups, the app keeps a key derived from that password inside its encrypted file, never the password itself. Where backup files go (for example a USB drive or a folder synced by a cloud service you use) is your choice; that service's own privacy policy applies to its copies.

**Screen sharing:** if you turn on "Hide this window in screen sharing and recordings", Windows shows other people an empty area instead of the app window.

**Local data:** besides the encrypted file and its previous copy, the app stores its settings (theme, auto-lock time, shortcut, backup folder) and a small diagnostic log in your Windows user profile (AppData). The log contains only counts, times and error types — never codes, keys, account names, passwords or file names. Uninstalling the app removes this data; backup files you saved elsewhere stay where you put them.

**Purchases:** the optional "Pro" upgrade is handled entirely by the Microsoft Store under Microsoft's privacy statement (https://privacy.microsoft.com/privacystatement); we never see your payment details.

**Children:** the app does not knowingly collect information from anyone, including children.

**Changes:** if this policy changes, the updated version will be published at this address with a new date.

**Contact:** luzartstudio.apps.support@gmail.com
