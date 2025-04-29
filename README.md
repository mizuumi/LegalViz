# LegalViz

LegalViz is a novel dataset of legal relationship visualization task based on legal texts taken from EUR-LEX that store EU official legal documents.

# Paper

[LegalViz: Legal Text Visualization by Text To Diagram Generation](https://arxiv.org/abs/2502.06147).

This paper has accepted at NAACL2025. 
Please visit paper from the link.

# Dataset License

LegalViz dataset annotations are distributed under CC BY-SA 4.0. 
When you create any derivations, e.g., datasets, papers, etc, from LegalViz, please cite our paper accordingly. If your derivations are web-based projects, please cite our paper and include the link to this github page.


# Download

Annotations can be downloaded from [Here](dataset/).


# Annotation descriptions

## Annotated files

```
dataset/legalviz_train.jsonl
dataset/legalviz_valid.jsonl
dataset/legalviz_test.jsonl
```

## Annotation entries
```
"ID": Annotation unique ID.
"case_name": The name of the cases.
"case_number": Case ID numbers taken from EUR-LEX.
"document_url": Document URLs where the annotated texts taken from.
"year": The year cases have published.
"graphviz": DOT language Graphviz codes that visualize legal relationships.
"language": EU official languages that judgment cases written by.
"legal_text": Legal texts taken from EUR-LEX.
```


# Citation

```
@inproceedings{onami-etal-2025-legalviz,
    title = "{L}egal{V}iz: Legal Text Visualization by Text To Diagram Generation",
    author = "Onami, Eri  and
      Miyanishi, Taiki  and
      Maeda, Koki  and
      Kurita, Shuhei",
    editor = "Chiruzzo, Luis  and
      Ritter, Alan  and
      Wang, Lu",
    booktitle = "Proceedings of the 2025 Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers)",
    month = apr,
    year = "2025",
    address = "Albuquerque, New Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.naacl-long.339/",
    pages = "6657--6676",
    ISBN = "979-8-89176-189-6"
}

```
