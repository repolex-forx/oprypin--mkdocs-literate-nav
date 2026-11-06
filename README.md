# Repolex Knowledge Graph of oprypin/mkdocs-literate-nav

RDF knowledge graph data for [oprypin/mkdocs-literate-nav](https://github.com/oprypin/mkdocs-literate-nav), parsed by [repolex](https://repolex.ai).

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
rlex download oprypin/mkdocs-literate-nav
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b15147038b68f56bf7894549062d6bb4985223a1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b15147038b68f56bf7894549062d6bb4985223a1
│           └── chunk-001.nq.gz
├── blob
│   ├── 003dffdce8c72acf117ad72c7c9044dec5064f67.nq.gz
│   ├── 0aba43968eb9212cfb6767e8aa3ba756962e4569.nq.gz
│   ├── 16800de1c44d36db1e8ee0e22a60ea17dce2d32e.nq.gz
│   ├── 1d1232fc061bb08aa1bbbf221a85a776779bfbb8.nq.gz
│   ├── 1d290bf9c553d65920b23be3f40da6ae00eacb16.nq.gz
│   ├── 1f68e82511e62aa088dc7a5e5221fb5ca8bf49ad.nq.gz
│   ├── 2245bdc5c7271b51d39c996cd5560665dc7b99e6.nq.gz
│   ├── 231435582e8322438fd7428b615876c68bab351d.nq.gz
│   ├── 2374dd75f06a880a4e315e3669dab13630813b6f.nq.gz
│   ├── 23aacacbf009c23cd67f41d785aef154f4e9ad8d.nq.gz
│   ├── 255f3d4bfa620772412006ae4de925ef1345b0e9.nq.gz
│   ├── 26d4303182749c3f1da438b25e7f1ff494fa9ec3.nq.gz
│   ├── 295f18503d06f8bf16c7cd7ff869e12ffe409202.nq.gz
│   ├── 29c1345c47f3229eed6d15b56cac33555089b35a.nq.gz
│   ├── 2ef787c331d19a92bbb0b3fa99b02c6968572f08.nq.gz
│   ├── 392e294ed1b4f6bceb451e743cdb34ef84288c01.nq.gz
│   ├── 3ad5a6656a22ba1ead7804db68928716fcfc6541.nq.gz
│   ├── 3cd2517849187c94b0e26237e5db77934b241a3d.nq.gz
│   ├── 3d092a56709dad1a35b136ce3b199c51c2ab8830.nq.gz
│   ├── 3f0631cf61194ad0f017060a705a9f4a9af8423a.nq.gz
│   ├── 4150d712260e995bdf8905ef4f951befd708229b.nq.gz
│   ├── 41d98a78a6bc5b260b63abbc9bfb18d6b72a17a6.nq.gz
│   ├── 437b4a31b320741c282dd03de22dac532583683b.nq.gz
│   ├── 537a0fa46014cd8cbce3195fc2ccad2c67ef6f03.nq.gz
│   ├── 568562ccca4cb45a7a0ba3f949edb5e936fcb780.nq.gz
│   ├── 59edbc851bc7aae65ac19e6d4175e5ed3bcd33f6.nq.gz
│   ├── 5a75d854450407e8d585d55db51ecd36d80df222.nq.gz
│   ├── 5ce9dc18c15d48760b9da8d094fe080c4867cb24.nq.gz
│   ├── 5d0c9a8972f3e3a2c53dbf2db9047ee494658f2d.nq.gz
│   ├── 5dfa3988c9ff0fb9bcdfb7baef29027dabe71c8c.nq.gz
│   ├── 5f47cc4fb979aa4d75b89b767f2dc1bb4ed69cc2.nq.gz
│   ├── 612c7a5e0d17657e51018285d9850b8fa8e76174.nq.gz
│   ├── 63af88769b0100b52aa69009748553004623fd03.nq.gz
│   ├── 6616dfbf4c0995e3fd87cf4bdd2f61d1b7135121.nq.gz
│   ├── 67801c626c02ef194c04e12a6d3e01847f2a8004.nq.gz
│   ├── 6885f43792c18e2a16fc84eabccd9cd2ba579032.nq.gz
│   ├── 6a48594a166a6a9b3c696df5f14f7580139f0c43.nq.gz
│   ├── 6fe12891c95cb3daed6995f503f04b14bab1befc.nq.gz
│   ├── 764d98d09fd64c945d6216f67e79760f004a10e2.nq.gz
│   ├── 7b287096c68c3df91df42bae5984c16ab940af5d.nq.gz
│   ├── 7c317f2ab3c046d83d14f52cd4412d03641db624.nq.gz
│   ├── 7f095bb03cddff053969b4116c1a0120b6864dc0.nq.gz
│   ├── 82a7e70732182b2e203d63b8485d44deaaeff4dc.nq.gz
│   ├── 82da27c3110716b339eb8c94e62c622fe673cb36.nq.gz
│   ├── 91f44fa3c59c3f17dbf679c70efee7f578720a4e.nq.gz
│   ├── 92edb4000704f1f92e66e9c6fe738f01674cddcb.nq.gz
│   ├── 94535a1d65702edebd81ccda55624280b87a959b.nq.gz
│   ├── 96a1cec44a7ff2a72050d7b949d019939c356492.nq.gz
│   ├── 9875998a06cafa892c7f17c9bd5622cde148d14b.nq.gz
│   ├── 9e59e9bc78cb6658d9c7aeeb2629b7691dc25e73.nq.gz
│   ├── 9fee4dac128ac7d2068e5173cdfd26f3c6a1ca2b.nq.gz
│   ├── a327e034713594736fa6f9ee9644af5c26db3f84.nq.gz
│   ├── a6c51bd585d308e43456824264c3f3fc12ee0210.nq.gz
│   ├── a6f5866be477b9eb1a4be0ee9ef98c553148cca2.nq.gz
│   ├── a904bbcc1545e299e8906cb84f3d1226b63230bf.nq.gz
│   ├── b1a0a02549f91996f426ed53b9fdc75c2e48c23e.nq.gz
│   ├── b69fb37e7ca9414ad28f4097484a36620a922550.nq.gz
│   ├── bad88c1160ef78085a3e09efbecc7d4c7fe02d3c.nq.gz
│   ├── bba2bd653812dcd5f357b8a61a7d2e7877827392.nq.gz
│   ├── c56a786984c83fa06e285f0372094023555ed806.nq.gz
│   ├── c8ff618e524e5f7e653669075d17e64f03d7d134.nq.gz
│   ├── ce8dc483105cbf21435e88b2b620deff53dea80d.nq.gz
│   ├── cf9bd8751b276722e9e6f6f5363766ec5b45f7d7.nq.gz
│   ├── d0d23352ea08c8e31b465da4e9f270458d6d52bf.nq.gz
│   ├── d753874048e4043f8aa37eae4c39458416895360.nq.gz
│   ├── d947e110c86ec04a6b1b7e67af18ddae9f8a2370.nq.gz
│   ├── def16e60145727991eb78874016b62e7fbebb7cc.nq.gz
│   ├── df9054014cc84b9919dad02c31b1dfd51c603c58.nq.gz
│   ├── e3a47ba0ee7bfe2300433f740430e8631c897e02.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea4ccede51cc6b1e7dce082248e57fcb4b1a3a9c.nq.gz
│   ├── ec9eeaa9841534a0719b66de494c06946983a69c.nq.gz
│   ├── ef57663991b4abc0cfd93da92a053b71a04b356e.nq.gz
│   ├── ef5fabbb4da550a7b40fd82a6cb3b3ac950cf3fe.nq.gz
│   ├── f6a638abe97823a3b84c6247ce92d609158f0501.nq.gz
│   ├── fa7367201ead6678fc64fbed416337a473a3fb1e.nq.gz
│   ├── fde455f4ae811f64049b7b34683636e29df0bed9.nq.gz
│   └── ff541b1a4ce30183a788d3d5b71de17b13999758.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b15147038b68f56bf7894549062d6bb4985223a1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 86 files
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

[oprypin/mkdocs-literate-nav](https://github.com/oprypin/mkdocs-literate-nav)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
