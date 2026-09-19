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
│   │   ├── 1d12ae3dbb8aae87b9b7016df7220877a30d039a
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
│   │   └── d277866bbf2b7677732a21fc9985479e7bfff1b0
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 1d12ae3dbb8aae87b9b7016df7220877a30d039a.nq.gz
│   │   ├── 328d53859b896c8fdcd58dafe05774084b5f1e92.nq.gz
│   │   ├── 572064700e606d5a124386072e7a348b86490d19.nq.gz
│   │   ├── 6bffca6bada2e071418a9092e7958bcecf4652c1.nq.gz
│   │   ├── a726a879bf0a56ae31ae5809654ea8bf72cf62e0.nq.gz
│   │   ├── c4c2701c25628715c01ca9884da5bcbe31729e24.nq.gz
│   │   └── d277866bbf2b7677732a21fc9985479e7bfff1b0.nq.gz
│   └── repolex
│       ├── 1d12ae3dbb8aae87b9b7016df7220877a30d039a
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
│       └── d277866bbf2b7677732a21fc9985479e7bfff1b0
│           └── chunk-001.nq.gz
└── blob
    ├── 0016ceac2e0305158295e61342940f3b45406bad.nq.gz
    ├── 00769f2774875dd7e934f26f1c7e512d6f85f9b0.nq.gz
    ├── 043a518a5b5001824c2090a44949a118dbe22b21.nq.gz
    ├── 04643733a89ed822474ddcf40ee955f5a05aef80.nq.gz
    ├── 048e84b441790278e1a18e1e69f6a4a3721014b5.nq.gz
    ├── 04b8606504e4671b10e0658088ca5e1a01c30dcf.nq.gz
    ├── 04c7f7f8b48eb320708c24040f4cef566b2b7dbc.nq.gz
    ├── 04d460ca7f237213b10212f775878d760ea45771.nq.gz
    ├── 04edd7b16b980c5f0111fa64a18423c33feb27a2.nq.gz
    ├── 06f79102f3079873d9f021bd3f5b7f01410974bd.nq.gz
    ├── 07477a71a98d3d3c70f36859ac6aca5aa6258966.nq.gz
    ├── 0896fa0c060c03673604658a358aa913a9518282.nq.gz
    ├── 0901e43fae5dc1dc177ef72f5c040af41c45d524.nq.gz
    ├── 0916a83978e27c2c486e4ded1c0b51a12233425c.nq.gz
    ├── 09b1f9d33b11675b59f576e3b9c3db60fbd1b66f.nq.gz
    ├── 0a52a76aa5e45cc0faab33e169f88af1f23207f8.nq.gz
    ├── 0a610258a83c4af85fab59dbc2ef295f78c68274.nq.gz
    ├── 0aa94be4649c1fe150d9331145e3f9554e8cd6e5.nq.gz
    ├── 0c2fdae4581e1655792997e46df9108350352103.nq.gz
    ├── 0c44b02514e06c8c7efadc754a8f5bb837d5f904.nq.gz
    ├── 0cf18cabbdacc70cf080f6b7528cd2543c2c9ebe.nq.gz
    ├── 0d7ce5d48661b33a875f848f597293460ea7e387.nq.gz
    ├── 0d87f679beb5bb0428f624f53fb975571c7dc9ea.nq.gz
    ├── 0df2ad8c408705336e1b3ccaef825302b039ab8a.nq.gz
    ├── 0e0399ac8f152105edd3f8dac06aa8893393be87.nq.gz
    ├── 0f524f1b8511cfab16cfc206002f87c28c468a84.nq.gz
    ├── 0f78c86f18c0bf2e413cbbebaa247fb28a9ca6b2.nq.gz
    ├── 0f9e234a4a9843e5f21d6459d1decb8a9ed7a25f.nq.gz
    ├── 0fb4c3a6d0fe8d68ad0d0d9010562c8670488e89.nq.gz
    ├── 0fecf591cf781eadd14abe035b341452fa507ccc.nq.gz
    ├── 102efec183a22185bb07c33181311ab62f02a87c.nq.gz
    ├── 111f3dee68c3728e11b50e5fe03b33329d64dd16.nq.gz
    ├── 111f84085b75a16b67b6cf45c46cde8b935d7025.nq.gz
    ├── 1241dedb972e0f184c621d9cae7b89932191ad2e.nq.gz
    ├── 134a3b8ae58434d2b142814b228d2859a204ddc6.nq.gz
    ├── 1601f4cba36d21b35cce2a803c2e2e54bf1781ab.nq.gz
    ├── 178838f24882005652735a0482bd477ffb3e94ae.nq.gz
    ├── 179ba7f7f659b969128c08eb13aa6e1c8116bf49.nq.gz
    ├── 1812156544723f2496d885f6784cd33f6955be8d.nq.gz
    ├── 1817ca0fb7070c5417152576f5377c688d8c71ab.nq.gz
    ├── 19010549ef3891d068824b0fc3d50ff7388efcfd.nq.gz
    ├── 19806ab0f68f2b414b8565543381913200118be6.nq.gz
    ├── 19b5a760bd8ec9d617417283d104f94e0f38641f.nq.gz
    ├── 19d76f93074f4b9a4299d8c88576013f80a6b7c3.nq.gz
    ├── 1af06baa29ccf3afe9ff9791ad7c5640bc2ff174.nq.gz
    ├── 1d3f9d9ade54acde3e2c16e82d8ba3769a4c57b1.nq.gz
    ├── 1dbc920271ebe4fd1ce14ec385faf863b7e3abdb.nq.gz
    ├── 20755a5eee10c4f06e202be0c009bd0fe078ffbe.nq.gz
    ├── 209e844a20d298ac6b8a424219d5a9d2748d1fe7.nq.gz
    ├── 20f0f8f1ebd777762dc044ec3fca631826683cf1.nq.gz
    ├── 2104cbb75e4a9fa5aac16474f6d2f05f57d7139e.nq.gz
    ├── 211762380e783d8ad7fc96f730ebca2118588c8d.nq.gz
    ├── 2187160bbe3ade6943127d9fdfe3f28c1d2adac2.nq.gz
    ├── 23097461354f66d7536f601bd9fec4b173cc6173.nq.gz
    ├── 23b3c1509b84da526fa7c6bc744c06ca2745000e.nq.gz
    ├── 23cf4b2c52419731e54940c31d0c6147454d7eb2.nq.gz
    ├── 23f84e8ee76c5b9367530dd44e6466fc534b66d0.nq.gz
    ├── 24fc363cb66dc84a059c87e28e205add3f6f0a1b.nq.gz
    ├── 2505e36ee571f20504334582db7e5f94df9f9920.nq.gz
    ├── 27e094a80220a96aae987433ca11a1255585b7fe.nq.gz
    ├── 283710f8cd57cb013ffc03b99a4a1f3e1d1678ec.nq.gz
    ├── 284b1cf1c68f5a3b3f4471eab992913dd21ec7b9.nq.gz
    ├── 2a1412dd5a17e1770542aba75c9b72067b138d6a.nq.gz
    ├── 2a222ace531beb04f0374febdc679aca52a5104f.nq.gz
    ├── 2a86bb237ff549754cb1baffaf27be43da9a2ed4.nq.gz
    ├── 2a8957310e8dc4d5b2b5cd3c0b12d632b4b3282e.nq.gz
    ├── 2b63f22cce3cfb951ab51c9ef4aa6837f5e65e38.nq.gz
    ├── 2bae4c713103e7dcc6698faef8e868eb7fa2bb14.nq.gz
    ├── 2c8975019b64a14dbb2eb2cfefb184b3585d3ee0.nq.gz
    ├── 2d05fbe8506e8c02dce60d52ce9eb4c927516ecd.nq.gz
    ├── 2f2f4ba2488c171440bc6807aa200ea921ba5437.nq.gz
    ├── 2f73ac6eb96b973dc6dccfe0581b029102bfb710.nq.gz
    ├── 301ed3b32b892928ebcc9f80bb5b5bad50f18634.nq.gz
    ├── 30d5408864dcbf395026f91ecb23ea89937a4e0e.nq.gz
    ├── 3309d6c39fe3a734551e946cc557b74c8a072026.nq.gz
    ├── 3506c33da19878f5f1ca8925752ce6cc4fa6d8d1.nq.gz
    ├── 3604bfc62ee7df0435f87e04e4986630bc9d4562.nq.gz
    ├── 360b1612285147c5959f5d9331d660b21958405d.nq.gz
    ├── 36fc482a4edefd99051444870957dc3e4f276a3d.nq.gz
    ├── 39b4f9fa018a27219cfc6ea4519d8aee3fc0a24e.nq.gz
    ├── 39cddb77f3084cdbdc97797a1a9dba1d0a53a135.nq.gz
    ├── 3a344bfe010068306a4fec3e30ec93cb88c5c9cf.nq.gz
    ├── 3b09d3af285a54bcd29b1b1ed463665de76e8e99.nq.gz
    ├── 3b2ceacc7ab897907b1b6d009de933a20c437b17.nq.gz
    ├── 3b7b82d0da2db857eda1a798dbd908ea136f07b5.nq.gz
    ├── 3c3d342e788b0e922d6291619c5ee04485fa543d.nq.gz
    ├── 3d8e887ef40a6f1d3792ef3fca7359ccb3a057c2.nq.gz
    ├── 4061fe6f29f5b7627ce9afd0ee7df73515627c9f.nq.gz
    ├── 415d21ca9706e1d0bbf2a7e63d470b49248dc324.nq.gz
    ├── 41b0befb0cd870bb33d6e1e3d04410aadd77e050.nq.gz
    ├── 41f814af5410b5722f60ac89159abe39175c1b07.nq.gz
    ├── 4243df61209e6072db7ef016a1f62b98b018fb71.nq.gz
    ├── 43d9292b05589db09c0883e2b4dfa2defbdf8d76.nq.gz
    ├── 43fb8447aa4f95f6f4d5383ae5043b3fe81c80c7.nq.gz
    ├── 448cc4e3515146a3fb095b5f9fa3cd6190552389.nq.gz
    ├── 44c43e4e8dc36d9531ff1eb9d9dce76059464c7d.nq.gz
    ├── 4653778bfcea73f9d1427f1101db79c767e268a2.nq.gz
    ├── 46d486f08726b56dea12f3ab91c9d1c4d88e2738.nq.gz
    ├── 4836e66d08853a66e7b1f91487c84b70f3601efb.nq.gz
    ├── 495e9f51df5001596beb90047dec0ae2dfcfd76a.nq.gz
    ├── 4962ecc611837c13cb203d1965ce7a12c0180e7d.nq.gz
    ├── 4a7c0a030d8c4cadf0f71ccde60681faae162c1c.nq.gz
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
    ├── 518f77831682ef5b36d6b428e049d76dde5290ae.nq.gz
    ├── 52990e0c569545714aa1fc5485896b1129a29d9d.nq.gz
    ├── 52e63f785726a9b1b8f68cb5168bf97a4590aa77.nq.gz
    ├── 532955dfa2f7bfa2f183df1ecbc1e42de8ece55f.nq.gz
    ├── 53a11af02a252f5aec231d452835bab46697d1f6.nq.gz
    ├── 541d10df7aaf87e3c15258c713d9809d6a133b0b.nq.gz
    ├── 57b75cdcc400373b059225f9c7328de74e07620e.nq.gz
    ├── 58170739907de0efcff64a751d163409566f8ded.nq.gz
    ├── 588b2367113d809ebaabc18292c9cf57f06b8aab.nq.gz
    ├── 5a7c3c2ef09279172db4686e8fbd3abc1580ce24.nq.gz
    ├── 5b2a0776e09edda7eb9e591d2656fa3219d87616.nq.gz
    ├── 5b350fa08e189c5085d3e293cfb80830c5b92b7c.nq.gz
    ├── 5b564fcfe9ae5001d366a82f7d71435fed22886a.nq.gz
    ├── 5ba59ac90dfbbea5f87393574c2f92cb39d782b1.nq.gz
    ├── 5bb90aa1f60ea5b450aa94e5c0cc6867c6abb5b6.nq.gz
    ├── 5bc0e1ccc07590156dedba4a3c3703f784fc294f.nq.gz
    ├── 5bcf32854ec74e4c931aac564c5c2b8574f537ec.nq.gz
    ├── 5c2473a72ec46bccb3335d98200971de47f42bb1.nq.gz
    ├── 5c670b74972539a0a86d56ea5658d73e77d06a83.nq.gz
    ├── 5cb6494ea59a426e68dbf587610d0c1be1c17f5c.nq.gz
    ├── 5cc931ad662b21e9486535cccb2693a57b0b97d8.nq.gz
    ├── 5d44fc0bef70d4ec504b76216beba5ac21a8fb30.nq.gz
    ├── 5f899589ca61481923f47701250282e6641ce8c7.nq.gz
    ├── 60281e07ea929d2a81f21682fbeedb3aec4c45da.nq.gz
    ├── 602c1093c704b7cba6bc0d8327862650e6213125.nq.gz
    ├── 609eba9089c54ee815adf6ca0320e9d8d529274a.nq.gz
    ├── 60c6d06ade824d6df62dd47b614d1c53d6fb55b0.nq.gz
    ├── 6175838f5a68019c088657bca633c5b0739d89d4.nq.gz
    ├── 61902090a86d4b74b831cc2cac7cb4895d5d57c4.nq.gz
    ├── 61a1704a840af89240ead966ed726c3e458d31a4.nq.gz
    ├── 62494e94f02afa192ccc56c4db68c56263b14641.nq.gz
    ├── 62c7e58f9103d2c5a389858bd30335ab2d028c78.nq.gz
    ├── 632b9db9b9ae563ed81788f4d84692636c86370b.nq.gz
    ├── 636c0097f2bc9eeff885cfa8fadf889f2508c6de.nq.gz
    ├── 63f234c4e8b3a55b9b268dd2e1f2d1d318602892.nq.gz
    ├── 64207ce444d6b5bd1d95e9a34396ddc501b16ea3.nq.gz
    ├── 649dc185b8d562bfd170738311c1fe00a43673f1.nq.gz
    ├── 64a160ac1e352eece4ab969fd0de94230533b3a5.nq.gz
    ├── 64c256536259f8754a736480eceb30e956f429a6.nq.gz
    ├── 64e55264dd1e6c01f70d83d8d828d4867450a92e.nq.gz
    ├── 658fc601d0aeca8d786c6b3cf52c16bf8e0ea9b9.nq.gz
    ├── 65aeb6b3886de9aa1d538c2e8df76cc81a5e7264.nq.gz
    ├── 6638ae4011b61326b3c73c191f63dd9f7bb99a85.nq.gz
    ├── 6644018eb8d03fdd2249858d600ed73cca3e79cf.nq.gz
    ├── 67bbea52940bc25672ed74d34a168154cfbfa5fb.nq.gz
    ├── 68945e4df3b5848e596d1a85f42101b9f87f6eda.nq.gz
    ├── 69a2e2bd7da41ee8db37712ff46467d976dcc41a.nq.gz
    ├── 6a8c2ff4928143a4e441668ff3a2c05ca3d49a79.nq.gz
    ├── 6b0c01e5153301c04ea1894d7f9c60c30934e914.nq.gz
    ├── 6b3ffc4677ba0713ee45ca6d0a8a30b32aa2199f.nq.gz
    ├── 6be13edbcea906d3049d0b78d627712ee8625809.nq.gz
    ├── 6c12377bfc845b32276a15df4cc64504eeb07d69.nq.gz
    ├── 6c1da1228ccf3f6d23cdc1d519789e9d3097c4a7.nq.gz
    ├── 6ccb111a6c0bb472afe894224841c24af462df4a.nq.gz
    ├── 6d0033f472b75bb8a36985df61b8403c5d6f7440.nq.gz
    ├── 6de9f6265208740adafd2b9673af0cecfbd0153c.nq.gz
    ├── 6ed2ea38e9ec76e4ffba794f9fe6a3e0dbce95a2.nq.gz
    ├── 6f26a06f4a3c7f66ba6a2da17d01610ac68ddb47.nq.gz
    ├── 70050b57d557b61a81224f4156c466346063b567.nq.gz
    ├── 7046032926b9d198761535c46a46cf55b0682b91.nq.gz
    ├── 708db14974e5d977dbf4e18e6f4d78d49fc2ae03.nq.gz
    ├── 7291ea57cf8392a459177feea8c22df0fae8d4c5.nq.gz
    └── 742186654e5a50340ef26b89372b8e346e597d7a.nq.gz

20 directories, 200 files
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
