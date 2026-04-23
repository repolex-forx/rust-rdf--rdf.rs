# Repolex Knowledge Graph of rust-rdf/rdf.rs

RDF knowledge graph data for [rust-rdf/rdf.rs](https://github.com/rust-rdf/rdf.rs), parsed by [repolex](https://repolex.ai).

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
lexq download rust-rdf/rdf.rs
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c7d1872610f04e19caffb8882d73706ad89cf241
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── c7d1872610f04e19caffb8882d73706ad89cf241.nq.gz
│   └── repolex
│       └── c7d1872610f04e19caffb8882d73706ad89cf241
│           └── chunk-001.nq.gz
├── blob
│   ├── 02fd3e6c7dcc7897a5fb4eb20a246cf77d056601.nq.gz
│   ├── 07ff83b82feb8dbc1c93bc4b2f9d9b26feb7d9d3.nq.gz
│   ├── 0e057e9a7ef01131e74ac1ed3c386c9331671d02.nq.gz
│   ├── 0ea3a944b399d25f7e1b8fe684d754eb8da9fe7f.nq.gz
│   ├── 0fa53372a997ace55435d9341b2cd5f5b7558508.nq.gz
│   ├── 110ee03fa2408939a387b44fcedc4e3640ded3d6.nq.gz
│   ├── 11267fbe135a9deffc42e13b0c906966ca5c5b73.nq.gz
│   ├── 13edb27f8341a15f7ef6805243c5be8572913129.nq.gz
│   ├── 17e51c385ea382d4f2ef124b7032c1604845622d.nq.gz
│   ├── 1c0de950fb9d794a0e245e90aa9b38f770ac4c63.nq.gz
│   ├── 1d1a24ba2030273d490543aebeb8326d4305418c.nq.gz
│   ├── 1d411b6333063b2f5711574ef36e07cf231ad0bd.nq.gz
│   ├── 2058baffb4f97d0456cfdfe4f39f6cd949f73b5d.nq.gz
│   ├── 24d974d20898e1566a6b8cc0dcff8a385ab201e8.nq.gz
│   ├── 251c44093ed1b5db27e015be76fa3b22ded61ec2.nq.gz
│   ├── 2601b3f4151f2ad62821425751ff1867283aa420.nq.gz
│   ├── 271649cf062bfb396d429c714d1c73eff4b0e5d6.nq.gz
│   ├── 272f2d836ed4e32d472d29fedf98acf7217d2af9.nq.gz
│   ├── 280fb8d04170d32ee9c5f1537fb204382a2602ff.nq.gz
│   ├── 283d3ff321d1688f7cd6a45d0c38619ac59a7f14.nq.gz
│   ├── 29f511aeb7034835768d1f1870ec3b7db821ddd5.nq.gz
│   ├── 2a53d7a090c552319f199ba3bb17e40987073750.nq.gz
│   ├── 2c10648bd185c25f80f6d9ff9c010e59f72f470c.nq.gz
│   ├── 2f37af5ff7907db597bca2974a3c8ec163359878.nq.gz
│   ├── 2f93f6ac192285e396d4dc3fd4c3e12a0bc3c267.nq.gz
│   ├── 333bce1c3d2ec9c4df526f010b42540285cd1f7d.nq.gz
│   ├── 33c599a3736c480a237650ace21679f498203149.nq.gz
│   ├── 348bcbdb7b0a05a656f9f13659f8397609c4c1de.nq.gz
│   ├── 374d1dc55f9aee3947eb5bfeeba857cfc5595881.nq.gz
│   ├── 3de9f4854fe376328ea736144ca7913be5206a0d.nq.gz
│   ├── 3f400467828f6ff3ad71433592adc2c772f1b244.nq.gz
│   ├── 4785d6b63c67a09ee5967442cd47879d6a28cad6.nq.gz
│   ├── 487524eefc198ffdf1eef8eb5d8cf87c396b9f1a.nq.gz
│   ├── 4bf5bae2ec735de4cad00960d45465f236482aeb.nq.gz
│   ├── 4c357d82bb64ad3edebe76ed114c77f1df81649a.nq.gz
│   ├── 4e331277021c633174bc4f7df4ac8b285c129018.nq.gz
│   ├── 5088b2670277584c18b5e41c0be5c880cbf3744a.nq.gz
│   ├── 568e3cb194850867785f3b7e4eb582c803b9cf29.nq.gz
│   ├── 5b077ab2bb6bfadeb657d8b6ff7144fa24a52464.nq.gz
│   ├── 5b82abaa2ced7e4ba67ca324e8b0ec1614c31640.nq.gz
│   ├── 5e35b944762eec305952035e3e8de443ef501c6a.nq.gz
│   ├── 5ec23b176ad4de15adf726bc82a372bae3c73f99.nq.gz
│   ├── 6186d7464f87a98cc8e165072518c2505671e99e.nq.gz
│   ├── 63d0a18c7785b6b8feb522207a39f561fadb759e.nq.gz
│   ├── 6704c2ace41403e51285d29fc70fd867622dc7b3.nq.gz
│   ├── 686f0a0c02b4e26652c2452694282bba3f1292e9.nq.gz
│   ├── 6972185d84ef10de4787deace65824b41c50c0de.nq.gz
│   ├── 6999858eb5c4ee58bcb28eb2c281ff542c76dfe1.nq.gz
│   ├── 6b9a3b947cb4461e28f2e796801f4c9e088202ed.nq.gz
│   ├── 74c82c0c4acfb495cf03d3a7f4a7dea949519f6e.nq.gz
│   ├── 75e3b65f99b29f48ab230e3eab3de8d0b7a9229f.nq.gz
│   ├── 763b1ec12431aa132b6aa523ac830f2232d37325.nq.gz
│   ├── 7a34c68981dde80f6c2a1c7ad5371b403cc5c552.nq.gz
│   ├── 7bde73a894bf3dede281769b96a96813ce7790a0.nq.gz
│   ├── 7d9fcf2fc67632e074eb54cc0c32256d1ae371ff.nq.gz
│   ├── 7da08602438b119d740b4b629c413fd5ce95a21b.nq.gz
│   ├── 7fc4646453155fb1313aa4bafd93aff44b4e17c8.nq.gz
│   ├── 856e56bae0dafef78f39f5f5d9a0fe2ccbe48ea3.nq.gz
│   ├── 8a850d77969a17bfc1f794345cb22195ca0dd118.nq.gz
│   ├── 90e9b58256e3aef7168e6e34a555ff2b253e75d6.nq.gz
│   ├── 91f3bf69a44208848aa793a06170ce06007ca816.nq.gz
│   ├── 92e2b2696607ce6916cc617cf4ffdd06bca476d3.nq.gz
│   ├── 955a3d69d0be908deef453148e0ac8940d117796.nq.gz
│   ├── 9ca654e0f9d0509baba745b1e8fc8f1e1b2c5237.nq.gz
│   ├── 9ea7cafd2b8befd00d30b8caf59bfc77daa62506.nq.gz
│   ├── a0a18a6a48a9e56c06aea95b88da0851cf8add50.nq.gz
│   ├── a3c88613fc85744297005eff5bface52bd553210.nq.gz
│   ├── a751161618df5cdb2759176d763125460fc2e799.nq.gz
│   ├── a9851ef6eb8efbb837488e9e857fcd6582851503.nq.gz
│   ├── a9882c503de51171f8594b7ecb7b513531f77d1d.nq.gz
│   ├── b2dbe32c32cb916f0b4458c35bc1f1b2d2690b79.nq.gz
│   ├── b55e3e5388d2bee3dc184d2f0b73e1f2802cd81f.nq.gz
│   ├── b56cb4c9851c49f7b66e3459813fc2dc80ed3b53.nq.gz
│   ├── b5c69dc06bbfb98f287d4cb76d4fda1d66a51a6d.nq.gz
│   ├── b619b355ead79de57f36a7c94e976c037bb44c56.nq.gz
│   ├── bc099adb1d2307f6cf459954bf723b1290adc5f7.nq.gz
│   ├── be2bec05df3be5926fa80e722cf61e04be347618.nq.gz
│   ├── bf4fd08d2cdcf4e801411bd4031624122b377343.nq.gz
│   ├── bf6cd6540cdec183eb4e180acfd48119959b2255.nq.gz
│   ├── bfed998a1ed16fbef10f3babf64cf17a80abdc47.nq.gz
│   ├── c6e4005ee06b1e6d7e332bbb14bbaf3d2829491c.nq.gz
│   ├── c9bd216c510d239ba77f3f31b890a81db3444021.nq.gz
│   ├── d2d774d685a805fac62723c16262a6ba9ded7549.nq.gz
│   ├── d64e1d2b75b2140baa6d4f732c0380825b174c8c.nq.gz
│   ├── d8284e449a2fc2d8eb5bcf61fa4224decba69dc1.nq.gz
│   ├── db39ba4236c7caeee2f58a62a63b81b2691efefa.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e796f1f21c0acf0ab4a89d705ce614e46c8a28f8.nq.gz
│   ├── e933b72b21d896581e33982bf830bd485a9c8953.nq.gz
│   ├── e93ccc1e5c235e259e6fcece4746050e0cc2ee40.nq.gz
│   ├── e9f06ac80f8fb66dad049d03d8e89e8a0b6e613b.nq.gz
│   ├── eed41a7f07589d8cc63b8acf41782101488abb49.nq.gz
│   ├── efb98088164f5786b17e83ed384971fc3c74f93c.nq.gz
│   ├── f218e4559bd0481c51effe6aa2b378e518408d4e.nq.gz
│   ├── f3e6cede88d5d593a77a96aadca4f3fc84d2b839.nq.gz
│   ├── f53ff8fc2d11c34bfd6262c665e54ec5ed079601.nq.gz
│   ├── f6b58d7faa6c4768a948fdec2565932709ce0aa0.nq.gz
│   ├── faaa70ba415c212fcb3dbebaac2c093a6a53859f.nq.gz
│   └── fd9c8a5bb0ac33f0f0c8f7a71aa032295582a548.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── c7d1872610f04e19caffb8882d73706ad89cf241.nq.gz
├── filetree
│   ├── 61e26eb5ce4d3b36a1f9d933488db9e4aad62ee9.nq.gz
│   └── c7d1872610f04e19caffb8882d73706ad89cf241.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 109 files
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

[rust-rdf/rdf.rs](https://github.com/rust-rdf/rdf.rs)

---
*Parsed on 2026-04-23 by [repolex](https://repolex.ai)*
