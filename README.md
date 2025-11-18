# Cognitive Analysis of Gas Pipeline Discourse

This repository accompanies the publication:

**Cognitive Analysis of Gas Pipeline Discourse**  
*Author:* Craig Frayne  
*Published in:* *Metaphor and the Social World*, Volume 15, Issue 1, May 2025, pp. 55–76  
*DOI:* https://doi.org/10.1075/msw.23019.fra

---

## Abstract

This paper uses cognitive discourse analysis to investigate whether differing cognitive structures and mental representations are reflected in opposing sides of pipeline debates. Quotations were extracted from a web corpus to assign statements to identifiable actors in two pipeline protests: the Dakota Access Pipeline (DAP) and Coastal GasLink Pipeline (CGP). Statements were then grouped according to the stance of the speakers. Aspects of cognitive orientation, depth, and constructiveness were compared between the groups, offering insights that can advance linguistic scholarship related to natural resources and the environment and support clearer communication in localized community–industry conflicts.

---

## Data & Methods

The study draws on two web corpora constructed to capture public discourse surrounding:

- **Dakota Access Pipeline (DAP)** — corpus constructed in early 2018  
- **Coastal GasLink Pipeline (CGP)** — corpus collected in 2021, following 2019–2020 protest events

### Corpus Construction

A custom Python-based web scraper was used to gather several hundred online articles, news pieces, and commentaries based on keyword searches (e.g., *“Dakota Access Pipeline,” “Coastal GasLink Pipeline protests”*). Keyword phrases included both supportive and critical terms to balance perspectives. This process produced **229 webpages**.

Sources included:

- Mainstream media outlets  
- Energy industry news services (e.g., *energynow.ca*, *canadianenergycentre.ca*)  
- Indigenous-focused news or non-profits (e.g., *theindigenousfoundation.org*)

### Quotation Extraction

Quotations were extracted automatically using regular-expression matching on quotation marks, with **500 characters of left and right context** to retain situational framing. This procedure produced **685 raw quotations**.

A manual curation phase removed:

- extraction errors  
- quotations lacking identifiable speakers  
- duplicate or near-duplicate material  
- extremely short fragments (e.g., one-word quotes)

After curation, the final dataset consisted of **194 attributed quotations**, comprising:

- **91 DAP quotations**  
- **103 CGP quotations**

Each quotation was assigned:

- a **unique ID** (`DAP###` or `CGP###`)  
- the quotation text  
- an attributed speaker  
- contextual metadata (occupation, affiliation, identity markers when available)

### Speaker Identification & Categorization

Using contextual information from the source articles, each speaker was categorized according to stance:

#### Group A — Proponents (68 quotes)

Actors expressing explicit support for the pipelines or criticizing protest actions (e.g., company representatives, industry officials, law enforcement).

#### Group B — Opponents (112 quotes)

Individuals raising concerns about environmental impacts, fairness, rights, inequality, cultural identity, or Indigenous sovereignty (e.g., activists, community members, Indigenous leaders).

#### Uncategorized (14 quotes)

Speakers whose stance could not be determined from context.

These categorized quotations form the analytical dataset for the cognitive discourse comparisons presented in the publication.

---

## Repository Structure

The repository contains the raw text data used to construct the quotation corpus:

- **corpus1/** – Dakota Access Pipeline (DAP) article corpus  
- **corpus2/** – Coastal GasLink Pipeline (CGP) article corpus  

These directories include the full-text articles from which quotations and speaker information were extracted.

---

## Citation

If you use this repository or cite findings from the study, please use:

> Frayne, C. (2025). *Cognitive analysis of gas pipeline discourse.* Metaphor and the Social World, 15(1), 55–76. https://doi.org/10.1075/msw.23019.fra

---

## License

The data and notes are shared for academic and educational use only.  
Please contact the author for questions regarding reuse or collaboration.
