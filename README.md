# Repolex Knowledge Graph of jazzband/Watson

RDF knowledge graph data for [jazzband/Watson](https://github.com/jazzband/Watson), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/Watson
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d9de4fcf3ab74f981c92c7391f4f6887971b9707
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d9de4fcf3ab74f981c92c7391f4f6887971b9707
│           └── chunk-001.nq.gz
├── blob
│   ├── 008b16d39ad2ea52f86b571f4d1b21e36a48d0e8.nq.gz
│   ├── 03133930e447d764cc049d5877db2dfeae0ed552.nq.gz
│   ├── 037157e414909a033aa0d08383afcf2941c81243.nq.gz
│   ├── 04a84cb1236375a6026939812f828925f0238a26.nq.gz
│   ├── 0b297938083da361a931f6198e821ce70875ba5a.nq.gz
│   ├── 0d6e3a8d6287078a8943a97ebd514c291b18a905.nq.gz
│   ├── 0e305f8c7f772297aa8916366368dce0ff933771.nq.gz
│   ├── 0e511578b8d182dc72edb15741240b121e6f6d70.nq.gz
│   ├── 1273bda34ec31cd5c20f488796955ab280346d09.nq.gz
│   ├── 1a42bdd7641bc2b777981ac0e10bf213a002f897.nq.gz
│   ├── 1f64fcfc4a04414084cf5380c4791e1cfc426d0a.nq.gz
│   ├── 22e16370e9800d9dbfb1dacda32e77e7e01673ec.nq.gz
│   ├── 277ccae52d921093fe1ff9c51fda73818e05134c.nq.gz
│   ├── 2c5f80ea568e272b950478ea8521442bec69255a.nq.gz
│   ├── 3594054cc509ab6346e59be3429997582b3fe883.nq.gz
│   ├── 377b76b5c2ab8368a548710d8113975e4b81b5d2.nq.gz
│   ├── 387639f13bbf451e979283c86339369f949bb2bf.nq.gz
│   ├── 3b51437ec610ba410ba481fcf3a98249d8779be5.nq.gz
│   ├── 3df98730cf5acfe149483cfbd8c1be454d8d22c7.nq.gz
│   ├── 3f22278c9b9d4a8dda5b0d1848e755f69c21a9b8.nq.gz
│   ├── 41ea6bdc18ec04dee7f326d4fdb82952ded21464.nq.gz
│   ├── 4652d61fb4ac9f8ada65ecdd489e954f6f8a0b37.nq.gz
│   ├── 4b859d1ae94fb7c696c2da2f0898e874eb64797c.nq.gz
│   ├── 4c22740715c49ef9aa7f78cfb401c92fea8cfeeb.nq.gz
│   ├── 5abd553520d71b29ede7de6cb278bd03dc69864d.nq.gz
│   ├── 5c283171b54cfad52d6665f6eaf40329f8e18676.nq.gz
│   ├── 5e709e5db38da14933c68fd2612752c8c42abe3c.nq.gz
│   ├── 622be6ee06731aa7c3df560abe915d921ef5c78e.nq.gz
│   ├── 65ad9b79e8a4b9f96e8cdfc4e8e3b345ba155fae.nq.gz
│   ├── 6b394cec78e2d43901ae607808399d95366039b1.nq.gz
│   ├── 6c675b3c46e701f1d7b491312c3a669e141a903c.nq.gz
│   ├── 6f21a4bfab01067ffc5b7e9a13a8d150c0a8c462.nq.gz
│   ├── 79902d9afcdbe4acb2a246624bffbec480b15652.nq.gz
│   ├── 7ab7da126d308f1f55b39b6fd1c5972659ca05bf.nq.gz
│   ├── 7b408dd963eba8c48e6efbf61ca1d770855ef007.nq.gz
│   ├── 7ee07e294cd3292b834531d0fff8dbd234d810e4.nq.gz
│   ├── 88bee9a6d67ad68f22dd1ae148bc3e67fb34230f.nq.gz
│   ├── 8a1648264b50d33bca81719fdce0a406037d02fb.nq.gz
│   ├── 8bdb04ed85ad4fe02ea9abb5e3f4dadbe4bb9584.nq.gz
│   ├── 9152b69f960cca89b3ae3e760478496ad412272e.nq.gz
│   ├── aed23085da6049c137ea76dd3634aac35c25618c.nq.gz
│   ├── b3c8427058fda5fbec7a3bc7f63f2103f79ca56d.nq.gz
│   ├── b44ee17207ae563462866c68a4ed18551480dfb6.nq.gz
│   ├── b993767fd661a8a349ba73a628d131fcd21a4b21.nq.gz
│   ├── bd3d61f8e96cfddade931c28bec50069dddd5389.nq.gz
│   ├── bdc4d8dfa5952b9502266a307d848d5ca32abd27.nq.gz
│   ├── be163b8fa2b1eb6b7bc387d19759811d01a4b78e.nq.gz
│   ├── c276860d2491fe5643e8e943716e4ad7b15260af.nq.gz
│   ├── d29dc96275492d79b0d151ea13f69ece0be4a9e2.nq.gz
│   ├── d490bc1d37d60d2543a9a01ae83d33cb31447283.nq.gz
│   ├── d662cb96dc9140347ab1ae68be9e3c4423a75ad3.nq.gz
│   ├── d9db059d983392ee9e9e049be6e01bbf0104b9ee.nq.gz
│   ├── e2cf7ce34492d8f4f03844527ab441de196fb12f.nq.gz
│   ├── e6daedd908b67d5f482107719fe2f7bea699c2a2.nq.gz
│   ├── e93f9ba31e1027f06b360fa9b1cfd4679f20e9a5.nq.gz
│   ├── f500c5e225f2cf0176198716d70c19ec0ddbb71a.nq.gz
│   ├── f62f58276a8e86473dd05c151ee573050e0a0af9.nq.gz
│   └── fb5b3ad86a08aa2b4f3bfb03df1347be3720a7e2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d9de4fcf3ab74f981c92c7391f4f6887971b9707.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 66 files
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

[jazzband/Watson](https://github.com/jazzband/Watson)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
