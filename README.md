# Repolex Knowledge Graph of markedjs/marked

RDF knowledge graph data for [markedjs/marked](https://github.com/markedjs/marked), parsed by [repolex](https://repolex.ai).

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
lexq download markedjs/marked
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 28954e090f3814cff7c37de14352ddf2d9efebda
│   │   │   └── chunk-001.nq.gz
│   │   ├── 811ea59aca1a76a0add55f59b703b50fc5605195
│   │   │   └── chunk-001.nq.gz
│   │   └── e07037e943f75f3f941785af49d57d2f59780f71
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 811ea59aca1a76a0add55f59b703b50fc5605195.nq.gz
│   └── repolex
│       └── 811ea59aca1a76a0add55f59b703b50fc5605195
│           └── chunk-001.nq.gz
└── blob
    ├── 006b8eb801f18138c9c3fa5aa7ff8d2d2f56378c.nq.gz
    ├── 0077fbe3a88a44b4334678a99f6099629d62e0a9.nq.gz
    ├── 00969cb292c55a6cdaf834a33675f6be195c8512.nq.gz
    ├── 01502b3dcdc0568facb75ef4098361e9b5048e53.nq.gz
    ├── 01f9a733b6789260264c47b5220efca52a356ebe.nq.gz
    ├── 02309d215f45c7aff805f46b5beaf0a4ae84ef5d.nq.gz
    ├── 024cde92be18f889da71b82e20f6abc235dd39b3.nq.gz
    ├── 02660caffc37e8c068603e5da1083b8d123b7405.nq.gz
    ├── 0275511228bc7570be18921cf923cbc1ac633d5b.nq.gz
    ├── 0353927c2321d2922f2055de9b658018dc6236a7.nq.gz
    ├── 036fe479430e9252fa828d4d4949b9c32ad41421.nq.gz
    ├── 0421e75dad078f66a9ece07609ff6ef0b42931b5.nq.gz
    ├── 0704e280486a5e7839f195a146579d95680d69a5.nq.gz
    ├── 0972df8138c486da0691df1eb1d6c5f434d52101.nq.gz
    ├── 09c9b66bb3e89bf45a75ab8fecfbd96e8bdeb858.nq.gz
    ├── 0b164a91b2f17c626cb29604bcc849bdabb7dd98.nq.gz
    ├── 0be6ec1ac82e35c49e36eb925f518552f3c2148b.nq.gz
    ├── 0f4c5e8c1dee91ee326cbe76538fe7116e0de76c.nq.gz
    ├── 0fb46559f7949f64d47316542c2ea5777aa935d0.nq.gz
    ├── 0ff031fa663198bf9d925fb36a72d6de31fddcc8.nq.gz
    ├── 106dfeaf3f596c5e2bb3716ec8767c43ce399932.nq.gz
    ├── 109603266e8d6d0afe5b14bad9eec38c873a6bbd.nq.gz
    ├── 10ab1606e5d814d142eb94540e32916ec784afcf.nq.gz
    ├── 12b68f771615914102c951890b444aca3f9f148d.nq.gz
    ├── 13300a7a1bdc30ddd326d6eaeccc2121b2366659.nq.gz
    ├── 14059affdef3fc146872541dd47c2560fcdb592c.nq.gz
    ├── 14130980359ca84fc8d85faef05dd651c411aa7b.nq.gz
    ├── 14aa2dc272d0a056c71049fb4ff80d54d36f9adb.nq.gz
    ├── 15f724f96238b123cf4cc373b7ad63003293334c.nq.gz
    ├── 165ddd3451779b837c4a7c50bc0468b78fcc81ab.nq.gz
    ├── 1689e98aa1c2e9d5cfba0951636fe681837a0f53.nq.gz
    ├── 16d5f2de916b375472f1fa2067f082739d53905d.nq.gz
    ├── 187bcfd745a18946eb248ef8988eda61f6b9d473.nq.gz
    ├── 18826bf7a8ae9c7677907dae2a6b6cf438fd3c78.nq.gz
    ├── 195b87b6cc93bc0c92e7affed3c2df3e2bfd438b.nq.gz
    ├── 19e938294ac28192cbb803cb26b36526007f5a62.nq.gz
    ├── 1c94878a7b7c6aaa6f1ff6962b4552a93a70dd22.nq.gz
    ├── 1ca89d7078b26a1cfc885f224134fc9b6ff623ee.nq.gz
    ├── 1cc50d5ce9d2f38c2419f465d2e65d8a705877a3.nq.gz
    ├── 1cfddde101b6828b0ec7b5d1d76235febe1dd80f.nq.gz
    ├── 1d2afe07aa3e9b065bcacfcaa271dedf9882486b.nq.gz
    ├── 1dc692beca1127bbf87b12811b9e5918df21c785.nq.gz
    ├── 215e30880051618b33d0d30124f0a489ed3b309c.nq.gz
    ├── 2443a64a851ddfdcbc22af54a960116765270747.nq.gz
    ├── 248d88318de88fbab4ab20a52e52424ac26debff.nq.gz
    ├── 25d7f4fc526e658c1085dccaa956d4092cef6d7d.nq.gz
    ├── 26f60437df7264e48053fa45fdaecbfe2b7ea75b.nq.gz
    ├── 2792744c37e0cf024a8e16dcdcc7d55f5bcc04b1.nq.gz
    ├── 28314f367dbee6f8bb061baa1581c0dac20f65a6.nq.gz
    ├── 28f334908a86a675220d429d6f1c61b8f1d53fb8.nq.gz
    ├── 2ac021faca49de1959b4613273f25abd83c7823e.nq.gz
    ├── 2b728f4430841407b328cecd4dbfbb4980361a50.nq.gz
    ├── 2ce31e60baf917b712c3ae8d67ac5ee675c4a0d8.nq.gz
    ├── 2ea9a26285246906f6747c42b92b0d0161987b4d.nq.gz
    ├── 3066d0238af2adeee479cac1c03f846180217267.nq.gz
    ├── 3253491410d06ff1248b70d8f61e0c3133759ca5.nq.gz
    ├── 332298a692521c684a4e2bc1ed2dcc4af5819709.nq.gz
    ├── 33bd25400b0dfbae044797e84f3afe0d6d41e0bf.nq.gz
    ├── 33e6a55555b3fc5dc7261ac4e9cd7fe088778dfe.nq.gz
    ├── 35c058691d13742f4b9ba01c714b65a88980183c.nq.gz
    ├── 38c1107d4d6ac24061198511c32d950b53990881.nq.gz
    ├── 395b42b5d8377ae0f6c881074c2de0fa6c314ac2.nq.gz
    ├── 396ad33943bebccc617afca9c18b47ddf57421b5.nq.gz
    ├── 39ec03ccbdae358a4eeace9fc0f653c0b73ac23e.nq.gz
    ├── 3a8b2be7e851288f3ac304d43065c1222bb6ad66.nq.gz
    ├── 3d143d1fb2f21799851cacae74cccf4a9afe7bc6.nq.gz
    ├── 3dda53e95c53fee22730a8af73e99f4f1baf308f.nq.gz
    ├── 3df842cbd99e34a1963a5a92a5613b3d852cd7c4.nq.gz
    ├── 3f3a9855df4580e3730869f40b631f96be0c465f.nq.gz
    ├── 3fd460b3d771873436327b59dbc9e24dce8cf821.nq.gz
    ├── 403da804a6dcb6d5a64135f30468af6e5bd92187.nq.gz
    ├── 41d830d0385feec59a07b3476dedd68ef52749c6.nq.gz
    ├── 4371a12db9ffd51882352f7310174e7905baf175.nq.gz
    ├── 43b70b7d022172296d542807a889127ca4b41cd2.nq.gz
    ├── 47d28fd1124d5ba6a95171060f4e9abde2e84f0b.nq.gz
    ├── 4845c2333c9a5765f515d85f5d9b47342482ee75.nq.gz
    ├── 488a4612206e2d66fa38e60bd2538fa3d4f73608.nq.gz
    ├── 4983a8ab48ad6246d56d9c127c112263ca0af93d.nq.gz
    ├── 49bbbf0fc53df02446688f8f199190b4dfb4c20d.nq.gz
    ├── 49bbcfad4d0ef6b99fe7044ea403f71c90e56e06.nq.gz
    ├── 4bd2d4a084987ab634893a29f72ff6d1a67bf658.nq.gz
    ├── 4cebedb1ec78e8ecaf652943d2150152259f5983.nq.gz
    ├── 4e5c7c13a7dd7dc440079354c5d85113d7f0b068.nq.gz
    ├── 4e9298a5f86202b876c89afeae2f2e342d6f7e3c.nq.gz
    ├── 4ee680e6e4fe7cdc11e63a1c4a730f7ffa57b4e3.nq.gz
    ├── 502843b5c8ff7d4aaa7367b928cb0af571c723f8.nq.gz
    ├── 550d0eb998705277a40d48db68b305a4bce055b6.nq.gz
    ├── 5577817d5f46afac05e2b982b76f2919d04cdefb.nq.gz
    ├── 577745c4303f231fe35fee9fd3ecf7f0ce8606b9.nq.gz
    ├── 589d1136e19c0b56dcb6731e8a6c53ae0cedc9a3.nq.gz
    ├── 598915a8a809d659f8a22546671fcad40774c696.nq.gz
    ├── 5b014cb33d16c4ef2727eaf4e60256cc735e345f.nq.gz
    ├── 5b838ca17ba9e5b41f96b3703aca145432935341.nq.gz
    ├── 5bf521ce6f86b0f84b9ad5c6dddeeb256ebf3bf1.nq.gz
    ├── 5cd872a7bd54ee423b7e8925a2a0520e385c1ac4.nq.gz
    ├── 5d4630b995f4687a199e8153cd7f4914f50930f4.nq.gz
    ├── 5f18b8da214b794a88b9c4303974af06acd0678c.nq.gz
    ├── 5f356a8aa819d5f22c6f63ac9e41aafa1d2494a3.nq.gz
    ├── 5f6c0b781bf92ac82f121fc3c5c8eaee8359aeb4.nq.gz
    ├── 60639a2221ac918b2413b58130308da12427ae8a.nq.gz
    ├── 60b2a621a585619326242296f9d190ca1968f56f.nq.gz
    ├── 60f0b28bc095c0d2956b3d8209f05511df780938.nq.gz
    ├── 61e3af340299a283456f1fca343a3c23657f47ca.nq.gz
    ├── 6275de00eb0e2a7848808dc236da8574cfce100d.nq.gz
    ├── 634ee3a22b93acb6f7ac1b12331c69d54b20e33c.nq.gz
    ├── 636a8287b939c176e6a4df0fee8722e12b40c9bc.nq.gz
    ├── 63a1c34f27d79e67e8676f360a6c936bad097f5d.nq.gz
    ├── 6536fda297c202ea5964c1e39d90c03ffba32a8d.nq.gz
    ├── 65bc5f73629a5b6d8863f21520ed298a02b961b4.nq.gz
    ├── 65ff0aaa4c0140a3c66f9d55b8f0f3be4b593116.nq.gz
    ├── 665511c1d413bd8ac380a4d801d9c520c9d52978.nq.gz
    ├── 667c023074f8ff737389137d3a7ff2de92f55767.nq.gz
    ├── 6845de6e7dd80db7251653d6fc07d9bf097bf822.nq.gz
    ├── 692f3cff25840bc93990b080b1034a49267c1b8b.nq.gz
    ├── 69cd8c2a9abe328509428bca05d164f50572701d.nq.gz
    ├── 6a32cb94366bde86565315c1eb99f4a6a2612ace.nq.gz
    ├── 6dca1bd78119e8c6525795540a1135b788648abe.nq.gz
    ├── 6e14498b06901b760237fbede6f50f0eea20216c.nq.gz
    ├── 6eeb2981a9c6495a171b1cda2b7d1f8afe4c437a.nq.gz
    ├── 6ef3353330da0b715969e6d5b46e71cd12d05be2.nq.gz
    ├── 6fcf09e2aa6df963fee26c2b23ebbfea1b6959a7.nq.gz
    ├── 70990114d0c5a3a290428613eee3ccf5d884241e.nq.gz
    ├── 7182bc4c5b08d89a1a36bfc6ba9a83e0ad99dced.nq.gz
    ├── 7214ac6298d1e411d1580a4bb539dff61cd09bb8.nq.gz
    ├── 7254ef45b40da8e02a44ab86f9945e11de519105.nq.gz
    ├── 7352cf84faf52c6cba7a2887cb39a83f3fbaddff.nq.gz
    ├── 73de9cfec11deebfa1a53e5ee4154754263fdfed.nq.gz
    ├── 743e98226e22d90ceeaa8b0660503ab7b9d3ca00.nq.gz
    ├── 750a1973df9cd9c8cb62a6c5073dc46ba3bee732.nq.gz
    ├── 75e0a5f4f6f41099187a19437dd0b281e4535748.nq.gz
    ├── 7a9d4f2d67b491b14ea5fbd11d7a46bee86bff01.nq.gz
    ├── 7ad5eb1532041fd0dcc7b18644512b652eb502ce.nq.gz
    ├── 7b5e9c3c3744b6c436834abd48dcf5e2a9bc9ccd.nq.gz
    ├── 7bfa49e8a9adf99afdeb8c6fcfcbc54f059445c2.nq.gz
    ├── 7daefcd8d7af47a76583387045b1707cf3dc1e3c.nq.gz
    ├── 7db58ec7744c33cd97cab9c4660e48dbe71b9369.nq.gz
    ├── 7ed70e1b6c82e4a1a1f0fc236c02369e05b96501.nq.gz
    ├── 7fb623b42735ace9f1a1eff72dffc6ccceba6c2f.nq.gz
    ├── 814d5b8d20a343b2c4e01a0bcf73a84a1494503b.nq.gz
    ├── 83b6c07f89508fad0a80f6a6d58341d2ed02dc5e.nq.gz
    ├── 845a116ae70ca607bdece9f2090d2a8dcff80a7e.nq.gz
    ├── 85bd96032eaaa98f42f373e5109c66c3b4b216a4.nq.gz
    ├── 86b7206d2a19549b652186d4b8915f1a4d505f67.nq.gz
    ├── 86cd411dc0e897cd97c6028ac7e23ec93a523301.nq.gz
    ├── 86e356738385dc028e1c233aaf913f7596eeba77.nq.gz
    ├── 876e8248ab83e54677d2d63515d041b225df818d.nq.gz
    ├── 88700145b9c4c3f674543551fc4be437878d2ec6.nq.gz
    ├── 890ac2c4ec25d7ea96880d76144d085c4fb93849.nq.gz
    ├── 895d22f6d9948967a1c75042afb1d971dfc13ab4.nq.gz
    ├── 8d42263a92393b8303cfc73378901e61ad8c04c9.nq.gz
    ├── 8f7a1e8eb29e5668f79815a87c4d338418ec6b4d.nq.gz
    ├── 911868e5ae87c20dc4d16f63ac8a53018ba5ecda.nq.gz
    ├── 92b4888e4187d4282fa73d95285c3ca9258ca6f0.nq.gz
    ├── 9354ec400a7ada910756aeb5a8722ff63c7b9cdc.nq.gz
    ├── 941babfbfebad23181605feb739905000754f618.nq.gz
    ├── 94b80d6a4918f078a5736476b2a0b86e8446f423.nq.gz
    ├── 94d2ac6b6645a38f95813057bd6e92284368aa53.nq.gz
    ├── 95541b11018beee2e972f3a938626c173b09a37a.nq.gz
    ├── 96f106ce03ad8ed88b3b7ea5ecd8f1c1c34dca91.nq.gz
    ├── 97a160e7f6f22f1ab60fa91856f8208f6162bff0.nq.gz
    ├── 97e837a9d74ed10e3447230ee4864efef8c685ea.nq.gz
    ├── 97ff4e8a4fcb27fcb6536ca26f00fc0a22eda090.nq.gz
    ├── 9878daaaabfcc9c1e6185ae9b185f820ee450af0.nq.gz
    ├── 9aa76ceb9fab92ecc8c117534429d9ff6f6c3adb.nq.gz
    ├── 9b5dd2603d78a659686b123b0fc1e3466eb0311c.nq.gz
    ├── 9bd784c24d7f206004784bcd9d9859dd88144b7c.nq.gz
    ├── 9cee0ac60e77b9bea7582a06c54950d20797962b.nq.gz
    ├── 9d403a9a8bd8850a5910b37cf175ae5087a671d2.nq.gz
    ├── 9e1f98bf01376e29c6de8adce74fd95083bdbba6.nq.gz
    ├── 9e92e44f9c9a4ebfb755d43cf0be43a991ad037d.nq.gz
    ├── 9ea906ecc958c3708a1fdd5ea9abbb5ea94c52ea.nq.gz
    ├── a058b3eb44bbe35df97f47dded4d3909acd3d116.nq.gz
    ├── a1a6bccf66eacd8e3b4eea6d2367965bcd9a884f.nq.gz
    ├── a1f5cf18b64ad6e6ac5d7ffe56937840b9b5fbd1.nq.gz
    ├── a2f77fe672f6e21ea943b299b591290742eed849.nq.gz
    ├── a43a1568201f6789280c7288f85f69e7b151ecb4.nq.gz
    ├── a4ce622e3341f58fccdd05995a0d79c8f818cfdd.nq.gz
    ├── a5651439649d7926dce9885174793132a224f450.nq.gz
    ├── a56e93727f67a1975b510335a330a7dd5b04f874.nq.gz
    ├── a5ba5b84135585ef3ab76584ccdc025f5590e389.nq.gz
    ├── a5edd5b9955f83f50b6c7803ddec8b3aafe7e1ab.nq.gz
    ├── a700a63a04abec50de20f7826ffba2208441d055.nq.gz
    ├── a82e4a1caa3296d84e34192b00ac398bb759d42a.nq.gz
    ├── a8d4bcbeb2c8717c87ae8fee2c2c117d179960fe.nq.gz
    ├── a96aa5cd2304b806fc35c03bd95c43801b094229.nq.gz
    ├── aa97c91ae45cf3f0a9fa3bb75a0447c0ab6f194c.nq.gz
    ├── ad57510cdb4104bb527f1b4547a87de03b3a7a5b.nq.gz
    ├── adbc248fa53e2e282a5c9fd9cd44f63136468c51.nq.gz
    ├── adde417713c362f3008543c897c36576787e8a23.nq.gz
    ├── af1b2430e303980d9ce10792031f2dd2d39f1089.nq.gz
    ├── b43461138bfff1edac4f2cee694e490ca8709111.nq.gz
    ├── b5a09511a01a5aa69ce68e7aede492d82605b003.nq.gz
    ├── b75875a6799b6bb9196e0643a6c03b180e5d4b92.nq.gz
    ├── b7772941146a3b7f83e3ca3a73ae79d889ef25a6.nq.gz
    └── b7ee89b9178c91afcb4f963b98e8e4f55d3113ff.nq.gz

10 directories, 200 files
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

[markedjs/marked](https://github.com/markedjs/marked)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
