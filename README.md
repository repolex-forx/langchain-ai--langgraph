# Repolex Knowledge Graph of langchain-ai/langgraph

RDF knowledge graph data for [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph), parsed by [repolex](https://repolex.ai).

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
rlex download langchain-ai/langgraph
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 41c9c22fdc83d68a2859d0c9a2b627c8615a792f
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── 41c9c22fdc83d68a2859d0c9a2b627c8615a792f
│           └── chunk-001.nq.gz
└── blob
    ├── 0202a1400114cdc4c2e708f1ef7b4e71ccbe9f8c.nq.gz
    ├── 03493ab5a846fbdd5341831b7fb0fea70bf8fad6.nq.gz
    ├── 041b130c177dcd4cd126840ab046ea331696b0c8.nq.gz
    ├── 04704c0fbc9331be00dde622390e3f12a63aa871.nq.gz
    ├── 048d118828b9cee3c47863d47b7edf795113dacb.nq.gz
    ├── 04b0c94d415b6a6e0aa7055fac0dc5919c5251c3.nq.gz
    ├── 04e3984aeceaf136a7d9c222970d02387a8e57c2.nq.gz
    ├── 05bbb3ac52c8c3544ae0f66c9b67e82a7d7d4538.nq.gz
    ├── 061166ee13af4aeb3cf95a4e34551a6599412900.nq.gz
    ├── 06f64bc7d1275fe4a6097c7c098649f40323b0c0.nq.gz
    ├── 0720039fc32188cd2ef5e17877d99a659dd49c00.nq.gz
    ├── 073b1380a249c620c5e788dda25bb321a484e60d.nq.gz
    ├── 0832ff61edb5e7b9b8096c3f5d565d70125d0cc4.nq.gz
    ├── 08acf1f2a34b783b0243529d43f9345dd719d49c.nq.gz
    ├── 092324e721d4717bdc35bc843ee0c317aabaf19c.nq.gz
    ├── 097e4355d5e96507c2c79008772163a749286af4.nq.gz
    ├── 0b289636ba7d72497a6ab7f7da66ccdd6e92a9f8.nq.gz
    ├── 0bf988173212f86b4961f7a7df97a7ee3924650e.nq.gz
    ├── 0d879526272880963cf851928e5d718dfe1f6a5f.nq.gz
    ├── 0dae6a5ffafdc2e44d316e0122beb28d6af1950a.nq.gz
    ├── 0dbce5c72062cb9a78f5a3c71fe2b56abfab4ce4.nq.gz
    ├── 0e57ba27f1b2e8f7fe438187c5656fc6114f160c.nq.gz
    ├── 0f0fd5ce6df87845bcb4faa789ea89571cba66d4.nq.gz
    ├── 0fb8bf468b347c2a8d61264de7de119d6fd53a54.nq.gz
    ├── 1064934f29da793430b7c2d111a5215c810dd3d3.nq.gz
    ├── 108588d0b8276d0b818d53cd908d0563e7181035.nq.gz
    ├── 109a57c63980c1fd043ce1619bf261d7da1a80e5.nq.gz
    ├── 11ff43527d9b6e849776c6ad2acad50d029a9cfd.nq.gz
    ├── 12e7b3d97c4b2442580d8b4286d5256b9213ba22.nq.gz
    ├── 132fa2e5460fb536053127e3e08432f2d22bf3c0.nq.gz
    ├── 13741777da57b21216fcfa76d35e098e6e5126e8.nq.gz
    ├── 13b202aaa6a620a48779685e484ec12c4f88cc5b.nq.gz
    ├── 13f922534ae4498f6ad59263ec7b6c12d1e5d18e.nq.gz
    ├── 14b12f13e351a1964901d895e60696f8429100de.nq.gz
    ├── 1510ed38b03c7aa1b41d6c2eb52e79382aac46f1.nq.gz
    ├── 15bfa54afd3e9b13aa8d9696cf7bdc7c6bff1530.nq.gz
    ├── 167692fa3019be9b4f3ebb26d0f7af96cb6f1d12.nq.gz
    ├── 16bf0e4ffd13a100a8141ed0f050c10021380704.nq.gz
    ├── 186e162fa76eb9cbabca88419673996a07453b28.nq.gz
    ├── 187abd21f71cc13c4c7a250226503d0c1ba52ea0.nq.gz
    ├── 18862fd28dddc6af1b30acbb3184bbcf6da671ae.nq.gz
    ├── 19854d1c814ba83a9236aef6816645ccc17e2e85.nq.gz
    ├── 19b41148038c5df1ca5b1e317434be6c2e427062.nq.gz
    ├── 1a5188f1fd9da8e80b8d090454883885ca3aa466.nq.gz
    ├── 1b8d7a7ef6aa447a8e8ea5234c32ca0a772ba4f7.nq.gz
    ├── 1bb2ec08e95a6c0b150c9a7ad6b44d127e3e57a5.nq.gz
    ├── 1da2ca701c0809bdd63b81065b0d2ec248b9300a.nq.gz
    ├── 1da8ce0d751faec1f8e60b6208bc552502d1cbf7.nq.gz
    ├── 1db8ccd1c3d8472684632d49a527de093b42d41d.nq.gz
    ├── 1e08269bd4eca18d79d723cba83bc90131fbb2df.nq.gz
    ├── 1e4066c4cf03312760a32730310829033b917c12.nq.gz
    ├── 1e6af158ab5917d0575d63f2288d5fed0f179335.nq.gz
    ├── 1ed453a371ba5c23ea9e365f9a6984d6aec0a13e.nq.gz
    ├── 1eed9498d1f5457759fd225d9fec41a568af75cd.nq.gz
    ├── 1ef2a97fd8ce1b0a1ad140d9b438e62ec62ee70e.nq.gz
    ├── 1f048d47ea86325194a8e3e687242c8b452cc6fe.nq.gz
    ├── 1f381d1b129b523afeec2434dc90ad4ca76ab28e.nq.gz
    ├── 1f8cbe51f43d7e8490342d01a7a6296143f5353b.nq.gz
    ├── 20c694223ad58db48feecc044599fc94409923f5.nq.gz
    ├── 214a4919897be0fdd71074ed16428ee82221398a.nq.gz
    ├── 221b35dafe48b4e1fa1cb714f5571dd3d8b6230f.nq.gz
    ├── 226eacc39bd0fe40aa43954f6adc39793135b54f.nq.gz
    ├── 2325a2198eae07a14a7d5ec2a48582ff69e5dd29.nq.gz
    ├── 23636b9ff39d1138fbb6edd82f70e473ca480938.nq.gz
    ├── 2387eb3c0b05125e081c477711b6166543264b7a.nq.gz
    ├── 23da8ca57d08229dadaa3d8ed0da723d12123441.nq.gz
    ├── 24bf823182cdf049a37453b2e6efed9c33d960b4.nq.gz
    ├── 268914f5142ab066e2fe08a75c74082dfaf48022.nq.gz
    ├── 280aac8df9e7e7daa58afac712738188dbb17984.nq.gz
    ├── 28990d51c1490354b427114e011813bda422c87a.nq.gz
    ├── 28d43a790517efdfe02d67773b1cc0f2de110a9f.nq.gz
    ├── 2a2649a46ec48a8f27ac162a088c51097d238556.nq.gz
    ├── 2a3f2a52c57e64896b1953f66cf28b8736d743a3.nq.gz
    ├── 2a9d52aae4b11b534e3539d09133fead05aa448d.nq.gz
    ├── 2c36ae3c725c801c462b19b1d9baf57ed1cb2096.nq.gz
    ├── 2cb244958b43e36949bb4ec349544c9b3adb8f5e.nq.gz
    ├── 2d50f323b2703f9747a7450d07f6eac868c665fd.nq.gz
    ├── 2d91eb5889e1e3466ee77daa2a9639f085a6f6a6.nq.gz
    ├── 2daca3f6c73750bb782f0d59bddd757771d7bcab.nq.gz
    ├── 2e0b58dbaa3f0ce29115a13f0166598b03f06ba5.nq.gz
    ├── 2e2857ae3e667da3f20e9b74c9473094821d9efc.nq.gz
    ├── 2e6cd1ef5c6005072969813f9ffc07ec1044c65b.nq.gz
    ├── 2e71cdc23604618ae999e82ee1a796b78543ddc4.nq.gz
    ├── 2e8a3bede803b766ca16a5aba54f39ab6c4358ce.nq.gz
    ├── 2f294544998ed584a4e5b3b14670c950964f4a2e.nq.gz
    ├── 2f3d7ed8ce1596fd437eb1c1581a6cf3093dda23.nq.gz
    ├── 2f45d59cbe20067797049920cb010af26dded9ef.nq.gz
    ├── 2f737bf7a999e9cb13c8c927be5acdaceed0635c.nq.gz
    ├── 2fb2dba5564294a54fca98d244f4418e848520ca.nq.gz
    ├── 30443b7732656e5f35c88a34a10537bd21ab88d0.nq.gz
    ├── 304ed4726d306b5744ec9fbc8fbba6ec582dc89a.nq.gz
    ├── 30ce9f1e07220ce7ae6a8881f398e09fa5cdf812.nq.gz
    ├── 319411a4c2eae1a6facc7d6c035319f55f6786a5.nq.gz
    ├── 32c3d3470e8f72d6375cf4bca5bf2625f0213429.nq.gz
    ├── 33319d0ee2598ca2cad9b0f59e05404ad9b532ad.nq.gz
    ├── 334c852b12c7d8558282d923ebf0c92c21597524.nq.gz
    ├── 34e8040beae3e409c330d054e4f522a57a6dffe1.nq.gz
    ├── 35b359094fdc10e6f2376876ea5fe32022b8471e.nq.gz
    ├── 36d3294075c96837a6706a8b1225a513868e50fb.nq.gz
    ├── 37133980f1f4646459f9111fe82ee0a3fa0fa079.nq.gz
    ├── 377b261e7e6206ea8ab7a885597f8249f2c91e3d.nq.gz
    ├── 37e605ceef4e514597478c27e74de5a84965fb79.nq.gz
    ├── 37ed1b8e8cbc4810edfdaad383bae677d06a7a87.nq.gz
    ├── 38e1a47373fc4ad457d076f12b0b10eb515b3a28.nq.gz
    ├── 391284d200739505cced687c6c06ed585f5d2ff8.nq.gz
    ├── 395a6f6984d98457244fcb720385c9ad4d5a40be.nq.gz
    ├── 39a077631d6faf60c5030631ce5c567f1a94f0ef.nq.gz
    ├── 39a36df68787da3cf33bbfd8a9ca8ab8b14874a2.nq.gz
    ├── 39ee31c758966665024ed1e9bcfba8e01a4a290c.nq.gz
    ├── 3a3b8b6b0cf6c9f72f5d9a1009edda7dd9a7f535.nq.gz
    ├── 3ab705dd4b1671116f8eddd459533b052ed63ae5.nq.gz
    ├── 3b0c4c9d9c3dff409d4e76e93c4cf81ee9d03a2a.nq.gz
    ├── 3c05dbda70ed04f1038268a201000d5141535832.nq.gz
    ├── 3c602c4137f37441134ec39e00a71967ef71d2e5.nq.gz
    ├── 3c9afee5b520e9c8de6f3c5c98519632cda286b0.nq.gz
    ├── 3d1e20ad24364953ba0a0baafe93d249b8c89032.nq.gz
    ├── 3d3878d9f6b8fc816cd2999231f91e8e88dcd757.nq.gz
    ├── 3da5c9484e59069eb1f4764110543b5d4001076b.nq.gz
    ├── 3e1263426389794b1b98a1d00427c507ca3f9a91.nq.gz
    ├── 3e8ede178aa51a151f803b166814c53b04b868cc.nq.gz
    ├── 3ec8f0908ec9348fb4670abaf216e308df534b9e.nq.gz
    ├── 3f498c6db45211c97fd0bd528d5cf07d20150914.nq.gz
    ├── 3f5ca1e40f41fb8c89e98d33e69825d42f6a1177.nq.gz
    ├── 3fa5e61d2a0f822aa13a7c30482156de57db975e.nq.gz
    ├── 41ae6b7d23d82283103831e2067aa419c7187d37.nq.gz
    ├── 42562133a1b95af7f833ed1ee052f81e35647d55.nq.gz
    ├── 4278b9af591de4609d019334dbe1c9a63e373a06.nq.gz
    ├── 43475d21a5b3d98c8ba1a42642a2b32fc844a468.nq.gz
    ├── 43f3424857aa804a1bb5f6d1b525fb3045fae213.nq.gz
    ├── 449e1180d3c5f3ca8d957749f771d8c5966494a3.nq.gz
    ├── 44b79ce8e420bbe9d8af49abdc5534265fa8bb28.nq.gz
    ├── 456241384385a9be979fbef7bf5ee12ed68ae5d1.nq.gz
    ├── 458b32c6a3715a6df0966e694b1c9135089fbeb2.nq.gz
    ├── 45959bf46dc2b3d9c5f84f8694c2775ed25779c2.nq.gz
    ├── 464edb80db60f4005380629add778fa1abc8c9ae.nq.gz
    ├── 46f92eb5b2c43e078b9df96459f3509e4c1f68cc.nq.gz
    ├── 47c0f043fd0a8cb08ea92d438c299eb20c4c1282.nq.gz
    ├── 47ee1c538e3fe0903d90b9a638b8a99d0a077e10.nq.gz
    ├── 4801c7c0bca8e486f47784cd92ce5c65db9e53df.nq.gz
    ├── 481395dd92643aed7ab69d39e7548140a949410d.nq.gz
    ├── 491d0d301c3c06f81e743da13c13f6dc119c3fc7.nq.gz
    ├── 49aa33e23b5db007573937e1dbf0130cde5b52d3.nq.gz
    ├── 4ac3b7482933fa1f7458428887f88ac2da028424.nq.gz
    ├── 4ae8c2445e161fd29349dbbf59d16cbafc63d88a.nq.gz
    ├── 4b5468e260445210a764e1206b6a58fbbce8dde9.nq.gz
    ├── 4c40356d76c06b4c880f5ea0a3a7352c46dc4905.nq.gz
    ├── 4cb2676a90dcff0d13f25c4f811b91051f8065d8.nq.gz
    ├── 4f17d7c9e8152c9bbe7b779f404ad2f7701101dd.nq.gz
    ├── 4f3d21538f25c8e87ab4ef0c4c233ecd74f4974e.nq.gz
    ├── 4ff42b6f9e4ecc801f85f06c919e6b76080f2a1f.nq.gz
    ├── 50cc0a3cec3ca3081ac951755afbafe861298117.nq.gz
    ├── 5130cd4c4f9e25ed09027c334ab4c4b52201f5f2.nq.gz
    ├── 51d5cc3b1c2ca4b1f504ee51d8c101bc82ba4b11.nq.gz
    ├── 5265d22b339674168372bffb013491ea5a779b15.nq.gz
    ├── 53e29a1f9d112b086caa80cb5493dca73a02cc3d.nq.gz
    ├── 546a417708eb87c8b4eedc4a7cb3c1db9bbbbe8f.nq.gz
    ├── 55e25f72b072c359a4811d0770548cac2b3a7142.nq.gz
    ├── 574f0640321e25a2ec641fe81b85e61db9746cc3.nq.gz
    ├── 5783ce0c2365d7063cec3d2bf9fdfaefc557575b.nq.gz
    ├── 57d8543a2ecb2fd827a3cea72fb3bce6ded5ce54.nq.gz
    ├── 58b77eaeb8026c1e0678c93b4e02a06e97496b74.nq.gz
    ├── 5b3753fa816a893617e9f67d1232a5e19c344bac.nq.gz
    ├── 5b7e52aae2d7c1c0824a475f71b9a45e985f254d.nq.gz
    ├── 5c0989516777edd6bc7a9cae1c96309081fe7568.nq.gz
    ├── 5c562ac1015ff274599eb051d4b61d9190e9ba09.nq.gz
    ├── 5d0a88e41fa10e8708ec565a74d20de4ef4bc0dd.nq.gz
    ├── 5d831a07141ba5a5b5496f3104d3e52326719832.nq.gz
    ├── 5da546297fd171ec5812d58c76932a922e3d7366.nq.gz
    ├── 5dc6d73a431e2191a251939f2270fba50e29dc0f.nq.gz
    ├── 5e5f0c00bf74a0b6997f94e4772fba25408bfd3f.nq.gz
    ├── 5e9c26394a7432bf1d8e8ace6df5749b1f37ab66.nq.gz
    ├── 5f807ddaae3e4148ebad3085a4372556d3fed53b.nq.gz
    ├── 5fabbe952fd0ad751a469abc30fa7c53827dd202.nq.gz
    ├── 62617ff1c8c9768723e3da6222e0b76675e6c566.nq.gz
    ├── 62e18c1a953ca1a577dec15c8691b8ab9a2c0bcf.nq.gz
    ├── 638e0dd722ef4a71978e493e04def0291c866253.nq.gz
    ├── 63b93715f23f36e529545057dcc3f0cb2b2033c9.nq.gz
    ├── 63fea05d0fe6e1ff715a6d3a79503b041c42ff97.nq.gz
    ├── 64604e093418715c161d9bfe14447a7c516e1e14.nq.gz
    ├── 649f8b9fd79ad26bd6befc988a940d2af93da3d9.nq.gz
    ├── 64b842634af5e1e60fb2e2c36ef29730d4f1d58c.nq.gz
    ├── 651b5d3c6ad741e7edee703a2179ba6332bc9f19.nq.gz
    ├── 654f6d3ab7ebb595fd2d147285d0c6af412ab6c6.nq.gz
    ├── 674c96f76b3d0f677d53dd8354ffe8031f3cb9bf.nq.gz
    ├── 6799d86bdaa1f697c9464304a75001088a83de13.nq.gz
    ├── 699b552c9b5674854147d140605a4c7c399c4e99.nq.gz
    ├── 69cc05171a1da1bee1bd3271fd19ae073803103e.nq.gz
    ├── 6a9adee68f14318b3ca64f5474c50fb589d6f93f.nq.gz
    ├── 6aac18d6162e9f516e3f66113ce064f5da698b9a.nq.gz
    ├── 6ac8a392a20cc5d17b3fa7daa4b04d26afc4a19d.nq.gz
    ├── 6b368232b95e753c9a53db28913f3d0f74ac67fb.nq.gz
    ├── 6bdeff0e1c49e9e96d356ce2c9ccdd27f1ed676b.nq.gz
    ├── 6c4068a2ff2d860f617617e9a552b701b15e239b.nq.gz
    ├── 6d3a7b92b8160d69fe7b80249fd733c73212810f.nq.gz
    ├── 6d4b20b1ea332fe9979138adc96b90b6050309b7.nq.gz
    ├── 6e01dfb39bef733daa69de8419527b03682a984f.nq.gz
    └── 6e0b37e860a2b94955a59e9048aab25bd89e2d37.nq.gz

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

[langchain-ai/langgraph](https://github.com/langchain-ai/langgraph)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
