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
│   │   ├── 3e41f4fb41ef8529c87d9208c8e5959621f6f135
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4a15d4163d68697032e9dbe245ba60db55927573
│   │   │   └── chunk-001.nq.gz
│   │   ├── 52325ac8103167ba58e79ef505bee3e83d991dd5
│   │   │   └── chunk-001.nq.gz
│   │   ├── 572064700e606d5a124386072e7a348b86490d19
│   │   │   └── chunk-001.nq.gz
│   │   ├── 589bd0f5d19a1065d9870d3f08b87c8fbef8cac2
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
│   │   ├── 7150375b8e09b1cfb70fd3ec18c77c227140f019
│   │   │   └── chunk-001.nq.gz
│   │   ├── 82ba2e99c5215a745a7d80df24bf5e5b04dfeb9b
│   │   │   └── chunk-001.nq.gz
│   │   ├── 90350872c674cc6ca7468ff901e36d1217fd2404
│   │   │   └── chunk-001.nq.gz
│   │   ├── 94a521ec6e6128b33416398b658ed16e6733530b
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9ad6dfe508f200e4e11d0bc3f5a00288c27d11d4
│   │   │   └── chunk-001.nq.gz
│   │   ├── a436ad5747fe66685ea9929e8d7643b5e47970ee
│   │   │   └── chunk-001.nq.gz
│   │   ├── a726a879bf0a56ae31ae5809654ea8bf72cf62e0
│   │   │   └── chunk-001.nq.gz
│   │   ├── b1e77b6db67dcc27511324c246ca7f156e66da26
│   │   │   └── chunk-001.nq.gz
│   │   ├── baa6badb22fe23737d1c939f528b792334e13bf2
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
│   │   ├── 3e41f4fb41ef8529c87d9208c8e5959621f6f135.nq.gz
│   │   ├── 4a15d4163d68697032e9dbe245ba60db55927573.nq.gz
│   │   ├── 52325ac8103167ba58e79ef505bee3e83d991dd5.nq.gz
│   │   ├── 572064700e606d5a124386072e7a348b86490d19.nq.gz
│   │   ├── 589bd0f5d19a1065d9870d3f08b87c8fbef8cac2.nq.gz
│   │   ├── 5d9aa438b4d033be49f94069c9724d0e64e9006e.nq.gz
│   │   ├── 5e2758301cc822a3654482bd3df0229c10ac4335.nq.gz
│   │   ├── 61f7258ddfb038772abdf195ccddfa04f624f1b9.nq.gz
│   │   ├── 67b924ad80b2acc653615048c4419c1548ef9a25.nq.gz
│   │   ├── 6bffca6bada2e071418a9092e7958bcecf4652c1.nq.gz
│   │   ├── 7150375b8e09b1cfb70fd3ec18c77c227140f019.nq.gz
│   │   ├── 82ba2e99c5215a745a7d80df24bf5e5b04dfeb9b.nq.gz
│   │   ├── 90350872c674cc6ca7468ff901e36d1217fd2404.nq.gz
│   │   ├── 94a521ec6e6128b33416398b658ed16e6733530b.nq.gz
│   │   ├── 9ad6dfe508f200e4e11d0bc3f5a00288c27d11d4.nq.gz
│   │   ├── a436ad5747fe66685ea9929e8d7643b5e47970ee.nq.gz
│   │   ├── a726a879bf0a56ae31ae5809654ea8bf72cf62e0.nq.gz
│   │   ├── b1e77b6db67dcc27511324c246ca7f156e66da26.nq.gz
│   │   ├── baa6badb22fe23737d1c939f528b792334e13bf2.nq.gz
│   │   ├── c4c2701c25628715c01ca9884da5bcbe31729e24.nq.gz
│   │   ├── c4ec1cdedf997f79857edf66512a2e330bb0faeb.nq.gz
│   │   ├── d1423451c182394d67ce0205f30a5c2489e2567e.nq.gz
│   │   ├── d277866bbf2b7677732a21fc9985479e7bfff1b0.nq.gz
│   │   ├── dd0ebb077e6f5060c45f245723fdfb23ce33e026.nq.gz
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
│       ├── 3e41f4fb41ef8529c87d9208c8e5959621f6f135
│       │   └── chunk-001.nq.gz
│       ├── 4a15d4163d68697032e9dbe245ba60db55927573
│       │   └── chunk-001.nq.gz
│       ├── 52325ac8103167ba58e79ef505bee3e83d991dd5
│       │   └── chunk-001.nq.gz
│       ├── 572064700e606d5a124386072e7a348b86490d19
│       │   └── chunk-001.nq.gz
│       ├── 589bd0f5d19a1065d9870d3f08b87c8fbef8cac2
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
│       ├── 7150375b8e09b1cfb70fd3ec18c77c227140f019
│       │   └── chunk-001.nq.gz
│       ├── 82ba2e99c5215a745a7d80df24bf5e5b04dfeb9b
│       │   └── chunk-001.nq.gz
│       ├── 90350872c674cc6ca7468ff901e36d1217fd2404
│       │   └── chunk-001.nq.gz
│       ├── 94a521ec6e6128b33416398b658ed16e6733530b
│       │   └── chunk-001.nq.gz
│       ├── 9ad6dfe508f200e4e11d0bc3f5a00288c27d11d4
│       │   └── chunk-001.nq.gz
│       ├── a436ad5747fe66685ea9929e8d7643b5e47970ee
│       │   └── chunk-001.nq.gz
│       ├── a726a879bf0a56ae31ae5809654ea8bf72cf62e0
│       │   └── chunk-001.nq.gz
│       ├── b1e77b6db67dcc27511324c246ca7f156e66da26
│       │   └── chunk-001.nq.gz
│       ├── baa6badb22fe23737d1c939f528b792334e13bf2
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
│       └── e79d5e6a8eba4b9ae202daf9a9afdccdbd100a14
│           └── chunk-001.nq.gz
└── blob
    ├── 0016ceac2e0305158295e61342940f3b45406bad.nq.gz
    ├── 00769f2774875dd7e934f26f1c7e512d6f85f9b0.nq.gz
    ├── 0089b17daa191d8cacf1bcfd91fbb17697492490.nq.gz
    ├── 00cc8bb28586b7338ba73ed151d7a35972c77883.nq.gz
    ├── 00d9120ccb5da92892e2b1ae4d6729632acb8605.nq.gz
    ├── 01058ccfde1a2053e9ebb1fb41b1264a35a541de.nq.gz
    ├── 0109cc2cd71a6af8f96b528cc567068b448a4c14.nq.gz
    ├── 010dc69829c77621bbebb0160b96d08038c45a4b.nq.gz
    ├── 01117f8bd91e7523ad4c660cb3c9c529fa25a4ec.nq.gz
    ├── 012fa85f6796e02c405e02be00cd8e1211208bba.nq.gz
    ├── 016beaabb6a8bf02f1e7c9b202b805705b14e1c6.nq.gz
    ├── 017d3c8f92feeb891fa9e810b4a56b4fa6b57798.nq.gz
    ├── 0201a2339189c7e546721313ccea05266f32dc8f.nq.gz
    ├── 024430a4023d664a7886166bc52f0bde858d58a8.nq.gz
    ├── 0267fda7e1fc98a3b87db748f4a3e7203ff9704f.nq.gz
    ├── 02812fee4e01cf5512a8d13a12f2760ad5803a8b.nq.gz
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
    ├── 05b16e6519717a769330beefbd4a7defb3e22aa9.nq.gz
    ├── 05e412a03f4dba07bf29e97cd0d984486ed00511.nq.gz
    ├── 065691474edce9a8f92eaa8d85c1181752233e8d.nq.gz
    ├── 0676b4a9151b9210b87a5bafd644a57a36ce38f6.nq.gz
    ├── 06cd0aee9f6a9b7d3433a241269956d9a541af59.nq.gz
    ├── 06e1528541708112ad1eb5dbc33d003f8734802a.nq.gz
    ├── 06e9a9e57e3c98e20c2cbb74454dc501375a0ea8.nq.gz
    ├── 06f79102f3079873d9f021bd3f5b7f01410974bd.nq.gz
    ├── 06f9387ceed4a72e77a69b0fa589b8007cfcde79.nq.gz
    ├── 07320d5face5a0109a70a52793136db89e93da4c.nq.gz
    ├── 07477a71a98d3d3c70f36859ac6aca5aa6258966.nq.gz
    ├── 074d99fe51b7351ed303ab70fa6c1117973a43ba.nq.gz
    ├── 0752af04c890f74a259529d8ffb7474df5f3ff0e.nq.gz
    ├── 077ce1a69d46df63bff283afe675a12c1e49f4a6.nq.gz
    ├── 07b1e3e02821fd3ed63d0f165704cecb10b24df6.nq.gz
    ├── 08114c17fd156596b870a836dd54793f1ad31471.nq.gz
    ├── 0815fce6f5a4a078e36de3ee859e251038df92f0.nq.gz
    ├── 0832e01ad301e27723ca91d5bf695e1d5fd5cf4b.nq.gz
    ├── 08839558fcbe015f0fa19a16685d99b7765c3cfa.nq.gz
    ├── 0896fa0c060c03673604658a358aa913a9518282.nq.gz
    ├── 08a301cfd22bb560914bceac76a018ea3b401b37.nq.gz
    ├── 08c01e731e74ac85fb1ed89a103e514f86aed1c6.nq.gz
    ├── 08db5de06c85d35ce08235f9840f92aecf5091cf.nq.gz
    ├── 08e73780d1d5449c902f213104f757b92b380e8f.nq.gz
    ├── 0901e43fae5dc1dc177ef72f5c040af41c45d524.nq.gz
    ├── 0916a83978e27c2c486e4ded1c0b51a12233425c.nq.gz
    ├── 09304aaccfa7c17f57b0aa5e5969771f31431ca2.nq.gz
    ├── 09628139bdc6a74b4cf9761491dff1de53cc1301.nq.gz
    ├── 09728da85710bde31bba8e88f009c9a17874d2f1.nq.gz
    ├── 098f3abf81d0c9f52e970b98f2c8e8a3aec7af2c.nq.gz
    ├── 09a05876a2f9ca3e23d7b3b7348c8c6922eeafdf.nq.gz
    ├── 09b16cc0fe9eea9c6efe87f7d7924a378be41d41.nq.gz
    ├── 09b1f9d33b11675b59f576e3b9c3db60fbd1b66f.nq.gz
    ├── 09b42c9a6b8c31e51a547c97652100c34d4d0534.nq.gz
    ├── 09e208aee150671c7acfd91fc5cd0b9c1d49b585.nq.gz
    ├── 0a221d8766690018df83b8574069c5d3934b4411.nq.gz
    ├── 0a40270522474176da2a276029b8638b0d202410.nq.gz
    ├── 0a52a76aa5e45cc0faab33e169f88af1f23207f8.nq.gz
    ├── 0a610258a83c4af85fab59dbc2ef295f78c68274.nq.gz
    ├── 0a7035e584e4e8ff5ad71f64dfd149a52b44ee1c.nq.gz
    ├── 0aa3b0dd40736b2d103e54d51b4e9f1271c03743.nq.gz
    ├── 0aa94be4649c1fe150d9331145e3f9554e8cd6e5.nq.gz
    ├── 0b31dead8f0151dc44574203677a76274ab387ce.nq.gz
    ├── 0b38de430e232008ea7bd41358cea840af101712.nq.gz
    ├── 0b5eba3453bcecf823dfdd97134076d094233242.nq.gz
    ├── 0bbae9af87b67ae3b6443d31cace5885788bcd28.nq.gz
    ├── 0bbd90b5cf2e3e6c160d331048cffe5d0f10e98a.nq.gz
    ├── 0bd1c95db101f847dae084f0dd6cdc26dff819eb.nq.gz
    ├── 0bf2658b9c39f69ffce318cdfcfdf1ec0a480af6.nq.gz
    ├── 0c2fdae4581e1655792997e46df9108350352103.nq.gz
    ├── 0c44b02514e06c8c7efadc754a8f5bb837d5f904.nq.gz
    ├── 0c469fdf64d652235b07a98387ec22caaeafeee1.nq.gz
    ├── 0cd220712c049be46402028fb4aca9cb77309ba1.nq.gz
    ├── 0cf18cabbdacc70cf080f6b7528cd2543c2c9ebe.nq.gz
    ├── 0cfe105ce4101b793549b664c587f6855d4a05da.nq.gz
    ├── 0d264708d5d8b3c8c6c9ef62da9e1962bf897b17.nq.gz
    ├── 0d7ce5d48661b33a875f848f597293460ea7e387.nq.gz
    ├── 0d87f679beb5bb0428f624f53fb975571c7dc9ea.nq.gz
    ├── 0decf5171e9f2ecb2f27e1a64a839e99fbc0833a.nq.gz
    ├── 0df007bec3bb33bb3a601b2ba42a0121666f0af2.nq.gz
    ├── 0df2ad8c408705336e1b3ccaef825302b039ab8a.nq.gz
    └── 0e0399ac8f152105edd3f8dac06aa8893393be87.nq.gz

72 directories, 200 files
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
