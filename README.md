# Repolex Knowledge Graph of canonical/pollen-operator

RDF knowledge graph data for [canonical/pollen-operator](https://github.com/canonical/pollen-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/pollen-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f62eef4fa693179aa607abc0d1bf256a3feed0b6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f62eef4fa693179aa607abc0d1bf256a3feed0b6
│           └── chunk-001.nq.gz
├── blob
│   ├── 02361050a74f8c7508cc12ed3d26ae641a0352af.nq.gz
│   ├── 07ccebba92c1f140c73a969360fc8547ac29ec86.nq.gz
│   ├── 0b0998257b1c90950cb0ed50f8999f2831910b6a.nq.gz
│   ├── 0ce00149f42b778e30d3aab3e8ce5747d395347c.nq.gz
│   ├── 1af85863bb31c0ebb3ac3fcff4e1f903598a8aaf.nq.gz
│   ├── 1d413c0dbe85b2797a476ea01cd3ac60825f7f06.nq.gz
│   ├── 213ec01d15a4e63159e610b387073bf3c6028137.nq.gz
│   ├── 21451eb06545c65d9882baf6f73f29accd081624.nq.gz
│   ├── 26ac226df88c6bc3785214f437d30606702a7736.nq.gz
│   ├── 2db7f38922b53bd3323492fe2532042a05ed74cb.nq.gz
│   ├── 306a6195a7ece2e344429f64fa017bf97a57455d.nq.gz
│   ├── 3372cdf832ee05e9662c2b38bd09673703f18820.nq.gz
│   ├── 350d969edb9e532c464817dc76bc145c2e282a05.nq.gz
│   ├── 38c04b8271361f116677bf7546dc9aa060c1e539.nq.gz
│   ├── 39c04edbff1522fab2469d0929f7a750855f321e.nq.gz
│   ├── 3a781086230b2d1249d692d70afc0672e943eaf3.nq.gz
│   ├── 3b6d95a77c7f608c6c0d82ae3f3ed4f0e6ba38c6.nq.gz
│   ├── 3d1e9d7486f5969c97905c017350c497003bf449.nq.gz
│   ├── 4abae6cba6c79328c9e4236a2e4b83ddde5a3c02.nq.gz
│   ├── 4c52c50333e9ba51b80419dc3a923cc59f9ffcb5.nq.gz
│   ├── 4f13f0380d610d4f0d7d0f6868fefe56d5f1841a.nq.gz
│   ├── 4fc3678fe4f5a9f5c60423295f4dabd4106606a9.nq.gz
│   ├── 539809700511e162580640fe6d0811c2ccc87dbe.nq.gz
│   ├── 56a6051ca2b02b04ef92d5150c9ef600403cb1de.nq.gz
│   ├── 58d6a4863683cf4eeccdf0788e2f4e6eab9d5753.nq.gz
│   ├── 5d6b3dd4c007e265b7e8a0af463a2ba0620f3d76.nq.gz
│   ├── 60113a892fe58b62f8b0c91343545314406ffd11.nq.gz
│   ├── 637cc0a8ee40c32c3b29a760116dd03fbe01bc5c.nq.gz
│   ├── 651c9d3b98f2dd150fc59fef2e2de001b9613068.nq.gz
│   ├── 66649de94c98ef7f1e46f41e111b81189077d8bb.nq.gz
│   ├── 6d4688e264dfeff5ebc955f8763ff99c1ab83063.nq.gz
│   ├── 71e44ce0a02fdd11386a8b77c8f1980ba09d2fbb.nq.gz
│   ├── 721d21283cc111bc00388e3bbbe6bfeb21e15e9a.nq.gz
│   ├── 7463b97afeddd71e376450e7f855f76f29881907.nq.gz
│   ├── 79f4d690463829cb93a10f481fe52270801b851a.nq.gz
│   ├── 8dd26f646a5a59e5446231eb3181bdcaaff54f19.nq.gz
│   ├── 9296ade15c1e3ac50aeb683dc3e6ecc8e81f2324.nq.gz
│   ├── 96a14d65ad0f696e4a6d4ab512e21e092261e2a2.nq.gz
│   ├── 97a68f8267c208408c342e31852f1aedb02025a8.nq.gz
│   ├── a599f03754f823bf2c51fa5766471f2077241cb6.nq.gz
│   ├── a84cba1f56fba00aee0a37b97c4bf07afeea2064.nq.gz
│   ├── aa3f45a62c744f97e9ad0bee3f925c45103e3f2c.nq.gz
│   ├── ac2748c1974e27c79e28e5ab760b47878d883bc1.nq.gz
│   ├── b4703853405c6f0b56ed76226acf79242125cd84.nq.gz
│   ├── b66780dc18eb269b144f7be6d824c226aac4a14c.nq.gz
│   ├── b845a37f5520e5747ea34a81bfc3669bf7b62266.nq.gz
│   ├── b8d8cd2f13e36d7a31a3c47fe18bd791cb471b63.nq.gz
│   ├── be24a1407a3eace99328dceef6471d33f7e5bb99.nq.gz
│   ├── c0aa441ace46b37c4c8fa289416e20d75e384920.nq.gz
│   ├── c1dbd4d9c23b20a6a598a385f72c9795a115c6d2.nq.gz
│   ├── c31583d437b5c545059ea4f1f8103fcd66fb17ab.nq.gz
│   ├── c4095eea8259c423a4a59a5e0f63fc7ad3a8360e.nq.gz
│   ├── c4a371b812c1a5056a6bfe2068b2a73eb8bd3a7a.nq.gz
│   ├── c51f8731433ae312f489f87b230c5aa38ef668fa.nq.gz
│   ├── c79941e647ba53840be6b8ee6e84ca0b1bd1f1a3.nq.gz
│   ├── ccbabb36de45639a0fbe5bc77fdf9d9cb24d80cb.nq.gz
│   ├── d28d5ffc0d62cae41ab2df4409c15673b466326f.nq.gz
│   ├── d34af00c4c150106d13c9b6dee4350e48738b8a6.nq.gz
│   ├── dd394cf1263bb5af558ef9cc6caca1b159543e88.nq.gz
│   ├── df541556b4c8b8d1d2040a3acdf1aa8872e9c1a7.nq.gz
│   ├── e38c5841dd941f8cdeccc2850966d3dbd5ecabdb.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e74cb0e8670d68ea532266f10163f480b88427cc.nq.gz
│   ├── e9517879f4ce7124233b51b3ed054de619c91b76.nq.gz
│   ├── ea9e6f5820ed32edc7a296832fbcb736a6e43104.nq.gz
│   ├── eb5545ffa3cc29ed5f25784c1e4fee97f8803318.nq.gz
│   ├── f032a192778de3db681feab64645621996bb1df3.nq.gz
│   ├── f4a7a77bdb5e2eeaa6a960f83ad61e27e79b76b8.nq.gz
│   ├── fc532631ea83659fe66aac37820a4e1bed0632e1.nq.gz
│   ├── fdeb2e732773806a1a26ae26068e1d464ddd56bc.nq.gz
│   └── fe3518b0772aaeea4b156d5d8453f58c15b3ab96.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f62eef4fa693179aa607abc0d1bf256a3feed0b6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 79 files
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

[canonical/pollen-operator](https://github.com/canonical/pollen-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
