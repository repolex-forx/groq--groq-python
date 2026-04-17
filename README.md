# Repolex Knowledge Graph of groq/groq-python

RDF knowledge graph data for [groq/groq-python](https://github.com/groq/groq-python), parsed by [repolex](https://repolex.ai).

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
lexq download groq/groq-python
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9793d5e9c3993ee7b7b0a9b75a7f324ac7de0323
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 9793d5e9c3993ee7b7b0a9b75a7f324ac7de0323.nq.gz
│   └── repolex
│       └── 9793d5e9c3993ee7b7b0a9b75a7f324ac7de0323
│           └── chunk-001.nq.gz
├── blob
│   ├── 0111eb53e5dac6de4817f402ecc4f292ca0539b2.nq.gz
│   ├── 01de91eafa40e6a840282cfce47ea8c78274e1ee.nq.gz
│   ├── 038cbf573b9e6b29844b5b9944df298906865636.nq.gz
│   ├── 041278a69da6086bb32a1fc40a7e8352f2ceb192.nq.gz
│   ├── 04d57c29bb573b2686eb442283f33e67efa7b897.nq.gz
│   ├── 06e18b322df8e0d34d7bd043fb31d8910b0c2641.nq.gz
│   ├── 06e7664a41c09786afe6aeafdbebf924e5c5fd72.nq.gz
│   ├── 088581b23e1edd2c9bf62b3c91b907882cb00304.nq.gz
│   ├── 08a0070617e77b1a8a5db4cb4af0f4dc7e5e5faa.nq.gz
│   ├── 091217c3b995ba85e53e80d7e46db929896cc5c6.nq.gz
│   ├── 09eb49f6587c2635062f33b64804c311a36e3c67.nq.gz
│   ├── 0b7362a89c3af065bfb48615411dd511fbbd2a53.nq.gz
│   ├── 0cf2bd2fd9d04040ba557f3f6658e6c4134d26d4.nq.gz
│   ├── 0f239a33c6df82d00988a48777a64ab13449b72f.nq.gz
│   ├── 10cb66d2d9564332bcaceafc71e6987a4a365762.nq.gz
│   ├── 1137ede2be61957167e799eb18b9a727f4b233cc.nq.gz
│   ├── 15e259987074d89fd00e5d0753ae12cef53bfbb1.nq.gz
│   ├── 1782f1c595b28481eaaf719efa02cb7e693c2bac.nq.gz
│   ├── 1837470b93e8c53dd60ae0cb8fd6a8458e2bb605.nq.gz
│   ├── 19201a09eb696a85779effa2e1386388848d8206.nq.gz
│   ├── 193109f3ad2b3c00e59ad3f41ad32d9f704f5f23.nq.gz
│   ├── 1aa62ce3edf803fd133d80557f1d2445af1fd21a.nq.gz
│   ├── 1bcfc0388dd2b1303e67fb8723ba8560a800040f.nq.gz
│   ├── 1e286bf26754c1f12003ec3b88ddc7a5de50860c.nq.gz
│   ├── 23d8496c5fee5cb0c81a45484e8d40ce32a6af42.nq.gz
│   ├── 251b35070def60e490cd2c2eec5d3c0bfe4caf16.nq.gz
│   ├── 2521d0b4f3d7fe3f5f5ab561b03117535e6870d8.nq.gz
│   ├── 26b73ee96e443b4df36049081c868b0e0c30cec0.nq.gz
│   ├── 26e2e0537162ca210be1cc9061f6969751a78634.nq.gz
│   ├── 27deec9df1a8e54eae751448af49237f50b227ac.nq.gz
│   ├── 29070e0558d3f7c8ff187ae9cf5b484bc378f009.nq.gz
│   ├── 2d3e94c0ff181bf44d4730927b6f60b1d09701d1.nq.gz
│   ├── 314a7f9afce1540a76b9640876e6298c21c20254.nq.gz
│   ├── 32412247a768168bd83f09765fb5f70eb5315c97.nq.gz
│   ├── 344a337542e58614e9b6fd1ae7f5a888c892d740.nq.gz
│   ├── 3706a08b8cd3bbd1e9b23b22950fb8ddbff1b6a9.nq.gz
│   ├── 3824f4c485fecaa52e43e02e76ebf397b3515ca4.nq.gz
│   ├── 3990a0671f53232ea0895914e1de1a394a135d20.nq.gz
│   ├── 3a66b2c35b46aeb8c4716e1cbea16e9991ec2eb9.nq.gz
│   ├── 3a69585284c3542df8d339579e8e0956100075d8.nq.gz
│   ├── 3ebc2ea5fc5248d80fac371185bc555285f470f4.nq.gz
│   ├── 3eea186fa78f991533d8f54bc3e239079bad6a9e.nq.gz
│   ├── 4094ef24ae3a4157b52e6e920fab089b17353370.nq.gz
│   ├── 44c671e3d1e1bb087bcebea47c93efe531d73ce1.nq.gz
│   ├── 45fc742d3ba84a7ec508b1122fe106c23f484a78.nq.gz
│   ├── 488331d131f0a198202285af672dad0f6fdf50c4.nq.gz
│   ├── 492ca37bb07dadfd96cabc7a76e2c647833082b1.nq.gz
│   ├── 499b4c8b47c40cdae676a7fa9cc41aa051da56e5.nq.gz
│   ├── 4c48c14b42cbe95985a55586305966da90d742ec.nq.gz
│   ├── 4c4c87662b38c9ca9cb8340248c2b433291a356b.nq.gz
│   ├── 4d6e1e4cbca09d0aa6e892fbe52b0f7aed3ba947.nq.gz
│   ├── 4d87d48673fd13e6be2ab5fcbed35dc9a9750737.nq.gz
│   ├── 4e29d9fc51e6e7e1b966012220720a94745c9fe5.nq.gz
│   ├── 4e359cf2631b4a031710bd625bb30acebbd7d7cd.nq.gz
│   ├── 5207549207e533479a7266b1b1a5bbdffe93a2ba.nq.gz
│   ├── 52af3a4895ab83511c027a0dd9d35d41bfb050d9.nq.gz
│   ├── 52dfdceacc4d3e7b88e8d7cf016c0670cd2fe977.nq.gz
│   ├── 5325182b80cad971215cf5e31a7d1351fa1681de.nq.gz
│   ├── 5367ff2abd0e8cec5cbf95b3c9839d57850797de.nq.gz
│   ├── 53bca7ff2aa7e73b6353d977a14c0d3b167f7135.nq.gz
│   ├── 53f2bac3cea084d3eabf8fe1873a087d26520c0d.nq.gz
│   ├── 54d645d04df64a8802e22c9b6d9d3131cca23844.nq.gz
│   ├── 59cd694cf83665f70b2405c7efcaa05e0ca262b2.nq.gz
│   ├── 5aba4b854b9f322dfaf0058cfdc2462caba51f78.nq.gz
│   ├── 5af12bf94faaba1b66a7c6104227ac0ea5aa38c0.nq.gz
│   ├── 5b01030785fafec33fdf6824265d11aeac343606.nq.gz
│   ├── 5c15322a229eb738ea00f4c5c8bd458272f123fa.nq.gz
│   ├── 5d122d2020f21362d9a0df8a86122a80953678e4.nq.gz
│   ├── 5e2c99fdbefc565576f8c5f37b0b0a66d60f2015.nq.gz
│   ├── 5fa0c6519a1a1eaf6ad9d1266c5ec96adf51826e.nq.gz
│   ├── 60584214af7a92e0f32e3fa713c9199f52ad6f72.nq.gz
│   ├── 60982c3a1f57c38f6d932ca1bd64f23a0e576f68.nq.gz
│   ├── 62092209f77fd91fa545f99cc31a85926cbff9cb.nq.gz
│   ├── 63391ce3b2ef641e536d6289989e757b1418bebb.nq.gz
│   ├── 647ca42e5b153575487e383f7c867cebf484a5ba.nq.gz
│   ├── 6506224a2070e2aedae5bb58359a4cbb3b2e846e.nq.gz
│   ├── 65163cdb7855ec44535f5f4666c51a7bd899cb21.nq.gz
│   ├── 667ec2d7af06d94ca031b1e53bfd1d1dfd4bbe5e.nq.gz
│   ├── 68a55db69beb9cc966d01d966214e52b270baeb5.nq.gz
│   ├── 6cc19871755586511b56ac4f488aec8fbd6e33e8.nq.gz
│   ├── 6ddf2c7170bbbccbd5d824e79c4e875ff80c5e1c.nq.gz
│   ├── 707dcbf4322141a1fb5fcfd59f9c504d383817a3.nq.gz
│   ├── 7363bf0cb7515266af4d582f92fe2381f7ec4571.nq.gz
│   ├── 777291efc884c19566dfcdb2026e3218372b6d7e.nq.gz
│   ├── 7abd3e3434e76d2a9f4fd304689c9473dc0d3fea.nq.gz
│   ├── 7add5ef6de21668ef87855cbf80a7a41986533a5.nq.gz
│   ├── 7c25e68535b48c79d9980b4d96f2c7420ba84127.nq.gz
│   ├── 7cb9d9e668c5a5efb1b12e72d115276298a70ec1.nq.gz
│   ├── 7d001e416ac99ce1a376fc01b67f744b33d0b31b.nq.gz
│   ├── 7dedf041b797befe982983b313730b2b8994a85e.nq.gz
│   ├── 7fba0b5b0e0ac30e73fbbd029349180e581f5369.nq.gz
│   ├── 821b560e7db615a8d5fefcc0dc9ff370564742a1.nq.gz
│   ├── 826054e9248cc9c66c7743ac7483c0fa1da683c3.nq.gz
│   ├── 867b999dd61b505f84bb40560415af30c0facff9.nq.gz
│   ├── 88adfc84200fb59e7cd7332c8b75a489ae92715b.nq.gz
│   ├── 89aa712ac4c923b6e3c4e72b8c8a764de282f585.nq.gz
│   ├── 8d2c44c86a81589e7759386843391e0176873a0e.nq.gz
│   ├── 8e5056d0a91d361d32a8555b2aec82fbc6cf99a4.nq.gz
│   ├── 8f8354495f3e969a744b0dff50a6a19fd56bfa1c.nq.gz
│   ├── 901ff69ac934465e12a0969868ef83e82ffd86a5.nq.gz
│   ├── 908203ff6d8556fbaf0a93c84070a3c7d6de28e1.nq.gz
│   ├── 922eb115d6ac3f7bbcd9bdae758d89fc81110e09.nq.gz
│   ├── 930a9fe664fd2aa00276e7373afbb7798fbc574c.nq.gz
│   ├── 9487be566f2e06545fba6a462ea68aac41ce5261.nq.gz
│   ├── 95aede5ce05acf74713320d8bbc9bdf7f7debc56.nq.gz
│   ├── 9795fa7cf176a62749d4c49f7ca7d72c634c0d23.nq.gz
│   ├── 9853d101a5655c2eef002ed47fdea29116d48e36.nq.gz
│   ├── 9c6a481f5bbeb2bb190388a092e1e2488e7f58b9.nq.gz
│   ├── a0c79edf7fdbf663813f3819e5338936e15c32d1.nq.gz
│   ├── a270744417f80d53119823c1adc17a458ac600ec.nq.gz
│   ├── a31ab4960ebe682ded3d60b54858a0e7dfa2df22.nq.gz
│   ├── a3d83e3496f94ba1ff63ca2b1088ac48a64d07f2.nq.gz
│   ├── a412dd0b3298712b0f23b7087e4f6883ea575b1c.nq.gz
│   ├── a628e32bce6243dc68cfeb18c373c229113de34a.nq.gz
│   ├── a67218da00504278777065cd658668b403b3adb4.nq.gz
│   ├── a8e5feca9bc0dd9cc4129a4cdc6c15fe69c604be.nq.gz
│   ├── a9308a8b1622943f45f1c338cabb313da6286d6c.nq.gz
│   ├── ab5e0cd7fec59f9eea782b4a8027c9d56c527e77.nq.gz
│   ├── ad20019a6afdd968d7af6e4933d171ee3311246b.nq.gz
│   ├── ada6fd3f7215975eba896b8dd19c9825ce3179df.nq.gz
│   ├── aed346148e160fcf19fdfd70b662f42924d671c1.nq.gz
│   ├── af34c9f4c789c5407ce4c8e6e067cb9e91ce2cf5.nq.gz
│   ├── af5626b4a114abcb82d63db7c8082c3c4756e51b.nq.gz
│   ├── aff160f2d5a492e222512f7f2f2065c58451392b.nq.gz
│   ├── affc3eebcf4ed9ac606792ecfdfdfaf6bf3d5e50.nq.gz
│   ├── b1ca37bf58d2098a8f4e770d2b23ce6384eb5bba.nq.gz
│   ├── b430fee36d6888bfcdd92327f064a4974cbf64b9.nq.gz
│   ├── b4bdfa963e7d03b359a732266eefb61a578af345.nq.gz
│   ├── b5c4097c84ba0fe156ff2b819793e40cc5911b88.nq.gz
│   ├── b845b0f4c968eec68dcc4259e37bcd53dc9a8007.nq.gz
│   ├── bed16c444c5b0a28f53ea5c5ce350f28ee5a5952.nq.gz
│   ├── bfa26d5a636191bef56f1e2d4df5dbe92f10f341.nq.gz
│   ├── c17fdc169fc6d3d200944c9839b6fb4fc40dfdc9.nq.gz
│   ├── c1d806cdff5ef1e708f17fe8c01ea3d442b04374.nq.gz
│   ├── c1e08418cd94dada217b472bc4f145d7aad963ce.nq.gz
│   ├── c2ebef74c872604a60c4b88b919e6710de0f36cd.nq.gz
│   ├── c3041f07488ae9e8d797c0d24f46d1592139a6e8.nq.gz
│   ├── c5894cceb64ed521ebd9556e759434c663910f98.nq.gz
│   ├── c69e258910d2390b98345a21ee52c78b966c4d76.nq.gz
│   ├── ca690705931275f64d322213d8295baefb8855de.nq.gz
│   ├── cff4feb6ca469497a7bea6e51a8e873a8b946387.nq.gz
│   ├── d2c9cfaa3f47af79d9d33f16d52891cecfcf0c8e.nq.gz
│   ├── d68a90df0bb582916e65f271baf788cd6b4fd6ea.nq.gz
│   ├── d75a2e0e4aa0302b5d726703111d2b52b735654d.nq.gz
│   ├── d8c73e937aeda0534b48d146e2816d5000f0680b.nq.gz
│   ├── db3ed8a36938fc1cd5df63ec59526cfc225012a0.nq.gz
│   ├── e085744e290fb280d75d4b006d8f34f6000a47be.nq.gz
│   ├── e1f68a0b97f53251cd9a52a9e80334f7df8c152b.nq.gz
│   ├── e46b9b58dfb5e94991b6a7338e53f5542bea4ad4.nq.gz
│   ├── e62311e3499d54a8a36512935f23204f50dea213.nq.gz
│   ├── e6690a4f2e2603f2bda48b119a3ec925aec812cf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7601f74e4938fa1970e01a45f32bb413d14ac99.nq.gz
│   ├── e98f5a46c1bd1c7f21e33c46d54014fc3efd094b.nq.gz
│   ├── ec65d94caebb0e9365ed418d41f41772a882fb28.nq.gz
│   ├── eec7f4a1f23b1745a3b2e35b8f8410deac55e3f0.nq.gz
│   ├── ef638cb27921bfb8c402906e77e0b60989debce1.nq.gz
│   ├── efc56f7f9b2303e3ce9f0c5075f1d7cf3bb8812c.nq.gz
│   ├── f4122a7576ea48d3aad8ad33e29f731abebb1303.nq.gz
│   ├── f45b069c5ce72856f3c2de37185aa9c8b5573e5f.nq.gz
│   ├── f4a0208f01c069616000eeed319029fc92c03b56.nq.gz
│   ├── f6027c183d1b6cdcdd7f798259f79824a067d5b2.nq.gz
│   ├── fc39158dffcf75a42c570fba4f2cb35b221cff52.nq.gz
│   └── fd8019a9a1ae24f57aad1f0228a0e9b8fbe426d9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 9793d5e9c3993ee7b7b0a9b75a7f324ac7de0323.nq.gz
├── filetree
│   └── 9793d5e9c3993ee7b7b0a9b75a7f324ac7de0323.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 173 files
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

[groq/groq-python](https://github.com/groq/groq-python)

---
*Parsed on 2026-04-17 by [repolex](https://repolex.ai)*
