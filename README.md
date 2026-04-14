# Repolex Knowledge Graph of aws/constructs

RDF knowledge graph data for [aws/constructs](https://github.com/aws/constructs), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download aws/constructs
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f1fd2869f9283dc52f3985856032f309b8002082
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── f1fd2869f9283dc52f3985856032f309b8002082.nq.gz
│   └── repolex
│       └── f1fd2869f9283dc52f3985856032f309b8002082
│           └── chunk-001.nq.gz
├── blob
│   ├── 0437cce841e28c001fee080faa17f31c424c1679.nq.gz
│   ├── 08960dd9f3d8827f7611d156963f98d1da49205f.nq.gz
│   ├── 0901666309875c19015f6048a8b6c8f925e513d4.nq.gz
│   ├── 0ed5c5fea8c016274d5f010ea3b482e6f4776e5d.nq.gz
│   ├── 0fca886ebd6523ff6f724583f9d144ee79fbc1ba.nq.gz
│   ├── 0ff66b25dbba5bca64da18270fd78d9c8aea182f.nq.gz
│   ├── 11d479bcaed65be96a75adb4dc2f8c98829291ee.nq.gz
│   ├── 17f4d807ede282cd0c316775f8a8f26e11f59789.nq.gz
│   ├── 1fbf87fbfdeceba890b190ecae266b0945255ade.nq.gz
│   ├── 26ae47e0eed5c07fd94b0b1d078497edce29292d.nq.gz
│   ├── 2bbc23d2e9d232a81edd1f9787cdac610392f0da.nq.gz
│   ├── 36de130c5b7f283589ef4d43b1af9d6263f33f82.nq.gz
│   ├── 47c74a79cf4174da458baec65aebeb2c41872603.nq.gz
│   ├── 48eb4b91ec12d668394975dad7f350742ee74635.nq.gz
│   ├── 534bc2ac387be5f162dc5bbaeea79f2b8644d68b.nq.gz
│   ├── 591259004216b3b4cfc9d90950c62cc37fe23ed1.nq.gz
│   ├── 592bca12b8ceba669980cfe80852134a5dc8a61a.nq.gz
│   ├── 5a2de2566a0e3016d2a11a79e6b404859ca4e505.nq.gz
│   ├── 5b627cfa60b5313da2c7df81aab2340225c2329f.nq.gz
│   ├── 64768fa28e56f016466b14f167a4c97ada7d9426.nq.gz
│   ├── 7682cdee000ca6428969f6b796e0550eaae04f8e.nq.gz
│   ├── 7b7d70f203c95b9833b1bccfa5b2de4860e4381d.nq.gz
│   ├── 8061456f11896726ae8fdcb2384d954505ecd349.nq.gz
│   ├── 830e1e9665c5835a3023f48e17b96e9b664c935d.nq.gz
│   ├── 93530c8aaf9eb904f9cef08183d2dcbfc39cb791.nq.gz
│   ├── 9cd8483e59978d64e97524a980ba7a6bc609354d.nq.gz
│   ├── a3ca6ae221779838d7d17921b9d3e20fdd5d3c83.nq.gz
│   ├── acaf102cdd7c18f0a31d46d7955d65cc8ce8d84f.nq.gz
│   ├── b296ae2ee7bc4694833a79e608400196d3ca4a69.nq.gz
│   ├── c682a1e68c028ce3296976ad0b3cbcb74d5df8a1.nq.gz
│   ├── ce7009e28da2515d18c744cba84092c3de399c9a.nq.gz
│   ├── d1b38cdb08d2d489b7e63dd06c474cf013952200.nq.gz
│   ├── d41c92d4498592713ae95f613c4ecda9d83e7f5a.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d797c6a6abde0e8d6a243be2a9c2628f79f19431.nq.gz
│   ├── da806b976d59deadb0a62728294362ccf5f8ba33.nq.gz
│   ├── db228de6c64ee1d0379317961a03e0a4be1213a1.nq.gz
│   ├── e9b3ebf1bd0eb3831b0033385f26a3431ccb3449.nq.gz
│   ├── f4360fe8397f689057b4d22287ef6bfebb2fb8af.nq.gz
│   ├── f7a04a2b5bbad52924917968246c70967373ad9d.nq.gz
│   └── fe73ebfd389d9fbc51e7feb1d1b598497916e0c9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── f1fd2869f9283dc52f3985856032f309b8002082.nq.gz
├── filetree
│   └── f1fd2869f9283dc52f3985856032f309b8002082.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 51 files
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

## Source repository

[aws/constructs](https://github.com/aws/constructs)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
