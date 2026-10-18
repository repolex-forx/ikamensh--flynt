# Repolex Knowledge Graph of ikamensh/flynt

RDF knowledge graph data for [ikamensh/flynt](https://github.com/ikamensh/flynt), parsed by [repolex](https://repolex.ai).

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
rlex download ikamensh/flynt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 34ec5eb2d0a5d392c2eed4d81f716c5a3c5e3ac1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 34ec5eb2d0a5d392c2eed4d81f716c5a3c5e3ac1
│           └── chunk-001.nq.gz
└── blob
    ├── 007ec6d3d597ecf6da8ee46aac8b7d8d475be25c.nq.gz
    ├── 031e57e7a9a448738fdbc3d543ba56e5d2f1e029.nq.gz
    ├── 035893cc626799fe3b88e575bb77323386b22d26.nq.gz
    ├── 03d367ee708ddc51efe4f96329ec1be573486665.nq.gz
    ├── 04c77c471a1d3873c33380f1917bad4cfc3f0543.nq.gz
    ├── 04d15efdb4d81937a2196671208720882748854d.nq.gz
    ├── 04fb946ec24a806b59606fb464b54dd364b20c8f.nq.gz
    ├── 05cb329f9a44b2733a5a12ac04ed01ba9252f6c9.nq.gz
    ├── 07eec2f96657a2ed53f8a41d2497b0b5243bdc70.nq.gz
    ├── 09a12fc22cdaf0dd5528b7fc094180087e020f72.nq.gz
    ├── 09a37a1f146a9ec3047a9fd4c9056ab8cb746c1d.nq.gz
    ├── 09a93b389666b73f9806848d4451612d3fe153d2.nq.gz
    ├── 09e663af383793e7e4119cdbb2e047caa10a876a.nq.gz
    ├── 0a7a2896cd0c81df306800ac990633cf7524ad12.nq.gz
    ├── 0ebec825e790c58618118aa91281fb6a0fe41418.nq.gz
    ├── 0ee0713063c9f675d51e82ab5d9e2ff690bfe2bd.nq.gz
    ├── 0f00eee3828090d369057ae87e5723a16cc5adf1.nq.gz
    ├── 0fa0fcb325de484e6497261eca131d7042ede96e.nq.gz
    ├── 0ff81e2ddec08628b3734c70ccbe0b1aea47da4a.nq.gz
    ├── 105ce2da2d6447d11dfe32bfb846c3d5b199fc99.nq.gz
    ├── 108fb60a826ff84afba27a35951fe50710080c5c.nq.gz
    ├── 10aecfd88df6536bebae61b4c161f8245703e83d.nq.gz
    ├── 10b2892e36acf970e42c760234807f4741ac04ba.nq.gz
    ├── 11c2a48de35cb727e2f0a030e9f085f517c0ee54.nq.gz
    ├── 126e3154fea9c21634821b9355e6e60c7b1e257a.nq.gz
    ├── 1374adc6ce9fe99dbebfdfeb4e5c7b8762ba2550.nq.gz
    ├── 146d017bfc34223381361d2470e8ccadad84f5f6.nq.gz
    ├── 15096ae95f57de1da562e33f0191acc242639e60.nq.gz
    ├── 15c85546450615a01ddc6870fe1d1f2e70a4623e.nq.gz
    ├── 16245428a56f5ee68198e148afaa90b8bf197289.nq.gz
    ├── 17110191e45e3f9ec363ad8a14ced3dd840e754f.nq.gz
    ├── 176ef59c387c370c15f2c47ac9a899caef4440f5.nq.gz
    ├── 18054f6ae4999444dabe6451bf2cf2c3574e913f.nq.gz
    ├── 18f0b75eb9c20babc8c40e3b724992de23702e77.nq.gz
    ├── 1ae81a4062a63721e6960b3fb52641393d0073fc.nq.gz
    ├── 1c421711a59187effd6102a8eebcdf0cfec588b4.nq.gz
    ├── 1df078ea5138facc01c0de0e457f95b900d5a5f3.nq.gz
    ├── 1e4a950ab6175be56cd3b924b3041acbd4dfef59.nq.gz
    ├── 1f10e53dac76892f4e9bf5ef2f6bc9311d7e16b8.nq.gz
    ├── 22d1159fc48f124efd2128db058f01e4ad93fe65.nq.gz
    ├── 24f1f340538678eb9f260bea2ebdc87fe6837ea9.nq.gz
    ├── 255b647a4b8f4077e65d2d9f3349f74c20cb1bb5.nq.gz
    ├── 25c55ae9ddfb23a6a64d4dd230399f61556ad8af.nq.gz
    ├── 26e2f542fc71e18f19c064a02e4f9bd0bbcad500.nq.gz
    ├── 280713830aaa5ff876f0694efd5ee3c14e8d4d38.nq.gz
    ├── 28634b001a36c5fc5400284e7af7f0c5fb02f952.nq.gz
    ├── 29f82c70954bee799c6f2156bfcc9a343f1d3525.nq.gz
    ├── 2b7ab0b7089a30a1431e995217ab3d62f1fc6b33.nq.gz
    ├── 2c11a77f23effbf4d4bc50c68de96e7102cf2aef.nq.gz
    ├── 2dcb7f1241976a1bc24cdc227b6befe8a5ff4e6f.nq.gz
    ├── 2ea1e53d7faa29763d8e43e809cfdd810db87a64.nq.gz
    ├── 30cf57ed7cba5157ad5f7c05ede08adde945ada6.nq.gz
    ├── 326bf47307a31cabc2e4105f3df7899eaf33b4d3.nq.gz
    ├── 33941da860d6813c82475cc371b6fc5b66f27663.nq.gz
    ├── 33e86ed1a85649281df72338184daebbd4f9d6d8.nq.gz
    ├── 35531d1365273074ae2e4f56f3dd737b04504dc9.nq.gz
    ├── 35eb1ddfbbc029bcab630581847471d7f238ec53.nq.gz
    ├── 382da38fa521a047b4fa1eee4d2d2429afde82eb.nq.gz
    ├── 38d81d4f3878d4aade91cbb6474b49c5028ca0b9.nq.gz
    ├── 395a7c81a6a6f411b53d61754d869a3310c3628e.nq.gz
    ├── 3b25cb145e85d9561d736df5d0128894bb06a94a.nq.gz
    ├── 3c5aeaca93e7f6820489ff1b28e7130903792b4a.nq.gz
    ├── 3e2722673514055761488571712a429dc6b32d3c.nq.gz
    ├── 4044713c52f4509337a7540dee67dbaef11711c1.nq.gz
    ├── 40c4a573d301d64730016249d75ca011617c32c6.nq.gz
    ├── 413f505803192bed05388950c391b78c4c1f7ba9.nq.gz
    ├── 4620c386faa76bdceef019280571f47567355c20.nq.gz
    ├── 46475165c67dfee7644a6967e23e155d5774b98e.nq.gz
    ├── 46f73e740fd3bc7ebdc5dfff2558c12e5b0da6a6.nq.gz
    ├── 49551129721975c0461534ae5de2a1f3626851fa.nq.gz
    ├── 4d1640179b557c3b1205be4f969da7d6536ab3d9.nq.gz
    ├── 4e4a0118d4e0acd2832cd9d421a37408f8b61486.nq.gz
    ├── 5084359b0f1daf9f8d41d894072d40cadd8eb9d4.nq.gz
    ├── 524e7ada56d3dae82b5f107a87908043f28e859d.nq.gz
    ├── 52c06198bfc03daeb4112e103a4027526406c89c.nq.gz
    ├── 53f1c64e6405eb9464819c247381617541fdfa87.nq.gz
    ├── 554085e72bfaa575f0c9da5555b29a3580295d6d.nq.gz
    ├── 56303e1a45bdafa72d7bf7534009cebd8a63a6c0.nq.gz
    ├── 56309435203130ee56d2961358ecceac87bf4c2b.nq.gz
    ├── 56a6358655527ab6a681980929a17fa6d1ea567b.nq.gz
    ├── 579654af7648c0caf8fdb073ebd2c3e0fb569159.nq.gz
    ├── 5928b55479c2f47ab562aaf4fd99b5f25bcba8b8.nq.gz
    ├── 592e2f2877beecf1ba5535128ae8cb75dac39acb.nq.gz
    ├── 5b7876d6a5045b25085c6236812af5dd283e03ca.nq.gz
    ├── 5c37753e7cf70f275045d603c6f2f15f49c3a044.nq.gz
    ├── 5ddbef493ded7ea61c9ed72e6c2fcfc65de907bb.nq.gz
    ├── 5ec8c4c339ce7352ebb2d0a8e888064cda2c27d8.nq.gz
    ├── 623fee3b6f06ce51d1bb52a08071aca0dbe89c1b.nq.gz
    ├── 6241a81ee547f9cd7196b66ecfd466d8ec917600.nq.gz
    ├── 6273d9433f1c12714f2a984679186b0ff7c88703.nq.gz
    ├── 652367b8b30ad43d0112da4bcb2f38f8438757f1.nq.gz
    ├── 6641807020f1f9924620eca37676f3f9b1b36dc5.nq.gz
    ├── 66ad1425b91fdb0796e08fe6291f93ee7d61be2d.nq.gz
    ├── 678b041e540011a7c81b46904e99b1ee3def4048.nq.gz
    ├── 6856467f4f230461d9a24e2357a5d51ab86d4bc6.nq.gz
    ├── 691dd207faedf1c552a33c1f719e6ab3deeb526c.nq.gz
    ├── 6a495e6ad4f389fec666c176c33384bc0ff40e88.nq.gz
    ├── 6aaca2de9de03d8870be63869f0351941954b30b.nq.gz
    ├── 6c4dd6420e85b3cb4f6f40db9ab030e1a5a9cb55.nq.gz
    ├── 6e1e6c46e10779edc5597f4180b14fffb1b87537.nq.gz
    ├── 6eeb4cc2f9701b086f79b4f9074deeace9befaa3.nq.gz
    ├── 6f6e6562dd82dceeb67fedfde75394809cc4841a.nq.gz
    ├── 6f8f2d0cf4c9426845f89c1f29c6ec3ed66353f7.nq.gz
    ├── 707f723851a1fd8ead216def37b7ccb54d60dcaa.nq.gz
    ├── 70fef47789362d425466edb06c1c4c3cae229208.nq.gz
    ├── 72c666c12bab8d960b6624b460a48c97089026a2.nq.gz
    ├── 7483f13be63020c1054810cd093f38f49e9bd18a.nq.gz
    ├── 754e6c3b62024b926232ea0df3fcf6fb91e5f5ab.nq.gz
    ├── 75c20b977e2fd31bd2f029231b137bd81264da72.nq.gz
    ├── 7846e1f5d0af90923e9c6ae0ebb9d60861e3d17f.nq.gz
    ├── 791102a6e185eb0632e5b9cb0b2349f4171eb3bf.nq.gz
    ├── 791da7b28922d2038ec9eb9524f1355a5a278870.nq.gz
    ├── 79ec3f3981707d713628f1a708d14b608c00d522.nq.gz
    ├── 7a6fef6acfbe305172f190a153d68b6a5c9ac45c.nq.gz
    ├── 7aec019768fd5b290fe96c0e914d50a38d3764d5.nq.gz
    ├── 7be5992e0a7004f6c344f2eb6b7d4ff09d7eb58e.nq.gz
    ├── 7c02cc241fb036a11c5d4043e56c1cd93d7ce267.nq.gz
    ├── 7efdb5e041e5ac7a51dad9560ec80c85ac2503ba.nq.gz
    ├── 7fe389744909ed840f691d52fb6931d81a92daa4.nq.gz
    ├── 80876433c00c1432de05cd73b62931873aa46756.nq.gz
    ├── 81767797801a6a027b36208d41505586f37be43d.nq.gz
    ├── 81994a9b40b25527a3ec6a4a7360dde4d8585b6d.nq.gz
    ├── 822bdd4a02e918475a5b3abc800e08b1ee9c7b6f.nq.gz
    ├── 826d8824352d75ff89dfc0686f5511a6365a0f24.nq.gz
    ├── 84321920c9505ce64c248f630f2e6bf5f1c18982.nq.gz
    ├── 852239ed851c730dac75389fae9c36768e85b221.nq.gz
    ├── 853164883479fa1a3d8a3fb8a6a19301c4ff142f.nq.gz
    ├── 86683da24f42506ad5de21c825b3e9193fe8ecc2.nq.gz
    ├── 86c4270d9faf9627cd34603ce10f50693d97388d.nq.gz
    ├── 8886497bd66fc494f7b580c332bc53de8dfe4bd0.nq.gz
    ├── 8992aa16014b80b7b0d946d5c7108f0d21a3c55a.nq.gz
    ├── 8ce7c5635b39b62f2b6185ea5c660adb7d5468ed.nq.gz
    ├── 8dad6c58d068a1abe5a00ac3d6b41c597428bc26.nq.gz
    ├── 8ee16f1699757d86a22bad5b8d258a7199ed02c9.nq.gz
    ├── 8f3c897a3b795f0d0c94f21d9974646136632ad7.nq.gz
    ├── 8f51ce9af331ffcf2d6de4936a42de1aa5cc0fd9.nq.gz
    ├── 949cf037732400a32f59edf7eaa2b2eeb75c3c8c.nq.gz
    ├── 9518389d3295d0c315691b786cc4f144a1c342f7.nq.gz
    ├── 9801ccb88a26d9659353026de0c0b0bf27545586.nq.gz
    ├── 9889afe60dbddbe121f27cd3470c9dc5415be7e9.nq.gz
    ├── 9965a2ff16b485ee52ed44913d7c6732504d98db.nq.gz
    ├── 9a5661ce9495a36af04f2095e8479396c45e640a.nq.gz
    ├── 9c81222006c4643e9d6fbfa53a8dfb02b8a24484.nq.gz
    ├── 9fbaf0a8b4f6edc13bc281063db128c244786802.nq.gz
    ├── 9fc5af920a65400885ec1b278d4cbfd36e3ed0f0.nq.gz
    ├── a09acf8b16d871d51d35af176daf0c854a68a666.nq.gz
    ├── a2e7272ec6b118e79a3b3fef6645017db5ffc6fd.nq.gz
    ├── a32eb589239ac9231ce9a9e9bd4a086c001f28f6.nq.gz
    ├── a3ef241fde952592875f24d085abfe60879bc83f.nq.gz
    ├── a63b10e8fb96d0c78d8ea1fd15a163e023bfce34.nq.gz
    ├── a69e60329f3ad2a325f89b11f5077a7133f11def.nq.gz
    ├── a7cc445902dc5e9c0b9e607a5e9d34afb11940f6.nq.gz
    ├── ab3033b415de1834f29f4e3ffeb80b3419602726.nq.gz
    ├── ad57bd7f4be8a0f18ca30d3de697f52d69274f41.nq.gz
    ├── ad971ad946224769815a1f9f6a195da2cdb65efb.nq.gz
    ├── afc9d9ac625fdee710cb862c1b697e8f7dcf5ed7.nq.gz
    ├── b1595fd7d8e758cb0d4532ae1f97a3094e002741.nq.gz
    ├── b2de091d2f82839121aa0111fddd5a66bb77199b.nq.gz
    ├── b3f4647dd857f22b6e49a7f40e7c96cfa7b31494.nq.gz
    ├── b40f704c8390b6cb53dab4cfed5df21578374cab.nq.gz
    ├── b591e579c48489d8d0a0f4b71cf80d5acb77ddf7.nq.gz
    ├── b5c7b3578abc2406e3b4755a4d57ceea0f1faef1.nq.gz
    ├── b7563c7aff76b4d1b1a434610ee0fe785e07a875.nq.gz
    ├── b7af2fd3dde263bc21290db2575d53927e19994e.nq.gz
    ├── b7ce7ef574ea12dd67ae8cb632173648e6918295.nq.gz
    ├── b7e1c7d0d250ae013998aedf6da6c03c4a8f2bda.nq.gz
    ├── b85daf0b9b8f6b37c76289246b2c2781d54e409b.nq.gz
    ├── bae5a42ce1d8a485005ba452f40722e86372c039.nq.gz
    ├── bd1789fd1a99f9b7f73a07c0a6983117554e0060.nq.gz
    ├── be006de9a1ae3b9628e796c74277cd6d61e0a34a.nq.gz
    ├── c06f494bf7d998eaa919f816dd11c7827f538c23.nq.gz
    ├── c0784749179056ef2880361ef8dee01874dbf621.nq.gz
    ├── c0c40e89dd863193f5cf5a1e27dc1b619eb84e22.nq.gz
    ├── c1483d5e82525b427f21d8195cebf20a42a39ea1.nq.gz
    ├── c2879c93f955232a0eaba2ad7b687af691decff7.nq.gz
    ├── c29d24fb812d2187c747c3520cf16391f6ca391b.nq.gz
    ├── c620cae68db4a84def7aa8a668ade4677313ca71.nq.gz
    ├── c63e6e6f0bad46f5a585b1e817fb3552e05f00c3.nq.gz
    ├── c943f73cf9102c918106bde598ecfb3613968bae.nq.gz
    ├── cb84b368eb2ee70efd9345172f308a055ebf8865.nq.gz
    ├── cde3556733b806ef58a80cb58e90c03d3c675f7f.nq.gz
    ├── ce4502a31e4fff1138d389003114a22dc37a380c.nq.gz
    ├── d09806c5c281eebb0e29886d432ceeec4300db70.nq.gz
    ├── d1d17a4382ff8f330d67a4e6b6ba0f9e76e8f2e2.nq.gz
    ├── d45dc5de181ffd02e49685955be7b229aac331e1.nq.gz
    ├── d4b6f9c9964f57fa8eb48ab0c4e89c42427e3310.nq.gz
    ├── d689c100661c24aba1597a299934dfd50274e491.nq.gz
    ├── d6acd25a249bd4c398f0e40c543fb5f54f608976.nq.gz
    ├── dbe155e1a8cb159afb09c36b45cdd7b59eaf66dd.nq.gz
    ├── dc2fe494dc7b3362ed090361408c9f07666a8d60.nq.gz
    ├── dc883fac5f6ed786dbf4bd34d67f43f4310863ca.nq.gz
    ├── dec8593d50b6c9ee06c1226a84efb3081bee2e89.nq.gz
    ├── dfecc46b54541f0f124cfbbbdec67ccf1c891b12.nq.gz
    ├── e1964c3ccca52389d9621ca7bdef06c201f90793.nq.gz
    ├── e1bf9b1d27ea4e8ca95f32728c965f7e4b1dc1f5.nq.gz
    ├── e2378eebf228fac7e21f727f1dea84dbfb7058e9.nq.gz
    ├── e27ed59ac24db487fed405da9c146a8c03803a64.nq.gz
    └── e4ed02c26ba211a3232b2b8a44e5c251b8b87bff.nq.gz

7 directories, 200 files
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

[ikamensh/flynt](https://github.com/ikamensh/flynt)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
