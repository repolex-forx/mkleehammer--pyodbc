# Repolex Knowledge Graph of mkleehammer/pyodbc

RDF knowledge graph data for [mkleehammer/pyodbc](https://github.com/mkleehammer/pyodbc), parsed by [repolex](https://repolex.ai).

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
lexq download mkleehammer/pyodbc
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7ee5b566984f7bd3d8fcfa0369e9e163e70e1cbd
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 7ee5b566984f7bd3d8fcfa0369e9e163e70e1cbd.nq.gz
│   └── repolex
│       └── 7ee5b566984f7bd3d8fcfa0369e9e163e70e1cbd
│           └── chunk-001.nq.gz
├── blob
│   ├── 0598190c62a1f27272e3ad311caccc54cfb67033.nq.gz
│   ├── 08002453fb9292d589af18c0c812ed44e2fdb36e.nq.gz
│   ├── 089202a8f4dff4c506c923f5bc8f5671e3ef3f30.nq.gz
│   ├── 0fe6405c8108e222e7983f1bb2dc1a9a31e28f09.nq.gz
│   ├── 16314a1ae594ebaa62c98138e6ecfe337f3a3a7a.nq.gz
│   ├── 19214023f3c4da745d62e572e91c1e05da5732bf.nq.gz
│   ├── 1a50d2b51012a41b1135ebd8e09eed5598fec6c3.nq.gz
│   ├── 1acf7ebbb6c70723c8f91c6f5c9ec689b1427f07.nq.gz
│   ├── 1d346afa88e351a37c9ed4618eaa16911b9d4cda.nq.gz
│   ├── 225ce02f80f0d293b61386ea804dd7351aded4ce.nq.gz
│   ├── 256fd95d24e36243e867b61d593750ca398cfd94.nq.gz
│   ├── 275781872ffb6403ee3aada269dde76eda42127f.nq.gz
│   ├── 2c484780fd14fb8916b16c1f0829fa62be0b7caa.nq.gz
│   ├── 2e4e7c76069926dc9bf2ecee0920e45f20278e3c.nq.gz
│   ├── 3008600bf498ae243250c34a8bc3e4bf3a3b545f.nq.gz
│   ├── 31d4ab8f4fc7a1dc53fc44eb90611597411d1eb0.nq.gz
│   ├── 32af7122a727a9d5e882f60ca49949a6e2853b67.nq.gz
│   ├── 37ecedaad612473124f5f94c486c7f81cfe2a3b9.nq.gz
│   ├── 3bcd2e03a54339bf9d2aa8c503c2167c2d9333cd.nq.gz
│   ├── 3cc627ff6c5b6443aaa6ab397249934291ff68ea.nq.gz
│   ├── 405637e33057abfee38c2fe5b6f5d56b371b1de8.nq.gz
│   ├── 458b8cfe6118556606778d80d0a7192ab557ec7f.nq.gz
│   ├── 5498eee887e1dbbf623bc8b8e4648d329b8c64fd.nq.gz
│   ├── 5f06976eb8f69eea6dd9f0113f74b5b89e50f718.nq.gz
│   ├── 657eb48305491208440c20258f66b4b34ae1d601.nq.gz
│   ├── 697a2f8936f08558698eb14f13ba09351d6f78c2.nq.gz
│   ├── 6a41706265b833f5833fdeac00b3a860f421546a.nq.gz
│   ├── 6a4b0ffdc2837d690bd26ad046a663cc09d2bbb4.nq.gz
│   ├── 6cc230b823728b14c470f659daa1c60e6e4cc94b.nq.gz
│   ├── 6dc32e2e7a0c82e50bb3c42fda9d9cd8a769d5d5.nq.gz
│   ├── 725265f0249b242bab6897d046e3d310e21d1fe2.nq.gz
│   ├── 7dcdba334fda93518bfc6111db41093e5dd04a8a.nq.gz
│   ├── 7f0343291f214951abd8d9cf15c92d3e5a70ae37.nq.gz
│   ├── 7f46fc2c0e3acd7d8df99a8e9524500e0bdafd56.nq.gz
│   ├── 8807a0de2383544b885b0c3301bff757dc440115.nq.gz
│   ├── 95cc8ae5023403f25cb315a9f886fa5eee333d8a.nq.gz
│   ├── 963f0f39db711bf6c27ff53b6c4fe08d1555f763.nq.gz
│   ├── 96c794b55af7065251a7840f958b494f1f8abd73.nq.gz
│   ├── 9e42e4c8783d5105b327a0c8e84ae3b1fc04e194.nq.gz
│   ├── 9f18a036c100a8e6fede7d1228a049553e20d8cb.nq.gz
│   ├── 9fd92a51a8a1591836a06b54ac7c8a2d93d5be2d.nq.gz
│   ├── a629c7e6ca4ba44fce9befffb246fd3476b840a7.nq.gz
│   ├── ab51ce0d4267c7c5f7d5279a4a5ad5923c78b946.nq.gz
│   ├── b38020855c1122712f27165df5ff7da5f16b4903.nq.gz
│   ├── b97389f232a3ef7013be5e29da32ddf0bf3cf9c2.nq.gz
│   ├── bdbfadeec0f58020e9d8a9e01571228653de0719.nq.gz
│   ├── c319c83300a5d3f3150da438198519bb001f8027.nq.gz
│   ├── c401a35a3bd0eacbce80a087b72c7be067d908b5.nq.gz
│   ├── c4f40d413c1ffaa5ad51d579ce2a5afb854db42e.nq.gz
│   ├── c7418817439b2f071c93a4a6cee831e996123c0b.nq.gz
│   ├── c8e77de2054b54c70d202b01e00cfce792306516.nq.gz
│   ├── cfed9e0a4ecaca89c07159f6bb60d9d974f49932.nq.gz
│   ├── d404c0aa0f3dc3f75374e63a5eb85fd5cb218a64.nq.gz
│   ├── d468630b6b9b4ac89f547ae26a355711ffbac946.nq.gz
│   ├── d470400385aba645ff661f912d489885a0ee1b1c.nq.gz
│   ├── dac96e8c0a4f023ebeab71b1d1151b876d9eb658.nq.gz
│   ├── dc3971abc027c972855ef4afc9cbeced2202a42b.nq.gz
│   ├── e00290ca63d7fb5e9a37d8520179c2c693c57ec0.nq.gz
│   ├── e3004a15d43a688310d15b0b87026e405667d4d9.nq.gz
│   ├── e6af0a9350a06eee33b15fb5b6e44471513dc9e1.nq.gz
│   ├── ede13fe346a60e1ebefcc4fa2830ad6604c0684d.nq.gz
│   ├── f2f47a3452bcfff46119c0831f5245d9c6db7633.nq.gz
│   ├── f41936f65665a1d2ca2cc693ac243ec4c54802a6.nq.gz
│   ├── f6f4c05bc8a1fac111ff4c9f8fc95a65c6eb2cff.nq.gz
│   ├── fea67f4be4f3bc42cd6a7a37cb789f4e44668b62.nq.gz
│   └── febcc67778e6e3ab12db12c8787bfde2f597f153.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 7ee5b566984f7bd3d8fcfa0369e9e163e70e1cbd.nq.gz
├── filetree
│   └── 7ee5b566984f7bd3d8fcfa0369e9e163e70e1cbd.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 76 files
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

[mkleehammer/pyodbc](https://github.com/mkleehammer/pyodbc)

---
*Parsed on 2026-04-18 by [repolex](https://repolex.ai)*
