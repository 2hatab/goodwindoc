# Quick start: Telegram bot @g00dwin_bot

Short guide for chat administrators: how to add the bot [@g00dwin_bot](https://t.me/g00dwin_bot) to a group and set it up in a few steps.

## Requirements

- You are an administrator of a Telegram group or supergroup
- The group should be a **supergroup** (with message history and extended settings). For older groups this is usually already the case; for new groups Telegram will suggest upgrading to a supergroup when needed

## Step 1. Find the bot and tap «Start»

1. Open Telegram and go to search
2. Type **@g00dwin_bot** or open the link: [t.me/g00dwin_bot](https://t.me/g00dwin_bot)
3. Tap **Start** or send the bot the `/start` command

After that, the bot will show buttons — one of them is **«Add to chat»** («Добавить в чат»). This is Telegram’s standard way to add a bot to a group with the administrator permissions it needs.

## Step 2. Add the bot to the group via the button

1. Tap the **«Add to chat»** button in the chat with the bot
2. Select the group or supergroup you want to add the bot to
3. Confirm — Telegram will offer to grant the bot the administrator permissions it requests. Confirm them

The bot will be in the group with the required permissions. You don’t need to make it an administrator manually.

<details>
<summary>Added the bot manually (without the button)?</summary>

If you added the bot via «Add members» in the group, you need to grant administrator rights manually: group name → **Manage group** → **Administrators** → **Add administrator** → select @g00dwin_bot and enable the permissions you need (delete messages, pin messages, etc.).
</details>

## Step 3. Configure the house address (required)

After adding the bot to a group, you must link the group to a house address. This step is required.

1. Send the bot the **`/house_add`** command (in a private chat with the bot or in the group)
2. Select the **group** where you added the bot
3. Enter the **house name**
4. Enter the **house address**
5. Review the information and **confirm** to save

After you confirm, the house information is saved and the bot can work correctly in that group.

## Basic commands

| Command | Description |
|--------|-------------|
| `/start` | Start the bot, greeting |
| `/help` | List of commands and short help |
| `/house_add` | Add or set the house address for a group (required after adding the bot to the chat) |

The exact command list may be extended; the bot will show up-to-date info via `/help` in the group.

## FAQ

**The bot doesn’t reply in the group**  
- Make sure the bot is added to the group and has administrator rights  
- Check that the command starts with `/` (e.g. `/help`)

**Can I add the bot to a channel?**  
- This documentation focuses on groups and supergroups. Channel support is documented separately if available.

**How do I remove the bot from the group?**  
- Manage group → Members → find @g00dwin_bot → Remove from group. Or revoke administrator rights first, then remove the bot.

---

After these steps, the bot is ready to use in your group. Additional features and settings will be covered in later sections of the documentation.
