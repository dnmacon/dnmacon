Built, operated, and secured production software and infrastructure. Researching agent memory, evaluation, and the limits on what model-written code can reach.

I work in the open at [alignment.farm](https://alignment.farm) and in [alignment-farm](https://github.com/alignment-farm) and [stack-research](https://github.com/stack-research).

### Working on

- [**construct**](https://github.com/alignment-farm/construct): research lab for governed agent memory, in Python. The harness chooses the context a model receives and scores the result against an external check. Spoofing an unauthenticated memory channel changed answers; authenticating that channel stopped the spoof. Pruning cold state and rematerializing it cut hot-context tokens by about 57% at matched answer quality. On a continuity test, governed memory passed 24 of 24 relevant cases against 6 of 24 for canonical state alone.
- [**construct-2**](https://github.com/alignment-farm/construct-2): studies of how an agent accumulates experience across sessions, and where it should live: explicit memory, lessons, executable tools, weights, or runtime rules. The clearest result is that learning a pattern, keeping it useful, and repaying its cost are separate. On a directly addressable collection, cheaper explicit access matched learned retrieval.
- [**substrate**](https://github.com/alignment-farm/substrate): local-first shared rooms, in Go. People, agents, and tools take turns in one conversation. The room is an append-only directory of Markdown, and every interface uses the same turn rules.
- [**materialize**](https://github.com/alignment-farm/materialize): builds an isolated workspace from a read manifest. Only declared paths are copied, a denylisted path aborts the build, and a hash audit records exactly what was present. Used to keep a red team, and separately a builder, inside a declared file surface.

### Writing

- [The Unaskable Question](https://alignment.farm/field-notes/the-unaskable-question/): mapping the negative space of language models (field-note, in progress)

### Background

Engineering consultant and former CTO. Experience in building systems, owning production infrastructure, security, architecture, technical leadership, and self-directed experimental work.
- Agent memory and evaluation
- Applied model systems
- Cloud infrastructure and legacy modernization

---

#### ATS Soup

**Languages:** Python, TypeScript, Go, Ruby, Bash.

**Applied models:** LLM integration, retrieval-augmented generation (RAG), structured generation, context engineering, agent and tool workflows, model harnesses, persistent agent memory, PyTorch, Ray, LoRA fine-tuning, reinforcement learning from verifiable rewards, evaluation harnesses, experiment tracking, Bedrock, SageMaker, MLX, vLLM-Metal, llama.cpp.

**Data and infrastructure:** Spark, Parquet, PostgreSQL (pgvector), S3 Vectors, SQL, NoSQL, key-value, and vector data modeling, streaming pipelines, fault isolation, Docker, Kubernetes, AWS (CDK v2, CloudFormation, Terraform, CodePipeline, EventBridge), distributed tracing.

**Security:** Application and cloud security, threat modeling, penetration testing, sandboxed execution (gVisor, Firecracker), tool permissions, auditable workspaces, zero trust, secrets management, SOC 2, HITRUST.

**Architecture:** System and API design, event-driven and service-oriented systems, incremental legacy migration, dependency decomposition, technical risk assessment, technical writing.

**Certified:** [AWS Certified Generative AI Developer – Professional](https://www.credly.com/badges/963321dd-5a52-4e2f-a8be-411543b9311d/public_url) (Issued December 2025)
