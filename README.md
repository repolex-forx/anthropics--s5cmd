# Repolex Knowledge Graph of anthropics/s5cmd

RDF knowledge graph data for [anthropics/s5cmd](https://github.com/anthropics/s5cmd), parsed by [repolex](https://repolex.ai).

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
lexq download anthropics/s5cmd
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a0c0cdb8cdc7284dbf7880ecd3e2e5812cd75ea5
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── a0c0cdb8cdc7284dbf7880ecd3e2e5812cd75ea5.nq.gz
│   └── repolex
│       └── a0c0cdb8cdc7284dbf7880ecd3e2e5812cd75ea5
│           └── chunk-001.nq.gz
├── blob
│   ├── 01c101e78563240d1c92a35718164e8cd21aa61c.nq.gz
│   ├── 05b2eceb7bed723984e75ae6bb571af253b923d1.nq.gz
│   ├── 077034006e608176390e9e0053291a4bb2aa746e.nq.gz
│   ├── 07926424be0a599838a98a8e55172fb60b865b76.nq.gz
│   ├── 0dfb04ad782cff0d630f832e170c7b1bf4db3d6d.nq.gz
│   ├── 1053ae49308fcbe73678993c6d0f7d78d04beb35.nq.gz
│   ├── 12e78a8b39a78239012bf98703c9048165dcee22.nq.gz
│   ├── 1609e8ad16f64ae63f03d683dd72e9c6a24a03e9.nq.gz
│   ├── 16d61d387dca247e9cbde3b8dd68b8163dae1b08.nq.gz
│   ├── 17cb23ed158f1834c190434985b2bf05ca0a1365.nq.gz
│   ├── 18f6bc4f377c4654467bcdbc9236b8cf7cfcd267.nq.gz
│   ├── 1eb78fb3d25c810688b404d51a6ce43d093fdf9b.nq.gz
│   ├── 203b1cac97763b3774e1e6fd83aa974549c715a1.nq.gz
│   ├── 22137341bf7188c4456209ab3fe630702a3c4f66.nq.gz
│   ├── 256b546f7291735d720045f8d80fb46316eea699.nq.gz
│   ├── 2c50517fb339c4ceccb233a926c213c50da406a2.nq.gz
│   ├── 2dc0f84cc6111a4931b5999ab68e9db90164f109.nq.gz
│   ├── 314f52ab8773a624879dda24c4f2eccab5fa4a0e.nq.gz
│   ├── 32cbda7aab4e933834ed96b0d6fc25cf324a37a3.nq.gz
│   ├── 37294ce4f318ebd9a5082e481fd48878dce499c6.nq.gz
│   ├── 38744b936be67b8e3980977a265c623189c8ad1e.nq.gz
│   ├── 38ffa6819cfb35e7237960e137861d4d6c2580fb.nq.gz
│   ├── 3ba092b23fdbd9e7427c97b63981805a3c211750.nq.gz
│   ├── 3ce56c5f9e69a8aa7fa93976460f66e02f7c5f51.nq.gz
│   ├── 3d835cbcb778d5291edf3aa815801aaf79b46dc8.nq.gz
│   ├── 40afb2291203a9e3e15a3cf333a123ee3f9e45f2.nq.gz
│   ├── 40bd07d31065d7bf3d5f242207662ee94df7bda5.nq.gz
│   ├── 414fe33c94db6eb1f7fa517e3a2e687e7beada06.nq.gz
│   ├── 43c6cb628710655fb672cf4afa91e25d9005e1ec.nq.gz
│   ├── 4561dd00b1c9abbc01626807e306a1db9220d126.nq.gz
│   ├── 48336d46c8782ac2e19aa504719697f7feca32a3.nq.gz
│   ├── 49755acdcd060ce77624a3bf3cf769876833807e.nq.gz
│   ├── 49c66183d406e813aa3ce70d866da63118bc6976.nq.gz
│   ├── 4c3a8fae2103b6aa6213ff6466cbcf53c42b2d30.nq.gz
│   ├── 4fc0000200db63bc9be34c5ba7821bad3d3df2f7.nq.gz
│   ├── 510e7aaeb3c5e2326fe89baea7fd73b94c51f11d.nq.gz
│   ├── 52a1e1f125b8f1cf75f77b4ede4a030c0c3d6bd1.nq.gz
│   ├── 5388057975467781314fcf99c163bc82bb6d34cf.nq.gz
│   ├── 56043dab09d1e96d55773c7a9c590d03c0562e24.nq.gz
│   ├── 562c02d8655525ea749d6e6d71c9070d1b14ee26.nq.gz
│   ├── 5a39199ab44535fe91e31401f6d05f87afde1a2a.nq.gz
│   ├── 5bd91271e47ecb2118b369c48cfa51b90d4d9315.nq.gz
│   ├── 5c3b662c87d635a5a912ab0131d25978bb8118d9.nq.gz
│   ├── 5e0ed492272b420bc6d55ceaf12d5cc89647f987.nq.gz
│   ├── 5ef3c789020909fba1cfb6319901f1fbfc88c52b.nq.gz
│   ├── 5fae3006da5f010942e00339cb28f600c4393098.nq.gz
│   ├── 61d117eff00f014e4043c8dac536f92c33b0130b.nq.gz
│   ├── 627e590b9ea14ee195eebf3f633a09f7aae3ebc4.nq.gz
│   ├── 6530fe82f19adae590c339fde4442297c44f31e8.nq.gz
│   ├── 6bc6d943d71fad7c46c4abee90b6c0c4ff398622.nq.gz
│   ├── 6bf67842aa9008ece57dc7f555e9a0b580eebe65.nq.gz
│   ├── 6c192407d85f153b6419cebb1c2465a660b1cf6e.nq.gz
│   ├── 6ec4829f231db0692549506e0af64e86dcbc9592.nq.gz
│   ├── 73ac239e7500eb68010b24629cbbff9d1f47bb0e.nq.gz
│   ├── 773d555a8af6b76fff402729a1b8112dc6fa5a27.nq.gz
│   ├── 78483d9f2129888020d1a1f00ed3f65c6e7b56fc.nq.gz
│   ├── 78e93218ff8212cabb05cdffac38541c7b368314.nq.gz
│   ├── 7d436cebe347d5c38af8beda06f52ebccce55dee.nq.gz
│   ├── 7d65deec33965e34df4219708de93c20f9e464b0.nq.gz
│   ├── 8030779594788f8be2410187e3f4d01fc4737725.nq.gz
│   ├── 80c3d572013322741dd5ee9258266b693d0b868d.nq.gz
│   ├── 87ff1e06b5d7bd92d7613654e1469d0020c089df.nq.gz
│   ├── 8812c9582b14cdf1bf39490651ae6791ea2bafc5.nq.gz
│   ├── 8c8a12f9f659f17dcec46067dda551e796e5d38b.nq.gz
│   ├── 9140e25ecbb95cc75701bf3c71269b118477d3eb.nq.gz
│   ├── 92477c3cc3d174b94c335c6f8a6c5d78166a8311.nq.gz
│   ├── 98746796353709c00ce52c54de3827a43d2ef208.nq.gz
│   ├── 9884279fd80714e40cb5300d68e3f8b718f0d079.nq.gz
│   ├── 99824979e227f7890b5a7ad3af79065557e5559a.nq.gz
│   ├── a0da0cee648e1b766565ebf70bfa77fe58fb2ac1.nq.gz
│   ├── a3c94bf6e33cf681d47138d6ba508d5dc6ece2d2.nq.gz
│   ├── a56bfdb51726eeed60a8b312c4670b83bf99d50a.nq.gz
│   ├── a6db3febb9999d146765a7dfcf67354beaa62cbb.nq.gz
│   ├── a77c8075a2727f4de9306a18bed6d02c339d1add.nq.gz
│   ├── aee6b0788dd623d82ca18d559fa483f813b70db7.nq.gz
│   ├── ba159299041671c1025c2c8ba84cf0e487bed5b7.nq.gz
│   ├── bd2499471481f07fb17f797e43b1829cdccb9000.nq.gz
│   ├── bf74e864f58d0558ae3b07835d13238b81b055a8.nq.gz
│   ├── c1a06d5313005c0e574c46e907563f69317d173d.nq.gz
│   ├── c44305375b5c0eeea5f19444aac76d11358dfa45.nq.gz
│   ├── c71462d09db16af93e04e40a3d2e89326ba04c52.nq.gz
│   ├── c848e7abf4ab712714284dfa83bf0f7b3fe94e69.nq.gz
│   ├── ca412dc216fb8ada0f9dc28b6722da26c64df280.nq.gz
│   ├── cc96448bac19c43dd2720264e7cfb34f4d5bb06f.nq.gz
│   ├── ccac38ff34db70ee1e51e4dade984930da0ddbe6.nq.gz
│   ├── cd76cf2b7226d9f9ec215da431f8ae909f0cf11c.nq.gz
│   ├── d079c225129c659ad81ac5a0c09292cec52e5919.nq.gz
│   ├── d09c73e12100dfbc05510ade55549c43e641d1d3.nq.gz
│   ├── d16a116003a984e7aa6974248a4ec455de12d78b.nq.gz
│   ├── d642ac7a8f4827349e5e79681da5b450bdcee7ef.nq.gz
│   ├── d8752d47dc8caf71f73d33fc14ce66e13664640f.nq.gz
│   ├── da82621d27a6f9706481ce0609a669ab777bf693.nq.gz
│   ├── df29d57e7923c8388985b67e048d798439c83f4a.nq.gz
│   ├── e5e48d6b8e3c9d147cbf2a5eb2e3a693bb62cd5e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6dddfd987e5c295fa8bc08b6b181b0dbef3fef8.nq.gz
│   ├── e7783356f24bd4395722d44952985a472d4dbfb0.nq.gz
│   ├── f1ab955b8fc281c72a3ac0ea3315467538891ea7.nq.gz
│   ├── f538f3a448ba880648698bd9f74a8d07d9f7095f.nq.gz
│   ├── f5cc90810b3b377f333ab9508e5173e412d64046.nq.gz
│   ├── fa7af636248d90e99d8680fa987a7d4f92df2b5d.nq.gz
│   ├── fd9c590a877e8db439230997d4a55f5b7f6fcdab.nq.gz
│   ├── fda459df9e171febc8187d8f255f742fd4c29a48.nq.gz
│   ├── fdfd46e1925e3d9c27d0cd3fd3161c485f15a82e.nq.gz
│   ├── fe01f949577ed1c6d4679adbd715e273d3017146.nq.gz
│   ├── fe6ac0a81cffd10a2377fcfc5e7e34e95cb46dfe.nq.gz
│   ├── fe6e948e9e09c28a13c2d52f2a0fb5d9fba54d11.nq.gz
│   └── ffe83b70436241c3ab7e913397731da917a70f3e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── a0c0cdb8cdc7284dbf7880ecd3e2e5812cd75ea5.nq.gz
├── filetree
│   └── a0c0cdb8cdc7284dbf7880ecd3e2e5812cd75ea5.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 117 files
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

[anthropics/s5cmd](https://github.com/anthropics/s5cmd)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
