###  Hi, I'm Suhas Hanamannavar

I'm an open-source engineer based in Bangalore, specializing in **AI/LLM infrastructure** and developer tooling. I build production-grade systems with clean code, strong testing practices, and careful attention to maintainability.

---

###  Open Source Contributions

I believe in contributing back to the tools that power our industry. My work has been reviewed and accepted by maintainers of major AI infrastructure projects:

#### [LiteLLM (BerriAI) — 10,000+ ★](https://github.com/BerriAI/litellm)
**LLM Gateway used by production AI teams worldwide**
- **[PR #44320](https://github.com/BerriAI/litellm/pull/44320):** Fixed a data correctness bug in the health check system where results were being cross-attributed across deployments sharing the same model name. Added `_get_model_infos_for_endpoint()` helper that matches by `model_id` first, preventing incorrect attribution when multiple deployments (different `api_base`, model-group aliases) share a model name.

#### [Soup (MakazhanAlpamys) — 8,000+ ★](https://github.com/MakazhanAlpamys/Soup)
**AI/ML Supply Chain & Provenance Tooling**
- **[PR #1565](https://github.com/MakazhanAlpamys/Soup/pull/1565):** CycloneDX BOM — fixed invalid UUID serial number format (`urn:uuid:` + RFC 4122 dashed form) and corrected license field usage
- **[PR #1566](https://github.com/MakazhanAlpamys/Soup/pull/1566):** SPDX BOM — corrected `BUILD_DEPENDENCY_OF` relationship direction for training data (training data is a build dependency of the model, not vice versa)
- **[PR #1567](https://github.com/MakazhanAlpamys/Soup/pull/1567):** SLSA provenance — added invocation command to `predicate.buildDefinition.externalParameters`
- **[PR #1568](https://github.com/MakazhanAlpamys/Soup/pull/1568):** CLI testing — fixed `json.loads()` test isolation from stderr warnings (Click 8.2 mixes stderr into `result.output`)
- **[PR #1571](https://github.com/MakazhanAlpamys/Soup/pull/1571):** Network security — added remedy hints to private IP refusal messages, consolidated `0.0.0.0` handling across modules


---

###  Technical Stack

| Category | Technologies |
|---|---|
| **Languages** | Python · TypeScript · JavaScript · Dart · C++ · HTML/CSS |
| **AI/LLM** | LangChain · LlamaIndex · LiteLLM · RAG pipelines · LLM APIs · Prompt Engineering |
| **Backend** | FastAPI · Click/Typer CLI · Pydantic · pytest · REST APIs |
| **Tools** | Git · GitHub · CI/CD · ruff · rich console |

---

###  Open To

I'm currently accepting **contract and full-time opportunities** for:
-  LLM Agent development and AI infrastructure
-  RAG system design and implementation
-  AI developer tooling and CLI tools
-  Python backend development for AI products

If you're building production AI systems and need an engineer who can debug complex codebases and ship clean, tested solutions — let's talk.

📧 **Email:** hanamannavarsuhas17@gmail.com

---

