# Repolex Knowledge Graph of daviddrysdale/python-phonenumbers

RDF knowledge graph data for [daviddrysdale/python-phonenumbers](https://github.com/daviddrysdale/python-phonenumbers), parsed by [repolex](https://repolex.ai).

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
rlex download daviddrysdale/python-phonenumbers
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e738f6f872ee9b053770c2784edc1b46d2903cc6
│   │       ├── chunk-001.nq.gz
│   │       ├── chunk-002.nq.gz
│   │       ├── chunk-003.nq.gz
│   │       ├── chunk-004.nq.gz
│   │       ├── chunk-005.nq.gz
│   │       └── chunk-006.nq.gz
│   └── repolex
│       └── e738f6f872ee9b053770c2784edc1b46d2903cc6
│           └── chunk-001.nq.gz
└── blob
    ├── 00562e73e8ca2f5a05fa19dfde0e43d9af47450e.nq.gz
    ├── 00f366db97387fb56a9ad4cc8ef56f25269a274d.nq.gz
    ├── 0148db346881bc90589fb83f75cda463d4536ae2.nq.gz
    ├── 01d9e5533165d3d87ae44d66877b46ac49357b64.nq.gz
    ├── 025a93351a8d4b7cb2baf3460a65da25835601e4.nq.gz
    ├── 035f4f123e183fe5b00c29bdab594af1d4eb576c.nq.gz
    ├── 03ae2bb78bfd540a9db7ddc76c0a5a0a95546847.nq.gz
    ├── 046001112b1b9be0010c02c728ba1a04fe5d179d.nq.gz
    ├── 059f71ac8fd9e2cbecc3a4999b51db3f831e4d37.nq.gz
    ├── 05fa16c126e48b2312c3505bc016c41fa569e377.nq.gz
    ├── 0674007a136f4776fe07672a4b2aaecb5fe423cd.nq.gz
    ├── 07514595ddcec45be5811fac8fd88c77f2d05c3e.nq.gz
    ├── 07829488d1fe135095d36b14b92048919678a0b6.nq.gz
    ├── 07c898aeeb4da506a428b9a3e3b84f9141254175.nq.gz
    ├── 0831d9a01a5433d6f66e92ace410f601fd3dc92d.nq.gz
    ├── 08470669a69b3ce3826e58a631f37710a62d0971.nq.gz
    ├── 08c360b491587fab652ffa8dec821c89f611e06e.nq.gz
    ├── 09088ba457bd89664aa9d757daa5fe34caadae91.nq.gz
    ├── 0a0d3ab84b3ecb21816630a4fa19db6f9daaaef2.nq.gz
    ├── 0a9cdc926fcdd1fda848b51c46910569a93c3bc4.nq.gz
    ├── 0acd0fee8edcf73f7d9a28a8382b0fc78b119433.nq.gz
    ├── 0aebe4acb24901be0a32035892f125192b370e81.nq.gz
    ├── 0b704f19d17d1a3731a34657be874da67cef40d0.nq.gz
    ├── 0c387b02eef01f111cee5e31d3ca6fb30af34ce7.nq.gz
    ├── 0c7232435c5dee6b88ec95cd078f06255e862e38.nq.gz
    ├── 0ca9e3989ef1e2f99e552102d33e5e14884fe67e.nq.gz
    ├── 0cb3b1dea82f18dbee6f939aaabf92f4ec8d81a3.nq.gz
    ├── 0da8b81ab590a08244ef994bf92144749f9539c6.nq.gz
    ├── 0ddf83d1937dc6827cce6a06d1d0fb4fd3a69c3c.nq.gz
    ├── 0e0c86c77ef6a3957267adb40d8826f8d42f7b17.nq.gz
    ├── 0e1c9d73e327d07e055591df2fe814351b2d4dbe.nq.gz
    ├── 0e47cb296a7269b3940bda3f710b111843d026af.nq.gz
    ├── 0e87427aa77cec5672097182f6dd4d49a476c780.nq.gz
    ├── 0e8aa9d008c5bf24701ddafa378c892b3a03d323.nq.gz
    ├── 0f1ffa1f5d91ebbe4fed3185f1b1b359dfe9d318.nq.gz
    ├── 0f64dd656ccae1f09a1ebc2e22fce963ec0e57ed.nq.gz
    ├── 0f941dc4a226ef7e6535845f8b39f7b451a8881c.nq.gz
    ├── 0fce1c8b5245431d7a449ccf4b1d2c74f7c71b25.nq.gz
    ├── 108d6636d322d2c4ee4c4d72ab9195c7e0baeda3.nq.gz
    ├── 109786c8ff8ea35d49d4d5388041ff0c8c4b7f9d.nq.gz
    ├── 11000c4b5c8fe8392e8be684f6a5f85c2ef247ed.nq.gz
    ├── 11391e54267fedf88ee0f159322310222b7af3f1.nq.gz
    ├── 117c1e0e6f400e9ef89139e4b4388dbf53d936b7.nq.gz
    ├── 11cb0373e4384baaf7fdf3a203e91456ac09c59b.nq.gz
    ├── 11d8cf5ac7fdd4c33d477760e514a07cc9588f6d.nq.gz
    ├── 11e18bfdedc5356283dfaa335258d58a2338a78a.nq.gz
    ├── 11e6f542497f56b6b77905db30fbddf09fcaeb97.nq.gz
    ├── 127444adfe12906c3b94083d0f4dda57114148fe.nq.gz
    ├── 13851b238fb6bb3be0b21d93e178ebcababf6e25.nq.gz
    ├── 14349cd94b58ae1a0d178ffc9a99571264c8a571.nq.gz
    ├── 1595adc6c21bf4cb35bc79e3f32c67aa7c42a1b3.nq.gz
    ├── 15e9a5dfab8f193fbac017cbec7aaa618baec0b0.nq.gz
    ├── 163c383d21b7067307065e1d69d8bc59cd199714.nq.gz
    ├── 16a91b5c7e74ec20c84f748df0bc608225b4cf3b.nq.gz
    ├── 16af364ea4005483f8aedcc380e9e86746fbbe51.nq.gz
    ├── 16f8b5dbfd57db515b80f17c723b3af2979bc390.nq.gz
    ├── 180f19bb732faab0297bc61633c27305691af255.nq.gz
    ├── 1826dd90c7aaac316bd063fa680a444cc9b863d2.nq.gz
    ├── 187f1d2928c720c97e40dccfef1aec47f78deca8.nq.gz
    ├── 18acde524a7726f5a9192d216b8fa163cb2de0c0.nq.gz
    ├── 198e609c11454148ac1391044a91c1d60c33ac82.nq.gz
    ├── 19c8775ccbea392561204fb9d2663fa6561660d8.nq.gz
    ├── 1ae3ab9b03133b52e8e874dc4ef2c83e84936365.nq.gz
    ├── 1b58ed65b5dc2a02792cd08cc04bc3e946c57750.nq.gz
    ├── 1bb0ae1aafd6b8122d0c2f09c7c0950b0bd13dce.nq.gz
    ├── 1c626960c56d40796bad5ced0f839efe91119389.nq.gz
    ├── 1cea39965c976a97278c54df4a9c194acc8c9b54.nq.gz
    ├── 1d25bda0480c1db406373a217bcd454dbd985506.nq.gz
    ├── 1d29dac322b0211b537d3415db983f34f23d2ecf.nq.gz
    ├── 1f176c8150469c4be249706a4e330a4923da8134.nq.gz
    ├── 1f3f74ab79c689d81dbb50610d2b13c6333ca1b1.nq.gz
    ├── 1f5d84518614f0ec449080a9c7bf66dc315acfa2.nq.gz
    ├── 1f8ec1c44409cc0924e72efb955cda8f58fe7b19.nq.gz
    ├── 1fbaade40b44829fb9442534ef02ba897a300dcc.nq.gz
    ├── 1fc46bc269f239be6f19fc2b3ef27ef6b646d4ed.nq.gz
    ├── 20a5fb9c2e5b149a2f76183e0790e39c316feb47.nq.gz
    ├── 211a844ad3923e82fc9cd1ff610f1c2765b81d5c.nq.gz
    ├── 228bc2adf4f140ff4d2e825ff243e1a55fad2aa4.nq.gz
    ├── 236555b580b94251c3143af65504da3e6d4fe599.nq.gz
    ├── 2383f985a415bb2535b51459b7de4cc06f136326.nq.gz
    ├── 23d14dcb6d157a1b4d8b4cccd9d841d731b23284.nq.gz
    ├── 240607f30f189ffb397d95862c10f7274665b5ed.nq.gz
    ├── 2484e17608b2ff1c9d80b79123ae9f5a1ba67251.nq.gz
    ├── 24d1f34dd6b949cc3034d612a3abf6470f5a98fa.nq.gz
    ├── 25241c7e27686087ee5c59729aa4cb14e3cd03b4.nq.gz
    ├── 258b21d697e77eb153d2439603530ed032f4d407.nq.gz
    ├── 25ac4e444ad40bcfc613268ef81b16d72fa8cd03.nq.gz
    ├── 25e53b8b4245b5d31b805494dd2d3db854e42022.nq.gz
    ├── 260d707b59ad2273a3767a959fc74b1af35b5cde.nq.gz
    ├── 26103202760dec18e6a8178905a0f8002f5a8b49.nq.gz
    ├── 26271accb869715eb29f68e0b40de909fffb346a.nq.gz
    ├── 264a1187b6193e04f93c49da5dc169383ca03bc8.nq.gz
    ├── 269d2023d1dfd57ca0f25229122124cf60ca9cab.nq.gz
    ├── 2873e069cafd4ed1e9b27a841e74375c95a404ef.nq.gz
    ├── 28c0006f73c39899824af9035b8e7949298bdb82.nq.gz
    ├── 2967dcf88ec910de27c966fa776fb14460cf8cfa.nq.gz
    ├── 2973b02350bc8be2747573738a5429af9a0ce555.nq.gz
    ├── 29912eb9a38737913728604964d428138f8265df.nq.gz
    ├── 29939b50d04fe76e269a85ffa9299ffee21b2abc.nq.gz
    ├── 29f2ec08cdf22fbe0a4ffb95382dd19cf5f70070.nq.gz
    ├── 2a65c5e19704553c4714127b97ea4080b969bfea.nq.gz
    ├── 2abcbaead01c4357a1c517949ec6bb9bb11e21ee.nq.gz
    ├── 2b4019732b1feee3dae88530204e121e438e68d5.nq.gz
    ├── 2b7e6875bf4644399ef304283d4c20caa151645f.nq.gz
    ├── 2b8315b591c643979377d1c804f9ebca7f27460b.nq.gz
    ├── 2bdf3b79a1ff8b948b7a9640bcdc8fa69982dd2f.nq.gz
    ├── 2ce3e47a8d64ed585e033efa577aabb36a1e6f73.nq.gz
    ├── 2d18c31487fd5493961808106de0e7885a765951.nq.gz
    ├── 2d9e86b159bb31297a8b2d804a08ccba35c89371.nq.gz
    ├── 2db373ff29811b87df78850ecd76dfe093dede69.nq.gz
    ├── 2dcfea1ba709c34122f63fc3c0f3ecef3741fafd.nq.gz
    ├── 2e7a4ee6197ab898ad024a38215f2f73b5784b5a.nq.gz
    ├── 2eeb9ad35dc0d8450bdfad268753020131d28294.nq.gz
    ├── 2fba3f3ed5b561f4ac6c6a49f43455532086f1dc.nq.gz
    ├── 2fef736075ec3c1a93cd395cd249dc044926ab32.nq.gz
    ├── 304fef74b60aee354afd4ae443490d07dd8976cb.nq.gz
    ├── 30b5d9c54302e110c2f22ac363f3cc80071b2036.nq.gz
    ├── 31efb2f97ee8c20c77664cac71446fca95017199.nq.gz
    ├── 31ff1914af368bcd2a46101efcc053cadb06c6b0.nq.gz
    ├── 3202bd14540aab772c02615f6045d9f519c4aa9a.nq.gz
    ├── 32b29a740342b3232e8504284413d00be88e8d6c.nq.gz
    ├── 33468666f08cfc516f07090c05b66c6d4826786a.nq.gz
    ├── 3374855ed6e7e154db94c5e67c0937e05a9740f1.nq.gz
    ├── 337e921a4d715d716b62259e4ce856681df023f6.nq.gz
    ├── 3412e61d4eef55940ce234becfa3cbc142ababc5.nq.gz
    ├── 3435bf69515d7131e563534b1302215067cc9f12.nq.gz
    ├── 348b9dbc7352b9cb69e0f83538efba50eca8528e.nq.gz
    ├── 34976f7e639847e30c494744245aadce432fc24d.nq.gz
    ├── 34ac3e82ec02124eb8773f4696d7bea58313b231.nq.gz
    ├── 35e853464e15a174e4c5b99a1faa672ae68794ee.nq.gz
    ├── 35f09184f2953fe6c176b550b7269cb791f6e4a7.nq.gz
    ├── 376f3d44d82567aafe23157ffb00e88f55ada0d1.nq.gz
    ├── 38291cc2c9701ab7d9f5176b5460f9e3e5f7b1b8.nq.gz
    ├── 3924437e955faa388a588cb7067e28c9dbb348ae.nq.gz
    ├── 397fc8db6130b470a5d97c799fffddab6e0beee6.nq.gz
    ├── 3a023cd3b724236e0e5c7148be3b1b921bf73490.nq.gz
    ├── 3a50dbc35ac9feeb65a64fee969754e3bc36a971.nq.gz
    ├── 3b54b7e121126d99becd1ed1648cd3d30dc11a54.nq.gz
    ├── 3bf3bbc0202b386d03eb09b05eafcc84fd3ee8f8.nq.gz
    ├── 3bf980a1ac52b0dc66bc259dd0d90df2a2fba56c.nq.gz
    ├── 3cd45fd680655a3bf6d74b61a8320bd2be67cb86.nq.gz
    ├── 3cfbc6bd13a623f507bafe841d6a44b67dd6d220.nq.gz
    ├── 3d2e991388dc62cf03c93e508683875732b58f13.nq.gz
    ├── 3dd32dcf00f27b07ab3fd8c542be5f78e330bab8.nq.gz
    ├── 3e09b0ce9a95218b4fd84f402d28bfffeed00eaf.nq.gz
    ├── 3e2f48c76b762ac95d888ff313123bfafe6121df.nq.gz
    ├── 3e4bdb296c666ee87137e82f6db4a64daedcd457.nq.gz
    ├── 3e70a5194bccdb9aaad66996646297f34577fee9.nq.gz
    ├── 3f934ae98dbdb88a06553975c19bc3b3fa57115b.nq.gz
    ├── 3fbe16b7e61709eceefe23fb3490dcc7bb92339a.nq.gz
    ├── 400b284fe1e376bdd6daf794297699459a4d06d4.nq.gz
    ├── 40c4cbe4636d31a0e90d009b3440689f7387b06b.nq.gz
    ├── 41654809e8fc14c19aba7563f881d2528e4603b4.nq.gz
    ├── 434eb8e070e66fcbac73c80ec68475a7ab7f00bd.nq.gz
    ├── 437c407740a52da7d9cd296e783c11bcd08108cb.nq.gz
    ├── 446b23d8b8532ba5f005d33b9634dc6b53a731dd.nq.gz
    ├── 451a99e4cdde9f0885c23667ced18a758ec9400e.nq.gz
    ├── 452102638de0232879ceccc986baba441c740f6c.nq.gz
    ├── 452322fdcbca6c944240a9b3f9d1247e0ef5cd36.nq.gz
    ├── 452fc8c17ed911d49b80c79197bcdfab89b99e13.nq.gz
    ├── 457784d554c5e5e514490a5b323c2b724460c580.nq.gz
    ├── 47160dcb1991d820b59801c2caa38d217d5a7199.nq.gz
    ├── 471c21fbe653a101f27fe4ec297efb40047283ba.nq.gz
    ├── 4837aa0c868246de9e63eecff5d54d8964c1dd17.nq.gz
    ├── 48f5a566ff258a6604bbd759b1a560717689c6af.nq.gz
    ├── 493a12c86fadc066f618b27f2b6b63ec0b1c6f12.nq.gz
    ├── 497954f845ecfe7f1f6a124d6f4da9a068874f25.nq.gz
    ├── 49be751acdc55b1d5e47658d3d9e675cf555d276.nq.gz
    ├── 4a900cfad35110dc20202fec5fc5e4b363dfeef0.nq.gz
    ├── 4afda2fd73f4b873950aca18787b7c0357564a2d.nq.gz
    ├── 4bb21b8af816a707379a61d5a27e274a801f1066.nq.gz
    ├── 4ccbb3b9f0eba33f469a19253469842b8d1ff303.nq.gz
    ├── 4d0563f0fded7e998b6b8272b7e066f1a899bed5.nq.gz
    ├── 4d8278e70f66233a5908aca73db7761d242750c5.nq.gz
    ├── 4dec210c3ba8c6b61dc93b8e8255675263ba36ee.nq.gz
    ├── 4e1a40086090b4a44d0cb9b009efac6f03115eca.nq.gz
    ├── 4f65e16ce246f9de478262d564f5f99c76042da9.nq.gz
    ├── 5004d57fce56db1bc7247d51d6e9708ca19acdec.nq.gz
    ├── 506bf2d69abcdda08869c265f10a3b9e5d3186f1.nq.gz
    ├── 50c8d8f9fa5275b21ac31b0cf739a94df4b87dfa.nq.gz
    ├── 517a5939d995b4307c73cc3fe6af501d7642eaba.nq.gz
    ├── 538e68665dc53958fd2646fb31ced6f16dddaf36.nq.gz
    ├── 5442d9a5faabdc458f0c5674897985c2e2a48ab3.nq.gz
    ├── 55b042c3d2bccdf69798eaeab6f55031b9d3496b.nq.gz
    ├── 55f2ec808eebac1af66a8eb33d7b200ec8c56ca2.nq.gz
    ├── 55fd61844a10d88ef15ab72719105f4f13f35648.nq.gz
    ├── 562536070dc46b00928fed34ff56853b39caa714.nq.gz
    ├── 562df6f85f2ddbc92ba61f1cab283e1bf210f7fa.nq.gz
    ├── 577d7e24060947923e50e4fd52bac0571fdc2878.nq.gz
    ├── 5803de8b35b6be2a40f8d12e37e927b15742063d.nq.gz
    ├── 5804d0b1e5abf97e4646d7bff6da2304834f5af1.nq.gz
    ├── 58ef237a65ecdb02dcf3b7771c6083574bcdf2d6.nq.gz
    └── 59073204b0aeb35fe6466a7ed55853ed83ec7144.nq.gz

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

[daviddrysdale/python-phonenumbers](https://github.com/daviddrysdale/python-phonenumbers)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
