# Repolex Knowledge Graph of evidentlyai/evidently

RDF knowledge graph data for [evidentlyai/evidently](https://github.com/evidentlyai/evidently), parsed by [repolex](https://repolex.ai).

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
rlex download evidentlyai/evidently
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 34771fe41c08ca074d96a52aaf4a45cd640cbaf5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 34771fe41c08ca074d96a52aaf4a45cd640cbaf5
│           └── chunk-001.nq.gz
└── blob
    ├── 002caca6558ea851b402ea98f04cfc9531a4eb0a.nq.gz
    ├── 003260aa0e71abe9e87433886034cd26522be677.nq.gz
    ├── 006bbfc8fdac36da03dcea9c32833c33e499307f.nq.gz
    ├── 00c7fcd9b50e25b44f2ab444cad542fec33f044b.nq.gz
    ├── 0159a3f8681d9aa6ca4011e466a89f14bb2a5a3c.nq.gz
    ├── 026d5ab12526338479d30ae7c91185000dc140f2.nq.gz
    ├── 0277b8ace6f66d0dc0387a903c89be73080ec424.nq.gz
    ├── 0331d30d5a0535c195db6f0d487f00df60543e82.nq.gz
    ├── 03574e1b333bd7cd8e5097d5dac4641665f0fd2d.nq.gz
    ├── 03ad3b948c99e8c5acce5e1cb5fdc2f3e132a457.nq.gz
    ├── 03c77b4ae5494f964da581e3412705d00c96444c.nq.gz
    ├── 052bbd3f21ea97e782a9327ddbd18005823c1ecc.nq.gz
    ├── 0544c977110314260b6437561af820b8c7a67e9c.nq.gz
    ├── 056dd221b13437c3a14b4431be3242ff4056d096.nq.gz
    ├── 05f1335910d5b054d135d43156660502b2b94d65.nq.gz
    ├── 07076f3e9f7c2a36859b5e5dadc8f4abfb61976e.nq.gz
    ├── 07f6f15181965b186fa056145cce18d932d66147.nq.gz
    ├── 084236dc5d3a5b72f0a1b932e3c96427ee8d2c24.nq.gz
    ├── 09dd160b9879cf78c1f760f422bb09a11d05d472.nq.gz
    ├── 0ae09f6eff32d17490ec41ec8a3a2c9b8e4706a2.nq.gz
    ├── 0b044078f5e3037251282c105e2419257c698808.nq.gz
    ├── 0b101e47f5a02520c36a1f7c01a4799289ce0bbf.nq.gz
    ├── 0c5d797dabb85405ca9490eb20a763e20320afcd.nq.gz
    ├── 0c7e53717ae808aa3e379339e4855c167061c6d7.nq.gz
    ├── 0ce5371b9f23471bfa1f2d3f52d14e2ebc392ecd.nq.gz
    ├── 0d305ca9e338f396e76605c55217bd4642987ba0.nq.gz
    ├── 0e9637604476b9477d276663de5889bf3f69a4a7.nq.gz
    ├── 0f0fe2c511908f54bad0f37afd107b5f48c66320.nq.gz
    ├── 0fd11d75264f69b20a6a374071f2a1086fd364e2.nq.gz
    ├── 1064087c1852b441b219bdd50a205b9b32174a81.nq.gz
    ├── 10a93e260d8d34fb9a11b85b6863ec40befe8a62.nq.gz
    ├── 1195948222e86c8b65e4f2943bb9af0ae77244ae.nq.gz
    ├── 11a1594468ef0e6fc389c69a41ee5a122ccdd3cb.nq.gz
    ├── 11f02fe2a0061d6e6e1f271b21da95423b448b32.nq.gz
    ├── 1242dc34ecb79ee9969867941435d93e4bf7bda2.nq.gz
    ├── 1260db62cdd07ab358330c0215b0e925a88f4e36.nq.gz
    ├── 12b3aeafcc05577e3b5d0c61c5258ac27f38feb4.nq.gz
    ├── 1358e18db14a57e42b7279debfdafe0c14cddf7d.nq.gz
    ├── 144491b5b3de802ba24e3fd925aab5321cc53c6e.nq.gz
    ├── 145fc6b259ef414519523f78b8a724ce60883180.nq.gz
    ├── 1517be3b31b02f2d847895e90868c3af305536f0.nq.gz
    ├── 160ce34d098a4c78e216a4a29a70a86528169933.nq.gz
    ├── 1675db0af3fbc476389d8003b69dd373a1d8f3cb.nq.gz
    ├── 16e0f1bc37288817447d1807af2eac733b74437e.nq.gz
    ├── 17323524f8e9d61e4cbbd0ca4216be05411e0d97.nq.gz
    ├── 179da6ddbc0b974fec81d27a4a66aa88093563b2.nq.gz
    ├── 17d59de26984cd1bea3187fcef076e6372334cdc.nq.gz
    ├── 184416f28398ead3a21cfa9c293ab494c43e2eb8.nq.gz
    ├── 1863902725adc5f728185316aada467b374c385d.nq.gz
    ├── 18be29574808e0d4cc38f80b5a26ebec2d782105.nq.gz
    ├── 19576324515a2322572f4c0ce3e94204dffccf3b.nq.gz
    ├── 1974e9e01e224bbd1d98139b594c7911b0a2bc3b.nq.gz
    ├── 197d040bb49a57217d13997e9f60528086fbfac5.nq.gz
    ├── 1a22daa7c0aa9a04370ddb8ab4c0e8aa874be50e.nq.gz
    ├── 1b60aafbe1f7957e36edb8c11776c8dfdade00eb.nq.gz
    ├── 1c99212d60fd212a7a70822d20466e97163477d8.nq.gz
    ├── 1cebb289e581e41fb571e8e504ec8d1365c22669.nq.gz
    ├── 1db9d2548840f06e7e6e2c64903e592de78ecaca.nq.gz
    ├── 1e98cfe464883e7b20b423fe3ca49f84eca4e68e.nq.gz
    ├── 1ea2b47f1ef644a06a4a04558b31fad05c86ec15.nq.gz
    ├── 1fa07bef8729c0d49f6633055fa42afd4193b5c1.nq.gz
    ├── 201c864b2fb4f89b00f875b1a44663ba9bce99a1.nq.gz
    ├── 207b893972b55e15efd4d39828b3a8e3dc741c4b.nq.gz
    ├── 20e47b15e46992dbb9b36d804b149c883b8566e6.nq.gz
    ├── 216c12449338512bb79f0a3bd330eb7dc399abc2.nq.gz
    ├── 21851d2edc1968abd66b55e874852e2aab130b55.nq.gz
    ├── 218b65c3b624a4d4a3d268ad9ecc879f75b3c427.nq.gz
    ├── 226d09ba413bf4dd62fc2f4f72607d3120178404.nq.gz
    ├── 2277d680ec580b402465cef6e782c4eaf91892f6.nq.gz
    ├── 234df3ec64936c94512e2ad86efb401b1f987ad5.nq.gz
    ├── 235475c402bf93eb1c61907abb3ca563b2d3bd9e.nq.gz
    ├── 24199291003b6e0d33a2515cc07037fbf73a5cf5.nq.gz
    ├── 24ebbecf067d07e50c83390b93acace8ca391772.nq.gz
    ├── 25fa03cc84d40bfe1e1431a96ac262968ed05781.nq.gz
    ├── 26b1c80db6d34163ca67373d3169cf9bd648c698.nq.gz
    ├── 27c547c87b7b7637835406143b6e32dc749c5a9d.nq.gz
    ├── 28fb5d0e5d9b17f6fb143c423fb02e4daa0b7dd1.nq.gz
    ├── 29b38661fbc80dddac4e049c64f42013e773084a.nq.gz
    ├── 2b517889f805e311a36f5096c59e92f54d42b897.nq.gz
    ├── 2b517ddce6e4c99f69777cd50b801f2af565389f.nq.gz
    ├── 2c8dfd3dd6f6120cfb1c94001e778703e7c0c4c5.nq.gz
    ├── 2dba9014cf01fd01bf1c29ee874629682323ff6d.nq.gz
    ├── 2ee3abaa9dac76baed737dd620f793c2781a4704.nq.gz
    ├── 2f2bc0c0efeba8a39ead0d4fcbf5512bcf636528.nq.gz
    ├── 315c7cfb0bb3a6a9b6daef837e5db240d6fd120f.nq.gz
    ├── 31e6ffa3204e6dcdbb19edc01f3ce31714581377.nq.gz
    ├── 320b0dac7f33512bb78409b183ce51e97a1fac39.nq.gz
    ├── 321c4b8311fcac02a5ba1220b027a01b471b38ed.nq.gz
    ├── 32f1648e932f2fcbb577f9308753db42e6ca8e07.nq.gz
    ├── 33780f225a5179c4800f575cf56e3e85d8886d3c.nq.gz
    ├── 3415086dcb55abecbb3310237ce5bbfa628ecd90.nq.gz
    ├── 34b2338d6425e69bba90f66231da0e292965f02f.nq.gz
    ├── 35014f7c3556301d8fa9a9654e0e2d5dfd824ca1.nq.gz
    ├── 369bc11163f7f6d1226deabfbf8a7fc7e6824e72.nq.gz
    ├── 37c0f34d63924e155253f67d2ff3716613ff5946.nq.gz
    ├── 37f8b3f3434437b7da5f92ab7a68cd2b90eeca1f.nq.gz
    ├── 38676a0ce87e7b1e17950ecdbaf9e02be9dd7aa2.nq.gz
    ├── 3876c93313ee5571f55bc02bad37a2563321a3c2.nq.gz
    ├── 38ec09af8496e9bb34c90e48f8f50979d3d55ffb.nq.gz
    ├── 39033d20fa4c88ccd4ee8b12d7652e49ea621c51.nq.gz
    ├── 3a0f5708b493967846cd678ac66f85a5fd38161b.nq.gz
    ├── 3a498f6e275a5aa6ad6d41774007ff38f0ba932f.nq.gz
    ├── 3a664c8fefd23bc5fa5a00fd5852ee80d5783fa3.nq.gz
    ├── 3ab84f35158b55363c29123354503d7908ed6a35.nq.gz
    ├── 3ac7dfc0b209094caee028033e2b60cd7ed26eac.nq.gz
    ├── 3b515dcc1ba8a6e37a6a5b52c74ccb6fcef53534.nq.gz
    ├── 3b56605759e3b6a485b65cdacb1d4fe2cb5da7a5.nq.gz
    ├── 3b5bb8b3f2bbcf1fb1a16b3138db39bca2084629.nq.gz
    ├── 3b91c6c714994f796db4e8347804b00354dcd15e.nq.gz
    ├── 3c278a1047bc3ff2c744704c7443a15342d8687a.nq.gz
    ├── 3c7eb22d3a7fb078087b128e154db354a1c6aa9f.nq.gz
    ├── 3c9bd150df5d9426d681c7f8d9039c0909b093a3.nq.gz
    ├── 3cf01f048c764144d9dcf9f9d5adf851b9103ec5.nq.gz
    ├── 3db2f458e821e65b57004ac3a90db76a9db2f0bb.nq.gz
    ├── 3e03a9fa8065e890c70e924764d2648a951d63c3.nq.gz
    ├── 3e051d78c25f3a68968e43859c3029efbbb3a16e.nq.gz
    ├── 3e14e38a9c71b83db452f00ac9a4e482d70bfe0b.nq.gz
    ├── 3f928e00b79b9e8dacc27fca59f74f076b0a8a21.nq.gz
    ├── 3ff3a0db03070720c17e7c7cd717500faf2d4be6.nq.gz
    ├── 407a3f1c1e43ad35b34bf9e3157e0ed17c9e1a3f.nq.gz
    ├── 40a44f82725cec234943982bcc7f35baf6fd6a45.nq.gz
    ├── 40ab31fd962cb1c08c4917f3734caff29b58a0a1.nq.gz
    ├── 40b485aa4a17801dfaaa4439242ba9df46df4098.nq.gz
    ├── 41870d0deed83296c97b26431b3adc13d95b981a.nq.gz
    ├── 41dac8fcf3eb269ace1beb9a083b0272c2ff6f22.nq.gz
    ├── 421f24277bd1243e8157e9e80a1115b655f1b184.nq.gz
    ├── 42dc0c23643dafe1180165e61ca2d1eca8d58823.nq.gz
    ├── 43610ddfde63eaf6d4639f6598616d2c3be997ec.nq.gz
    ├── 43c1d7e0a4d50d8d2427ca9cdd055a522284d6c8.nq.gz
    ├── 43d158586e80f74ff710e05795d8fd0e8006df6a.nq.gz
    ├── 441ac35f20c482c902b9f872f1ac7c70005bed76.nq.gz
    ├── 443a6c11453c15847e8b0e49cb4a50ceb4412b00.nq.gz
    ├── 45193f881f39f23ad84cfcffa7fcd09b87cf0797.nq.gz
    ├── 45eabb368f390f853c2bf19a34d643e2b9f6e6c0.nq.gz
    ├── 48640787c67d02602db38a3cbe0af2864aa9be15.nq.gz
    ├── 48741c51417d2b8ce7674f1f1ab2a1710750208e.nq.gz
    ├── 49373deb180d8613148f5fc956ce58a28feec4a0.nq.gz
    ├── 4a4822f056ff3510a28a906b41c4410761a440d8.nq.gz
    ├── 4af057c01cb115579ca3b0d203ecf847e607030c.nq.gz
    ├── 4c12939cead79547bc386617bdd8b5014d89a274.nq.gz
    ├── 4c422c1cb6df528200b3dba3f775d5ce85fdea49.nq.gz
    ├── 4c62d9e37f9b552e30064713e9c7792621392362.nq.gz
    ├── 4d0adefba3cc4447ecd58d3eaa47b83a278e04de.nq.gz
    ├── 4d96358baf7d0f304624680fed609d2682e066a1.nq.gz
    ├── 4db89c1cf817b85fe153c5d9c8ecb4531a169e9d.nq.gz
    ├── 4dc9bc0e15c2e902400e1654b6e66fbe2d5d9ac6.nq.gz
    ├── 4e0c68cea46863ca74ac8cc84f92ba2098c9e4f2.nq.gz
    ├── 4e763666a0d9d4632a3cd75787d904d41b7bac12.nq.gz
    ├── 4e94163cd5dafc326eddf3be196e38e8a2338f72.nq.gz
    ├── 4edc2347d487e20bd7909286189753d83b3bde37.nq.gz
    ├── 4ee6bf2f892f9dd8edfddb8504bc0eb1e387f7b9.nq.gz
    ├── 4f7516c89898aff13d41e414a81eb4512f0ab8c0.nq.gz
    ├── 4fa2196b83c79aceb3aa9f8bc8faa77f494dbbd6.nq.gz
    ├── 4fc0f20abf71e5c5706feff3550171662634c5b7.nq.gz
    ├── 4fc8b10915239967d293b58e46d64c2b885da215.nq.gz
    ├── 5036d00eb390451f988488c50fe57839448c4a82.nq.gz
    ├── 503fe6dd78ffe8c207f868960571afb8b4af46f5.nq.gz
    ├── 50b0e52623c5a6299df05db262dcc82801445d21.nq.gz
    ├── 50f8f744c64001e310841c266ad233b2de4b814c.nq.gz
    ├── 51973055237895f2d23e65e015793fd302f4b9da.nq.gz
    ├── 52ef892baba307f0282c02931dc3667b561954b6.nq.gz
    ├── 5319122dd3842b9edf498e155333b3a02e57cbdf.nq.gz
    ├── 533496c5dfbf538b2ef1dea73bb1f4b21c4cf166.nq.gz
    ├── 537bea32a0ff7554bd5c5b589e0bb96cb7c87ccb.nq.gz
    ├── 54c71225883f64b00f54e89e94c3d8723575ca37.nq.gz
    ├── 54cda0447a0583a635588b1af13ea95746ac0039.nq.gz
    ├── 5663563a4549b7409aa8cbb37027811dbee96cf7.nq.gz
    ├── 5735af72108e30fe4c05d0db3a6cfb2a4fe11452.nq.gz
    ├── 5737eb1ba7270844f1cbc93abc468ecf5ddc3244.nq.gz
    ├── 57632df67cbb4e920af57406373f54a179c7f253.nq.gz
    ├── 57b3ea66f69aa68f6abd315d5edca6405eb420c4.nq.gz
    ├── 5855f733410fc769697bf6fd26debe1fdb76946a.nq.gz
    ├── 58ec9d332e59ac240d2304fca009cb5b5471532b.nq.gz
    ├── 590f7faf1ce779bf16b8158c8bd460cc94cf8d0e.nq.gz
    ├── 591eed52deaa4ad4fb236ce2b992ea4f0f176ec6.nq.gz
    ├── 5973bc7615c9fbd8e7822f51cb1d998480120cf2.nq.gz
    ├── 5a55bb562e5c76f429d33ed5bb82568680f6bddb.nq.gz
    ├── 5b515f8ca73e1e9953c5b9d8f4cf68361f342eb3.nq.gz
    ├── 5b6dfe82f078082c34ee2d03615383bdb2d1b578.nq.gz
    ├── 5ba523879e69898a57a3346248e8389c18421523.nq.gz
    ├── 5bbc3337aed6bc8a239dd5feba8846059ba29572.nq.gz
    ├── 5c417e7a0c9650cf550573df87c370691f8cd467.nq.gz
    ├── 5c87532ac56cde7618c305cdeef07e8f2f6f9669.nq.gz
    ├── 5cea65f14d310622b3e25f4c4c15f9022dcc6b40.nq.gz
    ├── 5df80086877d7949a1bab14b00148b5a97884ccd.nq.gz
    ├── 5e0fc4d72c8ed3b34cc85d18cfd236bb8b40da7e.nq.gz
    ├── 5f232aab48e3ae071741834fcdf17e5e6f3fcc28.nq.gz
    ├── 5f82db617cb1a45a61a6f56d72826365c77d5c44.nq.gz
    ├── 5f9da3b1e372ababe876c8ff084bc0363a369d3b.nq.gz
    ├── 601d2da69acb622a21858a8f03ae170ba224ac1f.nq.gz
    ├── 6241c976945678a8909a9da36507587b367a8c6e.nq.gz
    ├── 62552ef4b75802a8d6934d8bb32c8ea4a4a15df7.nq.gz
    ├── 62b2b3a90eea28b5521225505c40960cc1c8ac98.nq.gz
    ├── 6381256959a3e1ee4620de324d57a40a977d0639.nq.gz
    ├── 6381ab43c281e7cc59f02b6e35694c3a67080d19.nq.gz
    ├── 64f5e32722bc6324784df4486748b8eef75894f7.nq.gz
    ├── 66cec982e77156cd8173f94836a45f6fefbf64be.nq.gz
    └── 6704ce61cf4c5ae8d6b3c6f7e00471a0a7e4f9f3.nq.gz

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

[evidentlyai/evidently](https://github.com/evidentlyai/evidently)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
