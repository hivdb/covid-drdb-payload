---
name: Suggest new study
about: Suggest adding a new study
title: "[New]"
labels: enhancement
assignees: KaimingTao

---

Important: first check this list to see if we have already have the paper: https://github.com/hivdb/covid-drdb-payload/blob/master/tables/articles.csv

**What's the identifier of this new study? Please provide. (Just need one)**
- DOI: [...]
- PMID: [...]
- PMCID: [...]
- URL: [...]

**What topic studied by this paper should be add to our database? Please describe.**
A clear and concise description of what the topic is. Ex. This paper contains neutralization results of [...] variants for vaccine [...].

**Which tables/figures contain the data?**
Ex. Table 1, Supp. Figure 3

**Additional information can help us entering this study faster. Attach files if necessary.**

- What's the neutralization assay(s) and where did you find it?
  Ex. Pseudovirus, Virus isolate, SARS-CoV-2 recombinant. Complete list: 
  https://github.com/hivdb/covid-drdb-payload/blob/master/tables/assays.csv
  Please also give the page/paragraph/table/figure number where you found this data.

- Questions related to the potency / titer / fold data:
  - What's the potency type and where did you find it?
    Ex. IC50/IC80/ICxx/NT50/NT80/NTxx, page X paragraph Y / line Z.
  - What's the detection threshold and where did you find it?
    For NT50 it usually started from 10 or 20; for IC50 it probably a number like 5ng/ml, 10ng/ml.
    Please give the page/paragraph/table/figure number where you found this data.

- For plasma/serum samples, when did the plasma sample collected? Ex. ~5/15/21.

- For vaccinee plasma/serum:
  - What's the vaccine dosage & shots?
    Ex. BNT162b2, 1st shot on ~4/1/21, 2nd shot on ~4/22/21. Vaccine complete list: https://github.com/hivdb/covid-drdb-payload/blob/master/tables/vaccines.csv

- For convalescent plasma/serum:
  - What's the infection variant? Ex. B.1, B.1.1.7, B.1.351.
  - What's the estimated time the person were infected?

Last question: can you provide us the titer/IC50/fold data in tabular form (CSV/TSV/Excel)? You can upload the file here or provide the URL. We prefer individual titer/IC50 data rather than fold or median/mean titer/IC50.
