# Papers for Repo-Level Code Generation


This repo maintains the list of papers for repo-level code generation.

Feel free to create pull request to add more.

# Benchmark 


1. 12/2024: **[FullStack Bench: Evaluating LLMs as Full Stack Coders](https://arxiv.org/pdf/2412.00535)**
    * Benchmark for full-stack programming in many domains, and also release sandbox tool to evaluate.
2. 10/2024: **[RepoBench: Benchmarking Repository-Level Code Auto-Completion Systems](https://arxiv.org/abs/2306.03091)**
    * Data mostly extracted from GitHub, task designed as retrieval and completion, etc. Using matching accuracy as evaluation metric.
3. 2023, **[SWE-bench: Can Language Models Resolve Real-World GitHub Issues?](https://arxiv.org/abs/2310.06770)**
    * Well-known benchmark to evaluate the agent's capabilties.
3. 2023, RepoEval: **[Repocoder: Repository-level code completion through iterative retrieval and generation](https://arxiv.org/abs/2303.12570)**
    * Similar to RepoBench, data is also extracted from GitHub

# Papers
1. 2024: **[RLCoder: Reinforcement Learning for Repository-Level Code Completion](https://arxiv.org/abs/2407.19487)** (ICSE 2025)
    * Using RL to implement Repo-level code completion based on RAG method.
1. 2024: **[EVOR: Evolving Retrieval for Code Generation](https://aclanthology.org/2024.findings-emnlp.143.pdf)**
    * Design a way to improve the quality of the knowledge for retrieval. Overall, the framework is RAG for code generation
1. 11/2024: **[Repository-level Code Translation Benchmark Targeting Rust](https://arxiv.org/pdf/2411.13990)**
    * Work on repo-level code translation task? (not sure about this task, it seems translating into test cases)
2. 10/2024: **[Repository-Level Compositional Code Translation and Validation](https://arxiv.org/pdf/2410.24117)**
    * Design a pipeline for code translation
3. 10/2024: **[M2rc-Eval: Massively Multilingual Repository-level Code Completion Evaluation](https://arxiv.org/abs/2410.21157)**
    * A benchmark and also an instruction-tuning dataset for code completion.
3. 06/2024: **[How to Understand Whole Software Repository](https://arxiv.org/pdf/2406.01422)**
    * Try to resolve the task in SWE-Bench, using some ASE methods.
4. 06/2024: **[Iterative Refinement of Project-Level Code Context for Precise Code Generation with Compiler Feedback](https://arxiv.org/pdf/2403.16792)**
   * iteratively retrieve the context based on the compiler feedback
2.  06/2024: **[GraphCoder: Enhancing Repository-Level Code Completion via Code Context Graph-based Retrieval and Language Model](https://arxiv.org/pdf/2406.07003)**
    * Slicing the blocks/lines of code as retrieved context
1. 06/2024： **[R2C2-Coder: Enhancing and Benchmarking Real-world Repository-level Code Completion Abilities of Code Large Language Models](https://arxiv.org/abs/2406.01359)**
    *  A repo-level completion benchmark and a context retrieval and prompt assemble powered code completion framework.
2. 06/2024： **[Enhancing Repository-Level Code Generation with Integrated Contextual Information](https://arxiv.org/pdf/2406.03283)**
    *  Designed for statically typed programming languages. Integrate relevant code and type context.
3. 05/2024: **[Dataflow-Guided Retrieval Augmentation for Repository-Level Code Completion](https://arxiv.org/pdf/2405.19782)**
    * ACL-2024 accepted: extract entities and relations formalism, to obtain the context graph
3. 03/2024: **[Repoformer: Selective Retrieval for Repository-Level Code Completion](https://arxiv.org/abs/2403.10059)**
    * A pre-training approach to tackle repo-level code retrieval
4. 02/2024: **[Enhancing LLM-Based Coding Tools through Native Integration of IDE-Derived Static Context](https://arxiv.org/pdf/2402.03630.pdf)**
    * Leverage the IDE cross-file information for LLM to perform repo-level code generation. 
5. 01/2024: **[CODEAGENT: Enhancing Code Generation with Tool-Integrated Agent Systems for Real-World Repo-level Coding Challenges](https://arxiv.org/pdf/2401.07339.pdf)** (from software engieerning)
    * propose a benchmark for evaluation. 
    * Method: use tool to retrieve, rather than similarity
6. 12/2023: **[Context-Aware Code Generation Framework for Code Repositories: Local, Global, and Third-Party Library Awareness](https://arxiv.org/abs/2312.05772)** (from software engieerning)
    * Focus on enhancing the retrieval process (based on GPT-3.5-Turbo)
7. 11/2023：**[ML-BENCH: Evaluating Large Language Models and Agents for Machine Learning Tasks on Repository-Level Code](https://arxiv.org/pdf/2311.09835)**
8. 11/2023: **[Guiding Language Models of Code with Global Context using Monitors](https://arxiv.org/abs/2306.10763)**
    * Maintain a monitor while performing repo-level code generation
9. 10/2023: **[CrossCodeEval: A Diverse and Multilingual Benchmark for Cross-File Code Completion](https://arxiv.org/pdf/2310.11248.pdf)**
    * benchmark that required cross-file reasoning
10. 09/2023: **[CodePlan: Repository-level Coding using LLMs and Planning](https://arxiv.org/pdf/2309.12499.pdf)**
    * plan first, then execute
11. 06/2023: **[RepoFusion: Training Code Models to Understand Your Repository](https://arxiv.org/abs/2306.10998)**
    * trained to understand the whole repo
12. 03/2023: **[RepoCoder: Repository-Level Code Completion Through Iterative Retrieval and Generation](https://arxiv.org/abs/2303.12570)** (EMNLP 2023)
    * Iteratively retrieve code from repo based on similary, until the code is correct
13. 03/2023: **[InferFix: End-to-End Program Repair with LLMs](https://arxiv.org/pdf/2303.07263.pdf)** (ICSE)
    * query the database to retrieve
14. 06/2022: **[Repository-Level Prompt Generation for Large Language Models of Code](https://arxiv.org/pdf/2206.12839.pdf)** (ICML 2023)
    * generate prompt based on the complete repo, classify from a list of prompt proposal






# Survey Papers
1. 06/2024: [A Survey on Large Language Models for Code Generation](https://arxiv.org/pdf/2406.00515)
1. 01/2024: [If LLM Is the Wizard, Then Code Is the Wand: A Survey on How Code Empowers Large Language Models to Serve as Intelligent Agents](https://arxiv.org/pdf/2401.00812.pdf)

# Relevant Agent-based Papers
1. 08/2023: **[MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework](https://arxiv.org/abs/2308.00352)**
2. 07/2023: **[Communicative Agents for Software Development](https://arxiv.org/abs/2307.07924)** 
