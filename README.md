# Repolex Knowledge Graph of falconry/falcon

RDF knowledge graph data for [falconry/falcon](https://github.com/falconry/falcon), parsed by [repolex](https://repolex.ai).

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
rlex download falconry/falcon
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 05b35ee93d10f616fbdd192bbf860ec9e59f9e14
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 05b35ee93d10f616fbdd192bbf860ec9e59f9e14
│           └── chunk-001.nq.gz
└── blob
    ├── 003725344485019861d24ddd9c1f46ee07c9d70f.nq.gz
    ├── 0099161300f3cbee3fd021aaa29921d1dd7f787b.nq.gz
    ├── 00ca3d9323bd561709d2780639ee05e6541bdee2.nq.gz
    ├── 0117ce6c868132570bbb350b89adef5916420eda.nq.gz
    ├── 05280cfe8ad5b5c7adbe180e8423eb1ac6a4eba3.nq.gz
    ├── 054514a6112745fcafa3feb26a87227240abd4d1.nq.gz
    ├── 0574978a843bfa62ab6d847778799aad0cc7f343.nq.gz
    ├── 05e7e98c843ffb0a95f83c4972d62dddeb7b7919.nq.gz
    ├── 05fde3c2374b9482fa58d867a650007916740d7f.nq.gz
    ├── 0673135f4300fbdf2cb1ebda41d401dd1cc8ce5c.nq.gz
    ├── 070c9715646f812f9aaaf9b70bf3e1445d10d05f.nq.gz
    ├── 087f1ec57eddf4b7778cb10ecaeacfb79595454e.nq.gz
    ├── 08d01875e5c757037bf39c6ac2a9eb134cefd008.nq.gz
    ├── 09a7eecfbbc47180f4a632a895a22603998cc993.nq.gz
    ├── 09e0831f30d924a94259d78b8f7ad49793e248ab.nq.gz
    ├── 0a194301314e94aa02d1b5e831bcae5b26f3b9a9.nq.gz
    ├── 0a44a692ecdb903c44a56107e18a13f363296e22.nq.gz
    ├── 0b028d09a8ae3bac53af71a4433356fb3110dd48.nq.gz
    ├── 0b4331b362b98a4e5947c491612f95a3c2e56686.nq.gz
    ├── 0b996817fca9b48244a7832eb51962b4ebf773ef.nq.gz
    ├── 0bddaa118acc1da9ba68b8862728dd14b3278f88.nq.gz
    ├── 0c1ac087b7ce8ab9469b3ce082173b119a471839.nq.gz
    ├── 0d74b67daae4265140923d86155a2abfa99c5e8f.nq.gz
    ├── 0dbf8404428986abf13878683ec0414f696bbc4f.nq.gz
    ├── 0df3429c1d51a083fb0fbde10ffdfc3a6d9ac366.nq.gz
    ├── 11554030b436065bbe7c07c9429496f6121f4edd.nq.gz
    ├── 11b5b42255def1b63d43bb8e3e124e0fd2800fcd.nq.gz
    ├── 12342593130f9469026f8ba7d2b55410c1a3d2df.nq.gz
    ├── 130f59875e67b808ade5bf6f92184f137d7ca406.nq.gz
    ├── 13963a0824bf009f10f7ec44c341e20eab972a5e.nq.gz
    ├── 140a64d9677924299aef5efe5131c2bb51811864.nq.gz
    ├── 1425dcd7c1330b2f0eadec8409c352b67f76062d.nq.gz
    ├── 14681663b3747b363caa2e5ed4b61840b9840d1c.nq.gz
    ├── 152cf106a30b676c5f6681a623f4a611b3cc65d3.nq.gz
    ├── 1686f815773f05858f928d3045ee6569eca5acb9.nq.gz
    ├── 16bf1734e2c9d73ecdbab1f885c6f3f5af136fbc.nq.gz
    ├── 16e271645fabe2d623c5feff5920ecc8b5f2bdda.nq.gz
    ├── 19dc4148df64110bd48ee43739abc4f30b7cc765.nq.gz
    ├── 1a09eb70700cc5ea91ca60a19d76f619d9f0d2b1.nq.gz
    ├── 1a66c6955fd33f1d59042d525329f09e29119c7d.nq.gz
    ├── 1ab80c51047901f7da9dea63ad98a391efbfc9ed.nq.gz
    ├── 1ac8d91cfab87497d7a17e444aec66829570d73e.nq.gz
    ├── 1ba40ffc0aa422a76794ea6ac5685468de5a0fce.nq.gz
    ├── 1cbe9ad0f1b9380822113b2f65513a67a0c3fd54.nq.gz
    ├── 1e042c09ca355e1dfbfccdc0cd07dbbd5eb71029.nq.gz
    ├── 1e6be6db23de5912c0aa0e7ef307ae50c075669a.nq.gz
    ├── 1ed3638a4df1bec17ec47502b337b01f857ace4a.nq.gz
    ├── 1f61026287a27be882bf87e15b20cf2da6d159b6.nq.gz
    ├── 1f92f2c87fb232f7fbd3520b6d9048b2252adc9e.nq.gz
    ├── 20ce345a04ad1a7b625f9479ac8eed14a5291ff0.nq.gz
    ├── 2173680a7072f9492a70058c5d6ccb76eeb07d24.nq.gz
    ├── 228cf115031f7236d384cb070e9c6593bf62996d.nq.gz
    ├── 23fa969044b595870f39701e267b3d6950f52a90.nq.gz
    ├── 24e79b27fb7e77cb1807b63cfc172ae970182de7.nq.gz
    ├── 251e8e8c05e9f0ca2736e02fcd9c97faee3dcf26.nq.gz
    ├── 2662d04789b98537ea726f2e1f2ae9bf3161356a.nq.gz
    ├── 268988801e338c10c74ad27c955e2851111f74f0.nq.gz
    ├── 270f6b58f6b838f5b2823ed6f29d3e918dbfd164.nq.gz
    ├── 278a71c7fb9cbfddbc6658477b9a0cc26e2ed207.nq.gz
    ├── 27cc5106e3ade414d89cf59d080ff7d7e7455de8.nq.gz
    ├── 27fbb2703bb012d8dda3a1cfb58e1e8ed212901f.nq.gz
    ├── 2989ad88341a4c3044f45a197c3a69bd54705c83.nq.gz
    ├── 29e43a93aacd37dc0bb859088f0b77bda5dad94b.nq.gz
    ├── 29f4b79e86cc3ec3289b11e023e435cd8b6d2fd3.nq.gz
    ├── 2a6da6f332f4d6bb00b168648319911ed024bcb9.nq.gz
    ├── 2ac20d9597861b972a1aacf9f2269ecbea8223be.nq.gz
    ├── 2ba73a326c7721e3537dab0c69511713090e0527.nq.gz
    ├── 2ce2b891a8019536fb298c920dc29d5918aec5ef.nq.gz
    ├── 2d95c4f4f7f0ad6c16c1e3609224d9139b83dd2c.nq.gz
    ├── 2da81013ebe58ced80c0697a83bfa2f135b96d30.nq.gz
    ├── 2ecc58acb92855fa4e7a210237f56cdd7ffe42ab.nq.gz
    ├── 2f4d07950b8c6d6993a59d440d5a684764e99190.nq.gz
    ├── 30afb82faf049f1d84acc8ca2274a7eb6cd99c57.nq.gz
    ├── 30cd986c03a9ac34183a016160f3b6ad669cc7d9.nq.gz
    ├── 30faab83356fb40dee05f22ffddaa5acbb5a1f51.nq.gz
    ├── 30fb88c40a47a5b0e46fcf71232b559ba81ab053.nq.gz
    ├── 31d1f965bc4a2e68f3b7fb8ae75e63077871066f.nq.gz
    ├── 3536520ad2fc6636aa38ca92be86da36186e2f9a.nq.gz
    ├── 35a4e425f4bdb5bfe83516b6856ebacbf581351b.nq.gz
    ├── 35ae54093a44c2c5f13cf0af994c5abbd64c7c87.nq.gz
    ├── 3633d6ce0d5210a6a69ee262a6502c7c61f78ed5.nq.gz
    ├── 3771d14317f74ef701015efd16cc0b98fd79c8b2.nq.gz
    ├── 384aa6e2e223e08532731d5ca3ddd0fa5fb3597d.nq.gz
    ├── 394639ca7086d8d35b61ab558290a21fc672fdd7.nq.gz
    ├── 3b95cad0f57098bdbe3db30c2f74f673575babd3.nq.gz
    ├── 3bd9768927cb62537421b932fa42ab374059fd5e.nq.gz
    ├── 3c581b0f9cfcf7e434e1efab1f3abb1074eeee2b.nq.gz
    ├── 3d74c939f1fb4ce4c0e8985379d912005db70806.nq.gz
    ├── 3d86fe81722d56111b455c6b843e71f4bc4d9d50.nq.gz
    ├── 3e177db930733ba8a2c04a151ea3cd8e24d8285b.nq.gz
    ├── 3eb99ac3b225f3ace2312fb8add47c4e320cb323.nq.gz
    ├── 406b085d7a6398dd350d6c77f1cc6c32235c5ba1.nq.gz
    ├── 4073892f95b80c23a2a3b7f0746e2a917b8b8d50.nq.gz
    ├── 408d768c31f59c48989af9b13c8a28e965efdc02.nq.gz
    ├── 40f39dd5acacf5c22783e94828cfea7910ec4186.nq.gz
    ├── 4185d360e9a725a190ddfd9b8cce8aeb0df64cc3.nq.gz
    ├── 41e49b59956f4ad1b5506cfbc917e8d34a1cb49e.nq.gz
    ├── 42415051ef143526a6f90c64b14340578afda9ab.nq.gz
    ├── 42b3121a1fe062aec0f48b330b411cae4635dbb0.nq.gz
    ├── 42c0ce22cab91e18369fdd13ac32320134793a41.nq.gz
    ├── 43619084d1e6b838c1d04d637e4d0d9a08c725af.nq.gz
    ├── 436a7dfe75630dd8cc4e9a89605af8ca22b7b28a.nq.gz
    ├── 43c994c2d3617f947bcb5adf1933e21dabe46bb5.nq.gz
    ├── 4456096fa3965e19ffa25b4dd614588caa7e927d.nq.gz
    ├── 4464c2f918b4b3709ec9d87dda339b4b5fc827f1.nq.gz
    ├── 450c15bac4d71fb0d158f6034263e3c6f556ea15.nq.gz
    ├── 460fcdf1180d8079f6d254747e7e0c7a73797fe3.nq.gz
    ├── 47b1e7b98cec35606f32536720908573cd266583.nq.gz
    ├── 47dd40f7243aeed33d508d9be5063c729aa1efbd.nq.gz
    ├── 47e53d5d746c3fd2516c7926613b10fa33b355bc.nq.gz
    ├── 4a526c3513dea017cea3056caf6bc2fbeaf895fa.nq.gz
    ├── 4a62fdf19f35ab3d051d643524907f557e9db27d.nq.gz
    ├── 4bbaec36cf29379f5b2792b757068c860d11fb2b.nq.gz
    ├── 4e8301c3c52380e4377776d56dd506372a618450.nq.gz
    ├── 4efdd3eb187e36276b93774f72b9a7bcc25dfab6.nq.gz
    ├── 4f2ecba06a1b364a6f5b03b378a296b58ea83ebd.nq.gz
    ├── 4fdb4265ff5b24986aa5749ab3a0d22a5ddc6f21.nq.gz
    ├── 5007affdec87f8e653a8b9bcce3138a7d8277b25.nq.gz
    ├── 50438f9fac112a591ca7edd2c344fef4200dbb50.nq.gz
    ├── 5095251761a17cc8ccb777037d344d4c454e32c7.nq.gz
    ├── 5097b1947cece0296e3055efc0c9b53a35d3f3ef.nq.gz
    ├── 50ad128a51460cfa23523f3876cabcc10ef42687.nq.gz
    ├── 513c3a5b50c92d072d424d0fd47eb2252bd8e71a.nq.gz
    ├── 52192974f647e0daf2290aae1087f96c0ffcfe17.nq.gz
    ├── 52244f583df5e65842e94d8e282ecbe2bd4875d5.nq.gz
    ├── 52e30cab0739b8a4dee058ad31f5ecedf24dd061.nq.gz
    ├── 5473aecfd364db9e2e32b09b2873b96a6a4238fe.nq.gz
    ├── 550e5d5f6491982b7886c04941f65396fa31fc86.nq.gz
    ├── 55a2e0624363b94dceaa4621ac609bf5434e4b6d.nq.gz
    ├── 55c9db54a055d8882d1751286ecf7711ab885957.nq.gz
    ├── 565c1a09b85c68277b3aac16e5d4078b3c313a6c.nq.gz
    ├── 56b15a03f53d81b2f0b9613136f93d2e4453b722.nq.gz
    ├── 56d396592918ecbef189d6fb9362447ef822c4a9.nq.gz
    ├── 5994d22d9b1edf086925d4e786bfc385125ce457.nq.gz
    ├── 59ff9bb15d51e413fe921f08997b8fef06110919.nq.gz
    ├── 5a02adf9156d41434edb3369257f97bbdabac467.nq.gz
    ├── 5bbafd5df7c2a699ca3f0edd543e3d51bb82da0e.nq.gz
    ├── 5c5b98f6a96a618e3580be3c8596dc847581dd23.nq.gz
    ├── 5c674da9a9e789df180b94138b2b14a80ff17e59.nq.gz
    ├── 5ca6420815fa18e9cf14b546900f7835f4003458.nq.gz
    ├── 5d6ec79f22bd5e796c7a50f859ca5f6b87caab4c.nq.gz
    ├── 5e13c8801e533c76e8779e859c0957206f55f09f.nq.gz
    ├── 5e4e075bd68565682e9260607929dc467bcbbc53.nq.gz
    ├── 5ec7dc6295f84a2be467133d43dce2b099fbc366.nq.gz
    ├── 602c3325fd4326672b7178d04a3e5f46a56387ef.nq.gz
    ├── 61b36fa830dc38f8f407987dc64c613ced1262c8.nq.gz
    ├── 61db17f1d961bf856037ed57de5ecf20295f6242.nq.gz
    ├── 62164fb473f685c776f0022c6e02b821df44536f.nq.gz
    ├── 6305fd5f625e49de1ea9addb40fac2e9dc67a2e7.nq.gz
    ├── 63d9e06142d70586e38cab6bca6a0520e4ab0b66.nq.gz
    ├── 6500ca9848941144550fe954e5d238c4bd05327f.nq.gz
    ├── 653beaad40ec2e426cb96958b23dbc047de32566.nq.gz
    ├── 657bc83c518a5f412847e3406980d3d1f716a798.nq.gz
    ├── 65eda79175d67a504682c5951ddb63b6f74e2f36.nq.gz
    ├── 668002f485222199e6a50c58f5762d2b8aa97059.nq.gz
    ├── 67011df9cf89bc7bef808b6aafb51e45646e8458.nq.gz
    ├── 6731a9910a2880aebc3ccefbe71bc95bc2a42947.nq.gz
    ├── 675bcdeb7b0ee17bd97544f657082e0af3d5c91c.nq.gz
    ├── 67db94cc2e422e0a2a8f99ded71bf75d084ee7b3.nq.gz
    ├── 686006e0bed20065d0d24c591ac5b632b65b45be.nq.gz
    ├── 687475c300fec46f4a41b12711a15d71b8699c5c.nq.gz
    ├── 6aab042d254c8e34ae5e8aec7ae9a80825650efd.nq.gz
    ├── 6aab0e408bd746f66271a043c55a333a8f79a9c8.nq.gz
    ├── 6aca2d19f1ea50d1c082f6f873043abcca23821d.nq.gz
    ├── 6b35f6e9be439c00c3ac2135cd57420cddce4d25.nq.gz
    ├── 6b536e1e35ae7000ebdea21b646749d7062b33a2.nq.gz
    ├── 6b59df9f4c0526ec84daa3a58decb94d94e6ce64.nq.gz
    ├── 6b8b675f35aea49ae35f5e4651dfab94a6bdb529.nq.gz
    ├── 6cf3357b0eafbb09716f9f7e31974566ff95ffb0.nq.gz
    ├── 6d1d5626a02069b2be458254022f5d75e321e5d0.nq.gz
    ├── 6d26a27a26f05e8b8a5caba9412cf45333eaaf2b.nq.gz
    ├── 6d46fd3b26cfeb43ce26898487565242fb881a00.nq.gz
    ├── 6e10d1b3db9d95fd40a8bbcbf998e92c43fcbc55.nq.gz
    ├── 6fd483dde76280eb795202cc7ca268534f9a5a64.nq.gz
    ├── 700513b4bd86a2e8f5d6db86d97087f506297f92.nq.gz
    ├── 701b4ab787127f64f61893bd50f8ccbde485c53b.nq.gz
    ├── 70327faac20563d63ab54c44b906b57efdde9b02.nq.gz
    ├── 7093a51756258bdc7f9af99b8979f4d0801236f1.nq.gz
    ├── 713141f82bb764b115b9a4937bfee6978cff84ff.nq.gz
    ├── 71c71414cc50a45ce24713fdcf85c1034a1d13d1.nq.gz
    ├── 71f80b629cd74cab0b2e1489b40053fb28779e23.nq.gz
    ├── 720facce200c6e558fdf4794e60b90d21afa7fe1.nq.gz
    ├── 723d87e3a731c321da0c330502f41c96758b19cc.nq.gz
    ├── 728836273d0e41f58e4b1e6b959f8bc97ff92daf.nq.gz
    ├── 72d35760567dc64090f3d0c8ac56733f7648eabd.nq.gz
    ├── 734237515bc9ab11337f879af24dcc765e1b188d.nq.gz
    ├── 73434282c139798d4ba0beb71d93ae1b6534cc96.nq.gz
    ├── 735fd062dbfb310a5546d65a50b5d1781bd52162.nq.gz
    ├── 751eddcb375a1de25b6707b2831d8f9606a647b8.nq.gz
    ├── 75d61006563caba57279cf4287061dabb6002694.nq.gz
    ├── 75dcc4e7d81f40c15c43ebcb9139255210d1564a.nq.gz
    ├── 762197cff70909f8d9d973d86a2c632f04a8946d.nq.gz
    ├── 78245f79c4f7defd756e2ef7f378a254f003ce33.nq.gz
    ├── 792d62d858d3ec337387e67c94d096c720fa91bb.nq.gz
    ├── 79357cbbb0929d31c67bd0362f860a2d45e11c0d.nq.gz
    ├── 793f52dc26724b68376dd0adda737ab5129343a6.nq.gz
    ├── 7a0de7f1422849d28c9217ef8a726e04f375bde5.nq.gz
    └── 7a834b8422b18e574ffa17348727f4c8e64d61c4.nq.gz

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

[falconry/falcon](https://github.com/falconry/falcon)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
