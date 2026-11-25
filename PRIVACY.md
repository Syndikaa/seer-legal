# Seer Privacy Policy

**Effective date:** November 25, 2026

This Privacy Policy explains what data **Seer**, a Discord application (application ID `1549599550933835786`) run by the Redliner team ("we", "us", "our"), collects, how we use it, and the choices you have. It applies to everyone who installs or uses Seer, and to Redliner players whose game data staff view or change through Seer.

## 1. Data we collect

### From people who use Seer

| Data | Where it comes from | Why |
| --- | --- | --- |
| Discord user ID, username, and where a command was run (server, channel or DM) | Discord, when you use a command | To answer commands, check access and keep an audit log |
| The commands you run and the options you enter, such as target player, reason, amount or duration | You | To carry out the command and keep an audit log |
| Roblox user ID, username and display name | Roblox sign-in, when you run `/auth link` | To link your Discord account to your Roblox account |
| Your rank and role in the Redliner Roblox group | Roblox | To decide which commands you can use |
| When you linked your account and when your rank was last checked | Seer | To refresh your rank every few minutes |
| Your reply preference (whether replies are visible only to you) | You | To remember your setting |
| Access granted to you by the Redliner owner | The owner | To give staff access |

### About Redliner players

When staff use Seer, it reads and changes Redliner game data that the game already stores in Roblox: player profiles, inventories, currencies, ranked records, trade history, moderation cases and Roblox bans. Seer reads this data on request and does not keep its own copy, apart from the audit log described below.

### What Seer does not collect

- Seer does not read Discord messages. It only receives the slash commands and button presses sent to it.
- Seer never sees your Roblox password. You sign in on Roblox's own sign-in page, and Roblox only shares basic profile details with us.
- Seer does not collect payment information, email addresses, IP addresses or location.

## 2. How sign-in works

`/auth link` sends you to Redliner's Concepts website, which uses Roblox's official sign-in (OAuth). That website stores a short-lived sign-in session, plus your Discord user ID and Roblox ID, username, display name and group rank, in its database (hosted by Supabase). This lets Seer finish linking your account. Your Concepts website profile is also tagged with your Discord user ID.

## 3. How we use data

We use the data above only to:

- run Seer and answer your commands;
- check that you are allowed to use each command;
- carry out the moderation and data actions staff request;
- keep an audit trail of staff actions, so the Redliner team can review them and stop abuse;
- fix bugs and keep Seer secure.

We do not sell data, use it for advertising, or use it to train AI models.

## 4. Audit logs and moderation records

- **Audit log:** each command, its options, the result and any failure is posted to a private, staff-only Discord channel. The post records who ran it (Discord user and linked Roblox account).
- **Moderation records:** when staff take an action, Seer saves it in Redliner's game data on Roblox, such as a case file, ban or trade ban. The record includes the reason and the staff member's Roblox username, Roblox ID and Discord ID.

## 5. Where data is stored

- **Linked accounts and preferences:** a private server hosted by DigitalOcean.
- **Sign-in sessions and Concepts profiles:** the Concepts website's database, hosted by Supabase.
- **Game data and moderation records:** Roblox's Data Stores, under the Redliner experience.
- **Audit logs:** a private Discord channel.

Pending confirmations, for example a ban waiting for its Confirm button, live only in memory and expire after 5 minutes.

## 6. How long we keep data

- **Linked account:** until you run `/auth unlink` or ask us to delete it. Linking a Roblox account that was already linked to another Discord account removes the old link.
- **Sign-in sessions:** they expire after 10 minutes.
- **Audit logs and moderation records:** kept as long as needed to moderate Redliner and review staff actions. They may be kept after you lose access or unlink.
- **Game data:** kept by Redliner and Roblox under their own policies.

## 7. Sharing

We share data only:

- with the Redliner team members who manage Seer and staff;
- with service providers that run Seer and Redliner: Discord, Roblox, DigitalOcean and Supabase, under their own privacy policies;
- when required by law, or to protect the safety of players, staff or the service.

## 8. Your choices and rights

- **Unlink:** `/auth unlink` deletes your linked account from Seer's storage right away.
- **Stop using Seer:** uninstall the app from your Discord account or server.
- **Access or deletion:** you can ask what data Seer holds about you, or ask us to delete it, including the Discord tag on your Concepts website profile. Contact us as described below. Some audit and moderation records may be kept where they are needed to moderate Redliner or to prevent abuse.

Depending on where you live, you may have other rights over your data, such as correction or objection. Contact us to use them.

## 9. Security

We keep tokens and keys on a private server, limit access to the people who run Seer, and only let linked staff with the right rank use its commands. No system is perfectly secure, so we cannot guarantee absolute security.

## 10. Children

Seer is a staff tool and is not meant for children. Anyone using it must meet the minimum age set by Discord's and Roblox's terms. If you think a child has given us data through Seer, contact us and we will delete it.

## 11. Changes to this policy

We may update this Privacy Policy. Changes are published in this repository, with a new effective date. If you keep using Seer after a change, you accept the updated policy.

## 12. Contact

For privacy questions or requests, open an issue in this GitHub repository or contact Redliner staff in the official Redliner Discord server. Do not post private details in a public issue; ask there for a private way to reach us instead.
