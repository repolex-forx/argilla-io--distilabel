# Repolex Knowledge Graph of argilla-io/distilabel

RDF knowledge graph data for [argilla-io/distilabel](https://github.com/argilla-io/distilabel), parsed by [repolex](https://repolex.ai).

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
rlex download argilla-io/distilabel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 313fac85b1a2472dd88db1a31c2b754599f46476
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 313fac85b1a2472dd88db1a31c2b754599f46476
│           └── chunk-001.nq.gz
└── blob
    ├── 000e6c0463b9361e1acc941df558447cbffd4cc6.nq.gz
    ├── 001ec827ed16355f43e6772e2115d0f4e195cd98.nq.gz
    ├── 0029615f2bf0bed6eb5cc93414ba4656ba4aa2b4.nq.gz
    ├── 00305100dbf59840df91dde7e864cd7d82f8f474.nq.gz
    ├── 00707f17a9b61f64b83ecf22d2103a7ec8f570e1.nq.gz
    ├── 0090ef2af409f91deddddffea35f8f182f573b00.nq.gz
    ├── 0101aec196bbc6f00c47e9c199ad93e6566aebd9.nq.gz
    ├── 0121550f541c110c7aed4ff931214b13a4d4e09b.nq.gz
    ├── 01921cbb7cb3b3db306a2fe511d5fe64361ecfcf.nq.gz
    ├── 019ea5e515b39bbfaca7c89f3b01efe1ca28b689.nq.gz
    ├── 01d33624b5d805ae81876661fad22fcbbb65217f.nq.gz
    ├── 027c67809bd51ba94090944cb308157cba2a1d5c.nq.gz
    ├── 0291a0626378bd4e450399f095fea49e4b408387.nq.gz
    ├── 02992ff20bc2740be544bf6701567fbf53b4a655.nq.gz
    ├── 02ed31feedcc5427201807285026cb093b02715d.nq.gz
    ├── 04125242ee9d18638e84265c7fabf24c1289001d.nq.gz
    ├── 05c80c6cafd0f113193cffcaf7e9d6572a21a4d2.nq.gz
    ├── 05ff410ac5005ddef54b89da0557ebba9cf6e422.nq.gz
    ├── 060eb71e0800ae8dc23494859bb56bc6404ed147.nq.gz
    ├── 06358a618961baa1847b3adb1424752a00fb9727.nq.gz
    ├── 0664a2729b01c86bb802b35561504d7a8106949a.nq.gz
    ├── 0718e1c28c701c469f09fcf791da164daa3837a2.nq.gz
    ├── 07b349334dc00c6608b18cbb68bc4fc9b15de475.nq.gz
    ├── 07de3982b75ff8b216cad9435b5042579055b980.nq.gz
    ├── 07e329b4d927844250669430d1f728e676c4744a.nq.gz
    ├── 0835cd834c2d0fb585178793e518c28175e81d5d.nq.gz
    ├── 08d32ba1bf757cef4e187f4ef9f85badd76db73a.nq.gz
    ├── 08d9456003363c6992dabfc4148d259519a182e1.nq.gz
    ├── 09042b36aaedba10f7581d46cbf6d904c1247d94.nq.gz
    ├── 0978edb3251b516cf12482205094e4a805cb0c6f.nq.gz
    ├── 0aaebf261b0f3f42e5e4a0af2a5072c8b001005b.nq.gz
    ├── 0b2277f0fb79d1394bcb271c5ed1dff4914558a9.nq.gz
    ├── 0b6d1715d665a6658a77023db76d34def88dcac5.nq.gz
    ├── 0c9a342aeaa92d29d643a2bb36526fab3914c623.nq.gz
    ├── 0d5b837b18f222a0c4d80e9556a061c1f4d6d009.nq.gz
    ├── 0f2bb66f2f09f94ff23e5552b0e1b37bfdf811ea.nq.gz
    ├── 0fddf6618dece45a9d9f5049fbc54ceefc1cabdd.nq.gz
    ├── 10335f15c366d63772c7528d56b3cdc64abca264.nq.gz
    ├── 104726307d8fbe6fecb78817c8cb7b38eeb6598a.nq.gz
    ├── 1139254abb81b0a45e8eaf472d353277f26b1d3c.nq.gz
    ├── 11725d41fd45e5d7c8ecf6f253786983d9a4cb7c.nq.gz
    ├── 11b04a9adbd8d95f973ae07177d9adac71273ff8.nq.gz
    ├── 1309232a27de4ff7e922ac0da43eb424220ff74d.nq.gz
    ├── 13c4f9f0be3c3f427f17a9c9bd118c219a4528b5.nq.gz
    ├── 14e08e1ff9eec846fe7a7d5a78254c5c01b27984.nq.gz
    ├── 152a0063d934c3734f86b51d097f6ce30c69f2cd.nq.gz
    ├── 16645c0957b90fef31bd5e0d935bbe26b28d3f84.nq.gz
    ├── 1675d369a661eb77276b0f35d21c196a17a62595.nq.gz
    ├── 168c28f72b477bd429bfdc251f4651d44b09e758.nq.gz
    ├── 16cd44f6bcaa039e86c8787685b5cc4c675309ce.nq.gz
    ├── 1742ac675d4a6442d62041e34c42ef992eec022e.nq.gz
    ├── 1781ac9e6a381cf30bc1b2104bf738d073e2cf14.nq.gz
    ├── 178b3e5eacfa041592bc4846792663a2620ea848.nq.gz
    ├── 180c46929ea31804533acb226916f22aaa9be645.nq.gz
    ├── 1874a14986f4f4ade16768833e47ce3aa28d8c20.nq.gz
    ├── 1888388f6e8f1415bd9f9494772d11764b4e823e.nq.gz
    ├── 1aab313fb92689f764838631244a7e772837617a.nq.gz
    ├── 1c96f5ab0bcd4c84082e70c8c41c58a88153c526.nq.gz
    ├── 1c99f2f5c40e23251f66804d313002d0f68ac28e.nq.gz
    ├── 1cb827ba8dac80126fe0189ca240333354a93730.nq.gz
    ├── 1cf238015f299750eda9802dcd6d835edeece06b.nq.gz
    ├── 1d98faa6fc1d4e4395ef6147c1c6217a80e7c146.nq.gz
    ├── 1e874c5f9b0f8d88ebd8650c292a0171678b4f5b.nq.gz
    ├── 1eb47a5e96336b5769620f1ecd51f9f67071bbb6.nq.gz
    ├── 1f73e19ce68f3f9f35975c273ada199318fac798.nq.gz
    ├── 205e96b984daef06211bd595d7119069c8c51c58.nq.gz
    ├── 20ce00bda79e3f8fffe7e8925feb00caca163cc1.nq.gz
    ├── 20f644dffc329b787d43814e3f25343217ca7e3a.nq.gz
    ├── 210a338e35e4013b23217988ca0ced7d8c53043f.nq.gz
    ├── 21da0784b7c18a6b51950963d872e7cee71e7374.nq.gz
    ├── 22807797992ed345de41ee8c1b1344ab5ddd26f6.nq.gz
    ├── 22cb6d02daf7ae0334f283fc54873907b3aa9ef5.nq.gz
    ├── 22d22e60a2b52bcd7347d2c29e02fa38c0a33229.nq.gz
    ├── 238d9338edc9018c6e82fbd494b3c374c7b8b384.nq.gz
    ├── 23fe6d66d52786695aa817c5d01777a5349c3df8.nq.gz
    ├── 242a3186260ecf16bc5dd7b98fe14e5691071675.nq.gz
    ├── 24dfc197550488543a45bf27ff9cd75cd43a819d.nq.gz
    ├── 24e5ca9b74e9e40fee3a30ac4c0ab2aa14c75ef9.nq.gz
    ├── 2598794f29f7c0f5d78961cb6c8955a0c816f3d9.nq.gz
    ├── 25e60cab0b2819aea5bead2f6e04962ce742b376.nq.gz
    ├── 2688088c6ff65086a817d4787d579289ce3329a7.nq.gz
    ├── 26dfa1b203ce8d2c8f5009b6038b83ab8d947ceb.nq.gz
    ├── 282b2987f12c64dd0ebe273ec880dee2b139978d.nq.gz
    ├── 28ba10a12b2806487bf19b71647c3bc9d8667e73.nq.gz
    ├── 29ab8131cb90e94a54fc9d7941a8cd45593b6d16.nq.gz
    ├── 2b36740c7afcc8c7d4fd6e63d10118618a33c562.nq.gz
    ├── 2b5839384bced5dfe64e6d511989565e2e17c582.nq.gz
    ├── 2baab4baee9a42d6170901e34cc5836ad97edbb1.nq.gz
    ├── 2d1158aedd6d39b0cb66bfb5b65d81c247a2d91c.nq.gz
    ├── 2dad1f5210886e6c9f7bda2b69c5b52e3695428f.nq.gz
    ├── 300237c843bb3b1e18365bf87ec84a33e782ff14.nq.gz
    ├── 308fe989be5220a5c06d6b8cbc8b45ef2d4eec8b.nq.gz
    ├── 30bd06262da3431c6316f916cf2f9a0ba47ec9e3.nq.gz
    ├── 31748034df6381981106cd70b28dc0d42bf3b84c.nq.gz
    ├── 317b7d6dbf8b2fd8567b5a96a7c4532f8e6834b1.nq.gz
    ├── 31889acc90fcf5e9b56bf737ef232774f2e478df.nq.gz
    ├── 319c69164be7b3068b0c028f4f7a1fb57d0301ac.nq.gz
    ├── 31c7010609f6d90c924fa56bc900819f2dbedb90.nq.gz
    ├── 32882e03794416d31bc41a1d4efc9dd8ac21d0ae.nq.gz
    ├── 3324caa3049e77c23d2f6c27b62aa55cef648bae.nq.gz
    ├── 3469c1e2bc6ff0bad9b996d4ec2b412ce2ba8d4f.nq.gz
    ├── 34accced2b17e5bf2714124eaffb4a7cbacd486f.nq.gz
    ├── 34ec873bd367e0af7eae6c6d33803180edce2c77.nq.gz
    ├── 3501b9332d159e3b5cf15501f179ae2e068370d9.nq.gz
    ├── 354777bd946c381bcb2d09527413dea7eb04c604.nq.gz
    ├── 356bf5a2e7b6afa548f95d682172128562a8dc15.nq.gz
    ├── 35a6d3b22f8e9ec407342726818218b87bfc7ea3.nq.gz
    ├── 35acda2fa1196aad98c2adf4378a7611dd713aa3.nq.gz
    ├── 35c1be4dbc2e4e101cef7e0679fb7934dcae6360.nq.gz
    ├── 36506711188a02f903747cbcf3c86470a49d78ac.nq.gz
    ├── 36e8e6ac9fcfd62cc461f93a3176e0768427efd9.nq.gz
    ├── 3767451991b7902aa67e1117ac6b93dd4f585f08.nq.gz
    ├── 37a4adf989b621c9b7802fdeb1d5877cdf45bf35.nq.gz
    ├── 3815c6db83952fbdac5d17d4bd4958cc3b6247f1.nq.gz
    ├── 3824cbf1160ade18dc3ad4221379a08f2b71e819.nq.gz
    ├── 38daa7f857e02b9a4abd418fa0ce39bc5a0bf545.nq.gz
    ├── 3929aaaedfddd1239876af0d8eeeaa8b6412d291.nq.gz
    ├── 39f8daba3bafa264e4e9dc5996183d418a91af86.nq.gz
    ├── 3a575545d14d8f079208c812f8d9bff048385c91.nq.gz
    ├── 3ab252fd248af2f64ad7a6dec9f571fbbac05eaa.nq.gz
    ├── 3b43e97c8fd5671bab0efb4542e671fd723eb0b8.nq.gz
    ├── 3b4c9f186dcdb42651ea12cc25da3f0ccf46310d.nq.gz
    ├── 3cdd17fc96b65b073637f1a843d1f30f698029c9.nq.gz
    ├── 3d16c0bf485b1e5f9995f4d1bf4b3e5f51e3f807.nq.gz
    ├── 3d2e5660479750d539faef5d88f262b3e31c9e1b.nq.gz
    ├── 3d3e6f9c576a342835a15c241a167ece3e881860.nq.gz
    ├── 3d64c7ab24709ddf60087894bf089971e391c3ab.nq.gz
    ├── 3d808463700886477df7d65c88fcdeda889ffb17.nq.gz
    ├── 3d89b11e50410e595a5bd6639b6867bbfeefb6e2.nq.gz
    ├── 3d9c7f7ee016396c40e59bf09898eabbc093c8ef.nq.gz
    ├── 3e0bef56e65b3967bc3cf0dfb9b72679175a8346.nq.gz
    ├── 3e1d1822f3b3d0e052c55040a3607423df0068f3.nq.gz
    ├── 3f739cbf2ad307c50e8e7ea08a4545b05564a738.nq.gz
    ├── 3fcb92baf3bbaf5eff885bc3ebb8875062163ef3.nq.gz
    ├── 3fdb037e14789e09acf1c042d2f855bda98b749e.nq.gz
    ├── 400014a4b06eee3d0c0d54402a47ab2601b2862b.nq.gz
    ├── 401ec0f36e4f73b8efa40bd6f604fe80d286db70.nq.gz
    ├── 4082f978e8f51187fadfc97008158e2d879a0ad6.nq.gz
    ├── 40c40426a08be5efd5ab59fe2ae6eb5ac98cc1e8.nq.gz
    ├── 4139eef525fd6c1a55614807edd01214958ef596.nq.gz
    ├── 41441381df5f673455770ca46ea9c5ce05e4b062.nq.gz
    ├── 415654ba12fa7175bb86cfb1b4422de5f20c1ce4.nq.gz
    ├── 41b70591ece8817f9046438bb969a1969a5dd3a0.nq.gz
    ├── 420c6ca0afeaa8e9d55e77ac89bec800cbc234e2.nq.gz
    ├── 42204c160524c21eb7dce85b320cf12b5265632b.nq.gz
    ├── 42a4f5a3dbe80513826da57c0832cbdfcc1bafcc.nq.gz
    ├── 4325e264b56ed5f68b326bb51f8eaf09db7c0428.nq.gz
    ├── 4334d72bdd84ef7caa3c64d7f2a93e2fd98b1739.nq.gz
    ├── 43a7d552b741792e4d200878b48c77732ed6525d.nq.gz
    ├── 43bb199b95e848e7472db28e2820f891049cb3aa.nq.gz
    ├── 4572bca5cf2cfc135587a9226856d8223f246c39.nq.gz
    ├── 45f9088ca502f27a529c677e59637acdd94753ed.nq.gz
    ├── 464ed0e763a52dcd0bfd478a6353e6599ee335c3.nq.gz
    ├── 46ab4fc18d0f5f92d3418519d607d219697eb603.nq.gz
    ├── 4757cb14705652059bcb4390ee1e20231f4d47e3.nq.gz
    ├── 47f1f9720e5dc1198baa975a9206b35ec9d3b9b0.nq.gz
    ├── 48b765c1a936fa9a9eea0d68ec8110106ceebf2f.nq.gz
    ├── 49d27748b464de2b6063ce218afa0ec88f51f674.nq.gz
    ├── 4b13451952e338067ba7937da000d152c3d81f00.nq.gz
    ├── 4c588419e01bc4bc3d607fb2e00a8b9ab8a3e759.nq.gz
    ├── 4cb5aa04288b4066377b91232448321d0ce9cd38.nq.gz
    ├── 4d13fc60404b91e398a37200c4a77b645cfd9586.nq.gz
    ├── 4def62615f9dc601d841f134aa0e1596ad626e6c.nq.gz
    ├── 4fbe7c5cfd6d677cf966544094b6b759d0d80ecc.nq.gz
    ├── 500c736e529621d3e9c111cf83d721ff8efb9957.nq.gz
    ├── 50ca5e52d7dfa6341426df421c01d604b47199a1.nq.gz
    ├── 51948e6660e2ebea4f58fd226737b8212dfefc69.nq.gz
    ├── 52405406ed07951ff2f16110451eeaccd1437d08.nq.gz
    ├── 5283bb79c360600b9f18b9cc4372c5717412fddd.nq.gz
    ├── 528abbbb879cffec78987838824be31903767f80.nq.gz
    ├── 52a07d6642619562e53bc30bfb8d934b42232f33.nq.gz
    ├── 52c0773359b5a2fb4cde62e83878bfa308bdee85.nq.gz
    ├── 52d6daf940ee1f9243eb57f66c04aece2cbeb798.nq.gz
    ├── 538a4b47768f903a6f2eed6fc69330512d536c51.nq.gz
    ├── 53d33868d86c742eab27744d47616d76ddd6e65f.nq.gz
    ├── 540fa5a624a98c2103d91caec49588d3ca8e9186.nq.gz
    ├── 551527d074549a209137b22416020546b1989f3f.nq.gz
    ├── 55575c3d305ff7869e0f2ac5df904814280c97c7.nq.gz
    ├── 5826756a2288c8b4040ac7701be0df48f9176d13.nq.gz
    ├── 585d618620e27187c809a0dc6c59f0ccdb40c09e.nq.gz
    ├── 58bcae613953a3a9c30f51d9d27a9672e661e34f.nq.gz
    ├── 59cf93242359cb4ef21917b001d9f98d2de975af.nq.gz
    ├── 5c251d84fb484343b959614c0cd2c42a1f329ed2.nq.gz
    ├── 5c53346f4896f937940cd010d3f5b55cceea5046.nq.gz
    ├── 5cb698d5481e2c927617a541814f02b281bec670.nq.gz
    ├── 5d0ba6f5b319d2ad83fa27b371237dcd0647d6d0.nq.gz
    ├── 5d1ec737898f442488f7fe4d45bbbcb81d863b4a.nq.gz
    ├── 5d2b72dd900dcf30302c115e806e0defd53f4bf1.nq.gz
    ├── 5d3522c1b7b9dd6caf294a2f136eee1111588d0a.nq.gz
    ├── 5e2a839f69e469460e86a4792e564c1a74505037.nq.gz
    ├── 5e7c9e6d509f818821f82fc26adecb98824583cf.nq.gz
    ├── 5ed8af993f925c72a40ccab02b79045c749af927.nq.gz
    ├── 5f775f604e7aa2bbfa996c9d62cbd2d52d93c910.nq.gz
    ├── 5fc918354dcc7434bd8ec4818b2b454b6e47b0fb.nq.gz
    ├── 60e2dd3050d5dd6a8fb1698450f023263ec81997.nq.gz
    ├── 60e7bcae7d0bc712948802d2ebbe9aff67ddb129.nq.gz
    ├── 60e951f5565089af801a9c6f2a8e27ea6a61bc71.nq.gz
    └── 61008bcee1acd117f28f238424f6a2cd5bf3271f.nq.gz

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

[argilla-io/distilabel](https://github.com/argilla-io/distilabel)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
