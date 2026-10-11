# Repolex Knowledge Graph of jazzband/wagtailmenus

RDF knowledge graph data for [jazzband/wagtailmenus](https://github.com/jazzband/wagtailmenus), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/wagtailmenus
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 53e9003ff183a48d1ddb3dc79552a8db9b365f95
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 53e9003ff183a48d1ddb3dc79552a8db9b365f95
│           └── chunk-001.nq.gz
└── blob
    ├── 003ff51d6b4b9eb88f815b10f32d6a7107295c2e.nq.gz
    ├── 00a2edac8bc5124a48098c91a993ee2f7ad78b19.nq.gz
    ├── 025e940c9dd905fcb7a3e7cf81f2aa02bc3d6518.nq.gz
    ├── 026d4e871519e6d787e24abe054b3243046777e7.nq.gz
    ├── 03c0303ba3efd6a157a02c27fb04eb41dc60da5f.nq.gz
    ├── 07574196d68f50fb2c7454aa67c218eed66efe7b.nq.gz
    ├── 0876993f3ca35311f0c6fa23f05b7e9fb0a71bd4.nq.gz
    ├── 0902e423a38c84b541068136b5610f4d86ed5967.nq.gz
    ├── 0de64c64e1f6634008130b6ae19fefe52a2ed49d.nq.gz
    ├── 0e8fae15c7f034ade2afd3c4cb74275ef9309f51.nq.gz
    ├── 0f546351b3dc2cada0bd22ce8ee8e544204a3848.nq.gz
    ├── 1088e0a361a298c8ad13fccf23fad21defa6ca51.nq.gz
    ├── 12a1d1a4466e84c82626d27651bab57196da62af.nq.gz
    ├── 13d8a9c332be0e2928e2ff47b2ef2d76eeed57ff.nq.gz
    ├── 13e0404aa5db6f8fd61653b4b68c68718f444e8c.nq.gz
    ├── 14580d79575195771cd2d9188e34a4ce75af2040.nq.gz
    ├── 14d1097cff8f3ac52f63e9c8ce21c11871b8cc4d.nq.gz
    ├── 155a8f6396d9a82b1333fc2dbb7ca40f17233fe5.nq.gz
    ├── 1652ff5b2c91cdc7303a2f8ef30a5c743175cd2d.nq.gz
    ├── 173795d206aca60f4683b8352e387e380eae514b.nq.gz
    ├── 1a86ad12b458ed6b3805d806d613eedcfa0d0c15.nq.gz
    ├── 1aa604ad5a500ab5a9410fbdcf82a671db865685.nq.gz
    ├── 1adebe1623b1e4d97e4b315631e84d0468673673.nq.gz
    ├── 1cb62dfe8ba6a29cedbc3c37785bf3b4f5677061.nq.gz
    ├── 1cfa329c7090551dad2f6d3c3c167ee9de9d3b40.nq.gz
    ├── 1d411dd4430f40ea053b1dfaefba923dd6ae96d3.nq.gz
    ├── 1dd35b9689f630a7f8882d86e0df62789552c6e6.nq.gz
    ├── 1de782576f7c3ee705e0ed0238a73b38b8b3c1a0.nq.gz
    ├── 1e13255b2bccdc691f734a43d26e3e97f4157ac4.nq.gz
    ├── 1ead9a7474690462c552254c1185f1018b6b3e76.nq.gz
    ├── 208c561842abbd80bf894c8ad81345bcc33ad75e.nq.gz
    ├── 20a4946089e97e5a43f811fed74541f6a8af4736.nq.gz
    ├── 2154c8dc3657f7e33a3bf1ec8cdd1da26e61f0a2.nq.gz
    ├── 21b2866326fd02df3c01f542d28211373b9ca1b8.nq.gz
    ├── 21ba1af4f605b0ca5195e24ac189a9faa2696b04.nq.gz
    ├── 21d5fb38c7b8942887bae78a1603582e12164917.nq.gz
    ├── 2216a426dbc0b2ddab3ab468a54b1a256e24744c.nq.gz
    ├── 233b8432387b2e030f5b2ca723d5e2dbf514d085.nq.gz
    ├── 24c4369ab4b58e208f9dabe7f9846f289a0432d2.nq.gz
    ├── 26f628082dbb9bf840e6627e245fe55368f657ac.nq.gz
    ├── 2753b3e374adf56139b7234db79094b8be746044.nq.gz
    ├── 2763819b0007bdd97deab18dc41e7cb967ff7525.nq.gz
    ├── 281438026d3b71bc0cfb1af8618d7c4a65de734d.nq.gz
    ├── 2885fb32e6299597481ec89502c61113948b04bd.nq.gz
    ├── 2912578fa386da4a5cf2b352ad342826ac47ecfd.nq.gz
    ├── 2aae25a2de74abca8bced6969926d9e1a2631d0d.nq.gz
    ├── 2d00c7e6f8422253ef8ebd38c185c51dcd242403.nq.gz
    ├── 2d5cbd8497bde1564ce63eebe47611952402c33d.nq.gz
    ├── 2f069b7f9ed4e9570440836e761870d3a83472e2.nq.gz
    ├── 2fd24057fb048b6a0ba3b38370f9766f539bfa61.nq.gz
    ├── 36488c90b256f6b2348b4d653cf6b97f06174f11.nq.gz
    ├── 37661c63920a83edcfcbcde9e3dc760c5620c67e.nq.gz
    ├── 37698d918b2cf453dd3ce853de6b75c90c0922b0.nq.gz
    ├── 37f1893f3ece2f2928c2a94b17a37559a2163345.nq.gz
    ├── 384fd463a3a19737a38642638daa390374498201.nq.gz
    ├── 3977d66519347fcc0c5f6d22f90504335ae1278c.nq.gz
    ├── 3aed5c98a195fc94e0a2d6ce6d8e9fb28b326d39.nq.gz
    ├── 3c65e64e17bd5542a69b448f2df38ff1464c3f69.nq.gz
    ├── 3d66f6c77fa051e3e88b713900f622cc1da4acc7.nq.gz
    ├── 3da25d10283f5240518e4781ef1b2201f5b3d9bb.nq.gz
    ├── 3e4aeb951230e69bc042e0a3b37ff95653626af1.nq.gz
    ├── 43540f574bb0c13ba1a825e69c87c1a9a0222f56.nq.gz
    ├── 450959910a2eb6e3faf82f27239192752ed2a538.nq.gz
    ├── 450c80a02fcca3f9255310929f68dfca92e94e7a.nq.gz
    ├── 47b74535180e08936e3383d715133f0e3cd24e6c.nq.gz
    ├── 483bb443526ae3e2e410f6d7a2a23bd818ea6baf.nq.gz
    ├── 495f4450fdf7f006362b7f5b6c9d68745de16f1c.nq.gz
    ├── 4adff65d747477a075d7878847d7c699002ee302.nq.gz
    ├── 4b1af2c0b30cedc77afe434412d5fc1c243842d6.nq.gz
    ├── 4c8f79247e29c06252195d2f1850af5ecd4a0b87.nq.gz
    ├── 4d588ca5556ebeb3b6fdfb65a440837c9c377f96.nq.gz
    ├── 51b37c654cb092ed0724c1946259d4b41e5a81b8.nq.gz
    ├── 528f7835ee4717f657bf32308303ad2f47192f04.nq.gz
    ├── 540d568fe47e635d1bc979a7b1025ea1677b7635.nq.gz
    ├── 555cbacdab6d91a929e60e4d2656ad6556c25bad.nq.gz
    ├── 56249fb3e5020791090cb47d272af1d7649b5787.nq.gz
    ├── 56530cb301c1f0c1aab3db3259926117eb03fac8.nq.gz
    ├── 56965f52dae9f19cd6f257f88cf5ea55235878c8.nq.gz
    ├── 56a6f36057bd8b9e38703c0a8239a44898d1af3a.nq.gz
    ├── 5797fe75bb678be017d0798335afc397520c487c.nq.gz
    ├── 5b48959ac736586dc1a23b00579c197f76d1dce3.nq.gz
    ├── 5cebfd8bc2b444af850e7785110c38e8a1fdd7bc.nq.gz
    ├── 5e911caaa03929c30293d8cafc2a6d274dd3abb6.nq.gz
    ├── 61d302c5849dde47df97139596e559d8ea54c890.nq.gz
    ├── 64370749e77e11f7d2049c6727aa06174cac8af6.nq.gz
    ├── 6506cef85599f2a2d6af5ec34198f680f8dca6aa.nq.gz
    ├── 6663b40e741b82cc1e5f9b4922be963031b655a7.nq.gz
    ├── 66f5311b03d660356abe98b2654a86a7c17a1e4d.nq.gz
    ├── 676d8a17f4b34c3ca01c67d7d749790b94506e69.nq.gz
    ├── 680f766647073cbff2b5ca9dcb0250f3b8d197cc.nq.gz
    ├── 6829fb975dcc7adf116f648dd986d2755a7b4aa9.nq.gz
    ├── 6831532fb5ad9e51356291697449a80d6ead64dc.nq.gz
    ├── 687d542043ed82ae76fc1174a469c90b1df333ae.nq.gz
    ├── 6a36f0af3d468f2776d0320bde63af631f892333.nq.gz
    ├── 6c28ae4369110d24083f960279ab57596aba82ae.nq.gz
    ├── 6c5906d1cd061dff54de8b533942893de34efc9e.nq.gz
    ├── 6cca006ab2e8102b472ee6e639438ae00e1c3a2a.nq.gz
    ├── 6d7c01c08d1a9cf3e47973725c2c8596bba75fbb.nq.gz
    ├── 6f46a75aaaed8e5891463e7612ebfdd05b7ff77f.nq.gz
    ├── 6f75fdeac5a403c16597acd83b0a6d9ac869d610.nq.gz
    ├── 6f7b3ee0f02e27c8956d346058b3da86132938a9.nq.gz
    ├── 6f8b8a65e94486f40a5e581dcb3d6a0a8e33750a.nq.gz
    ├── 71a4ba71327e231275364ab358806c24ffe8e38d.nq.gz
    ├── 72aae56272e1a7c92d65910d24438884d7d352db.nq.gz
    ├── 749bc1872316a7312a3c0a6913c549c0c2bbfefa.nq.gz
    ├── 750782960e069e895f040d284a2e1c8abdf03221.nq.gz
    ├── 767f477956badf73f2a270e93e351ca88861ceb0.nq.gz
    ├── 76a16ad5709527adcff1c6be9f6a1ddfd5f55dbd.nq.gz
    ├── 78abf2a8027e5d6b0c4416b891e1ab6d50f9f9b4.nq.gz
    ├── 78d855907b81eeaccc74112b21e83595f6b6ef65.nq.gz
    ├── 7bb08d14d74db971d6aa42f9b2db08b59cf36867.nq.gz
    ├── 7c0f5ee26e23293b9ca2373207c7ec486b4eaadc.nq.gz
    ├── 7d2090116cd35c89c6080abef1e54664f4dbc07f.nq.gz
    ├── 7e550f921b557d56df84b088de10325b20f00e6b.nq.gz
    ├── 833b6fb4254dad7382e1619a111e638e7ea9ae7c.nq.gz
    ├── 8398814e1b073daf72011cf120e0bd9befe816c8.nq.gz
    ├── 8418ea35322a122f898713027f7ea44215eacf51.nq.gz
    ├── 847b6c304244f9603346c96ac46078a8b3d85ea0.nq.gz
    ├── 86b8a22410fef4107ef748c16ed885d3de87796c.nq.gz
    ├── 87bde22edfc39a926b61718f0f0f4936a5cfaec8.nq.gz
    ├── 88d200a1d468e06e410e1d109c39f0d3a0034db2.nq.gz
    ├── 88d7d337e1ac4fc4505331ac4fefd7b655d5e84f.nq.gz
    ├── 893a31dca4ee4d7f3a432f47ba818d42c5591503.nq.gz
    ├── 896000db28cf87c6227beae56b56c1e0de8b32f2.nq.gz
    ├── 8ad867fb4df4bfe3c944c28eb5fece80e2721892.nq.gz
    ├── 8b1e6eaccbeb07c1a2f9ef8354b84cc4fb7b51fa.nq.gz
    ├── 8cf17895b30f8a10b3bd15a51223ec5511473bfe.nq.gz
    ├── 8d9d9e89dcd6b0f422835fc158ac69ee73cf6a32.nq.gz
    ├── 8e9c5b5cbeb20eb2eeca4940fbe328257b909048.nq.gz
    ├── 90d7226a0a902573da6b4ee0d85b8503e0e3ab22.nq.gz
    ├── 91bbe10fc2c795f0f1aece2c4ef40f146f62b277.nq.gz
    ├── 9419fc24788ff5aa2536c1c5241bb8f763f9c3df.nq.gz
    ├── 97796594cb600c907fdbad06cea775c720749c6c.nq.gz
    ├── 987f96df72436e749ddf459317802dfe8fc9e22c.nq.gz
    ├── 9899f9a68e0c8b8209813a4fd8042366bf44ab51.nq.gz
    ├── 99f5b75a5dea24dcf64e2ebcf57b24ac06281070.nq.gz
    ├── 9a4486ad937de827a82f94c689e66733656b2a80.nq.gz
    ├── 9e435b7c2f018f016624435fade6135a78d51fe7.nq.gz
    ├── 9ea002c1924815249d71fdc369ed0aa18ae17cf4.nq.gz
    ├── 9ed62c8b22e46e29ccaa5cb58d96fb84d93d036c.nq.gz
    ├── 9fbbda1a1e61d33b687e2c5d9c6ce9a34965a32e.nq.gz
    ├── 9fc553bdb37879217777f562a33e82d275474879.nq.gz
    ├── a0988189b0640e63c88a60f4e8ebde071f2dd4c5.nq.gz
    ├── a1375f40e5fe974f1d194861b23a9915eac5ba32.nq.gz
    ├── a2076b4addc7a922f67fe667c5984dacb12f36de.nq.gz
    ├── a5931417891d275524f6d521da8a7992a08c0d5c.nq.gz
    ├── a622461dc29188c20bfdd06863bc1180c9332de7.nq.gz
    ├── a98073c464b1807f29850f2bfc6638e9827e69c9.nq.gz
    ├── a9c057e4043608a5ba5c6c66381d74861b2ec73d.nq.gz
    ├── aa95aa48d73119d723efe86f112ac9472da84f95.nq.gz
    ├── aad17e11a63e50631ac60fcc9a295a7052a24379.nq.gz
    ├── abe5e284df31cb36f5f670ec3ce4bcc74b449dae.nq.gz
    ├── abfe3c26df102170b91c2aebb0338d865f118c0e.nq.gz
    ├── ac5edfcdf51cbe4f344369b50ec33f18b74b9dca.nq.gz
    ├── ac7bc3b0d213cb603808d3fd7d2eb0fa616513a7.nq.gz
    ├── ad8f28e228c0e85fdb4df834efe34a607cba7ad7.nq.gz
    ├── ad9a08be10698a1da71ce272f85c33af6809a776.nq.gz
    ├── aed973acf446b17b0919414918e7992dcc6d988b.nq.gz
    ├── afcd41e3c79f7f3cbb751b4508184b9754c141f0.nq.gz
    ├── b112c1143bd4dee009d141fcc4759fe19f009d67.nq.gz
    ├── b139723fbce1219178ddb20ce944f0d3613cc8bb.nq.gz
    ├── b2893a344efc2b12a6c237e03b112d79cf7b4256.nq.gz
    ├── b2ed1a07e0a34634ae513d3bf4ad10e82d066192.nq.gz
    ├── b3ce1b58b3a1b57dd103f34e9a6709b93c3f6367.nq.gz
    ├── b5554372c3eac1190c337fd42687302db038dffa.nq.gz
    ├── b7d4e6ba3a29e42b8f4a37b09777710bdd5036b1.nq.gz
    ├── b86ebba5f77f9c8f149698327f15a3cf2da42346.nq.gz
    ├── b8c8ebaa5c8abea4e36948afa0d8f232c64a9cbe.nq.gz
    ├── b8d82e2cb14a0aaeee6a647b4cad788dbd495d85.nq.gz
    ├── b9831ebce4e150d875af524d240f842325a00869.nq.gz
    ├── ba20fd1d4001297b92ca9753ef94183a00d529fb.nq.gz
    ├── bcfec9cc8eb14a44f3c935c5d0ca9ad312e3f9df.nq.gz
    ├── bfee9c8f6b66afc0d253b5c9f8041bcb98a85373.nq.gz
    ├── c0f7de27c25768dac492196fbf1b3a95d31ad03f.nq.gz
    ├── c28c3c1817d16adbed777168fb991b6cfa2db6c9.nq.gz
    ├── c377ba09df46953da56014c1c2294b3564939ea6.nq.gz
    ├── c3c96c9c9a2522e9e0e53dfd3155b88c53b76684.nq.gz
    ├── c4f1b339d2a61a9b617373ca65d3c63bc7f2baf7.nq.gz
    ├── c4fa5f70f5e1dfb2f991264b628e78c27ea5631e.nq.gz
    ├── c5914cd87825ae83a58ff61e1d898fd03c679538.nq.gz
    ├── c5aaab4815b124042134243a72c511042536b078.nq.gz
    ├── c6743b290b2f06c95304d488b42389e6de3d4af6.nq.gz
    ├── c88387c7ba4aef0d8644fbf50422fb6d7a070abe.nq.gz
    ├── c8bc28afd8a26a2767e62ea886e87b15fcd92bb0.nq.gz
    ├── ca60dfc9925a9e0c3905dae8fe70cb8a30aba0fa.nq.gz
    ├── ca867ac2538ebf09720f737785e01a8e97b6ab56.nq.gz
    ├── cae2f6a885f049e947c788e004f32529e1bb8cfc.nq.gz
    ├── cc8a16aa90a77733cdcfe8fc3a1f25a189713d98.nq.gz
    ├── ce3e72818d6efb03fd7df954f67543558033613c.nq.gz
    ├── ce8d16d6cb93e79f11a6277769d7d3316d04c3e2.nq.gz
    ├── d2832a2c8936d2cbe65ae3bca4edd3723c76180c.nq.gz
    ├── d45b5c71ae1db779a53471f0573e342ddee44bc7.nq.gz
    ├── d5606ad0be08a2702754f0859af889df1c0a273c.nq.gz
    ├── d5ece30e82f24bfa891a4229bf9e1359f303514c.nq.gz
    ├── d8602f52f43685f25f7ed310c58448e0a4f03a31.nq.gz
    ├── d9c4327fe822b05e05bd07189c54bc694adc05f6.nq.gz
    ├── dbcadedb9b1af02f32d160c1e8345e2e0dbc9779.nq.gz
    └── dc79ab0b5bec289036ebb9537d928bb69e1c70e7.nq.gz

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

[jazzband/wagtailmenus](https://github.com/jazzband/wagtailmenus)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
