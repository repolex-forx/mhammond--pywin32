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
│   │   └── 58f58184e4374cca9d177a5ca31c95705367df68
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   └── 58f58184e4374cca9d177a5ca31c95705367df68.nq.gz
│   └── repolex
│       └── 58f58184e4374cca9d177a5ca31c95705367df68
│           └── chunk-001.nq.gz
└── blob
    ├── 002fb0425b1355b2727a2fe965b38eabaa0a772d.nq.gz
    ├── 007d3aa82458344e5fd3f33600371c3a98a410e4.nq.gz
    ├── 009670335af8981063dc6c4836767a2502553d5d.nq.gz
    ├── 00fc77a8316d8dcc5b1eda5aaa74e228af0bd0a1.nq.gz
    ├── 0110526c63b2a31a98cb78c0083b12e815617e63.nq.gz
    ├── 012055fb84d4e273c4bbf4314ceecfa55f6b85b8.nq.gz
    ├── 0126cea50c194883b59d0431fc6b2b920f6e1598.nq.gz
    ├── 0147de13ac8e6ab08b944bb0433bf1ab35291cf7.nq.gz
    ├── 0156c0c1a9900a10a6c24743228fc8ceaacdf0e5.nq.gz
    ├── 01b025c4aed89a7d19d7481a4239360e427c72d6.nq.gz
    ├── 01d406d0d076701d562f0b5b1c86b72f9d0161e8.nq.gz
    ├── 01f48f0d957c5cd99da6290a45b344829edd29b2.nq.gz
    ├── 025d76ba821ed970732e9ce60b1584315428fcc3.nq.gz
    ├── 0282f8232b93a9257e27b84c33a52b8be8c631b6.nq.gz
    ├── 0299ea0a50fc91b403132b6b5f05c60e06a82e42.nq.gz
    ├── 02e2e2bd0be382195f519310a1b0ee495fdc7ee2.nq.gz
    ├── 02e358afd78a5483a21b3147a0261549e2f97cc6.nq.gz
    ├── 02e4cad0a92d5d2ca4c12c20fae2f1e9996efd10.nq.gz
    ├── 02edbd55ff1c68f7c0c01abf94cbd7adca3d817a.nq.gz
    ├── 0318c988dc6367c6539bf2b733ce5446361ac82f.nq.gz
    ├── 0344debd78eb506f6b79e7362376d50fd23bd862.nq.gz
    ├── 03dea5e73d36b754a9d25414a7684b55c6fcd006.nq.gz
    ├── 0403ca23821ea242767e7b7a9ffa730cbbfb35f8.nq.gz
    ├── 04206c8ad7bcb9b0d06777d3cbaeccfb0003f2ea.nq.gz
    ├── 043c5adfb9592531c594f1383b12574231e4a096.nq.gz
    ├── 047120e92102af6413998905f1d416aefa106289.nq.gz
    ├── 04ad288445b2f6bb0786fa00858e3e93fd88507e.nq.gz
    ├── 04e6bf14ce96243c23ad46154a2842fe19348093.nq.gz
    ├── 05028fcfc58b318f88961303d6bdc3e4c9176a5c.nq.gz
    ├── 05161d4433d86802e0c1253ba10ba4bcd4f3b58f.nq.gz
    ├── 0521e5e191645a37107915126a8e9b1bc67bd44d.nq.gz
    ├── 0554d9457a062a8e8188142468354ba8bbe95529.nq.gz
    ├── 05a613f0ac2a09bca0689e6888330cee7d70d8c4.nq.gz
    ├── 05cf63bcf9fa2ae5f079e46d6941db17c8eb218d.nq.gz
    ├── 05d915bd14ee78d037fa5d3ea37e2f353020d769.nq.gz
    ├── 05ee8fb4af2e453f593de89c473f688fc18d9fc4.nq.gz
    ├── 0662b93363fb96010cdb3f958954fec2610a0b19.nq.gz
    ├── 0690629c6186278eec0eb5904a86984541820831.nq.gz
    ├── 06c63fa85c502a1c7e65e3e600144a0c1d46f4fe.nq.gz
    ├── 06e7c1791fbe22d5e0e5cb8ccf20515f33952e93.nq.gz
    ├── 071224dc22d54e1dc0b99ddc22182e7ac3306aca.nq.gz
    ├── 071ceb1dc62a959abb5846cd718a45beb8b20898.nq.gz
    ├── 07756fdbd484c30c6dd888a3b7aa289e7d36f2a7.nq.gz
    ├── 07affcaf0c67c6f7f17617ba1fa34740f1a7a4d7.nq.gz
    ├── 07bcacbbff46b7ba54bd1b19f5ad47a24aa0550e.nq.gz
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
    ├── 0980da37e1cd8b9af969dd4a2ef4c2fcc27e7bd7.nq.gz
    ├── 09b5edd1036e974a8e48244f94b614c172aeaac5.nq.gz
    ├── 09d6b17761ea619ca8be8c43179950833b3271ab.nq.gz
    ├── 0a1257a6db8f13def323152602727bb01d334c8f.nq.gz
    ├── 0a15945524c3693bd4354f937e40dfea075ba9b1.nq.gz
    ├── 0a575fca050f4a154a06b57c07809020a354e7e7.nq.gz
    ├── 0a7765329e6f84387b09a0c292a1c2f38c5e68ad.nq.gz
    ├── 0a824d07dede5a6c46e9e8db835c7d3cc6910e43.nq.gz
    ├── 0a92bbbac68da0b795e9f05ff68ce890cb26add7.nq.gz
    ├── 0a9e38d58c72b00ea8848e58b55b1b990514711e.nq.gz
    ├── 0ab79a986e922344ba400749e388c004963dab44.nq.gz
    ├── 0ad8748af3f5ca9119ddfd327caa9982094dafee.nq.gz
    ├── 0aecdfd4263da1d9731f8cb4941d9cd25e8476c6.nq.gz
    ├── 0b143ef3e5b75b1974d3043578c6e22a4e604cde.nq.gz
    ├── 0b454ae131e9f37ae672eb0ab8e84e973f635009.nq.gz
    ├── 0b8b2c6199731c1f9bd19ec9f777fa32ec601c91.nq.gz
    ├── 0ba96851614334d5d094fdbe8378838271b2bb9d.nq.gz
    ├── 0bd57a81d3a6ff5506b9e8ee1fa24ea305606ada.nq.gz
    ├── 0be53b114f559e79b98b7b13cc3890c3529d18c0.nq.gz
    ├── 0c7f46d3455a4e137f20c9ea771235d0b2909062.nq.gz
    ├── 0cdc6e3617b0ff58947a260c757a7beef35998f7.nq.gz
    ├── 0ce417c0ef51b80f66032f0bd93e0e5d4812fa98.nq.gz
    ├── 0cf42ab4523c8d409c024400bbddbb12f9d04fe8.nq.gz
    ├── 0d0b8ac9c986d0e3eb5cd04b79a9902d91b896bf.nq.gz
    ├── 0d173963a20e8cda9e5f15a6bd61da25c2b9aa66.nq.gz
    ├── 0d202d68d3e200f50cd6d6038356849e9fa7011a.nq.gz
    ├── 0d24cca1cccf1319e1c5bc5ec3fcf43777c5c9eb.nq.gz
    ├── 0d37cb27bbfa14fbe3f97aebcbee316542d47f2f.nq.gz
    ├── 0d5bbc628ebfea3cd5b1102ff62dab49bb39ef96.nq.gz
    ├── 0d65a2928962860cf8b675b5192a43b165f31350.nq.gz
    ├── 0d7a75c7276d44c2604e67e4246e8beeb44aa09d.nq.gz
    ├── 0d7d646e895b4bb839a73142890893126b70387a.nq.gz
    ├── 0d7eb2cbbf4fd4b1309ba0e54354ae7e381364de.nq.gz
    ├── 0dae5a5a2cde902f6ac0c5b95d693332a9ec0edb.nq.gz
    ├── 0dca29ac8a6bbab2b184b94d544929eda14c05cb.nq.gz
    ├── 0dfda4f1eb3a615b9de1508afc43e036643275e6.nq.gz
    ├── 0dfff283aeb37c3d4aebc370f7f216f0adc3c09c.nq.gz
    ├── 0e2ddda9a1f3ff8b895619f42acf9b4d1272a31d.nq.gz
    ├── 0e4576064e9eedac13e7cced2b2b929f11553d19.nq.gz
    ├── 0e4906ca7c83cd026cb228cb302476a84354db76.nq.gz
    ├── 0e5f07d4d4f3c0d8dd63c92d71baf0e8506022b3.nq.gz
    ├── 0e9689121d9fa41390fd07a87f13bfe1739aa5b3.nq.gz
    ├── 0ee68c07204b1c00bd5ca0b8376e7861822a26a1.nq.gz
    ├── 0fb7a9a5b626dcbaca2da637c3233f2cc3e2ed4a.nq.gz
    ├── 0fbc150c9737d0185ac0e0cf777a392685a5409f.nq.gz
    ├── 0fe8f7f8016c26573aa8aeb76cea66d336e45739.nq.gz
    ├── 0fea45bcd5a7516b97f8d78e0aee35464b8d339a.nq.gz
    ├── 0ffa2dc96cf26ef125483ec094ee85d92d44abf4.nq.gz
    ├── 101264e4642ae12ffb5ec969fbbb5d2d26e65348.nq.gz
    ├── 1012cf877eb4139a56f4784a0ce9eb1914b2d7f1.nq.gz
    ├── 103d22b425a0dc1733af9130dda020e7f659da76.nq.gz
    ├── 1046db05995f8060bcabda0c58967959f2a863a3.nq.gz
    ├── 104a1d9b9cadd98afab7c8343613de8846ad4b94.nq.gz
    ├── 1072e13a3af2fdd62274b7dc4a450df660128e4b.nq.gz
    ├── 10abe5f5571f45adb5c880c5a0720cb51d8b78b3.nq.gz
    ├── 10e0bfb64f0fc10cd090a1e006e5060b0f0ce4fd.nq.gz
    ├── 10ee74a4b3bc69a91c3177e3db441b1f93fe6a15.nq.gz
    ├── 10ee911b3b92a0721a7255997797abbf8999e54b.nq.gz
    ├── 10f1aaeffa375f6f762b268f816ae97986651bef.nq.gz
    ├── 11044052042caad4b5c4ede72da34fdf620834a5.nq.gz
    ├── 110d4b557a5b69e53e87be5759384a92cd4f7772.nq.gz
    ├── 1110bb527157f8e739569b9a875a83ca04a49b42.nq.gz
    ├── 111f7de680185e4478a618246d07e26db65c2034.nq.gz
    ├── 1122609222c82e55b57c0a8a31fa1e8f3be6ab74.nq.gz
    ├── 1122e7dc7ce2ca9ff43341146b5bea82b8a97f92.nq.gz
    ├── 1170d6feab92ca7ef86562eceaaff2823e962f63.nq.gz
    ├── 11a975a125659dde65c6cf714cf4da0dc52482f8.nq.gz
    ├── 11ad6deb975aa4b73c527736a24e41c76ce29c6c.nq.gz
    ├── 11d9f9368e281891f920f6d106c82164d0bb0c53.nq.gz
    ├── 11f7b260e4fac46a0ec774ebb645c6b172d4d723.nq.gz
    ├── 12072679f88590f93a05c333e468674b51f020e9.nq.gz
    ├── 12753e26a87d03c9001317d34720f2545930744a.nq.gz
    ├── 128821c0c06d47e9f786cf4cf7a86d85389e763e.nq.gz
    ├── 12ed5dee2d1df987c6c3bd5d134e6075ff160c39.nq.gz
    ├── 1325124063fc6d514bdb5ef77be247a7a52940b9.nq.gz
    ├── 13622dae306257785f2b910294d4891d3b4784ec.nq.gz
    ├── 13696cb9dd07b06b1b776defdb3c6a9c1927310b.nq.gz
    ├── 13757f2a9b57d27ea3d5c8781e9158faef6f0ab3.nq.gz
    ├── 1388e51a48701e6a931badc46ba78f91754ba0b3.nq.gz
    ├── 1392197232458777a3f89239baffb8c03f2f15f1.nq.gz
    ├── 139597f9cb07c5d48bed18984ec4747f4b4f3438.nq.gz
    ├── 139e2b0eab9ed3e9c5050a5aa8babd8117a21325.nq.gz
    ├── 13fa577fb7cabc17250ae7e228f5cfbe1f872a81.nq.gz
    ├── 140e4a065cc485ffe75baa4ea7eac114b50afffd.nq.gz
    ├── 1421f3839afc25ec7a3bbf43c2c191cccd5c31ac.nq.gz
    ├── 143e1ba9cb3cbc6d2fc1905575868f016ec33ced.nq.gz
    ├── 149c360f824cda16aaf1f6d79d23bd2338459e14.nq.gz
    ├── 14d70f9995144b41170021635fa585247de1ebd9.nq.gz
    ├── 1519d4a027b4eec498d762f1034cfc292589bada.nq.gz
    ├── 152a9c01ed1f29033dbaabe93898a78091ea2ed7.nq.gz
    ├── 158258bf8c31c222e7eda56ad906b6df8f9d97c1.nq.gz
    ├── 1594f537a8c5a3d238a831fc227692e329351fe3.nq.gz
    ├── 15962488b07a16a0de57baf15624e0a813b8b73d.nq.gz
    ├── 15efea8cc5ca3bf59fbf54afc62b008f4e27e3de.nq.gz
    ├── 1614755a72c8bcf73686a2c0bfd29486700b5a02.nq.gz
    ├── 16553734640fc7db6d35cc84b6b85a13b2ac0007.nq.gz
    ├── 166d004b8e01f2ed142aa62b18d5c0d591b2740f.nq.gz
    ├── 167a3f4b6c0776afbf4470683923b4ba59061f6e.nq.gz
    ├── 16cd00f291d487458a832783243d623da85bce08.nq.gz
    ├── 16fd69d8b70272a58df9625ce0c06f9c05bcdaa3.nq.gz
    ├── 175e357130de7340a40fc9c4fe88cea85ee8e7a7.nq.gz
    ├── 175f9b6f20fb985aca9962de2c05ec2cc475d61b.nq.gz
    ├── 17670ec8bb610021ff7159d746848a5d02bd92c7.nq.gz
    ├── 178500f29d041f9a310c534171bb3d18e1ecfef0.nq.gz
    ├── 17fdc00ccb2eda03946dbbcc2e091bd684262abd.nq.gz
    ├── 18643dd75754377d57e7f4443ad8108397deb999.nq.gz
    ├── 18bc92a97c53a6d3a17f86537129ab9ac71acd51.nq.gz
    ├── 18d4678455fb54c292b9ed75cd0992e955a3d8e8.nq.gz
    ├── 18e94d4d82cdc18e65438259ec64a8fc9421b6c2.nq.gz
    ├── 18ed8dc15761018115335be6f3e6d4e314e286d9.nq.gz
    ├── 1917fd797c8d729090d2146714f01bc4dfb82e36.nq.gz
    ├── 191920393616e12f6b5d96075037ea7b4650f9ec.nq.gz
    ├── 1922d509c3f1c45d993821543a277948d10b535f.nq.gz
    ├── 192538b8c9e385edbc97b495bf1da73b5d2f87ab.nq.gz
    ├── 193c104fdf1bc47c777bc6e6596482b0308763c2.nq.gz
    ├── 194b84c516b096d0b0f9221fbdf54be50ec25a83.nq.gz
    ├── 196039f1365dbbd3e74635e59131929e369d0138.nq.gz
    ├── 19b0bf07a4459ca45a157ac4cbe783cd4200974c.nq.gz
    ├── 19bf585e0d7de500e68d40804e247b1535df57fc.nq.gz
    ├── 19c1e63553cfe2d4f538fc9cafefaa6baa22d681.nq.gz
    ├── 19ce343852b4aaa2ccc7de874255b9f4f246e266.nq.gz
    ├── 19f2eb7a1a2bc2a12f432b5cc2b2a26ba988136f.nq.gz
    ├── 1a39e92ea88a91d36ae353e5d5cb494245ac4d1a.nq.gz
    ├── 1a42d2e1b9f03b38d4ba982a474f57db8c6b41a5.nq.gz
    ├── 1a9cf94374bd5e55e8ea98deb6249fe88cea959c.nq.gz
    ├── 1af06af9a820d7419026dd8d1191c6b3b60c9dfa.nq.gz
    ├── 1b7e2af0c136e7229fc88319d18bb1655b4107be.nq.gz
    ├── 1b999f1cece8c3394400a9fd78e698ba4f866025.nq.gz
    ├── 1bbbb56cd7a8c7863ab2f89af16085f129d3fc3e.nq.gz
    ├── 1c496f0393c97d239e754e147e5ff77f783ee936.nq.gz
    ├── 1c5d7b42598d93ce3caf4035b3fdbb804e2f1b2d.nq.gz
    ├── 1c7c4e701f13c11b8f092d4f7ac1c9ffa47d7b2e.nq.gz
    ├── 1c92de72e7fc7e02c8f9e9ec8e30959c903141d0.nq.gz
    ├── 1c9dbdf45d76db2d8120ca95e6c508c156865cc3.nq.gz
    ├── 1caecaee73ffe228f0521348320bee167a26c098.nq.gz
    ├── 1cafb9b10a8948e1ae4bffec0882cb70da0cf3f7.nq.gz
    └── 1cf330f33a6fa9df67eed00060c00f066fa5e091.nq.gz

8 directories, 200 files
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
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
