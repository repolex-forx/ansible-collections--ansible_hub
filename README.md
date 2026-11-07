# Repolex Knowledge Graph of ansible-collections/ansible_hub

RDF knowledge graph data for [ansible-collections/ansible_hub](https://github.com/ansible-collections/ansible_hub), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/ansible_hub
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3c113cfa92777c5c575b7b0c742d2a2080ff9a52
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3c113cfa92777c5c575b7b0c742d2a2080ff9a52
│           └── chunk-001.nq.gz
├── blob
│   ├── 00853c60cb0c6aa7b884ff5806146fe54bac5054.nq.gz
│   ├── 0164155b81025416095f31a4732098ec238e6476.nq.gz
│   ├── 04eb2b67357d6a2b5fa62572338e2955fe6ca5f4.nq.gz
│   ├── 0511911a4e9314c1c3a7891386df309b0a850d3e.nq.gz
│   ├── 07c81f98684dfcf87a7fbe29dab3b81f592ac6da.nq.gz
│   ├── 09c6200ae43abbecd094018de29fee9774b73ba1.nq.gz
│   ├── 0a270fc096b72bac76eb122af3a0bb146a1ff462.nq.gz
│   ├── 0d55def02d5cb36ca7254ef13f1cb096549e79cc.nq.gz
│   ├── 106f6d611593ab6d84795957c324bb9056093139.nq.gz
│   ├── 10bdf4e6dfb5b4897dbf27656229c12d643364ed.nq.gz
│   ├── 149c1b1d1c47850c0c72aa926c59ad6616d00f0e.nq.gz
│   ├── 14f811672b7e5144c2d81fa59effe3a57a83aa8e.nq.gz
│   ├── 174ce2d872ec173aa1c409462a6489dbc3fcf566.nq.gz
│   ├── 18acb6e755f659574eef172e4ef6da962dcf5a0e.nq.gz
│   ├── 1bd7e5498315d697b4cd91ae2aa832b22347b410.nq.gz
│   ├── 1ff9711160e8c7a7a058ebca497caeecfe445634.nq.gz
│   ├── 21e622488877ca934af32fa9f32b1c635e91b807.nq.gz
│   ├── 2c4b07973271c8469bf9b16d74272e012a97fb52.nq.gz
│   ├── 2c4b331c9a77e5a96e6fb4833068ee66adc94e43.nq.gz
│   ├── 2f4430d860c1b30037d30320515c0d7f8d583718.nq.gz
│   ├── 37209d35a6de88f802c0315733f549b23ea6de92.nq.gz
│   ├── 3b2e58a2112c0b791d0b39cc5631155bdbc83eb0.nq.gz
│   ├── 3c09a22eb7269641a1bef957d535b8bfbb7bff8b.nq.gz
│   ├── 3f184b96eeadd8a4345f1d4840b0a585ef6c9516.nq.gz
│   ├── 42716483020492380ae92f1de10c799a0934918a.nq.gz
│   ├── 42f9b88a300b9727f57e6b06e43245c0b4ceab29.nq.gz
│   ├── 440ad1a580453a4568901530119c5398b7943536.nq.gz
│   ├── 455254ce8ebe56d20f9b3f2c0cf0814641770936.nq.gz
│   ├── 45e5ac24ff8ed9212a02ea8c3ebeee642b8f669e.nq.gz
│   ├── 46c3ced0e16f514d7bc6e00fb8815e39b7d32892.nq.gz
│   ├── 499a1d6adb8675b963d42153a6ea8a6cc6671112.nq.gz
│   ├── 4a029d76b994ffa10f27752a2db5b7c41a5c686a.nq.gz
│   ├── 4b822afe462146430bc06a5ce82d94e25bd81d4c.nq.gz
│   ├── 4d0fbac093a0844848684fad603d7a2bf69191e0.nq.gz
│   ├── 4d4cf8c67625b30507020ea5f9c55fe5ac1f69fb.nq.gz
│   ├── 4daff4109557e5e9d3750785728ebc1711e5f653.nq.gz
│   ├── 4eb8a3fb4fb4e1da505f9b0cba3b78027f03acc0.nq.gz
│   ├── 569e59c5dacee06a45ee025d7f771c3b8a28932d.nq.gz
│   ├── 58320f53a2264287119780377fc186366fd050d2.nq.gz
│   ├── 594036d96093dd4036181323dbf837ef2680e9f0.nq.gz
│   ├── 59452100cd6e15ccb71be5f9eb9a46029e822259.nq.gz
│   ├── 5c4b109783f2bd9e151a4d61ef4b2711caff5a85.nq.gz
│   ├── 5cae24f9438285bb0cd854d9e42b61299f333dad.nq.gz
│   ├── 5cc550c2ffce75dc585ae6b082e0efab71a649f3.nq.gz
│   ├── 5dfb97698506db512225ef7c222423599a0d8894.nq.gz
│   ├── 5e0de6f01f49b862bcfbfcc188c7c6181561e21c.nq.gz
│   ├── 67a66d4cd7a8747869c3e4fd5157240a97413542.nq.gz
│   ├── 67cda47b237235b5527169524acf27aa0ebd24eb.nq.gz
│   ├── 6935e83a4bb4de4b12b276c04aac45cb2e1de96e.nq.gz
│   ├── 695ed4d449b8d6714a4b599397ee39ffcb2ab971.nq.gz
│   ├── 6ca855e9d7d1debdc810b686f0130b50c6ddc9da.nq.gz
│   ├── 6d06b94f278ea1d894cc4ed297a600b907a09475.nq.gz
│   ├── 6fc48b0e7fba95b96658e8d459a6f7a08168bc35.nq.gz
│   ├── 6fe2c43ad80ed3695917f9155b12d97ba5afda5c.nq.gz
│   ├── 71952e012e5ff688ce5331a86fc7d8a35863e0bf.nq.gz
│   ├── 73a632e93288dded63bc9ecc8342573e30073879.nq.gz
│   ├── 756d808a0ec72c2c7eac4c47404cea05664c6bef.nq.gz
│   ├── 7adc82b6e37864c511d932ec6ee112f53c230379.nq.gz
│   ├── 7bec751f2b0c5e9cf7846bdf6f07faf6184f453c.nq.gz
│   ├── 814d0fd2885a96b4a54dedd124101d5bfc3bffc9.nq.gz
│   ├── 84e87510e68fdae49e7b4e237f2be6bded0f23d1.nq.gz
│   ├── 8bc7b09bdcb898f3908477066b39be95b28992c0.nq.gz
│   ├── 8cfc34cc610d035ace982d4780e6ac375499cafa.nq.gz
│   ├── 8d47b578db7bc8ed4652114ecd2a2090b5fbaa3b.nq.gz
│   ├── 909ec282f72c05f36e2676a820c0fae009f65e7d.nq.gz
│   ├── 90cd5f0d7065bd32b8a979811f69c804f2044f0c.nq.gz
│   ├── 90fba422737673d765cbdb0e338cc40385b23b83.nq.gz
│   ├── 92f06cd85779bd070219894a2c55766a6711217c.nq.gz
│   ├── 931e2b4176c13ff58d6ebc968f352f46efabba91.nq.gz
│   ├── 968bb75756e674e5c34b9cb2a4df0c41bcf65570.nq.gz
│   ├── 970a265dcd2dc098d74e7c5f7dd03709db4db61e.nq.gz
│   ├── 9879f6595e62bf69777158d3c3f00e2e9a2ad741.nq.gz
│   ├── 9ac3f9cdc37d10286b13cad5bd1de86208e47136.nq.gz
│   ├── 9ce9cff1bb42730e945b47962a3bb1cad54eea96.nq.gz
│   ├── a056a90e5819e018af1cf914f42fb88a8e819c11.nq.gz
│   ├── a5838c21a2ea57e2527d77ba54911cafe59d79ad.nq.gz
│   ├── a82860771a659cabdaa77d365660e3014022e07d.nq.gz
│   ├── a927c12848b9f466169af6b5584dfb47b9befa62.nq.gz
│   ├── a9a5a226bea699331decea1dcdcbe9f3845e7c49.nq.gz
│   ├── ad079ea6ead3ddd2f77c8df96a645240bb5c3ffc.nq.gz
│   ├── ad14c0e241ec8d07fa6c8cdc60af98933aa9e5ca.nq.gz
│   ├── ae3a85e843bc87ac40b4416ae2a5c4eec906fdc3.nq.gz
│   ├── b01d290bf96d74f2818126831548cd90e6759310.nq.gz
│   ├── b2ef5687fe7345be4205cf6750fbdcbe6c9a892b.nq.gz
│   ├── b7a645ab7d10ecaeae2f88c7036a46a783a66655.nq.gz
│   ├── b7e2e6dfb0d7dc45881b737c32b38a18d2237146.nq.gz
│   ├── b90dcb674848f8eeba9147739dacd77fa0835ac8.nq.gz
│   ├── bc588f8563488ebe6c55cb27d86156f85ed4f40e.nq.gz
│   ├── bfcf9f9ecb936a780f855796f28b1460240969ff.nq.gz
│   ├── c22e7abb3786c0fb8211516ed27844c580e37baa.nq.gz
│   ├── cb613355dab09d59cd244527246223871d433249.nq.gz
│   ├── cb8db17d0eb868d21f4bdfd17f159a234748cc2c.nq.gz
│   ├── cc98ce44ea41339b1a96fcb2ebf4cac64dc0129c.nq.gz
│   ├── ce13e04d94fa76e458dbc00638e8ca5ad4b766f9.nq.gz
│   ├── d19b32570f744e91e0a7002387fab9b056f0439a.nq.gz
│   ├── d45f3c5f2a62243d5a1b2a732ec28fb2ea4ce00b.nq.gz
│   ├── d484ec59de9a1cf5fed6577f5c1bc41c8fe118f7.nq.gz
│   ├── d6f27eccc1f6593d8982cffb203773666f7ab6f2.nq.gz
│   ├── d854788d0fb7b2c2ed5286e11244ad81f1193145.nq.gz
│   ├── db940192bf9a0e50fb50429eeae2e859f0e0ef5a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e93038d8766d296827290b1616cf1da14b3a9d85.nq.gz
│   ├── e938f9cba748575439d6892eb3bc49d622e3b51c.nq.gz
│   ├── e9a385c68b0bdfc5a378bb286fec30308578cba0.nq.gz
│   ├── ea4987de77920d5822037567f82831380848c71e.nq.gz
│   ├── ee19166c4a5f999ce0672eff76441be16399a83c.nq.gz
│   ├── efdcebf3f898e8dc87cb7d697815406dc5b727c5.nq.gz
│   ├── f248485003eb46b51a48b9211479b46cd85e9919.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f40beafdf9af6639df23553a2fc573c4da157cf0.nq.gz
│   ├── f4c5e87260e29070b99c2779ad294e7d67a78152.nq.gz
│   ├── f514df25506c732aa8e213d730cc4384040ad5fe.nq.gz
│   ├── fb7911f1386c59ee4e67e1d2a96fd7703e1e54cf.nq.gz
│   ├── fcba4fa0af592b5dbc1bcbde46faacca95124202.nq.gz
│   └── fef6af15a748e47575f24166026b72ffe97d0d97.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3c113cfa92777c5c575b7b0c742d2a2080ff9a52.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 123 files
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

[ansible-collections/ansible_hub](https://github.com/ansible-collections/ansible_hub)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
