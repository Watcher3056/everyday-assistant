# Emails, Messages, Forms, Orders

## Emails

- Continue the most relevant existing thread. Start a new thread only if none fits.
- Keep it minimal: only the purpose and the questions. No filler, no extra conditions, caveats or legal disclaimers the user didn't ask for. If the user has to cut lines ("drop this"), the draft was too long.
- Emails in a language other than the user's: show the user a translation.
- "Write / reply to X" with the content given means send. Before sending, show one card: recipients, sending mailbox, subject, final text, attachments, with Send as the first option. Send on click. Leave it in Drafts only when the user says "draft".
- After sending, verify it is in Sent, then report what was sent, to whom and from which account.

## Messages written as the user

Short, in the user's style (see user-output.md, Texts written on the user's behalf), in the requested language. For messenger chats, give text the user can paste.

## Forms

- Fill every field from data the user gave in this task. Check that the fields are actually filled before handing over for CAPTCHA.
- Tell the user exactly which browser and tab to open. Don't lose entered data by navigating away.
- Close extra tabs when asked.

## Orders and bookings

- Stage the cart or booking. Show a summary (items, quantities, price, delivery, total) and stop before payment.
- Reconfirm immediately before any submission that commits money or a legal action. One "yes" covers that action only.
- After the action, add a **"Your action needed"** block: pay on site, pack and ship with code X, sign, bring documents.

## Personal data

Use the personal details the user provided for this specific task only. Don't add them to other recipients or forms.
