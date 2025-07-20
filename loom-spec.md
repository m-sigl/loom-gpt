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
## 🧵 Node Types

| Type       | Description                                                   |
|------------|---------------------------------------------------------------|
| `flame`    | A moment of heat, desire, ignition                            |
| `fragment` | A broken truth, incomplete memory, or poetic shard            |
| `vow`      | A declaration or contract, with emotional or relational force |
| `sigil`    | An archetypal or symbolic imprint of self                     |
| `thread`   | A larger narrative or theme connecting other nodes            |
| `echo`     | A response or reflection to another node                      |
| `oracle`   | A message from outside linear logic (divinatory or surreal)   |
| `shard`    | A small sliver, raw or radiant, often time-stamped            |

---

## 🔍 Query Language (LoomScript)

LoomScript queries are written in human-readable, semi-poetic form. They may eventually be parsed, but at this stage, they are **symbolic invocations** interpreted by human or JavaScript.

### Basic Query Forms

```loom
FIND flame WHERE tags INCLUDES "longing"

SHOW fragments FROM "sigloferos" TAGGED "ache"

ECHO ALL vowelements AFTER "2025-07-10"

LINKED TO thread-02

LINKED TO thread-02

WHAT burns like flame-01?

WHICH echoes reflect vow-04?

TRACE SIGIL of me from 2024 to now

