# LangGraph-Autonomous-Multi-Agent-Research-System

The project creates a smart research assistant using LangGraph, designed to act like a team of AI experts that collaborate to build a complete report.

The workflow follows these steps:

1. Topic Analysis: You provide a research topic, and the system automatically generates a panel of specialized AI analysts to study it.

2. Human Feedback: The process pauses, allowing you to review, approve, or suggest revisions to the analyst personas before the actual work starts.
3. Parallel Research: The analysts conduct interviews with virtual professionals simultaneously, using Tavily to search the internet for factual information and evidence.
4. Report Synthesis: Finally, the system aggregates all research, transcripts, and insights from these interviews into a structured, cited Markdown research report.
