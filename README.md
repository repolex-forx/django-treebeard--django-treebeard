# Repolex Knowledge Graph of django-treebeard/django-treebeard

RDF knowledge graph data for [django-treebeard/django-treebeard](https://github.com/django-treebeard/django-treebeard), parsed by [repolex](https://repolex.ai).

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
rlex download django-treebeard/django-treebeard
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ba525b1ab000805cd26591cdd784b95f94017233
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ba525b1ab000805cd26591cdd784b95f94017233
│           └── chunk-001.nq.gz
├── blob
│   ├── 0221a545d754e90ee12c39821531aa8388d607aa.nq.gz
│   ├── 0ae3f6ee469f09bb77ac1b572abcb1c194edfe43.nq.gz
│   ├── 0c6d9b3b9763c4424bfb0de0bf800017b6fc640a.nq.gz
│   ├── 0eeb2ef0680f8a92a7908697920dd3c6bae508d7.nq.gz
│   ├── 1035e6677ffb819e2b31a0f90ce144305be8e985.nq.gz
│   ├── 1400631c9dff9be5e8bef14df28c3514c712bcdf.nq.gz
│   ├── 160f119d1e2c27e4a9073079fb9f8d880c28d2e1.nq.gz
│   ├── 17997afa53f69359f0249418cac0a0ba5c85cb75.nq.gz
│   ├── 1b197b53bd08050b507699f66ad61852e235c260.nq.gz
│   ├── 235b8980158c7e7b5cf2604e09461f381da567fd.nq.gz
│   ├── 2393cda5858be6486495455153afb550c33adfde.nq.gz
│   ├── 23f696ebc020ad2eec7fc21d54942f06b529e286.nq.gz
│   ├── 28e95397f55d62ba35d16507ae42b605eaf8f04b.nq.gz
│   ├── 2c515d4204cc8311eb8bd2ee1cce3ba622622a5c.nq.gz
│   ├── 2e668fe37a55e7e6e60f2ca833a1f86fb1638be2.nq.gz
│   ├── 32f39f45e090a8b7b56e6d38f604d025aafbc690.nq.gz
│   ├── 3b59f3c4f1d1c29d3a6d5d4c8c216ccfb96571ba.nq.gz
│   ├── 4010f208f6eb44ed7cc364bfff66ab7b4d07df7e.nq.gz
│   ├── 402cea55f407d4ce08dec887ce9a177483ec21dc.nq.gz
│   ├── 4404c494f61f813b5b270b6325de943d123cc364.nq.gz
│   ├── 45a5b3856f39714c8374f5ec2af36c84ba2e003e.nq.gz
│   ├── 4a2f52accc912bd7be36a59482c61c2f33aea3dd.nq.gz
│   ├── 4c786cfb5ef8949bcf4d2f8bdb1d8d05f5ba5fd0.nq.gz
│   ├── 4d91f09cb8743377ae248f12d52c14651bfd3813.nq.gz
│   ├── 4db9eecd16780b52b05181f7d502fcfbfd034da2.nq.gz
│   ├── 4e7fe8635b8f3e159e682f00e8364144790d6598.nq.gz
│   ├── 507bb850b3510d16c57aab5fa0d048e9c9a74971.nq.gz
│   ├── 52d8ea0087092de629462f774764ebad3248ba08.nq.gz
│   ├── 545be46ff367ba0747c2a4a5f2e4e9ce380d2318.nq.gz
│   ├── 565f987f200662f8bfe2bf37f3647bfb473f4df7.nq.gz
│   ├── 57adaf317fbe17cd1a9d65148360c1d95982856f.nq.gz
│   ├── 5feefc1f24f3a6ceb8d7edd49783ca8aa9b32eac.nq.gz
│   ├── 6236f646e254f203a23e745f0faaca4c4cb76f84.nq.gz
│   ├── 62853108e90b0a9f9cf6d4c6389725d16d4b900e.nq.gz
│   ├── 635e8093e7d0152d6f1867cb7e82a4dd823c8a1e.nq.gz
│   ├── 63ea90f99575d11dc04f7de7f44818c5f084b758.nq.gz
│   ├── 655e293ae89cff9d7045aa88e0f206f550db5091.nq.gz
│   ├── 697bde5ce0423f1cb25fe17b6f3bd486e7281345.nq.gz
│   ├── 6cea35f1e17624cad29f82faad60ae576e39c583.nq.gz
│   ├── 723b7529d6a70ee463ad9092f2aeb0c3f54fb452.nq.gz
│   ├── 7449f15d4038b0d0a298fb3515f9cd73037b36df.nq.gz
│   ├── 773936342d1a9f8eb4cce1759c5b14cb2750edea.nq.gz
│   ├── 7c3575da03a7ad4fc0162cb5c43b572b11162c9b.nq.gz
│   ├── 7cbfb4656ac08f38cef22ae04646837e5d245753.nq.gz
│   ├── 7eaf8a449d609dd60bdb756e00898b0a5873a8b6.nq.gz
│   ├── 7ef0783ed6ac74e8f853e7621d03eccc1bb44966.nq.gz
│   ├── 7f1949532e84d324da7fba904b608b43d25ac5e5.nq.gz
│   ├── 81f016d09e00aed07b746c8ca807d59967e323d2.nq.gz
│   ├── 88f252ab83f8b591697db951263bb1b527a03082.nq.gz
│   ├── 8a41c0d5561b22dbe737adb169eab9e37fbce4b3.nq.gz
│   ├── 8bb1d553987043102a9a0e41ccbe58b997890efc.nq.gz
│   ├── 8d791d177a191a4abf250e14a83f924c12a6b122.nq.gz
│   ├── 8f6b092d6d7dfc118724ab9e5755236c1ed1593e.nq.gz
│   ├── 93418d8c6954419d62b20fa9ef13420057e5d1f4.nq.gz
│   ├── 95cd2f69b90377d5ebdcbac19aa17ae87d0f332c.nq.gz
│   ├── 9bf235d68a544abce51a4f264840a159d25423e4.nq.gz
│   ├── 9c35c4b14f853f2a4a02c6d173b029105e6b0a88.nq.gz
│   ├── 9c3627427f6f459a3ffbfebd28ccdd369739e91f.nq.gz
│   ├── 9f6ffa1a8ebca28158539e69ba62620d254fb2c8.nq.gz
│   ├── abebb14fe3f7f3e00ec266a6ae141cd76977ba70.nq.gz
│   ├── abf7357a417327940afdad7eeed02338aa8c07ba.nq.gz
│   ├── ac9f0bfa52aed51dca40471f93b6fd28a69575af.nq.gz
│   ├── ae03afc20049b2cec6e9a8ab36671006f4c9a42f.nq.gz
│   ├── b02a2a1410b1c815277a38af259e674942b0ffd3.nq.gz
│   ├── b2575bf48564d5919c05ae1895e928f4ca2896bd.nq.gz
│   ├── b7465425be39f849b33108247b19cc878083963b.nq.gz
│   ├── b83871f4c680141ae7b7d5a27f0a1a6991f01b53.nq.gz
│   ├── b85fda6921cddc95dab9f171810229da0fcd2e09.nq.gz
│   ├── b870393f4782580a57a401d9ce9c5ac9b72dbcfe.nq.gz
│   ├── b92226850808e00f47ca5d7a7b86ff86b490944a.nq.gz
│   ├── be741ab79f7b39fde76be96775e030b4c5146aa3.nq.gz
│   ├── becd8518b0865feba60a17765ffbb2a09edb4878.nq.gz
│   ├── bf30b8658ff17437d8f1b1d434fd7da5a99c529a.nq.gz
│   ├── bfe138161442e6b93120559835b10f6df421bd2c.nq.gz
│   ├── c5aad5c26f97ec9419cc1b2b63a8abcb3d33a672.nq.gz
│   ├── c9433636bd84a1ace0c451c1b95f7a704f2db80c.nq.gz
│   ├── c950ba585fa59686064dafd4a4945a32885c578a.nq.gz
│   ├── cfb7d932914fb2df698dfd6b17467fd49774b583.nq.gz
│   ├── d101494f05d5f19cf3fdd1ae1975304c2ec77b50.nq.gz
│   ├── d93484f17d41c713a19fbc4f51927abacc60d74a.nq.gz
│   ├── dc35e0ef23d83a898173da2bdfd26ccb94c3d2ef.nq.gz
│   ├── dc935d6120c421a99f74699d91f410a7a32d50c8.nq.gz
│   ├── e219d8fe5ddc28671ba2fd164f8ac7a7aede30dc.nq.gz
│   ├── e220e42d9c18f3dea6839d985ac0c9567a7e2e76.nq.gz
│   ├── e2c1173f028ffef147bf0e5e2991c0d83533fa77.nq.gz
│   ├── e3059a613c2c962a2b48e94f24f55aacf130f19b.nq.gz
│   ├── e42fd579c5310fd31767f038343aad44180aee1a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ecf975e2fa63a1383916f0c755e0db3e0b3d62b2.nq.gz
│   ├── eea6e76f63f432f51fcf4b6cc9a8551213e1f8fb.nq.gz
│   ├── f31c26e2c44d4607c48627a08c635eff0ce36d9d.nq.gz
│   ├── f335c16e85e831fc89e18c13d26ef5e303c2459f.nq.gz
│   ├── f51957ca588a8698dc3dd193716cec084cd82e34.nq.gz
│   ├── f5e289dc62630ab1112759dd6c5eda43259a4106.nq.gz
│   ├── f8aa21b0c1cfe51ae7bce3d69f9963f2284fc6e1.nq.gz
│   ├── fd903050dacf128077b0c09df1ac663de4434c19.nq.gz
│   └── fe785000a52a55a9c6e30f4029e25491e240213a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ba525b1ab000805cd26591cdd784b95f94017233.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 105 files
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

[django-treebeard/django-treebeard](https://github.com/django-treebeard/django-treebeard)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
