# n8n RAG AI Agent Workflow Collection

## Overview

This repository is a reference collection of n8n workflow examples and documentation for retrieval-augmented generation (RAG). It is not a configured n8n instance or a single deployable RAG application. The examples come from multiple sources, including community templates, Gumroad, and original work.

For source review without executing or importing anything, start with the [Swarm-ready handoff](SWARM_READY.md).

## Repository Structure

| Path | What is checked in |
| --- | --- |
| [documentation-for-RAG/](documentation-for-RAG/) | Documentation snapshots and processing helpers, including the [n8n documentation index](documentation-for-RAG/n8n_documentation_index/). |
| [Categorized/](Categorized/) | Topic folders with text descriptions and some JSON exports. A description is not an importable workflow. |
| [n8n-blog-maker/](n8n-blog-maker/) | Blog workflow examples and supporting guides. |
| [Real Case Example (Credit to @imgroup)/](Real%20Case%20Example%20%28Credit%20to%20%40imgroup%29/) | Case-study files, including examples and supporting assets. |
| Root `*.json` files | Individual examples; they are not a package or a shared configuration manifest. |

## Offline catalog review

From the repository root, list the tracked sources without opening the exports:

```bash
git --no-lazy-fetch ls-tree --name-only HEAD -- documentation-for-RAG Categorized n8n-blog-maker 'Real Case Example (Credit to @imgroup)'
git --no-lazy-fetch ls-files -- ':(top,glob)**/*.json'
```

Expect four top-level directories from the first command. The second lists candidate JSON files; the count is **not** a count of distinct, valid, or runnable workflows. Repository-level environment variables, a common credential set, and benchmark timings are not established by this collection. The inventory check does not contact n8n, run a crawler or model, open credential files, or import or activate workflows.

## Here some sources to learn more about n8n

[Full basic - No prerequisites](https://youtu.be/c0Dqnd4HU8w)<br>
[Overall guide - No prerequisites](https://youtu.be/ZHH3sr234zY)<br>
[Webhook guide if you want to self host](https://youtu.be/kq5bmrjPPAY)<br>
[Neat tricks](https://youtu.be/NBhARSnjvwg)<br>
[MOST IMPORTANT](https://cdn11.bigcommerce.com/s-v7bssafn/images/stencil/760x600/products/1022/5529/20240624-DSC_3994-Edit__76162.1719226837.jpg?c=2)<br>

## Credits

- @imgroup: Real-world business implementations
- n8n.io community contributors

## License

There is no repository-wide license file in this checkout. Check the terms of each example's source before reusing or redistributing it.


