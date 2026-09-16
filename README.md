# Repolex Knowledge Graph of sindresorhus/type-fest

RDF knowledge graph data for [sindresorhus/type-fest](https://github.com/sindresorhus/type-fest), parsed by [repolex](https://repolex.ai).

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
lexq download sindresorhus/type-fest
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0329b2b2dc568df61ed6bfbbfa0f513b060a02bb
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 0329b2b2dc568df61ed6bfbbfa0f513b060a02bb.nq.gz
│   └── repolex
│       └── 0329b2b2dc568df61ed6bfbbfa0f513b060a02bb
│           └── chunk-001.nq.gz
└── blob
    ├── 003b35e0de3091d7f6a6bcda14164c7ac3c51f10.nq.gz
    ├── 01e48eecad1229b480a8bb2b1657dd76fb1e0fac.nq.gz
    ├── 029243db09d466494d2fa3c4ba5b9d7d7203f974.nq.gz
    ├── 02a029c04621348711dff4bf85f49754e7d71c07.nq.gz
    ├── 02b04e995120f942fa4a526128d3dc30d9f4388e.nq.gz
    ├── 030752fbfe504f3202b69133092310b830a07e07.nq.gz
    ├── 0412c27d39f863160656eb54566a03a706aa50d4.nq.gz
    ├── 044a5a8a779b4bfa644a86750eaec8831f394f11.nq.gz
    ├── 05e9a60b3399e075b00d03d00789ede5e2d097ee.nq.gz
    ├── 0683c792a9ac8a1162759ed18cb08f4b270fd3cc.nq.gz
    ├── 068c8a738176784cfae9041fa028d1c8e3808150.nq.gz
    ├── 06cbe6225d9bbbded88f30141d96b1b2b0a5c7b6.nq.gz
    ├── 07a7d3a8faa1f4800e0b22beb13e49d8a97594a3.nq.gz
    ├── 08a126d77605ec91b6965a95d3e9089be6b915c8.nq.gz
    ├── 08d686218a54499df8f5974b6143086cd8e778cd.nq.gz
    ├── 0a50adfb6a7e89acb0994075932e93a4d3b96f37.nq.gz
    ├── 0a9372d778edd40f048009cca09a15bc2b7f4f1e.nq.gz
    ├── 0b3bf29c533051cbcc9651cba76caf1707870b0d.nq.gz
    ├── 0c6ae5c0b161fda73aea006437f91b3b906c20b1.nq.gz
    ├── 0c6ba25c7f0b4e7da288a6e59dd41ea5b9eef6de.nq.gz
    ├── 0e259d42c996742e9e3cba14c677129b2c1b6311.nq.gz
    ├── 0e8e6a4420aa1de631426dc5d54d2ae5259f616e.nq.gz
    ├── 0ed0cbc789281e74ecfe0039076bbf28a8be3970.nq.gz
    ├── 110cdf9704617c54d6888de61a65864ec65119c7.nq.gz
    ├── 1165d3e511a63dd79aa0b5e3846c241ca45ae119.nq.gz
    ├── 11f2582ad9b14643b32a47ea7c4f832c8fb5ddc2.nq.gz
    ├── 12267771593ff411dba51291778ea110ba5b1f9a.nq.gz
    ├── 1276b8d93d685c13ad0312d04c4f3be2dd79073d.nq.gz
    ├── 1279f0390f0a64583183618e547de6433c7c46d1.nq.gz
    ├── 1293e6e7aa722c4ee1fc2cc5561e2e3162c9cf45.nq.gz
    ├── 12b9d80c8fd82110851808e1731dde39cee1d0c3.nq.gz
    ├── 12bad4c18ebda91bf12f9c839f475408edcfbf24.nq.gz
    ├── 13016ea88e11f2fbe9bb7d7683fca04b5b46edea.nq.gz
    ├── 1312e69cf3cbe6feae01baa2deaee993d8a9f2a3.nq.gz
    ├── 13398e7c53d24a67539e29525059b22f14bd8d9d.nq.gz
    ├── 1388120dd8fce1e7719990ff6c0ef6e6f29548d3.nq.gz
    ├── 13e369be4b9f917d0b7c74b766b598c5cd77c69e.nq.gz
    ├── 13e8d617cb8a93ec92e85b949034cb86955d751f.nq.gz
    ├── 146bf62c44bcd4e9f2421a5c937612ef3aed03a6.nq.gz
    ├── 14bf2db3b6989678688f9602407fb2e12aee1ce1.nq.gz
    ├── 152c37e9574dfe2f792faa5c0ed42013eb530011.nq.gz
    ├── 15d651c63276556902b29441bcb3df2963c654b2.nq.gz
    ├── 15e9b1481d3ab88260595db1c778a2c5da4eadab.nq.gz
    ├── 1644802f65a8216deadbd044e0c77b701c071c7e.nq.gz
    ├── 16cefc2d2225219cc7a945f5e2ab2d128acd869b.nq.gz
    ├── 171feaf9d67598ed9956382ed1b453b6000b160b.nq.gz
    ├── 17ce94be35c09e8bb2ff2f915d530d9095bf6997.nq.gz
    ├── 1802973beb1ea8f332fb6635d3f13c456e29ab25.nq.gz
    ├── 182f7707446e0cc50ff547b6328ea9b664f25254.nq.gz
    ├── 1870c77884c4fcdfc2501477663c61068c3553c3.nq.gz
    ├── 189a0a8669d4dbb623ef06132b3a6dc5f37a096a.nq.gz
    ├── 18d5a52b52c7fb1c1950078fda97e29fae4750e2.nq.gz
    ├── 18ec42a30645884be739e5249c9628512a156fcf.nq.gz
    ├── 192b1bf14d53b41927075bac067e84710c900a5a.nq.gz
    ├── 1acc0eb037e2a70972852fabf78a2c36e287c2b2.nq.gz
    ├── 1b30ffd117e2bd7f1166c124bce2d14274b29fcf.nq.gz
    ├── 1b90815c7543c636d6c4f283993264814e3f470e.nq.gz
    ├── 1c6314a31833395fd5ff016a6506bdd51860657c.nq.gz
    ├── 1ce5f0a598deabfc0c2bd789274d5767e69d4745.nq.gz
    ├── 1cf50f8b6c3712fd710c299425435a8f6b03937e.nq.gz
    ├── 1d96642035ce7bc331270155d5569d7e335f08d9.nq.gz
    ├── 1dcd09f5f74c7a43abb45f140a71c12511c809fa.nq.gz
    ├── 1df7fdaa05a1bad656e85e948a2381bba3f88d9a.nq.gz
    ├── 1dfa35edad9a514ff78228ccbc86cd897ce4dafc.nq.gz
    ├── 1ebc56b75f903549c005eba7283ca98202d8c9b5.nq.gz
    ├── 1f744820a9d1d5d30f18b3551d6a6b22f04af77d.nq.gz
    ├── 1ffa7aa3b39e7682a713da2cc26a6a7075d3a1ec.nq.gz
    ├── 20109d38cb670f8512b6f67e59d1068acbfbfa14.nq.gz
    ├── 2049455147f52cd7ea71fe5bda407696efc9812e.nq.gz
    ├── 20583bb7bfbb7ef7ba2cf59a8aaf09b4698fe4b0.nq.gz
    ├── 20a19919aa4fb85091a5d5cd1c9e9c3b2436adc3.nq.gz
    ├── 20a48555bbb9c77b95c3c2cd0c4f270b2065406a.nq.gz
    ├── 20a609f0365065647f733fb84fba65edaf026b57.nq.gz
    ├── 210c329235afc32fb82ac19978b81ff0583a11e9.nq.gz
    ├── 210fa9248bc081bca53a6952e769fd77bcc06dd8.nq.gz
    ├── 216e97ad3d1edab52e4467a4bb77661e9f82ef53.nq.gz
    ├── 21f0341a5e402060a64c6c5d3aa31fd6ce95b2bc.nq.gz
    ├── 2228b4f4a41155feed7c243c312fb3a297b87a99.nq.gz
    ├── 229cd1ba05adb636dcc1019e8609a52635ae7e00.nq.gz
    ├── 22b26fe9df9bc9e8a27de871377a56ba58d6003d.nq.gz
    ├── 2329ea6279cb5b7dfcfca3c56002c92351c52964.nq.gz
    ├── 23793d74b071684b8b4915704df1420c8d355b7d.nq.gz
    ├── 239ecff1372358a22aa99dcbb375fdad7abba817.nq.gz
    ├── 23a29e23343ce7db93a528c93f4a521807a15b4d.nq.gz
    ├── 23ef2b54922e9d2a776036df4729ef231a867b89.nq.gz
    ├── 2419ca1c7adea8a96a72b170edbaf88a3f3fb759.nq.gz
    ├── 24df88ce02d997158a818361fbdb2c9becfe91b3.nq.gz
    ├── 2503de0842d1f17048cfd844a3622d9833f5e12a.nq.gz
    ├── 28b998856d5ea41747fc55be273254ad36d7c49b.nq.gz
    ├── 2919d7bd374730ccd4b8605896f48db26ce5f698.nq.gz
    ├── 2993790f027333b2562c0c99fcd0b0cb705880cf.nq.gz
    ├── 29d429b4548d63e8a3739484caebc4e64f9223bd.nq.gz
    ├── 2a052de43a5e75a1e9046b1f1c29fd743e4389dd.nq.gz
    ├── 2a5dbbc66a3dfc8f304992df83756d2b6deb2623.nq.gz
    ├── 2b1211c390ad763047cd0ccc556159b5250aae7b.nq.gz
    ├── 2b3018319959965c601dafe5275f64abce6f3767.nq.gz
    ├── 2bafae5f883911ebb38700e43c9978cf545c0b43.nq.gz
    ├── 2c1f5608b7274ce150937f426e588e799d6bed66.nq.gz
    ├── 2c485c22223187179d6f282c2915910c60859d85.nq.gz
    ├── 2c661e3dfbd81a25aae3a02ebd4b2ad85621f749.nq.gz
    ├── 2cb5dd2d1d38cbebb0806bd39da5547abd4160cf.nq.gz
    ├── 2cb61d16d14b0942b9b30ebdd04d57b60b467b7d.nq.gz
    ├── 2ce91a716e0835dc283a4ae30fd7502899c51a58.nq.gz
    ├── 2d366688ce8d75688298f4f2cccccfaa23c97b52.nq.gz
    ├── 2dc67b6f6ff59a3652868f02c50313b9dbf7ac63.nq.gz
    ├── 2e6752a67216d12be69c5aa8bced6a2d95d221e3.nq.gz
    ├── 2eaffd7c2e84c439781c0ed4607e5c0e71d1f1e4.nq.gz
    ├── 2eb1d806eeb305ab24fa634914467927af2d555b.nq.gz
    ├── 30221f3947d958a74016e339c4e19583e4841a66.nq.gz
    ├── 306b4687e101795faba4b4b1b28c89019de00bdd.nq.gz
    ├── 30b94d1bc74b1ccbaf4234e3ff8235ff41a04ca9.nq.gz
    ├── 30cab3aed0ba7424064809fbd551c09e9f39ca21.nq.gz
    ├── 31224d875c4142ee084d94ca1f5b5a4597352a33.nq.gz
    ├── 315c4765256241d03591ecc975cc0fe4f3337a20.nq.gz
    ├── 31ce65a19a6c8815559ea40c473c5dfa6a15c262.nq.gz
    ├── 338c6a88413b30cdd80123d8293af1b5fe7690c1.nq.gz
    ├── 3467943dfa290b8ead4fc54a21f4764d48f36949.nq.gz
    ├── 34d4ad14633946074b7028f5b5a3a1a6a9dc95c2.nq.gz
    ├── 35091f3414ab4c438a775b0d812558f38a8fe5d6.nq.gz
    ├── 352475182644da92e029e4b4e88b6d652c525ec1.nq.gz
    ├── 368af17d87b6765e2d81c68a4569e2b0c82815a2.nq.gz
    ├── 377c456cbcb390a1c100b6fc16260333119b3c51.nq.gz
    ├── 379e1d6925825ca13527fe794adefc3a4b309050.nq.gz
    ├── 384243062569d435b0c9d3bef8e248fd0aeddbbe.nq.gz
    ├── 386e98e9ba153b381983af2ff93a6b445b6f1b51.nq.gz
    ├── 3a2b1a7d53f5679a3ddd484b293328665d6efb0b.nq.gz
    ├── 3a46d77c9807ce59eafeb55ec4f988db27f22a40.nq.gz
    ├── 3af5769b9c83cca1c9bfa505071b063116710897.nq.gz
    ├── 3b6db25c7b6ebfcc95ce14988664cc7136c7d11e.nq.gz
    ├── 3c57b3bc9157e11ae100e3fe08f6675af3e93f88.nq.gz
    ├── 3cbe44a79e18b4e2f9063c20e4117e2daa1f9e21.nq.gz
    ├── 3ce5c3529eac1eb3d52a4c5975585bca44445db8.nq.gz
    ├── 3ec2f228413e70c17cc2b2f534248ab8b5d79a85.nq.gz
    ├── 3ee3043263d773b7db623a7be3242963449d36bf.nq.gz
    ├── 3f7360dbcdfe2ec28ba2cee11bb6646520c6c256.nq.gz
    ├── 3fbcce13c26810d5e44d8a227478ee61b33cae19.nq.gz
    ├── 40ee66d52c7f37228ff7c9602d73d9f8c9b7d5bb.nq.gz
    ├── 417f8f3ba9456806664b1f91402e0d5ed7909cf8.nq.gz
    ├── 41ccb0d8f88d4d173ff89b1e7a35bf9a1f6c898c.nq.gz
    ├── 4267276b5db3974075afc9ad0884850407d96617.nq.gz
    ├── 4281ce92f087b05c3806caec65592b39359039a6.nq.gz
    ├── 428a268d8549b2affb7c726c9f8bca945e2749bf.nq.gz
    ├── 42cc591c4248602ddb1808233875ae05980d9a39.nq.gz
    ├── 432117899eb598f806bb2f7a7081e81dc9e73307.nq.gz
    ├── 4328cdabf0c2a4e671869aa35058f5b02fe8c19c.nq.gz
    ├── 43c97e719a5a824700932f72e6e7e6748ce45d01.nq.gz
    ├── 45ab74d0a8060a27254c454b6909cdaf2175c71f.nq.gz
    ├── 45bb48adf1f7ffd0400a7190b62b93daa49dde19.nq.gz
    ├── 45c6704c7d0d4cf54d5c4744a95dbc9d25fb64df.nq.gz
    ├── 45e1e5fdea3ed927afe2d124c529a81da24b0410.nq.gz
    ├── 461f8dc445acf3726765549c0af821838b3c0305.nq.gz
    ├── 466bbf95e2add9f12d96896e829787289012c54d.nq.gz
    ├── 46a16431448f4263a49e131ccf1133749dce5cda.nq.gz
    ├── 46d01b76b9fa7a9b1b2655f4e16c0191da34c807.nq.gz
    ├── 46f490b0abb2ab49bbd41faaa9e29114ad6baa24.nq.gz
    ├── 4740b6d0c89018e45258bce77280cb6d16b1d0c5.nq.gz
    ├── 4763b50873d88837bd6cd995abb864ce0451ffb7.nq.gz
    ├── 47bb838ef0c4b1dbb57780446b818c6541d5efbb.nq.gz
    ├── 47da483b6cfee8c4a04d768c4ba25caa296486ee.nq.gz
    ├── 49cad1c120a131c313f109747ee822f8e74e1b10.nq.gz
    ├── 4a900eb029049128bbbaa1aad71a7fe1236759d1.nq.gz
    ├── 4ba14678e7fca523d4caa46a06b7eabb2fe3a037.nq.gz
    ├── 4bf17640b28bd14ca05584f1f19ce455be5f5f08.nq.gz
    ├── 4c0814fa4602cec711baaea7456da3ef2765a1af.nq.gz
    ├── 4c61b68c032b8c45d5d8980e7459650a646adb0a.nq.gz
    ├── 4cd4b8ea6a0fbd81a053db8601db9e9ad8731259.nq.gz
    ├── 4d197554b2a72cd4e88f8c9b592d7255731abb83.nq.gz
    ├── 4df36e8a96d32ae83fc559437f274ec98a409e57.nq.gz
    ├── 4e05668bc3aeb8fe0113859ef62282da391f681f.nq.gz
    ├── 4e13986c61df797c99e603ab644ea2a9dae7aa4c.nq.gz
    ├── 4e98f792e31932f9422aa2f470ce6e16fcefda87.nq.gz
    ├── 519ac5f252d56e898d206be8491874a1f37f7944.nq.gz
    ├── 51fb64a3883367bc1f59b0be1ab72f8f2d9a2e6e.nq.gz
    ├── 5293ece7972c1d5e70293cadce07c24d92970bb5.nq.gz
    ├── 52d764074a4653414ef575da8343f4c0053ed106.nq.gz
    ├── 5358dc50b2883157fca0fa4a12d2bb18acb093ee.nq.gz
    ├── 53c5f570f07ece4401ead7ed77dd3f354f33d540.nq.gz
    ├── 549af5693fdc793109b38a923f6317bb6069d6f1.nq.gz
    ├── 554626bba788bd9c5bb568765a6a7ee84d70e70c.nq.gz
    ├── 5551f82a19489e10d3f4ac8bf2fda954126b20b7.nq.gz
    ├── 55b615037f014184101d06625d6a7fa28804cebd.nq.gz
    ├── 55da534d03303e8f9846f1871c36f288a6aa3362.nq.gz
    ├── 561843e163fa9d48ae4db85e66223848d8c8025c.nq.gz
    ├── 56667d2f610379dd71bec5263b8eef0dd718a1de.nq.gz
    ├── 56f1ae0895989f715204625bfca8e4545c35e041.nq.gz
    ├── 570143d11d1fe025bd20248c06d7f5ad5f97020f.nq.gz
    ├── 5740e180be96848fe5756326eb62131e0c02c4e5.nq.gz
    ├── 57abc481ffb19a28001f20bb8f7fa3653a0b48f4.nq.gz
    ├── 58e0ef2a42c6f47a415b365a545ab472f1125cd6.nq.gz
    ├── 5951f1037bf272dc41915d5446434d61c4ce072f.nq.gz
    ├── 5a2b1b8a88b6d61998f833ed89290d92f4d14cc8.nq.gz
    ├── 5ab98c4fac59a40f30bd4f95cb24bbadec6c13ba.nq.gz
    ├── 5ace1738d60f93583b26f1e14b9a2972ac523dac.nq.gz
    ├── 5ba07e4a45c2759567a65db24f48ecebfbbf6545.nq.gz
    ├── 5c78aedd89303ebc57e8fb4d83c806875430627a.nq.gz
    ├── 5cce564d6f6506813010b507c4e50c2c8f5533fe.nq.gz
    └── 5d14803f2167553db8b1527fe5d4f73d78b40c0c.nq.gz

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

[sindresorhus/type-fest](https://github.com/sindresorhus/type-fest)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
