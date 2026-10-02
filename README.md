# Repolex Knowledge Graph of block/dev-daemon

RDF knowledge graph data for [block/dev-daemon](https://github.com/block/dev-daemon), parsed by [repolex](https://repolex.ai).

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
rlex download block/dev-daemon
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 55c5d754cc044dd2ab174b4d772e3d3dd07f0873
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 55c5d754cc044dd2ab174b4d772e3d3dd07f0873.nq.gz
│   └── repolex
│       └── 55c5d754cc044dd2ab174b4d772e3d3dd07f0873
│           └── chunk-001.nq.gz
├── blob
│   ├── 01f390f51bd127624e5c46317c8f6964a7674ea7.nq.gz
│   ├── 038c544b569544ede892b3bd8d09d0cd23c6ea7f.nq.gz
│   ├── 06adf7ba766a5e016f0291201ba6f2ca2086f394.nq.gz
│   ├── 07ae3436dda6a3a8c4a9d2c7cce2a1778c22223f.nq.gz
│   ├── 07ea059fae3223c3204b7b6bd2971a73d03f2472.nq.gz
│   ├── 08ee91a7b6856cf3d61caa687a90538e1cc69a57.nq.gz
│   ├── 0a91be6beede517cdb6f9f869787e63f2da36b75.nq.gz
│   ├── 107acd32c4e687021ef32db511e8a206129b88ec.nq.gz
│   ├── 1299a875c349771dba912cdbbdfe2c556946aca8.nq.gz
│   ├── 14693a2cc915cab9bf9abe0a17f52117a3389169.nq.gz
│   ├── 17467b189ff8e28f5f533058454a649ed9ae6065.nq.gz
│   ├── 18a8ae65be881e0a205d4dd6bb001bde38b07e9d.nq.gz
│   ├── 1af26270d6f791fa449f5754c154d9a1d7ae8aec.nq.gz
│   ├── 1b6c787337ffb79f0e3cf8b1e9f00f680a959de1.nq.gz
│   ├── 1d9ea25d12f71dfab2d9b767e0968578c0d48787.nq.gz
│   ├── 1e3dd28cdffd2aa565973e5c7d4a8f2cbdb2ca8c.nq.gz
│   ├── 21e92fcf6fcc864f7d7064f07587e76de6728352.nq.gz
│   ├── 249e5832f090a2944b7473328c07c9755baa3196.nq.gz
│   ├── 26a1a270fc615b34d1c10179cdfd434b173d7a50.nq.gz
│   ├── 285792a4bde1ec15488a1781dee2cc5ce7ffc963.nq.gz
│   ├── 288349191e629dd8ee75899425aa7f31ac3d5dea.nq.gz
│   ├── 2cbf18624595841551f9995d7f64fb345278f7aa.nq.gz
│   ├── 2eab679c48afce6dcdc41d8d6e9827408c3ab101.nq.gz
│   ├── 30894542d13e7920ce7c9ff25182357dbdeadc8b.nq.gz
│   ├── 320f3b1cdbf5fc7bbb7ed4353d1a5b1bd5d1edb8.nq.gz
│   ├── 3517436796535102f71496854497cacbf78e69f4.nq.gz
│   ├── 378374d4b482dd68c7ac2f26a6edcaf0f416b008.nq.gz
│   ├── 37b5522d38aa23a0e1cafee519685047ae5591d9.nq.gz
│   ├── 3959bacd4503dcc014962475f43be37a691b511e.nq.gz
│   ├── 4177eba5f48dc60584924628af3c0768b7b1cd2a.nq.gz
│   ├── 49cf0e9162a0901d2831d203c4af2a327928a4b5.nq.gz
│   ├── 4cd374d4bf35e1e7786f028cc5a29913c14857b5.nq.gz
│   ├── 4f41d4f57086012bfb533c2284257bd5d4c8d7fc.nq.gz
│   ├── 55276ae1088f87c4cb008eaabb9768d647720c7a.nq.gz
│   ├── 56ee20364f389afc771990a9a2285e71264c4ca4.nq.gz
│   ├── 5f1cd028b82b6dde98f3770b347ba89cff0cb2cc.nq.gz
│   ├── 64c17ac9c68a9d28920aef5eac79d8b3211f47c4.nq.gz
│   ├── 653c6500a79c33f5d47d39730183865986171d6b.nq.gz
│   ├── 6b35c38b740450abf0eb2bf587b51c3cfcc6588b.nq.gz
│   ├── 6bccf43368fd7c96d9c659562a5142b8b8cb98a1.nq.gz
│   ├── 6cda08a20ef6014a6af2f209c5683bee95296d2e.nq.gz
│   ├── 6ecae0a7485ea67c8e5c2e8bc5b0d227c90b5e47.nq.gz
│   ├── 6ef923f8b0b1bc98d90b785c06a53772386dedf1.nq.gz
│   ├── 6f6f184dcffae829e930477f0b51c884c5d59b67.nq.gz
│   ├── 6fffb861524af2b61e8b0e50af60c9a912978aa0.nq.gz
│   ├── 71367854854c96d48990ff5e45863116e28bf5e6.nq.gz
│   ├── 759121c301274d2ed04dae4525b9321282fd2ae8.nq.gz
│   ├── 7e7bb36743c2738373258dc3f0ba8a3503d0e823.nq.gz
│   ├── 7fcf86263e899321ea4d863648e65b91bf7691f5.nq.gz
│   ├── 8025eac76e91a23a6f9cbbd92df99c929f2cf5c7.nq.gz
│   ├── 826ced9bbe878f4a23c5782919428e8d6a485a2a.nq.gz
│   ├── 8634e6c606aab135da4103cedcb0876d83e75258.nq.gz
│   ├── 875d8094b685144849565576b1d59cb594c326bb.nq.gz
│   ├── 8a7057189f4147855479e93e60047b9804139ca8.nq.gz
│   ├── 8b72244d246f059e82f3868b939ecd342ad7e1ef.nq.gz
│   ├── 8cabf9eb52b464f76312d0fad5b29bd73d74b04b.nq.gz
│   ├── 93d81afcea9abb5f18699a82bb7af1c48958ae3f.nq.gz
│   ├── 9b81f1fc8c3b595157ada73f42434e5489197c00.nq.gz
│   ├── 9f1683b1f4d6c11a0a3e5e14dd978000b308d4cf.nq.gz
│   ├── a4463c208afc3f1c94a88268f823d04752854116.nq.gz
│   ├── a49e4ccd0b177e0af32ef526c70d010deb7474b3.nq.gz
│   ├── a5b805b156bb3cafa908f36138762ff2403af07b.nq.gz
│   ├── adc3c9c7feeebdbc7c8987d94c0d40b92ce968cc.nq.gz
│   ├── affaf5965cb4ddd5452a50db66dea95d87d69ac4.nq.gz
│   ├── b1b03de1e42b3f6c504f7628f344116343fc26ba.nq.gz
│   ├── b5f8f1916c18237991e9708bc74010438fff111a.nq.gz
│   ├── b7328646cc6994693901fe556ecc06906da5e403.nq.gz
│   ├── bdbff0bbec9bf60c2756fb7db20a243e6ffc608d.nq.gz
│   ├── c849a7504e948d07d8fe6550a33b201550ba9533.nq.gz
│   ├── cb8e57e024faa7c0328d2a74f94f2a7b963fe483.nq.gz
│   ├── ce3ad7e5630efb75bdfe18b0af75cc780907ac44.nq.gz
│   ├── d132ba7b0757a5b437107b31835d25eeeb1eaf18.nq.gz
│   ├── d70caece52dbf2c9990fc8d8aef2eaec9f6e6015.nq.gz
│   ├── da0c2f86680cb65e89f9ca2f735fa363126e56aa.nq.gz
│   ├── dc4965917ce94e817c455f8bf4fb79ca7d3fc460.nq.gz
│   ├── de78ec032ead0626cf8bedf3b9489d1f89102c96.nq.gz
│   ├── e291573d408d23ded3a0601958b23b05ab60595f.nq.gz
│   ├── e43cacce28bfc0edc01ca4d4115c2a5f920405de.nq.gz
│   ├── e826675bd84fb99608bcf5926c9cac38d765ca33.nq.gz
│   ├── e891e668834d9fd0bd46bcf7d3b076fb2c670b4c.nq.gz
│   ├── e93ec69362a1ea077da07b681584f9d6b11758ff.nq.gz
│   ├── efc723d255c342dcf50713c51f1b3f673e4ca60a.nq.gz
│   ├── f01435f90db3017276111c9a04c32e4aabcebb06.nq.gz
│   ├── f0ae2114c305e310bf6c9e9b5074f9822879466f.nq.gz
│   ├── f53d39f59e6b9d370ce5ec94fed268caaf9555a8.nq.gz
│   ├── f5514d27701a0c4f5b09b08d7ee0f08b870c2116.nq.gz
│   ├── fa33e6308e040e177d42da5cd19d9924225b963e.nq.gz
│   ├── fd0589331de5fe8fb2cc28be5bc83c9428c9aeae.nq.gz
│   └── fe5673851ca71945898cab43050ab2512cb8d35b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 55c5d754cc044dd2ab174b4d772e3d3dd07f0873.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 96 files
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

[block/dev-daemon](https://github.com/block/dev-daemon)

---
*Parsed on 2026-10-02 by [repolex](https://repolex.ai)*
