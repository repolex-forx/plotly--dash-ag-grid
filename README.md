# Repolex Knowledge Graph of plotly/dash-ag-grid

RDF knowledge graph data for [plotly/dash-ag-grid](https://github.com/plotly/dash-ag-grid), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download plotly/dash-ag-grid
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 13eef10e8d0c7b7acbe42a655d65104637b4f268
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 13eef10e8d0c7b7acbe42a655d65104637b4f268
│           └── chunk-001.nq.gz
└── blob
    ├── 00eb5adf0530988891e243473e7fc6700b2a0137.nq.gz
    ├── 015fe69b1b385b8a17c6dc7428917261fd2149e5.nq.gz
    ├── 01afcd51a018dce92db0c39dd3b046e548bd55d5.nq.gz
    ├── 021f4e83c4ec74d33864ce02475b8de88ccd6240.nq.gz
    ├── 023ac1dbe04efaecbee690981a48fec1ea96d692.nq.gz
    ├── 02775ea4e69b1b9c47490a42905b52fb465c62da.nq.gz
    ├── 03a3c957e8b25b67816c9433c9f4830cf66719bf.nq.gz
    ├── 03ad7495ccb923fdc61b3e22b33e90c1b6746e64.nq.gz
    ├── 04ad558f91d01909944996d8feb47c22d44f7e8c.nq.gz
    ├── 04e3f1cacb1fbd92a8abf1a7e6ad74507106c77b.nq.gz
    ├── 057d94fa9199ef491dfc24a6965a1c2d9a3db918.nq.gz
    ├── 05f6b4092df52de90500ffc675e9f8ce08326089.nq.gz
    ├── 05ffea87c1ab3d6c4714276753a2b648658c8fe6.nq.gz
    ├── 06218f488b84bb49a45eb5e6e5c2c2414ca468cd.nq.gz
    ├── 07e7e6195bbc38c5a87939a9337a435a0cf980e9.nq.gz
    ├── 09ed2bbe2bb9dc6d7d3c8989b74c3d75412def40.nq.gz
    ├── 0a32fb0f5d4e318d92759e751989ec68f26a59d6.nq.gz
    ├── 0a5577f643ee53b999f40519bc2fd3a8c4b7ba13.nq.gz
    ├── 0bb1753afa634b98fe05d36c31fdc3425a5e3ff5.nq.gz
    ├── 0c28ed07a4c9f1ec53bf7127380e406fc98c17aa.nq.gz
    ├── 0fa875281d63dfc9fe238d3e9b453a71aa63ff7b.nq.gz
    ├── 0fb98771bb282aa7225d8f80594f2105908f8743.nq.gz
    ├── 10b992e6692b4240885539086dfdd588003e732e.nq.gz
    ├── 10f4639345d9ee2a19b48edb2dc690136c5735e4.nq.gz
    ├── 1264487416c997c11529ab714a69322a2dcead7d.nq.gz
    ├── 14394bfb78ce977d8e507d1207dcdb9289701234.nq.gz
    ├── 144300e17a2cbf1f150b9c4ccbf9f82002f4fea4.nq.gz
    ├── 14597d808b916a54088c8a3a8eae0e4cdb142d3e.nq.gz
    ├── 147c53762faab92b51ca6be27dfd52d3b784069e.nq.gz
    ├── 1515aef8937c2d436ed0dbbae5d1de85853d747c.nq.gz
    ├── 1585d00b3857427095fae3a1dbd67da1719b7dcc.nq.gz
    ├── 15d1345d6dbbd1e7fda79571918eb60bf33cd8ec.nq.gz
    ├── 15d5a49d5df56df2e9b38f67d5f2d7b1ee33e6ec.nq.gz
    ├── 160367eacb2719fccb4b99292230c8872fdfa9c0.nq.gz
    ├── 1643951243dacd6fe70e882bdbb71afb2f0d59ad.nq.gz
    ├── 16a4f3937a2bf3998ba1245192ecac015bf44869.nq.gz
    ├── 18030f26cbcaf1bd73e97e482df9910cbbf4161f.nq.gz
    ├── 18b60e99adab24d24695fbfe500aeae434dffdd0.nq.gz
    ├── 1958f19f2abba5e5509d8f0c93c4fb52eb26509a.nq.gz
    ├── 1b5a290df4dd9da30fd88e901eacee0f5a4eb7a0.nq.gz
    ├── 1c88bbe0bfcb877557b33d62ea1337c204f231ea.nq.gz
    ├── 1c9824af016c0fa0fdb22cec7e4dd2c045d37798.nq.gz
    ├── 1d1a7fe817903be421a0dfd032a0685d1eda1900.nq.gz
    ├── 1d6290ca6ea298a406e9007d619876b53646e8af.nq.gz
    ├── 1db3780f31af924e24d131aabfe92f9f8fea0095.nq.gz
    ├── 1db560d8d7d2fed7a0a854ad1facd043edb87e70.nq.gz
    ├── 1dbb7dc24f5bfd17a0b7d9d7084310fb6a7642ef.nq.gz
    ├── 1de6f1a66deb2278ae5422b6ff3436e29cf51cf5.nq.gz
    ├── 1e3d41444d36b0056d1139a5aef5f9353982faf7.nq.gz
    ├── 1e6cd3aa8efe7c03a2683879c62e2c89c98ed13d.nq.gz
    ├── 1e97c8f309cf1d181fcf9681f0789f513b809546.nq.gz
    ├── 1eb2601da6c670ed3b49f68e9989fce1737fcb53.nq.gz
    ├── 1f3a7200934a4a38b6b6ab284bcfd509e8cb41c7.nq.gz
    ├── 20300854f4c7fae8d14d30a1d6cbe470bc9c18a8.nq.gz
    ├── 2059175202643c8141ea8f8ff7c88ccc6f34eac7.nq.gz
    ├── 2060b4a1acd31f92d7c2ae3ab439bb6282be2e7c.nq.gz
    ├── 2076cfb79425e5e37c70785708c4f56a5b46db3d.nq.gz
    ├── 20cd2b78204d049ac8e21244c67ff02ccf23d59d.nq.gz
    ├── 228087c9a357f327687731c3229ea4520f79b77b.nq.gz
    ├── 22db32594cc14fe7803720ac193636b68798fcbb.nq.gz
    ├── 23dd3ca47337554d76aea129a2b84075bc2f8d4a.nq.gz
    ├── 23e12363559a6d9fb96668ad221a44dfff935f3e.nq.gz
    ├── 24ee8eaad4b6423f417135a06c40a90744cec5e4.nq.gz
    ├── 26d2632ac99fb5828fb0202543679fcbb2521a32.nq.gz
    ├── 28880c431f1cfe64a20a8e60eb6bbeb12b0fd786.nq.gz
    ├── 29d92c8d5ad5cb2c36ebb93332051f41a9311e85.nq.gz
    ├── 2b40077ca2dbd4a00eb8e559e0282156adc06134.nq.gz
    ├── 2b7d54e8d171b86441808023f5eef852e3ef7713.nq.gz
    ├── 2c1ec87f7dc120a1fe3bc3731030bc81cf7d1dbb.nq.gz
    ├── 2c8023e148595c700f0e082fb2e958c59a03d622.nq.gz
    ├── 2cac56fb0b228f7a211c727f822b47aa9363cc0b.nq.gz
    ├── 2ccaf793644a1236e2bb360be26c20273b5d984c.nq.gz
    ├── 2e81ce1e9799ee166e00d4dd5a6f526fda60a4d7.nq.gz
    ├── 2ea63d593a26280fbeab0c58797aed810c0ff3d4.nq.gz
    ├── 2f78d588b48bce196bb58a1c07cb097c2e3fd9bf.nq.gz
    ├── 2f95215ba5cd3a16877dd78d816e284db57801c9.nq.gz
    ├── 3020ee4f05a9a3b0c97118efd417b0548fa99d79.nq.gz
    ├── 30418a7038963268296b2a1df2f2e12d40fcc21d.nq.gz
    ├── 31953bf24b4c6bab2610f12c25dee1c1596cc290.nq.gz
    ├── 32011fcda2b34bd347c8f74b59b9d81247b437d1.nq.gz
    ├── 33018a59a9162de275b969c7bffae02293a6c767.nq.gz
    ├── 33552bc3c53eca41a0e370b97b0d6865951a7f28.nq.gz
    ├── 3558c7ba4f44bd63066d711726213c39f9b23493.nq.gz
    ├── 3571391689d668763a28a004f521dec63b34d884.nq.gz
    ├── 3590c360459942021f86e6d65d0fa1304b6b5b25.nq.gz
    ├── 36e1e2b8df9282e82d00abc338939cc2859c563d.nq.gz
    ├── 3704dcbdeadd7a7d02aaacff735ccd7791207cfe.nq.gz
    ├── 372400f1a4f66bb4165c2d31b6eae21be852ded4.nq.gz
    ├── 396c7f1077389891d80b8a671abf618ead9222a6.nq.gz
    ├── 3ab00a12d2e08d0f31bb97c4b2cdb36f47f323ac.nq.gz
    ├── 3ab8b164c1f5c89729d8cb98b7b03f732a72d266.nq.gz
    ├── 3af90fb1893ed83c1a77202b84c2d0a2d15e8734.nq.gz
    ├── 3ba8e09ceead8e13306ebc9bd287247c582db4b6.nq.gz
    ├── 3d455194f77f70210b12af7507356e096307784a.nq.gz
    ├── 3d67a0c3f1d2a07a8a52641abbb4410e809940d5.nq.gz
    ├── 3e9b0258324e8663e086f6e3584080ae85de9385.nq.gz
    ├── 40f7ef3491407bd02722cf691e9165ee557a5e95.nq.gz
    ├── 41b8f6cf5bf5ece39047f22a69b37776c8164ad3.nq.gz
    ├── 42d4bf86b2f1b9ac356e4f6872023a46821d0e35.nq.gz
    ├── 443d8568e5de783c2f48dbde011141aa364b04d4.nq.gz
    ├── 4597f5c8a7ce6cb9ed6a3de0fbfcb254124eb606.nq.gz
    ├── 45dd9904fa338f877ebef40cc28dcf0a6527422c.nq.gz
    ├── 48ad58adccffd7f06cdc3f5557a28cc61643d1c7.nq.gz
    ├── 48c5407fd7ed3a2e8d9fb15d05155dbe14e95716.nq.gz
    ├── 49c421588825fc76f166d46dde587d92a06ac677.nq.gz
    ├── 4b771fb9c74880cee0ce394c59160b78539ddded.nq.gz
    ├── 4bb02e3d43d29a6f55150df7737ed64c36de2d45.nq.gz
    ├── 4c1c27e64450ee22c35257aa5ec1062eeccdfbf5.nq.gz
    ├── 4cd35a48932546406dbdedcf9deaf946ae3346e3.nq.gz
    ├── 4d4cfc81ccf7b21fd6f4e7306c088da1ce3e1606.nq.gz
    ├── 4e8546e5aaad9231f0ad064b6be85cc953a636a6.nq.gz
    ├── 4ea213aaacd11cec510351c03b5952a06562db0d.nq.gz
    ├── 4f5f29a7fc211703bc1c10a67ada569e0dee0c99.nq.gz
    ├── 4fb6de76b39b33e91d201dc2a37f919a105a86cb.nq.gz
    ├── 50cb466403e384cc68163db3fa58079ca9e4cb96.nq.gz
    ├── 50f6edab12a0e93fbfb193547ece6380a452f8d6.nq.gz
    ├── 525667d1dc333e8a841e3575750cceaad4a04ce2.nq.gz
    ├── 52610b0756a413c9777b52c8492530d7ff67567e.nq.gz
    ├── 52bc8c75790580e85b54e5ae355267882cfd8e7b.nq.gz
    ├── 52c288a78a591df4fa75d3243c7f1da8a236bfd8.nq.gz
    ├── 537eae46e77a0a6aa24da87063f31983413f344d.nq.gz
    ├── 54ac88df9377f741cff860b0bd27ed2c583ee36b.nq.gz
    ├── 55048de8f95547cabb1b7df725d9c24a6f176141.nq.gz
    ├── 557213ffb02ff7acfefb2572ab2c80736d3f1fd0.nq.gz
    ├── 55786765cc5660eafcff6006aed735ba29d19cdb.nq.gz
    ├── 55987dc8472ed7d3c67c89376a358d576a89d1ee.nq.gz
    ├── 55dff4bd44a8b7c103b29ed93351851cd4651e4e.nq.gz
    ├── 55f89170416dcbf01336716880121836c1548b7a.nq.gz
    ├── 55f9bfdec9d464ba45b8f1b26cb406ae49c90981.nq.gz
    ├── 5608bad9ebbf71395dd74673bd5c5aa7383f09e3.nq.gz
    ├── 56f885be1b187bd80fbb7a8618265dbb8a26ecc1.nq.gz
    ├── 593e7dc2474201e44e0977440371d2dff6794a33.nq.gz
    ├── 596dbe7d2e9e240848a2556f1c128ef4f41b571a.nq.gz
    ├── 59928f7b05ec9adfa9ab752edb455834cd8cbb59.nq.gz
    ├── 5a231ffd523c62bf87c835ff118267535e1ef5ab.nq.gz
    ├── 5a9f30a3fdc3a9e1aed387d42f95dc7768f09de6.nq.gz
    ├── 5d0f981914b7d151f0d600c47a239f4b0eac1e00.nq.gz
    ├── 5d0fdf7cb855385800800bd6549088c5b297620d.nq.gz
    ├── 5dd02d0db165eeb82c3432f7642de697aa467f10.nq.gz
    ├── 5ecf53581c00e9d5f44294910716df71da96fc58.nq.gz
    ├── 5f0263c5a6e881fe6b4e7828440467527265c0f3.nq.gz
    ├── 5f709d4dacc5c5f22b6fc506f9fb0a36b7174c37.nq.gz
    ├── 60edded2ca21791d8a22b78b2363342ef9df9aeb.nq.gz
    ├── 61ca25bcaaab7d4b6a67dba13e994bd3d3324244.nq.gz
    ├── 626471e1237d24e349c5be6a2c254240e9e9e7d6.nq.gz
    ├── 627bb38f55ebd41cce4d34f89676f8d0babcab48.nq.gz
    ├── 62ae39c046e6254c2d6373c49954e0b2596ba7ab.nq.gz
    ├── 62e04e6bbe72be7bb5f707f9d82ef9a48b0c1e52.nq.gz
    ├── 62e0524d0e4ccdba86d16b6e5c8259a9f05e807f.nq.gz
    ├── 62f885e03d0417c5c23eeb71f9df2b3ea21bafcd.nq.gz
    ├── 63ac08baa1f6941403dcbe6c47c3c270e2e7627f.nq.gz
    ├── 63e90268de25236bed845ed82bd3d5653769fdb1.nq.gz
    ├── 645efe9925087e02a376fa48f918ef8c88adb5a2.nq.gz
    ├── 64ac5a6cb63b4d8c4695059f4973706b7c3ade8d.nq.gz
    ├── 656253801df415c1fb279c1a311cc5d797349abb.nq.gz
    ├── 660078a0702b6e132dd9b00d73eb7e8039a172d7.nq.gz
    ├── 669b1f701f97ee75f4574698a33747d0df7ada47.nq.gz
    ├── 66d56f13e9cf9752f723df46993738048eb2c2ca.nq.gz
    ├── 68188cfea28b7540531f607b89cbcccea93e6097.nq.gz
    ├── 688fc5f0a8b972df1dbed2d8cd4f0adc9401ceea.nq.gz
    ├── 68a0d58904c66f6a4686a4c1ddadeb9727203b07.nq.gz
    ├── 69227a1441391203ed75813a57d3ba2158eaf647.nq.gz
    ├── 692adb82b816f891c8e991b25bceb42419dcc3c9.nq.gz
    ├── 69eef2e88242dc4755e29dfb19c6faa60835df2f.nq.gz
    ├── 6a5ab2502a1f53ec11fd23e376b3260200836f51.nq.gz
    ├── 6b5f3e515ef64cdc538d0a5c48ebdb467cb80658.nq.gz
    ├── 6b82145bb368e1ef5407ea0ae8c634e92fdff2a0.nq.gz
    ├── 6cc78af760692f34089d2d18b920882ff36bfd17.nq.gz
    ├── 6da24a3ed7143ff42e97aa014aa45e887d4b4c8e.nq.gz
    ├── 6e03c18591ac4c647f1333fe54b9da45fc8de5e5.nq.gz
    ├── 6edd65e3d713189cf7da21ed67bcf9ff0b348c6c.nq.gz
    ├── 6fbb4a4849c4a9e219cefc813454715d55790558.nq.gz
    ├── 70a3dd6ea1d1dfaae93bab5432d2103dd5c1c45f.nq.gz
    ├── 70bac7f81af7e580059b86da2f3407caa2b09ea9.nq.gz
    ├── 713783ce97451aed78ab6191f41c6ba4d0eb878e.nq.gz
    ├── 7231971926d2b91188705679989453675e369ea5.nq.gz
    ├── 72e015a77b8ca0d222645a0739439d11c828a043.nq.gz
    ├── 72e64f51bb5e3682469871f0f0f2333641380551.nq.gz
    ├── 746faf254a5639055b6e3aac70f105c3e05ac618.nq.gz
    ├── 74aba81450616305ea81a880821fe7822eeae220.nq.gz
    ├── 74d92357dd0157ced028a78827247a8cc67061dc.nq.gz
    ├── 74ec67990f4e84296e470336a1c262cfdafa6940.nq.gz
    ├── 7540ce0b51729ea327aa649e09b7ea32496e5e61.nq.gz
    ├── 754dc3f7265bbc6894e675ab91aa70d4c6229d68.nq.gz
    ├── 75aac4b7d55c9988be6ee11247ca5ee75e41e6aa.nq.gz
    ├── 76002d2f30dea18781b2f8bc69964106aa6e485d.nq.gz
    ├── 773613dc0a8805642036be65ccb8d832e26ac0c5.nq.gz
    ├── 778e5d847327b261cb862a56e41837dbfd6bead3.nq.gz
    ├── 77e04705292d2e0634895a6ed25e8aae0f0a94f0.nq.gz
    ├── 77f767547f6db62d4b33c4c426ae302242a83e4e.nq.gz
    ├── 7811cf1e8429bcdfde9ade3aa03f90091bfb54bf.nq.gz
    ├── 784614a0d5f778b33cc4685f6312a243a344c440.nq.gz
    ├── 78f75e2102aeb21b1a66e283e123eeef508de79b.nq.gz
    ├── 78fcf8630eb55ac5aa4c92622391e5d61c4c02e8.nq.gz
    ├── 7a8e21c002d74384fab8915608d3fdd9da2f63b7.nq.gz
    ├── 7aa6c5bb76ff54af42f8647ce699bf3ca033753f.nq.gz
    ├── 7bf65e6168aa45031eea4efa55486913ba2bd5ff.nq.gz
    └── 7c217ca05db5c745638440aafa06f1d41479e841.nq.gz

7 directories, 200 files
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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[plotly/dash-ag-grid](https://github.com/plotly/dash-ag-grid)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
