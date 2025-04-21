# 🌐 Building AI Browser Agents

[![DeepLearning.AI](https://img.shields.io/badge/DeepLearning.AI-Short%20Course-blue)](https://www.deeplearning.ai/short-courses/building-ai-browser-agents/)
[![AGI, Inc](https://img.shields.io/badge/AGI,%20Inc-MultiOn-green)](https://www.agi-labs.ai/)

This repository contains materials and code examples from the DeepLearning.AI short course **"Building AI Browser Agents"**, taught by **Div Garg** and **Naman Garg**, Co-founders of AGI, Inc.

## 📚 Course Overview

AI browser agents can automate complex web tasks like logging into websites, filling out forms, navigating through pages, and even placing online orders. These agents leverage both visual information (screenshots) and structural data (HTML/DOM) to understand web pages, reason about appropriate actions, and execute them.

This course provides a comprehensive introduction to building robust and reliable AI browser agents, exploring their architecture, capabilities, limitations, and the advanced decision-making strategies that power them.

## 🎯 What You'll Learn

- 🏗️ Fundamentals of autonomous web agents including their architecture, key components, limitations, and decision-making strategies
- 🕷️ How to build web agents that can scrape websites and structure outputs based on natural language instructions
- 🔄 Techniques for creating autonomous web agents that can execute multiple tasks sequentially
- 🧠 The AgentQ framework and how it enables agents to self-correct through:
  - 🌳 Monte Carlo Tree Search (MCTS)
  - 🔍 Self-critique mechanisms
  - 🎯 Direct Preference Optimization (DPO)
- 🚀 Current state and future directions of AI agents

## 🗂️ Course Structure

This course consists of **8 lessons** with **4 code examples**:

1. 🌟 **Introduction**
   - Overview of the course and its objectives

2. 🤖 **Intro to Web Agents**
   - What web agents are and how they work
   - Key components and architecture
   - Current limitations and challenges

3. 🕷️ **Building a Simple Web Agent**
   - Creating a basic web agent to scrape the DeepLearning.AI website
   - Returning course recommendations in structured output format
   - Processing natural language instructions

4. 🚀 **Building an Autonomous Web Agent**
   - Building autonomous web agents using the MultiOn API.
   - Manage sessions, navigate URLs, and execute tasks automatically
   - Use a custom MultiOnClient class for simplified control
   - Tasks run without user input; results include screenshots for feedback

5. 🧠 **Agent Q**
   - Introduction to the AgentQ framework
   - How AgentQ enables self-correction
   - Overview of Monte Carlo Tree Search (MCTS), Self-Critique Mechanism & Process Supervision, and Direct Preference Optimization (DPO)

6. 🌳 **Deep Dive into AgentQ and MCTS**
   - Explore Monte Carlo Tree Search (MCTS) and AgentQ algorithms in a gridworld setting
   - Run MCTS with varying exploration weights to analyze performance

7. 🔮 **Future of AI Agents**
   - Key factors shaping AI agents proliferation
   - Hardware, algorithms, and data availability considerations
   - Web agents challenges and current solutions
   - Benchmarking web agents with Realistic Evaluations for Agents Leaderboard (REAL) benchmark
   - Multi-agent systems and design needs
   - Future trends and potential applications

8. 🏁 **Conclusion**
   - Summary of key learnings

## 💻 Code Examples

The repository includes four hands-on code examples:

1. 🕸️ **Simple Web Agent** - Build a simple web-scraping agent using Playwright to extract and visualize website content programmatically.

2. 🤖 **Autonomous Web Agent** - Build an autonomous web agent using MultiOn API to automate tasks like logging into websites, filling out forms, and navigating through pages.

3. 🧠 **AgentQ and MCTS Implementation** - Implement Monte Carlo Tree Search (MCTS) and AgentQ algorithms in a gridworld setting to explore and optimize agent behavior.

## 🚀 Getting Started

### Prerequisites

```bash
# Clone the repository
git clone https://github.com/duybaohuynhtan/Building-AI-Browser-Agents.git
cd Building-AI-Browser-Agents

# Install required packages
pip install -r requirements.txt
```

### Running the Examples

Each code example is provided as a Jupyter notebook:

```bash
jupyter notebook
```

Navigate to the `notebooks/` directory and open the desired example.

## 📋 Requirements

- 🐍 Python
- 🐼 Pandas 2.2.3
- 🎭 Playwright 1.51.0
- 🧠 OpenAI 1.70.0
- 🔍 Pydantic 2.11.1
- 📊 Tabulate 0.9.0
- 🔑 Python-dotenv 1.1.0
- 🌐 MultiOn 1.3.8
- 🌊 Seaborn 0.13.2
- 🖼️ Gradio 5.23.2
- 🥒 Pickleshare 0.7.5
- 🔗 LangSmith 0.3.21
- 👨‍🏫 Instructor 1.7.8
- 🔤 Litellm 1.65.1
- 📊 Igraph 0.11.8
- 📈 Plotly 6.0.1

## 🔗 Additional Resources

- [DeepLearning.AI Course Link](https://www.deeplearning.ai/short-courses/building-ai-browser-agents/)
- [MultiOn Documentation](https://docs.multion.ai/welcome)
- [AgentQ Paper](https://arxiv.org/abs/2408.07199)

## 👨‍🏫 Instructors

- [**Div Garg**](https://www.linkedin.com/in/div99/) - Co-founder of AGI, Inc
- [**Naman Garg**](https://www.linkedin.com/in/namangarg20/) - Co-founder of AGI, Inc

## 🙏 Acknowledgments

Special thanks to **DeepLearning.AI** and **AGI, Inc** for creating such comprehensive learning materials.