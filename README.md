# Repolex Knowledge Graph of PyCQA/pydocstyle

RDF knowledge graph data for [PyCQA/pydocstyle](https://github.com/PyCQA/pydocstyle), parsed by [repolex](https://repolex.ai).

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
rlex download PyCQA/pydocstyle
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8d0cdfc93e86e096bb5753f07dc5c7c373e63837
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8d0cdfc93e86e096bb5753f07dc5c7c373e63837
│           └── chunk-001.nq.gz
├── blob
│   ├── 04ddeb4479f65d277272dae42a0c8a2c094c3300.nq.gz
│   ├── 07257918737cf94731c45766202d676f42f8ca57.nq.gz
│   ├── 1066c789c08373f7202d4c39886f9a9144f0e009.nq.gz
│   ├── 185d331f8a41215d80ff1c54c66b2900c4ffe3e6.nq.gz
│   ├── 1ae054c136b51de1c53d64be8ff4655df4b1b82e.nq.gz
│   ├── 1cbd8ec4c9fe1b1f41fe6cd4d37a6ab90e5156f6.nq.gz
│   ├── 2663a8fcb252d6da50d8610fb3e606d78509f60b.nq.gz
│   ├── 296a9e69636a67894861761a068ff325677b0ab2.nq.gz
│   ├── 301f83c46f117073928a6cbff0f4044dac85537f.nq.gz
│   ├── 34fb1503b0a9c1bbcf16f034f6f1a1bf707963a7.nq.gz
│   ├── 363ea3ff673a0dfb874eacbf591eb3a93f1b41e7.nq.gz
│   ├── 40b0d90a2dad94386f5fca144ac19320f6ffd2b3.nq.gz
│   ├── 46e36562ff7dd1c441ee5873c3f078dd89efcb76.nq.gz
│   ├── 4e9878629820b6f60fbe2ded16949925e43036fc.nq.gz
│   ├── 566a2ac422ec8e5cc8e84b8caab6972f63bf10fc.nq.gz
│   ├── 582c6cdedec4b18349859b16cf36efeff37ec82b.nq.gz
│   ├── 59f10fa15143522bc1b230f9305e939c9ecb120f.nq.gz
│   ├── 5fc95b02c723b12066f2026e0dee42f9c0b53fb6.nq.gz
│   ├── 6253f2430d93190b6e9274caa974889dff188d4b.nq.gz
│   ├── 697c73db964f408364c8079d077821a284f8349d.nq.gz
│   ├── 6be743ef4a1cbd3a9cb20ee66c3613ed5d28cb1a.nq.gz
│   ├── 6f9d6d8ace5a13ae3a40dfff54fba8b67a67ea9f.nq.gz
│   ├── 6ff33f2cea41265b119188919858e05a60b3297a.nq.gz
│   ├── 7359aece3bf056e9d5535bae4b40121948dbd201.nq.gz
│   ├── 7cc0e1b50dd1ff6ec3c932aadb3ac8030a5f341e.nq.gz
│   ├── 7d4683934a124418f7339fea53ce0fcf4556022b.nq.gz
│   ├── 7da556754960730b2b6a2f52f9c5bf3ec40336ae.nq.gz
│   ├── 7e29d1733a9eeaf82366cda9a8ecb171459483e5.nq.gz
│   ├── 8156921aeaf8391636181bddc57ef24e00c39353.nq.gz
│   ├── 846a1c9b3a1d06785f38464f5fe77217f3d5285f.nq.gz
│   ├── 86c74b5c6dc1370a17a477dff496ed0713b2a781.nq.gz
│   ├── 86cbaa481a6310a4e7b397e959b9fbe5dd88464c.nq.gz
│   ├── 87de8a1c3a6423289f52ee9e5ee498b20d905e86.nq.gz
│   ├── 8b0065499d9590e9d008ffa6e05d33414c09cdc6.nq.gz
│   ├── 8ed2f0b54596cadd7ed5e7f1f1255e6e868106ce.nq.gz
│   ├── 95bd0a1043346f0ab15662542c24329437243c90.nq.gz
│   ├── 97ac7a568f4f54b715596b9757487183601204cd.nq.gz
│   ├── 981f292e1ccfcf954d61978c33ab09c9ce40ce3d.nq.gz
│   ├── a15c79f3b81f1ad9ff8572fa31e665cdf6163471.nq.gz
│   ├── a7cb58079cdd015f05e7ef882afb3e9a6e8d8ad1.nq.gz
│   ├── b492c1b7b9e53d6d22c1e8e49e7d1ed28f417f1c.nq.gz
│   ├── b654c228655a36c7359090b9266b4e048fb04753.nq.gz
│   ├── b812fd6540cf289c820d5f39e9f6898fed06d14b.nq.gz
│   ├── bbbc6a41ed131e8a48166770acb58b70b013cd21.nq.gz
│   ├── c23192f91ca600dc77b4f3785c2d57ea8451249b.nq.gz
│   ├── c280a23dc1ea23d9131064e42ecfe125e7e84811.nq.gz
│   ├── c44f000f694bc129e686f5e9df5873d73b07d012.nq.gz
│   ├── c4e3295f4fa1381c3fa14d2bc5bef1c428d94b5d.nq.gz
│   ├── c6b6d1ac1ad8704b242e0e8138200a4614b99c21.nq.gz
│   ├── cb55ee452c09d2377e77501d9e4787b9746b8c67.nq.gz
│   ├── cb73f48ff8e36eba86bea66ee5f07beabf22f245.nq.gz
│   ├── cbde4e595c7dbac62575133f1730d503a019ce53.nq.gz
│   ├── d391d4b0e91a4311380d5aa88c0c94aa64ef96a5.nq.gz
│   ├── d58e5020dc69eca8a986161133567bd145d0782b.nq.gz
│   ├── d6b5fadeee637d218c9bbbff7f5b3ab95692939b.nq.gz
│   ├── d8dcb3b9ebc8b338c088f2f0b4517c4363700474.nq.gz
│   ├── db7b9fabf8015d4181a33c2e3d49aea06abfaa89.nq.gz
│   ├── e01ba6f381c8eae0d19905bd571449c3680d9051.nq.gz
│   ├── e3d5d8cbae45ccb963d934f064bb7d748feb99b8.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7a7dcc314aec4e9532000de636a8c5355ff72e0.nq.gz
│   ├── ea25ba623e7b3f9f3f89239bc4e30f677f792384.nq.gz
│   ├── ebe90734f46348d41afc16d880423c007defd260.nq.gz
│   ├── f0732b3790878e95404ba9b3b18ca53a5069660d.nq.gz
│   ├── f0aa466e0241e506c21067be7850a7d804acd9ca.nq.gz
│   ├── f131e16acf5d32b67018d058c4165ebabd46992c.nq.gz
│   ├── f236d68b6817fcb7f926a470c14dd7c3924de637.nq.gz
│   ├── f239d1c19eb9bcf3ba5830bb63471aafda0edd02.nq.gz
│   ├── f35135f2580fecd7f533a2c58362945162e8878b.nq.gz
│   ├── f3b4a4c64932dd739eb255182c24cc6d636d3ce9.nq.gz
│   ├── f54d678a97115003a48012d34a04d686f1a5dd25.nq.gz
│   └── f8b43117edfbe63b66fba00dddf2ca53597912e4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8d0cdfc93e86e096bb5753f07dc5c7c373e63837.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 80 files
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

[PyCQA/pydocstyle](https://github.com/PyCQA/pydocstyle)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
