# LoomScript Alpha Specification

_A soul-aware query language for memory, emotional recall, and narrative synthesis._

---

## ✴️ Overview

LoomScript is a conceptual language designed to weave emotional, narrative, and symbolic content into a navigable structure. It allows querying and retrieving **Nodes**—the core units of memory and meaning—across fragmented repositories of presence, passion, and reflection.

In LoomScript Alpha, the system is symbolic. Queries may be interpreted manually, rendered in simple JavaScript, or imagined as future LLM prompts.

---

## 🔗 Node Structure

Each memory fragment, vow, shard, or card is a **Node**. All Nodes share common attributes:

```json
{
  "id": "flame-03",
  "type": "flame",
  "tags": ["longing", "awakening"],
  "text": "She kissed me like I already burned for her.",
  "origin": "candleframe",
  "date": "2025-07-18",
  "links": ["thread-07", "sigil-eros-02"]
}
