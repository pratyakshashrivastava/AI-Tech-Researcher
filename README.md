# AI-Tech-Researcher

AI-Tech-Researcher is a deployed Smartly agent designed to research and summarize AI and technology topics using reliable external sources.

## Features

- Researches AI and technology topics.
- Uses external web search when current information is required.
- Organizes information into clear sections.
- Provides key concepts, applications, advantages, and limitations.
- Mentions sources when external information is used.
- Handles web-search failures using a fallback approach.
- Produces concise and structured Markdown responses.

## Workflow

The agent follows a simple research workflow:

Search → Analyse → Summarize

1. Search
   - Finds relevant and reliable external sources.

2. Analyse
   - Reviews and organizes the retrieved information.
   - Evaluates source relevance and reliability.

3. Summarize
   - Generates a structured answer.
   - Includes relevant sources and uncertainty where necessary.

## Documentation

Detailed project documentation is available in the `docs` folder:

- `system-prompt.md` — System instructions and response guidelines.
- `workflow.md` — Research workflow and source handling.
- `testing.md` — Test cases and testing results.
- `improvements.md` — Project improvements and future enhancements.

## Current Limitations

- External web search may occasionally be unavailable.
- Current information cannot be externally verified when the search service fails.
- Additional testing is required for complex multi-source research questions.

## Future Improvements

- Improve web-search reliability.
- Improve source ranking and evaluation.
- Improve citation handling.
- Add more complex test cases.
- Improve response consistency.

## Project Status

Active development — the agent is being continuously tested and improved.

## Summary

AI-Tech-Researcher combines structured prompting, external research, source evaluation, and response synthesis to provide clear and reliable AI and technology research.
