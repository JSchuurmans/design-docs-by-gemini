# design-docs-by-gemini
Agentic system for creating a Design Doc using Google's [Agent Development Kit](https://google.github.io/adk-docs/agents/llm-agents/) [Python package](https://github.com/google/adk-python/blob/main/README.md).
The goal of this system is to speed up the process of creating Design Docs.

# Design Docs
_“The design doc documents the **high-level implementation strategy** and key design decisions with emphasis on the **trade-offs** that were considered during those decisions.”_ [Malte Ubl](https://www.industrialempathy.com/posts/design-docs-at-google/)

It helps you start early with making decisions and sharing knowledge.
Early identification and reduction of risk helps you prepare for change and reduce unknown-unknowns.
Making decisions early helps you move fast and may reduce attrition of other engineers if they can be involved with designs.
Sharing knowledge creates organizational memory.

A design doc contains 5 sections:
- Context & Scope
- Goals & Non-Goals
- The Design
- Alternatives Considered
- Cross-cutting Concerns

The key is collaboration, so why not add an agentic side-kick to the team you create a design doc with.

# Final notes
This project is inspired by https://github.com/JasperHG90/rfcrew.
