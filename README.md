# OLL2026 Swiss Legal QA Datasets

This repository contains three datasets created at the **Open Legal Lab 2026 (OLL2026)**, 
held on April 25–27, 2026 in Magglingen, Switzerland. The datasets were produced as part 
of **Challenge 11**, led by the association [Gerechter.ch](https://gerechter.ch). All data 
was created, annotated and reviewed by legal professionals during the hackathon.

---

## Datasets

### OLL2026 QA Input Dataset

A collection of **79 legal questions** across six areas of Swiss law (*Alltagsrechtsfragen, 
Arbeitsrecht, Kaufrecht, Kinderrechte, Mietrecht, Schuldbetreibungs- und Konkursrecht*), 
each answered by two AI models: **IUS Chat** and **Gemini 3 Flash**. This dataset serves 
as the unannotated input for human annotation via Label Studio. Questions and answers were 
drafted by jurists during OLL2026 and have not yet been validated or rated.

### OLL2026 Ground Truth

A partially annotated dataset of **63 questions** with human annotations on retrieval 
quality and generation quality. Annotations were produced by legal professionals using 
Label Studio during OLL2026. The dataset includes source rankings, relevance ratings, 
missing source annotations, and – for a subset of **20 questions** – dimension-level 
quality ratings. Annotators are anonymised.

### OLL2026 LLM Benchmark

A pairwise comparison dataset of **79 questions**, in which legal professionals evaluated 
side-by-side answers from **IUS Chat vs. Gemini 3 Flash**. Each entry contains the 
anonymised preference judgements and dimension-level comparisons from more than one 
annotator, as well as a derived winner field. Where annotators disagreed, the entry is 
marked as contested. Annotators are anonymised.

---

## License

All three datasets are licensed under **CC BY 4.0**. You are free to share and adapt the 
material for any purpose, provided appropriate credit is given to the associations 
[Gerechter.ch](https://gerechter.ch) and [eJustice.ch](https://ejustice.ch).

---

## Disclaimer

The data in this project was created by legal professionals during OLL2026 for **research 
purposes only**. AI-generated answers (IUS Chat, Gemini 3 Flash) are included as input 
material for annotation and do not represent validated legal advice. We do not guarantee 
the accuracy, completeness, or reliability of any content contained in these datasets. The 
human annotations reflect the individual judgements of the participating jurists and should 
not be treated as authoritative legal opinions.

We did not intend to infringe upon any copyright laws or intellectual property rights. If 
any content in these datasets raises concerns in this regard, please contact us immediately 
and we will address the issue. We cannot be held responsible for any damages or losses 
resulting from the use of these datasets. Please use the data at your own risk and verify 
its accuracy before relying on it for any purpose.
