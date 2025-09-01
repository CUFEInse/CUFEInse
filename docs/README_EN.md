<div align="center">
<img src="logo2.png" alt="CUFEInse Logo" width=auto height="100" style="max-width: 100%; height: 80;">
<h1 style="font-size: 48px; color: #2c3e50; margin: 20px 0; font-weight: bold;">CUFEInse</h1>

<p style="font-size: 22px; color:rgb(0, 0, 0); margin: 10px 0 20px 0; font-weight: 900; letter-spacing: 1px;">Central University of Finance and Economics Insurance Evaluation Suite</p>
<p style="font-size: 22px; color:rgb(0, 0, 0); margin: 10px 0 20px 0; font-weight: 900; letter-spacing: 1px;">The World’s First Professional Insurance LLM Evaluation Framework</p>

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
![license](https://img.shields.io/badge/License-Apache--2.0-blue.svg)

[CUFEInse v1.0 evaulation report](report_v1_EN.md)

</div>

---

## Table of Contents

* [Background](#background-and-significance)
* [Benchmark Construction](#cufeinse-construction)
* [Innovation and Value](#innovation-and-value)
* [Access and Usage](#access-and-usage)
* [Contact Us](#contact-us)

---

## Background and Significance

Large language models have demonstrated outstanding performance on general corpora and in several vertical scenarios. The Chinese insurance industry, characterized by strict regulation, high risk sensitivity, and knowledge intensity, urgently requires a systematic and reproducible evaluation framework to objectively measure the real capabilities of LLMs in insurance tasks. Existing financial-domain benchmarks provide preliminary tools but lack completeness in coverage of insurance disciplinary knowledge, professional depth, and comprehensiveness of evaluation dimensions. In particular, they fall short in actuarial science, compliance and safety, and logical rigor.

Although some research teams have recently released financial LLM evaluation reports or proposed multimodal benchmarks for the insurance industry, a benchmark that comprehensively covers the insurance theoretical knowledge system, professional rigor and expert-driven has been missing. 

Drawing on CUFE’s strong academic foundation, the School of Insurance and the China Institute for Actuarial Science designed and open-sourced  **CUFEInse** (CUFE Insurance Evaluation Suite). This is the world’s first professional benchmark that deeply integrates the insurance disciplinary framework, comprehensively covering theoretical knowledge and application scenarios in the insurance domain. It pioneers systematic evaluation of LLMs in insurance, aiming to fill the gap and provide academia and industry with a professional, systematic, and authoritative evaluation tool. The benchmark leverages CUFE’s longstanding expertise and rich industry-academia collaboration, ensuring credibility and authority.

CUFE has a long history in insurance and actuarial science, with academic programs dating back to 1952, making it the first institution in China to establish an insurance department. It hosts the only Ministry of Education Key Research Base for Humanities and Social Sciences in insurance and actuarial sciences—the China Institute for Actuarial Science. The School of Insurance serves as the secretariat for the National Steering Committee for Professional Insurance Graduate Education, with insurance and actuarial programs consistently ranked among the top nationwide. CUFE actively promotes “government-industry-academia-research” collaboration, establishing joint research bases and postdoctoral stations with industry leaders, while maintaining close ties with regulators and top universities worldwide. 

CUFE also embraces internationalization, holding long-term collaborations with leading global actuarial associations. It has secured full course exemptions (core and advanced CP1) from the UK Institute and Faculty of Actuaries, the first in Asia to achieve this, and has been recognized as a “Center of Actuarial Excellence (CAE)” by the Society of Actuaries (SOA) and certified by the Casualty Actuarial Society (CAS) under its URP program—the first in mainland China. CUFE has been internationally recognized for its contributions to insurance education and research; at the 2005 World Insurance Congress, it was honored as one of the three Asian universities making outstanding contributions to global insurance.

In addition to academic excellence, CUFE proactively embraces industry trends, pioneering innovative talent development aligned with the AI era. In 2024, CUFE partnered with Beijing Institute of Technology to launch the country’s first cross-university, cross-discipline program in **AI + Insurance**, integrating economics, insurance, AI, machine learning, intelligent insurance practice, and insurance operations programming. This forward-looking initiative aims to continuously supply high-quality talent in intelligent insurance and InsurTech. 

The CUFE School of Insurance and the China Institute for Actuarial Science uphold a co-creation philosophy with the industry, welcoming universities, research institutions, insurers, tech companies, and industry experts to participate in the iteration and construction of the benchmark. **CUFEInse v1.0** evaluation data is publicly available, and industry peers are encouraged to share feedback and suggestions.

---

## CUFEInse Construction

### Benchmark Dataset

**CUFEInse** follows a methodology of “quantitative-first, expert-driven, multi-validation,” progressing through industry research, expert item design, cross-review, and sensitivity audits. The result is a comprehensive framework covering five dimensions:

* Insurance Theory
* Industry Understanding
* Regulatory & Security
* Agent Applications
* Rigorous Reasoning

Version 1.0 contains **14,430 high-quality questions**, covering multiple-choice, true/false, short answer, reasoning & planning, retrieval-based QA, and lab-extraction tasks. These comprehensively assess models’ knowledge reserves, reasoning ability, and scenario adaptability.

### Scoring Mechanism

The benchmark adopts a “dimension-equal, subclass-balanced” strategy:

* Equal weights across primary dimensions to avoid dominance of a single dimension, ensuring comprehensive evaluation.
* Subclass items are distributed evenly according to knowledge granularity, ensuring interpretability and comparability, and clearly reflecting the strengths and weaknesses across specific knowledge areas. 

---

## Innovation and Value

Compared to existing financial-domain benchmarks, **CUFEInse** introduces significant innovations:

1. **Systematic disciplinary structuring**: Faculty from CUFE’s School of Insurance and the China Institute of Actuarial Science systematically classified and designed questions across insurance theory, products, systems and principles, markets & operations, law, actuarial science, finance & investment, and social & policy insurance. This ensures completeness and rigor, avoiding the fragmentation and superficiality seen in prior evaluations.
2. **Hierarchical classification and balanced distribution**: Categories were refined and proportions adjusted to align with knowledge distributions in real insurance business scenarios. This fine-grained approach ensures results reflect true strengths and weaknesses across subdomains.
3. **Focus on logical rigor and compliance**: Dedicated dimensions for logical rigor and compliance emphasize chain-of-reasoning integrity, output stability, factual accuracy (avoiding hallucinations), and adherence to regulatory, ethical, and professional boundaries—well-aligned with the heavily regulated, risk-sensitive nature of insurance.
4. **Coverage of actuarial and professional exams**: Ensures precision in actuarial formulas, symbolic expression, and calculations, resolving formatting and semantic issues common to LLMs, and simulates standardized exams to measure whether models meet professional knowledge benchmarks.
5. **Model adaptability and efficiency**: Multi-scale evaluation schemes accommodate both large-parameter and lightweight models, supporting efficiency metrics such as response time and resource consumption in insurance business scenarios, and providing practical references for industry adoption.

---

## Access and Usage

### Access

**CUFEInse** is open-sourced under Apache-2.0. Portions of the dataset are available on [GitHub](https://github.com/CUFEInse/CUFEInse.git) and [Hugging Face](https://huggingface.co/datasets/CUFEInse/CUFEInse). Full evaluation access can be requested by contacting [us](#contact-us).

### How to Use

The open dataset includes full items with prompts, stems, answer choices (A–E), and correct answers.

* Full items include prompts required for evaluation scenarios, supporting few-shot and zero-shot setups depending on context.
* Stems contain standalone questions without prompts, allowing flexible adaptation for different tasks.

**Note**: Actuarial questions include an option E; therefore, all questions consistently use options A–E.

```json
{
    "完整题目": "以下是关于保险法的单项选择题，请直接给出正确答案的选项。
            题目：在人身保险合同具有现金价值的情况下，投保人可以按合同当时的现金价值扣除欠费及利息、借款及利息后的余额，作为一次交清的全部保险费，以相同的合同条件减少保额，合同继续有效，此种处理方法是：
            选项：
            A：减额交清
            B：减保
            C：退保
            D：垫交保费
            从ABCD中选出唯一正确的答案。",
    "题干":"在人身保险合同具有现金价值的情况下，投保人可以按合同当时的现金价值扣除欠费及利息、借款及利息后的余额，作为一次交清的全部保险费，以相同的合同条件减少保额，合同继续有效，此种处理方法是",
    "A":"减额交清",
    "B":"减保",
    "C":"退保",
    "D":"垫交保费",
    "E":"",
    "答案": "A"
}
```

---

## Contact Us

We sincerely thank all faculty, students, and industry experts involved in building this benchmark for their dedication and support.

We look forward to broad cooperation with academia and industry to advance the safe, reliable, and efficient application of LLMs in insurance. Contributions of sample questions, evaluation methods, and technical solutions via GitHub or Hugging Face are welcome to help jointly improve this vital infrastructure.

For collaboration, evaluation access, or further information about **CUFEInse**, please contact the CUFEInse team at **[cufeinse@cufe.edu.cn](mailto:cufeinse@cufe.edu.cn)**.
