# MCP Quick-Start Briefing (English)

*Sources: Wikipedia, "Model Context Protocol" — Background section summary and the article's key facts. Prepared for new hires joining the tooling team.*

## Background

The Model Context Protocol (MCP) was announced by Anthropic in November 2024 as an open standard for connecting AI assistants to data systems such as content repositories, business management tools, and development environments. The protocol was created at Anthropic by engineers David Soria Parra and Justin Spahr-Summers, and was designed to address information silos and legacy systems. Before MCP, developers often had to build custom connectors for each data source or tool, resulting in what Anthropic described as an "N×M" data integration problem.

Earlier approaches — such as OpenAI's 2023 "function-calling" API and the ChatGPT plug-in framework — solved similar problems but required vendor-specific connectors. MCP reuses the message-flow ideas of the Language Server Protocol (LSP).

In December 2025, Anthropic donated MCP to the Agentic AI Foundation (AAIF), a directed fund under the Linux Foundation co-founded by Anthropic, Block and OpenAI, with support from other companies. Later that month, Anthropic also published Agent Skills, a companion open standard for packaging task-specific instructions and resources that AI agents load on demand.

## Key facts

- MCP is an open standard and open-source framework introduced by Anthropic in November 2024 to standardize how AI systems like large language models (LLMs) integrate and share data with external tools, systems, and data sources.
- MCP provides a standardized interface for reading files, executing functions, and handling contextual prompts.
- Following its announcement, the protocol was adopted by major AI providers, including OpenAI and Google DeepMind.
- In December 2025, Anthropic donated MCP to the Agentic AI Foundation, a fund under the Linux Foundation.
