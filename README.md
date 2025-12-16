## 👋 David A’Hearne

Senior software engineer and engineering leader with 13+ years of experience building, operating, and scaling production systems across fintech, energy, defence, and SaaS. Extensive experience owning complex systems end to end, leading engineering teams, and delivering business-critical software in regulated and high-availability environments.

I finished my role at Bright in December 2024 to focus on strengthening my foundations in mathematics and data science. I am currently studying for a BSc in Mathematics with the Open University and completing the [Cambridge Data Science Career Accelerator programme](https://onlinecareeraccelerators.pace.cam.ac.uk/cambridge-data-science-career-accelerator).

## 🛠️ Core Engineering Experience

My primary background is in senior and lead engineering roles, with long-term ownership of production systems:

- Design and evolution of distributed systems and microservice architectures  
- Cloud-native development on Azure and AWS, including infrastructure automation and CI/CD pipelines  
- Strong emphasis on reliability through TDD and BDD, including unit, integration, contract, and end-to-end testing  
- Refactoring legacy systems, managing technical debt, and improving observability through logging, metrics, and alerting  
- Hands-on experience with C#, .NET, SQL, JavaScript and TypeScript, React, and service-oriented architectures  

I have consistently worked on systems under real operational pressure, balancing delivery speed with correctness, performance, and maintainability.

## 👥 Leadership and Management

Alongside hands-on technical work, I have held senior leadership and management responsibilities including:

- Hiring, onboarding, and managing engineering teams of up to 15+ mixed-discipline members  
- Defining technical direction, architecture, and development standards  
- Owning delivery from ideation and prioritisation through to live operation and support  
- Mentoring engineers through structured one-to-ones, pairing, code review, and development plans  
- Working closely with product, customer experience, marketing, and stakeholders to align technical delivery with business outcomes  
- Leading incident response, post-mortems, and continuous improvement initiatives  

My leadership approach is pragmatic and delivery-focused, with an emphasis on clarity, sustainable pace, and building teams that can ship high-quality software consistently.

## 🧠 Data Science and Machine Learning

Alongside my core engineering work, I am developing deeper capability in data science and machine learning, with a strong emphasis on fundamentals and real-world applicability.

Recent applied work includes:

- Exploratory data analysis using statistical measures, distribution analysis, skew, and outlier detection  
- Feature engineering from raw transactional, temporal, and behavioural data  
- Unsupervised learning including IQR-based detection, One-Class SVM, Isolation Forest, and K-Means clustering  
- Dimensionality reduction using PCA and t-SNE for analysis and validation  
- Supervised learning with neural networks and XGBoost, including handling class imbalance and staged feature availability  
- Structured model evaluation and hyperparameter tuning using precision, recall, F1, accuracy, and AUC  

My interest lies in how these techniques translate into reliable, maintainable systems rather than isolated notebook results.

## 🔧 Current Technical Exploration

I am actively exploring architectures that combine:

- Go for performance, concurrency, and simplicity  
- HTMX for minimal, server-driven interfaces  
- Modern NLP and ML techniques for low-latency, cost-efficient systems  

The focus is on building lean ML-enabled products that avoid unnecessary infrastructure complexity or vendor lock-in.

## 🧩 Current Side Project

My current side project focuses on building an ML-enabled product, prioritising clean architecture, operational simplicity, and low-latency interaction.

Key approaches and implementation details:
- Hexagonal architecture in Go with clear separation between:
  - Domain contracts and types
  - Use cases as the application boundary
  - Infrastructure adapters for external dependencies
  - HTTP delivery layer as a thin interface
- HTMX-first UI with websocket support for a server-driven interaction model, reducing frontend complexity while maintaining responsiveness
- LLM integration via Ollama with streaming responses:
  - Incremental decoding of streamed chunks
  - Server-side chunking strategy to emit readable partial responses while streaming
- Vector similarity search backed by Postgres using pgvector:
  - Persisted prototype embeddings
  - Nearest-neighbour queries using vector distance operators
- Service integration between:
  - A Go web application as the primary delivery surface and orchestration layer
  - A Python FastAPI service responsible for embeddings and similarity lookups
- Docker-first packaging and environment-driven configuration for reproducible local and deployment workflows

The next phase of the project focuses on evolving the system into a low-latency natural language interface backed by a structured internal knowledge model, while avoiding unnecessary reliance on large, opaque models
* **Structured memory with temporal awareness**: 
Introduce a slot-based representation for capturing relevant information from natural language input. Facts are stored with confidence, provenance, and temporal validity, allowing the system to retain history while prioritising recent or explicitly updated information.
* **Targeted extraction over free-form generation**: Populate structured slots using extractive question-answering models in combination with named-entity recognition. This enables precise, bounded extraction from short interactions, with explicit uncertainty tracking rather than implicit assumptions.
* **Semantic routing and intent interpretation**: Replace brittle keyword triggers with embedding-based routing and lightweight intent classification to determine how user input should be handled, whether updating stored information, querying existing knowledge, or retrieving contextual signals.
* **Natural language querying of structured knowledge**: Expose stored information through the same natural language interface used to create it. Wherever possible, queries are resolved deterministically against structured data, with retrieval-based techniques used selectively for nuanced or contextual questions.
* **Application-level safeguards and adaptability**: Enforce constraints on storage, updates, and retrieval to prevent low-confidence accumulation or misuse. Conflicts, revisions, and uncertainty are handled explicitly, allowing the system to adapt naturally as information evolves.

## 🧾 Employment Timeline

| Years       | Company             | Role                     | Focus |
|------------|---------------------|--------------------------|-------|
| 2023 – 2024 | BrightHR               | Delivery Lead            | Product ownership, team leadership, architecture, global delivery |
| 2023        | Schneider Electric   | Contract Engineer        | .NET libraries, embedded integrations, TDD |
| 2020 – 2023 | OpenMoney            | Tech Lead                | Greenfield systems, CI/CD, mentoring, architecture |
| 2018 – 2020 | Raytheon             | Senior Software Engineer | Distributed systems, refactoring, defence projects |
| 2016 – 2018 | Zen Internet         | Systems Developer        | APIs, web platforms, cloud prototyping |
| 2013 – 2016 | Swinton Insurance    | Junior C# Developer     | Enterprise .NET, BDD and TDD |
| 2012 – 2013 | Parker Sandfords     | Junior Developer         | Web development and CMS |
