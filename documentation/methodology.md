# Methodology

The proposed framework consists of six major stages.

## 1. Literature Retrieval

Relevant biomedical publications are retrieved from PubMed using disease- and protein-specific search strategies.

---

## 2. Sentence Extraction

BioBERT-based natural language processing is used to identify sentences describing protein–disease relationships.

---

## 3. Regulatory Classification

Extracted evidence is classified into one of three regulatory categories:

- Positive Regulation
- Negative Regulation
- Neutral Regulation

---

## 4. Experimental Evidence Filtering

Evidence is filtered according to experimentally validated study types including:

- Knockout studies
- Functional assays
- Clinical investigations
- In vivo evidence

---

## 5. Evidence Aggregation

Each experimentally validated statement contributes a weighted score based on evidence quality and regulatory direction.

Scores from multiple publications are aggregated to infer consensus regulatory behavior.

---

## 6. Regulatory Role Inference

The final regulatory role is determined from the cumulative evidence score while maintaining complete traceability to supporting literature through PubMed identifiers.
