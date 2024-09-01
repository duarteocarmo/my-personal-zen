# Building A Generative AI Platform
- It’s not about how to build AI applications and, therefore, does NOT discuss model evaluation, application evaluation, prompt engineering, finetuning, data annotation guidelines, or chunking strategies for RAGs. All these topics are covered in my upcoming book AI Engineering.
- Term-​based retrieval is much faster and cheaper than embedding-​based retrieval. It can work well out of the box, making it an attractive option to start. Both BM25 and Elasticsearch are widely used in the industry and serve as formidable baselines for more complex retrieval systems. Embedding-​based retrieval, while computationally expensive, can be significantly improved over time to outperform term-​based retrieval.
- Text-​to-​SQL: Based on the user query and the table schemas, determine what SQL query is needed. SQL execution: Execute the SQL query. Generation: Generate a response based on the SQL result and the original user query.
- and SAFE, Search Engine Factuality Evaluator (Wei et al., 2024). You can mitigate hallucinations by providing models with sufficient context and prompting techniques such as chain-​of-​thought. Hallucination detection and mitigation are discussed further in my upcoming book AI Engineering.
- You can mitigate hallucinations by providing models with sufficient context and prompting techniques such as chain-​of-​thought. Hallucination detection and mitigation are discussed further in my upcoming book AI Engineering.
- While it’s tempting to jump straight to an orchestration tool when starting a project, start building your application without one first. Any external tool brings added complexity. An orchestrator can abstract away critical details of how your system works, making it hard to understand and debug your system.