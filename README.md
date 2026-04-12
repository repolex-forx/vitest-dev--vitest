# Repolex Knowledge Graph of vitest-dev/vitest

RDF knowledge graph data for [vitest-dev/vitest](https://github.com/vitest-dev/vitest), parsed by [repolex](https://repolex.ai).

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
lexq download vitest-dev/vitest
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 07bc56a7a8b0ca7453af71193429c2745355dc6d
│   │   │   └── chunk-001.nq.gz
│   │   ├── 0c2c01361a95dd26d0d7fd7bc38bcca8dbc6e5d2
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 11f207fc60ccf6071597d5540a475585a8218c02
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 1c4506978b4431b0aa5ef26805f6dd543ec37213
│   │   │   └── chunk-001.nq.gz
│   │   ├── 1d9e3b3315024e3443a5a72fa8387508f4223528
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 1f2d318493363855b66a22caaf7c1c10579029d5
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 1f5d9d2ccfd0fb23b270e39992eed0a7aaa3f4d7
│   │   │   └── chunk-001.nq.gz
│   │   ├── 23c10e44b0beea92f88a62d56e047c0cd8e59c03
│   │   │   └── chunk-001.nq.gz
│   │   ├── 259a3d1b563ecafa51ced4641218545dab635be7
│   │   │   └── chunk-001.nq.gz
│   │   ├── 260d0bfb718fb0ba8614db7630fdf9aa2c7c9a8d
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 2dc0d62eaf08d8acb1f5042fdb8ac5b4a19fdc73
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 2e7b2b8b98dafc047a3bf2fc0422076ca5e346fa
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3cb2c857057815274ed3b2d06fae8ad925c033f0
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3e4b6b762ed3c58de8381910db006833eca67c57
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4150b913171bda3971a4a4c47c633c26d0c6ae45
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 46bfd0983d3ed5362592e0e94af4173164440ffe
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4783137cd8d766cf998bdf2d638890eaa51e08d9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4a28faa67783db5de87194d39a1b3f643bc38287
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4d3e3c61b9b237447699deab9aca0eb9d6039978
│   │   │   └── chunk-001.nq.gz
│   │   ├── 512ac7f8d6f3ccb242dc14972f1bcda93abfeed2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 579093192925598809884211c9dd437a1d648dab
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5aa84d56a609422b09a39b231b6c15e4d68cf3fb
│   │   │   └── chunk-001.nq.gz
│   │   ├── 62fab2443132a62327cbb937573f29cfc7a9820c
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6fc78903fc3b68e74793a62d160bcc979567b979
│   │   │   └── chunk-001.nq.gz
│   │   ├── 73b54ce2859d34f3847de465efb3f6affda0f8c1
│   │   │   └── chunk-001.nq.gz
│   │   ├── 79672d7e1586981f04dce7619cbd8c3a31eff284
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 79bcd1aa02151fe0a1761403de20077dfe3537b8
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7f03103928b6ee2c322bc86112b527ed40d7571d
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   ├── 9b75ec5f2fa46daaaa649493eb7f643a1cc9f51a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 9ca74cfb2060d8bc1c7a319ba3cba1578517adb0
│   │   │   └── chunk-001.nq.gz
│   │   ├── a0cdc959f9eb081039d80151086e3eb99721dbef
│   │   │   └── chunk-001.nq.gz
│   │   ├── a9006b3b8791a143b851156a04a27914cd851669
│   │   │   └── chunk-001.nq.gz
│   │   ├── b0f06dec9988e30866a32725511c1d32e2a0c48f
│   │   │   └── chunk-001.nq.gz
│   │   ├── b46d7444cc3a14296c5a4db67232226dc094f35f
│   │   │   └── chunk-001.nq.gz
│   │   ├── c3befb049fb4550d1b421d8e5990c6945e906a04
│   │   │   └── chunk-001.nq.gz
│   │   ├── ca1766f45ca178f6f79248452d131581c1debd78
│   │   │   └── chunk-001.nq.gz
│   │   ├── d06013f2e1f7ebbebfbad32058fb70d51cbc09a7
│   │   │   └── chunk-001.nq.gz
│   │   ├── d19ff43f2a61f7381cbf60c37edc65c2831b77e6
│   │   │   └── chunk-001.nq.gz
│   │   ├── d677c0ba21905252aea2ff7559e990f486a4d95b
│   │   │   └── chunk-001.nq.gz
│   │   ├── da7ce1712fd4d0e4e807ec01ce755581e6892d5b
│   │   │   └── chunk-001.nq.gz
│   │   ├── dd54e944ec0d7b2730933341f3b940e92b186fb6
│   │   │   └── chunk-001.nq.gz
│   │   ├── e24e56b82ffc4ce600c8ac4005d2a53e671c1eb3
│   │   │   └── chunk-001.nq.gz
│   │   ├── e8289280b6ad130d3e593f00982c5ebcdc02622b
│   │   │   └── chunk-001.nq.gz
│   │   ├── eb1abf08573032a532015b999ad3501c5e89e3bb
│   │   │   └── chunk-001.nq.gz
│   │   ├── ed9fc71076f94f23320922f115e37bc9a84b6dbb
│   │   │   └── chunk-001.nq.gz
│   │   └── fc6f482f4c54bf6a766a0ff502b9843994af5bf5
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   └── 79bcd1aa02151fe0a1761403de20077dfe3537b8.nq.gz
│   └── repolex
│       └── 79bcd1aa02151fe0a1761403de20077dfe3537b8
│           └── chunk-001.nq.gz
└── blob
    ├── 00101c8d1a0d1f1c7d62719057236229833c7348.nq.gz
    ├── 0019fc931dee2b3e7ef92e5756bdf9170a9a4905.nq.gz
    ├── 0023c778baca209ec037449d52065569719fb8a1.nq.gz
    ├── 002bb7bc606394495fbcb40e16a0f92bf4a4f35e.nq.gz
    ├── 0036634657d851c6febd74a704d65f51c67a1ecb.nq.gz
    ├── 00372a6cd23c6c24d1d304aeddc8e8c37bbcae47.nq.gz
    ├── 004e6a8ea87ecc36bdae8acb0a5fc4eec349cc1e.nq.gz
    ├── 004efbe69c99a4bc7609669a76df04279dc586cf.nq.gz
    ├── 00569c5968c05b86ae877c8b75d227abd35d8d6b.nq.gz
    ├── 0057b5a881568a330479a01d03d0a83a20dbb30d.nq.gz
    ├── 00589e6d4f4a4e6188da65bca586e86f9b5d5e92.nq.gz
    ├── 006380088ce5dfe8cc83f8d7310a04f7f64e12e4.nq.gz
    ├── 008126bb09558b7cdd6dfcc1ab83ea54f262ba7b.nq.gz
    ├── 008b584bf6e4430c1b87b20102e0bde530d584e7.nq.gz
    ├── 009d6fe6b4bf19809e7f4aef14de2e67bd9cca17.nq.gz
    ├── 00bdf498a48115a691b5014f97a452bbdf9bba9d.nq.gz
    ├── 00be3df7a415a230a96da338a0bf9e74b8be0769.nq.gz
    ├── 00c0d56f9f9789f4126f60b204c05a77e2061526.nq.gz
    ├── 00c8e99d0917a4b619ab80a93c7a05b3e8de9b9d.nq.gz
    ├── 00cae7d6207ee38327188e9e3369fea84a2d4ac5.nq.gz
    ├── 00d55ab713fa5fd649d0a12b263a708c317346a3.nq.gz
    ├── 00da160aaacadf629c1f68193ac628613aad578b.nq.gz
    ├── 00db3293cf1ce0720e59a4dffe68e59838930c5a.nq.gz
    ├── 01164d4cc9068f205193cb419f87ed30e50fb687.nq.gz
    ├── 012084d8417ce312a63f4f2bddf9bcb7131135af.nq.gz
    ├── 01271ef91866134bbf85ef4fb653806f6806a2cf.nq.gz
    ├── 01295139ff0b6adc6e37957452bb4d0bd67a2a28.nq.gz
    ├── 01323c1ed4f6f042160b40a4bc925bea820db48e.nq.gz
    ├── 013c92a3b09ea18a9cbd71dd29523794574d6a38.nq.gz
    ├── 013f3a33b1c6f0f65bf0ba95c97694f28ecaeb12.nq.gz
    ├── 014d3e750bc48e3415914cb922e72f205447008c.nq.gz
    ├── 0152418f303417a50313b96924d444c016cee132.nq.gz
    ├── 0152d02550f4ca30fefc1d4c17b88ce5c6091924.nq.gz
    ├── 016fde0031a78d8ef565c6e7aa50d76fc7e54285.nq.gz
    ├── 017bac54f691eae1ef2b2c965a1010f37e4251a4.nq.gz
    ├── 017bd6f32010b96547343fed7e6a42c39c157760.nq.gz
    ├── 017d538938335833811a9557bfe47532adc20737.nq.gz
    ├── 01950e4f87c3228ac75548c7bd99c0e9069a1600.nq.gz
    ├── 019e3e080b593b2333256509ebea1c1be0bfd210.nq.gz
    ├── 01a145fd7dd16a27ce92513d97af86440a0efd16.nq.gz
    ├── 01aaa33ac60d7d24bfe761181f7aa348251d72cb.nq.gz
    ├── 01b098a7ec60cd79a0e837c9d72e29f361e3f871.nq.gz
    ├── 01bca471a9d27618e5d566798d6a5f1afc581995.nq.gz
    ├── 01fb70dba6d7c23ee8eaa946355b8783732caa73.nq.gz
    ├── 0200bd4957554ecbf360b02d48c502b1ebf19ecd.nq.gz
    ├── 020859f8ff9c4ca435697486cefdcc8088767684.nq.gz
    ├── 0211bfd17acb9279fbc4ce906977011ece9f0e7a.nq.gz
    ├── 0211f5068ff9dd9ee3f8f112c31492e5c0f096ad.nq.gz
    ├── 021455fd1e0a9ee1be79dbf3cdd18b786cf0ea10.nq.gz
    ├── 0215cf1df90bf36dde8c3dccdda26c88ccb56268.nq.gz
    ├── 021fe52d1b2af04319a560dea8cfecd346d7e406.nq.gz
    ├── 022835826b5af5788dab6ac7a44c64eddf2c2f52.nq.gz
    ├── 022d1226edbe18abcc9cb87650447f16f06a7200.nq.gz
    ├── 0240d11a2636fe234852bb549719184c359c7de8.nq.gz
    ├── 0245f2cdf1122162cdf522de52cd110cc518341f.nq.gz
    ├── 02498f366da8b69df5d940d96cfb21b7a2c3a1e1.nq.gz
    ├── 02553ef8fc0d58e5729e4c1e7a594db6d33bc70c.nq.gz
    ├── 025641b7eda95761789f683d607b897ee6013026.nq.gz
    ├── 025f1c001c0164f4a111086265e5473341ad6d1c.nq.gz
    ├── 0268eca1373c38082493e05a0c85e31a9b56fb27.nq.gz
    ├── 026939e469dc9aa6130e4fb9997751ba2b1203a2.nq.gz
    ├── 0269c8f771fd2859825a4088140b337e4d752083.nq.gz
    ├── 0269f09544793950684f2ad2faba1129aefb31f7.nq.gz
    ├── 026ab1cc4e0531b9fb916f11703033bef0727471.nq.gz
    ├── 0276e0d3095caf94b9a96096d71ba88c88194b90.nq.gz
    ├── 02784f3a1c6361688ded0f5adf5d08d0182fba0b.nq.gz
    ├── 0285a44389cfc83cda771d8b7b204b3bb5db440d.nq.gz
    ├── 028d6c4e14a92508a2a61b1827c1534a29f252f1.nq.gz
    ├── 029d706edd569a65e2868a2f6fd1a505772c55ab.nq.gz
    ├── 029d7c246f436718d46d81e62b54e1baecf6effd.nq.gz
    ├── 02dd4714b90340442ab2b2b72a704a99c9b5e4b8.nq.gz
    ├── 02e2669c7ccc37a33cdaf38296ce5887e7a928e3.nq.gz
    ├── 02e8822291f5921eb9eccbcb685e6ddf3e56b7af.nq.gz
    ├── 02ec2a0ce242d02f22bfacd918aa3588e5f36979.nq.gz
    ├── 02fac6a55a985e70bce4473ee5c1d8e1f2145813.nq.gz
    ├── 03007895835e9841b879a44af77304bed63122c6.nq.gz
    ├── 03142e4e71aef682118f31db21e86a869c2aae5a.nq.gz
    ├── 032556f6d93708b17045052fd9710198cd702b42.nq.gz
    ├── 0325fa675032401a2449c243a0724e18e4b36c12.nq.gz
    ├── 034b6ba06b7173596c011a0c63038a3c0cd8863a.nq.gz
    ├── 034c5c15283e777a9bb8ccd5363ed3463abd4b67.nq.gz
    ├── 035619c638421b20ef2e95fe49d901c4e078b0bc.nq.gz
    ├── 0360ff9a3ab4bd689276e8a885858f465089e03f.nq.gz
    ├── 036373aff09ea3ca5ad75cefbcd9acfa95865009.nq.gz
    ├── 037210cd163206139ec1399d51ceb28aa01d7338.nq.gz
    ├── 0376ac57b9dae901b37be07938546d404470c00e.nq.gz
    ├── 038c2202159457b3a3cbf4851c1011c4b99c9f88.nq.gz
    ├── 0394e0c9c30593bdf4f38c927fb9e69aaba030c7.nq.gz
    ├── 039bf7c69a3d7538de620643122ed7b04b650caf.nq.gz
    ├── 039f9a9e1099e09b14b1148b7d606e20afb2115e.nq.gz
    ├── 03b016d532ce5ac27c01fd331fb3852795d8e6f3.nq.gz
    ├── 03b7f8d2e93b4f15c4d20b13e8d79f330c612d12.nq.gz
    ├── 03bd82fa6c6cc99c73397829ec45ef3648bce46b.nq.gz
    ├── 03d0fe4c78ac5dcfe1750ddd064098f42fc35ce7.nq.gz
    ├── 03dab89bf490cf7746e48f428c115aadd4e4bcd3.nq.gz
    ├── 03f8b7ac706000af3353e6da06deba7866f841ea.nq.gz
    ├── 04162d6205f0170972abf47efab9337bf5e86f27.nq.gz
    ├── 042013f62c8a79d57c106bdd2d79c3ba9d4c2ba4.nq.gz
    ├── 042663203c97c252ee1172903ecda762b8f7cf6d.nq.gz
    ├── 04651f1711627ad4310c1fbae90d952066f0f765.nq.gz
    ├── 0477c34a9a47d4c8c7601a9fcf91015b7ca2e3db.nq.gz
    ├── 0485164bd592dbf23ec1c879a16501cd32bc7670.nq.gz
    ├── 0495ca4a1c48eb35ef62435c9e5ead8c47fddf1c.nq.gz
    ├── 04a72c0a600ed2696aad2e0be795b8d903c66f78.nq.gz
    ├── 04ad7c23ea19e847d7336f2f8d7cd6855ca8bc9d.nq.gz
    ├── 04ae02b839b8b5a48e035ae81bf93745cffcf603.nq.gz
    ├── 04b712c13cd2821e8199f9acbc229e3d9d2ff91a.nq.gz
    ├── 04baa15963d5cc75d5d8944e65ab8b64448c3d75.nq.gz
    ├── 04be4c6ac8d423787d12ca3c16b24a4e29453858.nq.gz
    ├── 04e66fb93e24f60588c2607b6c602adb37e59fa7.nq.gz
    ├── 04f0440ccc77431f687f029b175aad483a349157.nq.gz
    ├── 04f82b67a4a5b5f8ad272ad02c7d24d9d4278046.nq.gz
    ├── 051d394d3a957a4d692f46aa6a02701b8512d309.nq.gz
    ├── 05261a02dc91337e38d1f6374e9eadc2267a8a07.nq.gz
    ├── 0530f28793e9640fb7f5f3c5f5d85fe9d94a08bb.nq.gz
    ├── 0544676b9d91585dca35de861252f64a761511f2.nq.gz
    ├── 0559aa01ac9947772e4165727ddefe6129b3c729.nq.gz
    ├── 056aceb85a506e52392679ac7d5a2e2d9c4c0f7b.nq.gz
    ├── 056e4fc8feaa89b79582e306cc8c3eedf80a2b5b.nq.gz
    ├── 0572c73653adad268fa68cccc82da6a2fa7dbda7.nq.gz
    ├── 057555d616313f9089a1f2b76f73ff1bc699211c.nq.gz
    ├── 0590db3c1e153d871494f18cb192745ffc6b91d5.nq.gz
    ├── 05922eee80be1017b97c515421b9d53c890d3578.nq.gz
    ├── 059c23eb2ece6ba7de45d37893685b72e28972ed.nq.gz
    ├── 05ad48dda3c9e9e70a64b206e63c77e993d77d55.nq.gz
    ├── 05b1205b1cca6b70dcddf722e0d9a9f7085485ca.nq.gz
    ├── 05bda44e0262d4da1033eb0d10a5f07d23328bca.nq.gz
    ├── 05dac499e00a7598fbb6435b4c40d1e37a0d6146.nq.gz
    ├── 05e2b7f5cef8e308853d7c4ea3f15d43244a795e.nq.gz
    ├── 05e6a94a2c44305a1dd770209d199417dc69ceb6.nq.gz
    ├── 05e9f82322aa38c5341dd06ae04081e90cbb99a0.nq.gz
    ├── 05f0476808b62b4fb0bc8a3db00245005d295017.nq.gz
    ├── 05f746724952a881caee442987b2fd2814fbdffb.nq.gz
    ├── 05fca9acf7d71e068f7203f992aaa77d89a81a4c.nq.gz
    ├── 05fef48145a4443399d4ee3fccc57f85dd9aec5a.nq.gz
    ├── 0603417436c2c1b6fb4a8b232bfa597f78c132df.nq.gz
    ├── 06047664e37809f466f10c4b38a28fb8b2ff2c87.nq.gz
    ├── 0606045c06725e3e45ed9cd7d4b56a26e8daa5b9.nq.gz
    ├── 06082ebda97a011c0ea044e3eb7ef4129c28a85d.nq.gz
    ├── 060c4dc4ef832e92adf4c13a5e98970a878cd2a9.nq.gz
    ├── 060da4dbbac7d8df1a791e1d6d34d8f80f000a5a.nq.gz
    └── 061bc7b82eb69335495ab0c608a626a0c1700866.nq.gz

53 directories, 200 files
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

[vitest-dev/vitest](https://github.com/vitest-dev/vitest)

---
*Parsed on 2026-04-12 by [repolex](https://repolex.ai)*
