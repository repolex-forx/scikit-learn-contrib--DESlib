# Repolex Knowledge Graph of scikit-learn-contrib/DESlib

RDF knowledge graph data for [scikit-learn-contrib/DESlib](https://github.com/scikit-learn-contrib/DESlib), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-learn-contrib/DESlib
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d0eaeec4f60dfc98a306620a258d68fd4d7331ef
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d0eaeec4f60dfc98a306620a258d68fd4d7331ef
│           └── chunk-001.nq.gz
├── blob
│   ├── 0015f8a7c5a764713b1f753fb8927f587813e136.nq.gz
│   ├── 0415ca040d3c7a37ca1730c150023538e85e264b.nq.gz
│   ├── 05262f9dd41a3000245325282d11bbbda427aee5.nq.gz
│   ├── 059facfb841f5fec09ad24955fb0b740c40a2232.nq.gz
│   ├── 06bcb450c79e185690873047a03201b7e008dbf0.nq.gz
│   ├── 0b8c399b99969eb0180802f886c7e802615130e9.nq.gz
│   ├── 0d3ad2a8c9f05421bd385a41fe0253f9e61c1fb7.nq.gz
│   ├── 15406a41db764a98cec53f9db64ebcadaccd1ebe.nq.gz
│   ├── 15cc533ba2a74baf6c7cbd021473924d5c406194.nq.gz
│   ├── 15e961a451274b5f6dc6556bf19df679b875644b.nq.gz
│   ├── 1b6bc7a320c495b47d5697b2cceefe0aea81dfa0.nq.gz
│   ├── 1bdce0b746acb1c0dd72cf921009d7e63b4b7a28.nq.gz
│   ├── 1d0d47773d20a67af0485ad908a374cd336732cd.nq.gz
│   ├── 1e53ddbb9599830aa17d6e2f7109644bd43401af.nq.gz
│   ├── 20d15653aa80f246925d71a194c120b5eee91c4b.nq.gz
│   ├── 229717f93b008494cf1665ca58bb0bbe3369cfae.nq.gz
│   ├── 23e668656b6d3b4afd303014f0a6858ceab77569.nq.gz
│   ├── 24e5b9bb16bd9ceaa3f01ecfc9c5e2b39ccdd511.nq.gz
│   ├── 2584474453d15e6af324c47164853de1877c00b4.nq.gz
│   ├── 25e243d7f2e35b2e036f02a4816ec27c2820f637.nq.gz
│   ├── 28224e54d8b2fe544a199376f49ec0ef65b784de.nq.gz
│   ├── 28792959f2611853c5ad48026f3fe1918cd62c5e.nq.gz
│   ├── 298f0d3f70e8f438bbddd6d03765b3eaa4809f80.nq.gz
│   ├── 2adaffe1f308db270ca560bf0a88d3ccbbd0886c.nq.gz
│   ├── 2aec4d5f0485c1f4a49cc659c8bf83e410276947.nq.gz
│   ├── 2cb7026985a3f3f293a39819f324e942fd68a6d9.nq.gz
│   ├── 2d4d4fcad6f7daa1aa0d9a38dc293d3ef83a07c6.nq.gz
│   ├── 2f16d66b93906901d0162f54a422c415064d45b8.nq.gz
│   ├── 30799235a6cbf78d53a858aa61f0c0fa96d7df49.nq.gz
│   ├── 33baac745f9753f78ae7c8493ef27fd686001b64.nq.gz
│   ├── 344dcade73f91eed369d4e38ef33f0b2ebe6ac05.nq.gz
│   ├── 364aabe2e244b3fbfc5117e8c3c87520b3a853bf.nq.gz
│   ├── 368800959c133e65288bc607bf1a79137936e7d1.nq.gz
│   ├── 37411fedf8a537bca734f1a48f93573e07a5e79f.nq.gz
│   ├── 37c894da9facfeddb40f61f7750961f8bd53204a.nq.gz
│   ├── 38542d1106f7e2f1f81e3cbcb8b5acd8fd6b0d48.nq.gz
│   ├── 39db387653109febf1ed2ef3f14b914a41384cec.nq.gz
│   ├── 3bc518abb48722b867c6f58204d662e520bc9e11.nq.gz
│   ├── 3e419d95d7a758607a2ef21b2728b5272be2d7e1.nq.gz
│   ├── 400ceda0206fccc36c5a38fd32dd36f5756180ea.nq.gz
│   ├── 438d073409e8ed95dd2feafe793e30694207b583.nq.gz
│   ├── 43f0e31989269d90f9a3ee7035135ceabdab2759.nq.gz
│   ├── 44b788911547601632a61b69ac69528797101b85.nq.gz
│   ├── 456faa513b7621e3154e93ff13c69df50e822d23.nq.gz
│   ├── 482d4c9b4c5927bc6ed6cbd31c0cbe3b35fc869a.nq.gz
│   ├── 4cdd84b08239f151fd95696923ee1f47fee5cdcd.nq.gz
│   ├── 4d1b54343d375c8fc716bc54341a25805c83ec10.nq.gz
│   ├── 4d8c076b2af16f4cc655ec30e6bc57329b0248f8.nq.gz
│   ├── 4df05fc6675a02d9b94e9ccfbf11c8416bc41a8b.nq.gz
│   ├── 4dfaec54ac9bdceeb2a344bc1c7118be12798a5f.nq.gz
│   ├── 5091eea9ff50d6b4a8d784caaa7c66f1c5a3d925.nq.gz
│   ├── 54daceca40292644c2deca88acf147b33838f262.nq.gz
│   ├── 551cfe3b7474fa553e8d9d8111210d89df15b831.nq.gz
│   ├── 5629a2b7acf7912438eea72a023d2c20d6719220.nq.gz
│   ├── 56c449e4524784c508e14cded20fd18d5a76b044.nq.gz
│   ├── 5870ed7c23890fac5082b01b04a8f2fe1e781d49.nq.gz
│   ├── 595dccc878d48140a5c8b9cb2aafa8504846741f.nq.gz
│   ├── 59dfdd47c7bdc9592dde030555eeee80776a4a15.nq.gz
│   ├── 5a27f6e16e69013257d5224b8de879f7691ae777.nq.gz
│   ├── 5ba81e136bd93bd3c075dede1be838a7498cab09.nq.gz
│   ├── 5bc8d7b220908c2568286836df7c20d95abbeb45.nq.gz
│   ├── 5e0d90f3562a35b97d4b7e9d78ba69f8a1f26eda.nq.gz
│   ├── 5eae90dc18bbff2947578f0fc2f6b332a1a722a7.nq.gz
│   ├── 5fe0388fb680bfee53406a8183d2ffb7ce0f6428.nq.gz
│   ├── 633f382121cd18b39f1bf31e4fe535f6f2d90388.nq.gz
│   ├── 6371558a5e6ada279107d994b35259c74df6cb35.nq.gz
│   ├── 67601f42b8ecd14dc6f669f5d1f90816828d60fe.nq.gz
│   ├── 689d8c92548474db29391e47618c4480c5a629b0.nq.gz
│   ├── 6a06f6555134e68d1da903eed4ae795f8fe595ce.nq.gz
│   ├── 6cb55e84d3d3d186229d23d9e8a96d53675fbe77.nq.gz
│   ├── 6cdf86ee6a5a507017d32235fcc13861f9680dcb.nq.gz
│   ├── 6ec024219483be37b986e7bc6ffb0f44e6cd7099.nq.gz
│   ├── 6f2ad35532dfded9e98a848553ca04979e644c94.nq.gz
│   ├── 6f5319604204dc69eb0a205a9c5a9b77e9d16c91.nq.gz
│   ├── 7060398e168642a7e7fa380ef69b90f75d931b2e.nq.gz
│   ├── 70f744866f31ee3d6b6d35e07aea19e39b642e01.nq.gz
│   ├── 71a0ab5372c8177771fc6967d0cdbc98b63dbd91.nq.gz
│   ├── 71a6e19a6fa7fbfdc11494008fd9e978265703ba.nq.gz
│   ├── 7217070ad07d7e5c1d06c4ec7f62224a2455d571.nq.gz
│   ├── 753acdcfbc4f3b4357a65f49d19f80cc069fd5e0.nq.gz
│   ├── 768e0fab75a1e3a919b967902317b5d60d67a31d.nq.gz
│   ├── 7b80292d5e3c0de5e2fbab4a93808e50848d31b2.nq.gz
│   ├── 7cc35fbb8e27682e2ab65b82b583bc5f03cc37ba.nq.gz
│   ├── 7df2de3546801e69fee444a20e6f9b777f0bd078.nq.gz
│   ├── 7f9b4665c0cde24391504d00726a6bb121ca8915.nq.gz
│   ├── 823bc67dbea1977b1506b6e42939bfdec64cc749.nq.gz
│   ├── 82dd981e0f8028d9af2b9f89960832e694d957b4.nq.gz
│   ├── 8639cdd873ac867068fc52954bf39d4f7ce5f396.nq.gz
│   ├── 87204a9df231382b6670430ca4384f0e79b1628e.nq.gz
│   ├── 8b7cc3c60fb6dc8f8f1771ef5623585f497201e3.nq.gz
│   ├── 8cd7fea23c5754d72c0b76d5395d43cf38fcdaf6.nq.gz
│   ├── 8d75c301c3178e6762108fa836236c4e2620e102.nq.gz
│   ├── 8ddbf20d33587eec73a5591c39bae25678f13772.nq.gz
│   ├── 916fd4f406b4f1727482534f856db69b9685e5ed.nq.gz
│   ├── 935512e535625d4e7a5077ad87217e3cccaf1a6a.nq.gz
│   ├── 95aa027af688fe96938f9a438500668ea06b0d24.nq.gz
│   ├── 990d924679037efcc69c886af9758fc3ef20e993.nq.gz
│   ├── 9a52ca002a64656d71b9854c80d235d458eb9b03.nq.gz
│   ├── 9ad85a775cc91e77c62a1e2f698cd20e2d67b78f.nq.gz
│   ├── 9bd34cf03e9f8b9dce2e11fb52f16dddbbdb5028.nq.gz
│   ├── 9c1c71a8701bd0d56c8cb36d16a799103f1f567d.nq.gz
│   ├── 9d89c6bbb0e09805d1ddac509f0ec6c9bc10d484.nq.gz
│   ├── 9f3f973a71d3986e68c3a5f7211c6a5582ed4128.nq.gz
│   ├── a254a71c102e60c1d287286344f6e08b4eb92218.nq.gz
│   ├── a26a472ddded81a52eeec3a495ec7d16e3f6282e.nq.gz
│   ├── a29b3d7ab7cb052956a0c7a66c77d07bc704167c.nq.gz
│   ├── a3310c82b677b80c571328b26154cabe1316976f.nq.gz
│   ├── a471fe504d641ce54e6c7440dc20a9f2bae50edf.nq.gz
│   ├── abd2a919c981c5c70b9e73f6fcf7225d5611a220.nq.gz
│   ├── ac44355169b296da08a622e01cd4b9c749538833.nq.gz
│   ├── ace89bf03c8756b08de69babeeb3a93a4dc5ad78.nq.gz
│   ├── adf3fc1eb3299977366e939e5c9bf8549ab2e7fa.nq.gz
│   ├── ae5b526cf8f247997f42fc751f32d62baeafa986.nq.gz
│   ├── b1a7816066e8e661e037932c1b9b0a1118b11e6f.nq.gz
│   ├── b213d4dfa5c4adf31103b56e9b7a0004e717adbb.nq.gz
│   ├── b25ededca897725095a6e5a4a8d7901c54ebb2d8.nq.gz
│   ├── b3c6703f571f3b7ddb74d596deb0b6f5a412b680.nq.gz
│   ├── b54e6446b4ec843b26a461536ad5072d80e68520.nq.gz
│   ├── b68175fecd0d1f6db5b60cda26a6b26f28884a68.nq.gz
│   ├── b724db0db674c8b397a03c90b3c34e7bdab415b9.nq.gz
│   ├── b7a65b3d83c075f9d208f22f4eccb2a6ca68ffa4.nq.gz
│   ├── b888839311e04d7f831e50970ca5c1940a758283.nq.gz
│   ├── bb2ff167b69c1a62920ed747af1589ec4e14de06.nq.gz
│   ├── bd492565847ba75819f5522d62af4d49c0e613d2.nq.gz
│   ├── bdeecd6439277b9f707f0e8fcd6a74756a51a55e.nq.gz
│   ├── bea79fe27fc94d17b2d9bfb24ee39adc888f5a96.nq.gz
│   ├── bfc2ecb13ba520a5b8bb703994cbb2b7ca4a2cb5.nq.gz
│   ├── c1769f3fe5b13a7e4cb0b6c973ca930b4de8a6f8.nq.gz
│   ├── c19bf87cf3ba3b41ebc5725822f42ed22f431b64.nq.gz
│   ├── c1cdc076e1cffdd2d7588461ace98c003f5dfcf2.nq.gz
│   ├── c48a4754f670c16985c58ce96de4f4b8dd6753ab.nq.gz
│   ├── c4be93235ac989e36cca5bb9bbf03004247ce440.nq.gz
│   ├── c7576f1c3217460df7deb8fed964089d3903786c.nq.gz
│   ├── c80e66478a191970b80a39673add36e4b22e0638.nq.gz
│   ├── c9ed9434cf83694b4ffb114f096de8ec53990f1b.nq.gz
│   ├── cb0c56cf1dee8a112c864ffb7f0afefe59446721.nq.gz
│   ├── cb61e4ff65fcca9a31e9d2d319c137c80e28ea74.nq.gz
│   ├── cc4185266e331f737f2b0a3069d8cfd19f09e43b.nq.gz
│   ├── cd574f52c0eb81198f56384d9503a2d9a78d12a6.nq.gz
│   ├── cdfd56297a6851853d2d32146e10bef7cc23336a.nq.gz
│   ├── ce00ba0e1dd5211a8e8e65a8da6c71602e74cc46.nq.gz
│   ├── d04043d305f6e6582846a828db995f9649a8c863.nq.gz
│   ├── d2c3d21a063c1c8413840276117af9b5ba911725.nq.gz
│   ├── d361c82b93658d27283abe29634efabce23d4da0.nq.gz
│   ├── d5b434ea3f84430dd5cd7b008c0ed07eb285ad42.nq.gz
│   ├── d7352bc3aa0762956b2066571adeac75b6c737cc.nq.gz
│   ├── d87e710ab5464211300033539d4c24e453ba5010.nq.gz
│   ├── d8fb23c6a026e4c0dff078bbcd6a3d7511240f28.nq.gz
│   ├── e0b8dbc0c092952c9e83b2f41fbd999dc567d756.nq.gz
│   ├── e14944e1cfa693f13f0e26d058ad7735fae72887.nq.gz
│   ├── e2e441d7ccaaf8961d64b07535571c2b8cd52979.nq.gz
│   ├── e35d8850c9688b1ce82711694692cc574a799396.nq.gz
│   ├── e65b8055e16a47f5c19a5f9da80da2f86a9a2908.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8838724eb2fa4f50c325734483d64ce780a4f27.nq.gz
│   ├── eb0c0d9a6406e076b346e6a829c1fdedf74f42cc.nq.gz
│   ├── eb5415fceaa161e8d3671ac3297752dbd562330c.nq.gz
│   ├── eb57a7a417aa78089ba055a57431d0b43d16c9b6.nq.gz
│   ├── ee83da5a3b914a07b421f9fb3f2e2dba57e4122c.nq.gz
│   ├── eed213f1b30367213989d86d95d4b18f103ea60e.nq.gz
│   ├── ef49b5e0dd463bd23e4e0e4553039837123dc404.nq.gz
│   ├── f3815661323e90d8d69b77384244747601f329f1.nq.gz
│   ├── f4e19772c5d2121ac00f9f42c08426df38462565.nq.gz
│   ├── f51b73ab80a14cfad65bf8f0e4417bc74412dbac.nq.gz
│   ├── f5fc1487f9b14865be128cbf5fe591b650db0bee.nq.gz
│   ├── f678d26d2f9fe7349e941e0e4d5fa990bf6b328a.nq.gz
│   ├── f69bc9ee33ec8faf0ffb26b8d8775f6ccd2b66d9.nq.gz
│   ├── f7003e2d87af3a6d515755b906bf350880af30e5.nq.gz
│   ├── f72f9a4a69b96f55bb307eba6b52d42fd43306b8.nq.gz
│   ├── f74f4a20438894d5372d3a75ff041c9bab4ba901.nq.gz
│   ├── fadd504a587df561e4bb771a0da93e12191dab84.nq.gz
│   ├── ff1e9dd06859c8f623e4bfe96b492d14ba3ae7c0.nq.gz
│   └── ff4c5f606582be814c7555c7af3997251c255be7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d0eaeec4f60dfc98a306620a258d68fd4d7331ef.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 181 files
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

[scikit-learn-contrib/DESlib](https://github.com/scikit-learn-contrib/DESlib)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
