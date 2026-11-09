# Repolex Knowledge Graph of Triple-T/gradle-play-publisher

RDF knowledge graph data for [Triple-T/gradle-play-publisher](https://github.com/Triple-T/gradle-play-publisher), parsed by [repolex](https://repolex.ai).

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
rlex download Triple-T/gradle-play-publisher
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 18af18281213c2da5d1031505aae56bf5857a74d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 18af18281213c2da5d1031505aae56bf5857a74d
│           └── chunk-001.nq.gz
└── blob
    ├── 00c7c4c219781670dabeb20a5cf0a86448a6d9cb.nq.gz
    ├── 00c7f19415b326d79667393f42fd09603fa9a09a.nq.gz
    ├── 027298af95f140c4e7fc70bf41a5bea0a2b4faa3.nq.gz
    ├── 0345d8b6984d93e2d968635ef39f156f30acc5c5.nq.gz
    ├── 058db0a857b85fb37f4c6ec047b8899d4252059f.nq.gz
    ├── 08f7a1b321eba16b47069509564b0871b49456f5.nq.gz
    ├── 0a77831c10c45420764d4d71d616d242b0e6accc.nq.gz
    ├── 0b73307bc7e0acf419c7172f4355a3119b678360.nq.gz
    ├── 0db2a64f8932cb6d1907103a67b61149ecf47dbc.nq.gz
    ├── 0e06aad3968c86c705ad2dc52da142df89e5c876.nq.gz
    ├── 0e10892d3cdec91f723fd6b983e82acacd069b53.nq.gz
    ├── 0eb6d0f3782831b3a351e82300f2541b546749c2.nq.gz
    ├── 113570afe10e75335882d4b8ba6d86644acd31ad.nq.gz
    ├── 12307f1399ed1e416181dff026c86ef384531c4f.nq.gz
    ├── 13b6af5534cdf2f690ecd5c1b834dc4be2b1626b.nq.gz
    ├── 1435ef3921dbb388bf80cc7dd3b089056b2eb3ec.nq.gz
    ├── 187ba974b0df375bc44ee47014e775daf4514929.nq.gz
    ├── 19a6bdeb848a07b73de75435f2a2c404e6aa1990.nq.gz
    ├── 1cb895bd134837cfdb2793165fb2caeea3979197.nq.gz
    ├── 1d3aaf18909062b31aeeeb3b683f1c2fad3e304e.nq.gz
    ├── 1e139b19f674a99b1b6e7b7e3ece313492461cfe.nq.gz
    ├── 1ece16b3fa2d48cf2aa1efe65169296ed0ae6e32.nq.gz
    ├── 20625879c901e88da1cf0ad8ccb3e6ae6cef3c27.nq.gz
    ├── 21de6eb35602a98bfcef242d7d7e5b3b00034d9d.nq.gz
    ├── 2404444d234f89b3dbd789cf779fa1bea2e7ad12.nq.gz
    ├── 24592d1927194df40895052d1fe3b5b9889edc17.nq.gz
    ├── 256819d3e14c4277076d0b476a7033fa0e197994.nq.gz
    ├── 2569ff102b014e6e0d983e42a69a8e1136c45114.nq.gz
    ├── 2654d6886dff115a138237b99564c89df1dc0cbb.nq.gz
    ├── 2714a1ac90fe7802ff20be6587126327c2a5062f.nq.gz
    ├── 2816214deea07a402f00d97b01c8c2def0545569.nq.gz
    ├── 287714799ebe66fe3c12e32a2cfde3677ef631d4.nq.gz
    ├── 2b6dd522068b477820ca57fc2eb8bfcc3bf4956a.nq.gz
    ├── 2bc3aeb71a987a38e2fc7b3a628b7c59da13628f.nq.gz
    ├── 2c24d90c62fe4aed7a2e46f8735776a735d347b4.nq.gz
    ├── 2d188a259060ec6d914981e94483d81a27e996b0.nq.gz
    ├── 2e27b0f420ca1f07328f6a468d8ff692e2cfd9d6.nq.gz
    ├── 324e72cdd7480cb983fa1bcc7ce686e51ef87fe7.nq.gz
    ├── 3393587e517d20628660cb6cbcdd458d1a274039.nq.gz
    ├── 34487b117ad490c135b68eeb5c1027adb7e98409.nq.gz
    ├── 3761823a74acc1577c4b372992d8a277d242c459.nq.gz
    ├── 38ac2a5fefd0d717d8f4345dad1873fa124a1905.nq.gz
    ├── 3ab3e9cbce07f7cdc941fc8ba424c05e83ed80f0.nq.gz
    ├── 3d2fdc6aeaa894d704b37e74a2cbdf8af632abbc.nq.gz
    ├── 40f3fbf3efcd3ca38d98a89537c79ed7fd5aaafc.nq.gz
    ├── 43618211ab86f0a4ab300da507e966c08657fbf2.nq.gz
    ├── 43995ddfd8d08f8eb97e4ef577921c4206341ed8.nq.gz
    ├── 4403d14f7770de77c7cf3baaa2c63ed4992183db.nq.gz
    ├── 440b7eed488f6b7c99a8ea9e2161f01820eb044c.nq.gz
    ├── 44740e9980a45a3b14d7d6aea4314c2f0c2e11be.nq.gz
    ├── 4482262ed4e52766c43d57e6c166a883e4d527ff.nq.gz
    ├── 4499a69860ed8d666054b8fa69e50ab4044021c0.nq.gz
    ├── 4501db7ce7623dc4dba043d76ca6f52e5363d017.nq.gz
    ├── 458ff7d49cdb11ed5bbbd4e0c37f9fb0a2b624ad.nq.gz
    ├── 45e44bea47032f2b0bcec1dff52ea2be61c999cc.nq.gz
    ├── 46339ac1592096726d6f8929be112dbda4a3cf2c.nq.gz
    ├── 4b1c3cbef6d7fcc80f69a1a522e80617137875e0.nq.gz
    ├── 4b22f873ad03f75256d4080711867bdfaf585c2a.nq.gz
    ├── 4bd32556208c6371cb7a1de2ab4a13e892220246.nq.gz
    ├── 4cdbc34bdc246bfed0e6b23e214423eecb9c7eee.nq.gz
    ├── 4e2041ff7b9c278e4193ed5fb0d257090f9c8954.nq.gz
    ├── 4e5c86f86c6f4ca38192956e43a86a985fbfc405.nq.gz
    ├── 4f9290be8ff37b779a61a503783e18b5530476e0.nq.gz
    ├── 54b0569f4f760b85134c85c3f8093dd97d8bf04c.nq.gz
    ├── 54c9bfcff87a84a1c31dfb0ba5ecb6ea5b293bbd.nq.gz
    ├── 54e06d8b74f6321474b87ce4b2c24a755a392fac.nq.gz
    ├── 556b6789422b470f7298ea593cfe19c82f347a64.nq.gz
    ├── 5748bfce72d466a940c3eb8d8b5cf79e7b7ad65b.nq.gz
    ├── 597f0788057ae48b61841571d5fc7b6f0c3f2af5.nq.gz
    ├── 5a243285d4b42e77cf376a9af427a867ef8fd7b4.nq.gz
    ├── 5a577fe6510772d1274e89585dde6eb63dcb4346.nq.gz
    ├── 5ff7615f4571d3d8041cc982fd00d97d3f8cd6fe.nq.gz
    ├── 606cdeae0c996abbcc279f9017951d23c8b86ad7.nq.gz
    ├── 61285a659d17295f1de7c53e24fdf13ad755c379.nq.gz
    ├── 61ac748ea539e504c5455a4e9c63c6cdd0a842e5.nq.gz
    ├── 648c8a5b5b2c089bd86e97b947a0d8bd18dc8724.nq.gz
    ├── 65815bfe765c1dcfa0028b396bdaf4c515d7d253.nq.gz
    ├── 66791d4552af6739bbb5ae640e91d04da8392ab6.nq.gz
    ├── 68ab536213989878abfa85cd4d56b8b7fe01e3fa.nq.gz
    ├── 68e4565d25342b957e66324d1ecec7d33b209c6b.nq.gz
    ├── 6ab9bed30c502bbdb1943f7d13c8c7709661c0ba.nq.gz
    ├── 6b04a7908c009408952a909e6e5f74fc4e07baad.nq.gz
    ├── 6f9bf2aa15d513315b8116a15cd9ce87f84f41b1.nq.gz
    ├── 706f256a4b502cccc194e0b83ed0a9a275b8e633.nq.gz
    ├── 71b6aa38df6b04c44d4c7deaa97074cee57d6f61.nq.gz
    ├── 71d2eb1c7fcd99e8b9927877b95f353314167536.nq.gz
    ├── 734f3db067889dd18962444b52ce6242509776ef.nq.gz
    ├── 744753689e350ed606a787552494bbe391a66ccd.nq.gz
    ├── 78197a61d88f30336b32c5f83340df572d308b95.nq.gz
    ├── 787215d4eaefab4509813ee9e7da067b48b8c1ff.nq.gz
    ├── 79bdd954024e69cec1ea230f313c9cb136fda67d.nq.gz
    ├── 7c3b27b20fab29e3e0f9e042496811bfde137c06.nq.gz
    ├── 7c6ff72293057232b6e41f0004e4451a1c0e7745.nq.gz
    ├── 7d90670d5baf2c3acc6a054f8fd3a91810898231.nq.gz
    ├── 7dd86cdc03a5c12637e2375a26719e8b0c19d766.nq.gz
    ├── 7df2c2848b4d3cab373a45bd1217a18879a5817a.nq.gz
    ├── 8072ee00dbf16d9161b7464ef3d2194a7d659bcc.nq.gz
    ├── 808381f2558b3c067299a0f2d1423ba6cd396628.nq.gz
    ├── 80d09594e71b6708f80e387ad0cc8b696481e0b1.nq.gz
    ├── 813f2965834e2ef76b189b6bed1cbde369edbf2b.nq.gz
    ├── 814323a53083cc0617deb87a06057ad6352d5fd1.nq.gz
    ├── 826cb93a365da2f8cfb9a355fa51733f18f76e86.nq.gz
    ├── 82c8a552594ee8cfd6c8ae4a975203bd06f2d271.nq.gz
    ├── 8344c9bc21c1bfa8f7edd899fcc5473406e28b4d.nq.gz
    ├── 839f44131418373203718e6de0d66981d33a14d6.nq.gz
    ├── 83a3157d14d9081ed01cd799287899822e19523a.nq.gz
    ├── 865b3dfa673b85900098ecbe5db36639da79f21e.nq.gz
    ├── 86ec6776fc1215f077c56c226af1e3b692042312.nq.gz
    ├── 87874d47e78c36fa9fcf4ed84ea3cde6608d864a.nq.gz
    ├── 88069315d39b15c0e687320061169ad7fa041d63.nq.gz
    ├── 88d050b1908057b53d38b42702ebc659e3d7f696.nq.gz
    ├── 8c418c281a416c98122ece292ccbbba7b3bdb1d5.nq.gz
    ├── 8e806964dca2a2f530e83ecac3c46a731a60c922.nq.gz
    ├── 8ea0ad1276c4fcb31498be7700ef3415cee79377.nq.gz
    ├── 903cce9434271aee9263a06844b6985629c29af1.nq.gz
    ├── 90589e656909a12eb4c101c643d7ebc00111c875.nq.gz
    ├── 9096d91d156c0a1dadeeebbf0e383187b7782661.nq.gz
    ├── 90e7ab2dce069c943183050af61cebd2b99909cc.nq.gz
    ├── 9338d54bbc03a62d3eccd537120aad25b7f46c3c.nq.gz
    ├── 941884aada964050dd025a2e21fe360c89de4138.nq.gz
    ├── 94d67717fbac22b1c91890e329690480a0ea86fd.nq.gz
    ├── 9556834287aa7adb26e61c67503d9189e71f56f4.nq.gz
    ├── 96389d1eab7f93534055d699997187602cb1c4b2.nq.gz
    ├── 96cdd3b9a973693706c3db1c8e63d5e22d0c727e.nq.gz
    ├── 993fe92eac9b94d78639f12f666d7bee2371d4f7.nq.gz
    ├── 9c14a262b24834774215f967351cfdc8ec147ddf.nq.gz
    ├── 9d1cd74fd3e9b8d6ececbed8b51e3e7a98a5a5a4.nq.gz
    ├── 9daaee181f60c43e49d2dac9b69138cfb5a75c43.nq.gz
    ├── 9f4cb42bc2c6cff55d7b784a1268f43e0620ad64.nq.gz
    ├── 9f854e54d9634e6f6b46557a7cc625f4c2ea7125.nq.gz
    ├── a1004423459058dd95f2daa1c3a179c97907be8b.nq.gz
    ├── a23af04e1a90688305dd9da37e168c4f2f72ba64.nq.gz
    ├── a25737134791fffbef3b8a98f0046a6a86794f8a.nq.gz
    ├── a31b0e08635879a467ddc0726493fa257073c612.nq.gz
    ├── a31c82c43d5ddc98275cadb57de8d29b2e8ea48b.nq.gz
    ├── a4d37fda0b154bacc55598c6db44de5413a33ad5.nq.gz
    ├── a5a45719486c15ec41a45b93e18d94d5f0be77c0.nq.gz
    ├── a9e01b971475190015cfc153df1d09682607edeb.nq.gz
    ├── aa11b527de03ad5a77985e184f40fafafe630970.nq.gz
    ├── ac763b52235add34d7bdc868dd2bccaead653d9c.nq.gz
    ├── ad02a40fb9a8a745e7520bd7351a4d861af50ace.nq.gz
    ├── ad453198c7e892a52ea9c9c0f9d57f8b5c5a1dca.nq.gz
    ├── adff685a0348c64b2b64f0b302f1f82b28eeaaea.nq.gz
    ├── ae7c40bef6ff298f1946000200dae35639a2cbb8.nq.gz
    ├── aee44e138434630332d88b1680f33c4b24c70ab3.nq.gz
    ├── b469a2f6e029a9ba4b9b92b1c60a28c64e061d1e.nq.gz
    ├── b4a4a97354f11c9038d622b67b2a9d636b58d5fd.nq.gz
    ├── b53a97374ec8b3bd48d46b2e50b630c724332acb.nq.gz
    ├── b549b0bcd52465f46842f6e8c8e7b206c559891a.nq.gz
    ├── b57116faccde8995439a280eb1a862ad01fbd6f2.nq.gz
    ├── b88004278d2b653858c2fcca80ab42f330062bac.nq.gz
    ├── bb152d4eb8c755b43e15e28a3c3f09337ff9a7d2.nq.gz
    ├── bb7738020a457f1dfdf3773997aadc328bd04481.nq.gz
    ├── bbab5e7a79526536fedc11671e267b05d7318e29.nq.gz
    ├── beb9970be0573da85819043f0ebf680ec6937da7.nq.gz
    ├── bfa42f0e7b91d006d22352c9ff2f134e504e3c1d.nq.gz
    ├── c133a0cbd379f5af6dbf1a899a0293ca5eccfad0.nq.gz
    ├── c23f7a808862a331e800fc07b1c7b4ca1d538718.nq.gz
    ├── c2b8e3d62900ebd37b8ef1408b22bb9fc164c733.nq.gz
    ├── c2c2c9661389c17bd0659e8cb192197c935fbe93.nq.gz
    ├── c50fac3cc627914c7c9035e5d8e4954d883eba2d.nq.gz
    ├── c5e68ed7a5e1ab6e785b473d9ad9f23bc7b5ddc2.nq.gz
    ├── c736fb82f3cf6a0507e927c7a93f8b559379f0dd.nq.gz
    ├── c8dacb720f9e03d946cbfabb0cd35ad9c667d582.nq.gz
    ├── cde69bcccec65160d92116f20ffce4fce0b5245c.nq.gz
    ├── cf536716db478b70bfe2c88dcd1575b8c832cd55.nq.gz
    ├── d0e33400779125edcc8a2f43ec82d9da7efe6547.nq.gz
    ├── d10af1d023146dace1a36f1e280673a72b8aaf89.nq.gz
    ├── d317042e8c9e4647da3332aba723d307f732cd06.nq.gz
    ├── d425d90b23ea02f82936cd7501616bc6e8bcf400.nq.gz
    ├── d44584ccaeff9fde3cebb24b2d5543f6321179dd.nq.gz
    ├── d4e691d56f90a3467c33d95471eb1bea0d32338a.nq.gz
    ├── d5ff0576ae3eb2118f1c843595a46ad35d2074c3.nq.gz
    ├── d605416b9ec522c7693f9c3e3b5d17d0ebbc6ca0.nq.gz
    ├── d914cbba4042d88a4bca52d6c63896594de8d8f5.nq.gz
    ├── db5b4483b31fe6761224590649481ee84fd83f57.nq.gz
    ├── dba87efada3618a1d75e6b26c02d6c042f6675cb.nq.gz
    ├── dd1fd1f7878dea9504e9a58b435ab01db017fc9e.nq.gz
    ├── dd3255b5c3806eac281f9175b4047c257d0c9653.nq.gz
    ├── dd530b3ab1b518f75355192f7778344420cac193.nq.gz
    ├── de9fb218387d3dad97623a9cffa86d74edb13746.nq.gz
    ├── def73e6f4a5e87f31cec099e4e05b44673b8b5c2.nq.gz
    ├── dfb37df28e2d38dde75340576cd1f80689f5ead2.nq.gz
    ├── e509b2dd8fe5579a5954a2c28633ad914cd1c225.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e73034f9cc30af032077938827d05542dc053127.nq.gz
    ├── ea3320439d3bd9c7a39cb19d3f6217a088915ead.nq.gz
    ├── efae06b06ff5002eabd31838c972b96f145941bb.nq.gz
    ├── f06c9b0c8751122a1f4eefe171359bcd8c5eca39.nq.gz
    ├── f13a556d5d70782699edeef181fd1af159e08682.nq.gz
    ├── f15c2f0f87ef92d6e7579eebc7cbf54c089e81be.nq.gz
    ├── f1a797a6b196603c55b2093874bb7354ad5fc402.nq.gz
    ├── f3774ca9b678b82b3d45a1043b0b7db84adb0a25.nq.gz
    ├── f656ed8744886238c5bae0f46a4b5060b3d4d206.nq.gz
    ├── f8e1ee3125fe0768e9a76ee977ac089eb657005e.nq.gz
    ├── f93693e7ba3abc989b27c503a30629c839024612.nq.gz
    ├── fa4cd9106ca3b833e8c48a1297b0a44c95076422.nq.gz
    └── fc453d53d6ba82776b30318beb2e388f5309dba0.nq.gz

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

[Triple-T/gradle-play-publisher](https://github.com/Triple-T/gradle-play-publisher)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
