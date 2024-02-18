# ChatGPT-4 Vision Evaluation on ENADE 2021 Bachelor in Computer Science Exam

This repository contains supplementary materials for the study reported in the paper "Evaluating ChatGPT-4 Vision on Brazil's National Undergraduate Computer Science Exam." 

The tables below provide an overview of the ENADE 2021 Bachelor in Computer Science exam questions, including their subject, modality, reasoning strategy, and scoring status, and the accuracy and challenges/errors of ChatGPT-4 Vision in answering them. Click on the links on the right-most column of the tables to view the model's full conversations and the expert assessments (when available) for each question in English and Portuguese.

**Open Questions**:

| #  | Subject                 | Modality | Reasoning Strategy | Status     | Model Accuracy | Model Challenge / Error Category | Model Conversations and Expert Assessments                                  |
|----|-------------------------|----------|--------------------|------------|----------------|----------------------------|----------------------------------------------------------------------------|
| 03 | Theory of Computing     | Visual   | Direct             | Scored     | Partly correct | Logical reasoning / Incorrect multi-step reasoning, <br>Visual  acuity / Misidentification of visual elements | [English version](/questions/q09-eng.md), <br>[Portuguese version](q09-por.md) |
| 04 | Computer Architecture   | Visual   | Direct             | Scored     | Partly correct | Visual acuity / Lack of domain-specific visual output | [English version](/questions/q09-eng.md), [Portuguese version](q09-por.md) |
| 05 | Algorithms              | Visual   | Direct             | Scored     | Partly correct |  Logical reasoning / Incorrect algorithmic reasoning | [English version](/questions/q09-eng.md), [Portuguese version](q09-por.md) |

**Multiple-choice Questions**:

| #  | Subject                 | Modality | Reasoning Strategy | Status     | Model Accuracy | Model Challenge / Error Category | Model Conversations and Expert Assessments                                  |
|----|-------------------------|----------|--------------------|------------|----------------|----------------------------|----------------------------------------------------------------------------|
| 09 | Operating Systems       | Text     | Direct             | Scored     | Incorrect      |                            | [English version](/questions/q09-eng.md), [Portuguese version](q09-por.md) |
| 10 | Programming             | Text     | Direct             | Scored     | Correct        |                            | [English version](/questions/q10-eng.md), [Portuguese version](q10-por.md) |
| 11 | Artificial Intelligence | Visual   | Indirect           | Scored     | Correct        |                            | [English version](/questions/q11-eng.md), [Portuguese version](q11-por.md) |
| 12 | Comp. in Society        | Text     | Indirect           | Not scored | Incorrect      |                            | [English version](/questions/q12-eng.md), [Portuguese version](q12-por.md) |
| 13 | Software Engineering    | Text     | Direct             | Not scored | Incorrect      |                            | [English version](/questions/q13-eng.md), [Portuguese version](q13-por.md) |
| 14 | Computer Architecture   | Text     | Indirect           | Scored     | Incorrect      |                            | [English version](/questions/q14-eng.md), [Portuguese version](q14-por.md) |
| 15 | Software Engineering    | Text     | Indirect           | Scored     | Correct        |                            | [English version](/questions/q15-eng.md), [Portuguese version](q15-por.md) |
| 16 | Computer Architecture   | Visual   | Direct             | Scored     | Correct        |                            | [English version](/questions/q16-eng.md), [Portuguese version](q16-por.md) |
| 17 | Operating Systems       | Visual   | Indirect           | Not scored | Correct        |                            | [English version](/questions/q17-eng.md), [Portuguese version](q17-por.md) |
| 18 | Artificial Intelligence | Text     | Indirect           | Scored     | Incorrect      |                            | [English version](/questions/q18-eng.md), [Portuguese version](q18-por.md) |
| 19 | Human-Computer Inter.   | Text     | Indirect           | Scored     | Correct        |                            | [English version](/questions/q19-eng.md), [Portuguese version](q19-por.md) |
| 20 | Programming             | Text     | Indirect           | Scored     | Correct        |                            | [English version](/questions/q20-eng.md), [Portuguese version](q20-por.md) |
| 21 | Computer Networks       | Visual   | Direct             | Not scored | Incorrect      |                            | [English version](/questions/q21-eng.md), [Portuguese version](q21-por.md) |
| 22 | Information Systems     | Visual   | Direct             | Scored     | Correct        |                            | [English version](/questions/q22-eng.md), [Portuguese version](q22-por.md) |
| 23 | Programming             | Visual   | Direct             | Scored     | Correct        |                            | [English version](/questions/q23-eng.md), [Portuguese version](q23-por.md) |
| 24 | Computer Security       | Text     | Indirect           | Scored     | Correct        |                            | [English version](/questions/q24-eng.md), [Portuguese version](q24-por.md) |
| 25 | Distributed Systems     | Text     | Indirect           | Not scored | Incorrect      |                            | [English version](/questions/q25-eng.md), [Portuguese version](q25-por.md) |
| 26 | Web Development         | Text     | Indirect           | Scored     | Incorrect      |                            | [English version](/questions/q26-eng.md), [Portuguese version](q26-por.md) |
| 27 | Distributed Systems     | Visual   | Direct             | Scored     | Correct        |                            | [English version](/questions/q27-eng.md), [Portuguese version](q27-por.md) |
| 28 | Computer Architecture   | Visual   | Indirect           | Scored     | Correct        |                            | [English version](/questions/q28-eng.md), [Portuguese version](q28-por.md) |
| 29 | Image Processing        | Visual   | Indirect           | Invalid    |                |                            | [English version](/questions/q29-eng.md), [Portuguese version](q29-por.md) |
| 30 | Compilers               | Text     | Indirect           | Scored     | Correct        |                            | [English version](/questions/q30-eng.md), [Portuguese version](q30-por.md) |
| 31 | Theory of Computing     | Visual   | Indirect           | Scored     | Incorrect      |                            | [English version](/questions/q31-eng.md), [Portuguese version](q31-por.md) |
| 32 | Algorithms              | Text     | Indirect           | Not scored | Correct        |                            | [English version](/questions/q32-eng.md), [Portuguese version](q32-por.md) |
| 33 | Programming             | Text     | Direct             | Invalid    |                |                            | [English version](/questions/q33-eng.md), [Portuguese version](q33-por.md) |
| 34 | Theory of Computing     | Visual   | Direct             | Scored     | Incorrect      |                            | [English version](/questions/q34-eng.md), [Portuguese version](q34-por.md) |
| 35 | Algorithms              | Text     | Indirect           | Scored     | Correct        |                            | [English version](/questions/q35-eng.md), [Portuguese version](q35-por.md) |

The following suplemmentary materials are also available from the repository:
* ChatGPT-4 Vision prompt templates \[ [English version](/prompts/prompt-templates-eng.md) \] \[ [Portuguese version](/prompts/prompt-templates-por.md) \]
* ENADE 2021 Bachelor in Computer Science exam document \[ [Portuguese version](/exam/2021_prova_bacharelado_ciencia_computacao.pdf) \]
* ENADE 2021 Bachelor in Computer Science exam response standard (for open questions) \[ [Portuguese version](/exam/2021_padrao_de_resposta_bacharelado_ciencia_computacao.pdf) \]
* ENADE 2021 Bachelor in Computer Science exam answer key (for multiple-choice questions) \[ [Portuguese version](/exam/2021_gabarito_bacharelado_ciencia_computacao.pdf) \]
* ENADE 2021 Bachelor in Computer Science exam results and statistics \[ [Portuguese version (external link)](https://download.inep.gov.br/educacao_superior/enade/relatorio_sintese/2021/Enade_2021_Relatorios_Sintese_Area_Ciencia_Computacao.pdf) \]
