# 🐙 The Corpus of Cthulhu

> *"That is not dead which can eternal lie,  
> And with strange aeons even data may arise..."*

A curated collection of the complete works of **H.P. Lovecraft**, painstakingly transcribed into plaintext for use in machine learning rituals, natural language incantations, and other unspeakable experiments.

## 🧠 What Madness Lies Within?

The **Corpus of Cthulhu** is a raw and unchunked digital grimoire of Lovecraft’s writings—unclean, unstructured, and whispering to those who dare fine-tune language models on it. These texts have been left in their natural, unknowable state to allow maximum flexibility for:

- 🧵 Text classification and thematic thread-pulling  
- 🐍 NLP pipelines and sequence modeling  
- 🧠 Fine-tuning LLMs for eerie eloquence  
- 📊 Stylometric or linguistic analysis  
- 🐙 Generative storytelling soaked in cosmic dread  
- ⚗️ Experimental procedures best left unexplained

No tokenization, no embedding, no safety seals. You have been warned.

## 📚 Contents of the Vault

Inside the `txts/` directory slumbers a collection of `.txt` files, each named like an archival specimen (`The_Call_of_Cthulhu_Lovecraft.txt`) and containing:

- Core **Cthulhu Mythos** stories (*The Dunwich Horror*, *The Shadow over Innsmouth*, etc.)
- **Dream Cycle** works (*The Dream-Quest of Unknown Kadath*, etc.)
- Juvenilia, essays, letters, and eldritch oddities
- Select collaborations and ghostwritten tales (when HPL’s presence can be psychically confirmed)

> ☢️ **Warning:** Some texts may induce madness, existential unease, or neural network overfitting.

## 📄 Format

- Plaintext (UTF-8)  
- Minimal formatting or metadata  
- No footnotes, inline tags, or protective glyphs

Each file typically begins with a title and, if known, a date of composition. Consider each one a raw relic for your preprocessing rituals.

## 🔧 Usage

This corpus is for **research**, **education**, and **experimental horrors** only. Lovecraft’s writings are mostly public domain in the U.S., but always verify with your local grimoires of law.

#### Examples from the Cult Codex:

```bash
# Glimpse the void
head -n 20 txts/The_Dunwich_Horror-Lovecraft.txt

# Count the words. Beware the numbers.
wc -w txts/*.txt
# Load one of the blasphemous texts
from pathlib import Path

eldritch_texts = list(Path("txts").glob("*.txt"))
words_of_madness = eldritch_texts[0].read_text(encoding="utf-8")
```
## 👁️‍🗨️ Project Philosophy

Originally assembled in the candlelit halls of grad school, this corpus exists to further the computational study of horror, language, and all things tentacled. It is a tool, a gateway, a black mirror through which neural architectures may glimpse the ineffable.

Whether you're building a GPT to speak like an ancient alien god, or tracing stylistic features across unnameable centuries, this corpus may serve you well… if you survive the encounter.

## 🕯️ Attribution & Disclaimer

Texts sourced from the public domain and lightly normalized for readability. This is not a critical edition—errors and archaic spellings may remain. Contributions welcome from other brave cultists.

If you use this corpus in a project, citing or linking back is appreciated. It strengthens the arcane connection between realms.

## 🦑 Ph’nglui mglw’nafh AI Cthulhu R’lyeh wgah’nagl fhtagn...
