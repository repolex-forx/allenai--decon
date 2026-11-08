# Repolex Knowledge Graph of allenai/decon

RDF knowledge graph data for [allenai/decon](https://github.com/allenai/decon), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/decon
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4cdcc5696ed047bf7d0d48b8d86a274f5a06c0a6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4cdcc5696ed047bf7d0d48b8d86a274f5a06c0a6
│           └── chunk-001.nq.gz
├── blob
│   ├── 00774ce9a0fe6e8391df1d8d0c9b0f2756f76d0a.nq.gz
│   ├── 0092b6739dc1efa065f0e633bf65acc9dc3293a3.nq.gz
│   ├── 00dd505abe1dfd06cdd28d7adbc61592a2334830.nq.gz
│   ├── 0116658ad39fb473780f397dbf9eba382e618c43.nq.gz
│   ├── 01fbc4b3c335a2735233f453451a319597b53db2.nq.gz
│   ├── 030a819c1540599c832c15229b05e93645a37c2e.nq.gz
│   ├── 0463a0a7ef6807d9a99e9b2bce6226bf33448ee7.nq.gz
│   ├── 0a7425c0e33884caf8f1ab34d48ca032144de11a.nq.gz
│   ├── 0a9c15dfa01fc4d35942d340997439dda99986c3.nq.gz
│   ├── 0c960cd77a884860a47a143a3686643503bc6527.nq.gz
│   ├── 0d77779e9547f1c0a398a8a302dc1751fae9f98b.nq.gz
│   ├── 14f98f2dbe2b2d1404ea5a4d46272aa4f8adefeb.nq.gz
│   ├── 182db82852a41713270aadbe9ed4f07254ac22de.nq.gz
│   ├── 18817695ef9926a27c37197710ca0a17ec7c4b17.nq.gz
│   ├── 1b00cc3a5ea1aa7b649fa48d79b18304f393023f.nq.gz
│   ├── 1c9e015e96f45ae1788e9739b1947833af8ac636.nq.gz
│   ├── 1ced8ea75d8531c928f94dd85930a707a55e9067.nq.gz
│   ├── 1df337cf82a4c1c90a3bde57bbe832105261a221.nq.gz
│   ├── 21981e34fa35ec1383eb23060fc831fe7986b8ab.nq.gz
│   ├── 2621944d41f5d8a5b168575099bd34c65f415263.nq.gz
│   ├── 2c8da81c74df08a2f879c2c501ab5ae9ad9f505f.nq.gz
│   ├── 314fbda62b5b35a95184dc62294a80b02ac2d2a7.nq.gz
│   ├── 32264b03699b5f907db370d1425010e2ad480898.nq.gz
│   ├── 38a3c70e1d97ad266a04d2b7ce6c6a02f80599e0.nq.gz
│   ├── 39bac4908ff2dc4f7c1422eaab5b1d669ef2cadb.nq.gz
│   ├── 3a140047ce09a045249bb5f56421f100d54d5eac.nq.gz
│   ├── 3e99091902743356fac82c24d27421970376eab8.nq.gz
│   ├── 42e9cdd9f3974dfe5545f571664759a74d4ffef0.nq.gz
│   ├── 450bd8f93b5f948c7c646e3c164030165365c75b.nq.gz
│   ├── 468052ad31028c3ad39d0df5500ba9de8e1cb6ee.nq.gz
│   ├── 49198742c4326df2bfb546e1e6fd4f12c68c8706.nq.gz
│   ├── 4a9ac85c44c7bbf2c0607582ab3dd30b0e047c84.nq.gz
│   ├── 4c3cc0535b5074d444001329a62de459a682aecd.nq.gz
│   ├── 4e973e8e2945321bf156cbc4cd96f8500dba5946.nq.gz
│   ├── 523a9b312cf7dd9d099f35f144a9e53bb9d479da.nq.gz
│   ├── 57ec71a8a61acb008f15cbec1cf50c08338f0577.nq.gz
│   ├── 5a6462ca1c4ac802e1c559c0cd3c8354bd895c8e.nq.gz
│   ├── 5b36a3a4e8da93ff9386a12dc4d06a34971de482.nq.gz
│   ├── 6103a8714f9fe3180e94b1429c6bb940f2cd920d.nq.gz
│   ├── 62456b87846b130e2f4707b39297e08c331dc635.nq.gz
│   ├── 646b5aa76ced9a2040ecba1cce0056abff9f1b73.nq.gz
│   ├── 6771048ffcd6549f978178b8069bada541639864.nq.gz
│   ├── 69169fe04b66e5f0020c942fc51d535a0d5e1af5.nq.gz
│   ├── 69ea82c3049a254870983af23d13332644254ad5.nq.gz
│   ├── 6ad18a520163b97f6b36cf740413bb27745179c5.nq.gz
│   ├── 6b66a0beb2804c84713aa37c2a996e9e167a365b.nq.gz
│   ├── 6ca047a62daaff3614bbd5ee4aeb45bbe29346e5.nq.gz
│   ├── 703109e9ee8fac8dbfd24a0c755f1e71910ee264.nq.gz
│   ├── 70f9b56daae14c943415b35b002a68ae0a42b127.nq.gz
│   ├── 71ddf0d6b886fee9b3126046576abc2e97a3ab63.nq.gz
│   ├── 7278803a3caaff94abaa6fb0b353705d96281e84.nq.gz
│   ├── 7887a81fc602789977d249792d7c52cb0edd2cce.nq.gz
│   ├── 7d4aca1b03ec2be7b663ee413f2604b1a34a075b.nq.gz
│   ├── 7d5601f9b0e95f5fb21e745c453ede79f7fe22e5.nq.gz
│   ├── 7dc0dc107947081778971b368124657de3add979.nq.gz
│   ├── 7ef14a1f05fcd6311bab792bd8b005bbaf781b86.nq.gz
│   ├── 8147fe1ce6e91a912ef5b2aaa99d42d4c73e4841.nq.gz
│   ├── 82a8fe80a49ac293a31f74c644f1bc98820a35fa.nq.gz
│   ├── 83b2a55465ea75afcd354f83c5613140838968e4.nq.gz
│   ├── 83c799cdcc86ac4e2d3097df8c0607ad4578eca0.nq.gz
│   ├── 8503d5c5abd96405b3925af1bbb69c700d84c5b3.nq.gz
│   ├── 8657d05323423f55f3115a162af248562e82fb88.nq.gz
│   ├── 86c25ebb9f23153ca714f090b9141a4b946a9676.nq.gz
│   ├── 88638cd692c4d83931ad1623b93a6bc185466f83.nq.gz
│   ├── 894437afa7da6a592d76308149c8057083721cc6.nq.gz
│   ├── 92c7f1317062a12afcb379f18327e73ea34b01f2.nq.gz
│   ├── 932af40b34175a93a45271ffdd5fda9ef38aa9bf.nq.gz
│   ├── 9949b9f33bdec1a44e8ffff8c22c366d0bbb174f.nq.gz
│   ├── 9aa42871ddf0f7e9788ea92db447cf005dd40d54.nq.gz
│   ├── 9bf8c1da385802ceb9ee346ea1e16b83056832c0.nq.gz
│   ├── 9e78ffdb500f2dea23e583a48625c1494208f162.nq.gz
│   ├── 9e901868176d8e301e586741ae6c80000ce1167f.nq.gz
│   ├── a10f1b941ad95e207c97082ad071d2c0440156a7.nq.gz
│   ├── a1383ab1a94fe860c963bb08c4953b3ae414926f.nq.gz
│   ├── a1d67b89e9f7909af2436605ff57f576c028b5cb.nq.gz
│   ├── a27dae33137d559d9b83cb1600e49378368cd470.nq.gz
│   ├── a39502dcbf49a7b01b32a062201cb3fda8d1e6c7.nq.gz
│   ├── a701273961015e83401c77e98e2d08a0d3e97237.nq.gz
│   ├── a71ac346723f7f3bcc05ace0b70f47318a0b5f6a.nq.gz
│   ├── a81768bf6e75e5040a30447e7a3192c97a20ef9c.nq.gz
│   ├── ac087040b192d8be3ff2e8ba37fe8d97623d9fe4.nq.gz
│   ├── ac3dba12c5e6b634215192211e3fa3efd5531140.nq.gz
│   ├── ae9a97e95d1a76d8e9b28bb304b615dacc5cfc64.nq.gz
│   ├── af1b70ea919d2d45c9a732489153b984f7fd66b9.nq.gz
│   ├── afd24af49307aa4e0146c23eb8e786ea88e9c54b.nq.gz
│   ├── b746f25ef04dc2a5a6c3c2830834c7433e61d3b0.nq.gz
│   ├── b789449b3571566364a82814a6185f01eed94b2d.nq.gz
│   ├── b88a363c674076a5290135186178ab296991dd7b.nq.gz
│   ├── b94eaf269f97711f9642c83323a87cf75516e9f4.nq.gz
│   ├── bd58bd6b35f65d960b65506c4f720d70cab2859c.nq.gz
│   ├── c2f9f227e59163645aa95c20794ece799535c510.nq.gz
│   ├── c8af219c965f2b56e798f1556172866d687215c1.nq.gz
│   ├── ca4218be00aa168f813f8f3af1e9ea5877717b07.nq.gz
│   ├── cdb992aa138b7900a37a50e64a7f5f8dcc001ac7.nq.gz
│   ├── d099babee6cfb35ffddc7267fb76eec039d77cfc.nq.gz
│   ├── d13ce246959288d8d2eb64c5eb1cd35eda5c583f.nq.gz
│   ├── d1d8ae8a0b72346819cae5df047fed68364c5819.nq.gz
│   ├── d2746dd114aaa5ffab6353ff2f27618b20e3319d.nq.gz
│   ├── d420eba9f3c3c434146a2815d766e0e14d352eaf.nq.gz
│   ├── d543a75e2bbf233b6555115343f118d4cc2f1ddf.nq.gz
│   ├── d87c2841b717e537163187023c2f4f93d5aceff7.nq.gz
│   ├── d90248105850382bc3f6dd38affbd04e3d4e3ad1.nq.gz
│   ├── da87183581ee7523e4e740da51707c33fcda35ae.nq.gz
│   ├── dad0edb53945706ed7dc22e326dd18c0972a2863.nq.gz
│   ├── e19702b4f8ca3968310ee906068c2f9d7e7220c0.nq.gz
│   ├── e23686be67073357058cf7b61860a0a5d39c7062.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea0a6f1fe63e220916f20caf7135ea696bc3c4cf.nq.gz
│   ├── ec86f68e1c50a1979f6c2a418883a17e086eebcc.nq.gz
│   ├── f2f81e72f48a2955b40ae4290699669842cb26e8.nq.gz
│   ├── f6ca97592d2f2a2916eea79c609f6350d88cfeea.nq.gz
│   ├── f7116f203800450bd6be48ab8d56bdef88037791.nq.gz
│   ├── f9a93ed70364bb73be354364f49ac7721527a57c.nq.gz
│   ├── fb2511fb679def0d6f65ac77a58c0a05a1775e4c.nq.gz
│   └── ff341a84d5ba7a044b2f9d583051285eeb132b7d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4cdcc5696ed047bf7d0d48b8d86a274f5a06c0a6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 123 files
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

[allenai/decon](https://github.com/allenai/decon)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
