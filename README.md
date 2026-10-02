# TraceSynthesis Tutorial Materials

**TraceSynthesis:** https://trace-synthesis-autoextraction.reviewtools.workers.dev/

TraceSynthesis is a browser-based application for structured LLM-assisted information extraction from research documents. This repository provides example materials for understanding and testing the workflow. It includes the coding sheet used in the examples and two exported result files produced with TraceSynthesis. These materials also accompany a submitted tutorial manuscript describing the workflow.

## Files

### `Coding_Sheet_TraceSynthesis_Ready.xlsx`

This is the coding sheet used for the example extractions. It contains 37 coding items, including item names, definitions or instructions, response options where applicable, and single- or multiple-selection rules.

### `Sample_Result_1.xlsx`

Example output generated with TraceSynthesis for:

Saritepeci, M., & Yildiz Durak, H. (2024). Effectiveness of artificial intelligence integration in design-based learning on design thinking mindset, creative and reflective thinking skills: An experimental study. *Education and Information Technologies, 29*, 25175–25209. https://doi.org/10.1007/s10639-024-12829-2

### `Sample_Result_2.xlsx`

Example output generated with TraceSynthesis for:

Cao, X. (2024). Case study of China’s compulsory education system: AI apps and extracurricular dance learning. *International Journal of Human–Computer Interaction, 40*(13), 3419–3426. https://doi.org/10.1080/10447318.2023.2188539

### `documentation/TraceSynthesis_Tutorial_Materials_Guide.docx`

A short guide to the files in this repository, the settings used to generate the example outputs, the organization of the exported workbooks, and the source articles.

## Trying the workflow

The coding sheet is provided so that readers can inspect the structure used in the examples and, if desired, use it when testing TraceSynthesis with documents they are authorized to use. Running an extraction requires the user's own API key from a supported model provider. API use is billed by the provider associated with that key.

The two sample workbooks are included as reference outputs. They show the type of information exported by TraceSynthesis and can be used alongside the tutorial when reviewing the extraction, evidence, and verification fields.

## Version and settings used for the sample outputs

Both sample outputs were generated with **TraceSynthesis v4.3, released October 1, 2026**, using the same settings:

| Setting | Value |
| --- | --- |
| Model | GPT-4.1 |
| Provider | OpenAI |
| Document reading | Text + Table + Page Image |
| Temperature | 0.2 |
| Reads per study | 1 |
| Coding items per request | 8 |
| Other extraction settings | TraceSynthesis v4.3 defaults |

These settings were the default extraction configuration in v4.3 except for the selected model and document-reading option described above.

## Reading the sample outputs

Each example workbook contains several worksheets. The `results` sheet contains the main coding-item-level output. The remaining sheets retain additional information produced during extraction, including structured source records, numeric values, page coverage, definitions, and notes about the exported file.

The sample files are provided as examples of the workflow and exported output. They should not be treated as fully verified coded datasets unless the human-review fields indicate that a value has been checked.

## Source articles

The source PDFs are **not redistributed in this repository** because they are published articles that I do not have permission to redistribute. Readers can use the citations and DOI links above to obtain the articles from the publisher, a library, or another authorized source.

## Software updates

TraceSynthesis is actively updated. Supported models and provider APIs may change over time, and later versions may include changes intended to improve processing time, reduce API cost, or refine parts of the extraction workflow. For this reason, the live application may differ from v4.3, and rerunning the same task with a later release or different model settings may not produce identical output.

The current application is available at:

https://trace-synthesis-autoextraction.reviewtools.workers.dev/

## Source code

This repository contains materials for using and evaluating the workflow. It does **not** contain the production source code or the development repository for TraceSynthesis.
