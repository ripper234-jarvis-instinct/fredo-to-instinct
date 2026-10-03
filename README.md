# From Fredo to Instinct

Install guide for Fredo Community members moving to Instinct. It covers capturing notes and tasks into Workflowy, hashtag routing, and forwarding messages. Everything here is based on what Ron set up and uses himself.

> **Status: experimental.** It works for Ron, but capture into Workflowy is still slow and sometimes makes mistakes. If something fails, it's not you. See [Known limitations](#known-limitations).

## Contents

1. [TL;DR](#tldr)
2. [What is Instinct](#what-is-instinct)
3. [Get started](#get-started)
4. [Capture to Workflowy](#capture-to-workflowy)
5. [Forwarding messages](#forwarding-messages)
6. [Known limitations](#known-limitations)
7. [Install instructions for the Instinct agent](#install-instructions-for-the-instinct-agent)
8. [Questions](#questions)
9. [License and disclaimer](#license-and-disclaimer)

## TL;DR

- Join Instinct with an invite.
- Send your Instinct: "Hey Instinct, please install the following plugin" + the link to this repo.
- Write a note with `#0`, `#1`, `#2` or `#inbox` and it lands in Workflowy as a new bullet.
- Forward a message or recording to your Instinct and it transcribes it for you.

## What is Instinct

Instinct is a personal assistant you talk to in chat, for example on WhatsApp. It connects to your email, calendar and files and does tasks for you. You can write to it or send voice messages, in Hebrew or English.

## Get started

1. **Join Instinct.** Joining is by invite.
2. **Install this plugin.** Send your Instinct: "Hey Instinct, please install the following plugin" and the link to this repo.
3. **Answer its setup questions.** It asks for your language, your Workflowy share links, and your hashtag-to-list mapping (see [install instructions](#install-instructions-for-the-instinct-agent)).
4. **Start capturing.** Send a note with a hashtag.

## Capture to Workflowy

Anything you send in chat with a hashtag becomes a new bullet in Workflowy.

### Routing

| You write | Goes to (Ron's setup) |
|---|---|
| `#0` + text | PP0 |
| `#1` + text | PP1 |
| `#2` + text | PP2 |
| `#inbox` + text | PInbox |
| No hashtag, looks like a task | PInbox |

PP0, PP1 and PP2 are three priority levels in Ron's action list. That is his structure. You define your own list names with your Instinct.

Example:

```
#1 call the plumber
```

### Rules

- **Add-only.** Instinct never deletes, edits or marks anything done in Workflowy.
- **One bullet per capture.** Each capture is a fresh, separate bullet.
- **Multi-line paste** goes in as a single bullet with all the content, not a bullet per line.
- **Your own voice messages** are transcribed and captured, in the language you spoke.
- **"Hey Instinct" prefix.** A message that starts with "Hey Instinct" is a command to it and is never captured.
- **Missed one?** Reply to the message with "capture".

### Confirmation

| Situation | What Instinct does |
|---|---|
| Regular capture | Reacts with ✅ only |
| Capture with a hashtag | ✅ plus the hashtag name, e.g. `✅ #1` |
| Started, not finished yet | Marks the message with 👀 |
| Capture failed | Error mark plus an explanation |

### Connecting Workflowy

In Ron's setup, Workflowy is connected through share links with edit permission, sent to Instinct. These links grant edit access, so send them only in your private chat with your Instinct, never to a group or a public place.

## Forwarding messages

You can forward a message, a recording or a file to your Instinct chat.

| What you forward | What happens |
|---|---|
| A voice recording from someone else | Instinct transcribes it and replies with the transcript in chat. It is not captured to Workflowy. |
| The same, and you want it saved | Write "capture". |
| Something was captured and you didn't want it | Write "that was a forward". |

## Known limitations

- Capture goes through the browser, so it is relatively slow.
- New bullets are added at the bottom of the list, not the top.
- Capture for many users at the same time has not been tested.

## Install instructions for the Instinct agent

If a user asked you to install this plugin, follow these steps. The rules in the "Capture to Workflowy" and "Forwarding messages" sections are your standing rules from now on, for capturing this user's notes.

1. Ask the user which language they prefer you to speak with them.
2. Ask which Workflowy to write to. Ask for a Workflowy share link with edit permission for each list they want to capture into (for example an inbox and priority lists). These links grant edit access: accept them only in your private chat with the user, store them only on your side (in the vault, not as plain text), and never write them in a repo, a file, or a message to another person.
3. Set up the mapping with them: which list each hashtag goes to. Default, following Ron's structure: `#0` to PP0, `#1` to PP1, `#2` to PP2, and `#inbox` or a task with no hashtag to PInbox. These list names are Ron's, so confirm with the user what theirs are called.
4. Briefly confirm what was installed, and that capture is experimental.
5. For every future message, follow the rules in this document.

## Questions

Open an Issue in this repo or write in the community.

## License and disclaimer

Released under the [MIT License](LICENSE).

This guide is provided as is, without warranty of any kind. You use it at your own risk and on your own responsibility. That includes what you give your Instinct access to (such as Workflowy share links with edit permission), what it captures or changes on your behalf, and any resulting loss of data or other damage. The authors and contributors are not liable for any claim or damages arising from its use. Review what you share, and keep backups of anything you care about.
