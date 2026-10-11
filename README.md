# Repolex Knowledge Graph of cherrypy/cheroot

RDF knowledge graph data for [cherrypy/cheroot](https://github.com/cherrypy/cheroot), parsed by [repolex](https://repolex.ai).

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
rlex download cherrypy/cheroot
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a6283c12ca185cb0b94dda002150cdd21939a08e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a6283c12ca185cb0b94dda002150cdd21939a08e
│           └── chunk-001.nq.gz
└── blob
    ├── 01927d72295123d78ad60dde6cd71436c5a20cab.nq.gz
    ├── 02addec802540523aa119c827827a214aba1fe79.nq.gz
    ├── 02fa86a57998a4dc5183c808392ae950cd7120cc.nq.gz
    ├── 049b9d4ce035d4fe049a3daf4c6e65b498486a8e.nq.gz
    ├── 0612d2e54307381c379c6f8a7208d10ab5ee7325.nq.gz
    ├── 073b28f3b324f63eb1d27d4ec1f57c06c28ace3a.nq.gz
    ├── 07a4f3292c202bc47bdb1e68b4807059104a959c.nq.gz
    ├── 098b8f25ff80ca80fbaa182c45106a4edbff4519.nq.gz
    ├── 09bc80f014b481e5a599a528f4c0490e45a1bca1.nq.gz
    ├── 0bf10432438094efb4fc7c09ec07c5ca1d9d377d.nq.gz
    ├── 0c71a1aee9e40cf11381b42637b3ea5f613160ea.nq.gz
    ├── 0d9192add8ca84f802a8b2fe270ae940f6b978cd.nq.gz
    ├── 0d93ac77ed5a0099788f5b4bed16f8b91329d315.nq.gz
    ├── 0f8e24455ad875ec39abe3fba1274ae5caf38941.nq.gz
    ├── 0fac949c872b036d4bad250bbc62543d0735d5d5.nq.gz
    ├── 0fde174341f185a7b444ea43a714fa8bdcb304ee.nq.gz
    ├── 12e5599fc78557f921be97945f4b2ccff194af50.nq.gz
    ├── 13b724aafc6bbfdc3e5985f465dd94d3aac6a6df.nq.gz
    ├── 140bad1a20cefa01e4922ad0b7103a8a50a3f63a.nq.gz
    ├── 146c670585462d62459e1078c0f060d8793f1384.nq.gz
    ├── 171b405382cbee7eaa1ca3a78bf9e116cfbd4162.nq.gz
    ├── 17b74509cc52a7616d5992883912142b47420d8b.nq.gz
    ├── 18bd840b4dfe3a800ad85a21203df126dd669106.nq.gz
    ├── 1af89f9988f7957f47fe56334beefadf2d126397.nq.gz
    ├── 1b1f1a41e4a8fdb19042b6fbe54d16e8600fe3f0.nq.gz
    ├── 1d4379d8916a5da993d35d614075f8b2c55d05e9.nq.gz
    ├── 1d4c6b5020f693eaabee4a12cdec9f69da3d267c.nq.gz
    ├── 1e3e1ae543021b23655be3418c4d063ab7be6a4c.nq.gz
    ├── 20e6a6b512d1ea774b31b19f50646c42092c2dac.nq.gz
    ├── 21052bc2c8bc60f7147f3bfab3a5c9219c539340.nq.gz
    ├── 218bd29082da1e0e6123538acf42901a9ad8231c.nq.gz
    ├── 24a0751574f64ac4c28c18a3d3380cfc3c9bb14b.nq.gz
    ├── 251a1ea3cd8b7621186cc249ecfe77178ce51d22.nq.gz
    ├── 2879ab2fdd3580dd4a1f12acccefd0b9bdc09cc9.nq.gz
    ├── 297feb8a7b112e5985d0e12a85402e0c3e31ee93.nq.gz
    ├── 2c0bed6ba192fc2ffe03c7b496fd9d5aa4905b38.nq.gz
    ├── 2dc9dc2ca003cda2aab0c5e864edc9853fa46b26.nq.gz
    ├── 2e0fc5688d58d87057247da2499b920feeb8e324.nq.gz
    ├── 301d39025a2e942605b8a448f86b7e594af42932.nq.gz
    ├── 31055153ff12ed8167df176d564a94d5659306c7.nq.gz
    ├── 3592439c031e901e49afbb9fb10b063117687d56.nq.gz
    ├── 36beb23ba5e2913b0c113876836677ae8901fd84.nq.gz
    ├── 372c86aaa1eae64fe1366b5d08d94f0897023b81.nq.gz
    ├── 37749cafb1587dc5f2244fc24ad4d963bff137e6.nq.gz
    ├── 378b73b7f9748741bad7040f4c652000d6cec518.nq.gz
    ├── 37c5a042a42da51dbcfb7ea16d13f34d021f2396.nq.gz
    ├── 380386266ad8b05d6e8463459e40e87fb602645f.nq.gz
    ├── 384723769c744bcf6a69164a62ddfe26921b16a2.nq.gz
    ├── 39a8263ddcc773b67ecf947240749d5acac249d5.nq.gz
    ├── 3a38e02d4a37fc2702a256a09b425a509608a7b9.nq.gz
    ├── 3c59fdde9bafc43046974180b65065f7d4c780be.nq.gz
    ├── 3dde2eaa4cfe6dee0045748b18c8db8a4fb2fca6.nq.gz
    ├── 3f2f3692b5e740947e079fc97587da3fde8f96a8.nq.gz
    ├── 3f5ea2756b143896bac557a302e7707187c3c1f2.nq.gz
    ├── 3f7b5cfad2bee07776e9dd2045d23ba2977f4389.nq.gz
    ├── 4032a326e629e8255c265d0cdd0fd37060980578.nq.gz
    ├── 4072d6b2ba953f3834f0d45ef78a7d382d9a1f5e.nq.gz
    ├── 409aaec6c0678d94934bb18b23d89bb3a75fea29.nq.gz
    ├── 41f62685482d00608c3255cb9df48fe59dbe3f9b.nq.gz
    ├── 434de436443a6a2cfebf4408d66eb5417714c798.nq.gz
    ├── 43db925f0dfda1a186d7a183cf417d1370f13431.nq.gz
    ├── 43fdcf9d9f285f5c55cfe3dd5f90e85047cd4e34.nq.gz
    ├── 458bdcc3d6a3cdf27feb97dd16d820c8d9832c2f.nq.gz
    ├── 472bf57a098606ffdcdd2816d6d10fa71e6b00aa.nq.gz
    ├── 496a32be4adf3bcc0f4769d09a85148654d0c780.nq.gz
    ├── 496f5ed181d497ea6f34eef2d5201b45c17ff6eb.nq.gz
    ├── 49d17d08f7a6f2291321ebff61ee0855414edb6e.nq.gz
    ├── 4ac4b16764126e2329b09440c41baa02abddcab3.nq.gz
    ├── 4ae1d9ae11ca9e32d818deb69c593ced8f2845b2.nq.gz
    ├── 4b0e79678400e184fd5a3602c3fa02b7ca8039e5.nq.gz
    ├── 4d27454f1a048fdb1d8b450cc4df236c5fb0afda.nq.gz
    ├── 51c7e3753566dd42106d7e8774f3fec3d29d4f0c.nq.gz
    ├── 52177bb680d801e5ad732db90325decc4a626584.nq.gz
    ├── 53483a2be86991ca3c050a93857d0d359c8912c9.nq.gz
    ├── 5387ca403cd19f10658ca948f17af4b23c8eaed2.nq.gz
    ├── 54649fdd55e4098f6265fea4316d63bedba90f9f.nq.gz
    ├── 551bb1a942b08816010b1f104a98824fc3d04de6.nq.gz
    ├── 554996340bad8847e9b63756f526e148b80b8c9c.nq.gz
    ├── 5630c8d1038a3eaa9afb2a21841b2084a31a8d0e.nq.gz
    ├── 568851f92dd5b44aa3a4fa356aa13fbec6acbad7.nq.gz
    ├── 582588e9b939f39bac8928e927c91091debdc8ea.nq.gz
    ├── 5896f56338cffb94eba8b114be7b2aad30536ddc.nq.gz
    ├── 5e2eca6f0597f7f65cf091dc99ba60d09466e298.nq.gz
    ├── 5ef796cdef4fd83c1ee83a9b391c2101a70ba52b.nq.gz
    ├── 607b79a570905132b3f42f2f42bb104c067db49e.nq.gz
    ├── 60bcc3f396c82229cbfc89148a0dd68b900eff64.nq.gz
    ├── 61ba303ace517978f8ebce095df12fac8a426633.nq.gz
    ├── 620069cde5f0a761893da3d142d2aa7f37b1593a.nq.gz
    ├── 6227be2773624d8afd7ce9e524e2931a88144974.nq.gz
    ├── 6287e68db8f8909249210cfca1bf985807267098.nq.gz
    ├── 632bef6e79497059dbd2d8ccd0f77e9820f6de97.nq.gz
    ├── 657997c3f269aa6e92159b97e83c9c06dc46b269.nq.gz
    ├── 67aca43ef27b86c9814ef738426a6deedb46e59e.nq.gz
    ├── 68a874dd2f320ec8f4421b94bfe57ef1a33c171c.nq.gz
    ├── 6a09f07f61de40ebddd9a2f9723e54edd71ea149.nq.gz
    ├── 6ab1219ead29a488b0f60c8679a44336bcb5553f.nq.gz
    ├── 6acb3b415aa0ee5568c3c30ff1e447d21c53b6a5.nq.gz
    ├── 6ca8d09eca869567eb8991bd3f382e6dde740a94.nq.gz
    ├── 6cf700341a674287ee80e7561dfa9919bd705e72.nq.gz
    ├── 6d86e5fb89e87285f4208d3c9990ed1a5b8d72c9.nq.gz
    ├── 6dd7f7977d2f5bb7066191ef1c13002719fe0959.nq.gz
    ├── 6e1d70c319fadae221207dcfc513d3e3893e3159.nq.gz
    ├── 6fe5f03e852878748422ec019b610105df14d94d.nq.gz
    ├── 703e4620d55aa39e83c0e77ae12d3f94c8380cf2.nq.gz
    ├── 705f43bc9209a05df9ed633b1b721108ee1abf2d.nq.gz
    ├── 71940dcbc50be1bf9ff57bb640cbe8bcd8b547a9.nq.gz
    ├── 71c9d9a19b70db98a64e01a862d9d893aab5c48c.nq.gz
    ├── 7472f61c8c0b5a276071f9c1d252e6ebb75928cb.nq.gz
    ├── 7605ec3ee8211df3df20b9deb9aa48d905c51bb7.nq.gz
    ├── 76342657dc5ef988b817805a3f02281f657636a5.nq.gz
    ├── 77ac31ae832559f226f3b15ef18aef9bdebfc283.nq.gz
    ├── 78e7d56e59f94db4c54c616ceddd7cce959d61aa.nq.gz
    ├── 79587652f08e61d95133fb4d0aa18bb36c387122.nq.gz
    ├── 795ac0802db9b205e1568eb87dfd68e39e866237.nq.gz
    ├── 7aa87d3841056c17de23f7c9170d0367d18ec8f6.nq.gz
    ├── 7ae658e5ccb15b8cd33291d58b1af414217acf7a.nq.gz
    ├── 7b0b224b347570df3485c3f0eb64462b5cff4818.nq.gz
    ├── 7bf593761535cfaed34414214a5c97e153722741.nq.gz
    ├── 7c2cc5514282523d77bbbb7eaf68c462e8d6f9d4.nq.gz
    ├── 7e7501ae3493efad97968f980e81f73bcfe601ad.nq.gz
    ├── 819ef68debce59c09ae71a13e32563969ec0dbf9.nq.gz
    ├── 831d85ab91ac02c4103e1dbead633fb7331a0a7d.nq.gz
    ├── 85b514f825d7a5d57732356e6b153a2096e2be0c.nq.gz
    ├── 8841e2754280e8c14ac4940e889ca2bbce1bc13a.nq.gz
    ├── 89292604d8ca8243c651dc9089aeb7ec585188cc.nq.gz
    ├── 89793309aa2798f0334b07280e4ae2286b248490.nq.gz
    ├── 89997250ceb53de13fb998c1991651503986b5a7.nq.gz
    ├── 8a04762bae4ceccdbad7a88621d8affb1db3cae9.nq.gz
    ├── 8aef368513ecff529f92480dc76913639d430762.nq.gz
    ├── 8b36b8870015212b5aec8b5e4550040aaa61f77d.nq.gz
    ├── 8c6f171eef78bb63e91f289f3cb1cea6b8742133.nq.gz
    ├── 8d3a9752e04703a276cb39e3fe781c3c75b0b3cc.nq.gz
    ├── 8d9683c25cd73736ce324987c6a9d8ad5c68cb5b.nq.gz
    ├── 8ea38fd99b1ac6e15d4858a33fd9e519e3f03d3a.nq.gz
    ├── 8f1aafbd01c22fce63412abab825552a2ef8395b.nq.gz
    ├── 8f5a13eae83d6447945257a69b8d2d7e00ba1cda.nq.gz
    ├── 91466e1f7cfe2f20b68bd4d315a162a99f39a034.nq.gz
    ├── 9216409088b7f5d8e4400b3fe1b3375043ab5359.nq.gz
    ├── 938176b69547eaacba3ba2be97338a32ad4774a0.nq.gz
    ├── 95c93aeb04db25e76cb2cd63fe6d97a1734d9206.nq.gz
    ├── 9626e175dc61ea6292f1ad5c7ca17e64d2be8e62.nq.gz
    ├── 96b41076676d36f8dbc1ba5163db6910d5099bd8.nq.gz
    ├── 97afb0483bce3ff91d4364d2420d10d7516240b1.nq.gz
    ├── 98885c8ff03f960ef75719a84b711e2abe5129d9.nq.gz
    ├── 988e5843a584b3d923d66dcb7d75d54229c9c168.nq.gz
    ├── 99cc2208ec7af9b680e2e71ed5ef69092ff5de8d.nq.gz
    ├── 9b5de0aabfaa23d9f7abaf77c360bda8841b1352.nq.gz
    ├── 9bf1d50e75c2c1509201daeaacaae14a266f22a3.nq.gz
    ├── 9d8403cf2b5b21c7892156b5352fc3700cfa1380.nq.gz
    ├── 9e0f00a5fdaea3d13945c5898df70582abfa1146.nq.gz
    ├── 9e17664b1a0768843f67df51a9c42895fae926e8.nq.gz
    ├── 9ed75440ded09e930da30118ef038393e4797c27.nq.gz
    ├── a1103595c22a35297a0795f19aec5146188eee45.nq.gz
    ├── a4f20adfd69262ed89d33f34bcdb81844112fb70.nq.gz
    ├── a55be37ee446bc2aca05666116b7e9ca8db84bbd.nq.gz
    ├── a58af9410399d2f3a1ddf89273f609fb3b69796a.nq.gz
    ├── a5f0594b58b4009a5bcc2e2667c0f8f62608e2d3.nq.gz
    ├── a639e6699410594b2023e36410d4de1c71d57785.nq.gz
    ├── a821f3795800f4eb80e6cb0d48c552313004979f.nq.gz
    ├── aac4386ef213d773d1a35370a2cc75df11b14e4d.nq.gz
    ├── ab33c6e3385f37fa217cee64ad8d2eda19588de1.nq.gz
    ├── ab5c1af86e78cf6c103d05bf411e28392e3777da.nq.gz
    ├── adc5ada024c2f9a853c974f4684169b7fe337f8f.nq.gz
    ├── ae6e390a44e8d9a831651a8bf19213d32a771d39.nq.gz
    ├── aff9cf133483ee53ca7130827d4bd0694e54f3a9.nq.gz
    ├── b0159eaea51f902de7e7ecb9f8786a6a542ddfa4.nq.gz
    ├── b18bba5502bcd2dd4c4e4c001010a7b5ca080701.nq.gz
    ├── b1c1de7c3806bfbffbae6aaadffa04d81aea41ad.nq.gz
    ├── b382ff2f8685f60fe5012a7d2d999f928e6f6c8f.nq.gz
    ├── b3993ce7003cfe1f3a4e2aa3fca48e41d134f113.nq.gz
    ├── b659ddfee8ca085867c9936e19770607300d3353.nq.gz
    ├── b7fed72b214ca61fb70205eaa31d15d6d8b25912.nq.gz
    ├── b8120ee06e45ab1a5ba46561ae22a7592c2aaf12.nq.gz
    ├── bca8cb7479465fcc54af71e32af1d66ac4bd0973.nq.gz
    ├── bda5b5a7f4cc3cdc8ef37ca67f3a0d26c3c0aad7.nq.gz
    ├── bdfe180a6879beb0df4e316020e15446195b8f98.nq.gz
    ├── c129309a8ca2cd25eb39eab5d57b74369a46cbf7.nq.gz
    ├── c49d065bab3e42f69c96d5a24ef14bcdf9dbb69e.nq.gz
    ├── c5bb97ee0b2821b05901e323916d48d796526627.nq.gz
    ├── c7856d567adec02ad46d6199dbadd05412e8fb60.nq.gz
    ├── c78b1c9095d66c27fa06b9557ec6de118328a412.nq.gz
    ├── c7df2da5996efcb37d0f5f68cde7567effe5539f.nq.gz
    ├── c827a567aa12ee01356110be5a897e7d303f5e7c.nq.gz
    ├── c874f59ab4992d4f70a6775b419a24a66ab615ee.nq.gz
    ├── c93701177f8830e76281b934f93548ba49617d27.nq.gz
    ├── cab0fab89122b1416dcf37157c7b18a2b37d1d8e.nq.gz
    ├── cb7b45518ff7532784b76ea00a19918d35d1f566.nq.gz
    ├── cd3841d4284ff204c4836d769e11e9029dd4bb87.nq.gz
    ├── cd6fccd5ff5869829ee70abe9f67a1aa947491b5.nq.gz
    ├── cfb907db5c1781bc4aed8a5f4444dd6f4cf43a2f.nq.gz
    ├── d0a53b4410947ef4a8974cf63901ef29354cb83c.nq.gz
    ├── d0a842cc60c7b6f00bc172111b1a473255a2976f.nq.gz
    ├── d200556f0b9d23648dbe922e4c167dc87371c5a4.nq.gz
    ├── d36832df25913e9b986db37b6c6a2ea4f9f4fdef.nq.gz
    ├── d65d4ea268311f1c61141c447e522ec6175171a9.nq.gz
    ├── d6b7ef32c8478a48c3994dcadc86837f4371184d.nq.gz
    ├── d9ef0e9e87ab0d8aa937a934d5e119ac9f2be5ed.nq.gz
    └── da3daa4e9f103ff704764a1bcf565f420ced2b93.nq.gz

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

[cherrypy/cheroot](https://github.com/cherrypy/cheroot)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
