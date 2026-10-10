# Repolex Knowledge Graph of aio-libs/aiomonitor

RDF knowledge graph data for [aio-libs/aiomonitor](https://github.com/aio-libs/aiomonitor), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiomonitor
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 73de9b00b2b7671237120328b45c39374b0810d0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 73de9b00b2b7671237120328b45c39374b0810d0
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a7b00c94e08b86c765d47689b6523148c46eec.nq.gz
│   ├── 033b709ed48fa7e361b2fe28e57745da1da3e41f.nq.gz
│   ├── 04e5b04084f21edb8e046b882213a666cfc981b1.nq.gz
│   ├── 0598c87a239b63d4852b6f65738f3ab5a1b64eac.nq.gz
│   ├── 079c6dfbc1f9f2f73fe9b59461a6bfaca4dcf43a.nq.gz
│   ├── 09109f027ec50fa8145797c9861a1addc798a63c.nq.gz
│   ├── 103c9491c92b94d140b9b4571bb60733230218a0.nq.gz
│   ├── 1a513f321e1823d68c00a9f3cb9777eed603582f.nq.gz
│   ├── 1cb19dc22da8eb4a2a4bb80bf0af5d936c607a64.nq.gz
│   ├── 1d1633903ab1ab39e90c0368449d8c605ad8a57d.nq.gz
│   ├── 1dab00fbd02c62c2ee0e48601f44b702d8d4cfe6.nq.gz
│   ├── 24c17c9b130c85e5efdb2eefb2abd74ec268d2d5.nq.gz
│   ├── 2572abcba8e8de9de5551417f953562926d449b0.nq.gz
│   ├── 2713008395ed68a5e4812f9f237baca6328cd151.nq.gz
│   ├── 29f788d31730f6b4d8485c08b147d170e584567d.nq.gz
│   ├── 2a02aea1b09a278c12a917c7e6c222b9c8c278c9.nq.gz
│   ├── 2f4c80e307508cb30bd6635716963f88f6796738.nq.gz
│   ├── 3302cbcce38e9cb469a9ab51f0766a109715b26b.nq.gz
│   ├── 35285754b0fd375d407dc7844d59a67e660b7a15.nq.gz
│   ├── 36a3edc36a310f02dbaaf8d9641cfa857c8e9d18.nq.gz
│   ├── 3adb374ec69c75f00bc59b189bab7ab823c7aa5d.nq.gz
│   ├── 40de7f6b902d81f7c0495f70e351b968c19fe74a.nq.gz
│   ├── 4bcec02ae09822b5d7f71255d12f094bbd373710.nq.gz
│   ├── 4f4038f5de283b78e3772db168804ebc2c986c79.nq.gz
│   ├── 4ff1bf9d5f2234bf41fd008f431c2e38f9ace9bd.nq.gz
│   ├── 5a2ad70d1ceae9c8e73c1715638188275ea5ec87.nq.gz
│   ├── 62f74e0c67c0129bef6e847812010483f1336fc2.nq.gz
│   ├── 62fac4d632620f0f407d7dbf76c3d36d14468b45.nq.gz
│   ├── 676ada9cfb9ac26bfe894a43ae7e83b44f43a4ac.nq.gz
│   ├── 682fc6a75d2e06bb8c89b7f9a98c0ffa4171adec.nq.gz
│   ├── 689c94aec6dc054d4da8df0d4fb0bba752e73f31.nq.gz
│   ├── 68bf02c49f131e9434b18175116f2a39e2d25059.nq.gz
│   ├── 6b40cb28c19161cf54867f63d235d49950939bf7.nq.gz
│   ├── 6cb035fce7522974da56c0850c852918681e41ad.nq.gz
│   ├── 723c664da3ecf4f6bb8fc6fb844cbad3fec31f16.nq.gz
│   ├── 73c4f3687649b03960dec65d8f045281177fc539.nq.gz
│   ├── 74274309156af334e3a0ba13c4345e9880132c1e.nq.gz
│   ├── 763b6d4b95c318e07a6b22886437e83022548632.nq.gz
│   ├── 767ec48277fd03989024ade04c7715dedb30e1da.nq.gz
│   ├── 7c4938b57afd0304a6f398921d52bf8e5527ae01.nq.gz
│   ├── 806907f3acb1111719a25b2a242c5f5ce5b5a44e.nq.gz
│   ├── 87082b719d50ec267326ea9d2f277a6bd4a347d1.nq.gz
│   ├── 876dcd084342f82ff4ace05ab92d5f8a1ae2f1bf.nq.gz
│   ├── 8fb235d7045be0330d94bcb3abd2ac43badaa197.nq.gz
│   ├── 949b5bec472fe7c26e1e6065f9e636d28e48c108.nq.gz
│   ├── 965abfe891e3f346140fd808c32256e4598ec800.nq.gz
│   ├── 966965eff8295963347a8b729fadccd814bf0ed3.nq.gz
│   ├── 96aa83dc142d261105b1e3f78cf5617090b7c823.nq.gz
│   ├── 989fceba0e10cead9cae16b542f245deef6b4508.nq.gz
│   ├── 9d47d270e03460fec77d6490a88b7b6185594d16.nq.gz
│   ├── 9ef832d2e52e081b17c6bfb555ca98d1d1876361.nq.gz
│   ├── a5bd441963a34727b93d80959e1a485bb35ed738.nq.gz
│   ├── a69fd22b634aacd9c3c64d7e47bdf0dbf6b4f3b0.nq.gz
│   ├── afcebbbe890ce725109a4529291422d3eaea98fe.nq.gz
│   ├── b5ff331144599586798ac9255434f503c7a6ca26.nq.gz
│   ├── bd5e8fb22450d48b4141a5b458de775458119a0b.nq.gz
│   ├── bd82d36c2f62048e9ace771653f46bd2f564ef46.nq.gz
│   ├── c683629250f7e8426dd28f3220141e5753dfaa4e.nq.gz
│   ├── cd4fc96dc298eb5cca6fb47e4b86c78ff6b11d24.nq.gz
│   ├── ce0d8109e3c5ee8f24eed27409106a1f8f8c0edf.nq.gz
│   ├── d11a766730982f6ed7470def089252cb067c00a1.nq.gz
│   ├── d76c4ebbfef1192bd48ef2f7b37ede00023d76c2.nq.gz
│   ├── d79de5df4d6eae3f79ee9a53f98cb9f799f33260.nq.gz
│   ├── df688f7c5635a8e85b7adedb9c81c5a9afd0a46c.nq.gz
│   ├── dfcf9d6aa3fd00e60ff8d68a72b75098fde26dc3.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e911706b1d055bc1a73e32e980c58b50d78bd74f.nq.gz
│   ├── e972736fd866198abd2fcd5b0c0e857f0106b713.nq.gz
│   ├── ee743aa1f5dedd3e16e95a78bb26162ee56f77a8.nq.gz
│   ├── f2f47db7ffc93b35f2c70ed389f9f82d47b8f31a.nq.gz
│   ├── f9f921081f44c537f021caec20a534e0dbfa0e1c.nq.gz
│   ├── fbf08a668f8dcff4ca2b7977bf37f4b1c7269933.nq.gz
│   └── fe1c1e88424f633b16f827867e7cdb037c5c1241.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 73de9b00b2b7671237120328b45c39374b0810d0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 82 files
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

[aio-libs/aiomonitor](https://github.com/aio-libs/aiomonitor)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
