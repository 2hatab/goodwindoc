# Assigning a guard

Guide for **chat administrators**: how to create an invitation and assign a Telegram user as a guard for the house chat. The guard will be able to check car passes at the checkpoint.

---

## Why assign a guard

A guard is a user who, at the checkpoint, checks whether a car is allowed to enter. For a user to be able to check passes in the bot, an administrator must **create an invitation** and send it to the future guard. After accepting the invitation, the user will get the message “You have been assigned as a guard” and can use [pass verification](car-pass-check.md).

---

## How to create a guard invitation

1. Open the bot [@g00dwin_bot](https://t.me/g00dwin_bot) (in private chat or in the group).
2. Send the **`/guard`** command or the message **“Охрана”** (“Guard”).
3. Tap the **“Create invitation”** (“Создать приглашение”) button.
4. Select the **chat** (house chat or community chat) to which the guard will be attached.
5. The bot will create a **one-time invitation link**.

---

## How to send the invitation to a user

- **Option 1:** Tap the created link. An interface will open where you can **select a Telegram user** — they will receive the invitation to become a guard.
- **Option 2:** Copy the link and send it to the future guard (in private or in a chat). The user follows the link and accepts the invitation.

After following the link and successfully accepting the invitation, the user will receive a message from the bot: **“You have been assigned as a guard”**. From that moment they can check car passes for the selected chat (house/community).

---

## Quick reference: commands and buttons

| Action | How |
|--------|-----|
| Open the “Guard” section | Command **`/guard`** or message **“Охрана”** |
| Create invitation | Button **“Create invitation”** → select chat → get one-time link |
| Assign guard | Follow link → select user (or send link to them) → user follows link and gets “You have been assigned as a guard” |

---

## Next steps

- [Creating a car pass](car-pass-create.md) — how a resident creates a pass for a car.
- [Checking a pass at the checkpoint](car-pass-check.md) — how a guard checks a car on entry.
