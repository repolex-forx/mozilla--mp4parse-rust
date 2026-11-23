# Repolex Knowledge Graph of mozilla/mp4parse-rust

RDF knowledge graph data for [mozilla/mp4parse-rust](https://github.com/mozilla/mp4parse-rust), parsed by [repolex](https://repolex.ai).

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
rlex download mozilla/mp4parse-rust
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e133798fb00969cad0561f0e92291d2d02803497
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e133798fb00969cad0561f0e92291d2d02803497.nq.gz
│   └── repolex
│       └── e133798fb00969cad0561f0e92291d2d02803497
│           └── chunk-001.nq.gz
├── blob
│   ├── 0d8a48b63ced1e8edd95a5c94465b3eea7899e2b.nq.gz
│   ├── 11b539230bb4a33aecf3d63d3cb2bee33453d014.nq.gz
│   ├── 1392b304f80b43cc4360eafc954e1ff07463b24e.nq.gz
│   ├── 14629882d0fae3b54bfec7cf2862a54a59728705.nq.gz
│   ├── 14e2f777f6c395e7e04ab4aa306bbcc4b0c1120e.nq.gz
│   ├── 1639eddb3defe430b914adf6c1db27bcf7f7b901.nq.gz
│   ├── 1a47e329fcd5c8eb9ee1ffad2505ad69e125cc9a.nq.gz
│   ├── 1ccbcc43fcf0e2367f476bd56830d1491e1b6955.nq.gz
│   ├── 1da111942e9c0cdb9b2293002cad8ce831a52939.nq.gz
│   ├── 2011e7bb7d508ce95b1c42df9778f6f9f13bb98a.nq.gz
│   ├── 202e03a8974346651786b49a81fd039ff1ebb059.nq.gz
│   ├── 2d59986a28c18db25329ca4a2f4e9e4d7bdabb91.nq.gz
│   ├── 2ee8fa86b3348e810075f1f001b35f9d9dad7093.nq.gz
│   ├── 2f8f235a9b4b826547a387fdb4ffc801d317a9b3.nq.gz
│   ├── 30e2bff887d1daa6c7fc095de0209315e4546ec3.nq.gz
│   ├── 31c7e424548d7583d81f0ae7fd5ef7ffa4fc3116.nq.gz
│   ├── 34137ce3c95c9710e6c0dde1e45d440f9ae61f94.nq.gz
│   ├── 35575095b1de15aca300407e5119a1686847a3ea.nq.gz
│   ├── 3778cf70809300fad186d7fc10d5bf50a6b370e9.nq.gz
│   ├── 3aa4b8f5bbdcfa8a9f5af7e0b26dda26185a0cf5.nq.gz
│   ├── 3ac3175c07a5d5aa9d215ff45b252c68e913ac79.nq.gz
│   ├── 3d998787444ed43fa618f53b63cf9c88f34484bf.nq.gz
│   ├── 40012f2114aa4c236f5716a2d4305c41a8b801cf.nq.gz
│   ├── 40652dfd4934ff04dd524d3dd9941abca0aad336.nq.gz
│   ├── 41cd15b39bea0a48e80566644b4f48909a805bb8.nq.gz
│   ├── 42f9651d8c514985afff0caceeaad1931b37df19.nq.gz
│   ├── 464944f965f26aac1f30fe260e42acceaf83d779.nq.gz
│   ├── 498baa3fb0f09a2042d2c8657b67fc7832cc2c30.nq.gz
│   ├── 51671e0484209be945dec715c554f1444e3a20a6.nq.gz
│   ├── 548b28e4b8f24d414784102c7e54ab5648aec33b.nq.gz
│   ├── 5db21d091bc41d7b0bd9a5f0de118fef576c6eb5.nq.gz
│   ├── 5ef216c63638100690b9e6b1eaaaf1584916ee12.nq.gz
│   ├── 66e632980b444c2631792637634353aca622ddb2.nq.gz
│   ├── 671b8b6585cc8eddaa7c1cf01b8bb1eb67276970.nq.gz
│   ├── 683baa7f54f989b42c096a8eaceba96cfab1adac.nq.gz
│   ├── 68f712092c0d30e9083807c23fadb0b31311ecd0.nq.gz
│   ├── 69f97caeae50d8eb2bea423ccd4cc66bdaa6371a.nq.gz
│   ├── 6baa293ab688a67c1a878755b2667061a5fc023b.nq.gz
│   ├── 6d674ebbbfcc1377bd9778c9816ac110628780c7.nq.gz
│   ├── 6e407560938a3f237dba734b13f533a41aa7f856.nq.gz
│   ├── 740b55cd2779d418a395db939cc80af4f4aecace.nq.gz
│   ├── 795223d5edf706ef7992f02c56e258046103a3b3.nq.gz
│   ├── 7d2ea0dc5255c56f28ebee9c1c60c748ae6a314f.nq.gz
│   ├── 7e8ff7f8146f682942074e0b5d338e40cd3d48a8.nq.gz
│   ├── 8087e7c04e01513482fdedbb866f2ae5f47ea6a8.nq.gz
│   ├── 85aa055fb928aee5fe3be674aba2ef5e7c5d0ac8.nq.gz
│   ├── 8c62e55ecc8c8028fce66de79f1a3e5cbd2ac841.nq.gz
│   ├── 918c9fbeaea78302947c0d5bfc4e7fafa755c953.nq.gz
│   ├── 91c3a4d1c1f7ab0c996eba29094d4b818a4ec79d.nq.gz
│   ├── 99c92a7fef994a9450b59cc4aca0dda1078e6095.nq.gz
│   ├── 9bc5e763094e2302bae73c85fc1b762644da4468.nq.gz
│   ├── 9e04a6817a5015f8782fcd0f65428a55bc0d1597.nq.gz
│   ├── 9fe1e672241766bccf54731219bf03b81ff223ef.nq.gz
│   ├── a0925114d619b8cee7d72961b052ddcc42023a24.nq.gz
│   ├── a2936ac1496626c4a1da2a2e87a4be2c073a77e7.nq.gz
│   ├── a4609aa93e4da55b2d71ffae7627f7559248a719.nq.gz
│   ├── a49f39438d449f024966e89e673642f1df5fb666.nq.gz
│   ├── a65db2d7cfc9d71262a5dc55771509bf6e13c5ea.nq.gz
│   ├── a893f7e1ac9ac00ad80f028c3ecc67c19e49de2d.nq.gz
│   ├── aa44c3b9a187b78c7a7a0a0bbfeb546f6ee3d96a.nq.gz
│   ├── ac5cbdbe85d57dc91f52eff2444ba13c8ac9a5ea.nq.gz
│   ├── ad030a94c5452986421a3389fb4f56f6a62c2662.nq.gz
│   ├── b192607495b269b18e60d43bb7d1ddd286dec3fb.nq.gz
│   ├── b3a9543b4092a962ea5c20593423938e197c8290.nq.gz
│   ├── b3c147903fd930ddb8fac9497e44af2d1a8b6d1f.nq.gz
│   ├── b827aa49aac417fce998e4d5541ddc8dd9438815.nq.gz
│   ├── b9fe1853ffc2049b17d181cf5eb5a43c9f3cfe43.nq.gz
│   ├── bbf272197ded0559151d83ca05375311a36ccc08.nq.gz
│   ├── c09ad1374a4d54caa7c02267ebb3a3e48e5f6890.nq.gz
│   ├── c5bf6ee0452f46cdf9dbcadb819c203fa315f497.nq.gz
│   ├── c9e65a43884593238ec238365fb6854ff67f7ad9.nq.gz
│   ├── caf1b7fe60675d868eb8059bf8afce9b89907f2b.nq.gz
│   ├── cc45d5fbb5464fdd57f09059394594aea1c31bb6.nq.gz
│   ├── ce5dc52247d182ae131fd2e05878ddfd88acb904.nq.gz
│   ├── cebd28bbac905e927bcfdee73f553658e765d551.nq.gz
│   ├── d02ef72424fcb07afdeb1f06086d7f193849491d.nq.gz
│   ├── d576365b6ef551b3ec82215a8a02275a4e6e1b68.nq.gz
│   ├── d6ebe1f177d503f4c93bf8203ae0ce2c6f9f21a2.nq.gz
│   ├── d75e8695895ce76340aa40a463214f2bd671fbe3.nq.gz
│   ├── d80798c15e2951a3849465a7b21f6f86337d5e0b.nq.gz
│   ├── db4aa844b471d300368a71a83f77051972607fa6.nq.gz
│   ├── dd306992cb3c2f421f98b3e9f56f974102500034.nq.gz
│   ├── de0150373455c76100a85ff75489ad6bb90f03d6.nq.gz
│   ├── e5ecbb993bbfe27b3cdc24f2bd5e1ad2366623c8.nq.gz
│   ├── e8442c166c789e2937b7c2d17d7872231f32a679.nq.gz
│   ├── e84ba63e2d1d748a7b7427b009d1f229c3874e60.nq.gz
│   ├── e8ced19127f3487d795c364ed5da006f18204a77.nq.gz
│   ├── ed47ebfe6fc711cc6c053a25df68ef44c86e179e.nq.gz
│   ├── eea6c788a75c3943e92339a3d98e72372df326fd.nq.gz
│   ├── eeb16f8ed80f895e6fc31392305bb3502ac45e80.nq.gz
│   ├── ef609e42813b93f644b26d5cede5ee2beb777a0c.nq.gz
│   ├── f10a33a7fd78345ffac9b17b798a532aa579c78f.nq.gz
│   ├── f46fcb65236222198d8661371699ea2486326256.nq.gz
│   └── fb6335f5631b86d0c6da8c39cab9378fe30dbb38.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── e133798fb00969cad0561f0e92291d2d02803497.nq.gz
├── filetree
│   └── e133798fb00969cad0561f0e92291d2d02803497.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 104 files
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

[mozilla/mp4parse-rust](https://github.com/mozilla/mp4parse-rust)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
