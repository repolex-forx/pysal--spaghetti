# Repolex Knowledge Graph of pysal/spaghetti

RDF knowledge graph data for [pysal/spaghetti](https://github.com/pysal/spaghetti), parsed by [repolex](https://repolex.ai).

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
rlex download pysal/spaghetti
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9ae829b45c8aa15ddbf33c7a1fe574e3524dfbbb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9ae829b45c8aa15ddbf33c7a1fe574e3524dfbbb
│           └── chunk-001.nq.gz
├── blob
│   ├── 04500dc493ef0e968f1cb31ca2db22f5b925c8cb.nq.gz
│   ├── 057674ddc660eb2c331dc95cfa783e29adc33546.nq.gz
│   ├── 06278021dddc868c617f29286e566f6bb2a6fbf6.nq.gz
│   ├── 08246ef5404aa3e980d3992a58d1c5bd7c539fcf.nq.gz
│   ├── 0bce9156a839438a91b77de84661619c71176508.nq.gz
│   ├── 0fb944be33f04b697175a45b93a7da35316d8dab.nq.gz
│   ├── 1117ea6c412bfc3580d57e93b1793d1622fbc80e.nq.gz
│   ├── 15480ff3c5d9cc76a765bedeff761b11e6922cb9.nq.gz
│   ├── 1aaccdcbb99f0327fb5261f1875fc40bc7518922.nq.gz
│   ├── 2906aa0d3d2fcba73d3004cb9e6ff1c1b66a8450.nq.gz
│   ├── 2f1b5306018476930d601cac0fbb54091c2411e6.nq.gz
│   ├── 32f043faaa8232628f3ca8681195dec9cff96934.nq.gz
│   ├── 37d49b7c0ca4ce8d63cc4ce43781b466f5329271.nq.gz
│   ├── 3c08b6bc63398af26781ba71745245a4f02fe150.nq.gz
│   ├── 4bfb7149fb55b44a17196014f4c20519b5c744df.nq.gz
│   ├── 500eeaee914d4fcef7c73136f5037e0592dbbe8b.nq.gz
│   ├── 52f280fe9bb3522fb89631d732a7549008b0f336.nq.gz
│   ├── 559ece34285d7042a5d70892d5dc7ee95a370e02.nq.gz
│   ├── 57fa59b44b47c23808ffaca4ac3d3bd78312eaf4.nq.gz
│   ├── 5992542bd86ba523c0c5a66366e0e4d3dcaef21d.nq.gz
│   ├── 5b7fb903178b2bc0125fc8a722c2f0929fd4143e.nq.gz
│   ├── 5ffe519ed7b3e88b8be181f97fcdd98c9edaae3d.nq.gz
│   ├── 62566ca9ab8d06fa1127902c271711f407f31e6f.nq.gz
│   ├── 696283b7d52cea7ec812c2c174cb8c5ee123eb0b.nq.gz
│   ├── 6ce42f73d6de79ef61743344e6704fe7e71aec67.nq.gz
│   ├── 71e4aec1f14bcc5f017f6918242ee4b60ad14d7c.nq.gz
│   ├── 7a5db4d7c80d8d92d280b66b38e4af427bab7c61.nq.gz
│   ├── 7ad012ba8a369fada6d71e5a6907115569407e9a.nq.gz
│   ├── 7d9fda959bc6976ffb2676473bde74b734d4e011.nq.gz
│   ├── 8370f5df78ab4d366509f0dfcbe723e60abf3a8f.nq.gz
│   ├── 8d1c8b69c3fce7bea45c73efd06983e3c419a92f.nq.gz
│   ├── 8ff5f4c8627fbada3d8fa04273ff7a2fd2f3c5e3.nq.gz
│   ├── 940cd60e872800d57c88d18b18a698c0f732f2fa.nq.gz
│   ├── 97ece83b9ba264154015e074b47318a600e101ba.nq.gz
│   ├── 98a6a413041d856a5e118344a7b4113d81b9f1cf.nq.gz
│   ├── 9d7988821c5b96999abd6ddbac098ef86eec8a63.nq.gz
│   ├── 9f0d535ea0d662b2afedcfab7ac55016ffb9129f.nq.gz
│   ├── a0591db7543567b8867b7afab9de5a97b37647bf.nq.gz
│   ├── a05dae9acf383ab57b0e7f1422b37a4372954d07.nq.gz
│   ├── a1d18c549b24a057a7959918ed9b305365cd5eb3.nq.gz
│   ├── a246c92d76cea55c3d8f142d2b6f6ea0e5d66f55.nq.gz
│   ├── a3a6f0ee2b72de6b455b59a90f44cb800db3acea.nq.gz
│   ├── a4cf8dbb3d80aa97a6fbbb70a8c256a62b1cd08c.nq.gz
│   ├── a5905322800bc92bc0f4a9ca1256c0ca045105bb.nq.gz
│   ├── a67bfc5f8cb7cfae45455b8c966c8bae161d16f0.nq.gz
│   ├── a79ddc620dc69ad5bbac23ec678c3acab1ba1fa5.nq.gz
│   ├── b1d4843e395e756aca30a4d8a0627cb69eed7d11.nq.gz
│   ├── b862aaf2d13fbfa181f1df531f71c3bb57d8d901.nq.gz
│   ├── ba31605e554fa46a3e1623efa83536e99d2a8676.nq.gz
│   ├── ba3f53d06e8920d815026e2e3d8fb0c94433d68a.nq.gz
│   ├── ba49c57021cfe8422804f8516c1cea537cd1837b.nq.gz
│   ├── bc449d4759e25f2a082e62b9456dc7bc6d639d8d.nq.gz
│   ├── be17c4717ff2c798270602309c8308b491b88b62.nq.gz
│   ├── c010bbcbaa0607e494316a7b86577707f0bc6091.nq.gz
│   ├── c3418792ea020862be9a6ca12308a077268cfd5d.nq.gz
│   ├── ca02edb6e98b17e70ef7fa7f948120712a9ca04e.nq.gz
│   ├── ce72652ca102a51c3a43a52aad924a51fb5bdea4.nq.gz
│   ├── d0dfa651412924cdc1690a3ceac3111ed36131b1.nq.gz
│   ├── d32b0418eca9f9452d7eeea2d0ab109120968efb.nq.gz
│   ├── d50b9e2a1e64176a80d38038223d5ce8a89618be.nq.gz
│   ├── dece4eedadb28c470d95643a38bc70411e46ec4c.nq.gz
│   ├── dfd3a0629e9851109e55c930379a8e00df7430ab.nq.gz
│   ├── e24360ec10630dac829db538f4c29b2d86424ba2.nq.gz
│   ├── e4ee94b214c7199ce69cc61b5fafda4324b3be50.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e95dcb7ff3bd58261c72e2c9fe098fbe8159f98f.nq.gz
│   ├── f5af44d66109c89fc27b92f8169958ef64b6a11e.nq.gz
│   ├── f6b46ceb549e9f2241c050ea9e90c39085cc3de8.nq.gz
│   ├── fb823d152c8973d04a3f97c927caefcf004476d3.nq.gz
│   └── fc0a32af70e41e6a5a66a7a9ca1256c4d4c0c0c4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9ae829b45c8aa15ddbf33c7a1fe574e3524dfbbb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 78 files
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

[pysal/spaghetti](https://github.com/pysal/spaghetti)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
