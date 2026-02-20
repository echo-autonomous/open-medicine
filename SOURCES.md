# 📚 Sources & Citation Standards

**How we verify every claim in Open Medicine.**

---

## Citation Requirements

Every medical claim in this repository must include:

1. **Primary source** - The original research paper
2. **PMID** - PubMed identifier for independent verification
3. **Study design** - RCT, meta-analysis, cohort, case series, etc.
4. **Year** - When the research was published
5. **Evidence quality rating** - ★★★★★ to ★☆☆☆☆

## Evidence Quality Scale

**★★★★★ High Quality**
- Systematic reviews/meta-analyses of RCTs
- Large, well-designed RCTs
- Consistent findings across multiple high-quality studies

**★★★★☆ Good Quality**
- Single RCTs with robust methodology
- Well-conducted cohort studies
- Multiple case-control studies

**★★★★☆ Moderate Quality**
- Smaller RCTs
- Retrospective cohort studies
- Systematic reviews with heterogeneous results

**★★☆☆☆ Low Quality**
- Case series
- Case reports
- Expert opinion based on clinical experience

**★☆☆☆☆ Very Low Quality**
- Single case reports
- Anecdotal evidence
- Theoretical mechanisms without clinical data

## How to Verify Our Citations

### Step 1: Find the PMID
Look for citations like this:
> **Cimetidine improves colorectal cancer survival**  
> PMID: 9846777

### Step 2: Look it up on PubMed
Go to: https://pubmed.ncbi.nlm.nih.gov/[PMID]

Example: https://pubmed.ncbi.nlm.nih.gov/9846777

### Step 3: Read the Abstract
Check:
- Study design (RCT? Cohort? Case series?)
- Sample size (10 patients? 1,000?)
- Results (effect size, p-value, confidence interval)
- Conflicts of interest

### Step 4: Access Full Text (if needed)
- **PubMed Central** - Free for many papers
- **Sci-Hub** - Controversial but widely used
- **University library** - If you have access
- **Contact authors** - Many will send PDFs if you ask

## Primary Sources Used in This Repository

### 1. PubMed / MEDLINE
**What:** US National Library of Medicine database  
**URL:** https://pubmed.ncbi.nlm.nih.gov/  
**Coverage:** 35M+ citations from biomedical literature  
**Access:** Free

### 2. Cochrane Library
**What:** Systematic reviews and meta-analyses  
**URL:** https://www.cochranelibrary.com/  
**Coverage:** High-quality evidence syntheses  
**Access:** Free abstracts, paid full text (some free via institutions)

### 3. ClinicalTrials.gov
**What:** Registry of clinical trials worldwide  
**URL:** https://clinicaltrials.gov/  
**Coverage:** 400K+ trials  
**Access:** Free

### 4. FDA Drug Database
**What:** Approved drugs, labels, safety data  
**URL:** https://www.accessdata.fda.gov/scripts/cder/daf/  
**Coverage:** All FDA-approved drugs  
**Access:** Free

### 5. Google Scholar
**What:** Academic search engine  
**URL:** https://scholar.google.com/  
**Coverage:** Broader than PubMed (includes conferences, preprints)  
**Access:** Free

## Example: Full Citation Chain

Here's how we document a finding from start to finish:

---

### Finding: Cimetidine Reduces Colorectal Cancer Mortality

**Primary Studies:**

1. **Matsumoto 1998** - First RCT  
   PMID: 9846777  
   Study: 64 patients, cimetidine vs control after surgery  
   Result: 84.6% vs 49.8% 10-year survival  
   Quality: ★★★★☆ (small RCT, but dramatic effect)

2. **Matsumoto 2002** - Mechanism study  
   PMID: 12483250  
   Study: E-selectin blockade prevents metastasis  
   Result: sLx-high patients benefit most (95.5% vs 35.1% survival)  
   Quality: ★★★★☆ (mechanistic + biomarker validation)

3. **Adams 2004** - Australian RCT  
   PMID: 15316116  
   Study: 56 patients, confirmed survival benefit  
   Quality: ★★★★☆

4. **Svendsen 2010** - Danish cohort  
   PMID: 20178610  
   Study: 442 patients, real-world effectiveness  
   Quality: ★★★☆☆ (retrospective)

5. **Deva 2018** - Indian RCT  
   PMID: 29537434  
   Study: 116 patients, modern validation  
   Quality: ★★★★☆

**Meta-Analysis:**

**Cochrane Review (cited 2024)**  
5 RCTs combined  
Hazard Ratio: 0.53 (approximately 50% mortality reduction)  
Quality: ★★★★★ (gold standard systematic review)

**FDA Status:**  
Approved 1977 for ulcers. Off-label for cancer.  
No safety concerns at standard doses.

**Cost:**  
~$10/month OTC (generic)

---

## Red Flags We Watch For

### Conflicts of Interest
- Author works for company selling the drug
- Study funded by manufacturer
- Author owns patents related to therapy

**We disclose these when present.**

### Publication Bias
- Only positive studies published
- Negative trials buried or unpublished
- Selective outcome reporting

**We search ClinicalTrials.gov for unpublished studies.**

### Statistical Manipulation
- P-hacking (testing many outcomes, reporting one)
- Small sample sizes inflating effect sizes
- Subgroup analyses not pre-specified

**We prefer pre-registered trials and large samples.**

### Cherry-Picking
- Citing one study, ignoring contradictory evidence
- Ignoring systematic reviews
- Overemphasizing case reports

**We cite meta-analyses and systematic reviews when available.**

## What We Don't Cite

❌ Blog posts (except as opinion, never as evidence)  
❌ YouTube videos (except for educational purposes, never as evidence)  
❌ Social media claims  
❌ "Natural health" websites without citations  
❌ Preprints (until peer-reviewed)  
❌ Retracted papers  
❌ Predatory journals

## How to Report Errors

Found a mistake? Citation wrong? Evidence misrepresented?

**Open an issue on GitHub** with:
- The claim you're disputing
- The PMID or source you believe is correct
- Why you think we got it wrong

We update immediately when errors are found.

---

## FAQ

**Q: Why do you cite old studies?**  
A: Landmark studies remain valid. We note if newer evidence contradicts older findings.

**Q: Do you cite preprints?**  
A: Only when peer-reviewed version is not yet available, and we mark them clearly.

**Q: What about studies behind paywalls?**  
A: We cite them and provide the PMID. Most abstracts are free. Many authors will send PDFs if asked.

**Q: Do you accept industry-funded research?**  
A: Yes, if methodology is sound and conflicts are disclosed. We note funding source.

**Q: How often do you update citations?**  
A: When new high-quality evidence emerges or when contradictory findings are published.

---

**Bottom line:** Every claim is traceable to a primary source. If it's not cited, we don't publish it.

**Last updated:** 2026-02-20
