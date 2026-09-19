# Repolex Knowledge Graph of mhammond/pywin32

RDF knowledge graph data for [mhammond/pywin32](https://github.com/mhammond/pywin32), parsed by [repolex](https://repolex.ai).

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
lexq download mhammond/pywin32
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 58f58184e4374cca9d177a5ca31c95705367df68
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   └── 8a2bb0337d9fc48b651c18db50f33a7c17827d66
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   ├── 58f58184e4374cca9d177a5ca31c95705367df68.nq.gz
│   │   └── 8a2bb0337d9fc48b651c18db50f33a7c17827d66.nq.gz
│   └── repolex
│       ├── 58f58184e4374cca9d177a5ca31c95705367df68
│       │   └── chunk-001.nq.gz
│       └── 8a2bb0337d9fc48b651c18db50f33a7c17827d66
│           └── chunk-001.nq.gz
└── blob
    ├── 000611abed93d22fa34e7c3c068dc04184ec77fb.nq.gz
    ├── 002fb0425b1355b2727a2fe965b38eabaa0a772d.nq.gz
    ├── 007d3aa82458344e5fd3f33600371c3a98a410e4.nq.gz
    ├── 009670335af8981063dc6c4836767a2502553d5d.nq.gz
    ├── 00adf515945704e60f145a959741291e4fe365db.nq.gz
    ├── 00e54864029e600b746dcdf5b91f71fcf3ffe2f1.nq.gz
    ├── 00fc77a8316d8dcc5b1eda5aaa74e228af0bd0a1.nq.gz
    ├── 0110526c63b2a31a98cb78c0083b12e815617e63.nq.gz
    ├── 011606927b75b0a2207586eb6924c79a401748f0.nq.gz
    ├── 012055fb84d4e273c4bbf4314ceecfa55f6b85b8.nq.gz
    ├── 0126cea50c194883b59d0431fc6b2b920f6e1598.nq.gz
    ├── 0146abdb068eacaf2761affabb6b860a13067854.nq.gz
    ├── 0147de13ac8e6ab08b944bb0433bf1ab35291cf7.nq.gz
    ├── 0148e15f29373d1d8ca86b98234a52800d891811.nq.gz
    ├── 014f78522b9cc76d1b37430cf720c5dd588f799f.nq.gz
    ├── 0156c0c1a9900a10a6c24743228fc8ceaacdf0e5.nq.gz
    ├── 0169c8eb51e625e54daeec48f9f07db692a4ae65.nq.gz
    ├── 017174cbf4d6014a94545d3f81caf41cce89fce9.nq.gz
    ├── 019036a3b64647ed55a71c4d064d80936f33369b.nq.gz
    ├── 01b025c4aed89a7d19d7481a4239360e427c72d6.nq.gz
    ├── 01d406d0d076701d562f0b5b1c86b72f9d0161e8.nq.gz
    ├── 01db00e0193dac4df2df4d80644eabb8ed529690.nq.gz
    ├── 01e62441a1a521ec6d2a75c428e3b61579bcba89.nq.gz
    ├── 01f48f0d957c5cd99da6290a45b344829edd29b2.nq.gz
    ├── 01fa1f472bad1b13c5deae1863450dff766b0d9b.nq.gz
    ├── 022c3e7e11669d95f37ac7767c74691deb39536a.nq.gz
    ├── 022dbbe74fa30789eb1603725b437d025358e9fd.nq.gz
    ├── 025d76ba821ed970732e9ce60b1584315428fcc3.nq.gz
    ├── 0282f8232b93a9257e27b84c33a52b8be8c631b6.nq.gz
    ├── 0299ea0a50fc91b403132b6b5f05c60e06a82e42.nq.gz
    ├── 02affc8e9fcc29f1f747fb86720539e380efb275.nq.gz
    ├── 02bb620f4d1d4506c05cbd49fea8f050506dd9ba.nq.gz
    ├── 02e1a7da610026e26a37063cb88d021ac688bd03.nq.gz
    ├── 02e2e2bd0be382195f519310a1b0ee495fdc7ee2.nq.gz
    ├── 02e358afd78a5483a21b3147a0261549e2f97cc6.nq.gz
    ├── 02e4cad0a92d5d2ca4c12c20fae2f1e9996efd10.nq.gz
    ├── 02e69a6d51cbf62f1f84829bdcc9539b9e588173.nq.gz
    ├── 02edbd55ff1c68f7c0c01abf94cbd7adca3d817a.nq.gz
    ├── 030b4702517872f5c073a1151a567d3fab3a6e1a.nq.gz
    ├── 0318c988dc6367c6539bf2b733ce5446361ac82f.nq.gz
    ├── 0344debd78eb506f6b79e7362376d50fd23bd862.nq.gz
    ├── 036e2ebf81870affea3eaadf9010d6f194763fba.nq.gz
    ├── 037f215e90a9302cc07fa849b4082d680d1bbecd.nq.gz
    ├── 038b58fdb3f716e4fb5975d819be45eedac3930c.nq.gz
    ├── 03dea5e73d36b754a9d25414a7684b55c6fcd006.nq.gz
    ├── 0403ca23821ea242767e7b7a9ffa730cbbfb35f8.nq.gz
    ├── 04206c8ad7bcb9b0d06777d3cbaeccfb0003f2ea.nq.gz
    ├── 043c5adfb9592531c594f1383b12574231e4a096.nq.gz
    ├── 0457b475b34b1e2c8bad85ebf9f88a2a9cdffd85.nq.gz
    ├── 047120e92102af6413998905f1d416aefa106289.nq.gz
    ├── 049cfad59a525b0a3fba59a40b867d476812766f.nq.gz
    ├── 049f288b2f5b2cb7552097240f2cb7b250a27153.nq.gz
    ├── 04ad288445b2f6bb0786fa00858e3e93fd88507e.nq.gz
    ├── 04e6bf14ce96243c23ad46154a2842fe19348093.nq.gz
    ├── 04f0c1e1888d70ff502d2fa951e0391c44f79ac4.nq.gz
    ├── 05028fcfc58b318f88961303d6bdc3e4c9176a5c.nq.gz
    ├── 05161d4433d86802e0c1253ba10ba4bcd4f3b58f.nq.gz
    ├── 0517af58a558cefc916e322eb7fcaa64ac9c3c31.nq.gz
    ├── 0521e5e191645a37107915126a8e9b1bc67bd44d.nq.gz
    ├── 0554d9457a062a8e8188142468354ba8bbe95529.nq.gz
    ├── 058dc913e545e1be525cc91728dc7a1646d6cad7.nq.gz
    ├── 05a613f0ac2a09bca0689e6888330cee7d70d8c4.nq.gz
    ├── 05cf63bcf9fa2ae5f079e46d6941db17c8eb218d.nq.gz
    ├── 05d915bd14ee78d037fa5d3ea37e2f353020d769.nq.gz
    ├── 05ee8fb4af2e453f593de89c473f688fc18d9fc4.nq.gz
    ├── 06067ef9aa75dd0b69cfa815cb74fe43b65af6bd.nq.gz
    ├── 0662b93363fb96010cdb3f958954fec2610a0b19.nq.gz
    ├── 067d444f147adfaa108f1ec961c65413e5d6db96.nq.gz
    ├── 0690629c6186278eec0eb5904a86984541820831.nq.gz
    ├── 06a3f73bfa15219422f3069f0fc361c852f9a96b.nq.gz
    ├── 06c63fa85c502a1c7e65e3e600144a0c1d46f4fe.nq.gz
    ├── 06e7c1791fbe22d5e0e5cb8ccf20515f33952e93.nq.gz
    ├── 07093b9a804797c0fe5264aca2ac2c0aa5386aa9.nq.gz
    ├── 071224dc22d54e1dc0b99ddc22182e7ac3306aca.nq.gz
    ├── 0716c66b7de13fe3213b9f407076aa99ed582e7c.nq.gz
    ├── 071ceb1dc62a959abb5846cd718a45beb8b20898.nq.gz
    ├── 0721eb716068295b31d787b2a3bd0a098b15595e.nq.gz
    ├── 07756fdbd484c30c6dd888a3b7aa289e7d36f2a7.nq.gz
    ├── 07affcaf0c67c6f7f17617ba1fa34740f1a7a4d7.nq.gz
    ├── 07bcacbbff46b7ba54bd1b19f5ad47a24aa0550e.nq.gz
    ├── 07bfea84047e6f3e2f548406b03992cb7685afda.nq.gz
    ├── 07ce322080c961f8632211ab26320825b7db8213.nq.gz
    ├── 081c686d4a7fef6c4ff9d6527a52503b1e66bf52.nq.gz
    ├── 082f37b8401f7c21d6e51f3bbb6a324562c30891.nq.gz
    ├── 087841202b398d7c8225adb6dc6393b1dd471984.nq.gz
    ├── 087c49d6487f0c1654d6de850d4a90a125389cbd.nq.gz
    ├── 08adcad00e8e5f140a237d0bdfeb3c340f1a07a1.nq.gz
    ├── 08ceb34a32c6377b0417c39b1f6adc82f5afce16.nq.gz
    ├── 08d6ad9ca1937aedc9bdae90ef75d69f0cf2ffe6.nq.gz
    ├── 08de5cf1f7aa9ce89f3417d65b6bbbf921d7960c.nq.gz
    ├── 0938b03221d6f2bccb25a0e65a8167f7f0bc904b.nq.gz
    ├── 093efae755634ec66ab0bee96a1d5d3bf6c10624.nq.gz
    ├── 0941d7a75d0e2933af366432fa6b609294ad03b6.nq.gz
    ├── 0944fc398ccb44ceae4c46c62d25b5096eecb14d.nq.gz
    ├── 095675ee5b9c605e07c6d534622d57a4b895e064.nq.gz
    ├── 095eeb44549de1f4e5c589056579ae2ec792867d.nq.gz
    ├── 0980da37e1cd8b9af969dd4a2ef4c2fcc27e7bd7.nq.gz
    ├── 0981b62284aa583d4750d3492b6ef892fa851d88.nq.gz
    ├── 09832ecf15e310e9c524a7d393a6cfbea833cb9b.nq.gz
    ├── 09a7ef8679437a05885b3b0cf0a3e3a87027226d.nq.gz
    ├── 09b5edd1036e974a8e48244f94b614c172aeaac5.nq.gz
    ├── 09d6b17761ea619ca8be8c43179950833b3271ab.nq.gz
    ├── 0a1257a6db8f13def323152602727bb01d334c8f.nq.gz
    ├── 0a1264bfec5be91a8276df59086092a671b3d55a.nq.gz
    ├── 0a15945524c3693bd4354f937e40dfea075ba9b1.nq.gz
    ├── 0a333ca2aa39dc854bfc68655859f4caa8ae564a.nq.gz
    ├── 0a524e60dbed080374dee6c39ac7c4c93a5c4715.nq.gz
    ├── 0a575fca050f4a154a06b57c07809020a354e7e7.nq.gz
    ├── 0a7765329e6f84387b09a0c292a1c2f38c5e68ad.nq.gz
    ├── 0a824d07dede5a6c46e9e8db835c7d3cc6910e43.nq.gz
    ├── 0a92bbbac68da0b795e9f05ff68ce890cb26add7.nq.gz
    ├── 0a9e38d58c72b00ea8848e58b55b1b990514711e.nq.gz
    ├── 0aa8c4670935563500800af679e008edcd2f2820.nq.gz
    ├── 0ab79a986e922344ba400749e388c004963dab44.nq.gz
    ├── 0ab85342af1d3876959771a441fa1ac5933af093.nq.gz
    ├── 0ad8748af3f5ca9119ddfd327caa9982094dafee.nq.gz
    ├── 0ad8c25750eb6e3d9ea5382faf8dfd91ce10e85c.nq.gz
    ├── 0aecdfd4263da1d9731f8cb4941d9cd25e8476c6.nq.gz
    ├── 0af42a50555f43cb9192243bcb086d26ec1f29a5.nq.gz
    ├── 0b143ef3e5b75b1974d3043578c6e22a4e604cde.nq.gz
    ├── 0b25bf2b18281ec4d233a4d591e390c8dc88ada4.nq.gz
    ├── 0b454ae131e9f37ae672eb0ab8e84e973f635009.nq.gz
    ├── 0b8b2c6199731c1f9bd19ec9f777fa32ec601c91.nq.gz
    ├── 0ba96851614334d5d094fdbe8378838271b2bb9d.nq.gz
    ├── 0bb512639aedca14004378e9043163e6ce2afc74.nq.gz
    ├── 0bd57a81d3a6ff5506b9e8ee1fa24ea305606ada.nq.gz
    ├── 0be53b114f559e79b98b7b13cc3890c3529d18c0.nq.gz
    ├── 0bf81e0c5fec463e86ea9f47154d76326f82cf36.nq.gz
    ├── 0c0f61bcf508ffbcd279c2f15cd319b1ef75163f.nq.gz
    ├── 0c3c18e8f2451f8711b0182629d19e59bb68ec60.nq.gz
    ├── 0c5f20e8ee359ee5b1196db473aa2fccc2342bf2.nq.gz
    ├── 0c7f46d3455a4e137f20c9ea771235d0b2909062.nq.gz
    ├── 0cb93d5d00ed853063965967ba3f1d9a39dde037.nq.gz
    ├── 0cc97b2797619c45f188c63d829be3c2fec464ce.nq.gz
    ├── 0cdc6e3617b0ff58947a260c757a7beef35998f7.nq.gz
    ├── 0ce417c0ef51b80f66032f0bd93e0e5d4812fa98.nq.gz
    ├── 0cf42ab4523c8d409c024400bbddbb12f9d04fe8.nq.gz
    ├── 0d0b8ac9c986d0e3eb5cd04b79a9902d91b896bf.nq.gz
    ├── 0d10d1207151b61def4919a5d89c92865826ccab.nq.gz
    ├── 0d1384e39d38f5ec20af7020a572ba20fa9f2cc5.nq.gz
    ├── 0d173963a20e8cda9e5f15a6bd61da25c2b9aa66.nq.gz
    ├── 0d19cefeb537754e033ee407ea4fe6f513fa9280.nq.gz
    ├── 0d202d68d3e200f50cd6d6038356849e9fa7011a.nq.gz
    ├── 0d23b57179ce4e20b135843ae8f418b5843e9db8.nq.gz
    ├── 0d24cca1cccf1319e1c5bc5ec3fcf43777c5c9eb.nq.gz
    ├── 0d37cb27bbfa14fbe3f97aebcbee316542d47f2f.nq.gz
    ├── 0d5bbc628ebfea3cd5b1102ff62dab49bb39ef96.nq.gz
    ├── 0d65a2928962860cf8b675b5192a43b165f31350.nq.gz
    ├── 0d6a621f2193758453f3a1ca3201389398b0cce3.nq.gz
    ├── 0d7a75c7276d44c2604e67e4246e8beeb44aa09d.nq.gz
    ├── 0d7d646e895b4bb839a73142890893126b70387a.nq.gz
    ├── 0d7eb2cbbf4fd4b1309ba0e54354ae7e381364de.nq.gz
    ├── 0dae5a5a2cde902f6ac0c5b95d693332a9ec0edb.nq.gz
    ├── 0db30bcd5a86cb587dd907d378ea49f9afd71d9e.nq.gz
    ├── 0dca29ac8a6bbab2b184b94d544929eda14c05cb.nq.gz
    ├── 0dfda4f1eb3a615b9de1508afc43e036643275e6.nq.gz
    ├── 0dfff283aeb37c3d4aebc370f7f216f0adc3c09c.nq.gz
    ├── 0e1645503badf6cd70d40c1a353f3778adbb410d.nq.gz
    ├── 0e29e1a8afb1b54a46e5acb45c6e9347095c1637.nq.gz
    ├── 0e2ddda9a1f3ff8b895619f42acf9b4d1272a31d.nq.gz
    ├── 0e4576064e9eedac13e7cced2b2b929f11553d19.nq.gz
    ├── 0e4906ca7c83cd026cb228cb302476a84354db76.nq.gz
    ├── 0e5c20ad60040d2776ab54de9dfbde0b35722934.nq.gz
    ├── 0e5f07d4d4f3c0d8dd63c92d71baf0e8506022b3.nq.gz
    ├── 0e6670d0e03cb2b15e9c8226c1b38dd9e738eab1.nq.gz
    ├── 0e9689121d9fa41390fd07a87f13bfe1739aa5b3.nq.gz
    ├── 0e9ae6950208205d58547872c7e105e7ac4c071b.nq.gz
    ├── 0eb38423e19ba6afbb3dc72cd43c0e5439ebb62a.nq.gz
    ├── 0eb7c2d897c821701561d8112df6cc30f4ddcd00.nq.gz
    ├── 0ebdf038a77125491a65381dae4d21fe7243bfad.nq.gz
    ├── 0ecc4abd2ebd0d9c8e3b643b0b31dc5e9e5ccc14.nq.gz
    ├── 0ee68c07204b1c00bd5ca0b8376e7861822a26a1.nq.gz
    ├── 0f0f6612c12320ecd3a6c2628034ecc17475aa8b.nq.gz
    ├── 0f373ebb42b58cf9ab8536e3f05ccdbcc400d058.nq.gz
    ├── 0f4100afad65c92c07519ca8569abe0b685e3881.nq.gz
    ├── 0f699ff6d86f4515505fb9e4518f2b38ccae66c7.nq.gz
    ├── 0f848aa7797c4dc0913e8a8562c1d2be0db23fd1.nq.gz
    ├── 0fb7a9a5b626dcbaca2da637c3233f2cc3e2ed4a.nq.gz
    ├── 0fbc150c9737d0185ac0e0cf777a392685a5409f.nq.gz
    ├── 0fc0ddb3a4d31d3ab3d8586637d697e8c15f6361.nq.gz
    ├── 0fe8f7f8016c26573aa8aeb76cea66d336e45739.nq.gz
    ├── 0fea45bcd5a7516b97f8d78e0aee35464b8d339a.nq.gz
    ├── 0ffa2dc96cf26ef125483ec094ee85d92d44abf4.nq.gz
    ├── 100917731a6efbfe0e6dcd1582557731dcb7d42c.nq.gz
    ├── 101264e4642ae12ffb5ec969fbbb5d2d26e65348.nq.gz
    ├── 1012cf877eb4139a56f4784a0ce9eb1914b2d7f1.nq.gz
    ├── 1019b093f05af7671ef904593518b6f4601f3dd7.nq.gz
    ├── 101bd4c906f7836e0b6bbf4e3a2523eb5ee939c1.nq.gz
    ├── 1039258ded917b943ad561ad5be6e0b72d08c882.nq.gz
    ├── 103d22b425a0dc1733af9130dda020e7f659da76.nq.gz
    ├── 1046db05995f8060bcabda0c58967959f2a863a3.nq.gz
    └── 104a1d9b9cadd98afab7c8343613de8846ad4b94.nq.gz

10 directories, 200 files
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

[mhammond/pywin32](https://github.com/mhammond/pywin32)

---
*Parsed on 2026-09-19 by [repolex](https://repolex.ai)*
