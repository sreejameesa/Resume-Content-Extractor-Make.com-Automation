# Resume-Content-Extractor-Make.com-Automation
A Make.com workflow that extracts resume content from a Google Doc using pattern matching, then returns the parsed output for downstream processing.
Three-step Make.com scenario that pulls structured content out of a Google Docs resume.
How it works:

Text Parser — runs a regex pattern match against raw text input to identify and extract resume sections
Google Docs — fetches the full content of a specified document
Scenarios (Return output) — passes the parsed result back as structured output for use in other workflows or tools

Built this to feed into a larger resume analysis pipeline. The parsed output plugs directly into an ATS scoring workflow.
Tools used: Make.com (formerly Integromat), Google Docs API, Text Parser module
