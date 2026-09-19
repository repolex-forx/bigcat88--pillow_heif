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
│   │   ├── 0ba397455af9d048542bcba3c850a73b2023ee5f
│   │   │   └── chunk-001.nq.gz
│   │   ├── 0ffb681896cf20a46e088182ee6f8ac8f9d89f58
│   │   │   └── chunk-001.nq.gz
│   │   ├── 1aaba49ded2daf3a9d97c29c264143671f84f413
│   │   │   └── chunk-001.nq.gz
│   │   ├── 1d12ae3dbb8aae87b9b7016df7220877a30d039a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 295b6d7462986e41208f063262cff8436a320943
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2c96ef28df33984cf6ba66ec38a1b2a45c99722b
│   │   │   └── chunk-001.nq.gz
│   │   ├── 328d53859b896c8fdcd58dafe05774084b5f1e92
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3798f0df6b12c19dfa8fd76dd6259b329bf88029
│   │   │   └── chunk-001.nq.gz
│   │   ├── 52325ac8103167ba58e79ef505bee3e83d991dd5
│   │   │   └── chunk-001.nq.gz
│   │   ├── 572064700e606d5a124386072e7a348b86490d19
│   │   │   └── chunk-001.nq.gz
│   │   ├── 589bd0f5d19a1065d9870d3f08b87c8fbef8cac2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5d9aa438b4d033be49f94069c9724d0e64e9006e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6bffca6bada2e071418a9092e7958bcecf4652c1
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7150375b8e09b1cfb70fd3ec18c77c227140f019
│   │   │   └── chunk-001.nq.gz
│   │   ├── 82ba2e99c5215a745a7d80df24bf5e5b04dfeb9b
│   │   │   └── chunk-001.nq.gz
│   │   ├── a726a879bf0a56ae31ae5809654ea8bf72cf62e0
│   │   │   └── chunk-001.nq.gz
│   │   ├── b1e77b6db67dcc27511324c246ca7f156e66da26
│   │   │   └── chunk-001.nq.gz
│   │   ├── c4c2701c25628715c01ca9884da5bcbe31729e24
│   │   │   └── chunk-001.nq.gz
│   │   ├── d277866bbf2b7677732a21fc9985479e7bfff1b0
│   │   │   └── chunk-001.nq.gz
│   │   └── e79d5e6a8eba4b9ae202daf9a9afdccdbd100a14
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 0ba397455af9d048542bcba3c850a73b2023ee5f.nq.gz
│   │   ├── 0ffb681896cf20a46e088182ee6f8ac8f9d89f58.nq.gz
│   │   ├── 1aaba49ded2daf3a9d97c29c264143671f84f413.nq.gz
│   │   ├── 1d12ae3dbb8aae87b9b7016df7220877a30d039a.nq.gz
│   │   ├── 295b6d7462986e41208f063262cff8436a320943.nq.gz
│   │   ├── 2c96ef28df33984cf6ba66ec38a1b2a45c99722b.nq.gz
│   │   ├── 328d53859b896c8fdcd58dafe05774084b5f1e92.nq.gz
│   │   ├── 3798f0df6b12c19dfa8fd76dd6259b329bf88029.nq.gz
│   │   ├── 52325ac8103167ba58e79ef505bee3e83d991dd5.nq.gz
│   │   ├── 572064700e606d5a124386072e7a348b86490d19.nq.gz
│   │   ├── 589bd0f5d19a1065d9870d3f08b87c8fbef8cac2.nq.gz
│   │   ├── 5d9aa438b4d033be49f94069c9724d0e64e9006e.nq.gz
│   │   ├── 6bffca6bada2e071418a9092e7958bcecf4652c1.nq.gz
│   │   ├── 7150375b8e09b1cfb70fd3ec18c77c227140f019.nq.gz
│   │   ├── 82ba2e99c5215a745a7d80df24bf5e5b04dfeb9b.nq.gz
│   │   ├── a726a879bf0a56ae31ae5809654ea8bf72cf62e0.nq.gz
│   │   ├── b1e77b6db67dcc27511324c246ca7f156e66da26.nq.gz
│   │   ├── c4c2701c25628715c01ca9884da5bcbe31729e24.nq.gz
│   │   ├── d277866bbf2b7677732a21fc9985479e7bfff1b0.nq.gz
│   │   └── e79d5e6a8eba4b9ae202daf9a9afdccdbd100a14.nq.gz
│   └── repolex
│       ├── 0ba397455af9d048542bcba3c850a73b2023ee5f
│       │   └── chunk-001.nq.gz
│       ├── 0ffb681896cf20a46e088182ee6f8ac8f9d89f58
│       │   └── chunk-001.nq.gz
│       ├── 1aaba49ded2daf3a9d97c29c264143671f84f413
│       │   └── chunk-001.nq.gz
│       ├── 1d12ae3dbb8aae87b9b7016df7220877a30d039a
│       │   └── chunk-001.nq.gz
│       ├── 295b6d7462986e41208f063262cff8436a320943
│       │   └── chunk-001.nq.gz
│       ├── 2c96ef28df33984cf6ba66ec38a1b2a45c99722b
│       │   └── chunk-001.nq.gz
│       ├── 328d53859b896c8fdcd58dafe05774084b5f1e92
│       │   └── chunk-001.nq.gz
│       ├── 3798f0df6b12c19dfa8fd76dd6259b329bf88029
│       │   └── chunk-001.nq.gz
│       ├── 52325ac8103167ba58e79ef505bee3e83d991dd5
│       │   └── chunk-001.nq.gz
│       ├── 572064700e606d5a124386072e7a348b86490d19
│       │   └── chunk-001.nq.gz
│       ├── 589bd0f5d19a1065d9870d3f08b87c8fbef8cac2
│       │   └── chunk-001.nq.gz
│       ├── 5d9aa438b4d033be49f94069c9724d0e64e9006e
│       │   └── chunk-001.nq.gz
│       ├── 6bffca6bada2e071418a9092e7958bcecf4652c1
│       │   └── chunk-001.nq.gz
│       ├── 7150375b8e09b1cfb70fd3ec18c77c227140f019
│       │   └── chunk-001.nq.gz
│       ├── 82ba2e99c5215a745a7d80df24bf5e5b04dfeb9b
│       │   └── chunk-001.nq.gz
│       ├── a726a879bf0a56ae31ae5809654ea8bf72cf62e0
│       │   └── chunk-001.nq.gz
│       ├── b1e77b6db67dcc27511324c246ca7f156e66da26
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
    ├── 0089b17daa191d8cacf1bcfd91fbb17697492490.nq.gz
    ├── 00cc8bb28586b7338ba73ed151d7a35972c77883.nq.gz
    ├── 01117f8bd91e7523ad4c660cb3c9c529fa25a4ec.nq.gz
    ├── 012fa85f6796e02c405e02be00cd8e1211208bba.nq.gz
    ├── 016beaabb6a8bf02f1e7c9b202b805705b14e1c6.nq.gz
    ├── 024430a4023d664a7886166bc52f0bde858d58a8.nq.gz
    ├── 0267fda7e1fc98a3b87db748f4a3e7203ff9704f.nq.gz
    ├── 034d41eb96c16a13eadc5713a9f576d0a3b4e823.nq.gz
    ├── 036bc3643ef77b5b3059d3c79691d0b6b3c6bf9b.nq.gz
    ├── 038d67f3ae5f523503295c40e47b6e7937bd9253.nq.gz
    ├── 03e31960b3622f529ac0f3f704df3541c41ed459.nq.gz
    ├── 043a518a5b5001824c2090a44949a118dbe22b21.nq.gz
    ├── 04643733a89ed822474ddcf40ee955f5a05aef80.nq.gz
    ├── 0473f05c843ffc3391c9c09a2cf689c65e911bd6.nq.gz
    ├── 048e84b441790278e1a18e1e69f6a4a3721014b5.nq.gz
    ├── 049a763ff127adf99dedb133695c36e768901f0f.nq.gz
    ├── 04b8606504e4671b10e0658088ca5e1a01c30dcf.nq.gz
    ├── 04b8937cb6605ec8633f0ae820e75e9b9b8bad20.nq.gz
    ├── 04be03c5d9ed97fa88fcf26097321ed983ba4cf6.nq.gz
    ├── 04c7f7f8b48eb320708c24040f4cef566b2b7dbc.nq.gz
    ├── 04d31675759ffffe9eed08a5a07212419b5f5c73.nq.gz
    ├── 04d460ca7f237213b10212f775878d760ea45771.nq.gz
    ├── 04edd7b16b980c5f0111fa64a18423c33feb27a2.nq.gz
    ├── 054caed2e8a4c1e39683f6c008038891ad07f407.nq.gz
    ├── 0575f475d69bf901d898dd4cbabc6a3a5ce89aa2.nq.gz
    ├── 05aa4e9958042c38921826791f1f1e3abb7096d7.nq.gz
    ├── 05aacbaef7c1cdba022357f7d51a064daf9f4b7e.nq.gz
    ├── 06cd0aee9f6a9b7d3433a241269956d9a541af59.nq.gz
    ├── 06f79102f3079873d9f021bd3f5b7f01410974bd.nq.gz
    ├── 07477a71a98d3d3c70f36859ac6aca5aa6258966.nq.gz
    ├── 0832e01ad301e27723ca91d5bf695e1d5fd5cf4b.nq.gz
    ├── 0896fa0c060c03673604658a358aa913a9518282.nq.gz
    ├── 08a301cfd22bb560914bceac76a018ea3b401b37.nq.gz
    ├── 08c01e731e74ac85fb1ed89a103e514f86aed1c6.nq.gz
    ├── 08e73780d1d5449c902f213104f757b92b380e8f.nq.gz
    ├── 0901e43fae5dc1dc177ef72f5c040af41c45d524.nq.gz
    ├── 0916a83978e27c2c486e4ded1c0b51a12233425c.nq.gz
    ├── 09628139bdc6a74b4cf9761491dff1de53cc1301.nq.gz
    ├── 09728da85710bde31bba8e88f009c9a17874d2f1.nq.gz
    ├── 09b16cc0fe9eea9c6efe87f7d7924a378be41d41.nq.gz
    ├── 09b1f9d33b11675b59f576e3b9c3db60fbd1b66f.nq.gz
    ├── 09b42c9a6b8c31e51a547c97652100c34d4d0534.nq.gz
    ├── 09e208aee150671c7acfd91fc5cd0b9c1d49b585.nq.gz
    ├── 0a221d8766690018df83b8574069c5d3934b4411.nq.gz
    ├── 0a40270522474176da2a276029b8638b0d202410.nq.gz
    ├── 0a52a76aa5e45cc0faab33e169f88af1f23207f8.nq.gz
    ├── 0a610258a83c4af85fab59dbc2ef295f78c68274.nq.gz
    ├── 0a7035e584e4e8ff5ad71f64dfd149a52b44ee1c.nq.gz
    ├── 0aa94be4649c1fe150d9331145e3f9554e8cd6e5.nq.gz
    ├── 0b38de430e232008ea7bd41358cea840af101712.nq.gz
    ├── 0bbd90b5cf2e3e6c160d331048cffe5d0f10e98a.nq.gz
    ├── 0c2fdae4581e1655792997e46df9108350352103.nq.gz
    ├── 0c44b02514e06c8c7efadc754a8f5bb837d5f904.nq.gz
    ├── 0cf18cabbdacc70cf080f6b7528cd2543c2c9ebe.nq.gz
    ├── 0cfe105ce4101b793549b664c587f6855d4a05da.nq.gz
    ├── 0d7ce5d48661b33a875f848f597293460ea7e387.nq.gz
    ├── 0d87f679beb5bb0428f624f53fb975571c7dc9ea.nq.gz
    ├── 0decf5171e9f2ecb2f27e1a64a839e99fbc0833a.nq.gz
    ├── 0df007bec3bb33bb3a601b2ba42a0121666f0af2.nq.gz
    ├── 0df2ad8c408705336e1b3ccaef825302b039ab8a.nq.gz
    ├── 0e0399ac8f152105edd3f8dac06aa8893393be87.nq.gz
    ├── 0e41fc3389673d1177209e63ce9c9d0bd29f950e.nq.gz
    ├── 0ed26c5986402575b68266b423238e35258469a9.nq.gz
    ├── 0f524f1b8511cfab16cfc206002f87c28c468a84.nq.gz
    ├── 0f78c86f18c0bf2e413cbbebaa247fb28a9ca6b2.nq.gz
    ├── 0f893a0e26793e587230b8d8f3f14c4133dc579c.nq.gz
    ├── 0f9e234a4a9843e5f21d6459d1decb8a9ed7a25f.nq.gz
    ├── 0fb4c3a6d0fe8d68ad0d0d9010562c8670488e89.nq.gz
    ├── 0fecf591cf781eadd14abe035b341452fa507ccc.nq.gz
    ├── 102efec183a22185bb07c33181311ab62f02a87c.nq.gz
    ├── 108601692f79c91d840868360c6d4daa406c8276.nq.gz
    ├── 111f3dee68c3728e11b50e5fe03b33329d64dd16.nq.gz
    ├── 111f84085b75a16b67b6cf45c46cde8b935d7025.nq.gz
    ├── 1133cd4b53248e26faaa3f926bd57b35c8487054.nq.gz
    ├── 1162483fd80b3eba3173d960bccf08c08967ccd1.nq.gz
    ├── 1241dedb972e0f184c621d9cae7b89932191ad2e.nq.gz
    ├── 134a3b8ae58434d2b142814b228d2859a204ddc6.nq.gz
    ├── 136fa7c843ad8431916e81f762b5346069ec22a7.nq.gz
    ├── 140c469aed51a5c1b7bd1179595e7fb619bdd4af.nq.gz
    ├── 14d21562d96ed49f9e12c578f7d913331b3a688a.nq.gz
    ├── 14ee1818cfb20db07096048da2f5e492f2278057.nq.gz
    ├── 14f6170155b63272ce9b5c714854ce810cd315a7.nq.gz
    ├── 1601f4cba36d21b35cce2a803c2e2e54bf1781ab.nq.gz
    ├── 175e69e71d947f303d308e5abac20fa457b6088b.nq.gz
    ├── 178838f24882005652735a0482bd477ffb3e94ae.nq.gz
    ├── 179ba7f7f659b969128c08eb13aa6e1c8116bf49.nq.gz
    ├── 17a8edea73cab335bb46f382d0a99dad773a6a8e.nq.gz
    ├── 17c3ad6e54448b30058624dd99bd9bddc26a582b.nq.gz
    ├── 1812156544723f2496d885f6784cd33f6955be8d.nq.gz
    ├── 1817ca0fb7070c5417152576f5377c688d8c71ab.nq.gz
    ├── 183a093f2a2812ebf2240d49d55a251e871a384f.nq.gz
    ├── 19010549ef3891d068824b0fc3d50ff7388efcfd.nq.gz
    ├── 190db2a41ce95a6b1130ad9ce7683e0bc1956dec.nq.gz
    ├── 1918486173890496c2108f9afaf9bf991523d621.nq.gz
    ├── 1918afcf5da5bfd9dd5e81fb96c22ab90cfca1fe.nq.gz
    ├── 19248054a7484876719a2908cb1b31e5666eb500.nq.gz
    ├── 193c85e52a0845ac1a89306927bc34f8532c9703.nq.gz
    ├── 19806ab0f68f2b414b8565543381913200118be6.nq.gz
    ├── 19ab858dae99ccbe565dd338f552f0d149125891.nq.gz
    ├── 19b5a760bd8ec9d617417283d104f94e0f38641f.nq.gz
    ├── 19d76f93074f4b9a4299d8c88576013f80a6b7c3.nq.gz
    ├── 19dd1f96aa8cc1f4b4929e5f49376b7d77430589.nq.gz
    ├── 1af06baa29ccf3afe9ff9791ad7c5640bc2ff174.nq.gz
    ├── 1b2be457bd3f327bccda93704f2a82703f234d9f.nq.gz
    ├── 1b63c05f75c6b2f78ee7c3e60c824616ba33fd06.nq.gz
    ├── 1b9f7792c32ec982593e012be78d5212ec155a55.nq.gz
    ├── 1bd01d7dc829f0be73e7962db0d38696299a6ffd.nq.gz
    ├── 1c8dc9d8f1d7d11b732e80c946c3cbb0ab9078f4.nq.gz
    ├── 1c9b80ceb061930f35050af180092c0b3b80bde0.nq.gz
    ├── 1d3f9d9ade54acde3e2c16e82d8ba3769a4c57b1.nq.gz
    ├── 1d8f7b998a0a26c0a1566edc22e1735d1056161a.nq.gz
    ├── 1dbc920271ebe4fd1ce14ec385faf863b7e3abdb.nq.gz
    ├── 1e172683177a0bedf8fd43640c8dc85c017dad94.nq.gz
    ├── 1e7034d54c44503ae84b3f99a7f2e4f81de8e0ca.nq.gz
    ├── 1e9fd8f1076a006ecaf347644be5bcefee6a420a.nq.gz
    ├── 2038f67238f08cf07bc6ca17b53c275618670234.nq.gz
    ├── 20755a5eee10c4f06e202be0c009bd0fe078ffbe.nq.gz
    ├── 2089fcbf49ee42ef537c3e06c2346366f0b12a2c.nq.gz
    ├── 209e844a20d298ac6b8a424219d5a9d2748d1fe7.nq.gz
    ├── 20bfd168cec60144e1540612c55f28999818237b.nq.gz
    ├── 20c0720dc3188e7560f2db6e1c31048c0517d348.nq.gz
    ├── 20e5e988f75014c5cacf60e511985cbd710dcfa2.nq.gz
    ├── 20f0f8f1ebd777762dc044ec3fca631826683cf1.nq.gz
    ├── 2104cbb75e4a9fa5aac16474f6d2f05f57d7139e.nq.gz
    ├── 211762380e783d8ad7fc96f730ebca2118588c8d.nq.gz
    ├── 214f3f3b956ed80fd32698b10f2b4e6d9a62ed68.nq.gz
    ├── 2187160bbe3ade6943127d9fdfe3f28c1d2adac2.nq.gz
    ├── 2299cbc8305a4e8cd7a7f726edf7fd50c9e66843.nq.gz
    ├── 22d47ff77e2e77b1c197d9081dd1c3a554956479.nq.gz
    ├── 23097461354f66d7536f601bd9fec4b173cc6173.nq.gz
    ├── 23b3c1509b84da526fa7c6bc744c06ca2745000e.nq.gz
    ├── 23be6883c443639fa3b1290d00a0bc2a2b01fd90.nq.gz
    ├── 23cf4b2c52419731e54940c31d0c6147454d7eb2.nq.gz
    ├── 23f84e8ee76c5b9367530dd44e6466fc534b66d0.nq.gz
    ├── 247bb4f7ab3dbcaf44c69def818a6037810c4231.nq.gz
    ├── 24e73e90f3843f12447ad4196d39c40bc10541c7.nq.gz
    ├── 24fc363cb66dc84a059c87e28e205add3f6f0a1b.nq.gz
    └── 2505e36ee571f20504334582db7e5f94df9f9920.nq.gz

46 directories, 200 files
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
