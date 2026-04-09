# Repolex Knowledge Graph of psycopg/psycopg2

RDF knowledge graph data for [psycopg/psycopg2](https://github.com/psycopg/psycopg2), parsed by [repolex](https://repolex.ai).

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
lexq download psycopg/psycopg2
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fd9ae8cad2bcfc3e7e9410e7b6f07cda8f4f05ec
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── fd9ae8cad2bcfc3e7e9410e7b6f07cda8f4f05ec.nq.gz
│   └── repolex
│       └── fd9ae8cad2bcfc3e7e9410e7b6f07cda8f4f05ec
│           └── chunk-001.nq.gz
└── blob
    ├── 01cee9265f286ed56546d0b9298c3c0af225f968.nq.gz
    ├── 0229cfb8fec0b895562b1bb37af15ba352b2dd8e.nq.gz
    ├── 02b15890e5bb592e1a36a50a0531d2a89cd7d799.nq.gz
    ├── 0358aa61d35d595da8120435c79f70e4e9a156de.nq.gz
    ├── 03ab4cde2cae2c964ffc521e705239421e7770b8.nq.gz
    ├── 043285547fc9ee8b0cac19c657b601f1c54a523b.nq.gz
    ├── 050345f4384dff5d43946d244e5736874602103f.nq.gz
    ├── 05ad1404421d9167b426960e3e94ac85eb190e14.nq.gz
    ├── 0747f8c62b8edad52f2f8bdf2dc8379042fc5a7b.nq.gz
    ├── 0830f932e4c3dd246327f21b37ed6a235cbf8b89.nq.gz
    ├── 083379b94f103c158030a8628d23cd415658c9bf.nq.gz
    ├── 094c58c6b68a64cb7b268098f96c67a41a33d08c.nq.gz
    ├── 0b304d6a913b7d246d184101c283470eae6daab7.nq.gz
    ├── 0d284f8f5aca56cea32a989a8e583a5b47a691ee.nq.gz
    ├── 0e4901d106b9932c57a5b4f260f71fdd8e90fac4.nq.gz
    ├── 1173fb55ce21e2032c635cf60db5a121513d9b74.nq.gz
    ├── 139c1ade6ac5d35a90e6fffbfc2cdda319465e03.nq.gz
    ├── 13ca3ef7517ad8bcdbdb2c525c97eb67b7cfd4f0.nq.gz
    ├── 1490a92ef6955bec5ad22963bcb983ccfc11104e.nq.gz
    ├── 14c1220cf0667b417e6b22a4aea908be1b66afff.nq.gz
    ├── 16be9062ad52540d4b9d8eabd86893ce5f5e02fa.nq.gz
    ├── 16fd9c987af64b08a999e1f5f3a63a052c584557.nq.gz
    ├── 1731546e5a7e7c1ec319deb050af2f1e87fa585a.nq.gz
    ├── 17e475bffcc7b306af04334ee196048b4ba0b3c3.nq.gz
    ├── 1f780d4388b71876920d833bf830d310dd49ca7a.nq.gz
    ├── 1fdbda9a36cc839024b5f24fea512f1bddc72868.nq.gz
    ├── 24b5ec57da34afdde0a77edf95face19a09351ec.nq.gz
    ├── 25a7212d1a7245013e34cf079cb53155c13e741e.nq.gz
    ├── 2641db845426432025317508157b090db4401965.nq.gz
    ├── 267552738912098d028c2038e9baed24eca421ee.nq.gz
    ├── 289af5ee7684efa9205971957ac5b3506b814c86.nq.gz
    ├── 28c4be9f9c018fd612aeb550466fa1423a74444b.nq.gz
    ├── 293862621881db047ada3ba7d7f1d56a70b08e60.nq.gz
    ├── 2cbe0ea86356820b4fc9a093251b92773449e2ec.nq.gz
    ├── 2d9f36bcc5594eb8a752c3135f23902abb129c5b.nq.gz
    ├── 2e00b5313fb5a8a2ae53eac185fd83eb17f96bb0.nq.gz
    ├── 2e2858dd5840c4014dd1a525155746b2d97c4d81.nq.gz
    ├── 2ea5c912a8cf176c440ba81402db573f1edc6bc7.nq.gz
    ├── 2f80cb731a373060b593ef8964d5813a35b2f1b8.nq.gz
    ├── 2f989507afbdb5e9eac46376d8d09951ee57acfc.nq.gz
    ├── 304c24dd11ca2420a6aa9e4f2c18e48d3a94cada.nq.gz
    ├── 315d63eab4fc6c0990dd648db34efe5d5feb6b82.nq.gz
    ├── 31f0310d47bde5f1d03d7fb096de5e76624e946c.nq.gz
    ├── 33128995bec9ba6ce6b4fe2198577d3e65f550be.nq.gz
    ├── 333dbedd21f849fb32942cff839a03b8973a6b97.nq.gz
    ├── 339f7f181bb2c694b67545500da6b9e19275b652.nq.gz
    ├── 36e8ef9aa330a951803a49404a0b67bf5558dc57.nq.gz
    ├── 37001a8b99d309a9092ae065417e89842edb99fe.nq.gz
    ├── 378ce849cec5e9db76730821826b7ae030fd5cb8.nq.gz
    ├── 37e6b13b4c078b2b8141d10707b2230591b5cbf2.nq.gz
    ├── 38ad78d9b44911a124ce0ad728fb22d6bf0e644a.nq.gz
    ├── 3a3ad635910dab8598c59f5d2bdbcc9629e9cd60.nq.gz
    ├── 3e71affaf3d1acb4611eb18ab721fb0eb8aeda81.nq.gz
    ├── 3fcce43ba7108945decc3e8bf1824a0502b833ff.nq.gz
    ├── 4094dc5ce8a05cbba9fd8e25f7b3e73b7712faa0.nq.gz
    ├── 42c46db597f279e51cf5f38cdecc0dd87bd943c1.nq.gz
    ├── 434e9e9f48f73e6ed73f1d67dcaf2f1d58a3017e.nq.gz
    ├── 44b66b58689e30f5166f50c69971098b52591ec0.nq.gz
    ├── 4519b4a6eb86ab4e8e3602eb0db56a916bde5939.nq.gz
    ├── 46070133181adc07bb27011f125d3fd33c1ac98d.nq.gz
    ├── 471cdbeaf6755cafffd1f22d95d411a3b6cf1dad.nq.gz
    ├── 491226c85a9daa933e5c290754c31a85560df91a.nq.gz
    ├── 491d285f0ac43dfdf932ecf89920db32c4ea2b5d.nq.gz
    ├── 49ad8b297179a29c310a935539a8c24eb1afb35d.nq.gz
    ├── 4a2339ef93acddb962933e334ca01d2d554bb828.nq.gz
    ├── 4c2327850200cd9e3ea4ac7b07a9d0e230a5fac0.nq.gz
    ├── 507bc741085b555c17edba60e02248aa0a9a3c79.nq.gz
    ├── 5223d3a5a0086915531808a698725693877101fe.nq.gz
    ├── 52627e4d16f3cb27c4015ec395c149394989d7e5.nq.gz
    ├── 53a4e7248c0d7410b732548dc84b7528ae25b568.nq.gz
    ├── 53d0680d945b9dd0c6f1a61b9169efb0e2751565.nq.gz
    ├── 54f9fb55b159eb526c40f8a6dde97d54d32a8018.nq.gz
    ├── 55327a9260dc1e4ee3b4337945ba8649cfca6136.nq.gz
    ├── 562fedc0ed2365d60e53f52a125e0f73e2e0116e.nq.gz
    ├── 5793b1ca24b71c8d0038d17f29440ab607a9cf6d.nq.gz
    ├── 580d44aa66f77c568aaec99f00d54c663e686d9d.nq.gz
    ├── 5850291ea54bbb2cc5bddae8d8fbccfeb4ff7c72.nq.gz
    ├── 590397830762de72a5cc20df2c0e739d9d1b863c.nq.gz
    ├── 59a89386eff9d007499f3c35f6a56cf72443f1cd.nq.gz
    ├── 59b1b2b7d56860420bbfb382c1edc4b316844a56.nq.gz
    ├── 59c4070d4a88fe0024bd0a918b5acc2e6eb363b9.nq.gz
    ├── 59e01209660e0b09bfcf2cba7dbf0e1cc261ca85.nq.gz
    ├── 5c757860d99ad85893d9b37733eb04598ef3c68a.nq.gz
    ├── 5de989ed2bbd544e6d86b5a050360919bf13cf02.nq.gz
    ├── 5e2ae5132bfa96c6967911cc94c918022078d6f9.nq.gz
    ├── 5f3ba2c1b64c1cd388f8564e029ec6aba8896674.nq.gz
    ├── 5fd96e2483da93f1f0006fdc547271f1fe7fda42.nq.gz
    ├── 60677ddb6aaacf1e9a74fe4e441213446b9fe943.nq.gz
    ├── 62860dcbf848fdd4e623400beb55705a94371ce0.nq.gz
    ├── 6408cac9ccf3c7fa5969e80b00d926a1ec910600.nq.gz
    ├── 6484a1fe5a22c53ec12f8044ac403a83d3266afa.nq.gz
    ├── 64bae0731e192caa5a73936875f89a15ae246501.nq.gz
    ├── 65023752c1550af27631b33bf3bbfdff175d7111.nq.gz
    ├── 650d1a55c23cd24262ee04183babc00328fd168f.nq.gz
    ├── 6887d4b548cafcee4016a3effc1cea05c1b908aa.nq.gz
    ├── 69b352b79431340d77862ccb35f4ed6fcee139e5.nq.gz
    ├── 69d26003687ec4c1c82d968d593cf8d719a7a76c.nq.gz
    ├── 6a281190b44f890511ca4d4c336a5edaae623b0f.nq.gz
    ├── 6b934a1663658fb2dc4aecaed478d3c402bb5f4e.nq.gz
    ├── 6be565ec52486ebbb546ce22fbb6fdfe0934be32.nq.gz
    ├── 6d61c2eb0013b1250d113ca0c75c91fbc7c6cc2c.nq.gz
    ├── 6fd516d8f99af665a43549ae54860cbe0f1ad4bc.nq.gz
    ├── 7009ee836dc5fd253be832db113ffd74115e83c2.nq.gz
    ├── 70bd8a0ce131efcd89b6d8de928dfd7ba1d09a9f.nq.gz
    ├── 712102ee4e86013f1c13361202536722bc77cfa1.nq.gz
    ├── 71411899ca99a794368722674552f75ea450be00.nq.gz
    ├── 728176c2fec435fcf521b7ca053d42639c1106bd.nq.gz
    ├── 73a42c252aa507862423efaec61892d86faa234f.nq.gz
    ├── 73b6d7755f3b7fc710bb7ae8f0454bee2798f0c8.nq.gz
    ├── 742014add004186e837206cc5de4c3e9682c53aa.nq.gz
    ├── 763910dc35b40315e6214bc1a7d6970c9a2e2f26.nq.gz
    ├── 76748cb3fca57601977cb34ba82589b51e4541ce.nq.gz
    ├── 76f75630a92e37dac3bfce2560df4dce6e0f449e.nq.gz
    ├── 7705db316ef12dddaba461ed709819169b0c3e29.nq.gz
    ├── 789a8e692333dba6702e47a3f143fe81f0c8f708.nq.gz
    ├── 7a04aabca5163f99a3d0435dc81f3d19f57b4650.nq.gz
    ├── 7acbbbed5855d519f228804094160e560202382d.nq.gz
    ├── 7c032597f838dc8d0264f03982450208c274c925.nq.gz
    ├── 7c435b374cc56c3c94129ee2621f99c544408c9a.nq.gz
    ├── 7e139bae392ccec156aaa3c2003dbb2b65691062.nq.gz
    ├── 7e51904781f29bd4ba049a229be2a92b0e6c613c.nq.gz
    ├── 7eac99d9dc553e4a7e4a5b2dc74ee2ef90ca3681.nq.gz
    ├── 7faf4d5cc8d1af0bea380c7a9751c21b0658f4db.nq.gz
    ├── 7fc776a4bbb322f2f93e82eb04428793a7068b9c.nq.gz
    ├── 8365e048b9a99118f0b4dff932673df93a2ad11f.nq.gz
    ├── 8376b3a4f74f2b0345dddf202b5c1c4f0843ad3e.nq.gz
    ├── 83ab91f206e00416599b5509c64b2e97d5d091a5.nq.gz
    ├── 83e94172c7c0169411962cc38d1639b6813cc1d1.nq.gz
    ├── 85c9b18b720a0329842d769838e60be4ec516acb.nq.gz
    ├── 873a419b966deeadfdc64070bace06aa6859d643.nq.gz
    ├── 896efeddc80c0e30970b9d64aa3a94239207416d.nq.gz
    ├── 8a125640bbae22b7559b9b75b4a9a0c25c44740e.nq.gz
    ├── 8ac6b8c4984dcd382e54c7923325af6d226ca3df.nq.gz
    ├── 8ba87cb657119f50775f3354c11ecce0fe8cf968.nq.gz
    ├── 8ca2187f1ba05ff0bdaabd189ff6af1f5f109cfc.nq.gz
    ├── 8ca2f38d5ef1b849617d500fea8949711d4e2c30.nq.gz
    ├── 8d47d1201aea540980c676ef2c63910a21ac1c2e.nq.gz
    ├── 9029e70fc8c8dfdca187cb9632af896c660d15fe.nq.gz
    ├── 9320d3e5f37341cc16b2915d7cb2316a38965c56.nq.gz
    ├── 941bcab61e455483fcdf3306a6d354c2d25cf302.nq.gz
    ├── 94cdafdf01151ea0ebbd10230ee0a81d12c92b90.nq.gz
    ├── 950242237c690a16abe0e2f7647c6fcedcf9ad1a.nq.gz
    ├── 953f7a7a437125ea34de7eee261cd360f015f430.nq.gz
    ├── 95f4e23231c34a31cad94d2b78a6e53865e0e214.nq.gz
    ├── 975e7f4db62138cf42195e283eefdb40fdfcf47c.nq.gz
    ├── 9842141723bf9b0d8869bbc8d24f65c2bf9e43ee.nq.gz
    ├── 9893523b011b426e74db403cf09469a07029c324.nq.gz
    ├── 997425776af088079a64d20e63def38beebf993d.nq.gz
    ├── 9a10c94f28947bdc432e76986a7a24bbb61f5cbe.nq.gz
    ├── 9cbb16f97bbf7ec7a96dcad6092a5b0f9546a212.nq.gz
    ├── 9d1dbeb34ab14ee35940f605f6fcccd466a4b0b5.nq.gz
    ├── 9d67d68eb34861345f545c0148c5a4cde0b3d28b.nq.gz
    ├── 9de05e7a6f9bc547416476a746a5e7bb0d5d8874.nq.gz
    ├── 9df26ad16a71afe7323dd6b985ea401059a4d903.nq.gz
    ├── 9f0c308f8b8a96b4f36451d49f4a36bcbef89dd2.nq.gz
    ├── 9fc55da4ff07dd84368da482bd3984279fed0653.nq.gz
    ├── 9fca0d6af147fba5f96b862afe7fa6aa1093f9b7.nq.gz
    ├── 9fde430b161fcd8877522d11b4b8a643460a9216.nq.gz
    ├── a137f84557d32687de0432f90dcb5ea72b63129c.nq.gz
    ├── a36cf9184dd7123297c130ae4ffca6522f1857f8.nq.gz
    ├── a3c4ecdce86cd9c2980231bfbd0f485dea58ba82.nq.gz
    ├── a46e7d887c1447c398c4576bdfb51b90bbb51580.nq.gz
    ├── a998b3c3dec7e2dbcfca904aeff9bbe01e59df59.nq.gz
    ├── aa646c4658d56a5b98781db6c8a7d418b6df8109.nq.gz
    ├── abfbad9d735ba6fc8777bb60d85aa5b65a554172.nq.gz
    ├── afda00f47ff265d26ec1190122b59c9bb08ffb76.nq.gz
    ├── b105a4c463903f792195a08995ab53a95620c522.nq.gz
    ├── b18c3d628536dfe1ef9bf06afea7db332ba3bb5b.nq.gz
    ├── b275d22bb52bfe2b0461f1284bacc31d1b36a8d8.nq.gz
    ├── b2a62306a4e18f216c5c6557665559042b4f6468.nq.gz
    ├── b3c640515bd161e6d8acced7a893d1490b7048e7.nq.gz
    ├── b50894c1328ce338471d1dfb76f9a6db448f8b5e.nq.gz
    ├── b648a1ebb5e9aebc932d47bb4645dd24271a1d70.nq.gz
    ├── b6c82b722d17f917f734cd82cb79e9759d3f3779.nq.gz
    ├── b7c672f29c7c243bb3e52de948c8bcea03705151.nq.gz
    ├── b938d0ce171a7de800f7dee47a5297c9f81b3cdc.nq.gz
    ├── b98d8d575505b01edd6c12d683ddb229864a79b5.nq.gz
    ├── ba32e4735d3aa043b49fbcd8761b6e1d328d02ef.nq.gz
    ├── ba9a565bf78a1c9dd990e077864eeafd8325906f.nq.gz
    ├── bf3c91c8ffea0b584a18e4e144ea604fac1cd242.nq.gz
    ├── c03e60686a48a00921e3dd1924b5e98c54601fb8.nq.gz
    ├── c1bd5ff7e59083f5119495174d6fe20f22a9f9cc.nq.gz
    ├── c1facc49e0097f8c376b68506386d2c9a8d9bf85.nq.gz
    ├── c31f076c922f64faa512ead39f9f5d069546e320.nq.gz
    ├── c40c49307630e6a7839cab77661023319437b49c.nq.gz
    ├── c7cf52b253f4969ee2127cf26fd7ca24c563e031.nq.gz
    ├── c8898a41e908b0c57e6e780202eb03471dda956f.nq.gz
    ├── c9747da790ed9bbfa31a0700725a91329a5a2ada.nq.gz
    ├── cbd22da72d8971c0731ac76010cba7349a1f16f5.nq.gz
    ├── cc0fa6ef1f9348796035144d022e14d2bd1c59aa.nq.gz
    ├── cca7fc278f5c81ce23a2687208f0d63a6ea44009.nq.gz
    ├── cdb1c9ae1e0a60fa66588a31ad8e56dee603b5fe.nq.gz
    ├── d102d734ff57a4400257a3d19fc43fbe3a8be58d.nq.gz
    ├── d231c3add4b06a4f5d2998e9bad8bb1baa5d57c6.nq.gz
    ├── d32250ea2c9d1046d239e9e75bffef7cc19ec44a.nq.gz
    ├── d34a01710c699617436eb90acbf5956404e2f957.nq.gz
    └── d38566c88358edd3c0292f294964ac349d241304.nq.gz

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

[psycopg/psycopg2](https://github.com/psycopg/psycopg2)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
