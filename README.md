                                                             ResearchPaperAnalyser

Task 1: Research Paper Publishability Assessment:

Objective: Develop a framework to classify research papers as "Publishable" or "Non-Publishable" based on content analysis.
Dataset: 150 research papers, with 15 labeled for reference.
Evaluation: Accuracy and F1 score for classification.


Key Requirements:
Identify critical issues like inappropriate methodologies, incoherent arguments, and unsubstantiated claims.
Handle diverse research topics and maintain consistency across content types.
Achieve high accuracy in detecting issues for scalability to larger datasets.








Task 2: Conference Selection:

Objective: Develop a framework to analyze a submitted research paper and recommend the most suitable conference for submission, aligning the paper with the conference's scope, objectives, and standards.
Dataset: "Publishable" research papers, benchmark papers, and reference papers from prestigious conferences (CVPR, NeurIPS, DAA, EMNLP, TMLR, KDD).
Evaluation:
Efficiency of retrieval (latency and resource consumption).
Effectiveness of reasoning behind conference selection.
Effective API calls and tooling.


Key Requirements:
Evaluate paper content, research focus, and methodology against conference profiles.
Provide formal justifications for recommendations, comparing the paper with benchmark papers.
Classify papers exclusively into the aforementioned prestigious conferences.
Provide well-reasoned rationales for each classification (up to 100 words).
Integrate Pathway connectors and VectorStore/DocumentStore for real-time data streaming.

Additional Resources:
RAG (Retrieval Augmented Generation) resources.
Pathway developer documentation.
Langchain quickstart.
Pathway App Templates.
FastAPI Tutorials.
