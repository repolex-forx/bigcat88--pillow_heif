# Repolex Knowledge Graph of bigcat88/pillow_heif

RDF knowledge graph data for [bigcat88/pillow_heif](https://github.com/bigcat88/pillow_heif), parsed by [repolex](https://repolex.ai).

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
lexq download bigcat88/pillow_heif
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 0ffb681896cf20a46e088182ee6f8ac8f9d89f58
│   │   │   └── chunk-001.nq.gz
│   │   ├── 1aaba49ded2daf3a9d97c29c264143671f84f413
│   │   │   └── chunk-001.nq.gz
│   │   ├── 1d12ae3dbb8aae87b9b7016df7220877a30d039a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 295b6d7462986e41208f063262cff8436a320943
│   │   │   └── chunk-001.nq.gz
│   │   ├── 328d53859b896c8fdcd58dafe05774084b5f1e92
│   │   │   └── chunk-001.nq.gz
│   │   ├── 572064700e606d5a124386072e7a348b86490d19
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6bffca6bada2e071418a9092e7958bcecf4652c1
│   │   │   └── chunk-001.nq.gz
│   │   ├── a726a879bf0a56ae31ae5809654ea8bf72cf62e0
│   │   │   └── chunk-001.nq.gz
│   │   ├── c4c2701c25628715c01ca9884da5bcbe31729e24
│   │   │   └── chunk-001.nq.gz
│   │   ├── d277866bbf2b7677732a21fc9985479e7bfff1b0
│   │   │   └── chunk-001.nq.gz
│   │   └── e79d5e6a8eba4b9ae202daf9a9afdccdbd100a14
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 0ffb681896cf20a46e088182ee6f8ac8f9d89f58.nq.gz
│   │   ├── 1aaba49ded2daf3a9d97c29c264143671f84f413.nq.gz
│   │   ├── 1d12ae3dbb8aae87b9b7016df7220877a30d039a.nq.gz
│   │   ├── 295b6d7462986e41208f063262cff8436a320943.nq.gz
│   │   ├── 328d53859b896c8fdcd58dafe05774084b5f1e92.nq.gz
│   │   ├── 572064700e606d5a124386072e7a348b86490d19.nq.gz
│   │   ├── 6bffca6bada2e071418a9092e7958bcecf4652c1.nq.gz
│   │   ├── a726a879bf0a56ae31ae5809654ea8bf72cf62e0.nq.gz
│   │   ├── c4c2701c25628715c01ca9884da5bcbe31729e24.nq.gz
│   │   ├── d277866bbf2b7677732a21fc9985479e7bfff1b0.nq.gz
│   │   └── e79d5e6a8eba4b9ae202daf9a9afdccdbd100a14.nq.gz
│   └── repolex
│       ├── 0ffb681896cf20a46e088182ee6f8ac8f9d89f58
│       │   └── chunk-001.nq.gz
│       ├── 1aaba49ded2daf3a9d97c29c264143671f84f413
│       │   └── chunk-001.nq.gz
│       ├── 1d12ae3dbb8aae87b9b7016df7220877a30d039a
│       │   └── chunk-001.nq.gz
│       ├── 295b6d7462986e41208f063262cff8436a320943
│       │   └── chunk-001.nq.gz
│       ├── 328d53859b896c8fdcd58dafe05774084b5f1e92
│       │   └── chunk-001.nq.gz
│       ├── 572064700e606d5a124386072e7a348b86490d19
│       │   └── chunk-001.nq.gz
│       ├── 6bffca6bada2e071418a9092e7958bcecf4652c1
│       │   └── chunk-001.nq.gz
│       ├── a726a879bf0a56ae31ae5809654ea8bf72cf62e0
│       │   └── chunk-001.nq.gz
│       ├── c4c2701c25628715c01ca9884da5bcbe31729e24
│       │   └── chunk-001.nq.gz
│       ├── d277866bbf2b7677732a21fc9985479e7bfff1b0
│       │   └── chunk-001.nq.gz
│       └── e79d5e6a8eba4b9ae202daf9a9afdccdbd100a14
│           └── chunk-001.nq.gz
└── blob
    ├── 0016ceac2e0305158295e61342940f3b45406bad.nq.gz
    ├── 00769f2774875dd7e934f26f1c7e512d6f85f9b0.nq.gz
    ├── 01117f8bd91e7523ad4c660cb3c9c529fa25a4ec.nq.gz
    ├── 0267fda7e1fc98a3b87db748f4a3e7203ff9704f.nq.gz
    ├── 034d41eb96c16a13eadc5713a9f576d0a3b4e823.nq.gz
    ├── 038d67f3ae5f523503295c40e47b6e7937bd9253.nq.gz
    ├── 043a518a5b5001824c2090a44949a118dbe22b21.nq.gz
    ├── 04643733a89ed822474ddcf40ee955f5a05aef80.nq.gz
    ├── 048e84b441790278e1a18e1e69f6a4a3721014b5.nq.gz
    ├── 04b8606504e4671b10e0658088ca5e1a01c30dcf.nq.gz
    ├── 04be03c5d9ed97fa88fcf26097321ed983ba4cf6.nq.gz
    ├── 04c7f7f8b48eb320708c24040f4cef566b2b7dbc.nq.gz
    ├── 04d31675759ffffe9eed08a5a07212419b5f5c73.nq.gz
    ├── 04d460ca7f237213b10212f775878d760ea45771.nq.gz
    ├── 04edd7b16b980c5f0111fa64a18423c33feb27a2.nq.gz
    ├── 0575f475d69bf901d898dd4cbabc6a3a5ce89aa2.nq.gz
    ├── 06f79102f3079873d9f021bd3f5b7f01410974bd.nq.gz
    ├── 07477a71a98d3d3c70f36859ac6aca5aa6258966.nq.gz
    ├── 0896fa0c060c03673604658a358aa913a9518282.nq.gz
    ├── 08a301cfd22bb560914bceac76a018ea3b401b37.nq.gz
    ├── 08c01e731e74ac85fb1ed89a103e514f86aed1c6.nq.gz
    ├── 0901e43fae5dc1dc177ef72f5c040af41c45d524.nq.gz
    ├── 0916a83978e27c2c486e4ded1c0b51a12233425c.nq.gz
    ├── 09628139bdc6a74b4cf9761491dff1de53cc1301.nq.gz
    ├── 09b16cc0fe9eea9c6efe87f7d7924a378be41d41.nq.gz
    ├── 09b1f9d33b11675b59f576e3b9c3db60fbd1b66f.nq.gz
    ├── 0a40270522474176da2a276029b8638b0d202410.nq.gz
    ├── 0a52a76aa5e45cc0faab33e169f88af1f23207f8.nq.gz
    ├── 0a610258a83c4af85fab59dbc2ef295f78c68274.nq.gz
    ├── 0aa94be4649c1fe150d9331145e3f9554e8cd6e5.nq.gz
    ├── 0bbd90b5cf2e3e6c160d331048cffe5d0f10e98a.nq.gz
    ├── 0c2fdae4581e1655792997e46df9108350352103.nq.gz
    ├── 0c44b02514e06c8c7efadc754a8f5bb837d5f904.nq.gz
    ├── 0cf18cabbdacc70cf080f6b7528cd2543c2c9ebe.nq.gz
    ├── 0cfe105ce4101b793549b664c587f6855d4a05da.nq.gz
    ├── 0d7ce5d48661b33a875f848f597293460ea7e387.nq.gz
    ├── 0d87f679beb5bb0428f624f53fb975571c7dc9ea.nq.gz
    ├── 0decf5171e9f2ecb2f27e1a64a839e99fbc0833a.nq.gz
    ├── 0df2ad8c408705336e1b3ccaef825302b039ab8a.nq.gz
    ├── 0e0399ac8f152105edd3f8dac06aa8893393be87.nq.gz
    ├── 0e41fc3389673d1177209e63ce9c9d0bd29f950e.nq.gz
    ├── 0ed26c5986402575b68266b423238e35258469a9.nq.gz
    ├── 0f524f1b8511cfab16cfc206002f87c28c468a84.nq.gz
    ├── 0f78c86f18c0bf2e413cbbebaa247fb28a9ca6b2.nq.gz
    ├── 0f9e234a4a9843e5f21d6459d1decb8a9ed7a25f.nq.gz
    ├── 0fb4c3a6d0fe8d68ad0d0d9010562c8670488e89.nq.gz
    ├── 0fecf591cf781eadd14abe035b341452fa507ccc.nq.gz
    ├── 102efec183a22185bb07c33181311ab62f02a87c.nq.gz
    ├── 108601692f79c91d840868360c6d4daa406c8276.nq.gz
    ├── 111f3dee68c3728e11b50e5fe03b33329d64dd16.nq.gz
    ├── 111f84085b75a16b67b6cf45c46cde8b935d7025.nq.gz
    ├── 1133cd4b53248e26faaa3f926bd57b35c8487054.nq.gz
    ├── 1241dedb972e0f184c621d9cae7b89932191ad2e.nq.gz
    ├── 134a3b8ae58434d2b142814b228d2859a204ddc6.nq.gz
    ├── 1601f4cba36d21b35cce2a803c2e2e54bf1781ab.nq.gz
    ├── 178838f24882005652735a0482bd477ffb3e94ae.nq.gz
    ├── 179ba7f7f659b969128c08eb13aa6e1c8116bf49.nq.gz
    ├── 1812156544723f2496d885f6784cd33f6955be8d.nq.gz
    ├── 1817ca0fb7070c5417152576f5377c688d8c71ab.nq.gz
    ├── 19010549ef3891d068824b0fc3d50ff7388efcfd.nq.gz
    ├── 19248054a7484876719a2908cb1b31e5666eb500.nq.gz
    ├── 19806ab0f68f2b414b8565543381913200118be6.nq.gz
    ├── 19ab858dae99ccbe565dd338f552f0d149125891.nq.gz
    ├── 19b5a760bd8ec9d617417283d104f94e0f38641f.nq.gz
    ├── 19d76f93074f4b9a4299d8c88576013f80a6b7c3.nq.gz
    ├── 1af06baa29ccf3afe9ff9791ad7c5640bc2ff174.nq.gz
    ├── 1b63c05f75c6b2f78ee7c3e60c824616ba33fd06.nq.gz
    ├── 1d3f9d9ade54acde3e2c16e82d8ba3769a4c57b1.nq.gz
    ├── 1dbc920271ebe4fd1ce14ec385faf863b7e3abdb.nq.gz
    ├── 2038f67238f08cf07bc6ca17b53c275618670234.nq.gz
    ├── 20755a5eee10c4f06e202be0c009bd0fe078ffbe.nq.gz
    ├── 209e844a20d298ac6b8a424219d5a9d2748d1fe7.nq.gz
    ├── 20c0720dc3188e7560f2db6e1c31048c0517d348.nq.gz
    ├── 20e5e988f75014c5cacf60e511985cbd710dcfa2.nq.gz
    ├── 20f0f8f1ebd777762dc044ec3fca631826683cf1.nq.gz
    ├── 2104cbb75e4a9fa5aac16474f6d2f05f57d7139e.nq.gz
    ├── 211762380e783d8ad7fc96f730ebca2118588c8d.nq.gz
    ├── 2187160bbe3ade6943127d9fdfe3f28c1d2adac2.nq.gz
    ├── 23097461354f66d7536f601bd9fec4b173cc6173.nq.gz
    ├── 23b3c1509b84da526fa7c6bc744c06ca2745000e.nq.gz
    ├── 23cf4b2c52419731e54940c31d0c6147454d7eb2.nq.gz
    ├── 23f84e8ee76c5b9367530dd44e6466fc534b66d0.nq.gz
    ├── 247bb4f7ab3dbcaf44c69def818a6037810c4231.nq.gz
    ├── 24fc363cb66dc84a059c87e28e205add3f6f0a1b.nq.gz
    ├── 2505e36ee571f20504334582db7e5f94df9f9920.nq.gz
    ├── 2654f7a53ea90e79d4571277d8009be5d3455de2.nq.gz
    ├── 27d686fb4a54a60c6366c8e0af564eaa4dd2755d.nq.gz
    ├── 27e094a80220a96aae987433ca11a1255585b7fe.nq.gz
    ├── 283710f8cd57cb013ffc03b99a4a1f3e1d1678ec.nq.gz
    ├── 284b1cf1c68f5a3b3f4471eab992913dd21ec7b9.nq.gz
    ├── 2970feea58d9d9bd72cb79626b5c72c5c61e95e8.nq.gz
    ├── 2a1412dd5a17e1770542aba75c9b72067b138d6a.nq.gz
    ├── 2a222ace531beb04f0374febdc679aca52a5104f.nq.gz
    ├── 2a86bb237ff549754cb1baffaf27be43da9a2ed4.nq.gz
    ├── 2a8957310e8dc4d5b2b5cd3c0b12d632b4b3282e.nq.gz
    ├── 2b63f22cce3cfb951ab51c9ef4aa6837f5e65e38.nq.gz
    ├── 2bae4c713103e7dcc6698faef8e868eb7fa2bb14.nq.gz
    ├── 2c8975019b64a14dbb2eb2cfefb184b3585d3ee0.nq.gz
    ├── 2cdf17d8c33325088d78910ebe12f8e883aacecc.nq.gz
    ├── 2d05fbe8506e8c02dce60d52ce9eb4c927516ecd.nq.gz
    ├── 2f2f4ba2488c171440bc6807aa200ea921ba5437.nq.gz
    ├── 2f73ac6eb96b973dc6dccfe0581b029102bfb710.nq.gz
    ├── 301ed3b32b892928ebcc9f80bb5b5bad50f18634.nq.gz
    ├── 30d5408864dcbf395026f91ecb23ea89937a4e0e.nq.gz
    ├── 3165e5aa311ddf7c4e2f548d61b855d2aff93ea5.nq.gz
    ├── 324d6430461b061036d5dbf1144eb3d5b055d165.nq.gz
    ├── 3309d6c39fe3a734551e946cc557b74c8a072026.nq.gz
    ├── 3373dd9b03d9d978915929b3a5adb161cf388cc5.nq.gz
    ├── 33ec5ebabd6ebe9ecdbfc40b7d20a59e9f9a46e6.nq.gz
    ├── 3506c33da19878f5f1ca8925752ce6cc4fa6d8d1.nq.gz
    ├── 35ee43963e4adce637b13d7cfc9538e09b39283b.nq.gz
    ├── 3604bfc62ee7df0435f87e04e4986630bc9d4562.nq.gz
    ├── 360b1612285147c5959f5d9331d660b21958405d.nq.gz
    ├── 3670573d149cedee32074a3b923fad958cdbdaca.nq.gz
    ├── 36fc482a4edefd99051444870957dc3e4f276a3d.nq.gz
    ├── 382740bbab594c5229b65ac1bda0ab1cb280a0ef.nq.gz
    ├── 39b4f9fa018a27219cfc6ea4519d8aee3fc0a24e.nq.gz
    ├── 39cddb77f3084cdbdc97797a1a9dba1d0a53a135.nq.gz
    ├── 3a344bfe010068306a4fec3e30ec93cb88c5c9cf.nq.gz
    ├── 3a48a175d1b1dd8c44052c44b496ce073086f3bd.nq.gz
    ├── 3b09d3af285a54bcd29b1b1ed463665de76e8e99.nq.gz
    ├── 3b2ceacc7ab897907b1b6d009de933a20c437b17.nq.gz
    ├── 3b7b82d0da2db857eda1a798dbd908ea136f07b5.nq.gz
    ├── 3c3d342e788b0e922d6291619c5ee04485fa543d.nq.gz
    ├── 3c6163c9b2418c35d6020d3c3f4817d786188c11.nq.gz
    ├── 3d8e887ef40a6f1d3792ef3fca7359ccb3a057c2.nq.gz
    ├── 404b633850aff4a28de27e43bb3ecaf6164f859b.nq.gz
    ├── 4061fe6f29f5b7627ce9afd0ee7df73515627c9f.nq.gz
    ├── 407ebd5e2d67af1b507fe55bfac7c5c843d263aa.nq.gz
    ├── 415d21ca9706e1d0bbf2a7e63d470b49248dc324.nq.gz
    ├── 41a59bff484ac47f5be808324a928dc709f4899b.nq.gz
    ├── 41b0befb0cd870bb33d6e1e3d04410aadd77e050.nq.gz
    ├── 41f814af5410b5722f60ac89159abe39175c1b07.nq.gz
    ├── 4243df61209e6072db7ef016a1f62b98b018fb71.nq.gz
    ├── 439843cc4ff101278d029446181bcb37cb5de785.nq.gz
    ├── 43d9292b05589db09c0883e2b4dfa2defbdf8d76.nq.gz
    ├── 43fb8447aa4f95f6f4d5383ae5043b3fe81c80c7.nq.gz
    ├── 4409b40d3b3acbfb0283854f233eda39d62400dc.nq.gz
    ├── 448cc4e3515146a3fb095b5f9fa3cd6190552389.nq.gz
    ├── 44c43e4e8dc36d9531ff1eb9d9dce76059464c7d.nq.gz
    ├── 45e4905d17278408a247ab64f98207a71ceace49.nq.gz
    ├── 4653778bfcea73f9d1427f1101db79c767e268a2.nq.gz
    ├── 46d486f08726b56dea12f3ab91c9d1c4d88e2738.nq.gz
    ├── 4836e66d08853a66e7b1f91487c84b70f3601efb.nq.gz
    ├── 495e9f51df5001596beb90047dec0ae2dfcfd76a.nq.gz
    ├── 4962ecc611837c13cb203d1965ce7a12c0180e7d.nq.gz
    ├── 4a7c0a030d8c4cadf0f71ccde60681faae162c1c.nq.gz
    ├── 4af1b030a26333c073c039cce11ac40b5991d7b6.nq.gz
    ├── 4b1cae2b6b4a5492e7ecd9b01075be30809d9aca.nq.gz
    ├── 4bae6a424ba2ae310c63dd472a0d896aaef4d944.nq.gz
    ├── 4c23915490988fbbb3592f20c856dbb5a394c3ff.nq.gz
    ├── 4c4538f8341236e97beb19861ed1dd97d25327d2.nq.gz
    ├── 4c7da7da77236e23ec56893bb0bfc543fade6080.nq.gz
    ├── 4ca67495b9d666d92a95a7552d6eb952c6158d8b.nq.gz
    ├── 4cfb1c59c391be632d8932fbd5ec7493e8062439.nq.gz
    ├── 4d65935255f4e8b0f3a9dff4f3981ee543badf05.nq.gz
    ├── 4e033c6aaec25b3fd4418c116a460bcc9862d94f.nq.gz
    ├── 4e0baf0d7f3e84dc149db6b9a29a27526285847a.nq.gz
    ├── 4e65e0cd0879544cfb268eb45b4fe2816f08ceaf.nq.gz
    ├── 4f4d6896ea7b978d3d96020264f7869658998c6f.nq.gz
    ├── 4f7936b18690cda5c8ff24db8feb1a17da27e390.nq.gz
    ├── 4f847ea0df86a0b8a839e1b7c29ea14c1fa8d0be.nq.gz
    ├── 4fd5be4a7a558cf89d103d78f8abaed79a6b9dad.nq.gz
    ├── 518f77831682ef5b36d6b428e049d76dde5290ae.nq.gz
    ├── 52990e0c569545714aa1fc5485896b1129a29d9d.nq.gz
    ├── 52e63f785726a9b1b8f68cb5168bf97a4590aa77.nq.gz
    └── 532955dfa2f7bfa2f183df1ecbc1e42de8ece55f.nq.gz

28 directories, 200 files
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

[bigcat88/pillow_heif](https://github.com/bigcat88/pillow_heif)

---
*Parsed on 2026-09-19 by [repolex](https://repolex.ai)*
