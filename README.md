# Repolex Knowledge Graph of KelvinJin/AnimatedCollectionViewLayout

RDF knowledge graph data for [KelvinJin/AnimatedCollectionViewLayout](https://github.com/KelvinJin/AnimatedCollectionViewLayout), parsed by [repolex](https://repolex.ai).

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
rlex download KelvinJin/AnimatedCollectionViewLayout
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f6d163d761f9cd8af16eee1a65558614b396a874
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f6d163d761f9cd8af16eee1a65558614b396a874
│           └── chunk-001.nq.gz
├── blob
│   ├── 0c3a43f1aba7ebf62940548eb72e048ec7873420.nq.gz
│   ├── 0d39acea8a9a3441f87cd58b4e887ffeb7a96fa7.nq.gz
│   ├── 11a386f2342cae8b046c5b2d9df792774c797fca.nq.gz
│   ├── 1844004040e62fe19564ff85bddc5787565e1b52.nq.gz
│   ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
│   ├── 1996d2c7f4363f72b0597ea3127433e9b31c7370.nq.gz
│   ├── 1a97d73f170a4cc9c53526241449c6e8bbd7465c.nq.gz
│   ├── 26409cd1a70ac14a91a33e1444cd386e5218874a.nq.gz
│   ├── 2954047f23ec8caf758c06c03d4d9c9bd8509650.nq.gz
│   ├── 2cb9592fa595413ad56229add66ebb8687511f2a.nq.gz
│   ├── 2fe30a19c41fb0a978f2f4f64006e8fe34996ce1.nq.gz
│   ├── 355cd27ad30697e0ecd25208fe162ce8e31f494c.nq.gz
│   ├── 369564bdc1c5ed0eaa89a73baeeca4183602541a.nq.gz
│   ├── 376536593d4770298b7ca988411a4b212353ba4b.nq.gz
│   ├── 37e4fb38e6bc0d184e71596555e5a5b3a0b3350c.nq.gz
│   ├── 4d17f1d7901595781acc84185481e01e2bacff6b.nq.gz
│   ├── 559e7b411e3e69f72906709131e0159702549711.nq.gz
│   ├── 57084999dcc5fb0fb06678f4528a43be3f59982f.nq.gz
│   ├── 57981ed921c6eca9b3bce08e5a7f4479982a30a4.nq.gz
│   ├── 5926659a78e0c18a258b83dbfb0559ea5c2fdcff.nq.gz
│   ├── 5d9242d07b6ece998486a318327c10a6b5985a80.nq.gz
│   ├── 5df23e41de94abfad77c9b84629dfc7166f3a88c.nq.gz
│   ├── 5edac854b5e29f675741deda41348c4401d0c780.nq.gz
│   ├── 6c6c23c43adc88621ce3abfbd1585c8792bd165c.nq.gz
│   ├── 6cea53cf03c9dc162c68a69440b30d02cfcc1eed.nq.gz
│   ├── 733c4baa45007cd00c5ba4d0fa1f351edccacb7d.nq.gz
│   ├── 7bf7fade2ff5590f01c97e14f68c9d7ead60a9e1.nq.gz
│   ├── 86b112023b3bbbb0917e7af0b53028b6981c5610.nq.gz
│   ├── 919434a6254f0e9651f402737811be6634a03e9c.nq.gz
│   ├── ac79fbb6ee769edbc1f8164e58c4b9a66a21c42f.nq.gz
│   ├── bbecf3954c2eba0cbd77d25d19acccf1951ec871.nq.gz
│   ├── bfe77a2a8d486e6d7dfad8b3513c282b734005b1.nq.gz
│   ├── c9257fbdbee87018d8b9ff30fa63e95957be480c.nq.gz
│   ├── c9ffeacb8d3d59d80f32eb5d8a383a8504d164ce.nq.gz
│   ├── cb3daf263c8e5bf9063ab3be607ed60eb51fe79d.nq.gz
│   ├── cd626ad4666ede2111cd263e097fc5938598881f.nq.gz
│   ├── d0524738680109d9f0ca001dad7c9bbf563e898e.nq.gz
│   ├── d45dc7f545773acf4111d2392507c30d531b8bd9.nq.gz
│   ├── d889c70a4136533bd02dc38dfb4a1a4c0d5c4de4.nq.gz
│   ├── e3da824057252a1f98708a3299855f2e9a3dece1.nq.gz
│   ├── e6afe75b08d4c7815107e20a796bde13c9125820.nq.gz
│   ├── f607246c89d6093afe59cd77d4c790d7fdde6df3.nq.gz
│   ├── fbe1e6b31411578a3c89047fa396976ec32c013d.nq.gz
│   └── fdf3f97d1b6e9d8d29bb69a88c4d89ca752bd937.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f6d163d761f9cd8af16eee1a65558614b396a874.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 52 files
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

[KelvinJin/AnimatedCollectionViewLayout](https://github.com/KelvinJin/AnimatedCollectionViewLayout)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
