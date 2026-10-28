# Repolex Knowledge Graph of zarr-developers/ndsel

RDF knowledge graph data for [zarr-developers/ndsel](https://github.com/zarr-developers/ndsel), parsed by [repolex](https://repolex.ai).

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
rlex download zarr-developers/ndsel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 49b9e1db1ca93c55f320b025a666367de87a9014
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 49b9e1db1ca93c55f320b025a666367de87a9014
│           └── chunk-001.nq.gz
├── blob
│   ├── 018441ebc5603dfcd120c36c0eee9ca314237ae8.nq.gz
│   ├── 024d65d8f00298526668f14c3134dc1e83d6d76e.nq.gz
│   ├── 072acd0af536a2b94533243f1625d5f4001b55d6.nq.gz
│   ├── 07fcb2b0025f322286b61d21ef1bfdf30c95f886.nq.gz
│   ├── 0893b087f23f6779957eaa0f040a34f920a44e6c.nq.gz
│   ├── 0cbdba0f7e2a70ee1a8092b2059d262d5eb75dfd.nq.gz
│   ├── 0e259d42c996742e9e3cba14c677129b2c1b6311.nq.gz
│   ├── 14d44337ed25c8e35d908bd40881dda948a571f4.nq.gz
│   ├── 154dfe6d3733b903ec4b200c3aec40bf58820386.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 1ad92e12b179eb1b9fa36a014f8e53da25de8139.nq.gz
│   ├── 1b9f554d589e753a9c76a1076325d056f86e0c01.nq.gz
│   ├── 1c653a79a2a12f28193994440492d969f61d6822.nq.gz
│   ├── 1d3d7b8ae860d46ca165e07d8091d66a9b1ae06f.nq.gz
│   ├── 20ef7b6ebc499f5fbb2b6d946fddf5861cca3915.nq.gz
│   ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
│   ├── 279e1429b57bc4835359dc55e5faab4e7afb77cc.nq.gz
│   ├── 2c046bfd814caef19b04dc66c67a53b8f84ee4f4.nq.gz
│   ├── 3213c5012ca0b942dac335cd9bebda1f726da249.nq.gz
│   ├── 342c6c8b39f1d4aae5b6c4e1c674325d0e4a3bbe.nq.gz
│   ├── 3b7f94ae96999561b0640a208485210867539fc5.nq.gz
│   ├── 3bdd96db2d53a33cfe25c88119c97d5640eacfc8.nq.gz
│   ├── 3d12fe33528d19b8d11daf87ba708227649cef80.nq.gz
│   ├── 3df8d94d1f8e1aa2cc7d151c244ff84ba04241ff.nq.gz
│   ├── 42336da5224381c7e3fb79bf9f48365f67f2915c.nq.gz
│   ├── 44739305db1cff8ab1b33ff0f21c7a6d485407ef.nq.gz
│   ├── 44caf0db036bed15adfe0c6c7155874ebedb8e80.nq.gz
│   ├── 461454b4a7e136b8b3a32d40d92b1049d675e49f.nq.gz
│   ├── 473aed035fb5dde938a942af59ac302e91cca00c.nq.gz
│   ├── 479c5a66db53a6cbf6a9d03f7a070fb7beb9b0a7.nq.gz
│   ├── 4fc288396caf11873e9ba6ec48f2be7b45331322.nq.gz
│   ├── 505a3b1ca2716907d5b292ab90c36df043c42bb6.nq.gz
│   ├── 537df40ea4d4aca80257b647bff58adebcee8688.nq.gz
│   ├── 572a9538b51923008b37055192e3c5b4466bbc09.nq.gz
│   ├── 5eaf77585eb1595949e68c9597839753eee36e97.nq.gz
│   ├── 6bb74373551b4ed91080254db69fdca322e6686c.nq.gz
│   ├── 6d34368c585a357254d324b741b34485422ed77a.nq.gz
│   ├── 7113466506146241cff7b733b58860684a48fe23.nq.gz
│   ├── 735d4ed68c90cd4cf0beadf13d4072e627f5da04.nq.gz
│   ├── 74b255f4bb6d86a7e72eba50815870766e4ca3e8.nq.gz
│   ├── 78dd0aff3c95cf09926f857cdc8386537eb718b8.nq.gz
│   ├── 79c1fa78099f21c77566c863dd5581b85a829897.nq.gz
│   ├── 7a64eddf12344d6a184c0ecf2ac9df525ea0678c.nq.gz
│   ├── 7d5f8a551c50ea670e478ac1c858f53a57bb98e8.nq.gz
│   ├── 7dbdb729db5fc31b4bdc2c33d7a223d1bdba2893.nq.gz
│   ├── 7e151a0af1807103f8593759f48a64120f7fcb73.nq.gz
│   ├── 80c2bd06d567cbf9da41936e603a7f2a5e96680d.nq.gz
│   ├── 89704ab7b31e77be81a40fa83b19c35d2e9c53fa.nq.gz
│   ├── 89cda487b2e307719a652496c46bde364ae7c1c3.nq.gz
│   ├── 8d3514ccc092e68183d1e1e2d4a7a8f72b2e9183.nq.gz
│   ├── 8df04c4327050ee29e5b351b723229c8e6baf366.nq.gz
│   ├── 8f25c206180c3ab49cbc75dc3470fad7755bd834.nq.gz
│   ├── 94b7feddc8eeb63e73613727e04ae05d9a22dcf4.nq.gz
│   ├── 959ebc6247d121a879394fe2d8d83f21557578aa.nq.gz
│   ├── 9789f1a4d902fb2147845892c8d20ae6faa6af24.nq.gz
│   ├── 988b28b59de37eef795887d085dcd340f7afef50.nq.gz
│   ├── 99a5ea16d8fc5c161173d4ab9bcec3a5237d94a4.nq.gz
│   ├── a6ea6a1cd2666127cf3560dfc493a78508d370b8.nq.gz
│   ├── a8bb5c7a53671fb3cf2beccf19ddf35a56dc2652.nq.gz
│   ├── aa9d1ae32af910e38044443dea580950960c27bc.nq.gz
│   ├── b2b985f178c24738901b49eb34ed2c96b8315e51.nq.gz
│   ├── b4e86584f002dfc0ffe144f6296e3ce1caf871b5.nq.gz
│   ├── b7ceebab4348676203f4a32e06a82ad8e3518610.nq.gz
│   ├── b8601248ed9d14ff117e9c50442b1c87be2552ee.nq.gz
│   ├── b90e8408b08652b1bf7ad14549654444d5792025.nq.gz
│   ├── b9470778764f72c5257a3361590d2994547f90e1.nq.gz
│   ├── bb20a465a99c80cef8276537551c89ad0e9de8d0.nq.gz
│   ├── bffb89dd6f44ab4673823d702a6e0e92593206f6.nq.gz
│   ├── c7f7714bc1552a307d77d1dde20b9a5202e5a7f3.nq.gz
│   ├── c9aa13cc1f66c0a5d630bdb72346646ec12264ea.nq.gz
│   ├── ce0240f027d71c7c0de1a7b5d467677df7ea3f44.nq.gz
│   ├── d07cf1765f0aafd64681a9410b5ccde458119103.nq.gz
│   ├── d0bdca126c22e13b81b78d770ef44260818278a6.nq.gz
│   ├── d79b146d763054fff9d74b7f256e8846e806ee26.nq.gz
│   ├── da059c871153ddc05e98c58a1261146964e7e7dd.nq.gz
│   ├── df782fae7b113f1b0017eac7d21df741b937b1d0.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e847872f8667935e50bd424d07f03337ed914452.nq.gz
│   ├── e8f0352a177f6608addf41d5b7e9f8cc5e5ddb5f.nq.gz
│   ├── ea8c4bf7f35f6f77f75d92ad8ce8349f6e81ddba.nq.gz
│   ├── ecb0c57ca24d4bf0c2581c553f0d57d58d4a4d93.nq.gz
│   ├── edbb144ae469fbdf8013729d6c505a0b343b6caf.nq.gz
│   ├── f0c7ccab84d1863f336a046bc3e561942850b358.nq.gz
│   ├── f5212bd16ceef535fca12afea7f8c5e7fbcc3ebb.nq.gz
│   ├── f5bb524a0fb5e45ab33d2564c639941dbfeb11ff.nq.gz
│   ├── f65879be5f8233093b8d25d8fa14c0600596c7fc.nq.gz
│   ├── f73a9b9828f903aadeb5241a51238e50753bc7fc.nq.gz
│   ├── f760cd7e6a1085a1f61a8b74447bfa3a97d2bd48.nq.gz
│   └── fbadd2c4d5d047be5cd28d875dd21c951183c190.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 49b9e1db1ca93c55f320b025a666367de87a9014.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 96 files
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

[zarr-developers/ndsel](https://github.com/zarr-developers/ndsel)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
