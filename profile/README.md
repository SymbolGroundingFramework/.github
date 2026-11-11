# Symbol Grounding Framework

**Structure for text and data — things you can query and govern afterwards.**

Four projects, one problem stated four ways: the world's knowledge arrives as prose, as exports, as dictionaries, and as rows. None of it is addressable. Each project below turns one of those forms into something with identity, provenance and a query surface — and none of them guesses when it cannot ground a claim.

---

## The projects

| | What it does |
|---|---|
| **[ledbetter-data-pump](https://github.com/SymbolGroundingFramework/ledbetter-data-pump)** | A YAML-driven data movement engine. Postgres → Parquet/CSV, partitioned workers, checkpointed so a killed job resumes without duplicating or losing rows. Rust. |
| **[prose-to-sql](https://github.com/SymbolGroundingFramework/prose-to-sql)** | A compiler from free prose into normalised SQL data. One clause becomes one claim, with its source span attached, so a correction names a row rather than a paragraph. |
| **[ledbetter-workbench](https://github.com/SymbolGroundingFramework/ledbetter-workbench)** | An ontology workbench. Files in, model out — find the ontology already present in your data, then govern it. Local-first; never connects, never holds credentials. |
| **[synapedia](https://github.com/SymbolGroundingFramework/synapedia)** | A public dictionary. Seven million senses bootstrapped from WordNet, Wiktionary and Wikipedia, each with a canonical address and a disambiguating microgloss. |

## The architecture behind them

**SGF — the Symbol Grounding Framework** — is the theory the projects serve: a claim is a *predication*, stored as one predicate at the hub, its participants on spokes, eight dimensions on the rim, and the source span beneath. One claim in one place, so a correction has something to name.

The book is **[THE SYNAPSE](https://github.com/SymbolGroundingFramework/sgf)** — 614 pages on why the sentence is the wrong unit of representation and what replaces it.

If you want the argument in five minutes rather than six hundred pages, start with the extraction, then the book:

- **[The Synapse — an extraction](https://github.com/SymbolGroundingFramework/sgf/blob/main/THE_SYNAPSE.md)**
- **[THE SYNAPSE (PDF)](https://github.com/SymbolGroundingFramework/sgf/blob/main/books/SYNAPSE.pdf)**
- **[This Architecture Is Yours](https://github.com/SymbolGroundingFramework/sgf/blob/main/THIS_ARCHITECTURE_IS_YOURS.md)** — what is public domain, what is licensed, and why

## Licensing

The architecture is dedicated to the public domain. Reference code is Apache 2.0 or MIT per repository. The books and prose remain the author's.

---

*James Lee Stäkelum*
