# Repolex Knowledge Graph of sphinx-doc/sphinx-intl

RDF knowledge graph data for [sphinx-doc/sphinx-intl](https://github.com/sphinx-doc/sphinx-intl), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-doc/sphinx-intl
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1e9e8e9835921b6fa0392a6aaa0dbb56bb54788f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1e9e8e9835921b6fa0392a6aaa0dbb56bb54788f
│           └── chunk-001.nq.gz
├── blob
│   ├── 14520d3c8cc7d5b6bab7d78edd6841398bda0d79.nq.gz
│   ├── 1befc1935fd429faed4778fc6db1ba52830dcf64.nq.gz
│   ├── 21ad7021e21e0e3beebc0a090b7f3c5184278782.nq.gz
│   ├── 260f8ec5c837d160b4198fc912eeaca83f1f7661.nq.gz
│   ├── 274676bf77b7df2b0812e2b121f428ebe8836576.nq.gz
│   ├── 2ac218e04a13fbf6d9379417282df2cad94d664b.nq.gz
│   ├── 36dde003e6867008e1a5fe62da998af4d88b5bd4.nq.gz
│   ├── 3e1e18b35f93e754e651cf9d947fc07fba4fab7f.nq.gz
│   ├── 413dddcadf3d2b481e48e1806741b8b8f7e1dcfe.nq.gz
│   ├── 484754b71a80c30eb4375c659f7d06efe7a3f6e9.nq.gz
│   ├── 4b2694c14840e44624953b3f93381cdedffd666d.nq.gz
│   ├── 513d08ac93918f8016eab4a3a4a3b86978d280be.nq.gz
│   ├── 52f04b586adef88d7a58ae3941bc1cb5600878d3.nq.gz
│   ├── 5382febf70b465abbc1d294f6e5f411e6327e606.nq.gz
│   ├── 54d3f27aaab837ea32bfede0ce6d9ac0d1847e81.nq.gz
│   ├── 5df33b8df9205476dab259fe947a9495cd99f415.nq.gz
│   ├── 62e999af9e6a63043da4ce5b7f0145b1d6aac741.nq.gz
│   ├── 66ef1649e120ccd1760dfb3959bd7616eefc8a0d.nq.gz
│   ├── 6ad2a0e30ced5289d8e95c0c07e5f3068e19b941.nq.gz
│   ├── 6b12a25a717c50dbec6b3cb04aefd01d2a412cf2.nq.gz
│   ├── 6d438d7667766ae538cc88072a23b8f97c6a1a01.nq.gz
│   ├── 7344a6d1cd7f7611702cf3db373aa20e808204d2.nq.gz
│   ├── 74d214dcd8e440be312d2c5c3d7872691fbcb188.nq.gz
│   ├── 83ff2fdd83fcb3a6a360e74a5ca00eb738fab505.nq.gz
│   ├── 8d39a7c9e169e0f787bda7057bd5d1fe0ed6ff7f.nq.gz
│   ├── 9479c5d6a004cbd3a4bacc382624c03654207867.nq.gz
│   ├── 9a1cfeea58ef4a0037840a190b0537950416d25b.nq.gz
│   ├── 9f4ccf3b99f67652b94dcd90ea58eb83b16f814a.nq.gz
│   ├── a056ecba4beaae7525b136464daf08f09a9abc7b.nq.gz
│   ├── a172be86eba3f5e6698a05ca28fd56aaffddf8e6.nq.gz
│   ├── a2056203caecd5be87da35e2b17bef21c3a5ac0b.nq.gz
│   ├── a369a1b52e1c8f272d4028c9c559f69bc3b37876.nq.gz
│   ├── a52c3cdff230632882a90b4a6207c3a568ec4397.nq.gz
│   ├── a8f9a18bcd285b5f55b716f38e595acaba86decf.nq.gz
│   ├── a9047bfe54a34c1e7d48c20e984cdb6ae636e3b8.nq.gz
│   ├── a94cff0785c7fade91dbc20435c079913dd76822.nq.gz
│   ├── aff1a894a9cad7ebfaf8f858f0de2a300aab18cc.nq.gz
│   ├── b8098854daff8201a073e4eaf9fc0bc38b31fcea.nq.gz
│   ├── c24ca88a1b0473634f55eb0448e7d0aecb0cb2e5.nq.gz
│   ├── c5a418a7574913ea32732b331ba2148f11459d59.nq.gz
│   ├── ced37e1731ac71e52bd201853007ff95c03f59fb.nq.gz
│   ├── e35d8850c9688b1ce82711694692cc574a799396.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e896e384266c13bbb1d707d867759f8dc53c279b.nq.gz
│   ├── ed35667fb81f265e1f4a823abff89300b58c4538.nq.gz
│   ├── f62b542e363b21b87408fbc09e2578d4921bf7c1.nq.gz
│   └── fb3288fc48c9461fd7dbf5f2ec62af19a5f8f6e6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1e9e8e9835921b6fa0392a6aaa0dbb56bb54788f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 55 files
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

[sphinx-doc/sphinx-intl](https://github.com/sphinx-doc/sphinx-intl)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
