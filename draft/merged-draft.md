# Generative AI in Code Generation and Debugging: A Literature Review on Software Engineering Learning Among Data Engineering Students

## Abstract

The rapid advancement of Generative Artificial Intelligence (GenAI) has significantly influenced software engineering education and programming practices. Tools such as ChatGPT and GitHub Copilot provide students with assistance in code generation, debugging, and understanding programming concepts. This literature review investigates the role of GenAI in code generation and debugging among data engineering students, focusing on its applications, benefits, risks, and implications for software engineering learning. A Systematic Literature Review (SLR) approach was adopted to identify, screen, and synthesise relevant literature from academic databases. The findings indicate that GenAI can reduce syntactic friction, provide instant feedback, generate routine code, and support students during debugging. However, risks including hallucinated code, security vulnerabilities, passive learning, overreliance, and weakened independent debugging skills remain significant concerns. The review highlights the importance of active verification, critical thinking, and AI literacy to ensure that GenAI supports rather than replaces students' software engineering learning.

**Keywords:** Generative Artificial Intelligence, code generation, debugging, software engineering education, data engineering, GitHub Copilot, ChatGPT

---

# 1. Introduction and Problem Statement

The rapid development of Generative Artificial Intelligence (GenAI), particularly large language models (LLMs) and intelligent coding assistants (ICAs), has transformed the way software is developed and learned. Tools such as GitHub Copilot and ChatGPT can generate code, explain programming concepts, identify errors, and provide debugging suggestions. These capabilities create opportunities for students to overcome common programming difficulties and improve their productivity.

For data engineering students, GenAI may be particularly useful because their learning involves programming, database queries, data processing, ETL pipelines, and algorithmic logic. Students frequently work with repetitive configuration scripts, SQL queries, data transformation operations, and debugging tasks. GenAI can potentially reduce the time spent on routine coding activities and allow students to focus on higher-level software engineering concepts.

However, the increasing availability of AI coding assistants also creates concerns about student overreliance. Students may accept AI-generated code without understanding or verifying it. This can result in incorrect logic, security vulnerabilities, hallucinated outputs, and reduced opportunities for independent problem-solving. In data engineering, such problems can be particularly serious because errors in SQL queries or ETL pipelines may execute successfully while silently producing incorrect data.

Therefore, it is important to understand how GenAI is being used for code generation and debugging and how its benefits can be balanced against the risks to software engineering learning.

---

# 2. Research Objectives

This study aims to:

1. Examine how Generative AI tools are used for code generation and debugging among software engineering and data engineering learners.
2. Identify the benefits and risks associated with the use of GenAI in programming and debugging activities.
3. Determine recommendations for responsible and effective use of GenAI in software engineering learning.

---

# 3. Research Questions

The literature review addresses the following research questions:

- **RQ1:** How are Generative AI tools used for code generation and debugging among software engineering and data engineering learners?
- **RQ2:** What are the main benefits and risks of using GenAI for code generation and debugging?
- **RQ3:** What strategies can support the responsible and effective use of GenAI in software engineering learning?

---

# 4. Literature Review

The rapid evolution of Generative Artificial Intelligence (GenAI), including large language models (LLMs) and intelligent coding assistants (ICAs) such as GitHub Copilot and ChatGPT, has fundamentally reshaped software engineering (SE) education and practice. GenAI brings both important learning opportunities and unique educational challenges to data engineering students who are typically juggling complex data pipeline scripts, database queries, and algorithmic logic. Recent works address these impacts along three main axes: developer productivity and code generation benefits, debugging support and interaction dynamics, and security risks of academic overreliance.

## 4.1 Code Generation and Productivity Enhancement

One of the main drivers for the adoption of GenAI in technical education is its capacity to enhance programming productivity and simplify the software development lifecycle (SDLC). Studies have shown that AI code assistants can speed up routine coding tasks, help students stitch template code together, and fill in knowledge gaps when students encounter unfamiliar data structures or APIs. GenAI is able to act as an on-demand mentor in data engineering education where students often spend a lot of time writing repetitive configuration scripts and data transformation logic, minimizing syntactic friction and keeping them in motion.

## 4.2 Interaction Dynamics during Debugging and Exploration

It is important to go beyond just writing code and to understand how students engage with AI as they debug and troubleshoot. Barke et al. (2023) present empirical research showing that developer-AI interactions are predicated on bimodal behaviors: an acceleration mode, where AI is leveraged to quickly perform well-understood logic, and an exploration mode, where deep prompting, multi-suggestion comparison, and line-by-line validation are used to resolve unfamiliar errors.

Debugging AI-generated code requires active critical thinking rather than passive acceptance, especially when dealing with complex runtime errors or logic bugs in data pipelines.

## 4.3 Security Risks, Code Errors, and Overreliance

Despite the clear utility, recent literature highlights important cautionary notes regarding the risks of unrestrained GenAI usage. Comprehensive security analyses show that LLM-generated code can sometimes introduce subtle security vulnerabilities, syntax flaws, or hidden logic errors.

Additionally, educational researchers warn of the risk of overreliance, especially among beginner programmers who may overestimate AI reliability. Simply taking AI output and using it without thinking can lead to subtle plagiarism, erosion of basic problem-solving skills, and a reduction in the deep cognitive processing necessary to truly master software engineering principles.

---

# 5. Research Methodology

To investigate the role of Generative Artificial Intelligence (GenAI) in code generation and debugging among data engineering students, this study adopted a Systematic Literature Review (SLR) approach. The methodology outlines the systematic process of gathering, screening, and evaluating relevant peer-reviewed literature to synthesise current insights.

## 5.1 Review Process and Approach

The review process consisted of three main stages:

- **Identification:** Formulating clear search strings and identifying appropriate digital repositories.
- **Screening:** Filtering retrieved papers based on predefined inclusion and exclusion criteria that focus on the title, abstract, and relevance to software or data engineering education.
- **Selection:** Reviewing full articles to ensure they directly address code generation, debugging behaviour, productivity, or risks associated with AI assistants.

## 5.2 Digital Databases Used

The literature search employed academic databases and online repositories including:

- Google Scholar
- IEEE Xplore
- ACM Digital Library
- Springer
- MDPI

Google Scholar was used for broad multidisciplinary coverage of open-access and scholarly articles, while IEEE Xplore was used to identify peer-reviewed conference papers and journals focusing specifically on software engineering, computing education, and artificial intelligence.

## 5.3 Inclusion and Exclusion Criteria

### Inclusion Criteria

- Peer-reviewed journal articles, conference proceedings, and empirical studies.
- Literature published within the recent timeframe to reflect rapid advancements of modern GenAI models.
- Studies focusing on programming education, developer workflows, interaction modes, or software engineering learning outcomes.

### Exclusion Criteria

- Non-academic sources such as blog posts, tutorials, and unverified news articles.
- Papers lacking full-text accessibility or written in languages other than English.
- Studies focusing purely on hardware engineering or non-programming domains without direct relevance to software or data engineering.

---

# 6. Results and Discussion

The empirical findings were synthesised through the Systematic Literature Review (SLR) methodology described above, employing online repositories such as Google Scholar, IEEE Xplore, ACM Digital Library, Springer, and MDPI. The findings respond to Research Question 1 and Question 2 about the effects of Generative Artificial Intelligence (GenAI) tools such as GitHub Copilot and ChatGPT on code generation and debugging for data engineering and computing students.

## 6.1 Summary of Selected Literature

Table 1 provides a synthesis of current research. It compares the primary studies examined, summarising their core focus, key findings on coding and debugging, and identified learning risks.

### Table 1: Summary and Comparison of Selected Literature

| Study Reference | Primary Focus | Key Findings on Code Generation & Debugging | Identified Risks & Pedagogical Drawbacks |
|---|---|---|---|
| Barke et al. (2023) | Empirical study on programmer interaction with code-generating models. | Bimodal behaviours were identified: Acceleration Mode for rapid execution of well-understood logic and Exploration Mode for iterative prompting and multi-suggestion validation. | Accepting generated code without question can lead to logic errors and runtime bugs that are never found. |
| Yalwa et al. (2026) | Systematic review of GenAI for programming in higher education. | Reduces syntactic friction by auto-generating code snippets and routine code. | Passive use of AI tools may indicate a lack of deep pedagogical frameworks. |
| Strik et al. (2024) | Systematic mapping of GPT AI tools in computer science education. | Often used for instant feedback, explaining error tracebacks, and translating complex compiler messages. | Passive use of AI tools may reveal a lack of deep pedagogical frameworks. |
| Foidl et al. (2023) | Data pipeline quality, root cause of errors, and processing issues. | Reinforces the importance of rigorous script development, ETL logic management, and lifecycle management in data engineering. | Automated tools may struggle with complex data dependencies, allowing subtle pipeline bugs to pass usual compiler checks. |
| Bo et al. (2025) | AI debugging assistants for beginner programmers. | Shows that beginner programmers often use AI to speed up debugging and obtain instant code fixes. | High levels of passive acceptance and overreliance on automated assistants may occur among new programmers. |
| Kurniawan et al. (2025) | Preliminary study on AI-based debugging tools for inexperienced learners. | Determines how AI-based debugging tools help learners deal with runtime exceptions while troubleshooting code. | Automated code resolution may jeopardise student-driven debugging practice. |
| Reihanian et al. (2024) | Scoping review of AI hallucinations and security threats in computer science education. | Documents how LLMs support code generation tasks in various software development projects. | Highlights code hallucinations, inefficient database queries, and subtle security flaws. |
| Bien & Mukherjee (2025) | Data engineering education and software development life cycles. | Shows how data life cycles interact with modern AI software engineering tools to make learning easier. | Empirical research on data-oriented learners remains limited. |

## 6.2 Code Generation and Scripting

Students interact with GenAI assistants primarily in two software development domains.

1. **Scripting and Code Generation:** Students use natural language prompts to quickly generate standard syntax, database connection scripts, and basic SQL queries such as `JOIN` operations and aggregate functions (Yalwa et al., 2026; Strik et al., 2024). Students working in data engineering routinely deal with repetitive, standard code or tasks known as boilerplate (Foidl et al., 2023). AI tools reduce syntactic friction such as small coding obstacles and maintain learning momentum.

2. **Error Correction and Debugging Interaction:** Students use GenAI to understand complex compiler tracebacks and explain runtime errors (Strik et al., 2024). Barke et al. (2023) identify two modes of operation of student-AI debugging interactions:

    - **Acceleration Mode:** Quickly helps students handle minor syntax issues or formatting.
    - **Exploration Mode:** Used when dealing with runtime exceptions or bugs in pipeline logic. Students prompt iteratively, cross-check multiple suggestions, and validate code line-by-line.

## 6.3 Findings Related to Research Questions

Regarding RQ1, most students use GenAI for code generation tasks such as SQL boilerplate and setup scripts (Yalwa et al., 2026; Strik et al., 2024) and error interpretation (Strik et al., 2024).

Barke et al. (2023) describe the interaction between students and GenAI as switching between an Acceleration Mode for writing routine syntax and an Exploration Mode for debugging complex runtime bugs.

For RQ2, the main benefits include instant scaffolding and reduced syntactic friction for novice learners (Strik et al., 2024; Bien & Mukherjee, 2025). However, these advantages come with substantial pedagogical risks including AI hallucinations, security vulnerabilities (Reihanian et al., 2024), learner passivity (Bo et al., 2025), and diminished independent troubleshooting abilities (Kurniawan et al., 2025).

## 6.4 Implications for Data Engineering Learning

Syntax acceleration alone is not sufficient for data engineering. Students also need to learn pipeline architecture and database schemas (Foidl et al., 2023; Bien & Mukherjee, 2025).

GenAI is helpful in Acceleration Mode in multi-component pipelines but may be less reliable in Exploration Mode. Unlike general software errors that terminate execution, logic bugs in ETL or SQL scripts can execute successfully and silently corrupt data warehouses (Foidl et al., 2023).

Uncritically accepting AI recommendations therefore directly threatens data integrity (Bo et al., 2025; Kurniawan et al., 2025).

---

# 7. Conclusion and Recommendations

The synthesised findings reveal clear patterns in student adoption, key technical trade-offs, and institutional strategies required for GenAI.

For **RQ1**, students use GenAI primarily for routine boilerplate generation, SQL structuring, and error translation (Yalwa et al., 2026; Strik et al., 2024). Barke et al. (2023) describe bimodal interaction patterns that alternate between acceleration and exploration.

For **RQ2**, the main benefits are reduced syntax friction and rapid feedback for learners (Strik et al., 2024). Nevertheless, these benefits are offset by significant risks such as code hallucination (Reihanian et al., 2024), student passivity (Bo et al., 2025), and silent pipeline bugs (Foidl et al., 2023).

For **RQ3**, active output verification by students is required to ensure safe and effective AI usage, alongside formal institutional programmes that embed comprehensive AI literacy into the curriculum.

### 7.1 Recommendations

1. **Manual Code Verification**

    Students should manually verify AI-generated SQL and ETL scripts line-by-line before deploying them (Reihanian et al., 2024).

2. **Independent Error Trace Analysis**

    Students should conduct independent error trace analysis in Exploration Mode before requesting AI-generated fixes (Barke et al., 2023; Kurniawan et al., 2025).

3. **Formal AI Literacy**

    Formal AI literacy should be incorporated into computing curricula to teach risk assessment and evaluation of AI-generated outputs.

4. **Assessment Methods**

    Assessment methods should include oral code defences, database schema design, and manual code reviews to evaluate students' independent understanding.

5. **Institutional Guidelines**

    Explicit institutional guidelines should be established to define acceptable levels of AI assistance in software engineering and data engineering education.

In conclusion, GenAI provides significant productivity gains in data engineering education, but technical acceleration needs to be balanced with critical thinking. Through an emphasis on manual code verification and formal AI literacy, students can acquire strong and self-sufficient software engineering skills.

---

# References

> **Note:** Insert the verified final reference list here. The references must match every in-text citation used throughout this merged draft.

- Barke et al. (2023)
- Bien & Mukherjee (2025)
- Bo et al. (2025)
- Foidl et al. (2023)
- Kurniawan et al. (2025)
- Reihanian et al. (2024)
- Strik et al. (2024)
- Yalwa et al. (2026)

---

# Drafting Notes

This file is the **merged working draft** prepared from the individual sections contributed by the group members.

### Member Contributions

- **Member A — Thurga Devi A/P Ponnambalam**
  - Introduction and Problem Statement
  - Research Objectives
  - Research Questions
  - Abstract
  - Keywords

- **Member B — Nur Arissa Binti Azmi**
  - Literature Review
  - Research Methodology
  - Literature-related references

- **Member C — Farah Aisya Binti Jaafar**
  - Results and Discussion
  - Conclusion and Recommendations
  - Table of Literature Findings
  - Final formatting and consistency checking

### Final Editing Checklist

- [ ] Verify all author names and publication years.
- [ ] Ensure every in-text citation appears in the reference list.
- [ ] Ensure every reference listed is cited in the paper.
- [ ] Verify the spelling of `Barke`, `Foidl`, `Reihanian`, and all other author names.
- [ ] Verify the actual publication details of every source.
- [ ] Confirm the final database/search methodology reflects the searches actually performed.
- [ ] Replace the broad phrase "recent timeframe" with the actual year range used, if required.
- [ ] Remove drafting notes and member labels from the final IEEE paper.
- [ ] Reduce the paper to the required maximum of 4 pages.
- [ ] Check grammar, formatting, headings, tables, and citations.
- [ ] Run Turnitin and record the actual result in `logbook.md`.
- [ ] Complete the final group review before submission.
