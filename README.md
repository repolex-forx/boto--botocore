# Repolex Knowledge Graph of boto/botocore

RDF knowledge graph data for [boto/botocore](https://github.com/boto/botocore), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download boto/botocore
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d831a0618fc491a30135f89f743ed12cc09280af
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d831a0618fc491a30135f89f743ed12cc09280af.nq.gz
│   └── repolex
│       └── d831a0618fc491a30135f89f743ed12cc09280af
│           └── chunk-001.nq.gz
└── blob
    ├── 00326774342712fbe7d2b4ae1bc37957d38b46ad.nq.gz
    ├── 003c55a040780cf41a77cb53e3d5a957d94bfbb9.nq.gz
    ├── 005a72d7bf8a2cb6426917558044b7871fdb9e14.nq.gz
    ├── 005e53f9422df7414257db3d66a34d80013c58b2.nq.gz
    ├── 00661717a60d044ebb632cd709839c84d57869ef.nq.gz
    ├── 00700321b9ec92374a14d27d7d62731e1c740d52.nq.gz
    ├── 007118e680b281a6ccc7220b10928e9459094da8.nq.gz
    ├── 00790e4ecb6a04fe4fdb63903ac49251d0712b8b.nq.gz
    ├── 007c0fc533b471f0a0489487d1bf662e038446f1.nq.gz
    ├── 00985d01d03e4c27284c5636310eae54235c884f.nq.gz
    ├── 00afd80c1e059023d3d587a1b9b806694ae5a8fc.nq.gz
    ├── 00b31d214d136549c132eb7ab999b8cf504f03c8.nq.gz
    ├── 00bd15c36104b98df1e7ea21bb6feda3e6c278ed.nq.gz
    ├── 00c847a6a4805d74a635f666d9d52ebd44f89d99.nq.gz
    ├── 00ccdda622cb1619f6dde08ba2c3d5a7c8ce203f.nq.gz
    ├── 00d507fc078a5d92e96b8ec1334ef2ccf6283233.nq.gz
    ├── 00e031de32459d8a5ff7da2d1f368230ad16462c.nq.gz
    ├── 00e071c4dca01f81acc93ab79a81bf3e6bd57d27.nq.gz
    ├── 00fbe92049af99a775215c6ce0b8732e8d4a69ab.nq.gz
    ├── 010bbaffe2deea961f523cecd126b58dc80b2b34.nq.gz
    ├── 01176ffbc705dbe19dc7cb609cc84460221d7220.nq.gz
    ├── 0119102f65ff122c92de0864025e55ae0df5de41.nq.gz
    ├── 012059af695fee482680d83ef9b2a330016ab28c.nq.gz
    ├── 01254614ea2770a9fb1da79c3c40b255cd504732.nq.gz
    ├── 01362960114e7efc8bd1214be4f77ff1843a4fa6.nq.gz
    ├── 0137e842b62710014992849b81f5362064320e40.nq.gz
    ├── 01391db9d656fbc4d1d2b46dd858b4118bf93bf6.nq.gz
    ├── 0144a29417a7ce81ca65fcf43e40ad91ad128b26.nq.gz
    ├── 015e61a5329350e63d7e5295b8f5ae1605acb1f4.nq.gz
    ├── 0176ca15998f0ad605a34219c2d4e7c5dd5d6827.nq.gz
    ├── 017b09c132ea99269c3d571d21eaafe30b750c7d.nq.gz
    ├── 0184e26f6cfccc048cff738f9deb55e24b686e89.nq.gz
    ├── 01a4cee035697a6f5af68f19c601f5a6d288d22c.nq.gz
    ├── 01a99e68e76712e3d3f2eeed5c6ccd12cb427d32.nq.gz
    ├── 01bd9e40d7e0f18374944b75c7fe48be5e9fe281.nq.gz
    ├── 01cca0ccbf4141d631ad15879109396d8314ecf6.nq.gz
    ├── 01d43f0a0172a86618b8367ed977199874ce6116.nq.gz
    ├── 01d7ae1694f45bc9145275325a2bcac9385240b7.nq.gz
    ├── 01da4d3e16aa12d305312aacdbbb2b81a28085bc.nq.gz
    ├── 020262a1802eb7ea7489f6aa83fc922243ed7722.nq.gz
    ├── 020c562307369b9f74d766557c38415b228cd5b4.nq.gz
    ├── 0222806aadc877d482779942729e8498b9857c20.nq.gz
    ├── 023ab19ef538b13aed26f41012a00f9a980a3c81.nq.gz
    ├── 024682ba8a4863fcf7b9c638bcb49bc488e3d411.nq.gz
    ├── 024feff1c94103e741ff0dd2eecfc85451ef4857.nq.gz
    ├── 0253f19456b1b565e78ac795242bbd49b5e048a2.nq.gz
    ├── 0263a7a5990dc7302d6261ea05dd44dafda76d44.nq.gz
    ├── 02800697c139142bde915cfbf4ee7f0ac414d407.nq.gz
    ├── 02865046158e8347cc618c4e17fd60e0f9fe5da4.nq.gz
    ├── 02af499b6530a04956593cc47f962ae160de33d2.nq.gz
    ├── 02cc67872022462ab3f876ce218f895dd2241d6e.nq.gz
    ├── 02d230828393aeab7b44244ca6234ebd1db39379.nq.gz
    ├── 02ef1199c0685048995c1ff00c32b48c08e0f769.nq.gz
    ├── 03007a6028a86c29ece5050d383409026447dd03.nq.gz
    ├── 030502cf04c42aef94dbf0d83f3bee8c4429dfb0.nq.gz
    ├── 030d45ddf0b20b50519d22838c7d6ad6833149a1.nq.gz
    ├── 0325a2d8614a1a3c30e3da3716b4bef8e96b3216.nq.gz
    ├── 0326c2924b686202e054db852a0eb16f7d7b018c.nq.gz
    ├── 03313bbe4a51f343a27efb99134cf4b585f20add.nq.gz
    ├── 0341b4ac7ed81510d947f2c187a32a04be9f8e87.nq.gz
    ├── 0350f4f38af583025eb745293e8cb9db20855ca2.nq.gz
    ├── 036e1820fa0a23ba1ebd2ae29f5e9cf80a7750c5.nq.gz
    ├── 037b563a01382fcee3caaab11aeb44778c9b24f6.nq.gz
    ├── 037be5b72091d7a80c8cdb5eb8eee67074715e92.nq.gz
    ├── 0393685431610caff1948c1a604cca0840ea4efa.nq.gz
    ├── 03981a835666c4dbe40a824e978fb33a67d6704b.nq.gz
    ├── 039e04d60f3452d93a6ecffdb12bbca24802517c.nq.gz
    ├── 03a10ed65c11d3d2ca06a1d65aabb350eee1697c.nq.gz
    ├── 03a3ca4d58d588c5b29e24a6922e8b347f91ac7d.nq.gz
    ├── 03da75c8dc13fa513fd2a1b5016ef4c1596763dc.nq.gz
    ├── 03dca5a516d04cc640ed60dfb66d8b6e8551a570.nq.gz
    ├── 03e1cbfce771c4466194cd147cef7b3d620d9edc.nq.gz
    ├── 03e5937bcb9f8001e61d6b95ddc12ae784496f6f.nq.gz
    ├── 03f958ea1ebb0852a0f719a5f091ae91e4a87b86.nq.gz
    ├── 03fa1e7912f042e35314f0a9cb4df4e93b7b5bd2.nq.gz
    ├── 0405f5d7f3a790f69b42797ffa1cc241fd401c77.nq.gz
    ├── 04077dcdce00a4adba60728aa123caeea4a0fcec.nq.gz
    ├── 0419a71a177bde58fb633c0d2c9290e4e10d41ba.nq.gz
    ├── 041b709a9cc0cc0df2976c1c5073cf341029c507.nq.gz
    ├── 041b8caf797679179d8386021d49e88c932c366c.nq.gz
    ├── 0434a22e151ebc56f4eb6dcd75e601145870b1fc.nq.gz
    ├── 047d3e2f7f75c24931f262928d7e3c53a261ff77.nq.gz
    ├── 04806c31428a3e5bebdbbbc4fe305ea8bb0fbb3c.nq.gz
    ├── 04996ea1a21962bf178e17b6fa723177d7998e5d.nq.gz
    ├── 04ca217df157e5b4a6140d99326289b90be52f50.nq.gz
    ├── 04df99871cb8f06937fd4eb2f42efc7443b618bb.nq.gz
    ├── 04e014f6719e46f8af732da24dcfb2ce26744cf3.nq.gz
    ├── 04e4a111a1d3a5506ad46d36ad104be657c30a45.nq.gz
    ├── 04f1b7b1d231adec8b21e74f445865e5903ba7d5.nq.gz
    ├── 05085bc80bc96d656019b3cdac58d825ac4089b0.nq.gz
    ├── 0508b1b1abc3f727fe54fdc6653e5310e0105e71.nq.gz
    ├── 0511da33a6f47240b175d28d941c4b8d142f66ae.nq.gz
    ├── 051263cf237de0e5a1cd24f766a6c0be7609d01a.nq.gz
    ├── 0512ee697101459f4543fd0a36a831f479025285.nq.gz
    ├── 0526a90c9f38a0ab58d563a65bd2aa21fa6c50cf.nq.gz
    ├── 053c8e598067b03d078096901f85d90055dc17ac.nq.gz
    ├── 0547f1871fabc40bdc754d7859485625dccb4aed.nq.gz
    ├── 055348e8e3a0dbf756e416ace11b3ad50397be31.nq.gz
    ├── 055ddb0f9baf7d6a7620e07c069a6282727d4097.nq.gz
    ├── 056d7f3a50d4318d777b163089f3878dbe342f4d.nq.gz
    ├── 0574fef71d38a44d62f6de857ad9ee35bc2d3141.nq.gz
    ├── 0582f5aa8cb0f82b2e6710f432b8b3317b2216bb.nq.gz
    ├── 058f74513bd784efeafae2504c273823e4ed0e02.nq.gz
    ├── 05953374435079dfb0e7799fadd2fd7a5c99030e.nq.gz
    ├── 059dae7e0ce1f2791088236d6285350e6f79d9ee.nq.gz
    ├── 05a7ea8482fa00e21d3e5a776f0a3c82de576319.nq.gz
    ├── 05ab239ec51cce7db4f156baf765c2487a929c37.nq.gz
    ├── 05b1594aa149eba4522d4704f792866d77ae051b.nq.gz
    ├── 05b2393010e230074badba8cd5fef4240fc1752d.nq.gz
    ├── 05b541f045665d048b8aa34aad7ade34638e07d4.nq.gz
    ├── 05d5e01a9178d8f86c193811da0e3c12a82ae94a.nq.gz
    ├── 05d87d960645d930d1de07a8c3ad281cfad59e8b.nq.gz
    ├── 05eaa5781db97d019622e672dba85f2f01ea7ec1.nq.gz
    ├── 06186ce94d2b9ccd8c5d47d0ac89fd1c1dfcaa89.nq.gz
    ├── 061f8bc50ed78b751f00699f94ab49da91477570.nq.gz
    ├── 06247d72fee09085437a5c2bfeb0e9a66e2f6c02.nq.gz
    ├── 0625362eb61f9644c7ff66346ebca87552824abc.nq.gz
    ├── 0625b623a844d8de33afec5e03c25674bf00330e.nq.gz
    ├── 063c6236dca44658cbe9f56c74570331efe6ed13.nq.gz
    ├── 064adfd633ca60e660c1046ff15de550d71140ee.nq.gz
    ├── 064e20265ab6591a9d173a0c96184e9aad5dacac.nq.gz
    ├── 06681395a223e950bdce3c010caca2b644fe3fd1.nq.gz
    ├── 067de363bcd828b7ea5e517dc284c8cb18b724a6.nq.gz
    ├── 0697cd288213550dab395f0ea81082608881f6b1.nq.gz
    ├── 069fe163e144297c431f30a794dcee5f6e78c556.nq.gz
    ├── 06bd81300e64e0daf03fbae00b1e47a0018e7767.nq.gz
    ├── 06dd5fefae6d47acf50c3946f67f8409d1900e27.nq.gz
    ├── 07089a522af1c0231fad799c53058e44745f13fd.nq.gz
    ├── 070acd6ce458d9a59d4a5354d8557d11b92a71b8.nq.gz
    ├── 0714b1ae588cabc8ce3986c414629f6d6c34fa6f.nq.gz
    ├── 0714de81a05e33ebb780a49ecfd2b84a36f73501.nq.gz
    ├── 0724cea844d462052b2caad2a1c6c939d8963e2e.nq.gz
    ├── 0736a85471419ec0e7f874d202e3626bab390324.nq.gz
    ├── 073d83e87a8161e982bbf2353a3537e81dca95c3.nq.gz
    ├── 07482e8bc7b0a326f133c7054724b3f5ca22cf5e.nq.gz
    ├── 076165d84a9701be70b33658c987cadfb8e260b8.nq.gz
    ├── 076c8a1820537e375a6afa907eea8ffc4dc67b5b.nq.gz
    ├── 0772c8ac56f5197240c8b11b5fe4ebf8bdce19f1.nq.gz
    ├── 0775efc0fcdbd07c09c6e0503584c89380354314.nq.gz
    ├── 077b8c8f42a6f198bb1047e7d67c8a7f46a1d7e3.nq.gz
    ├── 0783efa23724126ad6ed5a3e639231481e004e11.nq.gz
    ├── 078d356478679afaaffac18bb41fc80654ce413b.nq.gz
    ├── 07903f1199ca553b08f3ced31983955b1c589df2.nq.gz
    ├── 07a287ff6fefd427ff50b8be8fd43f02421d408d.nq.gz
    ├── 07a64a056d43ded02a83c93f10934a1dbd1dcb2a.nq.gz
    ├── 07adb69f711c81cde7cbfb3e9c3af0d844303a88.nq.gz
    ├── 07b5dea6d8a1e542c736c7dda1ad74b37ea2c394.nq.gz
    ├── 07c35e5772597e1c8d7c43ca17189f7cce32d6e2.nq.gz
    ├── 07c51d8038d17899225a7b12ff8bcb52ee4703b9.nq.gz
    ├── 07cda416672bf18728d813c2c2c9fa1e32a2bb43.nq.gz
    ├── 07d44a2052839c1b77c84c29390cca753a352391.nq.gz
    ├── 07d8e9e55475cef182c7d19d7f669852ef730070.nq.gz
    ├── 080a83293070ec463ddcaa8c4440b965272b48a7.nq.gz
    ├── 080ca30079c068e9779357f3ee73ad6c854e726e.nq.gz
    ├── 0812c85b0ee44a2e5943b851e6b5c1b50476d747.nq.gz
    ├── 0815eadf91844c3a3027d72919abbd4957eeda46.nq.gz
    ├── 0877eb10be72afb803a47d4262edef2a27175a42.nq.gz
    ├── 089432ac9cbc59bc94746824a4788141d84ad29a.nq.gz
    ├── 0898a0fefaa892d7159312ae5c60579ad2570f52.nq.gz
    ├── 08a0364c82f165af8cc37dfce4b4ba52bc694ec7.nq.gz
    ├── 08a27a0c3db8f36f18edf519dff968e47ec5e3f7.nq.gz
    ├── 08cb6e952ac274f06075788b681681a09be570f2.nq.gz
    ├── 08e708884d03fe5acbc0f2d853d6d70056120f1a.nq.gz
    ├── 0906910a043d5c5546580af922d1485cd8552317.nq.gz
    ├── 090db9d095fd202715e3599682199a9e8c6d7772.nq.gz
    ├── 09121143b22d3d4752bc5af640397a90bb35fc2e.nq.gz
    ├── 09158c3e7b50721ec75bb0891711c6ecdf7522f1.nq.gz
    ├── 0916a8befd4bf8de0948dce478560390046138f0.nq.gz
    ├── 09191ed24bed550cd911390821da6bc46e3f1d5f.nq.gz
    ├── 094c54b914f86c95aa9e37e556bb2561c3291985.nq.gz
    ├── 0959e60dd3969e1651dcfbae7b88be989e24b410.nq.gz
    ├── 097e4b79968c1fac3c722d8b4939b46bc407bb84.nq.gz
    ├── 0981f103ecd0cb0573ed2c6207afb36770d89e3f.nq.gz
    ├── 0982d973b5e4651682f1f1adc7246082376d0c57.nq.gz
    ├── 0997fcec9254b076646ae8fa6a783174c8dfd3c2.nq.gz
    ├── 099c75803f1dfd66ccc0adf39bfc653cdbb3d268.nq.gz
    ├── 09c43ec08f6c4891da9cb58e1d93c3838a3d0b11.nq.gz
    ├── 09d33c77d0afb5ccf8a76af8f5316bed9d292c6b.nq.gz
    ├── 09d5fa8448a09480f02007fd4c265563bf90bb1d.nq.gz
    ├── 09f55affc474be6ae0e1ab9bbb4e9b660ca79c59.nq.gz
    ├── 09fa631bf248b6f58d638eb7b7f03593c4b38565.nq.gz
    ├── 09ff12b4d7d6460ff67d658e30353a4ed826a48a.nq.gz
    ├── 09ff7c212624f34cc6688f2c141f63a0fad811a7.nq.gz
    ├── 0a01f03f0a6722e90521cdc6ef1f252f21ba261c.nq.gz
    ├── 0a23c5c62e61e40af70f066185dc667cb3f02b44.nq.gz
    ├── 0a3c7457bdfd9c4b2db04cb55e3cbecf5176a5df.nq.gz
    ├── 0a45c4671f00d8d40535562d863eb0cd1b6addc6.nq.gz
    ├── 0a467a9dc1d7baa11a9194e63828851ce9c6b2f1.nq.gz
    ├── 0a52651d0815143a558cea7d98f1b63d5fc1a15a.nq.gz
    ├── 0a5d45800dd5eea8c9026bd309cda0025c27d37d.nq.gz
    ├── 0a5d8b6447a1951ae19c36ad661db2f6b41c1ee0.nq.gz
    ├── 0a8463540327b7352c892658557aaec87d743ca9.nq.gz
    ├── 0a87c6895d7e72136b134f0dfda84beb1c58c618.nq.gz
    ├── 0aa18786179ef04d794f42857aa405a9da4a7d7b.nq.gz
    ├── 0ab31fb16fd3a336d38cf61d950eb6026ed8e304.nq.gz
    ├── 0ac4c7b0e358be3d3ca9544396dcb82707bc7b9c.nq.gz
    └── 0ad02d5dfc3a95205525feb0c692437c7085e091.nq.gz

8 directories, 200 files
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

## Source repository

[boto/botocore](https://github.com/boto/botocore)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
