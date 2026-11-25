<p align="center">
  <img src="assets/hero.png" alt="Octohold: a friendly octopus holding a sticky note, an envelope, a lightbulb and other loose thoughts, and handing you one card that says ONE STEP" width="100%">
</p>

<h1 align="center">🐙 Octohold</h1>
<p align="center"><b>Dump it all. I'll hold the rest.</b><br>
A free AI skill for busy, scattered, ADHD brains.</p>

<p align="center">
  <img alt="Free" src="https://img.shields.io/badge/price-free-7FD6C2">
  <img alt="MIT license" src="https://img.shields.io/badge/license-MIT-FF7A59">
  <img alt="No scripts" src="https://img.shields.io/badge/scripts-none-13233A">
</p>

---

## ⚡ 10-second version

| | |
|---|---|
| 🗣️ **1. Dump** | Type or say *everything* in your head. Any order. Messy is fine. |
| 🪞 **2. Mirror** | Claude plays it back, sorted, on **one screen**. |
| ✅ **3. Check** | *"Did I get this right?"* Fix anything. Nothing gets planned until you say yes. |
| 👣 **4. One step** | You get **one** small step. Octohold holds the rest. |

<p align="center"><img src="assets/how-it-works.png" alt="Four panels: 1 Dump, 2 Mirror, 3 Check, 4 One step" width="100%"></p>

---

## 📦 Install (30 seconds)

### 🥇 Easiest: paste this into Claude Code

```text
Install this skill: https://github.com/Chinchuan24/octohold
```

That's it. Claude does the rest. ✅

### 🛠️ Or run one command yourself

```bash
git clone https://github.com/Chinchuan24/octohold ~/.claude/skills/octohold
```

Then restart Claude Code.

### 💬 Claude app (web or desktop)

1. Download **`octohold.zip`** from [Releases](https://github.com/Chinchuan24/octohold/releases/latest)
2. In Claude, open **Settings → Skills**
3. Upload the ZIP

### 🤖 Other AI tools (Codex, Cursor, …)

Copy `SKILL.md` into that tool's skills folder, for example `~/.agents/skills/octohold/`.

> ✅ **Nothing to block it.** No plugin, no scripts, no dependencies, no internet calls. It's one text file.

---

## 🎬 Use it

Just start dumping. Any of these will wake it up:

- *"brain dump"*
- *"let me get this out of my head…"*
- a long, rambly voice note
- or type **`/octohold`**

---

## 👀 What it looks like

> **You:** ok rent due friday haven't moved money. reply to Priya re offsite. dentist keep forgetting. half-written blog post. maybe learn pottery. honestly feel behind on everything

> **Octohold:**
> 👉 **Check I heard you right.**
> ☑️ Move rent money (due Fri) · Reply to Priya · Book dentist
> 📁 Blog post (half-written)
> 💡 Learn pottery
> 💭 Feeling behind on everything
> 👂 "Priya", or did I mishear the name?
> ✅ yes, go · ✏️ fix something

> **You:** yes but it's Maya not Priya

> **Octohold:**
> 👉 **Open your banking app and move the rent money.** It's the only hard deadline.
> Fixed: reply to **Maya**.
> 📥 Holding the rest. Pottery stays an idea, not a task.

<p align="center"><img src="assets/before-after.png" alt="Before: a tangled cloud of thoughts. After: one tidy card." width="100%"></p>

---

## 💛 Why it feels different

| Octohold… | So you… |
|---|---|
| 🪞 checks it understood **before** planning | never get a plan built on a misunderstanding |
| 👣 shows **one** step, not a list of 20 | can actually start |
| 💭 keeps feelings as feelings | don't get "feel behind" turned into a task |
| 👂 flags words voice typing may have misheard | don't email the wrong person |
| ✂️ shrinks a step once, then tries a new way | don't get stuck in "too big" |
| ⏸️ stops all pressure when you say "pause" | can just breathe |

---

## 🔒 What it will never do

- ❌ Send, post or schedule anything
- ❌ Promise reminders or remember chats it can't see
- ✅ Only writes **one** file per dump: `~/brain-dumps/<date>.md`, so you can come back later

---

## 🙏 Credits

Built on two great MIT skills:
- [brain-dump](https://github.com/TheCraigHewitt/skills) by Craig Hewitt, for sorting
- [adhd-brain-dump](https://github.com/yuchenbigpen1/donna-skills) by Donna, for one step at a time

Details in [`NOTICE.md`](NOTICE.md). **MIT license: free forever, for everyone.** 🐙

---

<details>
<summary>🤖 <b>For AI assistants installing this skill</b></summary>

If someone pasted this repo link and asked you to install it:

1. If `~/.claude/skills/octohold` does not exist, run:
   `git clone https://github.com/Chinchuan24/octohold ~/.claude/skills/octohold`
2. If it already exists, update it instead:
   `git -C ~/.claude/skills/octohold pull --ff-only`
3. Tell them: "✅ Octohold installed. Restart Claude Code, then say *brain dump* to try it."

No other steps. No scripts to run.
</details>
