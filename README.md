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
│   │   ├── 10b49d0c76429e7c9fdfec36338d98e81a2c4983
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
│   │   ├── 381253c664be978078116d7752b2c3be64ebd774
│   │   │   └── chunk-001.nq.gz
│   │   ├── 38779e7b37cce91a80b7c40a9dc1bde1e8a36b8a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3aacb3dc0282c43c50528d3759cd16af460748d6
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3e41f4fb41ef8529c87d9208c8e5959621f6f135
│   │   │   └── chunk-001.nq.gz
│   │   ├── 42550d3cbe8f20904800ed2a4da10b79de385e72
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4a15d4163d68697032e9dbe245ba60db55927573
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4e316145306352baffcfeae122d85fae5347a814
│   │   │   └── chunk-001.nq.gz
│   │   ├── 522ce5afd1a6287cdb7dd922d2915bafdb775cd2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 52325ac8103167ba58e79ef505bee3e83d991dd5
│   │   │   └── chunk-001.nq.gz
│   │   ├── 572064700e606d5a124386072e7a348b86490d19
│   │   │   └── chunk-001.nq.gz
│   │   ├── 589bd0f5d19a1065d9870d3f08b87c8fbef8cac2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5ce30384d70bd254885e827a030c366d107b88ed
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5d9aa438b4d033be49f94069c9724d0e64e9006e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5e2758301cc822a3654482bd3df0229c10ac4335
│   │   │   └── chunk-001.nq.gz
│   │   ├── 61f7258ddfb038772abdf195ccddfa04f624f1b9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 67b924ad80b2acc653615048c4419c1548ef9a25
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6bffca6bada2e071418a9092e7958bcecf4652c1
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6edb6d0537b3cf6dc029b28ac92850561ed9aba4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7150375b8e09b1cfb70fd3ec18c77c227140f019
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7aabeb2aa2c3ad67ffcbdd21d10134afd1ba02b7
│   │   │   └── chunk-001.nq.gz
│   │   ├── 82ba2e99c5215a745a7d80df24bf5e5b04dfeb9b
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8c0a842bcb404fda56d5416878c3f23f15d1f5cf
│   │   │   └── chunk-001.nq.gz
│   │   ├── 90350872c674cc6ca7468ff901e36d1217fd2404
│   │   │   └── chunk-001.nq.gz
│   │   ├── 94a521ec6e6128b33416398b658ed16e6733530b
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9ad6dfe508f200e4e11d0bc3f5a00288c27d11d4
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9ae367bc7f8929d954db6f93022cddcc2956c269
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9d2045111d27ff842678097175c7d95b5f1ec212
│   │   │   └── chunk-001.nq.gz
│   │   ├── a436ad5747fe66685ea9929e8d7643b5e47970ee
│   │   │   └── chunk-001.nq.gz
│   │   ├── a726a879bf0a56ae31ae5809654ea8bf72cf62e0
│   │   │   └── chunk-001.nq.gz
│   │   ├── b1e77b6db67dcc27511324c246ca7f156e66da26
│   │   │   └── chunk-001.nq.gz
│   │   ├── b5948eeae5216b95c1339182198e600dc736b33e
│   │   │   └── chunk-001.nq.gz
│   │   ├── b6ff992a95ef242a7046b13e3086aa0294d84d64
│   │   │   └── chunk-001.nq.gz
│   │   ├── baa6badb22fe23737d1c939f528b792334e13bf2
│   │   │   └── chunk-001.nq.gz
│   │   ├── c2feaa26a9efde3cf6b68e981faf9ad225c0f22d
│   │   │   └── chunk-001.nq.gz
│   │   ├── c4c2701c25628715c01ca9884da5bcbe31729e24
│   │   │   └── chunk-001.nq.gz
│   │   ├── c4ec1cdedf997f79857edf66512a2e330bb0faeb
│   │   │   └── chunk-001.nq.gz
│   │   ├── d1423451c182394d67ce0205f30a5c2489e2567e
│   │   │   └── chunk-001.nq.gz
│   │   ├── d277866bbf2b7677732a21fc9985479e7bfff1b0
│   │   │   └── chunk-001.nq.gz
│   │   ├── dd0ebb077e6f5060c45f245723fdfb23ce33e026
│   │   │   └── chunk-001.nq.gz
│   │   ├── e79d5e6a8eba4b9ae202daf9a9afdccdbd100a14
│   │   │   └── chunk-001.nq.gz
│   │   ├── eb23ef58bad682a285c07ac95cc571b54d8c5e17
│   │   │   └── chunk-001.nq.gz
│   │   └── f1e683c11909c47c67fcb1af3704e7667a1c3797
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 0ba397455af9d048542bcba3c850a73b2023ee5f.nq.gz
│   │   ├── 0ffb681896cf20a46e088182ee6f8ac8f9d89f58.nq.gz
│   │   ├── 10b49d0c76429e7c9fdfec36338d98e81a2c4983.nq.gz
│   │   ├── 1aaba49ded2daf3a9d97c29c264143671f84f413.nq.gz
│   │   ├── 1d12ae3dbb8aae87b9b7016df7220877a30d039a.nq.gz
│   │   ├── 295b6d7462986e41208f063262cff8436a320943.nq.gz
│   │   ├── 2c96ef28df33984cf6ba66ec38a1b2a45c99722b.nq.gz
│   │   ├── 328d53859b896c8fdcd58dafe05774084b5f1e92.nq.gz
│   │   ├── 3798f0df6b12c19dfa8fd76dd6259b329bf88029.nq.gz
│   │   ├── 381253c664be978078116d7752b2c3be64ebd774.nq.gz
│   │   ├── 38779e7b37cce91a80b7c40a9dc1bde1e8a36b8a.nq.gz
│   │   ├── 3aacb3dc0282c43c50528d3759cd16af460748d6.nq.gz
│   │   ├── 3e41f4fb41ef8529c87d9208c8e5959621f6f135.nq.gz
│   │   ├── 42550d3cbe8f20904800ed2a4da10b79de385e72.nq.gz
│   │   ├── 4a15d4163d68697032e9dbe245ba60db55927573.nq.gz
│   │   ├── 4e316145306352baffcfeae122d85fae5347a814.nq.gz
│   │   ├── 522ce5afd1a6287cdb7dd922d2915bafdb775cd2.nq.gz
│   │   ├── 52325ac8103167ba58e79ef505bee3e83d991dd5.nq.gz
│   │   ├── 572064700e606d5a124386072e7a348b86490d19.nq.gz
│   │   ├── 589bd0f5d19a1065d9870d3f08b87c8fbef8cac2.nq.gz
│   │   ├── 5ce30384d70bd254885e827a030c366d107b88ed.nq.gz
│   │   ├── 5d9aa438b4d033be49f94069c9724d0e64e9006e.nq.gz
│   │   ├── 5e2758301cc822a3654482bd3df0229c10ac4335.nq.gz
│   │   ├── 61f7258ddfb038772abdf195ccddfa04f624f1b9.nq.gz
│   │   ├── 67b924ad80b2acc653615048c4419c1548ef9a25.nq.gz
│   │   ├── 6bffca6bada2e071418a9092e7958bcecf4652c1.nq.gz
│   │   ├── 6edb6d0537b3cf6dc029b28ac92850561ed9aba4.nq.gz
│   │   ├── 7150375b8e09b1cfb70fd3ec18c77c227140f019.nq.gz
│   │   ├── 7aabeb2aa2c3ad67ffcbdd21d10134afd1ba02b7.nq.gz
│   │   ├── 82ba2e99c5215a745a7d80df24bf5e5b04dfeb9b.nq.gz
│   │   ├── 8c0a842bcb404fda56d5416878c3f23f15d1f5cf.nq.gz
│   │   ├── 90350872c674cc6ca7468ff901e36d1217fd2404.nq.gz
│   │   ├── 94a521ec6e6128b33416398b658ed16e6733530b.nq.gz
│   │   ├── 9ad6dfe508f200e4e11d0bc3f5a00288c27d11d4.nq.gz
│   │   ├── 9ae367bc7f8929d954db6f93022cddcc2956c269.nq.gz
│   │   ├── 9d2045111d27ff842678097175c7d95b5f1ec212.nq.gz
│   │   ├── a436ad5747fe66685ea9929e8d7643b5e47970ee.nq.gz
│   │   ├── a726a879bf0a56ae31ae5809654ea8bf72cf62e0.nq.gz
│   │   ├── b1e77b6db67dcc27511324c246ca7f156e66da26.nq.gz
│   │   ├── b5948eeae5216b95c1339182198e600dc736b33e.nq.gz
│   │   ├── b6ff992a95ef242a7046b13e3086aa0294d84d64.nq.gz
│   │   ├── baa6badb22fe23737d1c939f528b792334e13bf2.nq.gz
│   │   ├── c2feaa26a9efde3cf6b68e981faf9ad225c0f22d.nq.gz
│   │   ├── c4c2701c25628715c01ca9884da5bcbe31729e24.nq.gz
│   │   ├── c4ec1cdedf997f79857edf66512a2e330bb0faeb.nq.gz
│   │   ├── d1423451c182394d67ce0205f30a5c2489e2567e.nq.gz
│   │   ├── d277866bbf2b7677732a21fc9985479e7bfff1b0.nq.gz
│   │   ├── dd0ebb077e6f5060c45f245723fdfb23ce33e026.nq.gz
│   │   ├── e79d5e6a8eba4b9ae202daf9a9afdccdbd100a14.nq.gz
│   │   ├── eb23ef58bad682a285c07ac95cc571b54d8c5e17.nq.gz
│   │   └── f1e683c11909c47c67fcb1af3704e7667a1c3797.nq.gz
│   └── repolex
│       ├── 0ba397455af9d048542bcba3c850a73b2023ee5f
│       │   └── chunk-001.nq.gz
│       ├── 0ffb681896cf20a46e088182ee6f8ac8f9d89f58
│       │   └── chunk-001.nq.gz
│       ├── 10b49d0c76429e7c9fdfec36338d98e81a2c4983
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
│       ├── 381253c664be978078116d7752b2c3be64ebd774
│       │   └── chunk-001.nq.gz
│       ├── 38779e7b37cce91a80b7c40a9dc1bde1e8a36b8a
│       │   └── chunk-001.nq.gz
│       ├── 3aacb3dc0282c43c50528d3759cd16af460748d6
│       │   └── chunk-001.nq.gz
│       ├── 3e41f4fb41ef8529c87d9208c8e5959621f6f135
│       │   └── chunk-001.nq.gz
│       ├── 42550d3cbe8f20904800ed2a4da10b79de385e72
│       │   └── chunk-001.nq.gz
│       ├── 4a15d4163d68697032e9dbe245ba60db55927573
│       │   └── chunk-001.nq.gz
│       ├── 4e316145306352baffcfeae122d85fae5347a814
│       │   └── chunk-001.nq.gz
│       ├── 522ce5afd1a6287cdb7dd922d2915bafdb775cd2
│       │   └── chunk-001.nq.gz
│       ├── 52325ac8103167ba58e79ef505bee3e83d991dd5
│       │   └── chunk-001.nq.gz
│       ├── 572064700e606d5a124386072e7a348b86490d19
│       │   └── chunk-001.nq.gz
│       ├── 589bd0f5d19a1065d9870d3f08b87c8fbef8cac2
│       │   └── chunk-001.nq.gz
│       ├── 5ce30384d70bd254885e827a030c366d107b88ed
│       │   └── chunk-001.nq.gz
│       ├── 5d9aa438b4d033be49f94069c9724d0e64e9006e
│       │   └── chunk-001.nq.gz
│       ├── 5e2758301cc822a3654482bd3df0229c10ac4335
│       │   └── chunk-001.nq.gz
│       ├── 61f7258ddfb038772abdf195ccddfa04f624f1b9
│       │   └── chunk-001.nq.gz
│       ├── 67b924ad80b2acc653615048c4419c1548ef9a25
│       │   └── chunk-001.nq.gz
│       ├── 6bffca6bada2e071418a9092e7958bcecf4652c1
│       │   └── chunk-001.nq.gz
│       ├── 6edb6d0537b3cf6dc029b28ac92850561ed9aba4
│       │   └── chunk-001.nq.gz
│       ├── 7150375b8e09b1cfb70fd3ec18c77c227140f019
│       │   └── chunk-001.nq.gz
│       ├── 7aabeb2aa2c3ad67ffcbdd21d10134afd1ba02b7
│       │   └── chunk-001.nq.gz
│       ├── 82ba2e99c5215a745a7d80df24bf5e5b04dfeb9b
│       │   └── chunk-001.nq.gz
│       ├── 8c0a842bcb404fda56d5416878c3f23f15d1f5cf
│       │   └── chunk-001.nq.gz
│       ├── 90350872c674cc6ca7468ff901e36d1217fd2404
│       │   └── chunk-001.nq.gz
│       ├── 94a521ec6e6128b33416398b658ed16e6733530b
│       │   └── chunk-001.nq.gz
│       ├── 9ad6dfe508f200e4e11d0bc3f5a00288c27d11d4
│       │   └── chunk-001.nq.gz
│       ├── 9ae367bc7f8929d954db6f93022cddcc2956c269
│       │   └── chunk-001.nq.gz
│       ├── 9d2045111d27ff842678097175c7d95b5f1ec212
│       │   └── chunk-001.nq.gz
│       ├── a436ad5747fe66685ea9929e8d7643b5e47970ee
│       │   └── chunk-001.nq.gz
│       ├── a726a879bf0a56ae31ae5809654ea8bf72cf62e0
│       │   └── chunk-001.nq.gz
│       ├── b1e77b6db67dcc27511324c246ca7f156e66da26
│       │   └── chunk-001.nq.gz
│       ├── b5948eeae5216b95c1339182198e600dc736b33e
│       │   └── chunk-001.nq.gz
│       ├── b6ff992a95ef242a7046b13e3086aa0294d84d64
│       │   └── chunk-001.nq.gz
│       ├── baa6badb22fe23737d1c939f528b792334e13bf2
│       │   └── chunk-001.nq.gz
│       ├── c2feaa26a9efde3cf6b68e981faf9ad225c0f22d
│       │   └── chunk-001.nq.gz
│       ├── c4c2701c25628715c01ca9884da5bcbe31729e24
│       │   └── chunk-001.nq.gz
│       ├── c4ec1cdedf997f79857edf66512a2e330bb0faeb
│       │   └── chunk-001.nq.gz
│       ├── d1423451c182394d67ce0205f30a5c2489e2567e
│       │   └── chunk-001.nq.gz
│       ├── d277866bbf2b7677732a21fc9985479e7bfff1b0
│       │   └── chunk-001.nq.gz
│       ├── dd0ebb077e6f5060c45f245723fdfb23ce33e026
│       │   └── chunk-001.nq.gz
│       ├── e79d5e6a8eba4b9ae202daf9a9afdccdbd100a14
│       │   └── chunk-001.nq.gz
│       ├── eb23ef58bad682a285c07ac95cc571b54d8c5e17
│       │   └── chunk-001.nq.gz
│       └── f1e683c11909c47c67fcb1af3704e7667a1c3797
│           └── chunk-001.nq.gz
└── blob
    ├── 0016ceac2e0305158295e61342940f3b45406bad.nq.gz
    ├── 006218abe4064b17c13c85d9628b3501d96785e3.nq.gz
    ├── 00769f2774875dd7e934f26f1c7e512d6f85f9b0.nq.gz
    ├── 0089b17daa191d8cacf1bcfd91fbb17697492490.nq.gz
    ├── 00cc549c037e4241d6e3c739a409fb318e82dd9a.nq.gz
    ├── 00cc8bb28586b7338ba73ed151d7a35972c77883.nq.gz
    ├── 00d9120ccb5da92892e2b1ae4d6729632acb8605.nq.gz
    ├── 01058ccfde1a2053e9ebb1fb41b1264a35a541de.nq.gz
    ├── 0109cc2cd71a6af8f96b528cc567068b448a4c14.nq.gz
    ├── 010dc69829c77621bbebb0160b96d08038c45a4b.nq.gz
    ├── 01117f8bd91e7523ad4c660cb3c9c529fa25a4ec.nq.gz
    ├── 012fa85f6796e02c405e02be00cd8e1211208bba.nq.gz
    ├── 0146bf70dff01fc32b4a542a0c45478d68e2aad5.nq.gz
    ├── 016beaabb6a8bf02f1e7c9b202b805705b14e1c6.nq.gz
    ├── 017d3c8f92feeb891fa9e810b4a56b4fa6b57798.nq.gz
    ├── 01a93a215a7916fed96983aa66d5f8bd87718b73.nq.gz
    ├── 01f84a0ff1d0eb1e9275bd3ac1f6ba248c81c448.nq.gz
    ├── 0201a2339189c7e546721313ccea05266f32dc8f.nq.gz
    ├── 024430a4023d664a7886166bc52f0bde858d58a8.nq.gz
    ├── 0267fda7e1fc98a3b87db748f4a3e7203ff9704f.nq.gz
    ├── 027223b09c012b8e1fa555bc099dc8dd63dd914b.nq.gz
    ├── 02812fee4e01cf5512a8d13a12f2760ad5803a8b.nq.gz
    ├── 02b9651708082897a38b7d5440c30482b3e1e724.nq.gz
    ├── 0336e8e2ea9cf01ed9ff7acd75cdc3d120a42c98.nq.gz
    ├── 034d41eb96c16a13eadc5713a9f576d0a3b4e823.nq.gz
    ├── 036bc3643ef77b5b3059d3c79691d0b6b3c6bf9b.nq.gz
    ├── 038d67f3ae5f523503295c40e47b6e7937bd9253.nq.gz
    ├── 03e31960b3622f529ac0f3f704df3541c41ed459.nq.gz
    ├── 03fb2a61e01b00192d0a43130dfd8aadf7794e6e.nq.gz
    ├── 0412d30e054fafcb994e100b3776f6ca1af75f1a.nq.gz
    ├── 043a518a5b5001824c2090a44949a118dbe22b21.nq.gz
    ├── 04643733a89ed822474ddcf40ee955f5a05aef80.nq.gz
    ├── 0473f05c843ffc3391c9c09a2cf689c65e911bd6.nq.gz
    ├── 047fa417e7a406538d90c579490f752fd74a30c7.nq.gz
    ├── 0482b4d06f76593d05aff21e0c41ccee12c1d79c.nq.gz
    ├── 048e84b441790278e1a18e1e69f6a4a3721014b5.nq.gz
    ├── 049a763ff127adf99dedb133695c36e768901f0f.nq.gz
    ├── 04b8606504e4671b10e0658088ca5e1a01c30dcf.nq.gz
    ├── 04b8937cb6605ec8633f0ae820e75e9b9b8bad20.nq.gz
    ├── 04be03c5d9ed97fa88fcf26097321ed983ba4cf6.nq.gz
    ├── 04c7f7f8b48eb320708c24040f4cef566b2b7dbc.nq.gz
    ├── 04d31675759ffffe9eed08a5a07212419b5f5c73.nq.gz
    ├── 04d460ca7f237213b10212f775878d760ea45771.nq.gz
    ├── 04edd7b16b980c5f0111fa64a18423c33feb27a2.nq.gz
    ├── 0528849e4efe3bf971cebbed23d6503adf7680d1.nq.gz
    ├── 054caed2e8a4c1e39683f6c008038891ad07f407.nq.gz
    └── 05631c074666eb746520eb7fb308bd5a65acf7e3.nq.gz

108 directories, 200 files
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
*Parsed on 2026-09-20 by [repolex](https://repolex.ai)*
