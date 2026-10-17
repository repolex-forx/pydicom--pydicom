# Repolex Knowledge Graph of pydicom/pydicom

RDF knowledge graph data for [pydicom/pydicom](https://github.com/pydicom/pydicom), parsed by [repolex](https://repolex.ai).

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
rlex download pydicom/pydicom
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a6374203fe842a2936647cf75ed749227a384ccb
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── a6374203fe842a2936647cf75ed749227a384ccb
│           └── chunk-001.nq.gz
└── blob
    ├── 0068d34578a0ddd2cf815f81e8d3b7a57da48825.nq.gz
    ├── 00e6521866e04aa0dfe00f0fc790516384a61368.nq.gz
    ├── 011f2e680127236e3654e624a495c3f96c912265.nq.gz
    ├── 018cb404923c4c15495fa1c08446bad3dffa1161.nq.gz
    ├── 02219c0a5c1bfc74e684cc63a46b87d8dada48d9.nq.gz
    ├── 029448d763f29c7969024435b84a0390bdcc0d33.nq.gz
    ├── 038e299641dff84c8ee86a48a948cb796230d3ab.nq.gz
    ├── 0489b20328f408843f391a240b570b8f8fc22884.nq.gz
    ├── 0514b3c9cd116cd8bab83382c3a7ea8237bce939.nq.gz
    ├── 051f76f222412a0c81a2df216b8d70ec99dc6f44.nq.gz
    ├── 0548c8c15fbaa544067e50a005e19c0712bc4593.nq.gz
    ├── 058059b1ac0bdc7f048f0963824ec27c8a747b36.nq.gz
    ├── 058a8861bee15d560f4d4e61a8237763fe08e881.nq.gz
    ├── 062322f15bb1e64e1dbaec6f2dad8e21cdc5b29f.nq.gz
    ├── 06e343eecfd5b606879daf2471657901fd80b3a7.nq.gz
    ├── 0721b77a1e9d470f0cdfebd9827bd0f86c9ded71.nq.gz
    ├── 07f642d25ba5dd35780b75058cd4da12a61efe06.nq.gz
    ├── 08139577af1387e64dd83b06d8ed81063a46e5ed.nq.gz
    ├── 092b0e0dccc8673c6fdbdf90b2df2c6b5b976c22.nq.gz
    ├── 0941f8ce7f91008878fb64e020b8cdd78efacb3f.nq.gz
    ├── 0a5c94ee1dc3639526e06caa0ce85105e0429c07.nq.gz
    ├── 0c0a8054c21fc1f32b75b97334f36310a4d9e4d3.nq.gz
    ├── 0c0ed4dd34731dca5556ea6faf4d24def0c837e7.nq.gz
    ├── 0d13f7fb0419b4baa458dc4a28e224991af496f1.nq.gz
    ├── 0d22a42f2281ac17be2c12fc874265b42a9cbfcd.nq.gz
    ├── 0d34e0a42ed5617842d7da6038245589e15f23ce.nq.gz
    ├── 0d926dcf1f5efe242c382835b92a7c2c52051a2a.nq.gz
    ├── 0dd094f7d421b70a56fc7f0811e8801f3a0f26cf.nq.gz
    ├── 0e5e7648b2acdd51e73f1b7fde320351912d0b4f.nq.gz
    ├── 0f096e3de81e37eb612728f84166aa4e1385b907.nq.gz
    ├── 0f1a92b4b89d370618734fe5066c27b82f81b3e6.nq.gz
    ├── 0fb64f06ce7d19226ad5b41050776f4a4b88066c.nq.gz
    ├── 0fcab4b3023c6690eeb1eaba72eac2f6b473a04a.nq.gz
    ├── 0fd0836544777a3450e80387fc0f5edfa90c1f02.nq.gz
    ├── 0ff44407bfff4e523af3fd41b5fe33720b655910.nq.gz
    ├── 0ffd23978b9a866e4de1a69838e1470ef599c7ce.nq.gz
    ├── 106826ca0ec3473cae9d44e24742bd778f72a078.nq.gz
    ├── 10bc8153dd7ff9be4c3086b37d458f2b8186c81a.nq.gz
    ├── 119b1626b77a1840cae10a8e79b8a6287edcde0a.nq.gz
    ├── 11d3443be4691395333994856852df7f00e53a28.nq.gz
    ├── 12eafaf129478d05aa34890608f78a8123cf6296.nq.gz
    ├── 1312a73e363bc34ff4bf26f641e988ad89fa0809.nq.gz
    ├── 139b004a7828bffaed27d4bb1256f01a0420cc53.nq.gz
    ├── 1431f46d0cf271fc9110d592e18441549976b073.nq.gz
    ├── 151ebe4027c10b18e5ed410f8b8270ef0d3fecee.nq.gz
    ├── 15853101694bb78da71ced0d4f8c86f7e0e8ccb5.nq.gz
    ├── 15a881be9e4247236aa5fc5eec426aedec66c805.nq.gz
    ├── 15ad792672b20890be33cdbc2bf204b5b69aed85.nq.gz
    ├── 18058aebd458ea36399bc26905e9075d95ff5573.nq.gz
    ├── 1867e9d32d9a4ff9fe4a2418d3cbba3f27dd9e64.nq.gz
    ├── 19333e5713e0f2e7a7cf44d41cf4c0e12ad24e4f.nq.gz
    ├── 1990dffc31a7b2676cbf87557b87e3e6db7fe534.nq.gz
    ├── 1a6fe1ff6276b4bc12d6592898c842d7c3c6a5af.nq.gz
    ├── 1a7f5db3dfd20ee376bb2734b5a97d9e0afed0d1.nq.gz
    ├── 1add4eebaeee60f1c57dbe76fce737bacbe74b12.nq.gz
    ├── 1b5894d7df06de29aecac91cfd24a8f6e925f01a.nq.gz
    ├── 1b5dd9c2572d4275f11f892240ad89ec0d20ba2b.nq.gz
    ├── 1b7751b8318b9aa3319a0f134bea1f449242e38a.nq.gz
    ├── 1b85b33a07c3be97ef4c3b7003d45335114b15f6.nq.gz
    ├── 1cbbb729c66e9306d11f58dab3557e48364e7e12.nq.gz
    ├── 1ce199fdf6ac7e62efa0845b98284381868435f8.nq.gz
    ├── 1ce4420f9ffd5027c014e366ef434c8b69e3d2c9.nq.gz
    ├── 1d03766ff7a28cafd3c7d4aad0d41ce36d7e66dd.nq.gz
    ├── 1d84045265802b16c628433dd21a29aa97b3161c.nq.gz
    ├── 1dd710ba5dd5ca5b072f515be5fb4359bba26b87.nq.gz
    ├── 1e18d694c10252445c0884f8c87471e77d1ee8d9.nq.gz
    ├── 1e258a616a45c57b18a1a1f84d0a272b469c486f.nq.gz
    ├── 1e579744ab6b74b4aa1d7933fbb777f7d128b596.nq.gz
    ├── 1ed20d9351cdd4ba3f6e579b14ef2e2625c2d2bb.nq.gz
    ├── 1f8d2c6f72c0b1827d2ee6002f01e22d4dd28cb6.nq.gz
    ├── 20c660513aef651c5ff539ce6fb505d0852c19b3.nq.gz
    ├── 212ce83bb8ce680e796ec9418c540a41237b94a7.nq.gz
    ├── 21d43ae778f0276a6cb8f874a4504506817a2535.nq.gz
    ├── 22465dcd6421dabef2826586a9d58495c07887bf.nq.gz
    ├── 224b0941ae6c7be1371509062f715761f67c1bfc.nq.gz
    ├── 225cce68c26aa0b9a206456e74e662f4cb3d16b9.nq.gz
    ├── 2322c0547b1fd0041880709046e1236673eaf2be.nq.gz
    ├── 2463e7f0721a3f75c2a5ae3d7f7b6dbd5086728e.nq.gz
    ├── 24a65f38f97447bf825dc45afb4d0e6708a00729.nq.gz
    ├── 24dfccf18ad8b51e2921a093485b55cc73e7d478.nq.gz
    ├── 259c1086b8f4418a2a17df6c458362552d278eaa.nq.gz
    ├── 26eea3eb3e44d7777a7953d3d5afdf4c749c597b.nq.gz
    ├── 2723bf9c3b92943a77df77953092b0cd0091b9c0.nq.gz
    ├── 2727f002149eb8332238b666a0be62e07b334c5d.nq.gz
    ├── 2821c3daac2ba06b8d900be81f76d4b07012d7e4.nq.gz
    ├── 287b3e8212c5f2762b3235455ce7cbf748d2c9db.nq.gz
    ├── 2911830cbd72830b4cf9088fad29111d1efcc984.nq.gz
    ├── 293d04f1d7011da06cc09ecdafd0469ff9e3aeff.nq.gz
    ├── 29e859d99f56a8aaa7af3a6ac4aaeaf03e4dfcb7.nq.gz
    ├── 2a023c408722b9adfc606b82c1be831f01be652d.nq.gz
    ├── 2a309c940ee6605d69633a87fa1ff250fb78df71.nq.gz
    ├── 2a7126fd4897f41dd5c23535973c15d91edd6396.nq.gz
    ├── 2af30d7a01427542c1e576a8191535cf3a26a0fd.nq.gz
    ├── 2bc5ed66f339fab26b36b010c50d3cb163b228fb.nq.gz
    ├── 2c8c0da5891816380206e45c0689e61c0190aa48.nq.gz
    ├── 2c994aa55a0b8d7556df4c8e7ccf87db11210bbe.nq.gz
    ├── 2d171ee9dedf514160ca4536fcea467b6915dac0.nq.gz
    ├── 2db4b2172de32a3b890232684a48c7f9fc885be5.nq.gz
    ├── 2ec2c8ef59fd25997797261972684bcfdc3ffd91.nq.gz
    ├── 2ef011f8f3d78ae8613c82e12aac7649bffe5726.nq.gz
    ├── 2f4503460c0ccea0a643e7ead2285d53a37b90cf.nq.gz
    ├── 307eb7274bd7715fee8f46227770fb58e1228064.nq.gz
    ├── 3157e0fcb9dd47de90d8ec5649c550f4bbbba909.nq.gz
    ├── 33d7657d3265432746acbc3a276696662f5dde11.nq.gz
    ├── 34d941a48da27d2a17226d64f950bff4eafc1b1c.nq.gz
    ├── 355390fbb52a072830cb7d4fb707e97cb1ec9df2.nq.gz
    ├── 369b5cacf30cab8692c54522aca6d42f02e13538.nq.gz
    ├── 36a4e50221cdabf4bafdf50249128414ac1d501a.nq.gz
    ├── 36b507856406992deb886e48be5ed6b8a4a55f07.nq.gz
    ├── 370d85eca239ca017705bcc9ac60182b82c510ad.nq.gz
    ├── 371f088de09c2bc431b3936506f4302fe291bfdf.nq.gz
    ├── 37fc58c4d4ec244ca1e2dc7bfa003066a4a0c8d0.nq.gz
    ├── 38760fb85c69ef0805ab50da15149e0fc0d6f646.nq.gz
    ├── 390d03bbed4ea5a199f5681e958d157af779f01e.nq.gz
    ├── 39c7b9ee91768307fcf0511a8aa763e10ae2ecce.nq.gz
    ├── 3a8d57c3c3312fe84064f7e2ca5b3e00ea8bca5c.nq.gz
    ├── 3b21e5376ce99bf3c59852ad24e8da7cc9dd0145.nq.gz
    ├── 3d4ff09c58ec4203dcea392efa71287f0d958a03.nq.gz
    ├── 3df012718174c83dbc61309ece0c425ef208fb00.nq.gz
    ├── 3eb05a6a53c9fa6647f08ed55bcfbd16a1975591.nq.gz
    ├── 3ee129358bb4686d4605e57687b4a2c132a36a72.nq.gz
    ├── 3eef97467222900287d032493c53eae152d5d599.nq.gz
    ├── 3eff5e2e06a7cf6446008114c8f7597dec5baeaa.nq.gz
    ├── 3f9b7113fcdd4f4c56b06a082a320a4333b8cf6e.nq.gz
    ├── 3fe471fc48b60f253900856696b4a0846be6105c.nq.gz
    ├── 41689c1ea3a6bf7fe66bd33ccca4c135c05aa614.nq.gz
    ├── 417aff5e9b9d94124f700b09ac149b1b276be781.nq.gz
    ├── 4270a468db1f5919b690c697a5f6e2e75068cdfe.nq.gz
    ├── 42e47260cfa846571ee451ebeabb5e226fbc4516.nq.gz
    ├── 43733b224781ae7dd552106f24dc0b7bcd7fb18d.nq.gz
    ├── 44dbb715a7316d43166cf00eadbbef752e5da968.nq.gz
    ├── 44e87cb0f3e0cf55fd11c8ea8b29b2d522526586.nq.gz
    ├── 44ed456b3a93846f30c8286d864e63ab6a8ef9d3.nq.gz
    ├── 45244671c82381dab6145bc4e8874edcd5d29477.nq.gz
    ├── 45d7fa372497f3b4ee41034478a3fa404bbe044e.nq.gz
    ├── 46250f401024de45faa69beaa15592de646d2521.nq.gz
    ├── 4717a4b6eb5d5f34092f2842c58714ccc8090ca0.nq.gz
    ├── 471a75bdc36321bacd1807eed058f8266edcfe26.nq.gz
    ├── 483daa6c47692a915f6957bf5409b771f218b84e.nq.gz
    ├── 48cc3992d1b5e200a22dd5ebe10d76903bd9a477.nq.gz
    ├── 498303937074c2d50cc05eca7306b47ac1c3a3fc.nq.gz
    ├── 498967a1e6528ec2c2545c35ce2a508ec5c913b3.nq.gz
    ├── 49c283197cd8561747bf9ad2e779b9b344eaacd0.nq.gz
    ├── 4a4d9ee5689f2bfe00e2904be16658ef6b3d35eb.nq.gz
    ├── 4a665bc83e996625c931f541cac66367b0ee3601.nq.gz
    ├── 4a97c19a5776ef9f9bfbde9e73e7ff66217dcc25.nq.gz
    ├── 4aefb04d7eeca05dff144a453f615c9b0aa39825.nq.gz
    ├── 4ba355d57c873dcd0f43e0471b0df1b8d2a98374.nq.gz
    ├── 4d1424f6aa46be496b08d3c825e8a490893e3675.nq.gz
    ├── 4d24c67a8adaad838c434b8ac6e83e9e0fb51175.nq.gz
    ├── 4d733b271098afd46f4247bae670ea3f052fb599.nq.gz
    ├── 4d91043653728d85f472e95ce19b8845f112b80e.nq.gz
    ├── 4e012cbe14732f93a6b598ca8b1da640b398e2bf.nq.gz
    ├── 4e016882db7242bacfb9bef94a4cbe9723580c11.nq.gz
    ├── 4e4a6e75020f96de7795bc65fd842a00dc2a5b8f.nq.gz
    ├── 4eb984f4cdbc5fe85eca720b744d102c38e2c765.nq.gz
    ├── 4f068a7fe4014654c341ac7e80ce06ee9aa2d8de.nq.gz
    ├── 4fa3dd1fac7fc8bd7eb8f8576732c817535c9af9.nq.gz
    ├── 4fef74c0a708e01af70856f040394972d93edeea.nq.gz
    ├── 50582ac77c8e597ad012eab8110a1a5461865d3a.nq.gz
    ├── 508fd043f1ecbd370e1b28340a333141f1f9ba4f.nq.gz
    ├── 50ac74d3026d0a72385171b25ff3a9b4e156f347.nq.gz
    ├── 50bba3346ae32837a1365743a89c2a26fddad1bf.nq.gz
    ├── 510cc46513ab2cb4b8c17820b85e7ea6ae309d9c.nq.gz
    ├── 5261ba94636457b3511f7622b07001bd4ded95e0.nq.gz
    ├── 52ea870104bfa2c25597faac37b6f6f69dde3167.nq.gz
    ├── 5323b525619395b2396cb7def9ac072f015d8cee.nq.gz
    ├── 5450542e9f5b69e23435e20ee2538d3366be4f79.nq.gz
    ├── 54750b975ac168cb1ea1d003d9bf1d0541d2f6fa.nq.gz
    ├── 550f0f6237fcb93bbc9b97613272bc10692e0b6b.nq.gz
    ├── 558e1a81a7b9797524bb5acbf10677683213f62b.nq.gz
    ├── 566f43924c9d4090fc610776a1bdfc6238ab4246.nq.gz
    ├── 568e00b8fca8c172e4206205538809a1f7af5886.nq.gz
    ├── 5812bcf430178e044ecbb4846e038ebfaadf74b6.nq.gz
    ├── 58fe6bb60820ff922c8013323a0fffd8e2b8515c.nq.gz
    ├── 59ccc39f949ec21c0c49e0a422c2eef8b47c0752.nq.gz
    ├── 5a5490c647086db3dca19b8b70e257ad480c524e.nq.gz
    ├── 5a767eced6fa98288da721f5b583f931167e920a.nq.gz
    ├── 5a838651e8b1a12c4e7f4f1f46e3c17b00b1ae06.nq.gz
    ├── 5bd547f6690c2a223c23e07e64a7c924ed6697bc.nq.gz
    ├── 5c5fbf1f25277d686b82fe2b2024e56a944e6d52.nq.gz
    ├── 5de1dce91577dc3bcce3c04e11ec1b78b1fd5518.nq.gz
    ├── 5e43ff8c779576f509eb1e849fe5ed01dce189d7.nq.gz
    ├── 5f6623710efe4fc3407ac0c1fa2a4fcf33c8e5c3.nq.gz
    ├── 5f9a9134166204448d0b8a5275a0797f977eb146.nq.gz
    ├── 60cd50521fc5f53d443d94936622a0b30c07cc11.nq.gz
    ├── 60d3961b48ac3588bfa2f3503be89861d32ee7bc.nq.gz
    ├── 61ea83f6fc688877ace8efd05e60cbea00d5cb78.nq.gz
    ├── 61f0d48d317cba22f50adda8ad93c6bb594bdfd1.nq.gz
    ├── 6390991b4594775a6bcfb86f119bd40fed92ca08.nq.gz
    ├── 6486fc6cfb122aae8c0a77f1f001fc12de69747b.nq.gz
    ├── 6553d6586992afdd12c48749e862b35a7073f322.nq.gz
    ├── 655cd98c541eef825fe3ac2d3525b57ddafb9002.nq.gz
    ├── 656bdb4c31823362ce1e51f0e828d4286e70deb4.nq.gz
    ├── 65a0c71dff04768c463fb3fd596a3dd83d413e29.nq.gz
    ├── 65ecee2b317ac7f9e0020bc770d78116e3d52210.nq.gz
    └── 6635284dbcd7b3acd71d2dde9531701e66695d69.nq.gz

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

[pydicom/pydicom](https://github.com/pydicom/pydicom)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
