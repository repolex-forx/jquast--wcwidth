# Repolex Knowledge Graph of jquast/wcwidth

RDF knowledge graph data for [jquast/wcwidth](https://github.com/jquast/wcwidth), parsed by [repolex](https://repolex.ai).

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
lexq download jquast/wcwidth
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── blob
│   ├── 0da99b018c739af5031e0bf678150b631fcb766e.nq.gz
│   ├── 16163c8d886a39d5eac49d4965d6cb614864c574.nq.gz
│   ├── 1df34b19fb2caa1998f59cc6197738e6b89042f6.nq.gz
│   ├── 312937597ffcc96cc0b1d1afdd4425f9e3c4c4f2.nq.gz
│   ├── 490dbd61f5b5f3b5060c9a692f901a34575331d8.nq.gz
│   ├── 4a5af71c368e49d225199fba107ff7e200c4a8af.nq.gz
│   ├── 576a48d53d78128c31138d6d309d7b51d7dab5f6.nq.gz
│   ├── 696ea2cd11cedd896020e0dabb5dc70d0ef38526.nq.gz
│   ├── 69b0d8f8b3df0f97d7d81002142174a482984c73.nq.gz
│   ├── 8c7a7f462f3a6b2da1acc37e34ae7019d99e8076.nq.gz
│   ├── 94eccfc9fb2aab21df19d50ca39b9df2b65fce84.nq.gz
│   ├── 9b9e018f4824b3c2d52405ca7cc6d03851b6b489.nq.gz
│   ├── a41a93143c8392d5d5d22abab922c68fd1d1661a.nq.gz
│   ├── ad521f63828f678cde8a27e40b925402614f2a73.nq.gz
│   ├── b2daf89c984041f08e678d0c8fe5d40104bc90e4.nq.gz
│   ├── bbc936cb5e9ab91df2a8758656f762f22cc4eced.nq.gz
│   ├── be1f51c4cd23d15b23f2ffde649ba7cc18d1488d.nq.gz
│   ├── c0c7a2193b94b5b538171c6dab6000958d08a2eb.nq.gz
│   └── d747e1ed2734b0d66013685a4b899976a053a71c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   ├── 5b8809074cc41130be9ead0c68f9081747915149.nq.gz
│   └── df21a5713e4416ee35927c0bdd4405ea55384c3c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

8 directories, 26 files
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

[jquast/wcwidth](https://github.com/jquast/wcwidth)

---
*Parsed on 2026-03-23 by [repolex](https://repolex.ai)*
