# Repolex Knowledge Graph of UnityCommunity/UnityLibrary

RDF knowledge graph data for [UnityCommunity/UnityLibrary](https://github.com/UnityCommunity/UnityLibrary), parsed by [repolex](https://repolex.ai).

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
rlex download UnityCommunity/UnityLibrary
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9d05a5340d9e1be8473a96a4bc0e1321b977f6ef
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9d05a5340d9e1be8473a96a4bc0e1321b977f6ef
│           └── chunk-001.nq.gz
└── blob
    ├── 00d617312bc2475696981d7cacf81b4f78f70d3e.nq.gz
    ├── 00dfbe675fd6f74db21c174fdd973b7bc44a8fe0.nq.gz
    ├── 01540e4225d7d62d857b17fab5163d58bf4a2caf.nq.gz
    ├── 0279a2300dcedb6d45972d698ca39f88e2779d93.nq.gz
    ├── 02c51af6f46dc415eacb02d44d410cf865d25955.nq.gz
    ├── 03e279926acbcd944a03ac0dc219c248cbb56a80.nq.gz
    ├── 04399dd52fda84ce97f992b4bac374932d3886d2.nq.gz
    ├── 044c4e07c1a8647d4f97d05322e2d526aa655a4c.nq.gz
    ├── 053ace16e3b67c70d1e13cc778b46833f933c878.nq.gz
    ├── 05493cc56b0c1536621b484c3394a3e7c93eca7d.nq.gz
    ├── 058aacaf7ad7ebc5cffe15a6f8d48085508c71cd.nq.gz
    ├── 05f683a315414ac79d58d92fff03c875fa13e54e.nq.gz
    ├── 066da8d2588b1afebf962ef5d1083690e5d10c96.nq.gz
    ├── 068da7ccc4b7e09878d4908b4f995fb69df7626a.nq.gz
    ├── 06acb2e38b6313c9bb89d82e6c7d04a0fab8cb1a.nq.gz
    ├── 076fdceb48d4ad4922a84810db1c6f9a19275607.nq.gz
    ├── 07aa05165bcc08abb56cf6115eec3ad740b185ce.nq.gz
    ├── 07b07e93d813c129dd2afa9e8bbc6b08d255f130.nq.gz
    ├── 07b1323f2b1af204374333cd8690fd16be1723cb.nq.gz
    ├── 07b343c1d896aa31200c785a2f40d6f1f2e650de.nq.gz
    ├── 08253ed706546b5a16975bb93e59c315e9de1d0b.nq.gz
    ├── 084224f28a2fd0470cdc67226a19f4b3a391a600.nq.gz
    ├── 08e2df8d2633b322d9a7941e7026edff5455fcc4.nq.gz
    ├── 098c878a397b83e16eb78b1a57d63c96a8650dfa.nq.gz
    ├── 09ee286a45342d4abec7849fd1e88e84a69a0fa0.nq.gz
    ├── 0a5de2b489d5cb158da43fb4d170cf1f43580a75.nq.gz
    ├── 0a6d2b130ea00f1441a5808bd17aca1ea06af374.nq.gz
    ├── 0c46b6beadca01614e0783e69542836931aa1f8b.nq.gz
    ├── 0c9ab3596ee4ba5ff3789d5c4493216bd13b1682.nq.gz
    ├── 0cc0ce29980d2cef6fad5cf0d41d5d28d83b321e.nq.gz
    ├── 0cc89a07060030addeeb075d95f0ea9561ff845b.nq.gz
    ├── 0fef0efcfc1d8b226b64919ae2bb03ba1e0d39b0.nq.gz
    ├── 100a5b638652185bd704958a1acf5727ee2b08c0.nq.gz
    ├── 105bc74965ad2429e456efe15f18320c75ee9db7.nq.gz
    ├── 109bcdc9b41150fa0d524ca709dc1c22d30ae037.nq.gz
    ├── 11230f2a73eb4462ee64cc5a5e6d274c98d00eff.nq.gz
    ├── 11d902b8fd4f7297e6e33deeb1255ca02f990753.nq.gz
    ├── 12b4f5d886665743dfd823f23030e48915c8bca5.nq.gz
    ├── 12bf6c877b327093c9800daa98862802120b444a.nq.gz
    ├── 133c82f3af370f11f7e52be2a38d1b03e7a54f0d.nq.gz
    ├── 13e210fe43a91e8af7b89b4a2ab6f1c0a3b89a77.nq.gz
    ├── 1479c95072cadd82b0da4ec62be3dd0b899aeb36.nq.gz
    ├── 14edfa10eaf143b791102d39b227ba4afca919bb.nq.gz
    ├── 152989ef2e5474abd03b6c87b80ee9bba23fc267.nq.gz
    ├── 16d5f715ada0cde1fae0dd21104fb7405d718469.nq.gz
    ├── 17ebebb2304b2ca6b9aa0f53b9ace659817a3eb9.nq.gz
    ├── 1803923d8929c824525425f3702f8c85dc7f3311.nq.gz
    ├── 186265bcb20fed3b8f5af743095116f4e80ea37c.nq.gz
    ├── 18d2cfbd8788594a24ced999d95b31fdd7d2da2c.nq.gz
    ├── 18e75b1fc9cfa2572e1c7cdc11baea7d7c48a986.nq.gz
    ├── 1946cc36d84a9e381f5f5091f33742bb80affcd1.nq.gz
    ├── 199d1ef3b8fd23f9123a924dd19bbf7cd200b4eb.nq.gz
    ├── 1a5a1af194a9cd1a6c0657b3d64ba76bb62c23b8.nq.gz
    ├── 1ac886c9e4dbee2c7ff60c860a1baa760bd77354.nq.gz
    ├── 1b63ced817177cc37f805d5fd167ae99d7fdf329.nq.gz
    ├── 1ba400c92d60f93079170b96295b076240e1a37a.nq.gz
    ├── 1bc55dfd48f5855074353e0b1baaf33a3d33fe40.nq.gz
    ├── 1bd5cc5a1b7bd6efe4477fd7b9dde0022867af69.nq.gz
    ├── 1c85effc0ec8ab10c57d88721213bd8cf827e3f1.nq.gz
    ├── 1ca44cd09156616c95eadda1eee070d547e73e7d.nq.gz
    ├── 1ccc0f1a253d7a8b093ff7289c9cfd857273b5eb.nq.gz
    ├── 1e3f99d9473249af1029efbd425ae8c6a7ee9b08.nq.gz
    ├── 1e5a67620061e7893f44ae9c5a4a801afce58db9.nq.gz
    ├── 1ed747bd2aecb628aaf83b21a24b68a512bc5eac.nq.gz
    ├── 1ed7c16191f8c4e86711316ba1fe5907e26fb04a.nq.gz
    ├── 1f0217136fb749d62855032dda53c646df71f91b.nq.gz
    ├── 20d47a7fddaf819977e5344c06dfe4246b926051.nq.gz
    ├── 216ef4982c3b3c2bf9143865e89b0a44cba52cf9.nq.gz
    ├── 2176e9d2913ff98060642843308d3a9bbba79dce.nq.gz
    ├── 23456398abab5983befc23744afe7622cfcdb4a4.nq.gz
    ├── 24cd5ab59cd45f7a591e9757276c7a0d350b3bc3.nq.gz
    ├── 25ffb0f77c92035194d8d74a8256224d4233afeb.nq.gz
    ├── 277e32011b1481ef5e0f3ff612d82f810d1699ec.nq.gz
    ├── 2864d248704b35304bb6c9bfdaf880a511cf1e98.nq.gz
    ├── 295324c221d2aba043a3d0deb310554d41345cf0.nq.gz
    ├── 2a547fe7f65f56b94ad20b53f47eccdbbb74ea80.nq.gz
    ├── 2a5f50578cc1223cc7f1da9930ac3c68a6fdb167.nq.gz
    ├── 2b7093020b5c59f42d9e89c91734a37e0090a43b.nq.gz
    ├── 2c456fec1e0e53a67ba8dfac18b58e05eb4309c2.nq.gz
    ├── 2c5efc0bbf377262daad8eaad6d347c79d97d2bd.nq.gz
    ├── 2d208e8f0d371527fd22dd0997464db6d2d2e271.nq.gz
    ├── 2d338b37e35343c6da257dd197a5539c4382ca68.nq.gz
    ├── 2db28877d4ce07cca1acfd311bb6ff34fd67303d.nq.gz
    ├── 2e312da269521f479315587717c1d98195f346c2.nq.gz
    ├── 2ee9e8ad556c2dbf7b8057af1fb3858b8e869312.nq.gz
    ├── 2f85748873a22e5a844febe2b503d9e6e1f58974.nq.gz
    ├── 30a3e03f7401f2cb35a6682d2a883759d4a92046.nq.gz
    ├── 30a9f442a2138ab4948a5593c9c0ad37532a3f73.nq.gz
    ├── 30e71470f60e6d5158acdbf1f167d83baae92105.nq.gz
    ├── 3258a03cf0c38ac75422408023b4484b729fed77.nq.gz
    ├── 3290be2b479eb73891a5840b2c6b2dcfba15fdcc.nq.gz
    ├── 33663ed46fabd83d98d506844be0b0276608c373.nq.gz
    ├── 33a608c12aa41dd5b5be16b505deaed3bf12365c.nq.gz
    ├── 3525df88d97bc2a5adf10c41f3b699feacdd3ecf.nq.gz
    ├── 35f7ff2db4ad220c07c01f4cfd42b8cf6c4a6a69.nq.gz
    ├── 36b62d4089f10fdd8dc58d08e90b9f3f2cc247db.nq.gz
    ├── 3717894c090e26b7fbb9dd70c4f06c049bcd0761.nq.gz
    ├── 379c8336922788b38777f1a6224250f440a4f878.nq.gz
    ├── 390ab63c9cf77224d6a95955c872ca04b7809e5b.nq.gz
    ├── 398ee902b3f12ce5a02f6d0c40ca41297e4be034.nq.gz
    ├── 39b62d01bd365770153d9123ddd5f92cbefa7122.nq.gz
    ├── 3cf25b0dc8ed36e4b9dbbc55c1ab6a97374e25b9.nq.gz
    ├── 3d0c7549870fc5eb7bbb176cbdb9442de7ef1d1d.nq.gz
    ├── 3d568851eb7816b657550911fdf8c8d67a0774b8.nq.gz
    ├── 3d6d802110dae1945f3e26c8e8ed09528b84ccb4.nq.gz
    ├── 3ddccf29a0faffdaa5c0a18b2f160193ffa4e846.nq.gz
    ├── 3dfdd914f1867141f8504e419b9dbffe387e7915.nq.gz
    ├── 3eccce9c3bb3e594381999773228249a2ae398e3.nq.gz
    ├── 3f8f80c8e9e2967f242910235f8e7cb63c7ccabe.nq.gz
    ├── 4048b51eee4a8bb18d7005a033fab2bbdb386818.nq.gz
    ├── 406b9bb7ca87fe45fe130e81110567c13550e9a6.nq.gz
    ├── 40bf0d0da327bbfae90c7b11183296fb15f0afbd.nq.gz
    ├── 4130726a65746e39c6448366b70edf5e8df18a3b.nq.gz
    ├── 41759f96fbd310cc8e7ef2f09035971961a4b3ba.nq.gz
    ├── 41e518a7c5590ba87266b0f9f860882fc5a6d006.nq.gz
    ├── 451ceae37230b9b0fe884389fcbf5e82d7d3be89.nq.gz
    ├── 45734bfff5ffabf84212359e2a70df2c2a643200.nq.gz
    ├── 45b0b1f14858e5e0310f081a10a55c29395eeb19.nq.gz
    ├── 45f96a58a5b5f781dce2910a009d26c5dfab46c0.nq.gz
    ├── 46642b07e9c5619215a38985acd8166bc8155a56.nq.gz
    ├── 46ee47b9b596f3780dc328b3e92d1441b682b45a.nq.gz
    ├── 47e8cbc65a2ca1e108cb5c27fc38fa6f6e58e18f.nq.gz
    ├── 47f7bd5658f4e2e81b0fc419d3536e73ffea47b8.nq.gz
    ├── 48a88e6119048b267558e78450ee5efbf912d52a.nq.gz
    ├── 48e381b6f7ebdfa528ccf0047687f6ba1de908cc.nq.gz
    ├── 4aa5605cd96af27213ffc12572a60b329b121bfa.nq.gz
    ├── 4ae3cd670b44482ffde19d4e61f6c65afba2c9d1.nq.gz
    ├── 4baf055f961c72ba914b4016104f0c639c7787de.nq.gz
    ├── 4c59b67923c9ba2d8272908ed74b670e2d526db6.nq.gz
    ├── 4c9728c03293b512e387deecf2080dacdff23ab2.nq.gz
    ├── 4ca98328ac0c0ce76059400c2786429ea46c872c.nq.gz
    ├── 4ea8c7a7f4268cdc1787a410bcf689adb2eb4dfb.nq.gz
    ├── 4f29603b75a19bff70e6b75497d226dc3fcfa9a2.nq.gz
    ├── 4f5aace899c78f9a12a3f6f75b836ea214dea933.nq.gz
    ├── 4f602b9f99a1c2206e89d4bb974eeba0bf6d051e.nq.gz
    ├── 4fcb143350e41fcb9fc2cd81bc907f11f546d065.nq.gz
    ├── 50206f2957a2e46526b8c4abdb6e59e7c95d6d22.nq.gz
    ├── 5150edd5d33a69847dad38bbfd034af8a80ed462.nq.gz
    ├── 51f326b3d14769b8f44281e791b6e0f2ce7795c0.nq.gz
    ├── 523b38775d7b66364c2f988ccfdaefca1a8bcb2f.nq.gz
    ├── 52d2f55952d976258fa7bfcb845dcda904868ff4.nq.gz
    ├── 5330ceaa8402478fbe87f6e2298a452dd444588a.nq.gz
    ├── 539fbfa09ea2fc5c9dcbfdb2fb31089aca2e5747.nq.gz
    ├── 53ec44650a2f22539f078f603f7b6117711696a8.nq.gz
    ├── 5406c35c321b6b07b70ab3dd3ddb086702b03c2b.nq.gz
    ├── 560fc901cfe8ef24082db7e2a95ff76f03c6aefd.nq.gz
    ├── 567d3f21be9718de6d629174206e3a7443889099.nq.gz
    ├── 57ac59649cb5e730de03824af805ed8f672dc51c.nq.gz
    ├── 57e8c96ae284e0d3289fdd3bc7884d2fcd9b7246.nq.gz
    ├── 57ed2008b5b7b8d81545ee32142d25c497de90a4.nq.gz
    ├── 5931d497d337623e4f16adb2ea60570d4fac1ab8.nq.gz
    ├── 5bb330d4848fc06f81b28e080fb64ab8203f3ca3.nq.gz
    ├── 5bd716ff410b43bcf86a15bef347017385c30bbb.nq.gz
    ├── 5c43b888bc7cd69d3df522561a508489e087c702.nq.gz
    ├── 5d7f38cd3db79367203dd28b4cea0c0bc80622a1.nq.gz
    ├── 5d7f42270756d66df6949ce98e9263988b891289.nq.gz
    ├── 5da02113ff846973cdfdea5f64cd255c8c54d3ba.nq.gz
    ├── 5e5533c5b16d8d114ea361853530bf4e7a193503.nq.gz
    ├── 5f0ee7ad4960e286fb36df4cd1ab23d142b428ab.nq.gz
    ├── 6166d5354310c6cb1346ee17f803dac0bb92a58f.nq.gz
    ├── 61a16ba078d2c03a7416579245c4dcf61be7dceb.nq.gz
    ├── 627112c235dbc2628dbfd9ff8d380595a49b3018.nq.gz
    ├── 62a99e3922e96eeda4e59d3bb78bc7bfa7dc2410.nq.gz
    ├── 62f31dc57010e447e9546bac0e7f39191299d94b.nq.gz
    ├── 63f3e20e7d2cc1b2fbdc35383b33de16c5a93fcf.nq.gz
    ├── 64b1d974c77aba78165260b67833f0e24b526614.nq.gz
    ├── 652e0713f7bfdf6b4e2c96a47669af60e1af55c9.nq.gz
    ├── 6543586c818d4f1ac6b49a6c2719be0029f729ec.nq.gz
    ├── 664c8890c9c84282b65d11360ec49caa29df6dc2.nq.gz
    ├── 66a3390fb3d81960119eda528aa00420df33f955.nq.gz
    ├── 66df9703218d1374ec44b6cf01e62d2e85c248e0.nq.gz
    ├── 6731a47ae1db4465405949184605df02338f0b85.nq.gz
    ├── 67c55e7c9a5941730aea204d5ee31fb2f2ac7e40.nq.gz
    ├── 67ee210d21c6be07bedc1f14cc26d4f0c854ab75.nq.gz
    ├── 69020216e770ed3f194dfdd7fa366bc80e9e5634.nq.gz
    ├── 694024f235f06d650f2d518958cad41ddc957ece.nq.gz
    ├── 695b61d1a871fd9b04a1956258c6225f8065fe58.nq.gz
    ├── 69ac2e2700b19f1949630e1edfda4dce1fd97620.nq.gz
    ├── 69ba7a91ae490e2de4091bf96206f8632874cd7c.nq.gz
    ├── 6aea04064c95ef265f6663c5f96448bf214e0237.nq.gz
    ├── 6b0b99f3359156405978f985d7d4b4b7db5f782b.nq.gz
    ├── 6b58cf5d19b7de6d55cc7e4c5ed485ae6ec0fc1b.nq.gz
    ├── 6b8dbb7d1b58648b52567c6ece1c76ae7a045b61.nq.gz
    ├── 6bcbf0e034a3389d005ed4993ccc8903ad122190.nq.gz
    ├── 6cc6cc7196150267852e8647bd26a7c0f3aac1f4.nq.gz
    ├── 6d16785f6be01859c0dbd4b391e1aded8a43ae10.nq.gz
    ├── 6dfb806aa44f46773bd44d0d0ea5961b06781d49.nq.gz
    ├── 6f046003eaa636f3b3464d292ab05b613ca1c0f8.nq.gz
    ├── 6f472aa04a93fc77ce0a2d10c161d96d77c6ce1f.nq.gz
    ├── 6f5c1fa749d126ae8cb51bcc7e7ef064f0b95ef0.nq.gz
    ├── 6ffbfbd898235506e3f77985dbdfbfafe02007fd.nq.gz
    ├── 71aee8831c3954a036e58df99e50514740bcb4bf.nq.gz
    ├── 733ac03b73478a2dc0877c2c27cf650f88bbd876.nq.gz
    ├── 73e20d183b99382f8a31403ecfe38010f79fddb9.nq.gz
    ├── 73f3ef5b195ffbe5befc5db6e9205055332b8eca.nq.gz
    ├── 754da057b0bffb209a62bacd465335bbac094518.nq.gz
    ├── 75af3045e620462e3a5ae486f892e21089643ae6.nq.gz
    └── 762cc6b30dd145f494b48aea0befd51198c2fe4d.nq.gz

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

[UnityCommunity/UnityLibrary](https://github.com/UnityCommunity/UnityLibrary)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
