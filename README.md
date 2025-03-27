# ResearchAgent 

Welcome to my **Research Agent** project! This is a personal tool I’ve built to automate the process of gathering and organizing research on any topic, making deep dives into new subjects easier and faster. 🧠💡
Our goal is to enable your agents to collaborate effectively on complex tasks, maximizing their collective intelligence and capabilities.

This tool allows you to:

**Input:** Just provide a topic of interest.  
**Output:** A **detailed, well-structured research report** on that topic, automatically generated! check out this [report](https://github.com/Adity-star/Research-Agent/blob/main/output/report.md)

The goal is to save time and effort in compiling research data by automating the collection and organization of information. The research agent intelligently gathers relevant sources, analyzes them, and generates reports with structured insights.

##  **How It Works**

1. **Input a Topic**: You provide the research topic you want to explore.
2. **Automatic Report Generation**: The agent compiles the best available information, summarizes key points, and organizes it into a detailed report.


## **Current Features**
- **Topic-based Search**: Search by any topic and get structured data.
- **Data Analysis**: Intelligent summarization and insights from multiple sources.
- **Customizable Reports**: Generate detailed reports with personalized insights.

##  **Future Plans**
- **Expand Topic Coverage**: Add more topics and sources.
- **Improve AI Capabilities**: Make the agent smarter and more efficient at analyzing data.
- **Integrate More Formats**: Enhance report generation with additional export options (PDF, HTML, etc.).


## Installation

Ensure you have Python >=3.10 <3.13 installed on your system. This project uses [UV](https://docs.astral.sh/uv/) for dependency management and package handling, offering a seamless setup and execution experience.

First, if you haven't already, install uv:

```bash
pip install uv
```

Next, navigate to your project directory and install the dependencies:

(Optional) Lock the dependencies and install them by using the CLI command:
```bash
crewai install
```
### Customizing

**Add your `OPENAI_API_KEY` into the `.env` file**

- Modify `src/research_crew/config/agents.yaml` to define your agents
- Modify `src/research_crew/config/tasks.yaml` to define your tasks
- Modify `src/research_crew/crew.py` to add your own logic, tools and specific args
- Modify `src/research_crew/main.py` to add custom inputs for your agents and tasks

## Running the Project

To kickstart your crew of AI agents and begin task execution, run this from the root folder of your project:

```bash
$ crewai run
```

This command initializes the research_crew Crew, assembling the agents and assigning them tasks as defined in your configuration.

This example, unmodified, will run the create a `report.md` file with the output of a research on LLMs in the root folder.

## Understanding Your Crew

The research_crew Crew is composed of multiple AI agents, each with unique roles, goals, and tools. These agents collaborate on a series of tasks, defined in `config/tasks.yaml`, leveraging their collective skills to achieve complex objectives. The `config/agents.yaml` file outlines the capabilities and configurations of each agent in your crew.


##  **How to Contribute**

If you’d like to contribute to this project, feel free to fork the repo, make changes, and open a pull request! I’m open to new ideas, enhancements, and bug fixes.

##  **Stay Tuned**

I will continue to refine this tool, and I look forward to sharing updates as I build on its capabilities.

---
