# Results and Discussion

## 5. Results and Discussion

The empirical findings were synthesised through the Systematic Literature Review (SLR) methodology described in the research methodology above, employing online repositories such as Google Scholar, IEEE Xplore, ACM Digital Library, Springer, and MDPI. The findings respond to Research Question 1 and Question 2 about the effects of Generative Artificial Intelligence (GenAI) tools such as GitHub Copilot and ChatGPT on code generation and debugging for data engineering and computing students.

### 5.1 Summary of Selected Literature

Table 1 below provides a clear synthesis of current research. It compares the primary studies examined, summarising their core focus, key findings on coding and debugging, and identified learning risks.

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

### 5.2 Code Generation and Scripting

As illustrated in Table 1, students interact with GenAI assistants primarily in two software development domains.

1. **Scripting and Code Generation:** Students use natural language prompts to quickly generate standard syntax, database connection scripts, and basic SQL queries such as `JOIN` operations and aggregate functions (Yalwa et al., 2026; Strik et al., 2024). Students working in data engineering routinely deal with repetitive, standard code or tasks known as boilerplate (Foidl et al., 2023). AI tools reduce syntactic friction such as small coding obstacles and maintain learning momentum.

2. **Error Correction and Debugging Interaction:** Students use GenAI to understand complex compiler tracebacks and explain runtime errors (IJACSA authors, 2026; Strik et al., 2024). Barke et al. (2023) identify two modes of operation in student-AI debugging interactions.

    - **Acceleration Mode:** Quickly helps students handle minor syntax issues, formatting, and well-understood logic.
    - **Exploration Mode:** Used when dealing with runtime exceptions or bugs in pipeline logic. Students prompt iteratively, cross-check multiple suggestions, and validate code line-by-line.

### 5.3 Findings Related to Research Questions

Regarding the application methods stated in RQ1, most students use GenAI for code generation tasks such as SQL boilerplate and setup scripts (Yalwa et al., 2026; Strik et al., 2024), as well as error interpretation (Strik et al., 2024).

Barke et al. (2023) describe interactions between students and GenAI as switching between an **Acceleration Mode** for writing routine syntax and an **Exploration Mode** for debugging complex runtime bugs.

For RQ2, the main benefits include instant scaffolding and reduced syntactic friction for novice learners (Strik et al., 2024; Bien & Mukherjee, 2025). However, these advantages come with substantial pedagogical risks, including AI hallucinations, security vulnerabilities (Reihanian et al., 2024), learner passivity (Bo et al., 2025), and diminished independent troubleshooting abilities (Kurniawan et al., 2025).

### 5.4 Implications for Data Engineering Learning

Syntax acceleration alone is not sufficient for data engineering. Students also need to understand pipeline architecture and database schemas (Foidl et al., 2023; Bien & Mukherjee, 2025).

GenAI is helpful in **Acceleration Mode** for multi-component pipelines but may be less reliable in **Exploration Mode**. Unlike general software errors that terminate execution, logic bugs in ETL or SQL scripts can execute successfully and silently corrupt data warehouses (Foidl et al., 2023).

Therefore, uncritically accepting AI recommendations can directly threaten data integrity (Bo et al., 2025; Kurniawan et al., 2025).

---

# Conclusion and Recommendations

## 6. Conclusion and Recommendations

The synthesised findings reveal clear patterns in student adoption, key technical trade-offs, and institutional strategies required for GenAI.

For **RQ1**, students use GenAI primarily for routine boilerplate generation, SQL structuring, and error translation (Yalwa et al., 2026; Strik et al., 2024). Barke et al. (2023) describe bimodal interaction patterns that alternate between acceleration and exploration.

For **RQ2**, the main benefits are reduced syntax friction and rapid feedback for learners (Strik et al., 2024). Nevertheless, these benefits are offset by significant risks such as code hallucination (Reihanian et al., 2024), student passivity (Bo et al., 2025), and silent pipeline bugs (Foidl et al., 2023).

For **RQ3**, active output verification by students is required to ensure safe and effective AI usage, alongside formal institutional programmes that embed comprehensive AI literacy into the curriculum.

### Recommendations

1. **Manual Code Verification**

   Students should manually verify AI-generated SQL and ETL scripts line-by-line before deploying them (Reihanian et al., 2024).

2. **Independent Error Analysis**

   Students should conduct independent error-trace analysis in Exploration Mode before requesting AI-generated fixes (Barke et al., 2023; Kurniawan et al., 2025).

3. **Formal AI Literacy**

   Formal AI literacy should be incorporated into computing curricula to teach students how to assess risks and evaluate AI-generated outputs.

4. **Assessment Improvements**

   Assessment methods should include oral code defences, database schema design, and manual code reviews to evaluate students' independent understanding.

5. **Institutional Guidelines**

   Institutions should establish explicit guidelines defining acceptable levels of AI assistance in software engineering and data engineering education.

### Final Conclusion

In conclusion, GenAI provides significant productivity gains in data engineering education, but technical acceleration needs to be balanced with critical thinking. Through an emphasis on manual code verification and formal AI literacy, students can develop strong and self-sufficient software engineering skills.
