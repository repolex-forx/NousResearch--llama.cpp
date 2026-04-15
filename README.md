# Repolex Knowledge Graph of NousResearch/llama.cpp

RDF knowledge graph data for [NousResearch/llama.cpp](https://github.com/NousResearch/llama.cpp), parsed by [repolex](https://repolex.ai).

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
lexq download NousResearch/llama.cpp
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0728c5a8b9569183ffca0399caac099afef87595
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 0728c5a8b9569183ffca0399caac099afef87595.nq.gz
│   └── repolex
│       └── 0728c5a8b9569183ffca0399caac099afef87595
│           └── chunk-001.nq.gz
├── blob
│   ├── 014112e5db4848d7f5e5dc43f550ffef9785ab1b.nq.gz
│   ├── 0143601214b15cf2f08ee3747a123855ec6aae7d.nq.gz
│   ├── 019d5e1bf9cebe47bd08d451919f4ee378080ff1.nq.gz
│   ├── 02ea6ec15241bdcdca2011253542fb1ee69c658c.nq.gz
│   ├── 03652760c80dc5f90caa6faec939fa4870aad4fa.nq.gz
│   ├── 03e1d2c04be65db2dfea377e16ac8b484f884edc.nq.gz
│   ├── 042ebe43c48e1346d747bce23ec7db064c9d45a2.nq.gz
│   ├── 0462e842171991c61d79cd3a8e1510f04099b563.nq.gz
│   ├── 0ac9cb03a8eca4494f38e6c57efc4909d63ffb9f.nq.gz
│   ├── 0b4e6e1cfbd442f1d945f90d5d668e19252ccffd.nq.gz
│   ├── 0bb9537f693ed22ba58bb642d7f124cd2373e8c8.nq.gz
│   ├── 0c752c7bbb59f847876471a9ca26c88e5eb13dcc.nq.gz
│   ├── 0cfac5f32adf2669c262751d9a6edcc060ce4fb1.nq.gz
│   ├── 113ca5fd3cb17dec32f0a3b42874a4b02120d5b8.nq.gz
│   ├── 11ec6c7252f46e8f8e8d29f327b7654a24f7f094.nq.gz
│   ├── 135a7e4bce5a168e13818ac47da04a693ce8ff8d.nq.gz
│   ├── 15c9b77c0d37c73316528404360ef3cea72218e5.nq.gz
│   ├── 16f1a0caacfac483cf2c33e0715ca8d1c61ea7ce.nq.gz
│   ├── 17fedc2b176f611fe508e4d38a5a035a4c21bb55.nq.gz
│   ├── 1a42b9abc79edbdd0fcd8069faf78cb31d760544.nq.gz
│   ├── 1b21d4d55550b54966c4bf0d70e41acd23d33767.nq.gz
│   ├── 1b6c54bff73d13096140d1de2cd46cdaefc071d5.nq.gz
│   ├── 1e469584e0cea32f7949fd061d2dd64e2753026a.nq.gz
│   ├── 1e9fe964b961a3249c279ab36a2e4d583da1c320.nq.gz
│   ├── 1fc79b7e191374b434b645951610a68e55537305.nq.gz
│   ├── 221b37553cfe7d825a9666d8d5c337a7814a3c64.nq.gz
│   ├── 2224bdeb0bcd44528e67b2a176c9fba5d281d7f9.nq.gz
│   ├── 2287d2a2c442b151b3fe621e4ecb46f34607a037.nq.gz
│   ├── 26563821a10780f9e7ef3d4e7ff9aaa726204ba9.nq.gz
│   ├── 2787c21fe6928bb930ef56224e0399b9c06b0fdb.nq.gz
│   ├── 28746000cddceb5ecb8d8b56e7a25ab08ea7ee4f.nq.gz
│   ├── 307b7c08d86da9816036ecc3f156cfec95461bb9.nq.gz
│   ├── 30c01196ab520773d949f02a82ce6b14c2f89674.nq.gz
│   ├── 33164e09679533041f6d3a3a94f9ddd057727f9f.nq.gz
│   ├── 35c089d57d253ae828322f550f08f102f1aed59d.nq.gz
│   ├── 365c5b865f3f4518bcc080bf685b7a55f414938a.nq.gz
│   ├── 3782f9b80ab821408622594e9c24a38444f08623.nq.gz
│   ├── 3796a9230113653402911ffbde6e0d21d44f4ce9.nq.gz
│   ├── 379fbd7ad35f115b1477a7908310335040f9a37d.nq.gz
│   ├── 38f63493a97a7e85ef04a21697f7d2989156e5e4.nq.gz
│   ├── 39215298f981b9c57b87fda07ce46defcb543fb4.nq.gz
│   ├── 3aa95a9dda7e80dc6ffc5fa07773e334aa6fb9f0.nq.gz
│   ├── 3ab1decd6c2b5515eed5f7254026cc7f08acb081.nq.gz
│   ├── 3f3415350919c99058ace62fa61ebc20418e4c6f.nq.gz
│   ├── 40fa2b63732554acc2c37d79f54091edfa7df2ab.nq.gz
│   ├── 4178e97ffc5d0273674f7b104a078d18754647eb.nq.gz
│   ├── 43f25ab598586d740c3e92066bfad3a2e9e3c562.nq.gz
│   ├── 4437c39488e7af2ab1676a3970c6383d211cccdc.nq.gz
│   ├── 4459516d093d62bab42be9e80bf1aa65f3e660d5.nq.gz
│   ├── 462fac23a69321cd7ba478493dbaeac226155b19.nq.gz
│   ├── 47d0be72ecc0fa15c353af8af0fbf1d81fa65fa3.nq.gz
│   ├── 48758cda81fdfd7207cb7fa0fb787e610a60ebed.nq.gz
│   ├── 4b1f1cf44aaa160393bf7c75138546f53b9d920c.nq.gz
│   ├── 4c42e3cdbf5264805981e9ebe88a437e6cdd4aec.nq.gz
│   ├── 4d1a37ad7cb874769d911fc3362d567da3aca291.nq.gz
│   ├── 4e0e023575322fda13c7d4a359fd3093c0534188.nq.gz
│   ├── 4ecb3d5862a0d30a3234a10c1c7d84ada6589dd7.nq.gz
│   ├── 4eef62bcfb96b11eec2b8cf4845d577db93525f7.nq.gz
│   ├── 4fa725a90fac42decad924a7b397091b3c511074.nq.gz
│   ├── 5023b77abf95e5a3a1a40fa5233bbd9322fb79df.nq.gz
│   ├── 5192d6df5c2f8f057010eb87ff58049618990c39.nq.gz
│   ├── 51e6c9c4b03292a52dfd2b58acc2312fc8aa9338.nq.gz
│   ├── 5452a1866a23e372b78f6c648f7aabd176d2f77b.nq.gz
│   ├── 54dc2beed00809793613989767f01232ee31391c.nq.gz
│   ├── 5bbb1ea02a3c6aafd54d618aa33a003c0cea532a.nq.gz
│   ├── 5c4c75ea77cf9155c7b966c821939ccef25b9210.nq.gz
│   ├── 5e1be61ff6cef68fbdc4b24f036e19cdfaa537f1.nq.gz
│   ├── 5fd739e55c554a3e7f855c147789d873fd7aff24.nq.gz
│   ├── 61c71c3589fdf28869adbad4fa22e05c56fb110e.nq.gz
│   ├── 6348fce6b94d031071302b40c10c5113850f473c.nq.gz
│   ├── 65796fe2e423b3fd2d89f6f1938da5ac5da6bf0d.nq.gz
│   ├── 65cfe63ebe8e92cafd6edb93e9d0a22e93383780.nq.gz
│   ├── 6870a11b931dba4941026e05f4c2279049440b2c.nq.gz
│   ├── 687628b35e996f8ebe772fe82e24f901d5e04d17.nq.gz
│   ├── 696b33ce75cf4fa8d92850ef5e762c32190d6410.nq.gz
│   ├── 69ba6173c0c26b18a5cc6e915f369a090eeefecc.nq.gz
│   ├── 6aa06ec8fa1152dc3474c071ac3657b031dbe08c.nq.gz
│   ├── 6c32cbd047b84aadd0eb440ffeca4c771990befd.nq.gz
│   ├── 6d312216d58af7c89287696d00127966105bf7d7.nq.gz
│   ├── 6fa55b3194676ca0d126842859b96ba846daba07.nq.gz
│   ├── 726ec47c0ce4f90d1a99d7a8ba3ee85c096a179a.nq.gz
│   ├── 72d7afa463d741498af0063f0ccf14e5b9028bf9.nq.gz
│   ├── 73d027c70215495a5b5233b95110a2c3f622d46c.nq.gz
│   ├── 7438defdefcdfeada492d9ae758695c914ea9b6b.nq.gz
│   ├── 744f549c5bdf776b1524792bd76bc58dcd56450a.nq.gz
│   ├── 74a6bff40411784f2b13ca4c1a7bf607bfc400c4.nq.gz
│   ├── 75d1e16fd039c57b5653f5a712a08239d48fcf10.nq.gz
│   ├── 76f67efdc6470081b512a8db5bf2b1d4962d9c3c.nq.gz
│   ├── 7b70227a525e1a158cd775e089674b00c8c4d8d1.nq.gz
│   ├── 7dbfc7c2044e1b43829be2e6f889697075113ed8.nq.gz
│   ├── 8269e2592733b55a901ee461d9065c39a794cf21.nq.gz
│   ├── 84faad37ab95a2a58cc616b78bd60e1c8711f3da.nq.gz
│   ├── 87ef68771de5eba0e8315815ca4f512254f169b9.nq.gz
│   ├── 87fde16453d2526aa7e39e40dd65b30a18d0c95c.nq.gz
│   ├── 89dafc9f278dc169a808614837cd633fcd605757.nq.gz
│   ├── 8c7b7bef42784d3037c377e71fc20e08a7302883.nq.gz
│   ├── 8d2bae6918b622e06dff9a419e265e72ac153250.nq.gz
│   ├── 8d3c162d2bfa04bdb29a40131368dd9efda7523d.nq.gz
│   ├── 8dc3949648ff9620b1ca86ec8e4888649c618227.nq.gz
│   ├── 8fd95535677803e6349e9ce769cb51f5814e1458.nq.gz
│   ├── 9037d72728a42ed772f384f3d7ddcef01d0d15f5.nq.gz
│   ├── 92b3f6dd8b0eca9999962b128af9357377068ace.nq.gz
│   ├── 974484207251dce531df3228c5d9ae87493d8f5f.nq.gz
│   ├── 996d737de6deeb239ce9a3efb55246621fb8201f.nq.gz
│   ├── 9a928ef05431a847efa476433b19d24ca88c15ca.nq.gz
│   ├── 9acceb980c2643b3a0aba34311c88e9f3fc78705.nq.gz
│   ├── 9b3c3060515dbfdc4e942b5d621fef68bf4c38e5.nq.gz
│   ├── 9bdbc755c13a7894fc0bc48af1d41acabbe6b254.nq.gz
│   ├── a3b5be6d887b85409c72e2c3b891c9fb382ee0c7.nq.gz
│   ├── a43d5a7d56753b9495d63ada859f6273003b1a1a.nq.gz
│   ├── a4bc8d976560e59bb9cf0823add738b3a0a2265e.nq.gz
│   ├── a4f4f4ee665c47d6d7b5ad72b0c10e3e98476dae.nq.gz
│   ├── a5912ec20e335005d368b2f937354ba093f4d8b5.nq.gz
│   ├── a5ec8f87a94530840ef7c030a6db9c3e9cdef6e0.nq.gz
│   ├── a92b445c9d7660da6ed5dfcbc4cce9ae7a5b9827.nq.gz
│   ├── aa2c4352df294a4e2df58e614a98a38505264b32.nq.gz
│   ├── aa325a03ee444c9d141b1d35d4c44ce3979336ad.nq.gz
│   ├── ab6a4e10e49c3ba02ec9c14b9ac75e80ae655b55.nq.gz
│   ├── aba92480c833c8394cfae8c4affde523d23401e6.nq.gz
│   ├── ad494d831f6fb8df192c472fb8a38c3e74ecba67.nq.gz
│   ├── adc6a391376d45126e4f5eb0f0d688bf77d1755b.nq.gz
│   ├── ae176d7075826fb39255de5a080d8c3d69794ca0.nq.gz
│   ├── af00b4e16501626eff836f769339daa3b9935018.nq.gz
│   ├── b231d24b8185944deee075b33cb72a2bd0933d1b.nq.gz
│   ├── b4999ff5a07c866b80f601d03fc7fe910ebdb7a3.nq.gz
│   ├── b4e535acf1f647e506105ac71ca1520dc6dad02a.nq.gz
│   ├── b682057dd6891683a089bc17ce86ecfe6d94be0d.nq.gz
│   ├── b9174b4e6e12668e244d56f37847aa40c1b230c0.nq.gz
│   ├── bcbdd2bedfd1ae6aa1609a9ac1aa29a6c876dd04.nq.gz
│   ├── be2896614e9b37604f580159e7043f1d6b66aa94.nq.gz
│   ├── c0725088f10188b3f7969a820e21648362471cee.nq.gz
│   ├── c1ab6bb6d08a3272f8c6cc28a1e3cb8e099a2891.nq.gz
│   ├── c59e3075d26f25f743023c92feb879fce64b9afd.nq.gz
│   ├── c5c394058ced81642e6a503f86a87b448f88d474.nq.gz
│   ├── c5c8ac6efa81a552725538648592e3fc1563e1fa.nq.gz
│   ├── ca4d5a4a53531ebe048305f4ac503b5d6fff4b2a.nq.gz
│   ├── cc188894804bab4da86c67df7b5e152acab82305.nq.gz
│   ├── cee3a87f1a7b2e6d4e66d2e0740403ffb874abab.nq.gz
│   ├── d427054dd8d6ae585490fdc63ddb5cd2299c68fa.nq.gz
│   ├── dd15393c3fe45d47c2a3737103d4ed02e0a7a50c.nq.gz
│   ├── e0c251e5b03cc7819320368c1a6ba6879665a941.nq.gz
│   ├── e55b38bd9c0bda89a503bd13361e032db27a0c5d.nq.gz
│   ├── e5ca8269b9d5646e93744ed250d2404196e6e8ca.nq.gz
│   ├── e5e040f62a60a54bf16e1aeb8e4e687b8f933a9e.nq.gz
│   ├── e5fcb37d6fe7af16d06c6434f4b43f5792b83f3b.nq.gz
│   ├── e6439841dc1455775282df378c11050d9e06890c.nq.gz
│   ├── e7fe655dbcea3a724f575abc16a8ef6de8197b5f.nq.gz
│   ├── eacfb17c67fb2e8a476d9bc58b84a34c9942b24c.nq.gz
│   ├── eadd13cdf7930a09bdf6e1790c596a8b0a652ff5.nq.gz
│   ├── eb214a836489b04a4e3d6b9c6444ab30570edb89.nq.gz
│   ├── ebeadfdd05fd5ed587000d8b546eb3e0a2e89e1d.nq.gz
│   ├── ed0d6c56a23f8fc783516f73f0ddf58211557512.nq.gz
│   ├── eda119d449849a0de2764a71b0ba3d51e7d5522b.nq.gz
│   ├── eea78a057126ce5da310e31157914b540c534449.nq.gz
│   ├── ef0fc1b07f01c0ff32465597ced7dc36780f6171.nq.gz
│   ├── efb5ba5e2af4543685c824337b6b8ae18b018572.nq.gz
│   ├── efecad0cd89f16015347b014e376725b0978068e.nq.gz
│   ├── f11fbe57c11123736bc07ccb2d9dd16092f3b55f.nq.gz
│   ├── f16d491655948e72322016d85bca9ad464be8c0f.nq.gz
│   ├── f349e913e3d10dc84ca1e045048e92ede8a3d5d6.nq.gz
│   ├── f399fb19a6bc8651b764b0245ff9608c3dfb41e3.nq.gz
│   ├── f63d9fc22fb3fe41dff6f16ee85fec3a4ae91318.nq.gz
│   ├── f7215f43bb31ce88c8d16977a8ae30a9a08930aa.nq.gz
│   ├── fa0f98aa09df202e63dd89cb8ccf3538f3de38eb.nq.gz
│   ├── fa1977f2d949241834f3936424174c2133ef3ac0.nq.gz
│   ├── fb89a1cd4e8334b327249db1a0247f84d1252a04.nq.gz
│   ├── fdbe778af4664c2abe31e01179db551731a25805.nq.gz
│   └── fe8f5dcc62ed9e6e09202a7c6d4464679dff9be5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 0728c5a8b9569183ffca0399caac099afef87595.nq.gz
├── filetree
│   └── 0728c5a8b9569183ffca0399caac099afef87595.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 178 files
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

[NousResearch/llama.cpp](https://github.com/NousResearch/llama.cpp)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
