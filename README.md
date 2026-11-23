# Repolex Knowledge Graph of google/re2

RDF knowledge graph data for [google/re2](https://github.com/google/re2), parsed by [repolex](https://repolex.ai).

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
rlex download google/re2
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4286fd5bd9412a92b1392775034a6a197da8c36c
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 4286fd5bd9412a92b1392775034a6a197da8c36c.nq.gz
│   └── repolex
│       └── 4286fd5bd9412a92b1392775034a6a197da8c36c
│           └── chunk-001.nq.gz
├── blob
│   ├── 0292ea00a8b8feee418084480c12aec735d1148a.nq.gz
│   ├── 06ed88d81b65339b957066c5769072175ac61666.nq.gz
│   ├── 0754006fecfd199e34ff2a69f0882b7d1f3d778e.nq.gz
│   ├── 0780d005b1d316afe3877376e3bfec642f07847c.nq.gz
│   ├── 09e5ec1c74c187adc8fde6c74308c3492ef31f77.nq.gz
│   ├── 09ffe086b7e172cde095f09d1c27dd8d5d27b781.nq.gz
│   ├── 0d6f5fcbad6b84b5f7dae9468da62e70539d901e.nq.gz
│   ├── 14f629d4a01999df3940a3ce533a576180d75e52.nq.gz
│   ├── 151525f2d64966ea5ed7c0a1faeb475f5a075962.nq.gz
│   ├── 166652a2dbb37993254357a3415b1b8ad853b063.nq.gz
│   ├── 1891b14a7a13abaf4292432b271f6b637225ccb2.nq.gz
│   ├── 1a1c84827dafbaf9fbc860eff3ae1ef58608c56e.nq.gz
│   ├── 1ee2e2d4c291481054c4937d17f5b123550473af.nq.gz
│   ├── 1f298ce95cdc44e2bc3231c030b95eae61584c54.nq.gz
│   ├── 231fd348563b3343351ead69996fece15f498fb3.nq.gz
│   ├── 28d833abc4aa6b2fffe5b8ff268793ab39142a3c.nq.gz
│   ├── 2a8d7dae1f1ff8ee6d01c99e7f5d58ec7311e596.nq.gz
│   ├── 33179fdeb8110759fed886a1cdd4e3a2711a3ba9.nq.gz
│   ├── 38a0b87ccb26a9ef36899c78e0ac93b1f84ff733.nq.gz
│   ├── 39ba0e93f2df613b6aa3856ebd7f6bca6321d28c.nq.gz
│   ├── 3b54a85c07176e63170d95cc5b990b07ea343f6a.nq.gz
│   ├── 3eb8056db0d13412aa8ff1e903fb5304c8a066aa.nq.gz
│   ├── 3f43716b451c38f3164fac390ad6e9b566625a31.nq.gz
│   ├── 3fe419ba3c72c92780683c55205a5ca26dffe1ab.nq.gz
│   ├── 41923f314205436eb6c9f746b3c7003918722282.nq.gz
│   ├── 41f65a3561dbe2e1918335195318d9b89038ca98.nq.gz
│   ├── 450d1d749ce4df85c63a9df9f780c97bc9fd522b.nq.gz
│   ├── 45763a7b26d3a266a7c336c4fe7fe42782080e35.nq.gz
│   ├── 46874445816916a34087cf95a87345c94f595351.nq.gz
│   ├── 49cf68601b5c7ccda50e735701e6405a524df3c1.nq.gz
│   ├── 4acad68009f9a677094ad31d465077b6c2501053.nq.gz
│   ├── 4b00be35899c1b7d95771760b7ab791ce78321d8.nq.gz
│   ├── 4e7f4492e6118fa24e8c52f2aa2dc39fc5f61929.nq.gz
│   ├── 4f88493f5e680a89deb7a2012816f30d3b467c73.nq.gz
│   ├── 57256e415909ce2f9f4b3b3a8c1011fb60309ea6.nq.gz
│   ├── 59be5ea0af4d3b30bb3224bb3664b6ef426162dd.nq.gz
│   ├── 5caed925cddc71aac9df796d206d18a50ee4d0b7.nq.gz
│   ├── 5cddd2334602f72cc024a350505146bc4a52f4b5.nq.gz
│   ├── 5e586f1fec9309a87f2dcc999a026e539a88844e.nq.gz
│   ├── 618a276423da9ebba63a299b5103564f0ea82133.nq.gz
│   ├── 6ae22907db8216224c25309584b2598d5990b26a.nq.gz
│   ├── 6dc6532189768487a092d153c27db278e6f68710.nq.gz
│   ├── 727bea5f1126530d7829f2343371de01fdbdf196.nq.gz
│   ├── 745364b3c98e30d309fe00cd9dedd85f49ee8b7b.nq.gz
│   ├── 7525e5fe5e32c90e08ef755c84e3a626629e7a88.nq.gz
│   ├── 77099044431e32be5fa2622afbbbecdd0fe4b77e.nq.gz
│   ├── 782378f6e9fd1e2b6d8d61d45b4b2b8cc38ccf1a.nq.gz
│   ├── 7931cf911e4c4d00179b22e93e23578126a246f6.nq.gz
│   ├── 7f617a9d02d7c2bc38fd4f5adae2535cd5eca289.nq.gz
│   ├── 803adbd4231acb6910399688165d460636f496cb.nq.gz
│   ├── 81901b07321fbf03ef1a2e617fe27818c5e2cece.nq.gz
│   ├── 81b564ff9868bbbd19c0fa1ef8ae8cd08a88abb0.nq.gz
│   ├── 825b260e48482b3160fbb17bdb88990fd7c852fa.nq.gz
│   ├── 829659d6794c15dcf26b9b5ac8114420906b4fa5.nq.gz
│   ├── 82b4f5974578a97455890ac1069b6fc3ac21ab5d.nq.gz
│   ├── 85b42972390159f8ef9286417485f0d252ce7c74.nq.gz
│   ├── 87f84750b33b8ce25fbbe7af14d7a93b49e1082c.nq.gz
│   ├── 882b0e2f34b3ad266d06dbd7fe47bd63e5c9cc84.nq.gz
│   ├── 8f34b9e18bf66952c17f61bc4b3ff7dc1d5bf55d.nq.gz
│   ├── 90071bb0f7b75c1eaa378304603d2bb1b2d2470b.nq.gz
│   ├── 906be0c8c780de639f982689a421564011737dbe.nq.gz
│   ├── 913aee9529357fa728a685f834c316eba66cd1ca.nq.gz
│   ├── 930b3896e21134899ddb5b93df3b66aa5daaa635.nq.gz
│   ├── 933798995b8503acaba2dd9a08b638e3b507c8f4.nq.gz
│   ├── 940412a113fd5974a8e308816167ba7b58ac420c.nq.gz
│   ├── 946962b39bf56faf9a25b7a9e596f08de7a675c7.nq.gz
│   ├── 985016b5b6887cf4352aa55349c379e20c8697e8.nq.gz
│   ├── 9959f7cb0eaecb2097b57f51f27cef84140cefca.nq.gz
│   ├── 9cac1185ac65106e53ba7178d828bce82e8f163d.nq.gz
│   ├── 9d3954424a11d9dbc758a4af01a353aab8df72af.nq.gz
│   ├── a094cb4ff6861bd5f8b44b84e8ba436f402c955e.nq.gz
│   ├── a40e756c4ef2e6b5b331b882aa5635fd42820b4e.nq.gz
│   ├── a45e5b58b318aa9cf10d211a70cfb4f27a84cdca.nq.gz
│   ├── a57f700bcdd4675ec9e562d60a3dcc9de92710b2.nq.gz
│   ├── a655884d703ce8fa1c4bdc81d4c33a63420e5f07.nq.gz
│   ├── a671fe2cf03c9609f0a783c7e46eb9cafcc07f4a.nq.gz
│   ├── a9abd6919c83f6926d5567c1729eb9b17a1fa759.nq.gz
│   ├── ac0c69d7e77fbb4d88a2aee76539f7006a5731ac.nq.gz
│   ├── ad95d6c264a9e6c44621699e1d993c2476cdab3e.nq.gz
│   ├── b0759f7c7d7334e37afb35f755e34bd75ad62e49.nq.gz
│   ├── b1273d9f627aeaa07a5580fbf74ee89aa297e0e5.nq.gz
│   ├── b1761ed9378594673830029a32a82d219758d940.nq.gz
│   ├── b27b891bd49906f30bb73dce22e35586c00121e9.nq.gz
│   ├── b5199571672b18611e2aab774a46ba7d56a6d15c.nq.gz
│   ├── bce76fb912b849fad6a4d1e8b7b8ae2e4fe81f5a.nq.gz
│   ├── c0b93e1f4f0afa979541d288ebd1c41af3e0b3ba.nq.gz
│   ├── c12a482dde0317054ed72d6cb360aa09e6044fc8.nq.gz
│   ├── c14ef29c0356532e4d8f4133125de13b9a56c84e.nq.gz
│   ├── c4857ff5e5512635089f003cf8fd44e881224279.nq.gz
│   ├── caee6afb6b0051dabe19e7edf7f393752de42162.nq.gz
│   ├── cbe822ad93bf6b4b54a80d8e8220984054aaeb16.nq.gz
│   ├── d076b39b17892ceb7745f08da00d6725afaaed71.nq.gz
│   ├── d2c136a3cc770b057d0facbe4b14bad6a863855e.nq.gz
│   ├── d30d281460e97ad2a2a62e29cfa180e9c5a2e46c.nq.gz
│   ├── d9de2821d5f86a248670e70fab52f7f458ca1b00.nq.gz
│   ├── da06f85a335908e780749b0c20d61faadf7348d4.nq.gz
│   ├── de703c00eee73cbfab248d38a4264a24aa4212a9.nq.gz
│   ├── df4989479a2bb907b11455ab796c67526e94ee6c.nq.gz
│   ├── dff5e49de9b4d0abd9e220d226fc5c16e55532b6.nq.gz
│   ├── e1be1a93da51ce7840405634a1374743b049db80.nq.gz
│   ├── ed0d509dc327c37c5ab6d8a68662c720e210a303.nq.gz
│   ├── eea3bd73484b2a7d4a7d0b22b48888f3d5ffad78.nq.gz
│   ├── ef8f59d363f57ee5bc660391c94aba1f96b1ea88.nq.gz
│   ├── f234e976f40de79cf4b3aa9703371ecf8ab19fb3.nq.gz
│   ├── f389f08c5786a4562b0ee3be00053585a55b5cd6.nq.gz
│   ├── f4b2e471e4c3b988cbcf7657e3b73a0b89e59f60.nq.gz
│   ├── f5d87a53342c508d38ac221950a2febd1ab49aae.nq.gz
│   ├── f6899d3d274f5a400a8709f8a947340f336cd7b8.nq.gz
│   ├── fbe92e65d13770d7c885f95c7895b940fe1f29dd.nq.gz
│   ├── fdbc0b2c74a88d997cf20961feb3a63856788423.nq.gz
│   └── fe199c6629eb4d0aeaa6cf15f2d7249e047a1174.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 4286fd5bd9412a92b1392775034a6a197da8c36c.nq.gz
├── filetree
│   └── 4286fd5bd9412a92b1392775034a6a197da8c36c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 121 files
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

[google/re2](https://github.com/google/re2)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
