# Marmok Bots — Privacy Policy

Effective date: 8 October 2026

## Scope and operator

This policy explains how Marmok Event (Discord application ID: 1486027665751281837) and its associated event management dashboard process information. The operator is the maintainer of the GitHub account [sufferedkid](https://github.com/sufferedkid). This repository can host materials for additional Marmok bots; their data practices must be documented before this policy is used for them.

## Information processed

Marmok Event processes the following information as needed for its event features:

- Discord server, user, role, channel, message, thread and scheduled event identifiers. Guild membership and configured staff roles are used to resolve hosts, check access and add event staff to management threads.
- Event titles, descriptions, configuration, schedules and timestamps; host assignments; participant registration and attendance status; accumulated participation coins and event reward records.
- Host statistics, Discord display names and avatar URLs, and participant feedback associated with an event, host and submitting user.
- Dashboard authentication session information, including Discord user ID, display name, avatar URL, roles and access level; administrative action records, including administrator identifiers, actions and timestamps. The dashboard uses a session cookie to maintain sign-in.
- Information you voluntarily provide when requesting support or exercising a privacy request.

Voice channel joins and departures are processed to manage attendance and event access. The bot does not record voice audio. Its current event features do not track online presence, read private conversations or store the content of ordinary user messages. Text entered directly into event commands or dashboard forms is processed for the requested event functionality. A Discord message ID is a reference to a message, not its message content.

## Purposes

Information is used to create and run events, manage event channels and staff access, record attendance, calculate virtual rewards, maintain event history and host statistics, collect event feedback, authorize dashboard access, and support administration and troubleshooting. API data is not used for advertising, sold, or used to train machine learning or AI models.

## Storage, access and sharing

Event records and Discord identifiers are stored outside Discord in the application databases (PostgreSQL and MongoDB). Stored application data is encrypted at rest. Event features make relevant event information, participant information, feedback and host statistics available through Discord and the dashboard according to their configured access controls. Server administrators and authorized event staff can access information required for their event management roles.

Discord receives information when the application uses its API to create or update event messages, channels, threads and scheduled events. Infrastructure providers may process data as necessary to host the application and its databases. Data may also be disclosed where required by applicable law or at the affected user's explicit direction, subject to Discord's developer rules.

The public GitHub repository contains this policy and separately approved demonstration screenshots; it is not a storage location for the application's databases or routine participant records. GitHub and Telegram process interactions with their services under their own policies. Do not include private event data in public issues.

## Retention

Event history, participation and reward records, host statistics and administrative records may be kept for more than 30 days while needed for the stated application features. The current application does not apply a universal automatic 30-day expiry. Leaving an event or server, or removing the bot, does not by itself automatically erase previously stored database records.

Data no longer needed for the stated features is to be deleted. The operator handles deletion requests manually and promptly, including requests from affected users or Discord, except where retention is required by applicable law.

## Your choices and deletion requests

You may request access to, correction of or deletion of information relating to you by contacting the operator privately through [Telegram @sufferedk1d](https://t.me/sufferedk1d). Mention Marmok Event, the relevant Discord server and the type of request. The operator may ask for your Discord user ID and reasonable confirmation of account ownership to locate the records and prevent unauthorized requests. Never send passwords, bot tokens or authentication codes.

You can also ask the moderators of a server using the bot to connect you with its operator. General questions can be raised in [GitHub Issues](https://github.com/sufferedkid/marmok-bots/issues), but issues are public: use private contact for personal data or account-specific requests.

There is no automated per-user privacy opt-out command in the current bot. You can avoid voluntary event participation and feedback, but membership and role information may still be processed for configured staff workflows in a server using the bot. Server administrators can remove the bot to stop further server processing; existing records require a separate deletion request. Deleting event records may affect associated statistics or reward history.

## Updates and other services

This policy will be updated here when the application's data practices change. The effective date identifies the latest version. Discord's own processing is governed by the [Discord Privacy Policy](https://discord.com/privacy). Use of Discord API data is also subject to the [Discord Developer Terms of Service](https://support-dev.discord.com/hc/en-us/articles/8562894815383-Discord-Developer-Terms-of-Service) and [Discord Developer Policy](https://support-dev.discord.com/hc/en-us/articles/8563934450327-Discord-Developer-Policy).
