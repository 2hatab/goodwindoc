# Checking a pass at the checkpoint

Guide for **guards**: how to check a car when it arrives at the checkpoint. If the car has a valid pass created by a resident in the bot, entry is allowed.

---

## Who can check passes

Only users **assigned as guards** by the chat administrator. If you haven’t received an invitation and the message “You have been assigned as a guard”, contact the house chat administrator — they need to [create an invitation](guard-invite.md) and assign you as a guard.

---

## How to check a car on entry

1. When a car arrives at the checkpoint, open the bot [@g00dwin_bot](https://t.me/g00dwin_bot).
2. Send the **`/checkpass`** command or the message **“Проверить авто”** (“Check car”).
3. Enter the **plate number** in the format **А123АА77** (as on the pass, no spaces). Example: `А123АА77`.
   - *Photo recognition of the plate may be added later.*
4. Select the **house/community chat** for which you are assigned as a guard.

---

## Bot replies

### Pass found and valid

If a pass for this car exists and is within the validity period, the bot will send a message like:

**✅ Entry allowed.**

🎫 Valid until 09.02.2026 00:00 UTC  

🚗 Nissan (A***AA 77)

You can allow entry.

### Pass not found or invalid

If there is no pass with that plate, the pass has expired, or the wrong chat was selected, the bot will say that entry is not allowed (or pass not found). In that case follow your checkpoint rules (deny entry or ask the resident/administrator).

---

## Quick reference: commands and buttons

| Action | How |
|--------|-----|
| Open pass check | Command **`/checkpass`** or message **“Проверить авто”** |
| Check car | Enter plate in format **А123АА77** → select house/community chat → get bot reply (entry allowed / not allowed) |

---

## Plate format when checking

- Enter the plate in the format **А123АА77** (no spaces or hyphens), as when the resident created the pass.
- In the reply the bot may show the plate partially masked (e.g. A***AA 77) for privacy.

---

## Related sections

- [Assigning a guard](guard-invite.md) — how an administrator creates an invitation and assigns a guard.
- [Creating a car pass](car-pass-create.md) — how a resident creates a car pass.
