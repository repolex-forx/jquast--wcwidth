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
│   │   ├── 15efb1f02ba50f79f8905b9ef25fa9c50068b7b1.nq.gz
│   │   ├── 26a2dfed510a3aec99f4efef141de41bd6f8c81b.nq.gz
│   │   ├── 2708c81566c4b48f32062b3d8b8595c36dc9cd5c.nq.gz
│   │   ├── 36a625179ed2675287fe6b61c2ad319406449e60.nq.gz
│   │   ├── 3b1a268716cfa2e968881b5dd35b26210b9957ca.nq.gz
│   │   ├── 42e7af837b21e6627c79c2119a81c6041056e4e3.nq.gz
│   │   ├── 4f5ba6238edc345086ae060a307692623bf15ecc.nq.gz
│   │   ├── 55a3a771ef4cc1f28a856f03768716d220ef6f97.nq.gz
│   │   ├── 5b8809074cc41130be9ead0c68f9081747915149.nq.gz
│   │   ├── b217ed4eb06e3a2a523a995f85b4c84b4d17df62.nq.gz
│   │   ├── c71459ea91af86f3bbcdac2c8ed5e7773da2d848.nq.gz
│   │   ├── c9fd62df1628c88b0cc97c2567935111fa31406f.nq.gz
│   │   ├── df21a5713e4416ee35927c0bdd4405ea55384c3c.nq.gz
│   │   ├── e77dfdf85b56405edeb87b7c874c91ddfc71bc05.nq.gz
│   │   └── eb5e142098cffc3d0d7658bdfcecbda62c3f4585.nq.gz
│   ├── lsp
│   │   ├── 15efb1f02ba50f79f8905b9ef25fa9c50068b7b1.nq.gz
│   │   ├── 26a2dfed510a3aec99f4efef141de41bd6f8c81b.nq.gz
│   │   ├── 2708c81566c4b48f32062b3d8b8595c36dc9cd5c.nq.gz
│   │   ├── 36a625179ed2675287fe6b61c2ad319406449e60.nq.gz
│   │   ├── 3b1a268716cfa2e968881b5dd35b26210b9957ca.nq.gz
│   │   ├── 42e7af837b21e6627c79c2119a81c6041056e4e3.nq.gz
│   │   ├── 4f5ba6238edc345086ae060a307692623bf15ecc.nq.gz
│   │   ├── 55a3a771ef4cc1f28a856f03768716d220ef6f97.nq.gz
│   │   ├── 5b8809074cc41130be9ead0c68f9081747915149.nq.gz
│   │   ├── b217ed4eb06e3a2a523a995f85b4c84b4d17df62.nq.gz
│   │   ├── c71459ea91af86f3bbcdac2c8ed5e7773da2d848.nq.gz
│   │   ├── c9fd62df1628c88b0cc97c2567935111fa31406f.nq.gz
│   │   ├── df21a5713e4416ee35927c0bdd4405ea55384c3c.nq.gz
│   │   ├── e77dfdf85b56405edeb87b7c874c91ddfc71bc05.nq.gz
│   │   └── eb5e142098cffc3d0d7658bdfcecbda62c3f4585.nq.gz
│   └── repolex
│       ├── 15efb1f02ba50f79f8905b9ef25fa9c50068b7b1.nq.gz
│       ├── 26a2dfed510a3aec99f4efef141de41bd6f8c81b.nq.gz
│       ├── 2708c81566c4b48f32062b3d8b8595c36dc9cd5c.nq.gz
│       ├── 36a625179ed2675287fe6b61c2ad319406449e60.nq.gz
│       ├── 3b1a268716cfa2e968881b5dd35b26210b9957ca.nq.gz
│       ├── 42e7af837b21e6627c79c2119a81c6041056e4e3.nq.gz
│       ├── 4f5ba6238edc345086ae060a307692623bf15ecc.nq.gz
│       ├── 55a3a771ef4cc1f28a856f03768716d220ef6f97.nq.gz
│       ├── 5b8809074cc41130be9ead0c68f9081747915149.nq.gz
│       ├── b217ed4eb06e3a2a523a995f85b4c84b4d17df62.nq.gz
│       ├── c71459ea91af86f3bbcdac2c8ed5e7773da2d848.nq.gz
│       ├── c9fd62df1628c88b0cc97c2567935111fa31406f.nq.gz
│       ├── df21a5713e4416ee35927c0bdd4405ea55384c3c.nq.gz
│       ├── e77dfdf85b56405edeb87b7c874c91ddfc71bc05.nq.gz
│       └── eb5e142098cffc3d0d7658bdfcecbda62c3f4585.nq.gz
└── blob
    ├── 000a01723e4453a426ac26b9220fe1f2ce839a18.nq.gz
    ├── 018a884509fd440ccaf89d320c42fdef7764ab34.nq.gz
    ├── 02afd5c2b7c3103754fa19f68a0fdf36a4816875.nq.gz
    ├── 0356c886376ed74b45289616f947bc9af30274de.nq.gz
    ├── 0718cae022152eebc22b61c03358684d7ac3d990.nq.gz
    ├── 0719b80f41cc3aeaac2710112e0c7d8a547b160d.nq.gz
    ├── 0937dde1dfd98b2870072f0dc799e00351aea205.nq.gz
    ├── 09794f1915d061aa2fc59f56a1ec759e52c8fd18.nq.gz
    ├── 0bb984db5f46d90599253fa5b0a6e0397c77224b.nq.gz
    ├── 0da99b018c739af5031e0bf678150b631fcb766e.nq.gz
    ├── 13478812253ef9aaaf5f820891bc00b3a7277b5d.nq.gz
    ├── 13e2505a9cb4237762d6bebcd9d835b3192247a9.nq.gz
    ├── 16163c8d886a39d5eac49d4965d6cb614864c574.nq.gz
    ├── 176bf61c90e7bd32d7b33fc3515e83dbdc831c9f.nq.gz
    ├── 179dec11101f559329f12ac33a99d8aec2a44f0a.nq.gz
    ├── 19d0677ce12e0d0ec013567b9776c1c2e9a3b6c2.nq.gz
    ├── 1a05e721323e605bd87c9dcc706838ed835bbf0b.nq.gz
    ├── 1dc33e5bd8a27492ddbf326edc297d225c9cf014.nq.gz
    ├── 1df34b19fb2caa1998f59cc6197738e6b89042f6.nq.gz
    ├── 1e4f78d9e095181693aa75e26fdf20c1d73d828b.nq.gz
    ├── 2172ee6b05ae086b108e5ad3c8ba52fe50811dd4.nq.gz
    ├── 21bc2809608ef26321950b4640d53e8f22d618bd.nq.gz
    ├── 229419eef476903ab562335abf8f9a620a13c03d.nq.gz
    ├── 25f8b6154b5ffe7ca05fc3f372bca74f8e43bf36.nq.gz
    ├── 2780a0780d346fa9ff9e21efee28d332bc1d5301.nq.gz
    ├── 2876560e90a09906678704c2fa3434108b03d124.nq.gz
    ├── 29b92f0717441e0b22762ebf62f5b534f700ad1d.nq.gz
    ├── 2a8503d4f879e1682fa7460c6ee221c6cbea19be.nq.gz
    ├── 2a9acf13daa95e85642ea255d3e3bd1ef8252804.nq.gz
    ├── 2c0733315e415bfb5e5b353f9996ecd964d395b2.nq.gz
    ├── 2d6d4b102f29f098c41505ef8cdc218bc0c52859.nq.gz
    ├── 2dcc26724c2b76816cb553faa06f64294bf7bd2b.nq.gz
    ├── 304eb0804f2d7642615eee9594105d3972032b6f.nq.gz
    ├── 312937597ffcc96cc0b1d1afdd4425f9e3c4c4f2.nq.gz
    ├── 3249262d981b5ab2bc21dd87f110cd1e73d9c67b.nq.gz
    ├── 370b43004829ebfa542b5f9c5b34c721b73af290.nq.gz
    ├── 37630a342ddf7bc7522b05788b91cac817256e80.nq.gz
    ├── 381300347d0faccfcf45dd6e84713222a1225b04.nq.gz
    ├── 3b1dd236dea34783293aa950db82e93352e3de5a.nq.gz
    ├── 3b3c2b0dc5a3f1853a8bf941e92e1d096f3070ad.nq.gz
    ├── 40eedb6d22a3fbb4e604bb94532221087b50b550.nq.gz
    ├── 440684108060b8d4c9e210fed2e6e87da3f03079.nq.gz
    ├── 441124433554a4c234e9323150e4657e4dee47c4.nq.gz
    ├── 47db5e6a06f291ea8fea5ef1c18749306a4cecf2.nq.gz
    ├── 47e932ae57e0116aa52a53d6d10ebd618c1af695.nq.gz
    ├── 48a3a316627351a0aab839a65d2541bc7a40467b.nq.gz
    ├── 48c2e705b41985ce8279b4da8372f823da96d892.nq.gz
    ├── 48e772c9e6c3f87f4f1df669ea6bc65a76736837.nq.gz
    ├── 490dbd61f5b5f3b5060c9a692f901a34575331d8.nq.gz
    ├── 49165f6008755923e36a43287d802abbd68b0e93.nq.gz
    ├── 49a7d9f9b742b6717fa81a2f68d64ce75a80f073.nq.gz
    ├── 49e7d7ff3e126b5763ef8b8a03e65b2e5d900cc7.nq.gz
    ├── 4a5af71c368e49d225199fba107ff7e200c4a8af.nq.gz
    ├── 4a5cd87486b53c1f2a5fe69af2c850fef9825f67.nq.gz
    ├── 4e9ccbf7a71aeb8b6df0f5b3e721233c361c5f21.nq.gz
    ├── 4ef1387c35827c6b926f8ffacd5d449ac12eea8c.nq.gz
    ├── 4f88e2330e5a68d8b9de116614bf16318c741872.nq.gz
    ├── 541cd1c9728cc2df34ba650daf205b5c8968c65e.nq.gz
    ├── 576a48d53d78128c31138d6d309d7b51d7dab5f6.nq.gz
    ├── 59b4b3679dfa3b89c6c7e7e6e3fcde8d38ac9522.nq.gz
    ├── 59b9e81adeb7ad9675931ab7eb0183408d298756.nq.gz
    ├── 59eb5c0806f76591b8509c9588d08f26e23b51f8.nq.gz
    ├── 59f1aa0eb84811ba0a0924bbc0ac62f3978c4006.nq.gz
    ├── 5ecb4ce707e6af3128f3b286e1528b94401ab571.nq.gz
    ├── 5ffb5ff84fc988c92e284f8dade3e7c8a69fe0a8.nq.gz
    ├── 60ed6b1cde7455622a5adbcfa6820e510e8a08f5.nq.gz
    ├── 62109b9f82148a0de71177ce696b0fabb9b378c4.nq.gz
    ├── 624fcb9f7b121172dc896ae85d45096efa27e5b9.nq.gz
    ├── 654e835fc721e78030d0b9fafe5bff33e4d2bd74.nq.gz
    ├── 65796bb673cc1ac4df001e90ac34756271c85332.nq.gz
    ├── 65817a1f4bfcac9cef96b51ac96ebafc629bc64f.nq.gz
    ├── 65df2081b8da2545b467bd2f5772467988904257.nq.gz
    ├── 6653982250b1f76afef6949a04b996f8d36db84f.nq.gz
    ├── 66e63ddbe3fd1e2f2e5dd77b8bdfe5ad068f0ae4.nq.gz
    ├── 67261fd659aed3803558a70bc66e05aada57866a.nq.gz
    ├── 67982a40a07ce355838334aebc28dac4a9645cf2.nq.gz
    ├── 692f456d0f18369b028a3dbc554305fdc335f472.nq.gz
    ├── 696ea2cd11cedd896020e0dabb5dc70d0ef38526.nq.gz
    ├── 69b0d8f8b3df0f97d7d81002142174a482984c73.nq.gz
    ├── 6b584837e8cfac98e63aaaeb2b57ce748b797262.nq.gz
    ├── 7002aa12ed6931f8256a916c2226e9880a5ff837.nq.gz
    ├── 70e29c2f8ba8ce9d9b9852ca2c1cb56333a3ea04.nq.gz
    ├── 71fe11fac2a9d5543acd0498545228d3b0ff7f1e.nq.gz
    ├── 742bc1c93fc6423ee2bb995442d95f03cdbe86c4.nq.gz
    ├── 7483f0b80be71a31d09a848ba42eb9fc628cf21f.nq.gz
    ├── 749d89aa03afcf3c7a27cb82d07b57018cfc97e5.nq.gz
    ├── 76737f99aecb5e8f8e0aa46cb0aed19cf1660455.nq.gz
    ├── 7999130c1708f6bef85bc404189aa841a9e459d4.nq.gz
    ├── 79c2f85dea349cc8beceb9f68253101e9b1b68b2.nq.gz
    ├── 7b15fa1b069105ec0aa944837c631573205c0a39.nq.gz
    ├── 7ba691bfc9ddbb204ba7275bfb4fc1ca6a70fa12.nq.gz
    ├── 7cc55f041d6f3377ea55e7b5c4db427b2eda3b29.nq.gz
    ├── 7e39c8ad233da9057ee8501946d4bd4395c997fc.nq.gz
    ├── 7f68ea2a5ad7cdfcde73f93f8287534f73d0db40.nq.gz
    ├── 802316a2c09700c9380e2e31ee13a769ec3ecf79.nq.gz
    ├── 81ddec08a6ceb305fe42dccf5998d86c1b586cb3.nq.gz
    ├── 8616c3e76a96f4f6d14814eaa99ea936d20ace0a.nq.gz
    ├── 87e57043d94ec4a086d6023c341b89cb792667b2.nq.gz
    ├── 8c7a7f462f3a6b2da1acc37e34ae7019d99e8076.nq.gz
    ├── 8d8cc55aa7c4b63b419d47c7648583a5015a0f12.nq.gz
    ├── 8e9104e4fcb67a8cf9b33493251af3ffa4199ff2.nq.gz
    ├── 8eef37155a150a75787913d5f86c9291b9125496.nq.gz
    ├── 91e18dbe90a9db449bb254cb0a88f509b6797bc4.nq.gz
    ├── 936bcb96f9572b3c3eea29feaf5d2755eb185b3f.nq.gz
    ├── 94a7d39d36b5bdb739fe7fbf32402b8f9b322a41.nq.gz
    ├── 94eccfc9fb2aab21df19d50ca39b9df2b65fce84.nq.gz
    ├── 972151d748ae2995ce02b0749c3d859101e7e440.nq.gz
    ├── 97a365b546fd802c6ce130ae9948e79fd8b19f41.nq.gz
    ├── 984048ac484d18f99dbe91cf5c194c2a9379517e.nq.gz
    ├── 98869c621e5f5719f7650d0b0e32d8f582517bc2.nq.gz
    ├── 98ccf2feb7d54da1d670370696553039e5edf33f.nq.gz
    ├── 9a716adc11984c3ac5219b0449377ff519e5d008.nq.gz
    ├── 9b9e018f4824b3c2d52405ca7cc6d03851b6b489.nq.gz
    ├── 9cf915df08cd7f4760662ec59f1ab258ca5c0f9b.nq.gz
    ├── 9ec5f40c4e8744fdaeedd677a9a57cbc48702f8c.nq.gz
    ├── a0dd44cb83b3924a3fc9c09e76ae79a4d6f1030d.nq.gz
    ├── a22c719f4ebc2fa903aac2f2c35ca3b7f535eff0.nq.gz
    ├── a25710473422000862f0ae58c5ae2dc08db16982.nq.gz
    ├── a3c90bc1b81b0e2db07314a9b2c3413dbb1ef006.nq.gz
    ├── a41a93143c8392d5d5d22abab922c68fd1d1661a.nq.gz
    ├── a44c0757243a785b0b73c21a38c45f44a4a2c32f.nq.gz
    ├── a52cfd8da6d65c73e0bf798151339ae3847e0bf2.nq.gz
    ├── a5754c84615a814912aed5d3ed46c51fe7d522e1.nq.gz
    ├── ad4d72c2c9c4a2cf95377320841763af225bc6ff.nq.gz
    ├── ad521f63828f678cde8a27e40b925402614f2a73.nq.gz
    ├── af7c1c5060319b1e3278c9ce71ef124628e8fc08.nq.gz
    ├── b0482f5a2d11c88c71dbe993bbe30497d9e28399.nq.gz
    ├── b05a78881f842574691384387f135cb2a388579b.nq.gz
    ├── b0ec5ad854281df2fc8bb3890964eed54533e969.nq.gz
    ├── b137f6788f0485e23118908e2aec1d09ecab6aad.nq.gz
    ├── b16ca3e0751ad65a35cecb0c63cc1a6d96675bf4.nq.gz
    ├── b2960930de1c1ab4ac758feef7841e892aad3dc5.nq.gz
    ├── b2daf89c984041f08e678d0c8fe5d40104bc90e4.nq.gz
    ├── b8aa367b8fdf19b8d0adac8b3335e3f9b96fe721.nq.gz
    ├── bab458d9debf1c91bf89c8ce53da64b4449bc265.nq.gz
    ├── bbc936cb5e9ab91df2a8758656f762f22cc4eced.nq.gz
    ├── bd6dfdd82a032d60ede24530b3d83108f76a6c90.nq.gz
    ├── be1f51c4cd23d15b23f2ffde649ba7cc18d1488d.nq.gz
    ├── be256164574a973c4b9133a5cd18739b9780d4e3.nq.gz
    ├── bf77a7e4f73a3face472731800b99635f81b593e.nq.gz
    ├── c0c7a2193b94b5b538171c6dab6000958d08a2eb.nq.gz
    ├── c14bbb972f3f19dfa3c6d5d34a074e353918798e.nq.gz
    ├── c16abe3b4a5fdce53991d5313c364929ff9aa57c.nq.gz
    ├── c2f1b361a97eba2b0bb3f2161d7e3cc779f977c6.nq.gz
    ├── c32b45174bff484d5822bc1b0ec0c75872dffd61.nq.gz
    ├── c527cefd3d3d784fc2acc42e85b1a959ece9e7ce.nq.gz
    ├── cfff611b27af591e4bc7a55e8c6d6b5869d3acb8.nq.gz
    ├── d1b25eff346dd62663434ff0e7600610cde261f0.nq.gz
    ├── d1c40dc1d7363f2f3873cf3dc08d063bd3603395.nq.gz
    ├── d2776cd992b517cc1b08bd149a993f8a7cef3d83.nq.gz
    ├── d4e12729cb40f3c89d3a62cff5f4f7883c522cd1.nq.gz
    ├── d686b30e1b6c1932f7ba3427e88f0c69dec44541.nq.gz
    ├── d747e1ed2734b0d66013685a4b899976a053a71c.nq.gz
    ├── d7fe1db48fcd853c9127f0e73817622904a0bd87.nq.gz
    └── d8a3c9f431dc123505ff65dad7b37220bcd5984f.nq.gz

6 directories, 200 files
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
