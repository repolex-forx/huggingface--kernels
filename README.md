# Repolex Knowledge Graph of huggingface/kernels

RDF knowledge graph data for [huggingface/kernels](https://github.com/huggingface/kernels), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/kernels
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 32b3dc8cea813b011885fa656121fe8d9c8415ea
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 32b3dc8cea813b011885fa656121fe8d9c8415ea
│           └── chunk-001.nq.gz
└── blob
    ├── 00ea842a086097797c33f547e209dcc476db17f6.nq.gz
    ├── 010f917651320afb6df3ebfece3f07d892f89fc0.nq.gz
    ├── 026c2687e29635f23d4e40ccfcdc61a81b4e21b6.nq.gz
    ├── 02aa932facf11bf4d8affb056d554bcafe3004f0.nq.gz
    ├── 038c60a7be089ec31775bc48de10cab458792102.nq.gz
    ├── 04360cbd466950ea8ee8c867baf7a6f85cf773bb.nq.gz
    ├── 04d986c06c1abc5017fbee16c9a68eaed8bdf976.nq.gz
    ├── 04db9f4fe521013d5a2b75f68d08b16c9b609886.nq.gz
    ├── 05341ae03a78fbda156060c2e08658b1d1f8c028.nq.gz
    ├── 061ccd5cec1bbc6768c618df78bd3e878a584081.nq.gz
    ├── 069adaa0b33c43aaab0fe778769a5c5bc72588f8.nq.gz
    ├── 06f6bb7d75e76ab58dcc4c612d436c61709c3c59.nq.gz
    ├── 0779aed8bd89eefefdda41e249d289d4f64471fc.nq.gz
    ├── 07c475e374f0c0cc4bd0f89f6c9195a16f2ad88e.nq.gz
    ├── 07d6f55e199192a2d853cfb65466f2e2626efbec.nq.gz
    ├── 087f0c615c74bff22fcb9369d1f0d07b2778c53b.nq.gz
    ├── 08c23ee484749cde30a03a7ad9d403fe93e23f23.nq.gz
    ├── 096a74a659ea74510bac08df5be9d9a8c88667fa.nq.gz
    ├── 096da4beb07b3f085295b6c9c87aed07b057ffa1.nq.gz
    ├── 09c3929cf77a77e14f632c7347a1297036e3641e.nq.gz
    ├── 09d56ec976ade3637713d88c5c03e4f2bac55ce2.nq.gz
    ├── 0a1abf557b108a07d675b9b6be98dcd839b1be8b.nq.gz
    ├── 0a68a85cd015bb011cdb9a24c00695f1834476a7.nq.gz
    ├── 0b3ab38aedb9b9e971ba7bd7da0035bb4dfdd7f4.nq.gz
    ├── 0b7f70cf7e987fd968339998136af5d2faa182bc.nq.gz
    ├── 0bb300c381507f43ab46976699edb243fa11731a.nq.gz
    ├── 0bbfeedc007d5b70548061055698de9d062a1660.nq.gz
    ├── 0bc73a59f6d4121e093b6e0e802cf0351a1b937a.nq.gz
    ├── 0bd4851c92b84c38cdc1c128454382eb65dfe2f3.nq.gz
    ├── 0be0bea617802aeeb939d59ef8165eaa0d5dffb6.nq.gz
    ├── 0c5e08d142e47bf0d9b6ab3a382f292a7e173daf.nq.gz
    ├── 0cb2dac31c4b8d0b12a93340638d6c10f755716c.nq.gz
    ├── 0cbb68af0f897d7a96092c462122bae7c2cb6bb6.nq.gz
    ├── 0d39119c83d882b6552bb409bdfb603353b92738.nq.gz
    ├── 0dd3b062f73fad3312f8a6a7844ba5f1c3465c0c.nq.gz
    ├── 0e680b25de9cbb7997ff0bdde9b91b5eada6f9e0.nq.gz
    ├── 1017f06bfbdf40f53eb616a8a4bc6a6cce59d91d.nq.gz
    ├── 102e708c44c9f9b1c837577cb93538b80b83630c.nq.gz
    ├── 103c610f4a529f98b5ec95433ca279a21e85720a.nq.gz
    ├── 10493fce9ed45e3583e2b53f0e2497bcc4567a56.nq.gz
    ├── 107e2482db3faf4b06ab672dc58ed939e71ed2f8.nq.gz
    ├── 108df13f2c743b4c125d6073a8d8fc5b8181b2e8.nq.gz
    ├── 10d45a1355abb9a67b827c2182af2ff3d4939f41.nq.gz
    ├── 1217138f2228d34cda915e712dbc98a504cdf4b1.nq.gz
    ├── 1238e24ef9b9e5f7bbe0ad090f736058e12a0aa3.nq.gz
    ├── 1247f5b56f0a709dd6c8561269efa36f637972b8.nq.gz
    ├── 1289312c75dac391108824bb71eb669f7eac2080.nq.gz
    ├── 12ece274d433377c0d8d544a4f32bb12575d4f21.nq.gz
    ├── 135d3a91d0cef3b96ebe53986c15878ab7c4b69e.nq.gz
    ├── 13e9ca0103b2d68959f04c8648becd39704c5e1d.nq.gz
    ├── 143de315d31d300ad801e7da45f0fea367557e8b.nq.gz
    ├── 145b069a76ce460fff32aeaffbeef26fabee0fcb.nq.gz
    ├── 1502b2e278639a203c488d9a3fbd5520ab4b55af.nq.gz
    ├── 16182f4a4a1e3b6eb327c5ac16089482da4400c9.nq.gz
    ├── 165c80aa5c8aa12231354eef3b2322b4d42d464f.nq.gz
    ├── 1765d92d91f636013b03b75a0612f88c242e0f9c.nq.gz
    ├── 1809de08104bf7ef849e6cec202163412ef6600d.nq.gz
    ├── 198ea0bf3b503b29e55a5e444b0137b84a6b5a64.nq.gz
    ├── 19f8bfc7cce8175619fbef245da815a0e93976f2.nq.gz
    ├── 1b3576d99c50c778d47ebc78fb73ebd467acdee4.nq.gz
    ├── 1b5a77f5e456df9abb473d0ec202e91fb0a65037.nq.gz
    ├── 1bdf2e83e0d889fb89086d4c1ddb5109fc8d1cfa.nq.gz
    ├── 1c04071ccd6b04021ca56516573f8b25682716eb.nq.gz
    ├── 1cdf363acdec473a6a14bedddf44bbdfbf50b46d.nq.gz
    ├── 1d976a357629ddff8747d676131cd2fc52b7e434.nq.gz
    ├── 1de4acd06326d59f89c127da8021c41f223bb7f2.nq.gz
    ├── 1e24de4707db185be90dc9dbe85b66cb2f93b06c.nq.gz
    ├── 1eab4424b0d3156e535afabd98cc05db6c2103b3.nq.gz
    ├── 1eedff7e87df98331848c76984a59306f8240ed1.nq.gz
    ├── 1eff203adcfc208a8b9964bd3c564d770234c2e6.nq.gz
    ├── 1f6d227c6601be8f8ec0411c48f9bf6b34b5576c.nq.gz
    ├── 21123270fd4722021f7d553c8c640744ded2650b.nq.gz
    ├── 218410fdeb2ecbff53b1a1b2e32cd357df18ecbc.nq.gz
    ├── 23328ea97dc44bc884732caf770655374a0bf9d9.nq.gz
    ├── 2393da6f7d4ec51943635735e22b5838526b3321.nq.gz
    ├── 23fc3931d4438242c4faef7f4c707656e0035b3d.nq.gz
    ├── 2495ee6ca573e2aa96c1f8755cde41bc048ab663.nq.gz
    ├── 2577dd43c0f92aa9d8e27a2f2220b0d040e4bf2d.nq.gz
    ├── 2713fd363a780edf689ef51c17e4eb55eb7bf76a.nq.gz
    ├── 2764f02b9604a9aa0ca306705b803f3bbac3c82d.nq.gz
    ├── 280345d0562c223403a021f4a2f56db476fb7626.nq.gz
    ├── 2824b98a046e41fc6d75828111fbbf6e3044dd92.nq.gz
    ├── 284d81ce889fb179307387554e6cd7c549853c3d.nq.gz
    ├── 2868c79f57d7e4d43030dbafde34aee591d92e7e.nq.gz
    ├── 291603471774ca5a120364e20c5190d3786f55ac.nq.gz
    ├── 29c0cc8f89ffbdad7aa1e98cac6d8b658feefbac.nq.gz
    ├── 2a79439e2d2a8f900beb2ca120e71fd913d1916a.nq.gz
    ├── 2d734e2cfa29fbcad3a3fa5a081c3d170693a8fb.nq.gz
    ├── 2edfc477953853b9b968ac5d6393e4b8a5e59183.nq.gz
    ├── 2eec66c9ef36a0cbc6ee55d69d9f3094f0eecac7.nq.gz
    ├── 2fb2336c1bf054669bc66828f13c721b1a7a7a33.nq.gz
    ├── 301073dde3ba7caace8f3dccc6ed702c3d9b2187.nq.gz
    ├── 3053f556cd81173d8783b77d16da51489d07c65b.nq.gz
    ├── 323a2bde58abcf8fc0e4d5f21f8f932daedadec5.nq.gz
    ├── 3349449d9163449cc78929a0427651c13f05535c.nq.gz
    ├── 33ef241e2be11cb99107a06bd955d78500e7b64c.nq.gz
    ├── 341021b8ddba3c8c96efd48f86068c7c8900f847.nq.gz
    ├── 3427ee191f6e37c41baf8224497fe9d6fd1cc0fa.nq.gz
    ├── 349bdc195c001e6d0d5b6c5a9198c1d3e2e3fe91.nq.gz
    ├── 352f0a093dba9cb81bf05544fab8c81316eacf5e.nq.gz
    ├── 35ae5c18c936c88518283ef3ff72b4b4931ef735.nq.gz
    ├── 363918f6cab20b89499691a1d1245140c29e66e9.nq.gz
    ├── 366a2e2c8e2ce0b56580c42c3c8f520a11264f2f.nq.gz
    ├── 37f1b4a382438285cae64076f200850e5fa339a5.nq.gz
    ├── 38392aae3ae383d818c8499d15d90b8c0ff9da5a.nq.gz
    ├── 38d8a38ab535444ed9dbb317be2eac157f178cc1.nq.gz
    ├── 39445964a912f1b9691bc425431cb77617fe14b6.nq.gz
    ├── 395fc705825a9e69803896f947e027c929d46e4b.nq.gz
    ├── 39d1b804186c73407df42aa1cafffc3aa79bb6b1.nq.gz
    ├── 39ee33c0d1231ecfeeea6b0570bfe5d702a0e64f.nq.gz
    ├── 3b0453ce2cf9692eaa12123f149702e33d198e18.nq.gz
    ├── 3b5d577f164f2eec950b1064e8bd136265ac5afd.nq.gz
    ├── 3b708ec30aaa5fdda88b6714110a01a5d62c1926.nq.gz
    ├── 3bcf290482ad4adcac67efa739b2ee100baa7a10.nq.gz
    ├── 3be30957312e5fcfb995c83203fb87ef554b6090.nq.gz
    ├── 3be48ef45c97ae123111d8dfe1fde2e0a9a473f6.nq.gz
    ├── 3c9ac203ee7c192801c801f55198ea923be065bd.nq.gz
    ├── 3da858adcef39ec4be64c476c72a18514d057a0f.nq.gz
    ├── 3ddd12fa9bf6e1cb8057c67720855f2a212d2244.nq.gz
    ├── 3e645f24f704c50f1d2df8c691e4ab4af80a4814.nq.gz
    ├── 3eb2374da182db4c236e9a3c70e1c3fe9b6c2dc5.nq.gz
    ├── 3fcfbf4669e1312898579f8f8d001349f846df73.nq.gz
    ├── 401764af08cf275e8257babf9a4a9d38ce1d9315.nq.gz
    ├── 40d80efd6d5f172fbd58a2e0bf2fcf7452eaa4b5.nq.gz
    ├── 41e51eef7f8d944bca93bc39732c7b18c39d92cd.nq.gz
    ├── 42d32063caaa28ac6fc8ff806d08edd0a7836c8b.nq.gz
    ├── 42fce6c3bde6df40099eaf9365c6c9a1ce476fd6.nq.gz
    ├── 4315aefd50efd44cbd4f6fe746be4c5349ec5c0c.nq.gz
    ├── 43a3f143657048fc2b780b7cf7b9eca43b785e18.nq.gz
    ├── 43ede2e9f95391c2f9c9d85fc714e13771c655b8.nq.gz
    ├── 4432ad20c13efc1a7eabbfa323681a5b9de8080b.nq.gz
    ├── 4555285427b347510bd892b284d46720e7bf64fb.nq.gz
    ├── 4614271136d2c203537dd49078f3f677649a464c.nq.gz
    ├── 46d32cd92a6461ec9776697c70ca8c7083c8bc0d.nq.gz
    ├── 475d8c9804a959838a9c67efbf6a3d954f8c3380.nq.gz
    ├── 47b6a180eacbb9d9ed1e934446471f9a7eb0fe4d.nq.gz
    ├── 4825ea283c539f6beb18e11fe96f062f11c8ea07.nq.gz
    ├── 4842d19ff7e285038ba3975536f6f739ff00e374.nq.gz
    ├── 494897bcfed010a92084b7dcbaa98e7de03f9071.nq.gz
    ├── 4a40cfc0db924e2fcb22efa1f2b594af5e6169f5.nq.gz
    ├── 4b31d7522ae3b1d3d7d383f35d33112c9152dd0f.nq.gz
    ├── 4bf46d0769c453308d3dbfc7eab1bb51af041484.nq.gz
    ├── 4c5c8faec74b09d31ce3ffe0c88cdc0161e36329.nq.gz
    ├── 4d322102adc5d72d3d58ba7b31ea19b879d653e4.nq.gz
    ├── 4e3b59782a02ba7899f9f4a059df95977abe9034.nq.gz
    ├── 4f6cf449fcbb5b48aa831f96f07c7fd6ea1dbe2b.nq.gz
    ├── 4f75d886ee3ae9cb9da1850c36c1cd6c3ebec3bb.nq.gz
    ├── 50a376e76aef22f35699f3ccd544ef73bde2f001.nq.gz
    ├── 50b49f916f95c5e777cfdd26cdf99bd3fa9fdd79.nq.gz
    ├── 510410768aba88c1e6110cd951a0fc8992bb183d.nq.gz
    ├── 51146a5c945d785cc6420b7cd6f645849cd38ae3.nq.gz
    ├── 517e7b2f7e64442e9feda36d3a404251a3c5dbad.nq.gz
    ├── 5186df0f7d142cca6b79c631db0958d483ad6723.nq.gz
    ├── 522ab1344bbe33e3aefd4eaa39f8266ba1ff4789.nq.gz
    ├── 52344bb9dda4a9ef1f17c1bd029c1261f117cb8d.nq.gz
    ├── 52488a03733855c0956229a15650ca9fe5244e51.nq.gz
    ├── 52d4538663f06beebaba0e8b3501b7af8f8360de.nq.gz
    ├── 530763bf3ad0a7079b32b66c0a106bcc5e543c1e.nq.gz
    ├── 53424c8a8054e3f5b9eed0ca6e8e360c5f7f022f.nq.gz
    ├── 539b18d319c8e970e55e059c4aec40bc2a5b86ae.nq.gz
    ├── 5461e670c0c31112680845cede2eacc8cbfcbc95.nq.gz
    ├── 546a4a786d3a1385ef5dfc274abb467f0c4be582.nq.gz
    ├── 553d4c37afc5d46ee9b08a170deac09f2f049254.nq.gz
    ├── 55e7df5cbab4d492b4d630cf4a55f70115e1d66b.nq.gz
    ├── 563347c1cc78be01fedafa759048f2091587dac6.nq.gz
    ├── 566679383ff9155371e51618a622ea2b8f808fe6.nq.gz
    ├── 57650aa61b24bfe4a6ea61eb1303640d21a52d79.nq.gz
    ├── 57d2fc52b61a0643e9d760f2a67fd3068b12d99b.nq.gz
    ├── 59d4064715b89e19998aa9a5f039167ebef7994c.nq.gz
    ├── 5b29d22d1003e624a75f8bccf12f3fc89bb5ac1f.nq.gz
    ├── 5b6e7c7abd523eeab1d72b683619f8b632614c6e.nq.gz
    ├── 5bcc0f9cb601429100fd022461dd6506ae69e11b.nq.gz
    ├── 5bdb9243f8b520dece98e8e5ef6c89b9391aed09.nq.gz
    ├── 5c1590f1821f23de534ad20cce43cf39efee82ab.nq.gz
    ├── 5cc6191350800948c0774588d30657c46665926c.nq.gz
    ├── 5e487141deef2d1ef7d592ca9a8de6675d615324.nq.gz
    ├── 5f1362bde706750a83cbf6cc77b6ab4a636761c2.nq.gz
    ├── 5f1799c4a8823090d4960f8252b2c1a62e5647c3.nq.gz
    ├── 601b5d3f5bdaed6fb9dc07b44fbc742653e085b2.nq.gz
    ├── 6032aaac3a5467217e8d6bd39dc182759d28c3b9.nq.gz
    ├── 61946af0189b59c879dafbf6908349c3ad29a0ef.nq.gz
    ├── 61ce72498c14b42fce2b68bfc5fcdd6abd9ea38d.nq.gz
    ├── 6228121c95d1c36b88f6d2d7434eb4e69d40ce41.nq.gz
    ├── 62ae896cfbf135fa7e19657fc469e127cbb47444.nq.gz
    ├── 62f849951ba1530b717f82953b5dd99ab9698763.nq.gz
    ├── 62fb894a24bb3ce2f3441eff513423309e8239c0.nq.gz
    ├── 63241056ff7f98a4f079c8c616d48c73a47c9651.nq.gz
    ├── 64261056f0559ec99ccbbcca57e0b9611b26f2c3.nq.gz
    ├── 64571b7ec186748c98dddf287031ec594d0478a5.nq.gz
    ├── 65df993dd20be9977ae9c23109790cb8db951551.nq.gz
    ├── 65e7cef3b53721d85ecaaa92b1a86d29171802cf.nq.gz
    ├── 66541f500516aedcd40420afc4ab731807ce9a5f.nq.gz
    ├── 677bca5ff431398c3a250f3173cc40f43c21ba46.nq.gz
    ├── 679b28b7190b64da705f5c10b4725c0d6027996f.nq.gz
    ├── 67b315ab0ed6971bd93dc991bbb315a70809eb58.nq.gz
    ├── 67ba8a76fd83645ec19f5c265cf525c35e93c57b.nq.gz
    ├── 6890c993c08bdbf210569fc849eda3739bc02ff5.nq.gz
    └── 69af431a6f36d4a8777221aeb4ba3a92c611d519.nq.gz

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

[huggingface/kernels](https://github.com/huggingface/kernels)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
