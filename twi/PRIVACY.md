# 1F616EMO Survival Server Privacy Policy

Author: 1F616EMO; State: Draft; Date effective: N/A

## What Information is Collected

For all players, we collect:

* IP address
* Passwords (using the Secure Remote Password protocol)
* Preferred language/locale
* User actions (e.g. login, world interaction) and their time stamps

Map contents and player inventory contents are not considered personal information. Please do not store any personal information in the form of in-game items or structures.

Please avoid giving other personal information as we do not want it.

## How this information isused

* To debug the server. We check the logs if an error occurs, and often attach logs (without sensitive information) to bug reports.
* To combat abuse. We keep logs and IP addresses to investigate rules violation cases.
* For IP banning to work. We keep user IP addresses to avoid abuses.
* Passwords are used to authenticate the user.
* Preferred language/locale is used to do server-side translation, e.g. for item searching to work.

## Who has access

* Moderators with the `ban` privilege can check whether accounts share the same IP address, but not have access to the IP itself.
* Logs, after redacting sensitive information, may be shared.
* Otherwise, only 1F616EMO has access to the log and the personal information.
* If authorized by 1F616EMO, RelaxingPlay may also have access to such data.

## Third-parties

We do not share any personal information with third parties.

## Location

The production server is on TH2, located in Hong Kong. The server may also run on TH3, located in Germany. All data transfers between locations are encrypted.

By using this service, you give permission for the data to be moved within Hong Kong and/or Germany.

## Period of Retention

Logs are rotated when the server restarts. Due to technical limitations, logs are not automatically deleted.

IP addresses in the XBan DB may be deleted after roughly 7 days[^1]. However, if an entry involves banning players, the IP address inside will not be deleted to ensure server security.

Usernames may be kept indefinitely, but other user information will be deleted if requested. See below.

## Removal Requests

Please [contact 1F616EMO](#contact-us) if you wish to remove your personal information.

Usernames will be kept to ensure integrity with in-game protections (e.g. node ownership, area ownership)[^2], data storage (e.g. mails), and the log. If you wish to hide your username completely, you may transfer all your owned areas and nodes to 1F616EMO or any player you wish.

## Future Changes to Privacy Policy

We will alert any future changes to the privacy policy via the in-game news system[^3].

By continuing to use this service, you agree to the privacy policy.

## Contact Us

You can use the in-game `/report` form to contact 1F616EMO. Make sure to select "Admin" (instead of "Moderators") as the receiver[^4].

You can also mail to [`root@1f616emo.xyz`](mailto:root@1f616emo.xyz) to contact 1F616EMO via e-mail.

[^1]: The implentation checks for outdated IP addresses every 60 seconds if the server is running properly. In each check, all XBan entries are iterated, and IP addresses are wiped from entries that are not bans and are older than 7 days. The server may fail to wipe IPs at exactly 7 days after the entry's creation due to execution delays and/or server malfunctions, but generally it is done within a day after the 7-day period.
[^2]: Locked nodes stores the owner's name in its metadata for authorization purpose, and protection areas stores the owner's name in the database. While it may be trivival to list out one's protection areas, but listing all locked nodes is impractical due to the absence of a centralize database.
[^3]: The in-game news system can be accessed by typing `/news` in the in-game chat room. The game system will notify any players who have not read the updated news.
[^4]: The `/report` system sends user messages to the moderation team via the in-game mail system. If set to send to "Admins", only 1F616EMO and RelaxingPlay (if authorized) can read the message.