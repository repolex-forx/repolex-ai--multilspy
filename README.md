# Repolex Knowledge Graph of repolex-ai/multilspy

RDF knowledge graph data for [repolex-ai/multilspy](https://github.com/repolex-ai/multilspy), parsed by [repolex](https://repolex.ai).

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
lexq download repolex-ai/multilspy
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b07b682bb8912bd485e8608a78595e78425e8c40
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b07b682bb8912bd485e8608a78595e78425e8c40.nq.gz
│   └── repolex
│       └── b07b682bb8912bd485e8608a78595e78425e8c40
│           └── chunk-001.nq.gz
├── blob
│   ├── 00368eedf21931a03b41ef306d32625ad62ec407.nq.gz
│   ├── 00d1e1c2dca203a1a1876ea2c54f51faa185c53f.nq.gz
│   ├── 0932c3a370a248bbe4c9b45c8d752fe9cce8f1ab.nq.gz
│   ├── 0a5f6be714b02952c648869bdc8cf13474317653.nq.gz
│   ├── 0f295a0c0bd01c7dd90b4b2dc3aa5e977130ff2e.nq.gz
│   ├── 148841c3e09033c6ace3dcccb35e956614430f0c.nq.gz
│   ├── 149af3826701daba0b25ed976e756c865601f820.nq.gz
│   ├── 1a95eec6a8412e0282d08912f3acec3b06ac29ad.nq.gz
│   ├── 1d14543b0d3ae170d0591a50fd99ccd7445b56ec.nq.gz
│   ├── 26dfac90a166ebc345b451a940be4fbfcd5e23b7.nq.gz
│   ├── 2cbb41f877e8457faacfadfa722806ac96b23cb6.nq.gz
│   ├── 307f7d43870b357c3ba27dc7ac2a1c0eb8248bd0.nq.gz
│   ├── 38cc2372ddd6e8facbe69943a68fcf12868ec921.nq.gz
│   ├── 3b4ac168197ae3302e6edeb582a330c4b8d3d6cf.nq.gz
│   ├── 40031db43a73adf7e0fc865cdda16375aa4550d4.nq.gz
│   ├── 419763dcab8728a63044d306a8eba70a23e3a336.nq.gz
│   ├── 4330560e982585708a8a7b2e47ff615ac707f269.nq.gz
│   ├── 49b33b1bc588b0f2c61067fc8c43325c0e79aa77.nq.gz
│   ├── 4ff17ccd31e85a9e3782a7de0f75dd4730605e37.nq.gz
│   ├── 5047c70877bc2569a89c4d9391e994f382367766.nq.gz
│   ├── 517d8b87bd774cb716918c34642a6b2b3f8c6caf.nq.gz
│   ├── 59d7ba600463fbc17c49ecfe4fb505bfe0ffb96e.nq.gz
│   ├── 5afd9c059620ae092e3992ffae6de2c64b21a77e.nq.gz
│   ├── 5c4cd523776704a01861173bf9d07de902e00a4a.nq.gz
│   ├── 5d7ebfab6df0ed6e5bc9efb4d982214deb5d965c.nq.gz
│   ├── 5f7c2c0c4ec9eeac8b52da2efea6ee2f20f7b84f.nq.gz
│   ├── 6072cb5dea14c845593db56a86a509b59b1b001d.nq.gz
│   ├── 6209ba47791957ceae267bf8d1ecca723c115215.nq.gz
│   ├── 658e06191e7afb2e61d40813e96e8bfe91f039e8.nq.gz
│   ├── 6c50ccd17a9d2bd73b271f0825f033ff4ab71b7a.nq.gz
│   ├── 70beeee26c41638f649c528a0b0df7561cea105b.nq.gz
│   ├── 74e9f5ceca2578dd88229ab1077f9e4b5f8025b3.nq.gz
│   ├── 76bc1e863f2e6f26e2a727fc430d292691a154c4.nq.gz
│   ├── 78a4017e3506e8f9b5da30d3b136e31bf64e85dd.nq.gz
│   ├── 8010b940f240f3872e63fd2c1bbaa5df93d324ce.nq.gz
│   ├── 832677914cf3ead64296a9530eba651d5a370446.nq.gz
│   ├── 852df21db2e54bda70431d4a63642d181ea4bb78.nq.gz
│   ├── 868f53dff5a5f61470babd2fbcbcbedfd4cf103d.nq.gz
│   ├── 86a89ec6a4ea3a51860bc8e4a0475f866fec6a94.nq.gz
│   ├── 86c6a6c4f2dc80ab2008cfb1e3cf84df7bfa1770.nq.gz
│   ├── 8c83417a829fa44cf03b609356d666baf3c8859c.nq.gz
│   ├── 90824a7c131a6811223706cbd5326f71e9d119c8.nq.gz
│   ├── 98a983209aae7d9a1e10d73ebae9e4f3b3be0c13.nq.gz
│   ├── 98f70b33602b3110d05225abdd9e29f57a05ac32.nq.gz
│   ├── 9a5a6949ef98c9e5bc66d8fee9457b819538547e.nq.gz
│   ├── 9e841e7a26e4eb057b24511e7b92d42b257a80e5.nq.gz
│   ├── a5e53266503ae173f7f214f903e6413112419297.nq.gz
│   ├── a694c96802781e1f43250557d9ace3ddaf19ca20.nq.gz
│   ├── a72b3dd586eb295dda5dfe23553fbc767d892bc3.nq.gz
│   ├── a7b2ec0ac130baa48812d51c2a417024ade0b316.nq.gz
│   ├── a7b64b99c4843865f28903479cdacbb61e7c4771.nq.gz
│   ├── a8229e9fd84faf3da1fd365aa2991c6170bf0443.nq.gz
│   ├── b3c89efc852e22f71eabf5dfbc6ac62493425eb6.nq.gz
│   ├── b43d3631734d061de8fac57f461494e002835b3f.nq.gz
│   ├── b814306430d22cd3ce7c0e86e3e7b4fe9d3854a2.nq.gz
│   ├── bd05b2729a07df3834af5573d790d60e4a6253d1.nq.gz
│   ├── c065c0cd230e0fe2b539d4a0a3a3532a91c07c12.nq.gz
│   ├── c1a2ccc7de8db50614d6b993d716bfb658569389.nq.gz
│   ├── c224c6954e445944d721970c156f1518c549806b.nq.gz
│   ├── c4f570996309f5adbff465c790e00d8b04a6f7e4.nq.gz
│   ├── c7cc3806e812a458c015a04ac5a0aa891cea9a43.nq.gz
│   ├── d0d2a69bcd501a91d0c2d8247db9bd0c172b6122.nq.gz
│   ├── d3fe974087e7aef2b34f8b7c475b37d948a3cdd5.nq.gz
│   ├── d466074b93e359b51a433418339002bf860b21de.nq.gz
│   ├── d49ace2c1105901fcb6dfe7869dbe5cdc11d89af.nq.gz
│   ├── d645d1307934b32be945391096f7c3ddc928f472.nq.gz
│   ├── d7c633780cc369fd5dacf12eaaabc8953961cacd.nq.gz
│   ├── dafa767558e157f6fbac9438b16cd2bbae176472.nq.gz
│   ├── df856bf0a181c2e2f4d47b475ae04c1e0756ef06.nq.gz
│   ├── e13ea9221da89d656bd31e72626b998ed126c3e1.nq.gz
│   ├── e90e408ac006da400ae80eb5ddc335c40e451169.nq.gz
│   ├── ed4bfae638d8d434ed80e3fda10db89f8fe5aaed.nq.gz
│   ├── efb8c6acf0036e91bbf2713a5f3f1814bf9bdd10.nq.gz
│   ├── f89c3343366ca08a7a6acc0fb918dd612b860f97.nq.gz
│   ├── f96239db9fce6bb00b59d4edbb6fc3472fdf8a10.nq.gz
│   ├── f9ba8cf65f3e3104dd061c178066ec8247811f33.nq.gz
│   ├── f9ee86c3bf373fdb86fa6c2495731eb5dacbd0c4.nq.gz
│   └── fde7d3ba50bbfebcc1774cb104bb7db0db052eb3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── b07b682bb8912bd485e8608a78595e78425e8c40.nq.gz
├── filetree
│   └── b07b682bb8912bd485e8608a78595e78425e8c40.nq.gz
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

## Source repository

[repolex-ai/multilspy](https://github.com/repolex-ai/multilspy)

---
*Parsed on 2026-09-05 by [repolex](https://repolex.ai)*
