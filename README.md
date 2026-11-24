# Awesome-Document-Parsing-LLM-Ingestion-Engines

markdown
# Top Document Parsing & LLM Ingestion Engines Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on LLM-Ready Document Ingestion, Layout-Aware Markdown/JSON Parsers, Multimodal RAG Pipelines, Semantic Chunking & Enterprise IDP Engines*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Document Parsing & LLM Ingestion Engines**. These tools ingest, parse, segment, chunk, OCR, and transform multi-format enterprise documents (PDF, DOCX, PPTX, XLSX, HTML, Markdown, EPUB, images) into clean, context-preserving Markdown, JSON, and vector-ready nodes for Retrieval-Augmented Generation (RAG) and LLM agent workflows.

**Examples** include Unstructured.io, LlamaParse, AWS Textract, Google Document AI, Azure AI Document Intelligence, Rossum, Klippa, Docsumo, Nanonets, Hyperscience, and run-llama/liteparse (the category leaders and popular runtimes). 

**Open-source emphasis**: This section is heavily expanded with every major active project for lightweight & full-stack LLM document ingestion engines (`run-llama/liteparse`, `Docling`, `MarkItDown`, `Unstructured OSS`, `Marker`, `MinerU`), semantic & structure-aware RAG chunkers (`Chonkie`, `LlamaIndex`, `Haystack`), and high-speed OCR/VLM ingestion pipelines (`PaddleOCR`, `Kreuzberg`, `MegaParse`) — ideal for AI/RAG engineers, LLM platform architects, data engineers, and enterprise search builders.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Support & Share](#support--share)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[LlamaParse (LlamaCloud)](https://llamaindex.ai)**  
  GenAI-native document parsing and ingestion service transforming complex PDFs, nested tables, charts, and presentations into structured Markdown/JSON tailored for LLM RAG pipelines.

- **[Unstructured.io (Unstructured Platform)](https://unstructured.io)**  
  Enterprise unstructured data ETL and ingestion platform connecting cloud storage, SharePoint, and Confluence to vector databases with automated layout partitioning and chunking.

- **[Azure AI Document Intelligence (Microsoft)](https://microsoft.com)**  
  Cloud document extraction service featuring a dedicated Layout-to-Markdown model for RAG ingestion alongside prebuilt invoice, receipt, contract, and custom neural extractors.

- **[Google Cloud Document AI](https://google.com)**  
  Managed Google Cloud document understanding platform offering a RAG-optimized Layout Parser, intelligent chunking, high-accuracy OCR, and specialized enterprise processors.

- **[AWS Textract](https://amazon.com)**  
  Managed AWS machine-learning document analysis service extracting structured text, key-value pairs, forms, and multi-page tables from PDFs and scanned images via API.

- **[Hyperscience](https://hyperscience.com)**  
  Enterprise hyperautomation and Intelligent Document Processing (IDP) platform turning complex handwritten, distorted, and unstructured documents into structured AI-ready data.

- **[Rossum](https://rossum.ai)**  
  AI-first cloud transactional document processing platform automating invoice, purchase order, and logistics document ingestion with confidence-scored human-in-the-loop review.

- **[Klippa DocHorizon](https://klippa.com)**  
  Cloud Intelligent Document Processing and OCR API suite offering automated data extraction, document classification, fraud detection, and GDPR anonymization.

- **[Docsumo](https://docsumo.com)**  
  Document AI ingestion platform engineered for financial services, commercial lending, and logistics to convert multi-page statements and forms into validated JSON.

- **[Nanonets](https://nanonets.com)**  
  No-code cloud OCR and document workflow automation platform allowing teams to train custom extraction models and stream parsed records directly into downstream databases.


## Open-Source GitHub Projects

- **[run-llama/liteparse](https://github.com)**  
  Open-source lightweight document parsing engine from LlamaIndex engineered for fast, streamlined PDF and document ingestion into clean LLM-ready formats without heavy cloud dependencies.

- **[Docling (`docling-project/docling`)](https://github.com)**  
  Flagship open-source document parsing and LLM ingestion toolkit (originally from IBM Research) converting PDF, DOCX, PPTX, XLSX, HTML, and images into rich Markdown/JSON with table and formula structure.

- **[MarkItDown (`microsoft/markitdown`)](https://github.com)**  
  Popular open-source Python utility from Microsoft converting PDFs, PowerPoint, Word, Excel, images (EXIF/OCR), audio transcripts, and HTML directly into clean, token-efficient Markdown for LLMs.

- **[Unstructured Open Source (`Unstructured-IO/unstructured`)](https://github.com)**  
  Comprehensive open-source Python library providing modular document partitioning, metadata extraction, and chunking pipelines across dozens of office, web, and image file formats.

- **[Marker (`VikParuchuri/marker`)](https://github.com)**  
  High-accuracy open-source deep-learning pipeline converting PDFs, EPUBs, and Office documents into clean Markdown, JSON, and HTML with LaTeX equations and table preservation.

- **[MinerU (`opendatalab/MinerU`)](https://github.com)**  
  End-to-end open-source multi-column scientific and technical document extraction engine (`Magic-PDF`) turning complex academic PDFs into structured Markdown and JSON for LLM training and RAG.

- **[Chonkie (`chonkie-inc/chonkie`)](https://github.com)**  
  Ultra-fast, lightweight open-source text chunking library built specifically for RAG ingestion pipelines—supporting token, sentence, recursive, semantic, and late-chunking strategies with minimal dependencies.

- **[Kreuzberg (`Goldziher/kreuzberg`)](https://github.com)**  
  High-performance open-source text and metadata extraction library supporting PDFs, images, and Office documents with native async Python/Rust execution and OCR integration.

- **[MegaParse (`QuivrHQ/MegaParse`)](https://github.com)**  
  Open-source multimodal document parser designed for LLM ingestion with zero information loss across tables, headers, footers, images, and presentations.

- **[PaddleOCR (`PaddlePaddle/PaddleOCR`)](https://github.com)**  
  Industry-leading open-source multilingual OCR and `PP-Structure` layout analysis engine feeding clean text, bounding boxes, and HTML tables into downstream RAG ingestion workflows.

- **[LlamaIndex (`run-llama/llama_index`) & Haystack (`deepset-ai/haystack`)](https://github.com)**  
  Leading open-source LLM data and RAG orchestration frameworks providing modular ingestion pipelines, document readers (`LlamaHub`), metadata extractors, and vector-store connectors.

### Additional Strong Open-Source Options

- **[PyMuPDF4LLM (`pymupdf/PyMuPDF`)](https://github.com)** for ultra-fast, CPU-friendly extraction of PDF pages into GitHub-flavored Markdown with image and table chunking tailored for LLM context windows.
- **[Crawl4AI (`unclecode/crawl4ai`)](https://github.com)** and **[Firecrawl Open Source (`mendableai/firecrawl`)](https://github.com)** for open-source web-to-Markdown ingestion engines turning dynamic websites and sitemaps into clean LLM-ready datasets.
- **[Apache Tika (`apache/tika`)](https://github.com)** for the battle-tested enterprise Java/Docker content analysis toolkit detecting and extracting metadata and text from over 1,400 MIME file formats.
- **[olmOCR (`allenai/olmocr`)](https://github.com)** for Allen AI's open-source Vision-Language Model pipeline linearizing noisy scanned PDFs and multi-column layouts into natural reading-order text.
- **[CocoIndex (`cocoindex-io/cocoindex`)](https://github.com)** for a high-performance open-source Rust-powered incremental data transformation and indexing framework keeping LLM document embeddings continuously in sync.

**Frameworks for building custom systems**: Combine **run-llama/liteparse** or **Docling / MarkItDown** for multi-format document-to-Markdown parsing, **PaddleOCR** for scanned document fallback, **Chonkie** for fast semantic chunking, and **LlamaIndex** or **CocoIndex** for incremental vector database ingestion.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Support & Share

If you find this curated list helpful, consider supporting the project:

- ⭐ **Star this repository** to help others discover it.
- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.
- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!

[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
Use code with caution.
• Always inspect parsed Markdown and extracted tables on domain-specific PDFs (financial reports, legal contracts, scientific papers) before indexing into production RAG systems, as complex multi-column layouts or merged table cells can distort numerical context.
• Proprietary corporate documents ingested into LLM pipelines often contain confidential IP or PII; process sensitive files locally using self-hosted open-source engines (Docling, MarkItDown, run-llama/liteparse, PaddleOCR) rather than external cloud APIs.
Made for AI/RAG engineers, LLM platform architects, data engineers, enterprise search builders, and open-source contributors.
Let's make document parsing and LLM ingestion engines more open, accurate, and privacy-first.
