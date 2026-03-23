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
├── aggregate
│   ├── ast
│   │   ├── 26a2dfed510a3aec99f4efef141de41bd6f8c81b.nq.gz
│   │   ├── 3b1a268716cfa2e968881b5dd35b26210b9957ca.nq.gz
│   │   ├── 55a3a771ef4cc1f28a856f03768716d220ef6f97.nq.gz
│   │   ├── 5b8809074cc41130be9ead0c68f9081747915149.nq.gz
│   │   ├── b217ed4eb06e3a2a523a995f85b4c84b4d17df62.nq.gz
│   │   ├── c71459ea91af86f3bbcdac2c8ed5e7773da2d848.nq.gz
│   │   ├── df21a5713e4416ee35927c0bdd4405ea55384c3c.nq.gz
│   │   └── eb5e142098cffc3d0d7658bdfcecbda62c3f4585.nq.gz
│   ├── lsp
│   │   ├── 26a2dfed510a3aec99f4efef141de41bd6f8c81b.nq.gz
│   │   ├── 3b1a268716cfa2e968881b5dd35b26210b9957ca.nq.gz
│   │   ├── 55a3a771ef4cc1f28a856f03768716d220ef6f97.nq.gz
│   │   ├── 5b8809074cc41130be9ead0c68f9081747915149.nq.gz
│   │   ├── b217ed4eb06e3a2a523a995f85b4c84b4d17df62.nq.gz
│   │   ├── c71459ea91af86f3bbcdac2c8ed5e7773da2d848.nq.gz
│   │   ├── df21a5713e4416ee35927c0bdd4405ea55384c3c.nq.gz
│   │   └── eb5e142098cffc3d0d7658bdfcecbda62c3f4585.nq.gz
│   └── repolex
│       ├── 26a2dfed510a3aec99f4efef141de41bd6f8c81b.nq.gz
│       ├── 3b1a268716cfa2e968881b5dd35b26210b9957ca.nq.gz
│       ├── 55a3a771ef4cc1f28a856f03768716d220ef6f97.nq.gz
│       ├── 5b8809074cc41130be9ead0c68f9081747915149.nq.gz
│       ├── b217ed4eb06e3a2a523a995f85b4c84b4d17df62.nq.gz
│       ├── c71459ea91af86f3bbcdac2c8ed5e7773da2d848.nq.gz
│       ├── df21a5713e4416ee35927c0bdd4405ea55384c3c.nq.gz
│       └── eb5e142098cffc3d0d7658bdfcecbda62c3f4585.nq.gz
├── blob
│   ├── 000a01723e4453a426ac26b9220fe1f2ce839a18.nq.gz
│   ├── 0356c886376ed74b45289616f947bc9af30274de.nq.gz
│   ├── 0937dde1dfd98b2870072f0dc799e00351aea205.nq.gz
│   ├── 0da99b018c739af5031e0bf678150b631fcb766e.nq.gz
│   ├── 13478812253ef9aaaf5f820891bc00b3a7277b5d.nq.gz
│   ├── 13e2505a9cb4237762d6bebcd9d835b3192247a9.nq.gz
│   ├── 16163c8d886a39d5eac49d4965d6cb614864c574.nq.gz
│   ├── 19d0677ce12e0d0ec013567b9776c1c2e9a3b6c2.nq.gz
│   ├── 1a05e721323e605bd87c9dcc706838ed835bbf0b.nq.gz
│   ├── 1dc33e5bd8a27492ddbf326edc297d225c9cf014.nq.gz
│   ├── 1df34b19fb2caa1998f59cc6197738e6b89042f6.nq.gz
│   ├── 1e4f78d9e095181693aa75e26fdf20c1d73d828b.nq.gz
│   ├── 2172ee6b05ae086b108e5ad3c8ba52fe50811dd4.nq.gz
│   ├── 29b92f0717441e0b22762ebf62f5b534f700ad1d.nq.gz
│   ├── 2a9acf13daa95e85642ea255d3e3bd1ef8252804.nq.gz
│   ├── 2dcc26724c2b76816cb553faa06f64294bf7bd2b.nq.gz
│   ├── 312937597ffcc96cc0b1d1afdd4425f9e3c4c4f2.nq.gz
│   ├── 37630a342ddf7bc7522b05788b91cac817256e80.nq.gz
│   ├── 381300347d0faccfcf45dd6e84713222a1225b04.nq.gz
│   ├── 3b1dd236dea34783293aa950db82e93352e3de5a.nq.gz
│   ├── 440684108060b8d4c9e210fed2e6e87da3f03079.nq.gz
│   ├── 441124433554a4c234e9323150e4657e4dee47c4.nq.gz
│   ├── 48c2e705b41985ce8279b4da8372f823da96d892.nq.gz
│   ├── 490dbd61f5b5f3b5060c9a692f901a34575331d8.nq.gz
│   ├── 4a5af71c368e49d225199fba107ff7e200c4a8af.nq.gz
│   ├── 4a5cd87486b53c1f2a5fe69af2c850fef9825f67.nq.gz
│   ├── 541cd1c9728cc2df34ba650daf205b5c8968c65e.nq.gz
│   ├── 576a48d53d78128c31138d6d309d7b51d7dab5f6.nq.gz
│   ├── 59b4b3679dfa3b89c6c7e7e6e3fcde8d38ac9522.nq.gz
│   ├── 5ecb4ce707e6af3128f3b286e1528b94401ab571.nq.gz
│   ├── 62109b9f82148a0de71177ce696b0fabb9b378c4.nq.gz
│   ├── 624fcb9f7b121172dc896ae85d45096efa27e5b9.nq.gz
│   ├── 65796bb673cc1ac4df001e90ac34756271c85332.nq.gz
│   ├── 696ea2cd11cedd896020e0dabb5dc70d0ef38526.nq.gz
│   ├── 69b0d8f8b3df0f97d7d81002142174a482984c73.nq.gz
│   ├── 7002aa12ed6931f8256a916c2226e9880a5ff837.nq.gz
│   ├── 70e29c2f8ba8ce9d9b9852ca2c1cb56333a3ea04.nq.gz
│   ├── 71fe11fac2a9d5543acd0498545228d3b0ff7f1e.nq.gz
│   ├── 7483f0b80be71a31d09a848ba42eb9fc628cf21f.nq.gz
│   ├── 79c2f85dea349cc8beceb9f68253101e9b1b68b2.nq.gz
│   ├── 7b15fa1b069105ec0aa944837c631573205c0a39.nq.gz
│   ├── 7e39c8ad233da9057ee8501946d4bd4395c997fc.nq.gz
│   ├── 7f68ea2a5ad7cdfcde73f93f8287534f73d0db40.nq.gz
│   ├── 802316a2c09700c9380e2e31ee13a769ec3ecf79.nq.gz
│   ├── 81ddec08a6ceb305fe42dccf5998d86c1b586cb3.nq.gz
│   ├── 8c7a7f462f3a6b2da1acc37e34ae7019d99e8076.nq.gz
│   ├── 8d8cc55aa7c4b63b419d47c7648583a5015a0f12.nq.gz
│   ├── 936bcb96f9572b3c3eea29feaf5d2755eb185b3f.nq.gz
│   ├── 94eccfc9fb2aab21df19d50ca39b9df2b65fce84.nq.gz
│   ├── 972151d748ae2995ce02b0749c3d859101e7e440.nq.gz
│   ├── 97a365b546fd802c6ce130ae9948e79fd8b19f41.nq.gz
│   ├── 98ccf2feb7d54da1d670370696553039e5edf33f.nq.gz
│   ├── 9b9e018f4824b3c2d52405ca7cc6d03851b6b489.nq.gz
│   ├── 9cf915df08cd7f4760662ec59f1ab258ca5c0f9b.nq.gz
│   ├── a22c719f4ebc2fa903aac2f2c35ca3b7f535eff0.nq.gz
│   ├── a41a93143c8392d5d5d22abab922c68fd1d1661a.nq.gz
│   ├── a52cfd8da6d65c73e0bf798151339ae3847e0bf2.nq.gz
│   ├── a5754c84615a814912aed5d3ed46c51fe7d522e1.nq.gz
│   ├── ad521f63828f678cde8a27e40b925402614f2a73.nq.gz
│   ├── b0482f5a2d11c88c71dbe993bbe30497d9e28399.nq.gz
│   ├── b05a78881f842574691384387f135cb2a388579b.nq.gz
│   ├── b137f6788f0485e23118908e2aec1d09ecab6aad.nq.gz
│   ├── b2daf89c984041f08e678d0c8fe5d40104bc90e4.nq.gz
│   ├── bbc936cb5e9ab91df2a8758656f762f22cc4eced.nq.gz
│   ├── be1f51c4cd23d15b23f2ffde649ba7cc18d1488d.nq.gz
│   ├── be256164574a973c4b9133a5cd18739b9780d4e3.nq.gz
│   ├── c0c7a2193b94b5b538171c6dab6000958d08a2eb.nq.gz
│   ├── c16abe3b4a5fdce53991d5313c364929ff9aa57c.nq.gz
│   ├── c2f1b361a97eba2b0bb3f2161d7e3cc779f977c6.nq.gz
│   ├── c32b45174bff484d5822bc1b0ec0c75872dffd61.nq.gz
│   ├── c527cefd3d3d784fc2acc42e85b1a959ece9e7ce.nq.gz
│   ├── cfff611b27af591e4bc7a55e8c6d6b5869d3acb8.nq.gz
│   ├── d4e12729cb40f3c89d3a62cff5f4f7883c522cd1.nq.gz
│   ├── d747e1ed2734b0d66013685a4b899976a053a71c.nq.gz
│   ├── d7fe1db48fcd853c9127f0e73817622904a0bd87.nq.gz
│   ├── db54067bdad0bdff3e6cd6231f82b565ed3a8219.nq.gz
│   ├── e19eed1fa6b47d6bc4d19ceb65b91e2f2ecfb197.nq.gz
│   ├── e57463b08e15c906489bcc1485e3627fef6d4ed5.nq.gz
│   ├── ed502e475ac84e12ffa08d28632389f25a036322.nq.gz
│   └── f0d3471a27031ab753e3566fc4a81101d1fbb008.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 26a2dfed510a3aec99f4efef141de41bd6f8c81b.nq.gz
│   ├── 3b1a268716cfa2e968881b5dd35b26210b9957ca.nq.gz
│   ├── 55a3a771ef4cc1f28a856f03768716d220ef6f97.nq.gz
│   ├── 5b8809074cc41130be9ead0c68f9081747915149.nq.gz
│   ├── b217ed4eb06e3a2a523a995f85b4c84b4d17df62.nq.gz
│   ├── c71459ea91af86f3bbcdac2c8ed5e7773da2d848.nq.gz
│   ├── df21a5713e4416ee35927c0bdd4405ea55384c3c.nq.gz
│   └── eb5e142098cffc3d0d7658bdfcecbda62c3f4585.nq.gz
├── filetree
│   ├── 15efb1f02ba50f79f8905b9ef25fa9c50068b7b1.nq.gz
│   ├── 26a2dfed510a3aec99f4efef141de41bd6f8c81b.nq.gz
│   ├── 3b1a268716cfa2e968881b5dd35b26210b9957ca.nq.gz
│   ├── 55a3a771ef4cc1f28a856f03768716d220ef6f97.nq.gz
│   ├── 5b8809074cc41130be9ead0c68f9081747915149.nq.gz
│   ├── b217ed4eb06e3a2a523a995f85b4c84b4d17df62.nq.gz
│   ├── c71459ea91af86f3bbcdac2c8ed5e7773da2d848.nq.gz
│   ├── df21a5713e4416ee35927c0bdd4405ea55384c3c.nq.gz
│   └── eb5e142098cffc3d0d7658bdfcecbda62c3f4585.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 126 files
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
