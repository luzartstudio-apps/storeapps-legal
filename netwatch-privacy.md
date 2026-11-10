# Blipwell — Privacy Policy

_Last updated: November 10, 2026_

Blipwell ("the app") is a Windows app that checks your internet connection every few seconds and keeps a timed log of every drop, with whether the cause was your home network, your internet provider or DNS.

**What we collect:** nothing. The app does not collect, store on our servers, transmit or sell personal information. It has no account system, no analytics and no advertising.

**What the app sends over the network:** only what it needs to measure your connection, and only while monitoring is on:
- small ping packets (ICMP echo, 32 bytes) to your router (the default gateway of your PC);
- small ping packets to two internet addresses, by default 1.1.1.1 and 8.8.8.8 (public DNS services operated by Cloudflare and Google). You can change them in Settings;
- one DNS lookup of a test name (example.com by default, you can change it) to the DNS servers your PC is already set to use;
- with Pro: ping packets to the extra addresses you add yourself, and, when a drop starts and you have route tracing on, ping packets with a limited time-to-live toward the first internet address (the same technique as the Windows tracert command).

Like any ping, these packets let the receiving servers see your public IP address. They carry no other information about you or your PC. The app sends nothing else and does not contact any server of ours.

**Your data:** the history of checks (per-minute counts and latency) and of drops (start, end, length, cause, and the route trace if any) is stored only on your device, in the app's folder in your Windows user profile (AppData). The free version shows the last 7 days and automatically deletes files older than 30 days; with Pro, history is kept until you delete it. You can delete all history at any time in Settings. Reports (PDF or CSV) are saved only where you choose and are never sent anywhere by the app.

**Your files:** the app does not read your files, contacts or calendar. It only writes the report files you ask for.

**Location:** the app does not use your location.

**Microphone, camera, screen and keyboard:** the app does not use the microphone or camera, does not capture the screen and does not monitor your typing.

**Purchases:** purchases of the optional "Pro" upgrade are handled entirely by the Microsoft Store under Microsoft's privacy statement (https://privacy.microsoft.com/privacystatement); we never see your payment details.

**Local data:** besides the history above, the app stores its settings and a small diagnostic log in your Windows user profile (AppData). Uninstalling the app removes them. The log never contains IP addresses, host names, file names or report contents.

**Children:** the app does not knowingly collect information from anyone, including children.

**Changes:** if this policy changes, the updated version will be published at this address with a new date.

**Contact:** luzartstudio.apps.support@gmail.com
