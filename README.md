# Repolex Knowledge Graph of corteva/rioxarray

RDF knowledge graph data for [corteva/rioxarray](https://github.com/corteva/rioxarray), parsed by [repolex](https://repolex.ai).

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
rlex download corteva/rioxarray
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3182e84bff998789f8bebcfc2cee7f3c821a4762
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3182e84bff998789f8bebcfc2cee7f3c821a4762
│           └── chunk-001.nq.gz
├── blob
│   ├── 00eea61dfe4194d854dbddea19a39967c074c682.nq.gz
│   ├── 01d62cb00fd611d7f9ed2b61cf7981f23f6b3168.nq.gz
│   ├── 02b0bf834c43f566909759ede08cc776582912d7.nq.gz
│   ├── 06f1e9e2e941bc22b6c096cb27025cb89dac449b.nq.gz
│   ├── 08f0772344e6d4994fc39bcbf19960ef6aaa015d.nq.gz
│   ├── 0b7aff3dbfb7fa9a4bcc78d92e9236788efc6fde.nq.gz
│   ├── 0ba38f2bc47954b7e1c4a0da600431a6247c2ba0.nq.gz
│   ├── 10e7295314d1aec91f24f6179107e4aec9db4a96.nq.gz
│   ├── 11a96fd3dffbdf359e7da5e78554681923822e3b.nq.gz
│   ├── 12a60cbd0d9ad96beb33022d2321a36322902717.nq.gz
│   ├── 148ef672c6c22283e01e047068262d5aae06b703.nq.gz
│   ├── 14d365d8e93a3da9bea30c194ff8bd8bace374d1.nq.gz
│   ├── 16da3f3e1b168d9601fadcf8b12c03f5f2e5cc13.nq.gz
│   ├── 1946515378a79f4d99392d2d038fa70093b6c5e8.nq.gz
│   ├── 1b30f33038c31f1c492a93b75f78defbfd4d4a9e.nq.gz
│   ├── 20981d3b5e28dad7a5588a761d8c0d9633fc5a9b.nq.gz
│   ├── 23210d06a20a4243094acf692a8d12f6e6cccd37.nq.gz
│   ├── 249e4a7e54f250bd4f11a546e51c3bbcc5607b53.nq.gz
│   ├── 26a35f902d2d74db94901aa3277d724b7c9c79fa.nq.gz
│   ├── 289bdfd2fdd70b0a8bf028ef44b25e987a634d59.nq.gz
│   ├── 2c3f8412e0a49e15e5ab21f5fc90d15d74b19f94.nq.gz
│   ├── 2f31a0316498dcfc1eb69848cc86e7f7f03d191a.nq.gz
│   ├── 2fc52250d7ff3d6ca78690524dd76477a54f88c8.nq.gz
│   ├── 33d25f0dcd07e59359443ec7ac2c5a224d982227.nq.gz
│   ├── 33e4931a5912e1a426373a92240ff9274202e4a7.nq.gz
│   ├── 3506fa5bd30a5182209086dc1402099b064d70ab.nq.gz
│   ├── 366b7c67480e72fd1bc9ea8063353fabbf60add3.nq.gz
│   ├── 37ec93a14fdcd0d6e525d97c0cfa6b314eaa98d8.nq.gz
│   ├── 3dfad94b5b3cc950352aa7dd4fc9b523598cdae5.nq.gz
│   ├── 3ffac5ebc107e4a046bf0803e18051568d38dd3f.nq.gz
│   ├── 41ad1cfa7e479f08f5af9740e9a94055bb44abcd.nq.gz
│   ├── 436e8cc57edaaefa1bffcbd39997767479439ce2.nq.gz
│   ├── 462f860f9d93af7122d9fce4fd5b2931c6ebd275.nq.gz
│   ├── 4773066d3180e44f7387c84cdabd68183e59c18c.nq.gz
│   ├── 4aa4ba7b587a621d5047cd3939fb9b2718079ef3.nq.gz
│   ├── 4f267721cbe73db103807615e130d5c2f60ed757.nq.gz
│   ├── 4fa0650e835fb957591aa3f2e58e6be32b2f47a6.nq.gz
│   ├── 50b3db42e9fdac5bba9aa3647e64dbca746f39d9.nq.gz
│   ├── 512001b1b2eeded32e44d84e9bb87a87ef16b371.nq.gz
│   ├── 51daa965abec18ef82931d95b3445bab5867d7f2.nq.gz
│   ├── 52ae2ba06acdd6ac77121821f2a30c040b8efee1.nq.gz
│   ├── 5550a13839bef57722d848a72612c77cd7e54e6d.nq.gz
│   ├── 55b0265b3cf116783e9e078ce41568abd19d7810.nq.gz
│   ├── 58109470d708d47d021ea7007a3e2ad4f4fb65ad.nq.gz
│   ├── 5af24d178cc5c6a1805275ad9a14b07abd76a44c.nq.gz
│   ├── 5b3f7b09e9fc462888fa14ea78828b0e83d8bf1c.nq.gz
│   ├── 5de152ed856a9337982fcb490697b03d9fd32d30.nq.gz
│   ├── 5e901dd3be1b45be7ea2c94470821d362bd9fc3a.nq.gz
│   ├── 63377f044e4faf23167fa8b9f54646b3aec3365a.nq.gz
│   ├── 638515c50a8c86123125497111d2ebb28fcb535b.nq.gz
│   ├── 66621e79bff587b0bffa9de1b6fa3fec402f0557.nq.gz
│   ├── 6bbd5f1b069b9aef6b626ff18269840c0c08a5cf.nq.gz
│   ├── 6ff83b39db978e7593b0ebc9ac8e309c0a02f8ed.nq.gz
│   ├── 72a33558153fb57def85612b021ec596ef2a51b9.nq.gz
│   ├── 72c497740da338bbf573bedb62b98ef44f490fbd.nq.gz
│   ├── 7367d5ab7c2e0156972de9a2eccdd298d4e693ab.nq.gz
│   ├── 7543b3503418c04c4ba79b4046929452baafd818.nq.gz
│   ├── 7ee8506114c80253b70005142cec1890aa923dc2.nq.gz
│   ├── 7fb6ceff7e1e9dc2bd03a0e5dfe753250d3f444d.nq.gz
│   ├── 80eb9f841ac68a799ff8e502a87509c5608e5901.nq.gz
│   ├── 85a07939bb65b0d61abe462933cf67e44d869226.nq.gz
│   ├── 8803c6e1e92eaf4ac40f691cd0eb07f848354f6d.nq.gz
│   ├── 887454e930be537429e0b0a3e293fb28e460fbd1.nq.gz
│   ├── 88aba8b9ca12511aad2ad41c383add66dd2fc285.nq.gz
│   ├── 89489cb352d05ef4170a7da6cd448a8399e151f1.nq.gz
│   ├── 8aace0908e2ce3d96f649aa4135d0ab8b110f68c.nq.gz
│   ├── 8d07a038b14ddffa4c1a57ca66fb1eca2f65dc12.nq.gz
│   ├── 8d148fcca45dc64643c2b1c1003f36c734d038c7.nq.gz
│   ├── 909d12b35d029bdce88d0a4afcc8e17224887220.nq.gz
│   ├── 91bfe3cfc97e54a9a46c4ce1f86bba6b8e1dd397.nq.gz
│   ├── 9426f20734ba49d1040129b695d9da34764cc7ec.nq.gz
│   ├── 94f530b64ffe8a380b7a29c7b86ac46e6efdd8e9.nq.gz
│   ├── 9602d9de267b5ef03859f063ed250f5824b194df.nq.gz
│   ├── 966d4510b73e2af42add598cf83bc9ebcc81afdb.nq.gz
│   ├── 9b8fc6c0947ed7fdaf9cb24b463727f1a5c90bd7.nq.gz
│   ├── 9c72fd1d35623b2f7935d1fea870b0948b57b691.nq.gz
│   ├── 9e5415ef08e2b595c70998d5c4f56bbc2af5bbb5.nq.gz
│   ├── a4190e2f0e4a068b3c48af8552b2e3847fc9e7f3.nq.gz
│   ├── a4cef2e07ef5041011c15c0b63847e5ae1c3188d.nq.gz
│   ├── a68b6ad3a67146296e485b3ff40f0017c38723c1.nq.gz
│   ├── a7162b765157959b5952135e68788f7d891f3ce1.nq.gz
│   ├── a817ae0f1ceb0c00da8777b81a12228884e5d8aa.nq.gz
│   ├── a910ba1914fbf0c43a3eb86b0034e87dd922eeaa.nq.gz
│   ├── ab8d55a9ad32872828a574c574127b0cfb921709.nq.gz
│   ├── ac27a84869a2cb5b416c12fc1fcf57aa6f626958.nq.gz
│   ├── ac44f228b611dda9cb800cf78a33a6918be9d666.nq.gz
│   ├── adb035afc308bf6c8e00dd8f91b7d0296ef1b1d4.nq.gz
│   ├── ae03626d64ebb95419f6336d312322b62feb50b8.nq.gz
│   ├── aeb02d4e2f2b1aa96c50da83d453bdb8f96e2229.nq.gz
│   ├── b078bd76ab738a4719bd452d16fa684d18ab951a.nq.gz
│   ├── b393fc86cb2d363a09fcb1af22f8920571f96788.nq.gz
│   ├── b4b70b7ccd2b5b359254fe0009d97e68a2718b33.nq.gz
│   ├── b7d677d1031e726f81661ad30769035fe7aeb043.nq.gz
│   ├── b96a1bd6ab9355ebbfd706d96c590a0e3aa0630f.nq.gz
│   ├── bbe924caae85dcb4690b5fcaf481553b6d559b34.nq.gz
│   ├── c07fc71ba24c42d0b5af6f0adcc31092620bd971.nq.gz
│   ├── c3a536ede1607f94c508d66c007eef471a50e72e.nq.gz
│   ├── ca7e5eb3f3affed812dfb26d20aa49a4148c1fc9.nq.gz
│   ├── cb9fae3e5b0c43c94c1c83633a4b562bf84a4fea.nq.gz
│   ├── cca4bb2e9d5706da9f54a118ac256405d5698975.nq.gz
│   ├── d1fc67ac54f31acb859f03038d6788ec1ddf33ef.nq.gz
│   ├── d28fbe7b226ea8ab31f89e460772b446241ce42e.nq.gz
│   ├── d39a411ca79b6d2d08fe4c8e584ff1a0e6850d11.nq.gz
│   ├── d4a2c4405ec2e962c521a13af91bf5f7098a62a8.nq.gz
│   ├── d65734b5fd5a92137957b3a3a59a3084bcfec480.nq.gz
│   ├── da78a5e6ec1419f05de4d93a029e13c0e6cd3f21.nq.gz
│   ├── dd16044725e9fe68bf026392779e0c1c244fda54.nq.gz
│   ├── dd36db7aad226a19a4572d29da7c8049b4a18beb.nq.gz
│   ├── de934e3848cf9e2563ab40b2115533170666755d.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e1f676c0977988101f60f5e738e4d4002b4c0e9c.nq.gz
│   ├── e40646496a1d73fbc3a4e2ad8184dd2520d07ea3.nq.gz
│   ├── e53999d13003cb909e899579d528db5580abc36b.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f06335215e86d1f886c812a1c338d180f1c3f509.nq.gz
│   ├── f14bf2b3e57ced6d01af2b2682a55b493417085e.nq.gz
│   ├── f17fef834f0767c1608928ac2a3df9461a243544.nq.gz
│   ├── f1ac4a229d8a36bc23d5a9a061263c00ca644d13.nq.gz
│   ├── f1c727a54c3661bf0ce2291232e0c144401aa45f.nq.gz
│   ├── f1fc10921be2da03687ec9c248941fcdbf113f1c.nq.gz
│   ├── f2a4d870eec1d069cf8bf454a06b25c4383f78ef.nq.gz
│   ├── f4e8eb4bc74c83371a0fa8d702acf1305921272a.nq.gz
│   ├── f85fc93f1071577e62abe661f9e6275c5f185a4c.nq.gz
│   ├── f896f01139e503abaef1002364b54d03d814e8d2.nq.gz
│   ├── f8a54a9248de6c2741e7edb702537bf7f40ed8cf.nq.gz
│   ├── f9d6212f287323a057de162a90980920635d000d.nq.gz
│   ├── fa49e3483b60524cad55de285987ee4f59d51018.nq.gz
│   ├── fc94c5c8de99bbbc481975a0a94d9d178c50d850.nq.gz
│   ├── fca46323ef23e7a93147ffa4ab7a80ee975f7403.nq.gz
│   ├── ff380b5961a05fd7f3fbc392a03cc6b882b587cf.nq.gz
│   └── ffaf47ab0d473360b1acdea52d971d74af5ac57a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3182e84bff998789f8bebcfc2cee7f3c821a4762.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 140 files
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

[corteva/rioxarray](https://github.com/corteva/rioxarray)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
