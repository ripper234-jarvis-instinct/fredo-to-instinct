# מ-Fredo ל-Instinct

מדריך והתקנה לחברי קהילת Fredo שעוברים ל-Instinct, על בסיס מה ש-Ron הגדיר ובדק אצלו בפועל.

> סטטוס: ניסיוני. זה עובד אצל Ron, אבל לכידת הפתקים ל-Workflowy עדיין איטית ולפעמים טועה. אם משהו לא עובד, זה לא אתם.

## בקצרה (לאדם)


A guide and install instructions for Fredo Community members moving to Instinct, based on what Ron set up and tested in his own use.

> Status: experimental. It works for Ron, but capturing notes into Workflowy is still slow and sometimes makes mistakes. If something doesn't work, it's not you.

## TL;DR (for humans)

1. Join Instinct with an invite (see below).
2. Send your Instinct on WhatsApp: "Hey Instinct, please install the following plugin" + the link to this repo.
3. Instinct reads this guide, asks you a few setup questions, and starts capturing notes into Workflowy by hashtag: `#0`, `#1`, `#2` and `#inbox`.
4. Forward messages to your Instinct, and it transcribes and captures them according to the rules below.

## Install instructions for Instinct (for the agent)

If a user asked you to install this plugin, follow these steps. The rules in the "Capture" and "Forwarding messages" sections are your standing rules from now on, for capturing this user's notes.

1. Ask the user which language they prefer you to speak with them.
2. Ask which Workflowy to write to. Ask for a Workflowy share link with edit permission for each list they want to capture into (for example an inbox and priority lists). These links grant edit access: accept them only in your private chat with the user, store them only on your side (in the vault, not as plain text), and never write them in a repo, a file, or a message to another person.
3. Set up the mapping with them: which list each hashtag goes to. Default, following Ron's structure: `#0` to PP0, `#1` to PP1, `#2` to PP2, and `#inbox` or a task with no hashtag to PInbox. These list names are Ron's, so confirm with the user what theirs are called.
4. Briefly confirm what was installed, and that capture is experimental.
5. For every future message, follow the rules below.

## What is Instinct

Instinct is a personal assistant you talk to in chat (for example on WhatsApp). It connects to your email, calendar and files, and does tasks for you. You can write to it or send a voice message, in Hebrew or English.

## 1. Joining

Joining Instinct is by invite. (TBD: Ron to fill in the join and invite details here.) After you sign up, you talk to your Instinct in chat.

## 2. Capture to Workflowy

Anything you send in chat with a hashtag becomes a new bullet in Workflowy.

| What you write | Where it goes (Ron's setup) |
|---|---|
| `#0` + text | PP0 |
| `#1` + text | PP1 |
| `#2` + text | PP2 |
| `#inbox` | PInbox |
| No hashtag, and it looks like a task | PInbox |

PP0, PP1 and PP2 are three priority levels in Ron's action list. That is his structure. You define your own list names with your Instinct.

Example:

```
#1 call the plumber
```

### How capture works

- Add-only. Instinct does not delete, edit or mark anything as done in Workflowy.
- Each capture goes in as a new, separate bullet.
- A multi-line paste goes in as a single bullet with all the content, not a bullet per line.
- A voice message you record yourself is transcribed and captured, in the language you spoke.
- A message that starts with "Hey Instinct" is a command to it and is not captured.
- If a message wasn't captured the way you wanted, reply to it with "capture".

### Confirmation

- Regular capture: Instinct reacts with ✅ only.
- Capture with a hashtag: ✅ and the hashtag name, for example `✅ #1`.
- If Instinct started something and hasn't finished, it marks the message with 👀.
- If a capture failed, you get an error mark and an explanation.

### Connecting to Workflowy

In Ron's setup, the connection uses Workflowy share links with edit permission, sent to Instinct. These links grant edit access, so send them only in your private chat with your Instinct, never to a group or a public place.

Known limitations right now:

- Capture goes through the browser, so it is relatively slow.
- New bullets are added at the bottom of the list, not the top.
- Capture for many users at the same time has not been tested.

## 3. Forwarding messages

You can forward a message, a recording or a file to your Instinct chat.

- A voice recording you forwarded from someone else: Instinct transcribes it and returns the transcript in chat, and does not capture it to Workflowy.
- Want to save it? Write "capture".
- The other way around: if something was captured and you didn't want it, write "that was a forward".

## Questions

Open an Issue in this repo or write in the community.
