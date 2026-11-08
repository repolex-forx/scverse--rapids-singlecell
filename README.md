# Repolex Knowledge Graph of scverse/rapids-singlecell

RDF knowledge graph data for [scverse/rapids-singlecell](https://github.com/scverse/rapids-singlecell), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/rapids-singlecell
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a948cc20730782b09dfcdf589209bc8ab0c868a8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a948cc20730782b09dfcdf589209bc8ab0c868a8
│           └── chunk-001.nq.gz
└── blob
    ├── 002ec0884d1bbdd27353e1666e165cf467b42bd1.nq.gz
    ├── 004cc26a409ad630bad9cdc01e5e1c7f73d92db1.nq.gz
    ├── 009e4aded9f409018d2a14d4d198770d429e2614.nq.gz
    ├── 013c5397c1db70cfb8763ee0c44bb3c06e3b0103.nq.gz
    ├── 01733e46fb603f4ae819d3f75de89c4d91929874.nq.gz
    ├── 018d88ad0ec9d0a1160fc97ce11d0d2a68048eb0.nq.gz
    ├── 01990cc13a20850da07a606d98f2ecd3b688faa6.nq.gz
    ├── 02ae8e1a6ba79ee63d50fe0f967907f86df2079e.nq.gz
    ├── 02b81a5460aedd73bad76479a857a459e421ad91.nq.gz
    ├── 03b067748366e11e53b562ebf32d9d63031a7044.nq.gz
    ├── 03ba1ace690bc2d4b632a435050c200fb1ca3d2b.nq.gz
    ├── 052748f368f410293112f50e13220553b0814f68.nq.gz
    ├── 06a6b4d390d75fcc39d5952eebad9856d8f89a7c.nq.gz
    ├── 06c3c0aed46a09e7562e065d379738d53706e146.nq.gz
    ├── 07ac768c44aecfe6c631d85315771ef4abf57be6.nq.gz
    ├── 07deaa5ec608e03f32b1f00c7aa8f76f8a7264dc.nq.gz
    ├── 084d0f1fcabd8bfb699336ce686a4d1576363d83.nq.gz
    ├── 09330434404527884b4b0897d1b843735aa69d8a.nq.gz
    ├── 09fd47280c065dc89c5809404fde6f95f4e1ff76.nq.gz
    ├── 0a7986aa2533f9b78fa8a49944d6b16907cdb459.nq.gz
    ├── 0a9645fdbf6a0b73aa5d76aecab1d9e9011c2e7a.nq.gz
    ├── 0c280b1dc7df69f0a49cb490bcde39763dad2191.nq.gz
    ├── 0cb18a4787bec4b501c086a4541b4666ef3f87fb.nq.gz
    ├── 0cf6bd7cc70b421d5df97545e3edd16f3de30c44.nq.gz
    ├── 0d82da3696c4853f6a56d629633bebf722fe9d5d.nq.gz
    ├── 0d93b62d91d9483329e2fa6f8ae32427534f649a.nq.gz
    ├── 0daf62436bcfc630b1b9fe8310486eb0920b9455.nq.gz
    ├── 0dd0660492f4183ecdb67b0f4ff7e4fc05d1bdeb.nq.gz
    ├── 0ebeb346a56bfd23def15329d96894cf62dca527.nq.gz
    ├── 0ee6631063edd3f10974216aa8cf1d7bcabd3a12.nq.gz
    ├── 0ee79200f199608d227f79fecf2b7ee3cc3f2d22.nq.gz
    ├── 0f87a6160ef73acc4acb29e3e56d2b8581894904.nq.gz
    ├── 0f956d224aa4f8be86da53d6945cd8296490b51a.nq.gz
    ├── 0fbf4c4d9934dcab174dd4c2f0b1b237d03b4ff7.nq.gz
    ├── 0fc323ee1d8d3e548b43dc1fff6259df91ecd3b8.nq.gz
    ├── 10ebb3992780d72c356e09bddb785d69ddff5288.nq.gz
    ├── 11f2bce6dcd201c62a137b479b70faf433919f28.nq.gz
    ├── 11fc569a0d8e92a6b649ff12ccb29087c67ecbd3.nq.gz
    ├── 13370fc300d06cc7b2cffca10bc7ee4d1ddf3db4.nq.gz
    ├── 149a88ebeb1443021f4b9035f2618254d1041c46.nq.gz
    ├── 166e82e85498da9b6985c7acbc7edf453c0a4954.nq.gz
    ├── 1718d3986c0558389b406d99431c29f7b8a30489.nq.gz
    ├── 177ee2613c3eaad43a43b093a5f94ca7ee30e9df.nq.gz
    ├── 1879d2e964224fc264714bc589a22a63f3d2647a.nq.gz
    ├── 19d62a7d074c87566693b388f6779b423b65f2ca.nq.gz
    ├── 1a62e4262bc3cde0b401f5be990c20dd2277e669.nq.gz
    ├── 1b5f4a3bfdad708b69a6c97cc1fcca50e773ecf8.nq.gz
    ├── 1b94247278439dd53bc7b3239551e499a615416f.nq.gz
    ├── 1c02cca38e7f3a5879c5a81429d07b144a0fe088.nq.gz
    ├── 1c3ea082c2255a847d667757ed1a8660ab77b2c7.nq.gz
    ├── 1c51da5f9130a9a8a6f7510200eefba5b29e7fc5.nq.gz
    ├── 1ca101edea40442f8110c8fff87d7dc5a7d627c4.nq.gz
    ├── 1cb372e8472ea507ef8f4a2646e12bed7f19c413.nq.gz
    ├── 1e0db393fef1646c35a1682e4de30d289671add9.nq.gz
    ├── 1e3db252ee839b9662ad7ec577dd6d576306475e.nq.gz
    ├── 1e6092f22e910a94aa12cf91e869c845f8cdbebf.nq.gz
    ├── 1f2b46e512d6d02a67820fb74458d5ecfc01bf1e.nq.gz
    ├── 1fa81277094ff2497e5cc04ecd352da000bf0bb6.nq.gz
    ├── 1faab8c149d3e808cf98baf9fc689a715e3f0372.nq.gz
    ├── 207512e03b83f9beac2e5e7eb4a2ac8f36deb3cf.nq.gz
    ├── 210f26f42c3bb61bde7999b445d8a814156fc201.nq.gz
    ├── 214f1a3f0bbf7b7488ac6f62ec85198ce132dd7a.nq.gz
    ├── 21521da6661ccf6a1ff9b56f0a82d5e307057196.nq.gz
    ├── 2293e94e65eb49dbb6b3161dcc28aafe6e65100b.nq.gz
    ├── 2301cbfc2e43c5ee1a5583adbfe6ae9deef8e897.nq.gz
    ├── 234400be1859169a4a78b4c6e3c0fb29c8d46c41.nq.gz
    ├── 240d91cb05c9acc95f766db0ac27685715bae6bd.nq.gz
    ├── 251aec2c401291ecf777cf41ae737a32baf7b869.nq.gz
    ├── 252d3fbe21c5f8326a964080bb95d4747e62752f.nq.gz
    ├── 2792ab5b757f18200b389f056528e6493c239c96.nq.gz
    ├── 28828e63cf7bbfbf8119c00efa622f269a9a0646.nq.gz
    ├── 28b99a766275a520820d8c5fff3aca9185e2848d.nq.gz
    ├── 2a79338fbe040bb98a11e6133dd83e4ec9838a8f.nq.gz
    ├── 2ab7248e47a49ab228aa517f033b2443dc0c7ad5.nq.gz
    ├── 2b197e94819776a21f698c6c0abe3b26e46b330a.nq.gz
    ├── 2b75a352627bc9a9b2665ee111101e5855f52865.nq.gz
    ├── 2c6c4747cf2e5bd01b56659ec5f187aa360eecbb.nq.gz
    ├── 2d10ecaae36a403cd45f36d7d372e07a8fc3537e.nq.gz
    ├── 2d2127926f19033084178c662a47387348acf895.nq.gz
    ├── 2d493981c4df828925f868ff6c4dea095b8cdd8d.nq.gz
    ├── 2e3060763eff2013f935e1f9068ee2b173e7c159.nq.gz
    ├── 2ea317a5747bea3c4b8a5d5b8cc4f32592069f36.nq.gz
    ├── 2eac84d10ed3727c9f2d70a54b3de5091af9d394.nq.gz
    ├── 3023cb6067cbfe12f7e0671e252a6eb29d39332d.nq.gz
    ├── 305e1377abeb9f5d063215c5bba6f81a28857a3e.nq.gz
    ├── 31701d286cf5be08f14a379554117d7806450567.nq.gz
    ├── 32026b0eb261504252ff0767b4535732210b2cbc.nq.gz
    ├── 322793040792b8440f6bb6db6e29660b8e54b266.nq.gz
    ├── 33fbf1909fa3c67755330cc57e508ce63323edbd.nq.gz
    ├── 356e54cbbf43942557f0dee92de0afba473ca947.nq.gz
    ├── 38c84dcf063276f7fa9e034606ccf7943002377c.nq.gz
    ├── 39c267477b101f64cf04e0a64a13a37f8ca36a11.nq.gz
    ├── 3a1e2f409bc18447c79b1152b129e9f3423d738a.nq.gz
    ├── 3a3765672fdb2dbb409bde746648905a290890fa.nq.gz
    ├── 3a49926a34596f75f25b3ddaf1352568c95da909.nq.gz
    ├── 3a9ca41f8a9ebf481e87caa6a192fb5d60bb3f2a.nq.gz
    ├── 3ae25eacb670cd8d672d113032fe350e03eca034.nq.gz
    ├── 3bc018c4c6571c8041b07cca4059e7722dbc3f24.nq.gz
    ├── 3bce719d709373f700e8e016c882656196772373.nq.gz
    ├── 3c212f11401e5ef2a6938945f7fccdc32572e7a3.nq.gz
    ├── 3c49cd15b533ec04bdf6e01a94f77c2a2d47ffc9.nq.gz
    ├── 3c5447644d30a419d1d82c641d50bc1dfe94528e.nq.gz
    ├── 3cd2a6bb2e0dab656a7cc73c4ff6ecf0d30f2b7f.nq.gz
    ├── 3d140842d6522ca5b0711168398d9a50985f9414.nq.gz
    ├── 3d4a13e4aad5dd0cdf4f2c51568da2de07b3d5f3.nq.gz
    ├── 3e51dcd05f643e46d126a98ca9828b9eee9da004.nq.gz
    ├── 3e703c7f3e63d7124d7461ab14934c296da70a5b.nq.gz
    ├── 3e8bf79f23f21a66ddca6bcdf19983f037a3642d.nq.gz
    ├── 3ea0afd8e48bf884715963365d2a5745f93ab1b9.nq.gz
    ├── 3f065d96ad0963c839e22badaa4018cc544aad8a.nq.gz
    ├── 3f3d8012330590a62fe82553ef501629c01bd421.nq.gz
    ├── 40473cd66333b68f959d461714fb49e1fe09aef6.nq.gz
    ├── 4057742b6128307835ab0b1c9a5dc70c8827dd2c.nq.gz
    ├── 410cb8dc6083ac70f94f6e71af52b215e1144d23.nq.gz
    ├── 414dff4070646bf5936aab045c476b13bc428de4.nq.gz
    ├── 41c1879d42b60e9d4207b2ebaecdd5b65a56b65c.nq.gz
    ├── 42acc647c9248cef1b3077cd4c49f0e1272f52d3.nq.gz
    ├── 42b8121772d4b68b978c32e6547e93da3c88bffd.nq.gz
    ├── 4387a448e51994a1a066e60e377cee69d67e4d1b.nq.gz
    ├── 4439fd81b125f2838f7c1e5294ed8dffd9708c9e.nq.gz
    ├── 444816ea04160a50a8c9877a60dcf84f7229e2f5.nq.gz
    ├── 44ba183dacd9282e0c238ae764fe24bd02579363.nq.gz
    ├── 45f3d988c22df8c16379e5a8bbf0fa2bc2b55d4b.nq.gz
    ├── 466ca75a96e62da70813b09e4f3f4dd36471fb28.nq.gz
    ├── 470faf152a6fdc1cadb4739cea71e48fecac088c.nq.gz
    ├── 47fab9b89a2033a033e08b20d0148bdba84ce419.nq.gz
    ├── 481742f4ec714b533aeaeb6481b9428ff56297e7.nq.gz
    ├── 4840f5c04ed5b46cf61ce8da9f637267e346d489.nq.gz
    ├── 484557b6ba0ca5f0f312e6c1a73a2054d4a8b2b2.nq.gz
    ├── 4a267cad7f2f369469321fa1ec71d1e2b0ba37b8.nq.gz
    ├── 4be920990bad1b7d1f39b161b8b0aa4810eebb1f.nq.gz
    ├── 4d4b714823bb52335482553a388c6b08a753be47.nq.gz
    ├── 4e5443e19bba220cd3a3998ff601f7f3a5e96aa5.nq.gz
    ├── 4ecc22785cf9129e7f29cd78c98169dd843dfb53.nq.gz
    ├── 521aed3a792e59602a13415a51fe0c9f8fddb9a9.nq.gz
    ├── 539df5ed5c3e6522a4306900efa572756189074d.nq.gz
    ├── 53fc0f45e70d32cfcce2e3f88ee44f2da76847e0.nq.gz
    ├── 547b111cc3c25b9df89297fbb5c81c7e5fa6264b.nq.gz
    ├── 56c91a1ddcf2c50e91bb7749b5cf457d34e47e1b.nq.gz
    ├── 56f625158c46c965d68b7cd5f824ea350d7c6645.nq.gz
    ├── 5795225be0d45c2ea20bacfe76f91c87e4158ff4.nq.gz
    ├── 58124ae58c4b1ab2186bb294b1c177e916bfe875.nq.gz
    ├── 585860b62864e9040b8a835a2b14ada524a1c615.nq.gz
    ├── 59050c82f2bd3590848bc40d09521141aba986f7.nq.gz
    ├── 592184d418c3bb6a9ea386a45d01362afb4ddef6.nq.gz
    ├── 596d08f3f1b028ee5949b631b745a60ab9ecff4e.nq.gz
    ├── 5a590fb35f33916c28e2122cfd1a6f11a4854e28.nq.gz
    ├── 5a82b789a5ca8d043e65dcf6da26c62a37a590c4.nq.gz
    ├── 5aa883b9e25a91529b84935a1232b403a62d8d1c.nq.gz
    ├── 5acfe81a03455f16a89147c9f06428645bdba6e7.nq.gz
    ├── 5ad44ef8723b066c86b3f724a2ddddfe4ad8c430.nq.gz
    ├── 5b62547f9aef3da3a38806baf365ea8c059675d6.nq.gz
    ├── 5c0826c5921ec65ec2ccf04847c99481d9471e57.nq.gz
    ├── 5c14d59799b16b3b8736207952412fa3a3a5fd69.nq.gz
    ├── 5e7111b0ede0e11a3e862a2dcbde31cdd6ec260d.nq.gz
    ├── 5e737c9cce2a96174c10d8f405a8c03d8b41b1f2.nq.gz
    ├── 5e839dabf0ccb28ec98f2458383e57f90597deb9.nq.gz
    ├── 5f28763bb7e25e454c60172db9877717f004852b.nq.gz
    ├── 5fba61b7a75a3d9336bb5ea7841133374004b476.nq.gz
    ├── 5fd74b68f3f332762c94a7cf27b46b5035ad350a.nq.gz
    ├── 6031fb1eaffaa48eb4b1a83b70ae77c41c937a57.nq.gz
    ├── 6064e1bf3b0ba6d4821db7e5d062e621af04a81d.nq.gz
    ├── 6156c720489fecba5b7ab75f246278f4eaae77fd.nq.gz
    ├── 6313b56c57848efce05faa7aa7e901ccfc2886ea.nq.gz
    ├── 63468a7b4e577ba85b57e3e41adfa005755602ba.nq.gz
    ├── 6401ef9f05940afcd1cb54196aa6cd88f9d1610b.nq.gz
    ├── 64d7b6b7f671f1b02445f3c15d92413d1764ee2a.nq.gz
    ├── 651f0a82bfc4cf42bb57029baecfab27200c6d05.nq.gz
    ├── 654d7484f31becf484a059d783011a153dece95d.nq.gz
    ├── 6550ed15caceeadc3754a4cecba8905f6d73a635.nq.gz
    ├── 66220a692592890c8981a31de2b6ae07cf98135a.nq.gz
    ├── 67316cbfcb27eefa08a9314b5a41f65c3ced7363.nq.gz
    ├── 67937504933ba4b75182e949af37c03ff9f9ba22.nq.gz
    ├── 6977087598a24f0ec11b1046be6a080d735623f3.nq.gz
    ├── 6a4ce17df50cd05702c9fc9d82c103d5ecf4537d.nq.gz
    ├── 6ab0498af12b7984640405724137c0da3a2edf3b.nq.gz
    ├── 6ac3e066545b1c0c7d817b2c210c80d0ffa2abab.nq.gz
    ├── 6ad415b779c38dd1d0348ec4adc65a3eae55a256.nq.gz
    ├── 6b76f7cb060c3920bf75f613aa663bd416ebde86.nq.gz
    ├── 6be8cb508761803683fa1e706045d5a8a8a6b2d1.nq.gz
    ├── 6c5d2d3bc8a1079a71269b8dd8fe00fa7b862c1a.nq.gz
    ├── 6c64cfab60755af11495145d4134ff8bc6d4f37e.nq.gz
    ├── 6cbce00724e623fe3e3ab4af81c8e4c15773683d.nq.gz
    ├── 6d572e87d4f0b67e95e06985d45827c1448b9fbd.nq.gz
    ├── 6f42c383540febc5a165fe54d89303e8ea793377.nq.gz
    ├── 6f955273322d48b208e46e75e0df997648bc95b2.nq.gz
    ├── 6fe78a1d672820191071532d9a45fca6e44acec5.nq.gz
    ├── 7023bb606a6c782470c25cc98ddcf2b60f1c5db4.nq.gz
    ├── 708c3fc776342d81cefa04cb7ec335d678b38bd7.nq.gz
    ├── 72c6825574b95d88edd959954f290fb62a2798e8.nq.gz
    ├── 73b5668c001cd99373cdbd123ddd824c9f750c3c.nq.gz
    ├── 73f01edeb5269b3a8849680601c931a767a0e832.nq.gz
    ├── 74b68c8ad69d138fa78e10ceaac2710b1526bf92.nq.gz
    ├── 7560d34fa2e1d20e198c9650a317ce673d1b2d14.nq.gz
    ├── 76907389447ba8d91d9db294372e582f8a7b96ee.nq.gz
    ├── 77113ed92b6941a36898ef4b6f0580ce78477bb9.nq.gz
    ├── 775c88fc9a8aca26e0536bad6ff15b9dddd74296.nq.gz
    └── 77ceb1c2b72d6cb5ae4e0bb37ea51c467741a80a.nq.gz

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

[scverse/rapids-singlecell](https://github.com/scverse/rapids-singlecell)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
