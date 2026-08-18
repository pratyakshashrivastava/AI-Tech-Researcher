# AI Tech Researcher

An AI research agent built on Smartly Infra to research and summarize AI and technology topics using external web sources.

## Overview

The agent is designed to:
- Research a given AI or technology topic.
- Use reliable external sources when current or source-backed information is needed.
- Organize findings into a clear, readable structure.
- Explain key concepts, applications, advantages, disadvantages, and limitations.
- Compare models or approaches when requested.
- End with a concise summary.

## Workflow

```text
User Question
     ↓
Web Search
     ↓
Find Relevant Sources
     ↓
Synthesize Findings
     ↓
Structured Answer
     ↓
Summary
```

## Build

- Platform: Smartly Infra
- Agent type: Research
- Agent name: AI Tech Researcher
- Primary tool: Web Search
- Workflow steps: Search → Summarize
- Advanced mode: Enabled

## Example Use Cases

- Explain technical concepts such as DSA, SDLC, AI, ML, and cloud computing.
- Compare software development models.
- Research recent technology developments.
- Summarize technical topics in a structured format.
- Explain advantages, disadvantages, and practical applications.

## Improvements

The agent was iteratively improved by:
1. Adding a structured response format.
2. Making advantages and disadvantages explicit requirements.
3. Requiring a final summary.
4. Improving the search workflow.
5. Testing the agent with repeated technical questions.
6. Refining prompts when the agent produced incomplete answers.

## Current Status

The agent is deployed on Smartly Infra and is being tested and improved through versioned configurations.

> Note: This repository documents the agent, prompts, workflow, and testing approach. The hosted Smartly Infra configuration itself is not source code and is not reproduced here.

## Future Improvements

- Better source prioritization and verification.
- More detailed output schemas.
- Additional research tools where appropriate.
- Better handling of failed web searches.
- More robust evaluation using a fixed test-question set.
