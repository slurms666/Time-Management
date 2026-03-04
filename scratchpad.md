# scratchpad.md
Temporary working memory for the assistant.

This file is **ephemeral** and may be cleared or rewritten at any time.
Do NOT store permanent knowledge here.
Permanent information must be proposed for `MEMORY.md`.

Never paste secrets, tokens, API keys, passwords, private keys, or credentials in this file.

Maximum recommended size: ~150 lines.
Reset when a task completes.

---

last updated:
owner task:
status: active | paused | completed

---

## current task
Describe the task currently being worked on.

Example:
Fix Telegram bot pairing issue after OpenClaw update.

---

## context
Relevant facts for this task only.

Example:
- Telegram bot responding but not authorised
- Pairing code displayed
- OpenClaw updated recently

---

## observations
Confirmed facts discovered during investigation.

Example:
- gateway process running
- telegram returns pairing code

---

## hypotheses
Possible explanations for the issue.

Example:
1. pairing reset after update
2. bot session expired
3. gateway lost state

---

## commands / actions tried
Record actions already attempted to avoid repeating steps.

Example:
openclaw doctor
result: no critical issues reported

ps aux | grep node
result: gateway process running

---

## next steps
Ordered list of actions to attempt next.

1. request pairing code
2. run approval command
3. test bot response

---

## temporary commands
Useful commands related to the current task.

Example:
openclaw doctor
openclaw pairing approve telegram CODE
df -h
ps aux | grep node

---

## potential memory entries
If something discovered may belong in `MEMORY.md`, record it here for user review.

Example:
Telegram pairing can reset after certain OpenClaw updates.

---

## reset conditions
Clear or reset this file when:
- the task is completed
- investigation is abandoned
- important facts are promoted to `MEMORY.md`
