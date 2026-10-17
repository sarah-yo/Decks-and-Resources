# Kinda chic to be pwnd by your own agent - useful resources

Links and further reading from my Experts Live Switzerland 2026 keynote on AI agent security.

## The stories from the talk

### OpenAI's agents and government systems
- [iTnews: OpenAI agent accessed credentials via Medicare data portal](https://www.itnews.com.au/news/openai-agent-accessed-credentials-via-medicare-data-portal-629297)
- [Transluce: AI agent activity against US and Canadian government sites](https://transluce.org/us-canada-gov)

### The agent that wrote a hit piece
Scott Shambaugh's own account, in four parts:
- [Part 1: An AI agent published a hit piece on me](https://theshamblog.com/an-ai-agent-published-a-hit-piece-on-me/)
- [Part 2: More things have happened](https://theshamblog.com/an-ai-agent-published-a-hit-piece-on-me-part-2/)
- [Part 3: Forensics and more fallout](https://theshamblog.com/an-ai-agent-published-a-hit-piece-on-me-part-3/)
- [Part 4: The operator came forward](https://theshamblog.com/an-ai-agent-wrote-a-hit-piece-on-me-part-4/)

### PocketOS: production, deleted in nine seconds
- [The Register: coding agent deletes a startup's production database](https://www.theregister.com/software/2026/04/27/cursor-opus-agent-snuffs-out-startups-production-database/5224442)

### Moltbook: 1.5 million API keys and one switched-off setting
- [Wiz: Exposed Moltbook database reveals millions of API keys](https://www.wiz.io/blog/exposed-moltbook-database-reveals-millions-of-api-keys)
- [OpenAI misalignment reports](https://alignment.openai.com/misalignment-reports/)

### Replit and SaaStr: wiped prod in a code freeze
- [The Register: Replit deleted a user's production database](https://www.theregister.com/2025/07/21/replit_saastr_vibe_coding_incident/)
- [Paper: Agentic Cryptographic Debt (the post-quantum "migration" that wasn't)](https://www.mdpi.com/2073-431X/15/9/625)

### GitLost: "Additionally..." leaked private repos
- [Noma Labs: GitLost - how we tricked GitHub's AI agent into leaking private repos](https://noma.security/noma-labs/gitlost-how-we-tricked-githubs-ai-agent-into-leaking-private-repos)
- [Simon Willison: The lethal trifecta for AI agents](https://simonwillison.net/2025/Jun/16/the-lethal-trifecta/)

### The npm worms
- [Datadog Security Labs: Shai-Hulud 2.0 npm worm](https://securitylabs.datadoghq.com/articles/shai-hulud-2.0-npm-worm/)
- [Endor Labs: SANDWORM_MODE - dissecting a multi-stage npm supply chain attack](https://www.endorlabs.com/learn/sandworm-mode-dissecting-a-multi-stage-npm-supply-chain-attack)
- [StepSecurity: ChainDrop npm worm](https://www.stepsecurity.io/blog/chaindrop-npm-worm)

### The OpenAI and Hugging Face incident
- [Video: Black Hat USA 2026 - The 'Breaking' News: The OpenAI-Hugging Face Incident](https://www.youtube.com/watch?v=87DyyMV0kCY)
- [Hugging Face: agent intrusion technical timeline](https://huggingface.co/blog/agent-intrusion-technical-timeline)

## Other good reads

- [OWASP Top 10 for LLM and GenAI applications](https://genai.owasp.org/llm-top-10/)

## Microsoft security research

- [Microsoft Digital Defense Report 2026](https://www.microsoft.com/en-us/corporate-responsibility/topics/cybersecurity/reports/microsoft-digital-defense-report/)
- [Insights from the 2026 Microsoft Digital Defense Report](https://www.microsoft.com/en-us/security/blog/2026/10/01/insights-from-the-2026-microsoft-digital-defense-report/)
- [Observability for AI systems: strengthening visibility for proactive risk detection](https://www.microsoft.com/en-us/security/blog/2026/03/18/observability-ai-systems-strengthening-visibility-proactive-risk-detection/)
- [Defense in depth for autonomous AI agents](https://www.microsoft.com/en-us/security/blog/2026/05/14/defense-in-depth-autonomous-ai-agents/)
- [Securing AI agents: when AI tools move from reading to acting](https://www.microsoft.com/en-us/security/blog/2026/06/30/securing-ai-agents-ai-tools-move-from-reading-acting/)
- [Least privilege for AI agents: identity, access and tool binding](https://www.microsoft.com/en-us/security/blog/2026/07/16/least-privilege-for-ai-agents-identity-access-and-tool-binding/)

## Microsoft tooling to look at

### Identity
- [What is Microsoft Entra Agent ID?](https://learn.microsoft.com/en-us/entra/agent-id/what-is-microsoft-entra-agent-id)
- [Managed identities for Azure resources](https://learn.microsoft.com/en-us/entra/identity/managed-identities-azure-resources/overview)

### Config and exposure
- [Azure Key Vault](https://learn.microsoft.com/en-us/azure/key-vault/general/overview)
- [GitHub secret scanning push protection](https://docs.github.com/en/code-security/secret-scanning/introduction/about-push-protection)
- [AI security posture management in Defender for Cloud](https://learn.microsoft.com/en-us/azure/defender-for-cloud/ai-security-posture)

### Guardrails
- [Hosted agents in Foundry Agent Service (each session sandboxed)](https://learn.microsoft.com/en-us/azure/foundry/agents/concepts/hosted-agents)

### Untrusted input
- [Prompt Shields in Azure AI Content Safety](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/concepts/jailbreak-detection)
- [API Management llm-content-safety policy (covers MCP and A2A traffic)](https://learn.microsoft.com/en-us/azure/api-management/llm-content-safety-policy)

### Supply chain
- [Govern MCP tools with an AI gateway in Foundry](https://learn.microsoft.com/en-us/azure/foundry/agents/how-to/tools/governance)
- [Azure API Center](https://learn.microsoft.com/en-us/azure/api-center/overview)
- [Dependabot](https://docs.github.com/en/code-security/dependabot)

### Observability and red teaming
- [Microsoft Agent 365, now generally available](https://www.microsoft.com/en-us/security/blog/2026/05/01/microsoft-agent-365-now-generally-available-expands-capabilities-and-integrations/)
- [Discover local AI agents with Microsoft Defender for Endpoint](https://learn.microsoft.com/en-us/defender-endpoint/discover-local-ai-agents)
- [Transition of agent security features to Agent 365](https://learn.microsoft.com/en-us/defender-xdr/security-for-ai/transition-agent-security-to-agent-365)
- [PyRIT - Python Risk Identification Tool for generative AI](https://github.com/Azure/PyRIT)
- [AI Red Teaming Agent in Azure AI Foundry](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/ai-red-teaming-agent)
- [Microsoft AI Red Team playground labs](https://github.com/microsoft/AI-Red-Teaming-Playground-Labs)

## Where Microsoft is at

- [Agents built into your workflow: Security Copilot with Microsoft 365 E5](https://www.microsoft.com/en-us/security/blog/2025/11/18/agents-built-into-your-workflow-get-security-copilot-with-microsoft-365-e5/)
- [Video: MDASH at Microsoft Build 2026](https://www.youtube.com/watch?v=8QBDaRbur70)
- [Defense at AI speed: Microsoft's new multi-model agentic security system (MDASH)](https://www.microsoft.com/en-us/security/blog/2026/05/12/defense-at-ai-speed-microsofts-new-multi-model-agentic-security-system-tops-leading-industry-benchmark/)
- [Microsoft Build 2026: securing code, agents and models across the development lifecycle](https://www.microsoft.com/en-us/security/blog/2026/06/02/microsoft-build-2026-securing-code-agents-and-models-across-the-development-lifecycle/)
- [Rethinking security for the age of AI (Project Perception)](https://blogs.microsoft.com/blog/2026/07/27/rethinking-security-for-the-age-of-ai/)
- [Reimagining the SOC for the agentic era in Microsoft Defender (ISOC)](https://www.microsoft.com/en-us/security/blog/2026/09/23/reimagining-the-soc-for-the-agentic-era-in-microsoft-defender/)
- [Integrated Security Operations Center (ISOC) in Microsoft Defender](https://learn.microsoft.com/en-us/defender-xdr/isoc-overview)
- [Microsoft Ignite, 17-20 November 2026](https://ignite.microsoft.com/en-US/home)

## More from me

- [Azure Security Podcast](https://azsecuritypodcast.net/)
