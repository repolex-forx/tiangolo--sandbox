# Repolex Knowledge Graph of tiangolo/sandbox

RDF knowledge graph data for [tiangolo/sandbox](https://github.com/tiangolo/sandbox), parsed by [repolex](https://repolex.ai).

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
rlex download tiangolo/sandbox
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3dfd81eba4f89f213c4779453dd3a59f134c8d11
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3dfd81eba4f89f213c4779453dd3a59f134c8d11
│           └── chunk-001.nq.gz
└── blob
    ├── 00888b5226bf07ace0ddf47f6e3e8b8de5a8603a.nq.gz
    ├── 00b0c52202b37de904b3fd9b5a5432c942ee171f.nq.gz
    ├── 01dc369a0b3c6b7390fb3ad6edda645e876a622b.nq.gz
    ├── 02183293ce2a631ba423efb07c2863bcb958e8bd.nq.gz
    ├── 037e9628fbea8115a4e26885ed2cacde4c3984d6.nq.gz
    ├── 03a7be3995aaa480ee443d7d41e12ecb40fea338.nq.gz
    ├── 03a98a5f37332a5d91053ac114a9633e7b34a91f.nq.gz
    ├── 042351e0b70719b2d04ae104232bcdea00a3dad4.nq.gz
    ├── 049c3ae934d62b9e8ab657e11ecb6ed9009bdbb6.nq.gz
    ├── 065439acceb7dec558776433d57d8499dfa0b2f3.nq.gz
    ├── 066d6be7a845148fb1189c45fb1d400b098b747c.nq.gz
    ├── 06744507b8e28ff4cf47c927e4a5b526deb64461.nq.gz
    ├── 06e45ad4c63bc6eca7d610eb0c477bed723e77fe.nq.gz
    ├── 0777263125499ffc75f3ddbf6fbf9aa4bb3afbfc.nq.gz
    ├── 080e9e67dcb3ddb869a5c0a181598a7a42e5dcaa.nq.gz
    ├── 08ab44a941b912f06a37770a12d4dc11996a617e.nq.gz
    ├── 09039435f1420488294da9dc03023bb24c4d0534.nq.gz
    ├── 0962061a60d0b01c91dd73165ca1cad34110fa38.nq.gz
    ├── 0a91a5967f816c7aef34d0f9cbf1524a30533e4f.nq.gz
    ├── 0b0f44869fd5fbec5a02beb102c870fb28a31fed.nq.gz
    ├── 0b74b10f81c8c2e83bee1baabe84ade3f9ee9355.nq.gz
    ├── 0c91470bc0a0336a1d0556b0c4b05aaa4971da22.nq.gz
    ├── 0cfd1b6632f0bad274578dd028a3b592f5cb8b02.nq.gz
    ├── 0d1136eb4dcab6eda0afbd5b843b12b6678966c6.nq.gz
    ├── 0d4bd8de57da331940460136db32c2f4ef359377.nq.gz
    ├── 0e78cf02903a1a0e22da3d9c9597a552fcccd066.nq.gz
    ├── 0e90f20126431224d087a4a8d06fdf7c4fe325f5.nq.gz
    ├── 0f074ccf32dccf837a76079671fc549691c1d20e.nq.gz
    ├── 0f09bdf77fdb865b6dea4b9f87e3a868ade995bf.nq.gz
    ├── 10bf26a577943629bb9614f87b1077e6410aac35.nq.gz
    ├── 10d3771c1ab406db89192037433156c9d6a83c33.nq.gz
    ├── 111e93458e686c670d229c371a5670b2714f336c.nq.gz
    ├── 11558b8e813f4e0afecc9bea846b8149ed10e674.nq.gz
    ├── 11dd656eaf31bd019585afa8feef345f345f1cc9.nq.gz
    ├── 121b8c830dac4b44acfd9ce32119ded80e28b6c3.nq.gz
    ├── 128004c9fb65ff35d84a97820b6c0d62d537a6e4.nq.gz
    ├── 1301aafa8835bca38f384f341bac8f5dc6245cc0.nq.gz
    ├── 14b6d6e675da76346b3c2d6eb46e62fe2e3175f1.nq.gz
    ├── 154606406a6a042acef4b47ffd0066b3b4fd5ecc.nq.gz
    ├── 156a1a0aceb9b9443362a953bc9c270f44aa9ae9.nq.gz
    ├── 1588556e788eccd43a04b6f6ebd18be78063bde5.nq.gz
    ├── 15fb6f3232ff10af4b3fbdc26e023bb9da440fcc.nq.gz
    ├── 163aa261424645d20674bceed29318ec7a014d2e.nq.gz
    ├── 166acb5869d046ebbcf66bfb63a6323343afbb3d.nq.gz
    ├── 16c78aa3fdb2fc2d45a4d6e2d6f7fe8399846a52.nq.gz
    ├── 17177dabf9e47db92c6c616a0ab24e568cbb3d6c.nq.gz
    ├── 1720a74333251208a04d39c7707225cba759bb88.nq.gz
    ├── 1782971922ab2fae5c4724ecb269f7f71b196f41.nq.gz
    ├── 17e017b7e7142b5b88ea37f1033e84f9ad7076f4.nq.gz
    ├── 1818946c4e0876c51b0e3a420a4fd5c8f1543634.nq.gz
    ├── 194f2dc233c274bca8e2b40ed27d26ad81bd96ac.nq.gz
    ├── 1a9e27ad4d8d00c2729d03d4274384fd87f06e92.nq.gz
    ├── 1b617efdd128a043e7f06ccb863b33fe92fc3986.nq.gz
    ├── 1bea246cdc68bbb854773a460c6fdcd1efea5de3.nq.gz
    ├── 1bee540f2bdc7ba781d41be430a848bc0d2bfea5.nq.gz
    ├── 1c0ac3a7b384ea64cb9196d9b8601d1388b3a43f.nq.gz
    ├── 1d9c434c368a5a078ed0e77779017edcb21587cb.nq.gz
    ├── 1dec555a944e560730aacf39a3707026d38fe3cd.nq.gz
    ├── 1e137101d9e465aef37b532f78d45dfadf95e2ea.nq.gz
    ├── 1e1722fa0be9afb9f547ced04ff7dcae59e48478.nq.gz
    ├── 1eec66d90a74b2e389b9ef7daea2fade94caa583.nq.gz
    ├── 1f28ea85b738a1b8550504c4c477f5e915cc74a4.nq.gz
    ├── 1fe1e7a33db994720262dd08ea0088d37bbef147.nq.gz
    ├── 20a6d144442107f8b6321094fa560404a760eb0c.nq.gz
    ├── 218fbb0ace13b9b70304bdcb0935ade97adb4366.nq.gz
    ├── 2238e3c94b7e6f214bad75d0bf2ddf2a4174e9f8.nq.gz
    ├── 224e59602e227e5fadfaac1de252db40137f17ec.nq.gz
    ├── 22a143623631078cff6922ab604f41dfb9b8bd57.nq.gz
    ├── 232355658f54ded0b634f0a6c360c1255d94968e.nq.gz
    ├── 23c048ab9403c390dc8f29d0d64dd18f60879457.nq.gz
    ├── 23c495867b6bb3cee5b6eac158a08797ddda7268.nq.gz
    ├── 245e7110b195d257b8a93b063124465627f1f765.nq.gz
    ├── 261e252d00009632fd522665c2a2289e1a375bfa.nq.gz
    ├── 268ce9019e9e8a57a4115821225a71fa311d7662.nq.gz
    ├── 26a767221629703f45fc89681628cc148faec102.nq.gz
    ├── 26bf7dabae2026bc2d2595203e7a5308743c72f5.nq.gz
    ├── 27200ee4bad47406671f6380d9e2b9f4f57d986d.nq.gz
    ├── 27618cd6b65a46809a6ad919a68e4f922789dc39.nq.gz
    ├── 27884960fea7fd8261c027dddf90a0cf2f7a431e.nq.gz
    ├── 27f6e127179cbceb02da41761f7489f10ed086a2.nq.gz
    ├── 281746b26599a709e3980fb2aefad76b62c68a70.nq.gz
    ├── 2894e2d51a2231c63af86981c53a142b2655d258.nq.gz
    ├── 29121ffd630bb48d190957446dfba84ff1e02b55.nq.gz
    ├── 2961e6178e7a6b45d1341f6ea2788bacc3685d85.nq.gz
    ├── 299d546aa09e7ed4c621558fc5e5fe381cdff1e0.nq.gz
    ├── 29cd772da14084edc3b7f7df004bc9dec4fb2285.nq.gz
    ├── 2b650590b0060e39a324f378adb36eaa7d669915.nq.gz
    ├── 2badd1c7d27acd0d678eb29838e182887572767f.nq.gz
    ├── 2c4eb824c8c6d0b71d0f12c1017a57aeab311e37.nq.gz
    ├── 2d7160ae8e2bedcc98fd3ff6b865f8ba832c2b6a.nq.gz
    ├── 2de86f042d461cd4655ce0b5ba6f1e30b659b140.nq.gz
    ├── 2e2416ce6558a4459a85d452a11c6f9f708ce4e0.nq.gz
    ├── 2fd82db75463654571071c756d3899091f879490.nq.gz
    ├── 300a3834ff47cc05997f78565eb48cba8758e09a.nq.gz
    ├── 30eb9f8e3fb785b0848f8a4383a35b04ec745714.nq.gz
    ├── 3162180889e8bf24d9de6c76ee8f865d9bab8c34.nq.gz
    ├── 31b2110afc8281046d20eb289e4cc332fe90d5ee.nq.gz
    ├── 332f8f87f1e53e7c108ca783f98ff67140452e1d.nq.gz
    ├── 3362715b39702c6d043d07f6701c4e18d4d40ff9.nq.gz
    ├── 33f8e8f6e996b4796363244d2671ff30a1f978b1.nq.gz
    ├── 3431cc6365d162c2821232bdb0bad9df3dc0295a.nq.gz
    ├── 34437db161fc34379d74259c092301e8a23611d8.nq.gz
    ├── 34614e5397fd01107df9f1b3f52fe318a3cfc42e.nq.gz
    ├── 348ffda0163e9b0359f4fd7d27c3b8e8f662056a.nq.gz
    ├── 34ce1199e52b70e4e87e76233ed8388548bb5f45.nq.gz
    ├── 35443d19470614a20268334a4bb07401f7fb0b98.nq.gz
    ├── 35b381cae040c0eb0cbb9ed9a63864726f1ed978.nq.gz
    ├── 3695de40c725e2823a058cc6d624dc1efa3c5f00.nq.gz
    ├── 3703bf888a605ed826ee489c0d3ce4719b837d43.nq.gz
    ├── 38618aeeb09cd51c5ca9e8f6bc5ac9af24b22dee.nq.gz
    ├── 38bfa455b83ac7b8f40768ff7c1b140172ea5fd4.nq.gz
    ├── 392ba32c8e43a8ddc03552343fc12e59089abc30.nq.gz
    ├── 39ae5aa92feabccd13bed13abb40ca75423fee4b.nq.gz
    ├── 39b3d7e7cf255d852836ca54d70ec428e4d35425.nq.gz
    ├── 3aaae9b3710c365637592a2b8d53d6ae40e70e71.nq.gz
    ├── 3ac6b44adcf4b0c28df130ca0e16c674ea43e229.nq.gz
    ├── 3b4ca99cf6b50532429f8db0813b125bb6482890.nq.gz
    ├── 3b7d8be018bfbaa526a8020089e3c773ac698732.nq.gz
    ├── 3cb64c0476f0f53b7db4ab350bfdf0decb073319.nq.gz
    ├── 3d4b1956af477ff520e226fc3880eaad1484fad2.nq.gz
    ├── 3d58f57fb631f6ecb1b681218b0a87f71463c97b.nq.gz
    ├── 3d94afe2c054f2fba2720d8bfdc141f59d237a6c.nq.gz
    ├── 3dda4fe3cde13966924e12f1f95f00f0076b5fda.nq.gz
    ├── 3de21d2a82054f39fef7644d3cb698b9d1023451.nq.gz
    ├── 3deba54d5605e83ecd51d58458d913e5e15417ca.nq.gz
    ├── 3e43f302621f98e914f1a9b60dd8f770a819c181.nq.gz
    ├── 3ffdb512bce7d905f5a1f34222e65ff9e420bb73.nq.gz
    ├── 406c00897c8d80ac78499a79e76085d9d7e7aff6.nq.gz
    ├── 433c69129fde98a332a844ae7340a9c1065206b2.nq.gz
    ├── 4437327f3bf828c28c35088957a5de39c5b4104e.nq.gz
    ├── 452d4d38d7826cee8785e8ff668cc87b7b94fbd4.nq.gz
    ├── 45aca8e217fee2975f9b79c58a6fd2133a9e9bff.nq.gz
    ├── 45f3fc0bd6de1334bed7cc64688fa54d337d4d41.nq.gz
    ├── 460352c7e1596648682ee75e16e6770ecead1d4d.nq.gz
    ├── 465bd659d52e1c7086a170ba202d2b91b16a0012.nq.gz
    ├── 468496f51932543e909a181a0cbe9c773acdf24c.nq.gz
    ├── 482af8dc06f74eb0f03b4c82f0f0c5a6eee4a3a4.nq.gz
    ├── 489f631d5e90875a5b9128dffbd7aac973c50317.nq.gz
    ├── 498d935fe70dd10c1f9e4d0578f5d778fc1cf1d6.nq.gz
    ├── 49eab73a1bf52c6b2dc38b6b322c37a6f426cef0.nq.gz
    ├── 4ac32708a31a0ee74ae1f03b48de8aa8790beb26.nq.gz
    ├── 4b324866f6850d76b2862b05e5bf2e7e44b662c1.nq.gz
    ├── 4ba5e1bfbe9e60098a81f3c66029a2c9b49ce02f.nq.gz
    ├── 4be9385ddf530094a0cbc97031f230118cd91c84.nq.gz
    ├── 4c76a87ff53f6baa1152c6ab457293e947548808.nq.gz
    ├── 4cb8bdd438ab16d74b0aa56093620f46c6337b4e.nq.gz
    ├── 4e65d77e262628351a588e1f681e521c57f8648e.nq.gz
    ├── 4f5f52cd3ab4aca15b6c0fc24193cbbf546c9206.nq.gz
    ├── 500afa34b289e2da5e6d78e97feeed3d00b57358.nq.gz
    ├── 509fbd34079f0ef97fba53bc44f2ddaa46e2b314.nq.gz
    ├── 50e0a6c2b18cebcf70b6b9229b2844666e5599e6.nq.gz
    ├── 51ad3c146b4962d1732093e684e5380e5450574d.nq.gz
    ├── 51daf58e5abc1ec6d1e5e21b38d7091abb65c10f.nq.gz
    ├── 5206744b7a6e45b8c541ea55941f47f84a63eaec.nq.gz
    ├── 52694b5510c700cc7e18332f046f7da93cfbbdca.nq.gz
    ├── 5289afce28862c94e758455e3008ce8ca13ff941.nq.gz
    ├── 5346b997bd09d28911198b7566bf2df8fbca5f5d.nq.gz
    ├── 537f49a2e62ac7902b3146aea7d668a43be89710.nq.gz
    ├── 5406fd1f88b633c881ebb71fcc8b821268db7e9e.nq.gz
    ├── 551539b32e95f595f7fb084f158b6559a830843c.nq.gz
    ├── 554e7c45664e4a8d12b2ac28712553f99f6ece49.nq.gz
    ├── 559480d2bfeb963ed52e501dce48d369e4e5f3c1.nq.gz
    ├── 567427c03e393b7235b2b5ca766e2ed676fc2624.nq.gz
    ├── 56c5875595aace53c41a49f85bbf893d301974ba.nq.gz
    ├── 571dd583ce5f31b9a6adde27e827e66253576694.nq.gz
    ├── 5765cf2d6261109a5fd929bc52e2f584f0e76688.nq.gz
    ├── 590f6f5e407ed2d569e77a44629521f22d7bb7a8.nq.gz
    ├── 5933911fdfaafe464e26fb5131543e56c5d0da8e.nq.gz
    ├── 593ff893cab725987abd0dfe743fb2beaf6a7fbe.nq.gz
    ├── 59c1e50828d2025cbc79bde718acc9ed3af02f44.nq.gz
    ├── 59e68dd07357878a76bd228b61fb62f201bd0236.nq.gz
    ├── 59fdd3d878e6a929e5d1642c2d5fc4c5bca44627.nq.gz
    ├── 5a01264eda859a68f8c5d30e563a5b99cf4096c8.nq.gz
    ├── 5aaea04d165708e83524e7f424c660abb8eb12e6.nq.gz
    ├── 5b591a6a73a26368774bc5338453d53f8fd48a14.nq.gz
    ├── 5b8ed7de3dcd67515f1e5371b79db5e66e493753.nq.gz
    ├── 5bbfd950df7c7f1a63fbfa40581f9d41eff91f04.nq.gz
    ├── 5c7612aa09eebba42a11b7a64e5de8c13b3b1b5d.nq.gz
    ├── 5d22f6823785c058849176f4c1de29a5382ab166.nq.gz
    ├── 5d6b6509a715f15c873a54f9ec521b392b8bfaff.nq.gz
    ├── 5d9fe6ddfd035f409b882a3bd2fbc6087ec73cd4.nq.gz
    ├── 5dad4bfde16d31ad9fbe83500d58aaccef65ccd6.nq.gz
    ├── 5dd89b212a2e4f887262bede0f49a59359a28c0d.nq.gz
    ├── 5de88ec3a13a8da483d09aa3adf310b691b446d0.nq.gz
    ├── 5f0aa09234cd609383884a18f519e433ed758b0b.nq.gz
    ├── 5f55add0a9b4989fcef19ba9002594ed282d8e10.nq.gz
    ├── 5f7e7061e49938d96fbf7a07d82bb9171eba9005.nq.gz
    ├── 5fba54150be79ca4c82026592a8b12abfecfc316.nq.gz
    ├── 602734145d4a6f1086a6be5728c21cc63d827630.nq.gz
    ├── 606d355fe1012e94b5e6de40c1decd953560d3ff.nq.gz
    ├── 607c5707e6e30ed6000b1c8b0daa34fc9c99a13b.nq.gz
    ├── 60ec9c92c620883131e50748b35b44fa65357f9f.nq.gz
    ├── 611a18cc4912053081a58d68c691604df5420861.nq.gz
    ├── 61be74fcb9a17a27ffa2efc1bf8eb279931c7e30.nq.gz
    ├── 621be7b04535c1c69e2687b1fe74a2bfa5bedb84.nq.gz
    ├── 626af13583a83d093dd6cd12f3871fb3dffb84bc.nq.gz
    ├── 62d8ab4aaac162b6603c02ec2aeb55b2add296e9.nq.gz
    └── 630d36ae31ee4c1c39230d1f10164ff6d796f722.nq.gz

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

[tiangolo/sandbox](https://github.com/tiangolo/sandbox)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
