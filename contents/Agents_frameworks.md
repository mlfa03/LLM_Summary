<p id="reading-time-action-id" align="left">1 min read</p>

[**← Back to contents**](../common/contents.md)

# Agents Frameworks

Some points about Multi agents apps:
* Recommendation: do not create Multi-Agent LLM Apps with too many
hierarchy levels.
* Each agent of the Multi-Agent LLM App can use a different LLM.

## LangGraph

* Framework to build multi agents apps
* Launched February 2024
*  Core functionality of AI Agents are loops; the core functionality of
LangGraph are cycles.

Adding control is important with agents otherwise they can get into a loop. Control can be added by:

* Force to call a particular tool first.
* Control over how tools are called.
* Control over prompts.

Documentation: https://www.langchain.com/langgraph

## CrewAI
* Open source framework built on top of LangChain

Documentation: https://www.crewai.com/

_Put your content here_

## The End

[**Continue to Contributions →**](../common/contributions.md)
