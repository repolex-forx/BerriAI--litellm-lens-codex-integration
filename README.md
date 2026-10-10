# Repolex Knowledge Graph of BerriAI/litellm-lens-codex-integration

RDF knowledge graph data for [BerriAI/litellm-lens-codex-integration](https://github.com/BerriAI/litellm-lens-codex-integration), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download BerriAI/litellm-lens-codex-integration
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 69a89e531513605b56bec9960d55066bdf17a372
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 69a89e531513605b56bec9960d55066bdf17a372
│           └── chunk-001.nq.gz
├── blob
│   ├── 03a87577af52e48964b31fc31ed9ff99b8bea674.nq.gz
│   ├── 05383df1522498e63ed91fae36c6dfd1e41a4035.nq.gz
│   ├── 064a2a132308a1ae6c8e099ba270be27690a275b.nq.gz
│   ├── 08b4f2def48490661ce57d2054dcb77b23f45502.nq.gz
│   ├── 0b89ffac9eed4cc85fc99a4b1019f4d3aff13ae7.nq.gz
│   ├── 1ddaa7009caf22e01721f3ac05bcb556bf20e0d5.nq.gz
│   ├── 1eb59e3429bc9f4f311b32dcaf20b22050c5bc65.nq.gz
│   ├── 28ef210cc5454b20c5e707378ccfbbf3c194f2c3.nq.gz
│   ├── 2ba4ea1916ff3be57db9a27f09af5b20f5ef5c2c.nq.gz
│   ├── 397b219206effc46de74fc8c4eb36c101f2a65a4.nq.gz
│   ├── 415c6bc19c77785e2dd9b0a6507e366f4be4727d.nq.gz
│   ├── 4be472edd12eb362adc9c944295e0352cb931d58.nq.gz
│   ├── 4df00543457a57c3a7fbe39097d7f73180abc796.nq.gz
│   ├── 4e28416e104515e90fca4b69cc60d0c61fd15d61.nq.gz
│   ├── 5208b2cb2cd5159661d8ea9dd32900f3ad7e8111.nq.gz
│   ├── 578af5f13d700e2af0aebd9b0be24e034afa4e02.nq.gz
│   ├── 6d74c3b172de81c28bb15cd3378925c8dc0f9de5.nq.gz
│   ├── 7e236c486de56d920fc2d7d23982af326e519a57.nq.gz
│   ├── 800f387af264a87c50eb488ee475a141d2d4e9e3.nq.gz
│   ├── 84b5021341041e73720d192bd5a21d76d1e9e46a.nq.gz
│   ├── 8590e4b91328ca1c12a4b4c3b24ee395b55a9855.nq.gz
│   ├── 983108748217105ac76e701b1aa64a61b0f2f9bf.nq.gz
│   ├── 9a7b615f0d0622c568fa914b9d3535aa883109af.nq.gz
│   ├── 9d40e3b2645199913024ae1e88e0ce43afc3198e.nq.gz
│   ├── ab8dfe13b7a35ee730223b3cd6fc67d3e63f8ba8.nq.gz
│   ├── b3395c93a11e5fd2611f6147d8989bd7523165a2.nq.gz
│   ├── b515962806e1ebe2baaf03ab3fff5f4d150ecc56.nq.gz
│   ├── bff7637dafe93c09d007fbdfd955a9e9cc8d2116.nq.gz
│   ├── c0d95cecdf1058087290711b746a4f9126cc963e.nq.gz
│   ├── c1416fe1a34c330647f6b7f0a62b1fe951ae66e4.nq.gz
│   ├── c24dda1afc7b231965d49ae665defa434455f9f3.nq.gz
│   ├── c37089cff883cb93d7dec12fec06e094e48660e3.nq.gz
│   ├── c3c1906967828b5be422514047da19aeafb66daf.nq.gz
│   ├── c4ffbd43f68da5c81a49ce26ee1eb6618e15c196.nq.gz
│   ├── cc35be0a09859bd2c460ef4598c68292c1f02565.nq.gz
│   ├── cdd7ac6ee03f392d9e97a2ed6528b344b1c36b38.nq.gz
│   ├── d18e2320f7e0cd5f16f02828de2f5c653eac120d.nq.gz
│   ├── d407be0cc1bf023c7799471d154ecd7adf3889b9.nq.gz
│   ├── d5f440c749e512e72be50a481a13d9dc119d7f8a.nq.gz
│   ├── debd56d6bb9d6307558a2b8ccfcac90eb4099d75.nq.gz
│   ├── e466aa81afd1724e49f7dcec6c7f1de23d31bcd5.nq.gz
│   ├── e6ea5645e2cf0fc40bda962e3b1145b5127dfd5b.nq.gz
│   ├── efdcba377d486bde948f46f3695ef773befb0312.nq.gz
│   ├── f52f45a47ccebdc63c3383d57d294852cc23a935.nq.gz
│   ├── f8c94fea2bc121db7312f8a6099f6f1ce2d666e3.nq.gz
│   ├── f95c32e84832674cd7014e7967f465f598ef9999.nq.gz
│   ├── fbc8f1b56ddc25b6b73e697ef6fd3490f872cf59.nq.gz
│   ├── fd3e08034ac041e9bbc6f13e973920df9ea526ca.nq.gz
│   └── fd8ede15a80bf60f88aef54722ba9b04e35591ea.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 69a89e531513605b56bec9960d55066bdf17a372.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 56 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[BerriAI/litellm-lens-codex-integration](https://github.com/BerriAI/litellm-lens-codex-integration)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
