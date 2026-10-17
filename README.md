# Repolex Knowledge Graph of sunpy/sunpy

RDF knowledge graph data for [sunpy/sunpy](https://github.com/sunpy/sunpy), parsed by [repolex](https://repolex.ai).

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
rlex download sunpy/sunpy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 969514fa29259db7e5de9a69ff7e42af31240d3b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 969514fa29259db7e5de9a69ff7e42af31240d3b
│           └── chunk-001.nq.gz
└── blob
    ├── 003f9e5bf04032bd20cfc5225d79ee270e603e8a.nq.gz
    ├── 0071c4660c3a0cda3dffcee721d12501f04967d1.nq.gz
    ├── 01761291127678074c10268b578deaa72b8bb0e3.nq.gz
    ├── 01c568285ec0de42fc55f8846a7462eb72374bb9.nq.gz
    ├── 0265442dfcbc94633704b4b8cadcbf20632992f6.nq.gz
    ├── 031169d2e0151d33611f4e12501d2fbf69683c6a.nq.gz
    ├── 045d70d9303af1883db5e9a55b9a5c26d54cffb3.nq.gz
    ├── 0638bc3082bd660e09e3477496904cae8a2e3984.nq.gz
    ├── 065dc4b13ef5e26716331d1f3fbeafff20418543.nq.gz
    ├── 06871fca130cd74443f1b04d6eb18ea308c47fd3.nq.gz
    ├── 0776b4f0b7e9d4f370b16a1ba94690fb8dce6ac8.nq.gz
    ├── 0830a3707894eb8cc958b0cd18da3f8a02345408.nq.gz
    ├── 0a6eab38fc7fb660eea6277e0925ab9f4f0402b0.nq.gz
    ├── 0aa9a5fbb84b54860bb12484dc1c91d1aa707ac4.nq.gz
    ├── 0ad1cae9042131a59a5f50b5f3bc63913b158ae3.nq.gz
    ├── 0ad27843a10806efee9ba39e902c82934339e8b0.nq.gz
    ├── 0cc980e8d2f911951d1e0b3819b3d647604f9449.nq.gz
    ├── 0cef5218cbff845da5da5f1f2e67f1bd4fc56fdd.nq.gz
    ├── 0d1039f2a4acfc89c19f958b40853a01211b7bad.nq.gz
    ├── 0d4362974870134d72aa69195271d1b5c8264e90.nq.gz
    ├── 0d794765cac08f713da9c245e775e9651f10447e.nq.gz
    ├── 0db6ba41d6387ffceca0de4f19056e5675f3783d.nq.gz
    ├── 0e0ca929444f3023a6787527406edb1fbd1e858a.nq.gz
    ├── 0ea792010845dd2d680e6ea1ae165810ea70b85d.nq.gz
    ├── 0eb7a530785081737fcc6fc6ce4a1a282ccc0b75.nq.gz
    ├── 0f28e5dbe2136674ed555c25c6385906227bf448.nq.gz
    ├── 0ff8cd736cd884db3e66dc3a81e792993a5b83d0.nq.gz
    ├── 1041765ede33cd99cccedfefb1dc4dbc96e2efa7.nq.gz
    ├── 107c61405e3b4a3266a83064073910b6c8d4a42a.nq.gz
    ├── 109398366f96bc078adf13e22c30f0779b7907aa.nq.gz
    ├── 10dfd9a51b733c0e6dd9e7d99325ed2bec8cf14e.nq.gz
    ├── 10fe2c07ba2a928379ea7c5544cd2bc9ea8c0960.nq.gz
    ├── 11575517bf270ee4f1775ff4d9b5703f597edd07.nq.gz
    ├── 11fc8190d87471239a13bc4793d0d4467e69bda5.nq.gz
    ├── 126c84ba746f256649dd13f05aadb5dab821346a.nq.gz
    ├── 133faf6c7044894f98d46c5baebae2b6280d28d2.nq.gz
    ├── 134aa6144c52127c6c3dc5477664672ef5ac947d.nq.gz
    ├── 1367d8e1e31ac66243497bee69c8401d8375682e.nq.gz
    ├── 13baa6abcb9987ba5c0b5c34a26db4aae6d1dd86.nq.gz
    ├── 14afdee654c66d04d68d880549785ea1a9597746.nq.gz
    ├── 14ba83504510ecb6db069f1ae1366a39bf654f14.nq.gz
    ├── 14e4b30ba82a7489d32ed51acc07a5ac48abd7cf.nq.gz
    ├── 154dc1e930dad210a1f63af1d9af5ba4500610b2.nq.gz
    ├── 163e43414d86031acb335a3e61cd5fa99339f846.nq.gz
    ├── 16b08e7415b5e9e81ef44596c054e852fd7d69a9.nq.gz
    ├── 17a225d98bb02215b967c795a06e230afab6b5d0.nq.gz
    ├── 185a2bf9a4de16403c050dcfbc35aa02acce3669.nq.gz
    ├── 189c93a11bd5beef8bf4b9a995e36d11fc4b5f36.nq.gz
    ├── 18bbca8f8df7cc9b6171a08cad838aed5061f157.nq.gz
    ├── 197b552a624d36e65b5f8c1de4c2468353c7bd31.nq.gz
    ├── 199c87ede5da4c123f2971b356acf3a8a1e8710c.nq.gz
    ├── 19c7ca2bf65985d48dbd9159fecbb1f3788e4d4a.nq.gz
    ├── 1a2d0e98c0156aa8e2cc1bdab2a21a27bd4b3455.nq.gz
    ├── 1ab0da941280a5d3daab311c7a0caffd388dfa7d.nq.gz
    ├── 1aeceb7e5adaf5a43bb9aaffd3fa3cce2de6479c.nq.gz
    ├── 1b956cd1370ad11908683df7c9956eae3d1520c4.nq.gz
    ├── 1be0bf5a73f68e595ad0a8f7ed57358e06018b37.nq.gz
    ├── 1bf347e8ac28269d6737135cc863948abdbf4804.nq.gz
    ├── 1cece9d49a2d5f2c2bda6a204d40b305ca93b673.nq.gz
    ├── 1cef31738a7f74350f2ee99fc9b90e050acfc5ed.nq.gz
    ├── 1d02fa895046a75018e654f8fb37e512826e4a01.nq.gz
    ├── 1d5c0496a4e863bef859af4bd23b82d3d5aa2f2b.nq.gz
    ├── 1d7f9629b6e1f44a169bf5c733f20794d47118b9.nq.gz
    ├── 1e11c0b5bc88a2e37dd959187287aca083272f61.nq.gz
    ├── 1e3d5dbb9d3572f924ba0b28c6dfb5cf1fbd549f.nq.gz
    ├── 1f0830305f7736dd9c00a1c348610e6196208bf8.nq.gz
    ├── 1f9b3f53dad092cdebd7e54dc81728a959b3ae94.nq.gz
    ├── 1fab8db92b91abd16a88ec1a811ad20fb43bbb5a.nq.gz
    ├── 201b311e8e2964d00fe82eb79eef899f6245bbf0.nq.gz
    ├── 201b8129b61a3c021e1738dd65f8e68686e58620.nq.gz
    ├── 2086662fa1db8b3f7a74c370867ca571ccd83be2.nq.gz
    ├── 224aae892cb8f2ad273e5dce09a64032502ca750.nq.gz
    ├── 234fce8fb5b3ab7393cdd614816b282a02c876b8.nq.gz
    ├── 237c3bbcff9b7c9e2b5222ba18f8309d073efe66.nq.gz
    ├── 2419059cde7da8bcced1a5b664865bf1a5206ac0.nq.gz
    ├── 25354031f86b30dceb232a81d586bd2f8b571409.nq.gz
    ├── 25a6c36b842f764e0570fe05ee03526a08ed72c6.nq.gz
    ├── 25d7886499d8104ba3222d331aa3bd5083f92305.nq.gz
    ├── 260be591bf16cd9f0b3f62ada1a690f2a14f1217.nq.gz
    ├── 26285cb71e748e568752e9ade6d43a0e1a97852b.nq.gz
    ├── 26a32cb86f2fdd80fa111308808516920eb129a8.nq.gz
    ├── 26f80a64b727e1f12b47e6f4ff5cc4353d5fe76d.nq.gz
    ├── 27028ea44ec01cab8a23cb60902297253702b8b2.nq.gz
    ├── 27a99baee6e0ea78fef2636295896cf14d2925a1.nq.gz
    ├── 28631c320aefca81674c51ea1b1fb5da50dbdcae.nq.gz
    ├── 2907dd647903b7bb1af0a4d56d48742536ddbfca.nq.gz
    ├── 2a04de34fe69aec41f0d61746971944cc2052bc6.nq.gz
    ├── 2a8e45aba841e109741134241a5d0ac1a3a5ebef.nq.gz
    ├── 2abb41ad0ace40ddfa683e861daf2713fb9bc881.nq.gz
    ├── 2acd1debeb1d3b981fc577b777a77106c765c391.nq.gz
    ├── 2b48d4501c9c5d191fb9ce7ff1bdcd3d91b40c5d.nq.gz
    ├── 2b76b688897f8976e5300ec304d7f22a1de75dc3.nq.gz
    ├── 2bdabb4473669b55c2630e29da25062c23ae129b.nq.gz
    ├── 2c49ba500a3999a0048613d9b4bd82afa8ac709d.nq.gz
    ├── 2c7c3d092fa16061b43d903773884e6d074ae69a.nq.gz
    ├── 2d43a31df2cd6cbf78906f8f18c45913ac3be049.nq.gz
    ├── 2d6e08144f117ecf1352d098c1e7c270727e9a44.nq.gz
    ├── 2e0970f46de49dcc4536cb6021d745bc96728a4f.nq.gz
    ├── 2e776c2f0c84b65c42639a5684312446c4202198.nq.gz
    ├── 2e7b7eadf7378cc8cfe1ea92d24596187c4e5989.nq.gz
    ├── 2e8b17a27d35ce77f29e6465ae48db5c438a70e5.nq.gz
    ├── 2f34e0de93d9b303bad426a6aa83e303231c6a9f.nq.gz
    ├── 3030ee45d7789702463b2fae98e787f56a361d05.nq.gz
    ├── 304f42db70197eef7218b9debfeb3b6557d4d0d9.nq.gz
    ├── 30766f8a5dfb102696b315bce5346768b45b47ea.nq.gz
    ├── 3185bdead0a5b9fa1b50e9bf907db9003edf89e8.nq.gz
    ├── 31b9c1bfa1a3eecfe5dbb7ead1764297b3c9778f.nq.gz
    ├── 32280e320e375190af09cf94a2b61cc99a59968f.nq.gz
    ├── 3315e2a7f73b2d5be7ab4cdf8b5c7117009efc35.nq.gz
    ├── 3325cda64614954b39b5436ed86c0674f55bb666.nq.gz
    ├── 33f7744c78d9c0d4dca20124b0febd9782cc8f02.nq.gz
    ├── 34a5802bbccb67f7372dc0ee9dc2dab557cdf792.nq.gz
    ├── 34af6357f7073c9e4df7124c2ee6e5bf863a7e3c.nq.gz
    ├── 34b5f8090194ed9e0521efa81096885abc5d3e41.nq.gz
    ├── 350549296926bf8446e94e6971ca9a345bb8f875.nq.gz
    ├── 3619495ef34f078e3fd9bf3ba50b1a3a28f96a59.nq.gz
    ├── 3800a6a7df1d92220da6ef6fa676caec41f2c875.nq.gz
    ├── 3817d2d229bbc5ee84a9dbf01322b3853d3c44be.nq.gz
    ├── 382f6e7693a2a0f3d078984f7e227a8757462a84.nq.gz
    ├── 3834524fb52b29fe83f24e49e5f93578760f47a4.nq.gz
    ├── 38b398bf80f53a67c2970ffc42dd1f2b31ccdd0a.nq.gz
    ├── 3923b9fc8ac3fe9c3a85d87c4ab09a47a2b02264.nq.gz
    ├── 3a2916ee0dd7d9e5fd3bcf07605b2615786f7b94.nq.gz
    ├── 3ac61c7c037fdedcbf357ec0f7fa11664d5a90d2.nq.gz
    ├── 3aea723bf56d85edb9098e2312af819bef54f191.nq.gz
    ├── 3b46c2eb1d3544c88f06fa818be25d062ac088c3.nq.gz
    ├── 3c424d911909814514651ef8a4d75b48320d96be.nq.gz
    ├── 3d5dbcd2e1d44e7dcbcdd5d3f54c2f39dd3a9f7d.nq.gz
    ├── 3dca0f651a8f6acbbd8455eb4e38b851f8db3249.nq.gz
    ├── 3ea1529cc7a7d648f014dafc70529fb66ff5181b.nq.gz
    ├── 3fa55c53832be1050879464ea8be5069007da42e.nq.gz
    ├── 3fd2b0b019481670578ef542df55b5367a796031.nq.gz
    ├── 406878314960873164e2d1c75bf809d0b10e6e93.nq.gz
    ├── 40b4b83b420dd8614d56f81fa25584374623ea90.nq.gz
    ├── 427c59960746141db753a38eb639ebd693f5fe21.nq.gz
    ├── 430e96333d4f461a5569049f7f2d90ebacbad9d3.nq.gz
    ├── 431096b37a2be45301c206ca3fc40d7b7e610e91.nq.gz
    ├── 43262768c558abc9c4a73314f300da92f77d0137.nq.gz
    ├── 43dc76072f470d3ffbe383dab1d56619fa9806fe.nq.gz
    ├── 4428c139b2e9004eb841aabb619ef7a101914aec.nq.gz
    ├── 45036eb9a38824bc9fc47d9103a3cd1d283430a6.nq.gz
    ├── 459d2feef50e739ce444998d7ec737bbd9d0842c.nq.gz
    ├── 45f979460499515f81b8c2c3fbc3dbeb10895748.nq.gz
    ├── 478ef851aca3ff230640800251094c5f5ac649d0.nq.gz
    ├── 47f08ed2a34a4bf6eaeeeb3e13233b1c8f26b7fa.nq.gz
    ├── 47f449f3e41f74b7d1e9541340de99b61274eb03.nq.gz
    ├── 48f8865debaf74e1155461c1d9157afd79b63221.nq.gz
    ├── 490ecb3640fcc0448f7cdafc2aa8d0a1bff999ad.nq.gz
    ├── 4937f0893b9fc953a9fce6bf1543b251fb1f6814.nq.gz
    ├── 49b36d5102a40b04ab9c451813f2d02e3665c88d.nq.gz
    ├── 4a66ef30bf49ad77b8448ede0ba026c051d1a1e5.nq.gz
    ├── 4b3e573e8b068138f6edc344e42c6496a8c3ef14.nq.gz
    ├── 4b5c60725f8c81756b70e2794e09b2fbc4c267e2.nq.gz
    ├── 4c1164001638849e1ff5c4cab419b43d2befc2e9.nq.gz
    ├── 4d71121337276511bb1aa5f166b1825466d8ee2b.nq.gz
    ├── 4e089414a02d999242812dda8e57d192c30ab09b.nq.gz
    ├── 4f7bcc30e0230053a434edee0ce07b1278af950d.nq.gz
    ├── 4f84a1674036e6bbcfed71523e9e287044be5d77.nq.gz
    ├── 4ffa3631e8136e5c8367f32b2aaa93479f5a893d.nq.gz
    ├── 503599e862110a3f15d25d05cf3894894930151c.nq.gz
    ├── 508b589dbdf12acf974b635b6c9791bc902e9489.nq.gz
    ├── 52b8f0ae9e336fd722e61e599ec2e164b08d3da8.nq.gz
    ├── 52ef4cc00936357b10ac355fd842a04dc52ce316.nq.gz
    ├── 5338ffc2627383b0a6f9afaa7d530dd1b2d89ef9.nq.gz
    ├── 547a9a960c3dedc9283259ad2a1d8f65c8bab245.nq.gz
    ├── 55e2bae8414003bbed856893db71bb068096e3b9.nq.gz
    ├── 55f15ab4c26f93acc7fbf4f5689f7be7863cbaf1.nq.gz
    ├── 5605fa94ae37926b9d21345a5006fa7037a57829.nq.gz
    ├── 56155466a9bd78f34fa6bf2f6a32815b97217cde.nq.gz
    ├── 56c3d2b937feae22077b25787f74e3053bad2804.nq.gz
    ├── 57701c0e92196b5497b580d7c17d8aeb0ebbdba6.nq.gz
    ├── 57779a7549c0e43eb2b512ae01b2cf08aadddb2c.nq.gz
    ├── 578f176d6dc24f76dffeee06407f4acb25ba586e.nq.gz
    ├── 579ea32d0522a59fa8c233fe7e883f531945aeff.nq.gz
    ├── 57e27aa555ce37dcc6ceab1d1a489a67dff0b0b4.nq.gz
    ├── 5831dc6eb227bcb7d136d421170cf248dae28ecb.nq.gz
    ├── 58343a487f54ba504f88a7214d3db6ccf3f1e340.nq.gz
    ├── 58365a2666f34d2a09e73035f83dc973618f7592.nq.gz
    ├── 58806e1c1cf5ceaec87b48525f2b9179b966e66f.nq.gz
    ├── 58d38efcbcd43932692bcec681cbbd91212a00be.nq.gz
    ├── 595057c48523c9fc865356912850b0e840784a13.nq.gz
    ├── 5979a4d9206f665f69f51b2600cc6229c7b9f21c.nq.gz
    ├── 59b5361c693fb4733d5b932675154e6333638d74.nq.gz
    ├── 5ada34c02b539a8e2c290b9be506df94c9c604f2.nq.gz
    ├── 5c0c318791ed84f61597dbfefa7c73dcdbe68336.nq.gz
    ├── 5c304d1a4a7b439f767990bf1360d3283e45d0ee.nq.gz
    ├── 5caa76d3ea3a4e16c477b7e53c8fbcbc0967c20d.nq.gz
    ├── 5cbbfa5d7bc6e9bce582fc9e5a13f86653e36b8e.nq.gz
    ├── 5d46a18101d502b37edeb0fcd31441cc051aec51.nq.gz
    ├── 5d937c209f17af552c77bad45046dc798ad0be24.nq.gz
    ├── 5dd9303545bf31dd7d5fef3397833b445f044135.nq.gz
    ├── 5f3c857b3eda1a251224319a192d935ca570e5f3.nq.gz
    ├── 5f9465a29d5a2762316073fb1b1a9b5677130ece.nq.gz
    ├── 5ff7486b46c58693a1640c4f4d8914fa1f8d9d9d.nq.gz
    ├── 6099d8c139b3953ccadf3c6d717937c2ae6a2c47.nq.gz
    ├── 60ac6402b052129ec30504270667c737a329c5ef.nq.gz
    ├── 61adc668af960d55196077a92c3c60de0feae194.nq.gz
    └── 6321e7db470a34bb1c8aed0c2b71354346f1d265.nq.gz

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

[sunpy/sunpy](https://github.com/sunpy/sunpy)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
