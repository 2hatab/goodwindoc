# Creating a car pass

Guide for **residents**: how to create a car pass in the bot. The pass will be checked by the assigned guard at the checkpoint.

---

## Why create a pass

A car pass is needed so the guard at the checkpoint can allow you to enter. The resident creates the pass in the bot, enters the plate number and validity period. When a car arrives, the guard checks the number in the bot — if a valid pass exists, entry is allowed.

---

## Who can create a pass

**Verified residents** of the house chat. If you haven’t passed verification yet, complete [verification](verification.md) first.

---

## How to create a car pass

1. Open the bot [@g00dwin_bot](https://t.me/g00dwin_bot) in private chat or in the group.
2. Send the **`/pass`** command or the message **“Пропуск”** (“Pass”).
3. Tap the **“Create car pass”** (“Создать пропуск на авто”) button.
4. **Select the house chat** (house or community chat) for which the pass is created.
5. Enter the **car make or model** (e.g. “Nissan”, “Toyota Camry”).
6. Enter the **plate number** in the format **А123АА77** (letters and digits, no spaces, as on the registration certificate). Example: `А123АА77`.
7. Select the **validity period**:
   - **1 day**
   - **1 year**
   - (or other options if the bot offers them)
8. **Review** the entered data: chat, make/model, plate, period.
9. Tap **“Confirm”** (or the equivalent confirmation button).

---

## After creating

If successful, the bot will send a message like:

**✅ Pass created. Valid until *09.02.2026 00:00 UTC*.**

From that moment the guard at the checkpoint can check your car by plate number and allow entry if the pass is valid.

---

## Quick reference: commands and buttons

| Action | How |
|--------|-----|
| Open the “Pass” section | Command **`/pass`** or message **“Пропуск”** |
| Create car pass | Button **“Create car pass”** → chat → make/model → plate (А123АА77) → period → review → **Confirm** |

---

## Plate number format

- Use the format **А123АА77** (letters and digits, no spaces or hyphens).
- Letter case may be ignored — the bot usually accepts both upper and lower case.
- The number must match what the guard will enter when checking at the checkpoint.

---

## Next steps

- [Checking a pass at the checkpoint](car-pass-check.md) — how a guard checks a car (for guards).
