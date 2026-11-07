# Repolex Knowledge Graph of ansible-collections/ibm_eda_zos

RDF knowledge graph data for [ansible-collections/ibm_eda_zos](https://github.com/ansible-collections/ibm_eda_zos), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/ibm_eda_zos
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f23538894ab59f759621f45adb0157136105c251
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f23538894ab59f759621f45adb0157136105c251
│           └── chunk-001.nq.gz
├── blob
│   ├── 01334e24f550a785872f2cee7b357e044b3c230b.nq.gz
│   ├── 019aa2243fc9d8ff96f36cb3ccc5629033aa3ebf.nq.gz
│   ├── 02ed11cbcdc17d59a936292b951f6194d92ce319.nq.gz
│   ├── 04ad901972bfa17bb397997a05d766dea312973a.nq.gz
│   ├── 079b8adc3f1054fd31b673344f6c23df32335e77.nq.gz
│   ├── 087be901145a1ac8d3d8ae7af33d0a062b59c029.nq.gz
│   ├── 0f054b8335cb50d8ceca0f072dda987adf1a0c31.nq.gz
│   ├── 13a31897ec90ebbd33bbc17cf5747e58d67cf10c.nq.gz
│   ├── 149709e591421b2db9ad71d96f6a36b03f1f1427.nq.gz
│   ├── 1a6652e3cdf6961c868ba2461c713481c7308788.nq.gz
│   ├── 204fdd5876ed14a1d27e6ee10690b94b21ea9fc1.nq.gz
│   ├── 2590f9e88e49ddfe8dbfaf0d4271a02f0831e3fb.nq.gz
│   ├── 2aa73fee7e85b873e313e52d003f872df9c41744.nq.gz
│   ├── 31b9f2dfdc2678c4a1cc156b4ba5c12ab06ce575.nq.gz
│   ├── 344cac11538aab11b099eb1bee33b4d41877085f.nq.gz
│   ├── 3985909c6c517421de9f358255f25d6bdd51d31c.nq.gz
│   ├── 3d6704a660fa2c4ec5b4719d5e4b8808ef1a06ed.nq.gz
│   ├── 411cbc0a8f991ddf4962a9ea593ca3396b6bca6d.nq.gz
│   ├── 41a3849b4c594dfddfc248f7a8ef037d01396b1c.nq.gz
│   ├── 42c8d79fb75cd61b96231624db46358b79427181.nq.gz
│   ├── 494ed4ba7d9e11e4682161b7d0c6f02c9a379083.nq.gz
│   ├── 49c7554d4b2efff8e88120c51a2ac96526c1dba7.nq.gz
│   ├── 4bbf820fcf81bae724d0dd15e414647034b39057.nq.gz
│   ├── 4d1061095749482907ce8593abc09d31338e9d5d.nq.gz
│   ├── 4d790cf6d9b079839b0cb73add70a2902fb8d9c1.nq.gz
│   ├── 4fd0893121615438ca5acd88914ad1aac36e8f78.nq.gz
│   ├── 556b63ea9147a2a4a2d13ca653c901201a2808af.nq.gz
│   ├── 57df4c980b48cfc24ae042f2c165991ed3222f4e.nq.gz
│   ├── 583e47dfcde473ecb95bef37feb27fb5ffd629a5.nq.gz
│   ├── 59d80d5a590a8fdb99f91e308a3f6d72018e0631.nq.gz
│   ├── 5a8ca65f04775a213f58febbad7ecf5bc184e617.nq.gz
│   ├── 610ff61d3f2670c2a36d06636f3ec66ef3073d9c.nq.gz
│   ├── 645b1798e4da3f2ee670a22107a7d419fd2e2f14.nq.gz
│   ├── 65531791decf8d901c0b5a7b372d28b3ba877afe.nq.gz
│   ├── 69212c6d9f465368714671073a11c175c8f6b3af.nq.gz
│   ├── 695f0ca62aefee465480ea160caf5f0a527a3174.nq.gz
│   ├── 6ab6af49ddbe5980e57910ea8ab958418dbffecd.nq.gz
│   ├── 6f72b25115a8f7a7b55914c2edbef3cff4a9a56f.nq.gz
│   ├── 6f8f1c6286cd933f6ef848a9b6fbdead98c8b9cc.nq.gz
│   ├── 7040722b38b7e034ac120022ba27a26cf5540300.nq.gz
│   ├── 72097c3c7ea02fd963bef24ba05a2d36987faf94.nq.gz
│   ├── 79b0429a5097d8a2257519b4625d9f629d9c78b5.nq.gz
│   ├── 85c2772d34baa64e5a54db72b915953f0f414c7d.nq.gz
│   ├── 86e448103f7ace75d42da53d27c61f2ff0b16b9b.nq.gz
│   ├── 8fb2338773c5466c9ee3a9713af9d2423c8db0b9.nq.gz
│   ├── 9604fa86c4cc39270a879f986eb8e84fe00d1817.nq.gz
│   ├── 96f25d38c160919ca7769d4fe1c3a780d8159e86.nq.gz
│   ├── 978b9aed296002b71c6152ff266bf214faa9a7ce.nq.gz
│   ├── 97be64c1c2b328b60677ce3a179f383cd92dcdd9.nq.gz
│   ├── 9e7010f7994322c000ec7ddb7a183dba80a80157.nq.gz
│   ├── a27ca165fa2c82c91edaa6cf1d33cc314c37ff9b.nq.gz
│   ├── a397e44d4e2cb2f3d2ee1aaccb36d4a81c911933.nq.gz
│   ├── a67ebf11a299e5294daa72e0567962b545a33707.nq.gz
│   ├── aa315dc94bd6955d8ecbd977000aac33be0cea4d.nq.gz
│   ├── ac2f9a2d3c04b0818b362be1736c2f9985360f01.nq.gz
│   ├── ad10719528d03f5f0fe2dbe011111902e8f05d4d.nq.gz
│   ├── aebab5da7ba74f874a4dcfebea727defd2193917.nq.gz
│   ├── b10cbcff634479d11ba4b7b2a8382d9165a04770.nq.gz
│   ├── bea2106b7f801e053180caaf78186d81a67a68de.nq.gz
│   ├── bf2ef234b41293a3f6be9113d57ea12601ebbad0.nq.gz
│   ├── c53e0979cccfbca20ea4b69e1d6e760ea9a2b09c.nq.gz
│   ├── c54f881b48f10ae40d52f6809dab986942f2f681.nq.gz
│   ├── c9d783d4e55551e49cf8a83bca1547d8b8099d97.nq.gz
│   ├── cd75ae756ea056be710a4e6cf9090cb2c75747f4.nq.gz
│   ├── ce9aad1d8ce54e2271b9db9bc67c96647435dc3c.nq.gz
│   ├── cf87a75d32ec2e1f56cd2c04ff362c5ba626bc5b.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d823500ee5e3b4e91f3df07305829acfd8e354cb.nq.gz
│   ├── e0a1f91d9b1528c132de9aa56924d8f2f7ac61af.nq.gz
│   ├── e19c9b96cbf70a2676a7e3d514bf54f9926520d5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f4613b797821b00df269fae4175682f4826b9b56.nq.gz
│   ├── f7ab490cbb70dd6347f8b15ac7332fd9cae7339f.nq.gz
│   └── fa25184ba79931a2c1e9e08470409a69cf42e315.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f23538894ab59f759621f45adb0157136105c251.nq.gz
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

[ansible-collections/ibm_eda_zos](https://github.com/ansible-collections/ibm_eda_zos)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
