# Repolex Knowledge Graph of truera/trulens

RDF knowledge graph data for [truera/trulens](https://github.com/truera/trulens), parsed by [repolex](https://repolex.ai).

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
rlex download truera/trulens
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 86893205ee4ae749444df8d59d5a3d73d5bec4a3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 86893205ee4ae749444df8d59d5a3d73d5bec4a3
│           └── chunk-001.nq.gz
└── blob
    ├── 004b6fd3f8ce814eb3b741fe5442e06890267a0d.nq.gz
    ├── 00b29359b9ead17a1a9982a6b3216a7918b2fe2a.nq.gz
    ├── 014beaf6a0410654cf4b8bbad8a5e28d6768d348.nq.gz
    ├── 014eadba4ea14f084278e910aa4ab2ff58e564c4.nq.gz
    ├── 01bbe7b9b255494d36c03e83454bd50b071fa325.nq.gz
    ├── 01ffa3b64d538c396aa6cab9788d5968db8220ac.nq.gz
    ├── 0212451922df21c7ace61d198a263c5ac567640d.nq.gz
    ├── 0284370fc83af870d8d158bb660b82b563d5140e.nq.gz
    ├── 02e65d5677bb2bfdc654f6ab5c8ead837affa7b4.nq.gz
    ├── 038074e52d3217b2a1083ae16b8af89d9ed86f30.nq.gz
    ├── 03852e0eef083e2c39510d3014c0f4a4c459afca.nq.gz
    ├── 039be871da362c3f67fe58d2547547f2d80d92ee.nq.gz
    ├── 03e6c670e464b435b0d4a980188baad1dd0e1b82.nq.gz
    ├── 03e98056e90a309492b6d99a243e26d94dbb2959.nq.gz
    ├── 0489073ece65fe7f31955c88a2d09e3beb77870f.nq.gz
    ├── 06bb7e15fc09a1cfcaf5b5d37332cded3c2a729f.nq.gz
    ├── 075a3d6c62271de4a41f0e7758fd657f8e6b4e53.nq.gz
    ├── 080f2adedda6eeedeba28aba37cbbea79c7d788c.nq.gz
    ├── 091d027c6d6c3b6cab1614e7e1cbb8b093799951.nq.gz
    ├── 0ab35872d765407fc4c9d7dd711573ca38e51f79.nq.gz
    ├── 0b545eb09908e2bf1a5bd3fec880ce381de39725.nq.gz
    ├── 0b5a4fc5cdd39437f3fc0b3bf9907e34171bf5f2.nq.gz
    ├── 0bab10db336bfcb7925f0cb2fe13f2bb7e7a2434.nq.gz
    ├── 0bb891f3d5fa88c24ef397533026c23aaef88291.nq.gz
    ├── 0c14c3ba8650704fa328b1f5522126d9ae20cb36.nq.gz
    ├── 0c1f49787727fff1f2595a7493ed50bbb2f292b4.nq.gz
    ├── 0d0aeaf1b0bc5560e82e4c87f912da3e595015ba.nq.gz
    ├── 0e4bb39da98baa51e6181a41c7f1b391b4e9b077.nq.gz
    ├── 0eb8b9429610ef5d84ef567ef8b983b8c0075f01.nq.gz
    ├── 0f1313bf500f113b5343652273a0f49bbfa36d83.nq.gz
    ├── 0f7fc1ccf370ccc8c27bef73fb4464ad9eb1bdec.nq.gz
    ├── 10a0b15d7605cad61bc7ab30b77ec075482b1098.nq.gz
    ├── 10d81127ddadf5d3ae38ab54400ad2a29261a480.nq.gz
    ├── 1186cb5670d763e4ccc664374992f1c752b94bad.nq.gz
    ├── 11e8737192fa199b853efeafd197e278c0b44f8a.nq.gz
    ├── 11f02fe2a0061d6e6e1f271b21da95423b448b32.nq.gz
    ├── 11f50bcd8aaba558fefcb805c6e9c053bd534171.nq.gz
    ├── 1242d43277017748bbbf3d0a104ec4cf78245822.nq.gz
    ├── 129291c03b5ee109233814c346bd112ca36b7251.nq.gz
    ├── 13c4fbb8c41b0da2180dfe24212b7eb009bbf0dc.nq.gz
    ├── 149607f9b484f1c42353b7798f78d2400dc0d134.nq.gz
    ├── 16592e51d30738ecd7972a85206922bab11f6b49.nq.gz
    ├── 16773fe2f0c378fb2d3b91fc356f0ad6532b2133.nq.gz
    ├── 167a67426264b7ae3516540d09319be49ee74801.nq.gz
    ├── 1682dd16d58c02371ac2881a40d20834fc8a1b96.nq.gz
    ├── 16b70fdba8ee89fd2b49548c05f56eed4f6b493b.nq.gz
    ├── 16c8ecee7d0e992a7f7b2a96cef052c4240b9b43.nq.gz
    ├── 1701fab18f31588427a57502535decfd2162f3f3.nq.gz
    ├── 1784f419353d836f0f7fc5fcbf9ce0d132b714f6.nq.gz
    ├── 17c11c88cd6554de124ce5319ce9882443a7cf21.nq.gz
    ├── 17f2b43b4728bc42f857c29b8426d07c328621e5.nq.gz
    ├── 19cdbe640f7759889308dfba5c06fc494b82cf35.nq.gz
    ├── 1a6c075afe498e9e2512fe02c5d8c38537e826bb.nq.gz
    ├── 1a988a11c792421090d6fe57ce7a0e03ffd29d13.nq.gz
    ├── 1ad0af4d515f817ecc94e0a8506ace7f003a5c3b.nq.gz
    ├── 1b8fbd92a47a8e1c9b43278d836cdc97f2ada647.nq.gz
    ├── 1be08fc25e1f6c2675d2a0918d5120b7d999082b.nq.gz
    ├── 1c8f38edb4302a39004f67b0526402be494d02d9.nq.gz
    ├── 1ce50f94f8e9f9976ab89bc074e6e2b6daa628f3.nq.gz
    ├── 1cfb64f76f011750852453d9c172cd57b96e6a7d.nq.gz
    ├── 1d900eb7e1e82654e835f47293d8cc5b9b5348f6.nq.gz
    ├── 1d99b9d26f0dfb2949e3f5e19361097db77a8222.nq.gz
    ├── 1f13a432161b1037d18b0639a5eec025f004fcb1.nq.gz
    ├── 1fe3c25a8d1bbebc2aa7762d1ce50e4643dad76c.nq.gz
    ├── 2053add61d3a1725f985aba1110783b33b7bfa32.nq.gz
    ├── 2089b899eb331205857ed0921c5aa9cf8e75aba8.nq.gz
    ├── 20baf1fc7e4e7da5207d9ef41b0d0a10d46861c6.nq.gz
    ├── 2241660e4d6f5151feab8735a04d2b346c71917e.nq.gz
    ├── 226870c0d2c4661a6c16b042cc23aded023e7b45.nq.gz
    ├── 233023a1996ccfd9684be53d6f588ef3af5888e3.nq.gz
    ├── 2456042b24c05bfb1b1476e4402a307c00f19039.nq.gz
    ├── 247870a9b8127104df435c8426074aa2b01fb0ee.nq.gz
    ├── 24a47e010aa4a18e9fcb84c6789d5d0fa77c2269.nq.gz
    ├── 2526feee0b69daf1818306d121c740c08c3f23fb.nq.gz
    ├── 25846668683b8da02eb426c9e82351ad888b2f8d.nq.gz
    ├── 25ad7da4e084e14708159f81331b7fd0c01f9101.nq.gz
    ├── 25f7b4c915ab51a946c6186bd3d81d5b58a25e09.nq.gz
    ├── 273fcb1a28b67ad01784a4c77cd66f1e1d3b0cf4.nq.gz
    ├── 27cc5867bb6e1b270b75832b9dc8e936e5d3b8db.nq.gz
    ├── 281ab5fc40511255ff79ebac668d53d7664a43e3.nq.gz
    ├── 2854205a238f49a1bafb663b80e9bf766c83d230.nq.gz
    ├── 288aecd3b226b81856da5158166f53fdc664497a.nq.gz
    ├── 28c18d8d6adbf98d928b1816ae9d052bcefa02a6.nq.gz
    ├── 29edddd042c407bccf3766a16b413258ff1b1eb4.nq.gz
    ├── 2a6f0ff4d791c9ae1036be0f3817ae338f56dd65.nq.gz
    ├── 2a812b1498ca9f26e259f76e510e5b7d773e0dab.nq.gz
    ├── 2b146a40475b4d58e928771a92fdab18d52b5b44.nq.gz
    ├── 2b4bf3b2c2b318438fd16e7deb4d1c0a6c0d05c5.nq.gz
    ├── 2b9912cd869ba708817026b4766827f0e9e73861.nq.gz
    ├── 2bc62a293091c20ca47d130d2c55349a18b41742.nq.gz
    ├── 2c483e26f63a103a3c827bb24f627db45d0a1f4e.nq.gz
    ├── 2c5f7294f8c1ef647ed9fa98d6600577aab0a56e.nq.gz
    ├── 2c745108319d1ab748ebf0b2dbaa123cbe4944e0.nq.gz
    ├── 2caa495078f0e35a78ecc47ca983f51927ef0708.nq.gz
    ├── 2eaaea822cdf5fa22fd8acbc357f3fccfba61402.nq.gz
    ├── 3006768f8af90a9d8ba9a9de7bd135f81fdf91fc.nq.gz
    ├── 313aa26eb700b19f1b8ae1b75720201ecf173c6d.nq.gz
    ├── 32c29ac45b0e093ddcff70feba57937755935368.nq.gz
    ├── 3321d4d022e8189b21aa607f60754416cf312106.nq.gz
    ├── 334dec66e09415f576603fb612ad1dbb94c4d088.nq.gz
    ├── 33516b8f3afddfdc139d38ee3c9bf1bf9bc8111a.nq.gz
    ├── 33d7ad9814eae95538d23aa00761c5e2cf2bb75b.nq.gz
    ├── 34a157a20aaef56c3f5c9b2691d3bf8d362ebbe5.nq.gz
    ├── 350a4528b77b04f186199a82cfd220c6ace3fa19.nq.gz
    ├── 35102662cdc4a360398acd0766d6b210a9f32985.nq.gz
    ├── 355277c660e06166ea1a4b4634c7c9dadc6e9a1b.nq.gz
    ├── 3563e7347be1ef18a3a447df1cd5d049cc088e14.nq.gz
    ├── 356def7f2b01869b950baa4d63cabce1f5259fd2.nq.gz
    ├── 35c742de7edfd42b5d6eec4d8ae6779177113979.nq.gz
    ├── 366cd25aa11d7c7f30ddd0f47becad2094581669.nq.gz
    ├── 36c417b5c244962eb7cf7958f7cf8ede7a712504.nq.gz
    ├── 3781b6b5289e70648d1784c2f13985303ffe77be.nq.gz
    ├── 379d80f08417d3857bd4339c71a51512e5e62c77.nq.gz
    ├── 38398402e147809e9776ca1dbb9d5049aed98d90.nq.gz
    ├── 38802c5e83f621f6b01df67092720a2b02c523d7.nq.gz
    ├── 38f91e4b733e45c9670a828836ae5c5f1a47cd0f.nq.gz
    ├── 392ef1052cff8cc7105ac89ccad731cfd072532d.nq.gz
    ├── 39423ba1760d1b08466a70837dc4e81a0a5d9215.nq.gz
    ├── 39af3e2c13666d52fab3797d78f68c2ec5ca1076.nq.gz
    ├── 39e2d673b8af578c2966d121dddc338d1a99d222.nq.gz
    ├── 3a4c20dcb7937b9495b6dcac6595bc5a79fb37d9.nq.gz
    ├── 3b0a25f155157cd21edd4eebe55559a048279fc2.nq.gz
    ├── 3b45aa8193929e6fdad4715cf285e7b323801150.nq.gz
    ├── 3bb6929f519f4657a64b12eb2152f2174881b8f1.nq.gz
    ├── 3cb341b4c4777e11494bc4307aae931b9709771f.nq.gz
    ├── 3d64dfc496bf57e5716c2f18b0bf945f0769f0b7.nq.gz
    ├── 3d79fca10244d9e308f908b522f560aeeea62914.nq.gz
    ├── 3de08e3e7f3ca09c0fc6b915e6e20e00df7de498.nq.gz
    ├── 3e49eeddf80e97df7b0a4e5d3e68a78568f60c57.nq.gz
    ├── 3e9510ac654bcdcd58428b8acff4b10522a0f094.nq.gz
    ├── 3ecbe1e9dbd8c9b7b75be292c9cc29db9fdc6ba6.nq.gz
    ├── 3f1a3dd66293ce05b1055b425c7e4967ba78e137.nq.gz
    ├── 3f295ea30eafd9b26c2f60aa7c974a3d707743da.nq.gz
    ├── 3f97cf668d3feddd9d0f47fe754347d130415992.nq.gz
    ├── 40318587fba674a5598009a22583a69a24bdfac9.nq.gz
    ├── 42021fc9507608546d3b73ae7691f142e603f948.nq.gz
    ├── 4288e0b6c492fe2d0e6db2925f8291359ddae54c.nq.gz
    ├── 4465e1fe2e47a5abb55594e2d6b0111925e861a4.nq.gz
    ├── 44a068c05343580cc9bf23965eb0a5bf56e12d66.nq.gz
    ├── 457cae6579526f35041d20f7a7473e76715c667c.nq.gz
    ├── 45977af33ffa0037d86675685f5e7d8416aea619.nq.gz
    ├── 4792731ec0ea6110096e7ff96c70fc339268f570.nq.gz
    ├── 485dcfa3931f2aa51f10a2eaddce5ad8b9b5d40d.nq.gz
    ├── 48903163ac3c97808b0cf6a0e9fb74b5ceabf762.nq.gz
    ├── 4a8ea9c6ca90d3a4b65cfe7228577106577ae4c8.nq.gz
    ├── 4b5067812cca16438eea7a8bc183353bbec0ca9e.nq.gz
    ├── 4b74c501bba4ed2c303dec616ab014d587098216.nq.gz
    ├── 4be10a45e251b6a6b3e28299387209fe93b4dd55.nq.gz
    ├── 4c79e7c6c589c01512510286f7b02c835a25cf91.nq.gz
    ├── 4d640b0e12b8dc2b8555a63db76e6f3522281731.nq.gz
    ├── 4d99ea5f8692cc83c76cecfa1e63825fa65ca657.nq.gz
    ├── 4e05c1afa4a8ab5c4ca9fc6cefe2b7391bf8ecb9.nq.gz
    ├── 4e621733178de232b31890734906aa808fde359a.nq.gz
    ├── 4efdc85a415390902115e6277d28fd09ae6b8c19.nq.gz
    ├── 4f052216cb1cac275129f07715cde02abbf28f5c.nq.gz
    ├── 4f42fdb60686d98d4c18b5121a91da4de9744e2a.nq.gz
    ├── 4f5f17434a24a088194a87b6eba3497a81878aee.nq.gz
    ├── 505de82c670b3cba0cd072d664e03004920eddd5.nq.gz
    ├── 50dadff3b42881d5252996f8cd45951abc9690bb.nq.gz
    ├── 526be56c0354e6a353ba6d31ddfa137e45b33830.nq.gz
    ├── 52a3158e8726aefa5be4cb3d3eab1aaa3dd10dda.nq.gz
    ├── 52d6f8f007ba78904580aba494ec089911baf334.nq.gz
    ├── 54d145193a3864c273aefce5fc59f79448344f50.nq.gz
    ├── 54f48995de00a196cef24939c22a2c4aea3f89fc.nq.gz
    ├── 5556fc0e400bd91e9f1bcc68409a672fc0669c3f.nq.gz
    ├── 55ef2d0a6d4b4544608f6d561291f007535af0e6.nq.gz
    ├── 565310d4d4f532095e6357dcb2863879d868dc28.nq.gz
    ├── 5694e944629971b01d376fd29ef2e67b39bb008a.nq.gz
    ├── 5705e8084bb4bf667b3a737f91983a0ed78e2549.nq.gz
    ├── 5788e1650b8dd8f84525945f22e5a872de2c6b56.nq.gz
    ├── 5823cc2fe452c252db260945001ecb01a675800b.nq.gz
    ├── 58b12c3da4918ab78dc58d7b32281a2f5d375d23.nq.gz
    ├── 590b18cbbf0969006d7200c9d10c634083b6afc4.nq.gz
    ├── 5a5022831a6c07f4d87f8fbcaf722c00f072caad.nq.gz
    ├── 5ae97c36195aef82d2cec738c0995986e0b78f74.nq.gz
    ├── 5b80106b5875ca7fe81cd9675043875fcb33bab1.nq.gz
    ├── 5c9a75e0043638f7ff320713eda8292a06c20de1.nq.gz
    ├── 5ea1d09a06c6f7cb246a7328f4926b7d2ff1e40b.nq.gz
    ├── 5ee1df4808668ec643312bd1d7c4aff5076dab87.nq.gz
    ├── 5f1776ed869374664c08580a4fc615e36c0e75f6.nq.gz
    ├── 5f94cc0c1b17aa32498e7c311a20f701beb12712.nq.gz
    ├── 5fce17588862c9e5e3f86e655af7525d843aa709.nq.gz
    ├── 603e8d0b18fd7d16d425af5b82b09d2457093fd4.nq.gz
    ├── 615f4d0034acb6e0273a340b551badd1fa2a648b.nq.gz
    ├── 6174d6128e9c91216e63b44fe672dd7ffd834914.nq.gz
    ├── 61811f6f949df994f2d672494b58e4c9ec88eda6.nq.gz
    ├── 61b52a9eaefb4332d10fe5d9fb495090ea78e1e9.nq.gz
    ├── 62024ebc7dd71e4e11e64f7fe75bcd5b1d84479c.nq.gz
    ├── 6212bd112edfbd9a82ac5d84fd32a634567d72b7.nq.gz
    ├── 62904a979444c4e19d5bb8162417ad21db062715.nq.gz
    ├── 64c7b0517bd5d79bfd5d59eec63b44be71c8ec52.nq.gz
    ├── 6532bd1b307398890d30b6fb881bc0ee459dfd8c.nq.gz
    ├── 654494a07eb6714a8f3c3bc2034398743439655a.nq.gz
    ├── 656a787d96fbde0e735f8031dea3e666b6cbfddc.nq.gz
    ├── 65c2092ee72112caafdcd22954e6c0eb5a2f4f40.nq.gz
    ├── 65ec98cc8f1ff6abd698d29faf06e02ac3d5e25f.nq.gz
    ├── 669486171c008bab22f5c839db11aacbe077e3e3.nq.gz
    └── 67ee3d42d61c64d139965fc8bfc9e8dcc060bf74.nq.gz

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

[truera/trulens](https://github.com/truera/trulens)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
