# Repolex Knowledge Graph of python-rope/rope

RDF knowledge graph data for [python-rope/rope](https://github.com/python-rope/rope), parsed by [repolex](https://repolex.ai).

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
rlex download python-rope/rope
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 22f5e50151c76f8cd9718e264eb44e692ca82cda
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 22f5e50151c76f8cd9718e264eb44e692ca82cda
│           └── chunk-001.nq.gz
├── blob
│   ├── 0038ef9228d8fb80a3aaca5b86319ecb511039d8.nq.gz
│   ├── 0044434cc0edb3c4f02fd84541fa308565c8b9f9.nq.gz
│   ├── 01076ade5d52eb1e101b509b8aa24fc5055bdcf8.nq.gz
│   ├── 024c8e3463eb0e7743fe5af17fd143eba6d29783.nq.gz
│   ├── 02659076665f36c2a3be628502b673225f619f7f.nq.gz
│   ├── 06e4f8d8b848d669eb5189c382034d43a0a60a18.nq.gz
│   ├── 072ab1ed8edba479a6c912d7c9a46db8f92900b6.nq.gz
│   ├── 0799ff13970d01d6ea26038d9956d96df94af76a.nq.gz
│   ├── 08be8e933e896cd12e2075689cfda8dcde36cbb1.nq.gz
│   ├── 090b103374cf2279f315f09fc7c77cf60dbafab7.nq.gz
│   ├── 0974b11e7d3a8b2e3b6e3753ca2a037787ffdbda.nq.gz
│   ├── 0a041280bd00a9d068f503b8ee7ce35214bd24a1.nq.gz
│   ├── 0d3f837ef48aa3892a2f0b20aae33f0193449bfe.nq.gz
│   ├── 0d9d972c1e22121d6c365abbcbb67a47350f44a6.nq.gz
│   ├── 0e16accd7206a6a4907062f6ae2d533695d44c63.nq.gz
│   ├── 11ee6f20e048c661cf078c73bb4dcc5f99c9639e.nq.gz
│   ├── 11f58ccfe020c3bee00da16157c61e1b922ba05c.nq.gz
│   ├── 12a62681620bd3c5fe941a6c8e741764dc7dcf00.nq.gz
│   ├── 133652b20833988566360f07944c8efade3175e3.nq.gz
│   ├── 134b48b4a4794edd504b6066edab066a9e4cafe6.nq.gz
│   ├── 13edab91cf954de3a0ebff2ec564d7266484a3dc.nq.gz
│   ├── 14b3c89bc7cbdf3e819198f89de874a64fd7369d.nq.gz
│   ├── 151344bf66a509dd4d40142c6f3924d8c7fa835e.nq.gz
│   ├── 1a5b5135ffe846cbbd3ee67ade0f0761b4a628ce.nq.gz
│   ├── 1a8a92c78feca0c2484cf7739424adb98d9b4df2.nq.gz
│   ├── 1acbf17308b5b019d396c8936570efff67b3337a.nq.gz
│   ├── 1b1659fad93861b718a6340d3b77818d0c744e2b.nq.gz
│   ├── 1e791635070075eda8b15cadcee44a9ce5f9d44f.nq.gz
│   ├── 1f1b37d835cbdbbba9be87cd54666a84dad8aaf6.nq.gz
│   ├── 1fc4f474772c5525dcceda992153b946b252bdb2.nq.gz
│   ├── 1fd1684e35edac187c70a88eb417476dca38e9e8.nq.gz
│   ├── 2381c8472237d5359ffae949b058ea3f4d0f3799.nq.gz
│   ├── 257048acc09f572c551d70512483a83218982f66.nq.gz
│   ├── 274e8ef4f474a0d942e4bd2ceefc00a5ca2f4fc2.nq.gz
│   ├── 284a3d0dd3c401eb63ce622a71e40d01b091cd88.nq.gz
│   ├── 28f4184e3ff82fa06970aa25a4212871d0f130a8.nq.gz
│   ├── 2e8d0c0cba9859fba5ab830d4e49cad5b3fe3ef9.nq.gz
│   ├── 3078f7d65ceba58567e5743825e065ed60a32ffc.nq.gz
│   ├── 3198c26de5c8643a2db2365954ee2a4a1cea6c74.nq.gz
│   ├── 32547891e2a7752042be48cd28f8d89243ded082.nq.gz
│   ├── 32ee31f98f2eb1afb4dca3b024dc3863a1c25a62.nq.gz
│   ├── 3396cf163c0645a968e7c937b6150a72927a0a4a.nq.gz
│   ├── 35d4973379b9896824d09bf660e6b715f4619d7c.nq.gz
│   ├── 36514312c1b8a299105686d0a44165caa4513068.nq.gz
│   ├── 37811e15fa31915ae2996fa173108600cd59a52c.nq.gz
│   ├── 38468371396d11ff264e8fed4aa1c5da9f61f28c.nq.gz
│   ├── 3aa8e7fc364469e9d98638712794c6058878303f.nq.gz
│   ├── 3adbab7899e59b2ec07c46fdf5a5d467b4f3b576.nq.gz
│   ├── 3b28697c6832b700f2bc1ead566ba843180c86a8.nq.gz
│   ├── 3c74911b3c25e7692754a6b26bd18ba3401eea93.nq.gz
│   ├── 3d982a3242acd5b89f7fa7568a274f8f0592e39f.nq.gz
│   ├── 3ea5e8759df5f12c92fba7216858505a265cb5bd.nq.gz
│   ├── 3ece79688aed8e329b4558f3dab0e2a9151a761d.nq.gz
│   ├── 3febd2197d8c84ca0057bd05421d1e30c3b6876f.nq.gz
│   ├── 4061a9604e8551e02c55b8758547c754608b7f5e.nq.gz
│   ├── 406f102dc55d1e4aab9448463c16a3460ed59b55.nq.gz
│   ├── 43815ba430d58f1f4ffd428e154a1ab70957ddf9.nq.gz
│   ├── 47e6e8c7f50e24bdeb00f164f6930763d611ef26.nq.gz
│   ├── 48f0612c85121a96c373804ed7dc234335f741df.nq.gz
│   ├── 4b34d58d3338c82c049956099926bbbb03596aec.nq.gz
│   ├── 4c7580cce1f7387440b66af1309d673696f14eb6.nq.gz
│   ├── 4d0489fafb49d20a750868886fec2d310324e01b.nq.gz
│   ├── 4d5bee1ad89fc3da18b1b337e687b77e82d2acb3.nq.gz
│   ├── 4d9cd5ccf6b75af7f6d04a77f69a3531502ca66d.nq.gz
│   ├── 4f061590287587f9f6cf0a309c4793c16696e270.nq.gz
│   ├── 502e183faf5457c63f77989a3103eeaf6905c565.nq.gz
│   ├── 511e1a541b0b7f4def54185f28db4051f3df644d.nq.gz
│   ├── 55a4b2d03f80417d976be0070143a25031357607.nq.gz
│   ├── 5655419036b87f3a3dbe5c8853b7cf8997d61944.nq.gz
│   ├── 585214b41bc65845d321e2362262fa11fbb74109.nq.gz
│   ├── 5a50ae1ce8e639072d928f5a4f949f21a8ea9e6c.nq.gz
│   ├── 5ccd80d2a9599fe4d7775e9b94cacc798d22dfac.nq.gz
│   ├── 5d8a0c8fc70e431a70a9b79037379ad17ed2c05f.nq.gz
│   ├── 606849326a4002007fd42060b51e69a19c18675c.nq.gz
│   ├── 61364c1dd4604a29698c73dd8b1d81e7c3d0ab40.nq.gz
│   ├── 619b400954aedadedb63e2b1259daba89ce90561.nq.gz
│   ├── 66293e6801cdee34299aa6fee0c6611acb03c225.nq.gz
│   ├── 687dfb55a5fbab3df00f96d6de39a2267b490841.nq.gz
│   ├── 6a9b4c2cdb7e2de527702e31f87b769f1adff714.nq.gz
│   ├── 6dcae495c129f44a8e38267311ac9c57dab637b8.nq.gz
│   ├── 6dd16ab3b968679953c06f21444c6155547368dd.nq.gz
│   ├── 6eca802581f6c61aa34e71468015ca6468b316bc.nq.gz
│   ├── 70b7143bc6a9c0e3b6c86553263e96f2b031230f.nq.gz
│   ├── 7351fcd9e98213172d41b7011280e54aa8fab7e8.nq.gz
│   ├── 73f48229739c17929a4a4ecb8a6d303dc690db08.nq.gz
│   ├── 768d30b7d7041c40eae0e3509e48a84747e29cc2.nq.gz
│   ├── 787cce497330c44d570873e64ec488188b1fc330.nq.gz
│   ├── 796699986760a4a4615288956a904d7473160f73.nq.gz
│   ├── 79f514ad02fdf5f0db909db166b31c7f445f4f25.nq.gz
│   ├── 7a70a034410ad3e64cd41b763ab4982200b08edb.nq.gz
│   ├── 7ae8fb718dfae7deec0704ef5e7e10b9afaa0fb5.nq.gz
│   ├── 7f197a0a106be0cb58aece4584b3ef63b4b8c2e7.nq.gz
│   ├── 8245e626a449a1d5f6a2d4391a43a8b325d3fe9c.nq.gz
│   ├── 85ff18e5bce65752136848cf6a650bb83a559533.nq.gz
│   ├── 87c356864027b5f3c7ba81cbf03ecbf890cf4a0f.nq.gz
│   ├── 89c42db65e715a402db4a668a2eaa94b73c5e537.nq.gz
│   ├── 8b2186d2af2e79eab01622774b40bcfa2044291d.nq.gz
│   ├── 8cf1e00f3ad206322f1cf44bd4ca9e2dbf583fbd.nq.gz
│   ├── 8cfb2d7b99119e79ce3165dd2b2d1f13059cedac.nq.gz
│   ├── 8ecf244527d57e5e4b9b527b54b40ac47ef6e8c8.nq.gz
│   ├── 90f235d32d951e30c331d80c251f8fbd799f850c.nq.gz
│   ├── 9303fb15b273ed228ae273d06f356bee7e493a3e.nq.gz
│   ├── 93583b7917c2452c73b9bc85e5b6e1c1ac92c678.nq.gz
│   ├── 93b30d0beaf5418cdc471803e5ac25941372fcdd.nq.gz
│   ├── 94089b5a8222daba7c58f19e252c53a08b13ac8f.nq.gz
│   ├── 954237b9b9f2b248bb1397a15c055c0af1cad03e.nq.gz
│   ├── 95bd156912ab484a7c5cb05856163c5537e86fdb.nq.gz
│   ├── 99ec1b76bdc7debcc982f8938e8822fbb5712f31.nq.gz
│   ├── 9b48cbd258c59becf7b9da471ce6bb93276677df.nq.gz
│   ├── 9c8bd1611e6d883562a2a2adf85822ab7a88c84f.nq.gz
│   ├── 9db6b77f7dc0462393e315f4a7d517d1b99334da.nq.gz
│   ├── 9dca8ccf58a01fd405b227821efc7c6e5fea5d7a.nq.gz
│   ├── 9e0cdeaf301ba9a70aa6cfce89bae059d58329da.nq.gz
│   ├── a151465f2989654109894c7ab8eab5a3a5ef087a.nq.gz
│   ├── a2ebd49d12103bbeac50df20bea804d079409ed9.nq.gz
│   ├── a46a7c0183a7d37bfa1a3e5fc25ac0d7b5f9c1fd.nq.gz
│   ├── a4eed44d3409949b1e52f0a09a12c7c733816414.nq.gz
│   ├── a62b4afbf375855d8605d0add2e4f629b2330a6a.nq.gz
│   ├── a6871f867a4686ddc2d450f8e75b2c7d893ba81c.nq.gz
│   ├── a6f798b261abcec20f8b850d559a977947fb22f0.nq.gz
│   ├── a8795b98837f1201147cc9ffc8c07699fe35ae27.nq.gz
│   ├── a91568bbd7920ea54b542e4bd88b68d3759a2891.nq.gz
│   ├── ace4261f3a49eadea4e5ee65bfcf977ff18ece0c.nq.gz
│   ├── af2d15838ed35f4d5dc29c0bd06f82709b05dc4d.nq.gz
│   ├── af94352fbe1de25ab091d4c2eea09a37da5cb1a8.nq.gz
│   ├── b136cc5c91b118cf545f3d6dac4bddaf178e5439.nq.gz
│   ├── b2160180354710daeb058f6f46f5846b6d4e6928.nq.gz
│   ├── b2b3377ea178a095ea4766a3e3a28ae009147df6.nq.gz
│   ├── b3e7311ecf36b17323fbeed66a660325b8fb436d.nq.gz
│   ├── b7d7eeea9be939250c9c69f78118fd08d367458b.nq.gz
│   ├── ba7951d5f88f1ce884394f539c42b9c5c19289d1.nq.gz
│   ├── badd01dd8b21b098393330f8e8a1eae5c6fefb35.nq.gz
│   ├── bb65c1465e1aad897e46571bb2452844e4a5eed7.nq.gz
│   ├── bbcbbe7d61558adde3cbfd0c7a63a67c27ed6d30.nq.gz
│   ├── be14f2d710856f2de80adb5a4ab39ad42c8fd50c.nq.gz
│   ├── be3cffd62dd0dbb408179fc435ca3e6acc60732c.nq.gz
│   ├── bf19188224d90a55f5a0f0120f54b11678983ea8.nq.gz
│   ├── c436428b4939bb173013cfec5553e99fdfcf397c.nq.gz
│   ├── c4beed7fca24160acda07bbcb77855baaf25311c.nq.gz
│   ├── c6457044bff570b9e7e436199a80a2f309358af2.nq.gz
│   ├── c6671b084306ce96ef6fd60508ddeac726f34f9a.nq.gz
│   ├── c6e77775f33ccc68e8bbf5236d7e67026586feff.nq.gz
│   ├── c96c964280766f2512e6e052769efb27776f1e5f.nq.gz
│   ├── c9fbb2edb10ef196f9e5cf004d8584208dee739c.nq.gz
│   ├── cbc9a16e441cac2f1a2cac787f067b5406f2c339.nq.gz
│   ├── cbfeecfd43b2026caaaf56311aa793fd612780e5.nq.gz
│   ├── cc376e0bcd17ba3fa55272e819052b6389f27bb2.nq.gz
│   ├── ccba8f2e696f54b9a2ec9b615cfdcabf6387c180.nq.gz
│   ├── ce320e7ea2216b0b6a90fed72b16e5ff64b12c28.nq.gz
│   ├── cea93946a904a560a1d7b0128a7b203f8eaf3c2c.nq.gz
│   ├── cf1330e80d509ef13c1e9f3cf7f4796c73ea613f.nq.gz
│   ├── d335665400b9e1a53b1f7f459ff48c54e4970dbc.nq.gz
│   ├── d42ec14f77963606bf78d32620d44d9ebeac36a8.nq.gz
│   ├── d468fe90be18eae2ebe20252246cfaf9f7f07775.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d4df97d2582fdf23a9b05c0332bc455f013da69e.nq.gz
│   ├── d55aad4c99b5be8754d43c5b95787ab518d55e8e.nq.gz
│   ├── d60702b32d7d696ea7bc1d05ea5fea92cca30a26.nq.gz
│   ├── d6f5f60d274b6c3185257452609854a528992838.nq.gz
│   ├── d784381ca5e415ac09309ff8732a43ff1ef90464.nq.gz
│   ├── d8b8da0866c42576a0a3c7077e2be6d8bc318f6f.nq.gz
│   ├── dc02c410092c5b151f94b88443ec85c6006115ae.nq.gz
│   ├── dd5bec3620cfd146bf770ec1aef97531cde9cbad.nq.gz
│   ├── df60c6fbb14dc2852da5ac90db9d5512d060f256.nq.gz
│   ├── e5663b51236e5e32ecae170191a5d283a668067f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6d098dee4c81e473b1c35524f18f53cd5fba5d8.nq.gz
│   ├── e742e2cf0e0a56452f6f38e46b9c7ba0f774f55d.nq.gz
│   ├── e7d0e3600917c6e15ccb18a610d454f5486505d9.nq.gz
│   ├── e936d516104d6066e725e97b15b7997ad88db930.nq.gz
│   ├── e99310a37490a516274dba21184fdad6dc2aeb0a.nq.gz
│   ├── ea19722ac99b4d7408958d8e338e9ee9b7560a35.nq.gz
│   ├── edc2b623211bf0a593db353098bd3a835e4d4d31.nq.gz
│   ├── eee5165f743ecd66c57ab4cfcbaf5c995dc64565.nq.gz
│   ├── f0b6340f3e4035b48fbd67fe30bf432d6b5e642a.nq.gz
│   ├── f13aca6d1983874b5f86fd8a005503683b6ac567.nq.gz
│   ├── f3320f450e71b09bfb03266196354bee97b395b1.nq.gz
│   ├── f3467aed4a4b7feaf30fa50f0b9a7e17b75a9d5a.nq.gz
│   ├── f35b2252158ed08a4d9e3641499ebc3cb9e30006.nq.gz
│   ├── f4d794a44ec9047afeaffc4dedc189519983e63e.nq.gz
│   ├── f56f818099636088bdfc3c0e12590442d573d176.nq.gz
│   ├── f829de31d22bd35833e9a764428e879c8f55abde.nq.gz
│   ├── fbf1b34dfe3b21d572a1eca179f20f3724000805.nq.gz
│   ├── fc6bc90c92e2fdff5485577d81aeae206adb060d.nq.gz
│   ├── fcdd179649b536e5d4c05d4685d07faa15c514b3.nq.gz
│   └── fd7f1d2eadbc10a30afc79a713f6c864175dcb9a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 22f5e50151c76f8cd9718e264eb44e692ca82cda.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 194 files
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

[python-rope/rope](https://github.com/python-rope/rope)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
