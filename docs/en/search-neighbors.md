# Search neighbors by apartment number

Find the owner of a property unit (apartment) and send them a private message. Available **in the house chat** with the bot and only to **verified users** (residents).

---

## How it works

You write a message in the chat in the format **`#number message text`**. The bot:

1. Checks that you are **verified** in this chat (you are a resident).
2. Searches among verified residents for those whose profile has this number (apartment, parking spot, storage unit, etc.).
3. Checks whether those residents are **in this chat** and verified in it.
4. Tries to **send them a private message** with the text you wrote after `#number`.

The neighbor’s apartment (or other object) number is **not shown** in the chat — only your request is visible. The message is sent to the neighbor in private by the bot (indicating that it’s a request from the house chat).

---

## Example

In the house chat you write:

```
#404 please contact me urgently
```

or:

```
#12 Hi, is there a leak from your apartment? We're in 11.
```

The bot will process the request and reply in the chat with one of the outcomes below.

---

## Bot replies in the chat

After processing your message, the bot will reply in the same chat:

| Situation | Bot reply |
|-----------|-----------|
| **Neighbors found, messages sent** | Says it found neighbors and sent them the messages. |
| **Neighbors exist, but message could not be sent** | Says there are neighbors with that number in the chat but the bot couldn’t send them the message (e.g. user doesn’t accept messages from non-contacts). |
| **No neighbors with that number** | Says there are no neighbors with that number in the chat. |

Exact wording may vary — the bot will state the result clearly.

---

## Usage rules

1. **Format:** `#number` at the start of the message, then a space and the text. The number is the one you’re searching by (apartment, parking, storage, etc.) as registered at verification.
2. **Where to write:** only in the **house chat** where the bot is added and where you passed verification.
3. **Who can use it:** only **verified residents** of that chat. If you haven’t passed verification yet, the bot won’t process the request — complete [verification](verification.md) first.
4. **One request per message:** use one `#number` per message. For multiple numbers, send separate messages or ask in the chat / from the bot.

---

## FAQ

**The bot doesn’t react to my message with #number.**  
Make sure you’ve passed verification in this chat and have resident status. Check the format: `#number` at the start, then a space and the message text.

**Can I search by car or parking number?**  
Yes, if neighbors specified that at verification and it’s linked to their profile in this chat. Search uses the numbers/objects that verified residents have in their profile for this chat.

**The neighbor didn’t get the message — what to do?**  
The bot will say in the chat that it couldn’t send the message (e.g. “there are neighbors in the chat but the bot couldn’t send them the message”). Possible reasons: the user doesn’t accept messages from non-contacts, left the chat, or blocked the bot. You can contact them another way if you have their contact, or ask in the general chat to get in touch.

**Who can see that I searched for a neighbor by number?**  
The chat shows your message with `#number` and the bot’s reply. The neighbor only sees the private message from the bot (your apartment number isn’t shown in the chat unless you included it in the text).
