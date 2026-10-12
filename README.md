# Repolex Knowledge Graph of jupyterlab/jupyter-chat

RDF knowledge graph data for [jupyterlab/jupyter-chat](https://github.com/jupyterlab/jupyter-chat), parsed by [repolex](https://repolex.ai).

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
rlex download jupyterlab/jupyter-chat
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 977488a70758d684378041c7a5acc53a5bc3fa2a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 977488a70758d684378041c7a5acc53a5bc3fa2a
│           └── chunk-001.nq.gz
└── blob
    ├── 01c88c420b2c727504b2416e594b6b51eda2d5b7.nq.gz
    ├── 03720e00eb13f41ea213b57fa1cbb27a3813baef.nq.gz
    ├── 04709a0ecdff88cea862ce773ae0d1e2986ffff7.nq.gz
    ├── 0581739e5d0acabcef70a3e629df649328186076.nq.gz
    ├── 07332d95e0994f4b4a8ddf3111fe8055bfdde847.nq.gz
    ├── 0b5d2fc1bf717f4edb6c387f63fe88088e3fa2ad.nq.gz
    ├── 0c78f3c45bd2cfd75bdf4e6297c873fdb1f38e17.nq.gz
    ├── 0c8bb1aaf18f7aa9a3723b3fdf43db7bb65827e3.nq.gz
    ├── 0d1b28141d614482cef6df1da7c772663aa7ebbb.nq.gz
    ├── 0dd9748c17f201386088352350a38478d9a12b69.nq.gz
    ├── 0fdbd424fd9274306b6c1c44b6c540553efe8fac.nq.gz
    ├── 10aed9e914fc86e360759347233c79476d50446f.nq.gz
    ├── 121ecde2c5feb4460ab3a9a619a14e38722a89da.nq.gz
    ├── 121faaf64c54a642df5a31c36a87f37482c50d24.nq.gz
    ├── 1225b72a57d30c1090d3a226db92e7e6664db01e.nq.gz
    ├── 12cb9422f5c2a5dde8ace0f4f3d415e72f5a7bfc.nq.gz
    ├── 14718cf5cb3e96c0b28e093fba92040de3afb785.nq.gz
    ├── 1478fe3963c4d1457047864897a68c8c55b43f9e.nq.gz
    ├── 16673c26195f5b3eeb48165715ad7a1fcd9786e7.nq.gz
    ├── 16b3f9dfabd4661cce438d107fab4dc3907f188a.nq.gz
    ├── 182e47699b0be62a1d930722004f9fdd02522c8e.nq.gz
    ├── 186d8639820dd574fd85636e0daa7a128098179d.nq.gz
    ├── 18714cbd7e8968bdd581ef78b2445a003dd71f38.nq.gz
    ├── 1977e3a42fc076d69851a7fa2be556e9a8ead1ef.nq.gz
    ├── 1a59bfd48b7536d46a9028f98afee82a15e4e071.nq.gz
    ├── 1b1f99091636c5d0144aa187b5dd2b17f3a4b033.nq.gz
    ├── 1b8320054725d772b98f9383f14970f74c211200.nq.gz
    ├── 1c507bf237be46b3adce626b844220caa47089ac.nq.gz
    ├── 1d7cdd474ff2b124f56dd362568186d068a16e5f.nq.gz
    ├── 1de37fd0d50a92e2ba40704c6628d095d973d0e8.nq.gz
    ├── 1e5195d17301a2c9c0da834a9463a8627ea7b302.nq.gz
    ├── 2210f7d5cbac498cb0a8ed181361a7c4470dee79.nq.gz
    ├── 22a9bf3da5ba9c757a2fed3457b99d8f93ef6ae8.nq.gz
    ├── 25da48c2305fd5d9e8a7a2a62c4c48fe6bd7bec0.nq.gz
    ├── 27ea16760700033a4f9b33c3acfc26a3bf87f379.nq.gz
    ├── 28c7ef0a98ee7f6b57205a957f42b723088de5f9.nq.gz
    ├── 28e0d0d6d8ab64b907ae8a54582d2b9a0e2ce903.nq.gz
    ├── 2b15ee97c3a71bb0ec35d3f28f1a6b16b05dc1ff.nq.gz
    ├── 2be27a1f304f2922052c4673751eac8774a504a3.nq.gz
    ├── 2d352af421a2a63c8264e83877f79497337429a6.nq.gz
    ├── 2eb124611344beb5cd79e27d10a42946987db104.nq.gz
    ├── 2ee5304e0d12623a4d0c161bc235dc2e391b7f56.nq.gz
    ├── 2f3fb7d0eb9f3a60144b1d39b97c0e9414c815f7.nq.gz
    ├── 2f8a839f5d098e48d098110265d59b724b268d79.nq.gz
    ├── 301506db885c0d0497742c6204b0f1a10e756d2c.nq.gz
    ├── 304066ea4e2b734c3b9e88899ec448b27999d516.nq.gz
    ├── 3046b9c1dd999fb82181f16e6a079f419add9507.nq.gz
    ├── 3186f3f0795ab612d5508593672dc9ad94bccca0.nq.gz
    ├── 32c1ca421fafc468de1b4f86ea8bc0b095356887.nq.gz
    ├── 333b33e88f4613f61eee6780eb3657aead3e5491.nq.gz
    ├── 34271c58f715758ab771a35c4ced01bd2ed86337.nq.gz
    ├── 3500a15b69bb1f28806baf09dfd11d0aeeaf733a.nq.gz
    ├── 3624d0ce181af31ee1098cc9a2a9619cd865633d.nq.gz
    ├── 36732b5a84c7640e5ff705cd36a02f68ab3f9fe4.nq.gz
    ├── 36caad3daa8c39d5e05568df221ee4489ddf3bc1.nq.gz
    ├── 38a1b7084ed70cde09f1e16f610c84921a991fc8.nq.gz
    ├── 3948fbe95bbdc1dfa9d5dc28718d5eee65af5909.nq.gz
    ├── 39b15c28adb4f92eccd5c6b6cafc7dff67ccf1dd.nq.gz
    ├── 39f72958d6f20a7b8d268be0feb91eeaee19cbac.nq.gz
    ├── 3a326545153ef7dee2fe1f0141d850ef24704548.nq.gz
    ├── 3b3dea81f5d5b473240984d42b8272a0542d1245.nq.gz
    ├── 3b76c146bddbf79d11894d7eac896107fb08eefe.nq.gz
    ├── 3b86311d204c68aa1a3a526837fbe99e631637d7.nq.gz
    ├── 3bb159b91dc51f66ce2d4ec126e98b0873c3d88a.nq.gz
    ├── 3d5628946a00bbdd4f2403c4c98c4e8b3aa5b67e.nq.gz
    ├── 3da5fbb16459e0d0913e153a35b57b05ff128c09.nq.gz
    ├── 3dfdca9b7149ece8c524a570edaa24bc0b4788f9.nq.gz
    ├── 44fdf31dd8bff93e6a42455d56bfdf80f1b26383.nq.gz
    ├── 4599a2b7983b754ecef6c46b013534548a6777a9.nq.gz
    ├── 471dd26f9ced3081455b6ee23ae0231f5b3568c9.nq.gz
    ├── 47afc211b003b1751ccd2ca508da1a796f4211ac.nq.gz
    ├── 481ba29a5169bf8574d931b129b691b9371dd4d7.nq.gz
    ├── 49b102cf6f521dd91fc67e84f77ccbb3258a819f.nq.gz
    ├── 49f5d7750b6fb8e1ab075d4ea36152927f5a40e8.nq.gz
    ├── 4a5d274af8f7d63d3bea775024ddb72e1e7b6c1b.nq.gz
    ├── 4a8f6a640e222321fb78f2f9396fbe4dd3a6fce7.nq.gz
    ├── 4ed77b1cd5957dd7e204e04e0ba697fa9ae56780.nq.gz
    ├── 4eed6d620f7a6e9618366b6dccdc4d4913d05cc4.nq.gz
    ├── 4fef0b5c93b26aa2f59ff83308193a556c96d0e9.nq.gz
    ├── 53d0fa8a9e9de1eb9dfaeaa6de86ac17e8b5b075.nq.gz
    ├── 53e35b3205ecc6c2acdda21926312e458b9753e8.nq.gz
    ├── 557abe321e0a72f386d04d4b46c062d9770ede13.nq.gz
    ├── 56df81c2e6e222039e872a425acc67785362e3a7.nq.gz
    ├── 58254a77c4268fc72f22833a12f41a3318d260c2.nq.gz
    ├── 5945d0676c2a2097f9d33b76c1f37f87422199bc.nq.gz
    ├── 59876229ec9455460f9101255eec2c9fed7e9646.nq.gz
    ├── 5b7f50f4462daf528f5cd6cdd3b1b70198507463.nq.gz
    ├── 5d05c3ca1f115e568d979906316974f440ed9cc4.nq.gz
    ├── 5dd1c959d7fdd1a0df16e6bedbd00b88f01bcf4b.nq.gz
    ├── 5e688150b200e75675e93867080c87538dc3db67.nq.gz
    ├── 6013014ae41624d860af17964ea6a696d8e53dc2.nq.gz
    ├── 61007095493e8a205cdb01d69d4a28934c962b0a.nq.gz
    ├── 612ad06901dea7aae88131b87451d376d96cc6f1.nq.gz
    ├── 61dd6e9a948eec7ab8fe6ce2970d1a0ca54858c8.nq.gz
    ├── 621ced2d544158bc455bdf83de5cdcd9cb878849.nq.gz
    ├── 62f6c6d87c5121ba36cf2941331cb955c91c3c1b.nq.gz
    ├── 639279cc11ba06f16711b87a229d53e8b57cd255.nq.gz
    ├── 649752aca7ab82bd0fe8e8b905746dc03829d5f4.nq.gz
    ├── 65c21faff9ea710b9ec2d5a770fdfc412cef37e0.nq.gz
    ├── 65c9aba95a016e59cdeea36b44913fac7879547c.nq.gz
    ├── 664bb3486ccb9f8833388298ab270611d02b5cdf.nq.gz
    ├── 665b6c9f805ac400013bf851d2765700c79c9d22.nq.gz
    ├── 676eee439256df7f7c93409091e27f6879abdfde.nq.gz
    ├── 67740514cc9a9f9d77fe292588147d33b4a65543.nq.gz
    ├── 67f44396bab76a9f53b0e8a94099564d206d1566.nq.gz
    ├── 6914361d06bd7e270780e29bbaaf1115ab2314a9.nq.gz
    ├── 698d6eebab93772a2a6d578a35f84e91fe543877.nq.gz
    ├── 6abaf720e24daf6522b7e10b5ba94ebe3c0829a0.nq.gz
    ├── 6b122889bba91d89174b5ee0763fca81b1de9148.nq.gz
    ├── 6bdc832d8d1cb450e4976074ff29162bf1991d46.nq.gz
    ├── 6c33d1be79b5b9fe0bd5a45d6eef568fb09e8660.nq.gz
    ├── 6d60c4efa72f4f5eb64a928a6e29028861f8d5ec.nq.gz
    ├── 6dfeaeecf07d6c008536577736168e850e72ea2f.nq.gz
    ├── 6e96d72c856de4afec9360c1768560cb67ad65f2.nq.gz
    ├── 6ec6092f2abf8df967786f2361733d2698936442.nq.gz
    ├── 6fe7fa6667ac9ee2f74b146d55e918e4faaaa384.nq.gz
    ├── 70a6a12560f10e965b24b944df52d9ed42259f62.nq.gz
    ├── 711908dd4de062bc6bb0837c3e8bd3c7401f6141.nq.gz
    ├── 71290cd56685161c323c3963155a31b8f89733a7.nq.gz
    ├── 71826f923211449e5708d6747268b152d9818410.nq.gz
    ├── 71b038bdb4fb79062a92cc9df860f02571556f0d.nq.gz
    ├── 725feab5ce652dc39f3f2c77b9fd3c90bf049c65.nq.gz
    ├── 7362ed3f935be276356e3327c690170ebcef108f.nq.gz
    ├── 7414841ad8ac0ec4630b7e1c7c74c2e526ccedf8.nq.gz
    ├── 79e0fe2b929ef8425491b9e84f9e181210e4a432.nq.gz
    ├── 7c2029e4771490a595a806a549c93314719e8db4.nq.gz
    ├── 7f9cc1f3c86a1da608b7d460ce98ddc7eba25246.nq.gz
    ├── 7fed22193eff714db7e0e0528b19e660a8d12df8.nq.gz
    ├── 81bb0e8a0b582834dfdb02ae0d6ceb30999ffaac.nq.gz
    ├── 81fe9239f554d52ef5adfbc9f49da215412e5c22.nq.gz
    ├── 82e51420b28ddae08bda2862f611a5838857cbfb.nq.gz
    ├── 82f849b09bc764069bbdb33d571941ab6148026d.nq.gz
    ├── 82fde1bacd9142d9184325f70001efb5be6bd283.nq.gz
    ├── 839ff55c5678337a1728511409b7752a3a977573.nq.gz
    ├── 842cbff52c9e79f0ef608c3b2ce0437148c9c3f2.nq.gz
    ├── 85a5555740504c006e1c006d0502d146f7732297.nq.gz
    ├── 86b2f488ce3c8c187cb7c885839bfe7ced711d52.nq.gz
    ├── 86dabd6826ed6467ca9f35d5b7b8992dd7b24b46.nq.gz
    ├── 87e9cd29b58fdb1d83807bac61659dbaf58e1370.nq.gz
    ├── 890dbc0c5ea8d14cf9729c95346b5dcb76bf6092.nq.gz
    ├── 89ce56653ccb9a2132dfbafbcd9e4813a4168d89.nq.gz
    ├── 8aae8641389a29fbbe4f6f55d0a7d11fcd2db14e.nq.gz
    ├── 8ac8485ef0ef8ec4a402a8b4fda8d7ddbaa072c3.nq.gz
    ├── 8adee2dc3ec91100927ba9c6b3254db0fb0ec5a7.nq.gz
    ├── 8bcd7dc685ece8ffd9c1ba02729153186844c0f7.nq.gz
    ├── 8c31fd0865ccad76498b3732c7f9d35e93262404.nq.gz
    ├── 8ca0eb63b19e6971b54f8d42ff8b687ae713999e.nq.gz
    ├── 8d377fcca0634ddb094db913b5e4aef276da17c8.nq.gz
    ├── 8dbd8404589ab56ac9733321fd499451d24c77a1.nq.gz
    ├── 8f238222aa88bd1e72d7baee91198ed934891318.nq.gz
    ├── 90175bb79c05ff16dbf565ea4fb93a92bfe35eea.nq.gz
    ├── 908b4c21fe8f91509db5fd51c7d4fa5b7ee313ec.nq.gz
    ├── 9166d59f439d702f5ebf2662012cd3978abcbc64.nq.gz
    ├── 91ee007156c601c7c5acad8bd57c3d1f99dc79d6.nq.gz
    ├── 92670bc75203a88f00176790a7a0b9dc0f90b0cb.nq.gz
    ├── 92d6e92fb14cf53b4741c6b528576c9d3d85111a.nq.gz
    ├── 9387ae7492a796d82fda3cd7020ced046e548bb0.nq.gz
    ├── 94897e3acda682fb8ff20a1e6a8f92f2addf02ad.nq.gz
    ├── 974ac0aecccd2ce0ce82b8f55212619830c32988.nq.gz
    ├── 9984cb5711faa8056d8bf7269a0e55abb01bbc13.nq.gz
    ├── 99a29d42a8fe236378703971f4b54cf18b46b1e2.nq.gz
    ├── 9a18d29d1e35a80be3683159a124c48b279a2803.nq.gz
    ├── 9a45b86cc093bf1eda10c8b4d2472afa961164e5.nq.gz
    ├── 9aa56a91f1a9fb8e0e0afcba75857618350b86ae.nq.gz
    ├── 9ab595ecf1f4d705010ecd72808ae2c73c28d512.nq.gz
    ├── 9b8a26738bfe93aa2ad16a8f83ec1657ee08cc58.nq.gz
    ├── 9ead39c55e87351672ba60a9b99671b752b9a53b.nq.gz
    ├── 9f1827d9efb2310eb58095ad4ece2a11d2921663.nq.gz
    ├── 9f5aa2b656d1da26d087b6602c3662795c8f8775.nq.gz
    ├── 9f665aa728ecd9bf0509f9250caa4af64554b437.nq.gz
    ├── a075efbc576580a5712a7fecdf7f78698aa6197b.nq.gz
    ├── a139763cb2260bc9adea5d2aee90d0da5a710b6e.nq.gz
    ├── a20d45c0af21220d62df8c9f5e1d7de8664ad6ba.nq.gz
    ├── a2218464a1e1558fee440197d69bc679cecbfc53.nq.gz
    ├── a64a9a294e1c8a6a3f289d11af1fb57dfc42dd92.nq.gz
    ├── a64e6e840c0cd4dd947b0867bd17c2504de3aed2.nq.gz
    ├── a6eeac10af1bb8ade7464edb15b7731dc0b887e0.nq.gz
    ├── a877441e89f21b0628db675e4b90d69584c406b9.nq.gz
    ├── a9875a7dcb223a3bd54c058770ecca79bdfcbbdd.nq.gz
    ├── aa16067d0bdbf1e0d3ba6d3da9fbb86e62457883.nq.gz
    ├── aa38c0608657c8ad18acccf5d708c3e8fe166e8e.nq.gz
    ├── ab704c58bd0ead2005e190e78d6cd0251701ff5e.nq.gz
    ├── ac07ff8cd1390ce3379a1c2ea8137f0cc0e086e4.nq.gz
    ├── ad34bf0da21a478aaac33e4b59ae3099895c6f20.nq.gz
    ├── aedc532582837234ef4fc9e1e2274d25fad551a6.nq.gz
    ├── aee44003692c6a4722fbea8e484bfe196c98b379.nq.gz
    ├── aef0a3d6da6134617d0c824ea0e586a57e0f3a87.nq.gz
    ├── b08e26ad2a71e0adbbf243d4318897a026611293.nq.gz
    ├── b1233d9275f22cca7855b02b2061180e65c101cd.nq.gz
    ├── b1f139bb8409ab54daa6dbc38067abc841674380.nq.gz
    ├── b48ba3cf08316a9de112dc615c22fb739a29c2c9.nq.gz
    ├── b4fd11dcf9e071576579039fb644efbe8144c9bf.nq.gz
    ├── ba35ffcfb7068354c562c6c14203528b36aac96c.nq.gz
    ├── ba5f0819e0140c78dae8e5f549e22c15d65bf612.nq.gz
    ├── bb9557e8af2a62454c2437b92dd98357fccd646c.nq.gz
    ├── bbf8bb746f03b14ce253ba5bd6bd57c5301682ef.nq.gz
    ├── be6fd05f245a5cf6e3be88cf31e9609f0c258399.nq.gz
    └── beeabfecb7801e1b1e1091022c44bebeabd02684.nq.gz

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

[jupyterlab/jupyter-chat](https://github.com/jupyterlab/jupyter-chat)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
