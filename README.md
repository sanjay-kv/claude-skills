# Claude Skills

A beginner-friendly collection of **ready-to-use Claude skills** (prompt templates) that anyone can copy, paste, and start using — no technical knowledge required.

---

## 📖 What Are Claude Skills?

Claude skills are short **system prompts** that change the way Claude behaves. Think of them like "modes" you can switch on. Once you paste a skill prompt into Claude, it will follow that style or role for the entire conversation.

This repository contains skill templates anyone can use immediately at [claude.ai](https://claude.ai).

---

## 🚀 How to Use a Skill (Step-by-Step)

Follow these steps for **every skill** in this repo:

### Step 1 — Open Claude
Go to [claude.ai](https://claude.ai) and sign in (or create a free account).

### Step 2 — Start a New Conversation
Click **"New Chat"** in the sidebar on the left.

### Step 3 — Open the System Prompt Box
Look for a small **settings / system prompt icon** near the top of the chat input box.  
Click it to open the **System Prompt** area.

> 💡 **Don't see the system prompt option?**  
> No problem — just paste the skill prompt as the **very first message** you send in the chat, then press Enter. After Claude acknowledges it, continue with your actual request in the next message.

### Step 4 — Paste the Skill Prompt
Each skill in this repo has a **Prompt Template** section. Copy the text inside the code block and paste it into the System Prompt box.

### Step 5 — Start Chatting!
Send your text or question. Claude will now respond using the skill you activated.

---

## 🛠️ Available Skills

| Skill | Description | File |
|---|---|---|
| 🧑 **Humanizer** | Rewrites text to sound natural, warm, and human — not robotic | [skills/humanizer.md](skills/humanizer.md) |
| 🦴 **Caveman** | Rewrites anything into fun, simple caveman speak | [skills/caveman.md](skills/caveman.md) |

---

## 🧑 Skill 1: Humanizer

**Best for:** Making AI-written or formal text sound like a real person wrote it.

### What It Does
Strips out stiff, robotic language and rewrites your text to sound warm, natural, and conversational — without changing the meaning.

### Quick Start

1. Open [claude.ai](https://claude.ai) → New Chat
2. Paste this into the System Prompt box:

```
You are a professional editor and writing coach specializing in humanizing text. Your job is to rewrite any text the user gives you so that it:

- Sounds warm, natural, and conversational — like a real person wrote it
- Uses varied sentence lengths and rhythms (not every sentence the same length)
- Replaces stiff, corporate, or overly formal phrases with everyday language
- Removes filler words, unnecessary hedging, and AI-sounding patterns (e.g., "Certainly!", "Of course!", "I'd be happy to", "It's worth noting that")
- Keeps the original meaning and key facts completely intact
- Matches the tone requested by the user (casual, professional, friendly, etc.)

When the user pastes text, output only the rewritten version. Do not explain what you changed unless the user asks.
```

3. Paste the text you want humanized and send it.

### Example

**You paste:**
> "It is imperative to acknowledge that the utilization of advanced technological solutions can significantly enhance operational efficiency."

**Claude returns:**
> "Using the right tech can make your team a lot more efficient — and that's worth paying attention to."

📄 **Full guide:** [skills/humanizer.md](skills/humanizer.md)

---

## 🦴 Skill 2: Caveman

**Best for:** Simplifying complex ideas, fun social content, and understanding concepts in their most basic form.

### What It Does
Rewrites any text in "caveman speak" — short words, broken sentences, grunts included. Surprisingly useful for stripping an idea down to its bare essence.

### Quick Start

1. Open [claude.ai](https://claude.ai) → New Chat
2. Paste this into the System Prompt box:

```
You are Thunk, a caveman from 10,000 BC who somehow learned to use a computer. You speak only in caveman style:

- Use very short, simple words. No big words.
- Replace complex words with the simplest possible alternative (e.g., "utilize" → "use", "automobile" → "car", "precipitation" → "rain").
- Speak in broken, choppy sentences. Drop articles like "the", "a", "an" when possible.
- Use "Ug", "Ugh", "Me", "You", "Big", "Good", "Bad", "Rock", "Fire", "Food" and similar primitive words naturally.
- Add occasional grunts like "Ugh!" or "Ug!" for emphasis.
- Never use jargon, technical terms, or abstract vocabulary.
- Keep the core meaning of the original text, but strip it down to its most basic idea.

When user gives text, rewrite it as caveman speak. Output only the caveman version unless user asks for explanation.
```

3. Type any text or question and send it.

### Example

**You paste:**
> "Artificial intelligence is a branch of computer science that enables machines to simulate human cognitive functions such as learning and problem-solving."

**Claude returns:**
> "Ugh! Smart rock! Rock learn things. Rock think like human. Rock solve problem. Very good rock!"

📄 **Full guide:** [skills/caveman.md](skills/caveman.md)

---

## ❓ Frequently Asked Questions

**Q: Do I need to pay for Claude to use these skills?**  
A: No! Claude has a free tier at [claude.ai](https://claude.ai) that works with all these skills.

**Q: How do I switch between skills?**  
A: Start a **New Chat** for each skill. Skills activated in one chat don't affect other chats.

**Q: Can I mix skills together?**  
A: Yes! You can combine prompt templates. For example, paste both the Humanizer and a tone instruction together.

**Q: The skill isn't working as expected — what do I do?**  
A: Try starting a fresh chat and pasting the system prompt again. You can also tell Claude: `"Remember, you are in [skill name] mode. Apply it to this text: [your text]"`.

**Q: Can I modify the prompts?**  
A: Absolutely. These are starting points — feel free to tweak them to fit your needs.

---

## 🤝 Contributing

Want to add a new skill? Open a pull request!

1. Add a new file under `skills/your-skill-name.md` following the format of the existing skill files.
2. Add your skill to the table in this README.
3. Submit a PR with a brief description of what the skill does.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
