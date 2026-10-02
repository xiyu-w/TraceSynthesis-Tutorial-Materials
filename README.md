# TraceSynthesis Tutorial Materials

These files accompany the *Behavior Research Methods* tutorial, **“Structured Information Extraction from Research Documents with Large Language Models: A Step-by-Step Tutorial with TraceSynthesis.”**

**TraceSynthesis:** https://trace-synthesis-autoextraction.reviewtools.workers.dev/

This repository contains the coding sheet used in the tutorial and two example output files generated with TraceSynthesis. The source articles are not included because I do not have permission to redistribute the PDFs. Full citations and DOI links are provided below so readers can locate the articles separately.

## Files

### `Coding_Sheet_TraceSynthesis_Ready.xlsx`

This is the coding sheet used for the worked examples in the tutorial. It contains 37 coding items, including item names, definitions or instructions, response options where applicable, and single- or multiple-selection rules.

### `Sample_Result_1.xlsx`

Example output generated with TraceSynthesis for:

Saritepeci, M., & Yildiz Durak, H. (2024). Effectiveness of artificial intelligence integration in design-based learning on design thinking mindset, creative and reflective thinking skills: An experimental study. *Education and Information Technologies, 29*, 25175–25209. https://doi.org/10.1007/s10639-024-12829-2

### `Sample_Result_2.xlsx`

Example output generated with TraceSynthesis for:

Cao, X. (2024). Case study of China’s compulsory education system: AI apps and extracurricular dance learning. *International Journal of Human–Computer Interaction, 40*(13), 3419–3426. https://doi.org/10.1080/10447318.2023.2188539

### `documentation/TraceSynthesis_Tutorial_Materials_Guide.docx`

A short guide to the files in this repository, the organization of the example workbooks, the software version used, and the source articles.

## Version and extraction settings

The two sample output files were generated with **TraceSynthesis v4.3**.

Because output can change with the model and extraction settings, the exact settings used for these examples should be reported with the archived files.

| Setting | Sample Result 1 | Sample Result 2 |
| --- | --- | --- |
| TraceSynthesis version | 4.3 | 4.3 |
| Model / provider | To be confirmed from the run record | To be confirmed from the run record |
| Temperature | To be confirmed from the run record | To be confirmed from the run record |
| Number of reads | To be confirmed from the run record | To be confirmed from the run record |
| Coding items per request | To be confirmed from the run record | To be confirmed from the run record |
| Optional background notes | To be confirmed from the run record | To be confirmed from the run record |

## Reading the sample outputs

Each example workbook contains several worksheets. The `results` sheet contains the main coding-item-level output. The other sheets retain additional information produced during extraction, including structured source records, numeric values, page coverage, definitions, and notes about the exported file.

These files are included as examples of TraceSynthesis output. They should not be treated as fully verified coded datasets unless the human-review fields show that a value has been checked.

## Source articles

The article PDFs are **not redistributed in this repository**. Readers can use the citations and DOI links above to obtain them from the publisher, a library, or another authorized source.

## Software updates

TraceSynthesis is actively updated. Supported models and provider APIs may change over time, and later versions may also include changes intended to reduce processing time and API cost. The live application may therefore differ somewhat from v4.3, and rerunning the same documents with a later version or different model settings may not produce identical output.

The current application is available at:

https://trace-synthesis-autoextraction.reviewtools.workers.dev/

## Source code

This repository contains the materials accompanying the tutorial. It does **not** contain the production source code or the development repository for TraceSynthesis.
