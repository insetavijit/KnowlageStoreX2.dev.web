### **[[01 Python Fundamentals for AI]]**

Master Python as the primary language for AI and LLM agent development. Learn syntax, data structures, and programming fundamentals with an AI focus. Understand why Python dominates AI—it powers 90%+ of AI/ML projects, has the richest AI ecosystem, and is the language of choice for OpenAI, Anthropic, Google, and every major AI lab. Python is essential for LLM agents, RAG systems, and modern AI applications.

|Topic|Focus & Purpose|
|---|---|
|**[[1.1 Python & AI Introduction]]**|Python in AI landscape; why Python for LLMs; AI ecosystem; Python vs other languages; setup for AI development. Understanding context.|
|**[[1.2 Development Environment]]**|Installing Python 3.11+; VS Code/PyCharm; Jupyter notebooks; virtual environments (venv, conda); Git basics; AI-ready setup. Getting started.|
|**[[1.3 Variables & Data Types]]**|Variables; strings, integers, floats; booleans; type hints; None; dynamic typing; type checking for AI code. Data fundamentals.|
|**[[1.4 Operators & Expressions]]**|Arithmetic; comparison; logical; assignment; operator precedence; expressions for data processing. Basic operations.|
|**[[1.5 Control Flow]]**|if-else; elif; nested conditions; ternary operator; conditional logic for AI applications. Decision making.|
|**[[1.6 Loops & Iteration]]**|for loops; while loops; range(); enumerate(); zip(); break/continue; loops for data processing. Repetition control.|
|**[[1.7 Functions Basics]]**|Defining functions; parameters; return values; default arguments; docstrings; function design for modularity. Code organization.|
|**[[1.8 Project: AI Data Processor]]**|Building data processing pipeline; functions; loops; conditionals; cleaning AI training data. First AI project.|

### **[[02 Data Structures for AI]]**

Master Python data structures crucial for AI development. Learn lists, dictionaries, sets, and tuples for managing training data, embeddings, and AI responses. Build efficient data pipelines. Data structures are fundamental for handling LLM inputs/outputs and managing AI workflows.

|Topic|Focus & Purpose|
|---|---|
|**[[2.1 Lists & Arrays]]**|List creation; indexing; slicing; list comprehensions; list methods; nested lists; data collections. Fundamental collections.|
|**[[2.2 Dictionaries & JSON]]**|Dictionary basics; key-value pairs; nested dictionaries; dictionary comprehensions; JSON data; API responses. Structured data.|
|**[[2.3 Sets & Tuples]]**|Set operations; uniqueness; immutable tuples; when to use each; data integrity; frozen sets. Specialized collections.|
|**[[2.4 List Comprehensions]]**|Syntax; filtering; mapping; nested comprehensions; performance benefits; Pythonic code. Concise iterations.|
|**[[2.5 Advanced Slicing]]**|Slice notation; step values; negative indices; copying sequences; slice objects. Efficient access.|
|**[[2.6 Working with JSON]]**|json module; loads/dumps; parsing API responses; serialization; handling LLM outputs. JSON processing.|
|**[[2.7 Data Type Conversion]]**|Type casting; str(), int(), float(); list(), dict(); handling conversions; data validation. Type management.|
|**[[2.8 Project: LLM Response Parser]]**|Building response parser; JSON handling; data extraction; structuring LLM outputs; data validation. Practical parsing.|

### **[[03 Object-Oriented Python for AI]]**

Master OOP concepts for building scalable AI agents. Learn classes, inheritance, and design patterns for agent architectures. Build maintainable, professional agent systems. OOP is essential for creating complex multi-agent systems and reusable AI components.

|Topic|Focus & Purpose|
|---|---|
|**[[3.1 Classes & Objects]]**|Class definition; **init**; self; creating objects; instance variables; methods; OOP basics. Object fundamentals.|
|**[[3.2 Inheritance & Polymorphism]]**|Inheritance; super(); method overriding; multiple inheritance; polymorphism; agent class hierarchies. Code reuse.|
|**[[3.3 Encapsulation & Properties]]**|Private attributes; @property; getters/setters; encapsulation principles; data hiding. Controlled access.|
|**[[3.4 Magic Methods]]**|**str**; **repr**; **call**; **enter**/**exit**; special methods; operator overloading. Special functionality.|
|**[[3.5 Abstract Classes]]**|ABC module; @abstractmethod; interface design; enforcing structure; agent base classes. Design patterns.|
|**[[3.6 Dataclasses]]**|@dataclass decorator; automatic **init**; field(); frozen classes; agent state management. Modern data classes.|
|**[[3.7 Type Hints Advanced]]**|Type annotations; Optional; Union; List[str]; Dict[str, Any]; mypy; type checking for AI code. Static typing.|
|**[[3.8 Project: Agent Base Class]]**|Building agent architecture; base agent class; inheritance; agent properties; reusable components. Agent foundation.|

### **[[04 APIs & HTTP for LLMs]]**

Master working with AI APIs and HTTP requests. Learn OpenAI API, Anthropic Claude API, and API best practices. Build applications that interface with LLMs. API skills are fundamental for all LLM agent development.

|Topic|Focus & Purpose|
|---|---|
|**[[4.1 HTTP Basics]]**|HTTP methods (GET, POST); status codes; headers; request/response cycle; REST principles. Web communication.|
|**[[4.2 Requests Library]]**|Making requests; requests.get/post; headers; parameters; JSON payloads; error handling. HTTP in Python.|
|**[[4.3 OpenAI API]]**|OpenAI client; Chat Completions; API keys; models (GPT-4, GPT-4o); parameters (temperature, tokens); prompting. GPT integration.|
|**[[4.4 Anthropic Claude API]]**|Anthropic client; Messages API; Claude models (Sonnet, Opus); API authentication; streaming responses. Claude integration.|
|**[[4.5 API Key Management]]**|Environment variables; .env files; python-dotenv; security best practices; API key storage. Secure credentials.|
|**[[4.6 Rate Limiting & Retry Logic]]**|Exponential backoff; rate limit handling; retry decorators; tenacity library; API quotas. Robust API calls.|
|**[[4.7 Async API Calls]]**|asyncio basics; aiohttp; async/await; concurrent API requests; performance optimization. Asynchronous programming.|
|**[[4.8 Project: Multi-Model Chat]]**|Building app with multiple LLMs; OpenAI + Claude; API integration; comparing outputs; cost tracking. Multi-LLM application.|

### **[[05 Prompt Engineering & LLM Interaction]]**

Master prompt engineering for optimal LLM performance. Learn prompt design, few-shot learning, chain-of-thought, and advanced techniques. Build effective prompts for agent tasks. Prompt engineering is critical for agent reliability and performance.

|Topic|Focus & Purpose|
|---|---|
|**[[5.1 Prompt Engineering Basics]]**|Prompt structure; clear instructions; role prompts; system messages; best practices; prompt templates. Fundamental prompting.|
|**[[5.2 Few-Shot Learning]]**|Examples in prompts; shot selection; example formatting; demonstration learning; task adaptation. Learning from examples.|
|**[[5.3 Chain-of-Thought (CoT)]]**|Step-by-step reasoning; "Let's think step by step"; CoT prompting; reasoning chains; complex problem solving. Reasoning prompts.|
|**[[5.4 System Messages & Roles]]**|System role; assistant role; user role; role management; personality design; agent personas. Role configuration.|
|**[[5.5 Temperature & Parameters]]**|Temperature control; top_p; frequency_penalty; presence_penalty; controlling randomness; output tuning. Generation control.|
|**[[5.6 Structured Output]]**|JSON mode; response format; schema enforcement; function calling basics; structured generation. Reliable outputs.|
|**[[5.7 Prompt Templates]]**|Jinja2 templates; f-strings; dynamic prompts; variable substitution; prompt libraries. Reusable prompts.|
|**[[5.8 Project: Prompt Library]]**|Building prompt collection; templates; few-shot examples; CoT prompts; evaluation; testing. Prompt repository.|

### **[[06 LangChain Framework]]**

Master LangChain for building LLM applications. Learn chains, agents, memory, and LangChain components. Build complex LLM workflows. LangChain is the most popular framework for LLM applications and essential for agent development.

|Topic|Focus & Purpose|
|---|---|
|**[[6.1 LangChain Introduction]]**|What is LangChain; core concepts; components; chains; when to use LangChain; ecosystem overview. Framework basics.|
|**[[6.2 LLMs & Chat Models]]**|LangChain LLMs; ChatOpenAI; chat models; model switching; provider integration; model configuration. Model interface.|
|**[[6.3 Prompts & Templates]]**|PromptTemplate; ChatPromptTemplate; MessagePromptTemplate; few-shot prompts; partial variables. Prompt management.|
|**[[6.4 Chains]]**|LLMChain; SequentialChain; SimpleSequentialChain; chain composition; LCEL (LangChain Expression Language). Workflow building.|
|**[[6.5 Memory Systems]]**|ConversationBufferMemory; ConversationSummaryMemory; message history; context management; stateful conversations. Conversation state.|
|**[[6.6 Tools & Tool Calling]]**|Tool definition; tool execution; function calling; tool schemas; integrating external functions. Agent capabilities.|
|**[[6.7 Output Parsers]]**|StrOutputParser; JsonOutputParser; PydanticOutputParser; structured outputs; validation. Response processing.|
|**[[6.8 Project: LangChain Chatbot]]**|Building conversational agent; memory; chains; tools; multi-turn conversations; context management. Complete LangChain app.|

### **[[07 RAG (Retrieval-Augmented Generation)]]**

Master RAG for grounding LLMs with custom knowledge. Learn embeddings, vector databases, retrieval, and RAG architectures. Build knowledge-based AI systems. RAG is essential for creating agents that work with proprietary data and domain-specific knowledge.

|Topic|Focus & Purpose|
|---|---|
|**[[7.1 RAG Fundamentals]]**|What is RAG; why RAG; RAG architecture; use cases; RAG vs fine-tuning; when to use RAG. Understanding RAG.|
|**[[7.2 Embeddings]]**|Text embeddings; OpenAI embeddings; sentence transformers; embedding models; vector representations; semantic similarity. Vectorization.|
|**[[7.3 Vector Databases]]**|What are vector databases; Pinecone; Chroma; FAISS; Qdrant; Weaviate; choosing vector DB. Storage solutions.|
|**[[7.4 Document Loading & Splitting]]**|Loading documents; text splitters; chunk size; chunk overlap; recursive splitting; semantic chunking. Document processing.|
|**[[7.5 Retrieval Strategies]]**|Similarity search; MMR (Maximum Marginal Relevance); metadata filtering; hybrid search; retrieval optimization. Finding relevant docs.|
|**[[7.6 Building RAG Pipeline]]**|Complete RAG flow; ingestion; embedding; storage; retrieval; generation; evaluation. End-to-end RAG.|
|**[[7.7 Advanced RAG Techniques]]**|Query rewriting; re-ranking; HyDE; multi-query retrieval; parent document retrieval; RAG optimization. Advanced patterns.|
|**[[7.8 Project: Knowledge Base Chatbot]]**|Building RAG chatbot; document ingestion; vector search; answer generation; source citations. Production RAG system.|

### **[[08 LangGraph for Agent Workflows]]**

Master LangGraph for building stateful, graph-based agent systems. Learn nodes, edges, state management, and complex workflows. Build sophisticated multi-step agents. LangGraph enables the most powerful and flexible agent architectures.

|Topic|Focus & Purpose|
|---|---|
|**[[8.1 LangGraph Introduction]]**|What is LangGraph; graphs vs chains; stateful workflows; when to use LangGraph; use cases. Graph-based agents.|
|**[[8.2 Graphs, Nodes & Edges]]**|StateGraph; Node definition; Edge types; conditional edges; graph structure; workflow design. Graph fundamentals.|
|**[[8.3 State Management]]**|TypedDict state; State updates; Annotated fields; Reducer functions; managing agent state. Stateful agents.|
|**[[8.4 ReAct Agents]]**|ReAct pattern; Reasoning + Acting; tool use; observation loops; create_react_agent; agent reasoning. Reasoning agents.|
|**[[8.5 Human-in-the-Loop]]**|Adding breakpoints; interrupt(); human approval; review nodes; interactive agents; human oversight. Human collaboration.|
|**[[8.6 Persistence & Checkpoints]]**|Memory savers; checkpointing; resuming workflows; state persistence; long-running agents. Workflow continuity.|
|**[[8.7 Sub-Graphs & Hierarchical Agents]]**|Nested graphs; hierarchical workflows; sub-agent patterns; complex agent architectures. Advanced structures.|
|**[[8.8 Project: Research Agent]]**|Building research agent; multi-step workflow; tool use; state management; ReAct pattern; iterations. Complex agent.|

### **[[09 Multi-Agent Systems]]**

Master building collaborative multi-agent systems. Learn agent orchestration, communication patterns, and frameworks (CrewAI, AutoGen). Build teams of specialized agents. Multi-agent systems enable sophisticated task decomposition and parallel processing.

|Topic|Focus & Purpose|
|---|---|
|**[[9.1 Multi-Agent Concepts]]**|Agent collaboration; communication patterns; orchestration strategies; hierarchical vs collaborative; design patterns. Fundamentals.|
|**[[9.2 CrewAI Framework]]**|What is CrewAI; Crew; Agent roles; Tasks; Process types; sequential/hierarchical flows. Role-based agents.|
|**[[9.3 Agent Roles & Tasks]]**|Defining agent roles; role specialization; task assignment; task dependencies; crew orchestration. Agent organization.|
|**[[9.4 Microsoft AutoGen]]**|AutoGen basics; ConversableAgent; GroupChat; agent conversations; collaborative problem solving. Conversational agents.|
|**[[9.5 Agent Communication]]**|Message passing; shared memory; event systems; inter-agent communication; coordination patterns. Agent interaction.|
|**[[9.6 Supervisor Pattern]]**|Supervisor agent; task delegation; result aggregation; control flow; managing worker agents. Orchestration pattern.|
|**[[9.7 Reflection & Self-Improvement]]**|Agent reflection; self-critique; iterative improvement; feedback loops; quality enhancement. Agent learning.|
|**[[9.8 Project: Multi-Agent Team]]**|Building agent team; specialized roles; task delegation; collaboration; complex workflow. Complete multi-agent system.|

### **[[10 Tools & Function Calling]]**

Master creating and integrating tools for agents. Learn function calling, tool schemas, and external API integration. Build agents that interact with the real world. Tools enable agents to perform actions beyond text generation.

|Topic|Focus & Purpose|
|---|---|
|**[[10.1 Function Calling Basics]]**|OpenAI function calling; function schemas; JSON schema; tool definitions; structured function calls. Tool fundamentals.|
|**[[10.2 Creating Custom Tools]]**|Tool decorators; LangChain tools; tool interfaces; input validation; error handling; tool documentation. Building tools.|
|**[[10.3 Web Search Tools]]**|Tavily API; web search integration; search tools; DuckDuckGo; Google Search API; web browsing agents. Internet access.|
|**[[10.4 Code Execution Tools]]**|Code interpreter; Python REPL; sandboxed execution; E2B; code generation and execution. Code agents.|
|**[[10.5 Database Tools]]**|SQL tools; database queries; data retrieval; SQLAlchemy; database agent patterns. Data access.|
|**[[10.6 API Integration Tools]]**|REST API tools; API wrappers; authenticated requests; third-party services; tool composition. External services.|
|**[[10.7 Tool Error Handling]]**|Retry logic; error recovery; graceful degradation; validation; tool reliability. Robust tools.|
|**[[10.8 Project: Research Assistant]]**|Building research tool suite; web search; code execution; data analysis; tool orchestration. Multi-tool agent.|

### **[[11 Agent Memory Systems]]**

Master implementing sophisticated memory for agents. Learn short-term, long-term, and semantic memory. Build agents that remember and learn. Memory enables personalized, context-aware agent interactions.

|Topic|Focus & Purpose|
|---|---|
|**[[11.1 Memory Types]]**|Short-term memory; long-term memory; working memory; semantic memory; episodic memory; memory architectures. Memory fundamentals.|
|**[[11.2 Conversation Memory]]**|Buffer memory; window memory; summary memory; token management; conversation tracking. Chat memory.|
|**[[11.3 Vector Memory]]**|Semantic memory; embedding-based recall; memory search; relevant memory retrieval; vector stores. Similarity-based memory.|
|**[[11.4 Entity Memory]]**|Entity extraction; entity tracking; relationship memory; knowledge graphs; structured memory. Entity-based recall.|
|**[[11.5 Memory Databases]]**|Redis for memory; PostgreSQL; memory persistence; memory storage patterns; database memory. Persistent memory.|
|**[[11.6 Memory Retrieval]]**|Memory search; relevance ranking; temporal decay; memory prioritization; smart recall. Finding memories.|
|**[[11.7 Memory Compression]]**|Summarization; memory pruning; compression techniques; managing memory size; efficient storage. Memory optimization.|
|**[[11.8 Project: Personal AI Assistant]]**|Building assistant with memory; user preferences; conversation history; personalization; memory management. Memory-enabled agent.|

### **[[12 Agent Evaluation & Testing]]**

Master evaluating and testing LLM agents. Learn evaluation metrics, benchmarks, and testing strategies. Build reliable, production-ready agents. Evaluation is critical for agent quality and reliability.

|Topic|Focus & Purpose|
|---|---|
|**[[12.1 Evaluation Basics]]**|Why evaluate; evaluation types; metrics; benchmarks; testing strategies; quality assurance. Assessment fundamentals.|
|**[[12.2 LLM-as-Judge]]**|Using LLMs for evaluation; evaluation prompts; scoring rubrics; consistency; automated evaluation. AI evaluation.|
|**[[12.3 Human Evaluation]]**|Human feedback; annotation; evaluation interfaces; inter-rater reliability; quality standards. Human assessment.|
|**[[12.4 Task-Specific Metrics]]**|Accuracy; precision/recall; F1 score; task completion rate; success metrics; custom metrics. Performance measurement.|
|**[[12.5 Agent Benchmarks]]**|GAIA benchmark; AgentBench; evaluation datasets; standardized tests; performance comparison. Benchmark testing.|
|**[[12.6 Unit Testing Agents]]**|pytest; mocking LLMs; test fixtures; integration tests; test coverage; CI/CD for agents. Testing frameworks.|
|**[[12.7 Cost & Latency Monitoring]]**|Token tracking; cost calculation; latency measurement; performance profiling; optimization metrics. Operational metrics.|
|**[[12.8 Project: Agent Test Suite]]**|Building evaluation suite; automated tests; metrics dashboard; benchmarking; quality gates. Testing infrastructure.|

### **[[13 Fine-Tuning & Model Customization]]**

Master fine-tuning LLMs for specialized tasks. Learn LoRA, QLoRA, and efficient fine-tuning techniques. Build custom models for your domain. Fine-tuning enables task-specific model optimization.

|Topic|Focus & Purpose|
|---|---|
|**[[13.1 Fine-Tuning Basics]]**|What is fine-tuning; when to fine-tune; RAG vs fine-tuning; use cases; datasets; preparation. Understanding fine-tuning.|
|**[[13.2 OpenAI Fine-Tuning]]**|OpenAI API fine-tuning; dataset format; training; validation; deploying fine-tuned models. GPT fine-tuning.|
|**[[13.3 LoRA & QLoRA]]**|Low-Rank Adaptation; QLoRA quantization; PEFT library; efficient fine-tuning; parameter-efficient methods. Modern fine-tuning.|
|**[[13.4 Dataset Preparation]]**|Dataset creation; format; quality; augmentation; validation split; best practices. Training data.|
|**[[13.5 Hugging Face Ecosystem]]**|Transformers library; datasets; models hub; training pipeline; AutoTrain. Open-source models.|
|**[[13.6 Evaluation After Fine-Tuning]]**|Model evaluation; holdout testing; comparing models; metric tracking; regression testing. Quality validation.|
|**[[13.7 Serving Fine-Tuned Models]]**|Model deployment; inference; Ollama; vLLM; HuggingFace Inference; hosting options. Model serving.|
|**[[13.8 Project: Custom Domain Model]]**|Fine-tuning for specific domain; dataset creation; training; evaluation; deployment. Specialized model.|

### **[[14 Production Deployment]]**

Master deploying LLM agents to production. Learn containerization, APIs, monitoring, and scaling. Build production-ready agent systems. Deployment skills transform prototypes into real-world applications.

|Topic|Focus & Purpose|
|---|---|
|**[[14.1 API Development]]**|FastAPI basics; endpoints; request/response; authentication; API design; RESTful principles. Building APIs.|
|**[[14.2 Containerization]]**|Docker basics; Dockerfile; docker-compose; container orchestration; deployment packaging. Containers.|
|**[[14.3 LangServe]]**|Deploying LangChain; LangServe setup; serving chains; API generation; production patterns. LangChain deployment.|
|**[[14.4 Monitoring & Logging]]**|LangSmith; logging; tracing; debugging; observability; error tracking; performance monitoring. Observability.|
|**[[14.5 Cloud Deployment]]**|AWS deployment; Google Cloud; Azure; serverless functions; managed services; scaling. Cloud platforms.|
|**[[14.6 Rate Limiting & Auth]]**|API rate limiting; authentication; API keys; JWT; security; access control. Security measures.|
|**[[14.7 Cost Optimization]]**|Token optimization; caching; batch processing; model selection; cost tracking; efficiency. Managing costs.|
|**[[14.8 Project: Production Agent API]]**|Building production API; Docker; monitoring; authentication; deployment; CI/CD. Production system.|

### **[[15 Advanced Agent Patterns]]**

Master advanced agent architectures and patterns. Learn planning, reflection, tool use patterns, and sophisticated agent behaviors. Build state-of-the-art agent systems. Advanced patterns enable complex, reliable agent applications.

|Topic|Focus & Purpose|
|---|---|
|**[[15.1 Planning Agents]]**|Plan-and-execute; task decomposition; multi-step planning; Plan-then-Act pattern; LLMCompiler. Strategic agents.|
|**[[15.2 Reflection & Critique]]**|Self-reflection; critique loops; Reflexion pattern; iterative improvement; quality enhancement. Self-improving agents.|
|**[[15.3 Tree of Thoughts]]**|ToT prompting; exploration; backtracking; search strategies; complex problem solving. Advanced reasoning.|
|**[[15.4 Agent-as-a-Service]]**|Agent APIs; microservices; agent composition; service orchestration; distributed agents. Service architecture.|
|**[[15.5 Streaming Responses]]**|Token streaming; real-time output; streaming APIs; user experience; progressive generation. Live responses.|
|**[[15.6 Safety & Guardrails]]**|Content filtering; safety checks; input validation; output moderation; ethical AI; responsible deployment. Safe agents.|
|**[[15.7 Multi-Modal Agents]]**|Vision + language; image understanding; DALL-E integration; multi-modal reasoning; GPT-4V. Beyond text.|
|**[[15.8 Project: Advanced Research Agent]]**|Building sophisticated agent; planning; reflection; tools; multi-step reasoning; production quality. State-of-art agent.|

### **[[16 Specialized Agent Applications]]**

Master building domain-specific agents. Learn code generation agents, data analysis agents, and specialized use cases. Build agents for real-world applications. Specialization enables high-value, production applications.

|Topic|Focus & Purpose|
|---|---|
|**[[16.1 Code Generation Agents]]**|Code interpreter; GitHub Copilot patterns; code analysis; debugging agents; programming assistants. Code agents.|
|**[[16.2 Data Analysis Agents]]**|Pandas integration; data visualization; statistical analysis; Python REPL; analytical agents. Data agents.|
|**[[16.3 Customer Support Agents]]**|Support workflows; ticket handling; knowledge bases; escalation; FAQ automation. Support automation.|
|**[[16.4 Content Generation Agents]]**|Writing assistants; content creation; blog generation; social media; creative agents. Content automation.|
|**[[16.5 Research & Summarization]]**|Research workflows; paper analysis; summarization; literature review; knowledge extraction. Research agents.|
|**[[16.6 SQL & Database Agents]]**|Text-to-SQL; query generation; database interaction; data retrieval; analytics agents. Database agents.|
|**[[16.7 Web Automation Agents]]**|Browser automation; web scraping; form filling; workflow automation; Playwright integration. Web agents.|
|**[[16.8 Project: Specialized Agent Suite]]**|Building multiple specialized agents; domain expertise; production quality; deployment; real use cases. Production agents.|

### **[[17 Agent Frameworks Comparison]]**

Master choosing and using different agent frameworks. Learn LangGraph, CrewAI, AutoGen, and custom solutions. Build framework-agnostic understanding. Framework knowledge enables optimal tool selection.

|Topic|Focus & Purpose|
|---|---|
|**[[17.1 Framework Landscape]]**|Agent frameworks overview; LangChain ecosystem; alternatives; when to use each; comparison. Understanding options.|
|**[[17.2 LangGraph Deep Dive]]**|Advanced LangGraph; complex workflows; state management; production patterns; best practices. LangGraph mastery.|
|**[[17.3 CrewAI Deep Dive]]**|CrewAI advanced features; crew patterns; role optimization; production deployment; scaling crews. CrewAI mastery.|
|**[[17.4 AutoGen Deep Dive]]**|AutoGen patterns; group chats; code execution; agent conversations; complex workflows. AutoGen mastery.|
|**[[17.5 Custom Agent Implementation]]**|Building without frameworks; pure Python agents; custom orchestration; when to build custom. Framework-free agents.|
|**[[17.6 Framework Integration]]**|Mixing frameworks; LangChain + others; migration strategies; interoperability; hybrid approaches. Combined solutions.|
|**[[17.7 Performance Comparison]]**|Benchmarking frameworks; latency; complexity; maintainability; developer experience. Framework evaluation.|
|**[[17.8 Project: Framework Comparison]]**|Building same agent in multiple frameworks; comparing approaches; performance; code quality. Hands-on comparison.|

### **[[18 Real-World Agent Projects]]**

Master building production agent applications. Learn complete project workflows from design to deployment. Build impressive portfolio pieces. Real projects demonstrate professional agent development skills.

|Topic|Focus & Purpose|
|---|---|
|**[[18.1 Autonomous Research Assistant]]**|Complete research agent; web search; analysis; summarization; report generation; citations. Research automation.|
|**[[18.2 Customer Service Bot]]**|Support agent; ticket handling; knowledge base; escalation; analytics; multi-channel. Support system.|
|**[[18.3 Code Review Agent]]**|Code analysis; review generation; bug detection; improvement suggestions; GitHub integration. Code quality agent.|
|**[[18.4 Data Analysis Platform]]**|SQL agent; data visualization; insights generation; report creation; dashboard agent. Analytics system.|
|**[[18.5 Content Creation System]]**|Multi-agent content pipeline; research; writing; editing; SEO optimization; publication. Content automation.|
|**[[18.6 Personal AI Assistant]]**|Multi-functional assistant; calendar; email; tasks; personalization; memory; proactive help. Personal agent.|
|**[[18.7 Document Processing Agent]]**|PDF processing; extraction; summarization; Q&A; document analysis; batch processing. Document automation.|
|**[[18.8 Full-Stack Agent Application]]**|Complete application; frontend; backend; agents; database; deployment; monitoring. Production system.|

---

## **Learning Path Recommendations**

### **Foundation Path** (0-2 months)

1. Python Fundamentals for AI (Module 1)
2. Data Structures for AI (Module 2)
3. Object-Oriented Python for AI (Module 3)
4. Basic Projects (Modules 1.8, 2.8, 3.8) _Prerequisites: Basic programming understanding_

### **Core Agent Development** (2-5