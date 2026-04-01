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
│   │   ├── 1d3ec89bf08bc872428f3f46bd9a898be367090d.nq.gz
│   │   ├── 26a2dfed510a3aec99f4efef141de41bd6f8c81b.nq.gz
│   │   ├── 2708c81566c4b48f32062b3d8b8595c36dc9cd5c.nq.gz
│   │   ├── 29c32b382e3cca9f424020b38b31fee2cf416e00.nq.gz
│   │   ├── 2c9ab7c9d6905c0d4364071011a3168a3cbcadf2.nq.gz
│   │   ├── 36a625179ed2675287fe6b61c2ad319406449e60.nq.gz
│   │   ├── 3b1a268716cfa2e968881b5dd35b26210b9957ca.nq.gz
│   │   ├── 3bf7ba58bf54e4234c087bf6a46274c18af1f5cf.nq.gz
│   │   ├── 42e7af837b21e6627c79c2119a81c6041056e4e3.nq.gz
│   │   ├── 43fcd28ce2fd1f4ba1221120ed2e19539c81ca81.nq.gz
│   │   ├── 4738d7993c7911ce2f58cd9569a0251d1de7e9a6.nq.gz
│   │   ├── 4f5ba6238edc345086ae060a307692623bf15ecc.nq.gz
│   │   ├── 55a3a771ef4cc1f28a856f03768716d220ef6f97.nq.gz
│   │   ├── 5b8809074cc41130be9ead0c68f9081747915149.nq.gz
│   │   ├── 7918f581feedeaa4246dc0fc03ec6fb49cff15cb.nq.gz
│   │   ├── 7b4638522db445062065032a704ca5c486d78982.nq.gz
│   │   ├── b217ed4eb06e3a2a523a995f85b4c84b4d17df62.nq.gz
│   │   ├── c3310f9107791ec5b4cc9f314b7537451e648f45.nq.gz
│   │   ├── c71459ea91af86f3bbcdac2c8ed5e7773da2d848.nq.gz
│   │   ├── c9fd62df1628c88b0cc97c2567935111fa31406f.nq.gz
│   │   ├── df21a5713e4416ee35927c0bdd4405ea55384c3c.nq.gz
│   │   ├── e77dfdf85b56405edeb87b7c874c91ddfc71bc05.nq.gz
│   │   ├── eb5e142098cffc3d0d7658bdfcecbda62c3f4585.nq.gz
│   │   ├── ed5fb46d9c6fd0ad9977468f84640c4df8369c3b.nq.gz
│   │   └── f0232e5adfbcd7473021a5672c61ed79fee667f0.nq.gz
│   ├── lsp
│   │   ├── 15efb1f02ba50f79f8905b9ef25fa9c50068b7b1.nq.gz
│   │   ├── 1d3ec89bf08bc872428f3f46bd9a898be367090d.nq.gz
│   │   ├── 26a2dfed510a3aec99f4efef141de41bd6f8c81b.nq.gz
│   │   ├── 2708c81566c4b48f32062b3d8b8595c36dc9cd5c.nq.gz
│   │   ├── 29c32b382e3cca9f424020b38b31fee2cf416e00.nq.gz
│   │   ├── 2c9ab7c9d6905c0d4364071011a3168a3cbcadf2.nq.gz
│   │   ├── 36a625179ed2675287fe6b61c2ad319406449e60.nq.gz
│   │   ├── 3b1a268716cfa2e968881b5dd35b26210b9957ca.nq.gz
│   │   ├── 3bf7ba58bf54e4234c087bf6a46274c18af1f5cf.nq.gz
│   │   ├── 42e7af837b21e6627c79c2119a81c6041056e4e3.nq.gz
│   │   ├── 43fcd28ce2fd1f4ba1221120ed2e19539c81ca81.nq.gz
│   │   ├── 4738d7993c7911ce2f58cd9569a0251d1de7e9a6.nq.gz
│   │   ├── 4f5ba6238edc345086ae060a307692623bf15ecc.nq.gz
│   │   ├── 55a3a771ef4cc1f28a856f03768716d220ef6f97.nq.gz
│   │   ├── 5b8809074cc41130be9ead0c68f9081747915149.nq.gz
│   │   ├── 7918f581feedeaa4246dc0fc03ec6fb49cff15cb.nq.gz
│   │   ├── 7b4638522db445062065032a704ca5c486d78982.nq.gz
│   │   ├── b217ed4eb06e3a2a523a995f85b4c84b4d17df62.nq.gz
│   │   ├── c3310f9107791ec5b4cc9f314b7537451e648f45.nq.gz
│   │   ├── c71459ea91af86f3bbcdac2c8ed5e7773da2d848.nq.gz
│   │   ├── c9fd62df1628c88b0cc97c2567935111fa31406f.nq.gz
│   │   ├── df21a5713e4416ee35927c0bdd4405ea55384c3c.nq.gz
│   │   ├── e77dfdf85b56405edeb87b7c874c91ddfc71bc05.nq.gz
│   │   ├── eb5e142098cffc3d0d7658bdfcecbda62c3f4585.nq.gz
│   │   ├── ed5fb46d9c6fd0ad9977468f84640c4df8369c3b.nq.gz
│   │   └── f0232e5adfbcd7473021a5672c61ed79fee667f0.nq.gz
│   └── repolex
│       ├── 15efb1f02ba50f79f8905b9ef25fa9c50068b7b1.nq.gz
│       ├── 1d3ec89bf08bc872428f3f46bd9a898be367090d.nq.gz
│       ├── 26a2dfed510a3aec99f4efef141de41bd6f8c81b.nq.gz
│       ├── 2708c81566c4b48f32062b3d8b8595c36dc9cd5c.nq.gz
│       ├── 29c32b382e3cca9f424020b38b31fee2cf416e00.nq.gz
│       ├── 2c9ab7c9d6905c0d4364071011a3168a3cbcadf2.nq.gz
│       ├── 36a625179ed2675287fe6b61c2ad319406449e60.nq.gz
│       ├── 3b1a268716cfa2e968881b5dd35b26210b9957ca.nq.gz
│       ├── 3bf7ba58bf54e4234c087bf6a46274c18af1f5cf.nq.gz
│       ├── 42e7af837b21e6627c79c2119a81c6041056e4e3.nq.gz
│       ├── 43fcd28ce2fd1f4ba1221120ed2e19539c81ca81.nq.gz
│       ├── 4738d7993c7911ce2f58cd9569a0251d1de7e9a6.nq.gz
│       ├── 4f5ba6238edc345086ae060a307692623bf15ecc.nq.gz
│       ├── 55a3a771ef4cc1f28a856f03768716d220ef6f97.nq.gz
│       ├── 5b8809074cc41130be9ead0c68f9081747915149.nq.gz
│       ├── 7918f581feedeaa4246dc0fc03ec6fb49cff15cb.nq.gz
│       ├── 7b4638522db445062065032a704ca5c486d78982.nq.gz
│       ├── b217ed4eb06e3a2a523a995f85b4c84b4d17df62.nq.gz
│       ├── c3310f9107791ec5b4cc9f314b7537451e648f45.nq.gz
│       ├── c71459ea91af86f3bbcdac2c8ed5e7773da2d848.nq.gz
│       ├── c9fd62df1628c88b0cc97c2567935111fa31406f.nq.gz
│       ├── df21a5713e4416ee35927c0bdd4405ea55384c3c.nq.gz
│       ├── e77dfdf85b56405edeb87b7c874c91ddfc71bc05.nq.gz
│       ├── eb5e142098cffc3d0d7658bdfcecbda62c3f4585.nq.gz
│       ├── ed5fb46d9c6fd0ad9977468f84640c4df8369c3b.nq.gz
│       └── f0232e5adfbcd7473021a5672c61ed79fee667f0.nq.gz
└── blob
    ├── 000a01723e4453a426ac26b9220fe1f2ce839a18.nq.gz
    ├── 016e11e7b1f5703722150741d881d569611bce3f.nq.gz
    ├── 018a884509fd440ccaf89d320c42fdef7764ab34.nq.gz
    ├── 02afd5c2b7c3103754fa19f68a0fdf36a4816875.nq.gz
    ├── 0356c886376ed74b45289616f947bc9af30274de.nq.gz
    ├── 0441ec2cfd30f796b582df6d634ecf4e91c28d3d.nq.gz
    ├── 0718cae022152eebc22b61c03358684d7ac3d990.nq.gz
    ├── 0719b80f41cc3aeaac2710112e0c7d8a547b160d.nq.gz
    ├── 074ebb1a91d57e4b14bd4af35eab13df78ef5762.nq.gz
    ├── 0937dde1dfd98b2870072f0dc799e00351aea205.nq.gz
    ├── 09794f1915d061aa2fc59f56a1ec759e52c8fd18.nq.gz
    ├── 09938dbea2cddb300fd508425bca1c5835f289ae.nq.gz
    ├── 0bb984db5f46d90599253fa5b0a6e0397c77224b.nq.gz
    ├── 0c61cdacf9cb970fb8b52c62f5e4abb967652784.nq.gz
    ├── 0da99b018c739af5031e0bf678150b631fcb766e.nq.gz
    ├── 0e2ff668ea60296431b847e7cf4447671b94d1a1.nq.gz
    ├── 0ff6ffc9f2da39dbb37bb040d0ce412b9b3f5475.nq.gz
    ├── 106816aa6d219781739ec8f6760abe5c59d86a5e.nq.gz
    ├── 13478812253ef9aaaf5f820891bc00b3a7277b5d.nq.gz
    ├── 13639f032aa2c170e7319d4e73f21ee9f2fe9d98.nq.gz
    ├── 13e2505a9cb4237762d6bebcd9d835b3192247a9.nq.gz
    ├── 14b6740ab886fa507eb8e5b63f55d491d6c2d920.nq.gz
    ├── 16163c8d886a39d5eac49d4965d6cb614864c574.nq.gz
    ├── 176bf61c90e7bd32d7b33fc3515e83dbdc831c9f.nq.gz
    ├── 179dec11101f559329f12ac33a99d8aec2a44f0a.nq.gz
    ├── 17ce40c65ff486c2cc7a93f3244c47318e02fe1b.nq.gz
    ├── 19d0677ce12e0d0ec013567b9776c1c2e9a3b6c2.nq.gz
    ├── 19e407a827173d6e4072497369d3d534c9cd891d.nq.gz
    ├── 1a05e721323e605bd87c9dcc706838ed835bbf0b.nq.gz
    ├── 1a83668b06667880fb6072f8d4b9836e8f0fffe8.nq.gz
    ├── 1b45213b5e174f9b3ba1c4b4ebf92f77e573075a.nq.gz
    ├── 1b92ef4ca035a91eca0fc0a69631ccd26974e700.nq.gz
    ├── 1ca25c663681bb480dde5524212b101b7ae1d4a4.nq.gz
    ├── 1dc33e5bd8a27492ddbf326edc297d225c9cf014.nq.gz
    ├── 1df34b19fb2caa1998f59cc6197738e6b89042f6.nq.gz
    ├── 1e4f78d9e095181693aa75e26fdf20c1d73d828b.nq.gz
    ├── 1eef1ce2b2ab47dc8c9b1a079a6a4db083be9def.nq.gz
    ├── 1f62e29ad1cd9696593637b3b8863a912698fdb1.nq.gz
    ├── 20245049ef95ffc31a91c18a880fb2d9118b157f.nq.gz
    ├── 206bbdcab3884c9f2c5c2d95affef363ecaa7683.nq.gz
    ├── 212e72d033011057a7e3370688c07be9cecd0dd7.nq.gz
    ├── 2172ee6b05ae086b108e5ad3c8ba52fe50811dd4.nq.gz
    ├── 21bc2809608ef26321950b4640d53e8f22d618bd.nq.gz
    ├── 21c505be414b63bca7b9974d8c225322e519ce18.nq.gz
    ├── 229419eef476903ab562335abf8f9a620a13c03d.nq.gz
    ├── 24119f984c2fad56b464eb077594f6b8cc6d1de0.nq.gz
    ├── 24219d71aa719511dd37c37e38326c0cf2ddfe03.nq.gz
    ├── 25f8b6154b5ffe7ca05fc3f372bca74f8e43bf36.nq.gz
    ├── 27434b7e5e340d2817b339624fab5af09bbf2a09.nq.gz
    ├── 2780a0780d346fa9ff9e21efee28d332bc1d5301.nq.gz
    ├── 2876560e90a09906678704c2fa3434108b03d124.nq.gz
    ├── 28dd46c2c025f6502fedc98274bff0f1bfaf69a0.nq.gz
    ├── 29b92f0717441e0b22762ebf62f5b534f700ad1d.nq.gz
    ├── 2a8503d4f879e1682fa7460c6ee221c6cbea19be.nq.gz
    ├── 2a9acf13daa95e85642ea255d3e3bd1ef8252804.nq.gz
    ├── 2b8a2692910ac720a8fd3f0f69598b0bb5f21dae.nq.gz
    ├── 2c0733315e415bfb5e5b353f9996ecd964d395b2.nq.gz
    ├── 2d0a2779dbe6760e9b54ee826589613981b1dbd9.nq.gz
    ├── 2d6d4b102f29f098c41505ef8cdc218bc0c52859.nq.gz
    ├── 2dcc26724c2b76816cb553faa06f64294bf7bd2b.nq.gz
    ├── 304eb0804f2d7642615eee9594105d3972032b6f.nq.gz
    ├── 310d0c3d44ebd6e3ba22855cf32779a3ac90d618.nq.gz
    ├── 312937597ffcc96cc0b1d1afdd4425f9e3c4c4f2.nq.gz
    ├── 322fb47773574d4de1df7a39d770c90103ede628.nq.gz
    ├── 3249262d981b5ab2bc21dd87f110cd1e73d9c67b.nq.gz
    ├── 35e7fe94fa357e9a514187235456cf47a609c645.nq.gz
    ├── 3656b3928ece523dbc8e00625a0247b393f8d786.nq.gz
    ├── 36a233213c722fd0d33b3c0c6d9b14e69fdc64c2.nq.gz
    ├── 370b43004829ebfa542b5f9c5b34c721b73af290.nq.gz
    ├── 37630a342ddf7bc7522b05788b91cac817256e80.nq.gz
    ├── 381300347d0faccfcf45dd6e84713222a1225b04.nq.gz
    ├── 3a6fff76386241c07f760391aa320fd4dddb068b.nq.gz
    ├── 3a7ecd3c7b11dd6674cea24eb58a7ac808af9b7d.nq.gz
    ├── 3b1dd236dea34783293aa950db82e93352e3de5a.nq.gz
    ├── 3b3c2b0dc5a3f1853a8bf941e92e1d096f3070ad.nq.gz
    ├── 3c6649aaa22c9f5bf9dd9b14c5923a98b59ba6d2.nq.gz
    ├── 3ded9d5736e97b58b35de74308132891e00bb1f7.nq.gz
    ├── 3f422d48d33ea42cbd2982332e7331f265935b7c.nq.gz
    ├── 3ff281d829caad7a333cf8c5e61f9aa6a5af82ad.nq.gz
    ├── 40651406665a6fd4ef1a5f6f44b5d8e3c240c721.nq.gz
    ├── 40d3b6190651a1e5a587797d44b3b1248748a24c.nq.gz
    ├── 40eedb6d22a3fbb4e604bb94532221087b50b550.nq.gz
    ├── 437e8d48f51cd4b060108404d8fc0ca4a637916b.nq.gz
    ├── 440684108060b8d4c9e210fed2e6e87da3f03079.nq.gz
    ├── 441124433554a4c234e9323150e4657e4dee47c4.nq.gz
    ├── 465cecb1e872bf8742c99af9dfd9875515b0dd93.nq.gz
    ├── 4780dcf64ebe68da33c27513bc19e094371b2654.nq.gz
    ├── 47bedad6cd6a319dc933075bcbed0fd31cc67fbf.nq.gz
    ├── 47db5e6a06f291ea8fea5ef1c18749306a4cecf2.nq.gz
    ├── 47e932ae57e0116aa52a53d6d10ebd618c1af695.nq.gz
    ├── 489fddb255e01dab01a101730f6c1e7192ac2765.nq.gz
    ├── 48a3a316627351a0aab839a65d2541bc7a40467b.nq.gz
    ├── 48c2e705b41985ce8279b4da8372f823da96d892.nq.gz
    ├── 48e772c9e6c3f87f4f1df669ea6bc65a76736837.nq.gz
    ├── 490dbd61f5b5f3b5060c9a692f901a34575331d8.nq.gz
    ├── 49165f6008755923e36a43287d802abbd68b0e93.nq.gz
    ├── 49a7d9f9b742b6717fa81a2f68d64ce75a80f073.nq.gz
    ├── 49e7d7ff3e126b5763ef8b8a03e65b2e5d900cc7.nq.gz
    ├── 4a439a643e7debd812f388194f20e3b733623bf7.nq.gz
    ├── 4a5af71c368e49d225199fba107ff7e200c4a8af.nq.gz
    ├── 4a5cd87486b53c1f2a5fe69af2c850fef9825f67.nq.gz
    ├── 4cf03cb542655df536c60486bc06ba560f7d6b31.nq.gz
    ├── 4d140c181a77024f8309ec2d5457b6943d0ce719.nq.gz
    ├── 4e9ccbf7a71aeb8b6df0f5b3e721233c361c5f21.nq.gz
    ├── 4ef1387c35827c6b926f8ffacd5d449ac12eea8c.nq.gz
    ├── 4f21d23d9f71d0899ad5211de5d1fa71342b2b09.nq.gz
    ├── 4f539609b1987c3f52d53635ea12f61d0191eec4.nq.gz
    ├── 4f88e2330e5a68d8b9de116614bf16318c741872.nq.gz
    ├── 4fe575c2728c4aac27a03d55cc5253c8ccb3d721.nq.gz
    ├── 50ac7fbfd09d94bd04b0964ffa390f367d73f46b.nq.gz
    ├── 50f7ce8d95ee43834ec81df3f1422cbf4aeb300f.nq.gz
    ├── 5139b1f0d3be374a35aa688b7f581d8f855eac51.nq.gz
    ├── 51bcc21c791d27f6170d8d40a3ffea87391379fd.nq.gz
    ├── 540315c75a5213af3396e74f0d07d3055240b107.nq.gz
    ├── 541cd1c9728cc2df34ba650daf205b5c8968c65e.nq.gz
    ├── 545f91134cf037b42e71b33f557dd084739f4492.nq.gz
    ├── 549d9a90fcccc9739aff5e5a51a54400b2dd19d3.nq.gz
    ├── 556d1d49a852d22bf32fd79a6a4e92b1dedc9853.nq.gz
    ├── 55864bb23a51b5acb2701ffeb28715dea928ad0e.nq.gz
    ├── 576a48d53d78128c31138d6d309d7b51d7dab5f6.nq.gz
    ├── 59b4b3679dfa3b89c6c7e7e6e3fcde8d38ac9522.nq.gz
    └── 59b9e81adeb7ad9675931ab7eb0183408d298756.nq.gz

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
*Parsed on 2026-04-01 by [repolex](https://repolex.ai)*
