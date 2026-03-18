<div align="center">
<img src="docs/logo2.png" alt="CUFEInse Logo" width=auto height="100" style="max-width: 100%; height: 80;">
<h1 style="font-size: 48px; color: #2c3e50; margin: 20px 0; font-weight: bold;">CUFEInse</h1>

<p style="font-size: 22px; color:rgb(0, 0, 0); margin: 10px 0 20px 0; font-weight: 900; letter-spacing: 1px;">Central University of Finance and Economics Insurance Evaluation Suite</p>
<p style="font-size: 22px; color:rgb(0, 0, 0); margin: 10px 0 20px 0; font-weight: 900; letter-spacing: 1px;">The World's First Professional Insurance LLM Evaluation Framework</p>

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
![license](https://img.shields.io/badge/License-Apache--2.0-blue.svg)

---

**📖 Documentation** · [简体中文](./README.md) · [English](./README_EN.md)

**📜 Historical Versions** · [v1.0 Documentation](docs/v1/README_zh_CN.md) · [v1.0 Evaluation Report](docs/v1/report_v1_zh_CN.md) · [v1.0 README](docs/v1/README.md)

</div>


---
## Table of Contents
* [Background and Iteration Significance](#background-and-iteration-significance)
* [v2.0 Evaluation Framework Methodology](#evaluation-framework-methodology)
* [v2.0 Core Upgrades and Technological Innovation](#core-upgrades-and-technological-innovation)
* [Evaluation Dataset Distribution](#evaluation-dataset-distribution)
* [Evaluation Set Usage and Scoring Mechanism](#evaluation-set-usage-and-scoring-mechanism)
* [Open Source Plan and Sampling Design](#open-source-plan-and-sampling-design)
* [Contact Us](#contact-us)

---

## Background and Iteration Significance

In September 2025, the School of Insurance and China Institute of Actuarial Science at Central University of Finance and Economics released CUFEInse v1.0, an insurance domain evaluation benchmark. As the world's first LLM evaluation benchmark deeply integrated with the insurance discipline system and comprehensively covering insurance professional theory and industry application scenarios, v1.0 includes 14,430 high-quality questions, building a standardized evaluation system covering 5 first-level dimensions and 54 second-level subcategories, filling the gap in systematic professional evaluation of LLMs in the insurance domain, and gaining widespread application and recognition from academia, the insurance industry, and technology enterprises.

With the deep deployment of LLMs in the insurance industry, the industry has raised higher requirements for models' professional knowledge accuracy, logical reasoning rigor, compliance and security control capabilities, and full-scenario deployment adaptability. Based on six months of v1.0 application practice, we have collected feedback from numerous universities, insurance institutions, and technology enterprises, finding that the evaluation system still has room for optimization in question bank coverage breadth, calculation capability evaluation accuracy, segmented insurance product scenario adaptability, and question classification standardization.

Based on this, we have completed the full-system iteration upgrade of CUFEInse v2.0. The new version continues v1.0's core positioning of "discipline-oriented, expert-driven, industry-aligned," achieving comprehensive breakthroughs in question bank scale, quality control, capability evaluation dimensions, and scenario adaptability, aiming to build a more discipline-aligned, industry-deployment-adapted, and technically authoritative insurance LLM evaluation benchmark, continuously leading the construction and improvement of insurance domain LLM evaluation standards.


## Evaluation Framework Methodology

Building on v1.0's core methodology of "quantitative-first, expert-driven, multi-layer verification," CUFEInse v2.0 has upgraded to a full-process closed-loop quality control system, completing the construction and iteration of the full dataset through five core stages, ensuring the dataset's professionalism, rigor, and scenario adaptability:

1. **Industry Demand and Application Feedback Research**
Conducting in-depth research and interviews with universities and research institutions, insurance enterprises and intermediaries, and fintech companies to identify core pain points in v1.0 usage and new requirements for industry deployment, clarifying four core iteration directions: "strengthen calculation capability evaluation, expand core discipline question bank, supplement segmented insurance product scenarios, optimize classification boundaries."

2. **Expert Question Design and Question Bank Expansion**
Organizing full-time faculty from the School of Insurance and China Institute of Actuarial Science, senior industry actuaries, compliance experts, and insurance technology business experts, based on the complete insurance discipline system and full insurance business process scenarios, to complete new question design and expansion of the existing question bank. New questions cover insurance core theory, actuarial calculation, compliance and security, underwriting and claims, and other full-dimensional content, ensuring question professionalism and industry alignment.

3. **Four-Level Cross-Review and Revision**
Establishing a four-level review mechanism of "designer initial review - discipline expert cross-review - industry expert scenario validation - compliance expert review," conducting item-by-item revision of all questions (including existing and new questions), correcting v1.0 issues such as ambiguous wording, classification optimization, and insufficient answer accuracy, ensuring zero ambiguity in questions and zero errors in answers.

4. **Sensitivity and Compliance Review**
Collaborating with insurance regulatory experts to conduct dual compliance and sensitivity review of all questions, ensuring all questions fully comply with insurance industry regulatory requirements issued by the National Financial Regulatory Administration, eliminating non-compliant expressions and sensitive content, aligned with the insurance industry's core characteristics of strong regulation and high-risk sensitivity.

5. **Full Dataset Quality Verification**
Through dual AI format verification and manual review, conducting format consistency, content completeness, and uniqueness verification of all questions, removing highly similar questions, ensuring high quality and uniqueness of the dataset.

Key data metrics for this iteration are as follows:

| 📊 Metric | 🔢 Value | 📝 Description |
| :--- | :---: | :--- |
| **v1.0 Baseline Question Bank** | **14,430** | Full question set for v1.0 |
| New Questions Added | 3,207 | Effective new questions added after deduplication |
| Revised Questions | 239 | Questions with optimized/updated wording and answers |
| Deduplicated Questions | 11 | Highly similar questions removed from full verification |
| **v2.0 Full Question Bank** | **17,637** | Total evaluation questions in final release |

## Core Upgrades and Technological Innovation

CUFEInse v2.0 has achieved comprehensive upgrades across four core dimensions on the basis of v1.0, further strengthening the technicality, professionalism, and industry adaptability of the evaluation benchmark. Key innovations include:

1. **Significant Question Bank Expansion, Qualitative Leap in Discipline Coverage Depth**
v2.0 contains 17,637 questions in total, a 22.2% expansion from v1.0's 14,430 questions, making it the world's largest and most comprehensive insurance domain professional evaluation benchmark in terms of knowledge point coverage.
    - Core Discipline Focus: The core expansion area is the insurance theoretical knowledge dimension, with 2,316 new questions, total increasing from 5,254 to 7,570, proportion rising from 38.18% to 43.42%. Key expansion areas include insurance system and principles, insurance law, insurance products, insurance actuarial science, and other core insurance discipline areas, further consolidating the evaluation benchmark's discipline professionalism and building a more complete insurance discipline knowledge assessment system.
    - Comprehensive Segmented Product Coverage: Addressing v1.0's insufficient coverage of segmented insurance products, supplementary exclusive questions for health insurance, accident insurance, liability insurance, agricultural insurance, credit guarantee insurance, and other segmented products have been added in second-level categories such as insurance products, product comparison, and liability analysis, filling assessment gaps in segmented scenarios and significantly improving evaluation value for vertical product scenarios, enabling more precise assessment of model deployment capabilities in segmented products.

2. **Full-Process Quality Control System Upgrade, Comprehensive Optimization of Data Precision and Classification Rigor**
v2.0 has established a fully closed-loop quality control system, achieving full-process quality control from demand research to final release. Core achievements include:
    - Completing revision and optimization of all questions through the four-level review mechanism, achieving more scientific question wording and more precise standard answers, significantly improving the objectivity and reproducibility of evaluation results.
    - Completing dual compliance and sensitivity review of all questions, ensuring all questions comply with insurance industry regulatory requirements, further strengthening the evaluation benchmark's compliance and authority.

3. **Comprehensive Strengthening of Core Capability Evaluation System, Precise Alignment with Insurance Actuarial and Industry Deployment Needs**
Addressing the pain point of insufficient LLM calculation and compliance capabilities reported by the industry during v1.0 evaluation set usage, v2.0 has focused on strengthening three core capability evaluation dimensions, building an evaluation system more aligned with actual insurance business needs:
    - Deep Upgrade of Core Actuarial Capability Evaluation: The financial numerical calculation second-level category under insurance rigor classification increased from 19.00% to 26.09% in question proportion, the most significant growth among all categories; meanwhile, 111 new questions were added to the insurance actuarial second-level category. New calculation-type questions cover core scenarios across the full business process including insurance benefit calculation, actuarial pricing, reserve provisioning, and claim limit calculation. Question types have been upgraded from simple numerical calculation to multi-step logical reasoning calculation, enabling more precise evaluation of LLM complex logical reasoning and numerical calculation capabilities in insurance scenarios, effectively identifying model hallucination and calculation bias.
    - Strengthening of Underwriting and Claims Core Scenarios: The underwriting-related second-level category under insurance industry understanding classification increased from 4.41% to 7.26% in question proportion, the largest growth among all categories; meanwhile, claims-related, insurance liability analysis, and other second-level categories have been expanded, focusing on strengthening reasoning capability evaluation for the full underwriting and claims process, adapting to deployment needs of core insurance business segments.
    - Continued Reinforcement of Compliance and Security Baseline: The insurance values second-level category under insurance safety and compliance classification increased from 29.68% to 32.52% in question proportion, further strengthening evaluation of model compliance values and regulatory baseline, aligned with the insurance industry's core characteristic of strong regulation.

4. **Scoring Mechanism Optimization Upgrade, Evaluation Results with Greater Interpretability and Comparability**
v2.0 continues v1.0's core scoring strategy of "dimension equal weight, subcategory balance," while adapting to the optimized classification system to ensure fairer, more interpretable evaluation results:
    - First-Level Dimension Equal Weight: The 5 first-level categories (Insurance Rigor, Insurance Safety and Compliance, Insurance Agent Application, Insurance Theoretical Knowledge, Insurance Industry Understanding) have completely equal weights, each accounting for 20% of the comprehensive score, avoiding any single dimension dominating the overall score, ensuring comprehensive and fair evaluation.
    - Second-Level Subcategory Balanced Weighting Optimization: For the optimized second-level classifications, subcategory balanced weighting rules have been adjusted, with weight allocation based on knowledge granularity and business importance, avoiding subcategories with more questions from dominating dimension scores, ensuring evaluation results can precisely reflect model capability differences in segmented domains, with stronger interpretability and industry comparability.
    - Adaptation to Multi-Scenario Evaluation Needs: Optimized scoring rules for different question types, supporting zero-shot, few-shot, and other evaluation modes, adapting to different institutions' evaluation needs.

## Evaluation Dataset Distribution

CUFEInse v2.0 contains a total of 17,637 evaluation questions, covering 5 first-level categories and 54 second-level subcategories. Question types include single choice, multiple choice, true/false, short answer, reasoning and planning, retrieval QA, label extraction, and other full types, enabling comprehensive evaluation of LLM knowledge reserve, reasoning capability, compliance capability, and scenario deployment adaptability in the insurance domain.

### First-Level Category Distribution
<p align="center">
  <img src="./docs/images/v2/category_compare.png" alt="Main Dimension Comparison Radar Chart" style="width:70%; height: auto; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</p>

### Core Second-Level Category Key Changes
This iteration focuses on key expansion of core disciplines and business scenarios, displaying only the TOP 10 core subcategories by new question count. Specific changes are as follows:
<p align="center">
  <img src="./docs/images/v2/secondary_category_compare.png" alt="Secondary Category Comparison Chart" style="width:70%; height: auto; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</p>

## Evaluation Set Usage and Scoring Mechanism

### Evaluation Set Structure Specification
Each question in CUFEInse v2.0 contains standardized core fields, adapting to different evaluation scenario needs. Field definitions:

| Field Name | Description |
| :--- | :--- |
| Complete Question | Contains standardized evaluation prompt, question stem, and options, directly usable for zero-shot evaluation |
| Question Stem | Contains only the core question, no additional prompts, supports user-defined prompts, adapts to few-shot and other evaluation modes |
| Options | Unified A-E five-option format, adapting to professional actuarial and other specialized question evaluation needs |
| Standard Answer | Unique standard answer jointly reviewed by insurance discipline experts and industry experts, ensuring evaluation result objectivity |
| Prompt | Standardized prompt template for the corresponding evaluation scenario, supports user customization |

Sample question (from this evaluation set):
```json
{
"完整题目": "以下是关于保险法的单项选择题，请直接给出正确答案的选项。 题目：人身保险中，保险人收到被保险人或受益人提交的给付申请书后，对属于保险责任的，达成给付保险金的协议后（）日内，履行给付保险金义务；对不属于保险责任的，自作出核定之日起（）日内向受益人发出拒绝给付保险金通知书并说明理由。 选项： A：5，3 B：10，3 C：10.5 D：10，10 从ABCD中选出唯一正确的答案。",
"题干": "人身保险中，保险人收到被保险人或受益人提交的给付申请书后，对属于保险责任的，达成给付保险金的协议后（）日内，履行给付保险金义务；对不属于保险责任的，自作出核定之日起（）日内向受益人发出拒绝给付保险金通知书并说明理由。",
"A": "5，3",
"B": "10，3",
"C": "10.5",
"D": "10，10",
"E": "",
"答案": "B"
}
```
### Scoring Mechanism
v2.0 continues and optimizes the "dimension equal weight, subcategory balance" comprehensive scoring strategy. Core rules are as follows:

1. **First-Level Dimension Equal Weight Rule**: The 5 first-level categories (Insurance Rigor, Insurance Safety and Compliance, Insurance Agent Application, Insurance Theoretical Knowledge, Insurance Industry Understanding) have completely equal weights, each accounting for 20% of the comprehensive score, avoiding any single dimension dominating the overall score, ensuring comprehensive and fair evaluation.

2. **Second-Level Subcategory Balanced Weighting Rule**: Second-level subcategories under each first-level category are balanced and weighted according to knowledge granularity and business importance. The sum of all second-level subcategory weights under the same first-level category is 100%, ensuring capability in each segmented domain can be precisely evaluated, avoiding subcategories with more questions from dominating dimension scores.

3. **Single Question Scoring Rules**:
    - Objective questions (single choice, multiple choice, true/false): 0/1 scoring system, 1 point for exact match with standard answer, 0 otherwise;
    - Subjective questions (short answer, reasoning and planning, label extraction, etc.): Faithfulness reasoning evaluation algorithm scoring system, scored from four dimensions—answer accuracy, logical rigor, compliance, and scenario adaptability—ensuring evaluation result objectivity.

## Open Source Plan and Sampling Design

### v1.0 Open Source Plan Review
v1.0 adopted a "full question bank sampling open source + full dataset authorized evaluation" approach, open sourcing 1,532 questions. This provided academia and industry with convenient standardized evaluation tools, promoted industry evaluation standard adoption, while protecting the evaluation benchmark's core intellectual property and authority through the full dataset authorization mechanism, gaining widespread industry recognition.

### v2.0 Open Source and Sampling Plan
Combining v1.0 open source practical experience with v2.0's iteration upgrade characteristics, this release continues the core open source strategy. The final version determines 1,949 questions for open source. Specific plan is as follows:

#### Sampling Core Principles
This sampling adopts stratified balanced sampling to ensure the open source dataset can fully reflect v2.0's core upgrades and classification system. Core principles include:

1. **Balanced Category Coverage**: Sampling proportion of the 5 first-level categories matches the full dataset's category proportion. All 54 second-level subcategories have question coverage, ensuring the open source dataset can achieve comprehensive basic evaluation of model insurance domain comprehensive capability.

2. **Upgrade Focus Highlight**: Key coverage of core expansion subcategories for this iteration (insurance system and principles, insurance law, financial numerical calculation, underwriting-related, etc.). Proportion of v2.0 new questions in the open source dataset is no less than 35%, fully reflecting v2.0's upgrade core.

3. **Comprehensive Question Type Adaptation**: Open source dataset covers single choice, multiple choice, true/false, short answer, reasoning and planning, label extraction, and other full question types, including standardized prompts, supporting zero-shot, few-shot, and other evaluation modes, adapting to different institutions' evaluation needs.

#### Open Source Content and License
1. **Open Source Content**: Each question in the sampled open source dataset contains complete question, question stem, options, standard answer, and prompt fields, consistent with full dataset structure. Users can directly use for evaluation or customize prompts.
2. **Open Source License**: Continues v1.0's Apache-2.0 open source license. Dataset content uses CC BY 4.0 license, allowing non-commercial use, modification, and distribution by academia and industry, with attribution required to CUFEInse team at Central University of Finance and Economics.
3. **Full Dataset Evaluation Application**: Universities, research institutions, insurance institutions, and technology enterprises with full dataset evaluation needs may contact the CUFEInse team via official email to apply for full dataset evaluation authorization. The team will review applications and provide full evaluation access, continuously promoting benchmark industry application.

#### Plan Advantages
1. **Historical Comparability**: Open source scale is basically consistent with v1.0's sampling proportion, ensuring evaluation results across versions have historical comparability. Industry users can seamlessly adapt to v2.0 open source dataset for longitudinal iterative evaluation of model capabilities.
2. **Industry Universality**: Open source dataset fully covers insurance discipline core knowledge and industry core scenarios, meeting diverse needs including university research, insurance enterprise model self-evaluation, and industry horizontal comparison, further promoting unification and adoption of insurance LLM evaluation standards.
3. **Intellectual Property Protection**: Through the "sampling open source + full authorization" model, providing industry with accessible evaluation tools while protecting the evaluation benchmark's core intellectual property, avoiding misuse of the core question bank, ensuring the benchmark's long-term authority and iteration capability.

## Contact Us

The CUFEInse evaluation benchmark is jointly developed by the School of Insurance and China Institute of Actuarial Science at Central University of Finance and Economics. We consistently uphold the philosophy of co-creation with the entire industry. We welcome universities and research institutions, insurance companies, technology enterprises, and industry experts and scholars to participate in benchmark iteration and co-construction, working together to establish and improve insurance industry LLM application standards.

For cooperation, full dataset evaluation application, technical exchange, or to learn more about CUFEInse v2.0, please contact the CUFEInse team:

[![Email](https://img.shields.io/badge/Email-cufeinse%40cufe.edu.cn-0078D4?style=flat-square&logo=microsoft-outlook&logoColor=white)](mailto:cufeinse@cufe.edu.cn)
[![GitHub](https://img.shields.io/badge/GitHub-CUFEInse%2FCUFEInse-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/CUFEInse/CUFEInse)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-CUFEInse%2FCUFEInse-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/datasets/CUFEInse/CUFEInse)

| Contact | Link |
| --- | --- |
| 📧 Official Email | [cufeinse@cufe.edu.cn](mailto:cufeinse@cufe.edu.cn) |
| 🐙 GitHub Repository | [CUFEInse/CUFEInse](https://github.com/CUFEInse/CUFEInse) |
| 🤗 Hugging Face Repository | [CUFEInse/CUFEInse](https://huggingface.co/datasets/CUFEInse/CUFEInse) |

---

## Acknowledgments

We sincerely thank all participating faculty and students from the School of Insurance and China Institute of Actuarial Science at Central University of Finance and Economics for their hard work, thank all insurance industry experts participating in this benchmark construction for their valuable opinions and support, and thank academia and industry colleagues for their recognition and support of the CUFEInse benchmark. We will continue to iterate and optimize the benchmark, jointly promoting safe, reliable, and efficient application of large language models in the insurance domain.
