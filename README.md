### 🧠 About Me

I'm an **AI Engineer** based in Rotterdam, Netherlands, working on **LLM systems, agentic architectures, and NLP**. I build systems that are measured and evaluated, not just impressive in a demo.

- 🔭 Currently building **agentic systems** with LangGraph and MCP, deployed on AWS with Terraform and CI/CD
- 🧪 First co-author on a **2025 arXiv paper** on NLP explainability, validated by expert human evaluation
- 🎓 MSc ICT for Internet and Multimedia, **University of Padova**, 110/110
- 🇳🇱 Rotterdam-based, authorized to work in the Netherlands without sponsorship
- 💬 Ask me about agent security boundaries, LLM evaluation, or why most "agents" are actually workflows

---

### 🚀 Featured Projects

<table>
<tr>
<td width="50%">

**[Dealership Agent](https://github.com/aghababaeiali/dealership-agent)**
Multi-agent customer service system where authorization is structural, not prompted. Sub-agents split by tool permission scope, identity never enters tool schemas, PostgreSQL RLS enforces the boundary at the data layer. 71-case eval set for hallucinated action claims raised accuracy 0.690 → 0.901. Deployed to AWS ECS Fargate via Terraform.

</td>
<td width="50%">

**[Property Insights Assistant](https://github.com/aghababaeiali/property-insights-assistant)**
LangGraph workflow with SQL, RAG, and risk-scoring routing over PostgreSQL. Found and removed target leakage in the cancellation model, reported an honest 0.706 ROC-AUC. Deterministic answer grounding, LLM-as-judge, human review queue feeding a regression suite. Deployed on Azure.

</td>
</tr>
<tr>
<td width="50%">

**[arXiv Search Assistant](https://huggingface.co/spaces/aliabbi/research-agent)**
8-node LangGraph pipeline searching arXiv live, with query reformulation, per-paper re-ranking, contradiction detection, and grounded synthesis with citations. RAGAS Faithfulness 0.921.

</td>
<td width="50%">

**[Dutch Constitution RAG](https://huggingface.co/spaces/aliabbi/dutch-constitution-qa)**
End-to-end RAG with FastAPI, Docker, GitHub Actions CI/CD. Improved Faithfulness 0.55 → 0.86 via a documented A/B comparison after finding a chunking bug.

</td>
</tr>
</table>
