# 🧪 Bedrock Curiosity Lab

This repository is a collection of curiosity-driven mini-projects. I stumbled upon **Amazon Bedrock** and **Amazon SageMaker** while researching how to build a custom AI companion to help with my daily workflows and coding tasks.

## 🛠️ SageMaker vs. Bedrock (Why I Chose Bedrock)

| Service | Primary Purpose | Control Level |
| :--- | :--- | :--- |
| **Amazon Bedrock** | Fully managed, serverless platform for orchestrating foundation models (Claude, Llama, Titan, Amazon Nova). | Serverless / Managed API |
| **Amazon SageMaker** | Comprehensive ML platform for building, training, tuning, and deploying custom models. | Full Infrastructure Control |

> **Bottom line:** I chose **Amazon Bedrock** because it is developer-friendly, easy to set up, and—most importantly—significantly cheaper than running dedicated SageMaker infrastructure *(because I'm broke)*. 

## 🎯 Goal & Motivation

The main reason I ended up here? I cannot afford Claude Code subscription🥲 fees to help with my everyday development tasks. 

My goal is to learn the fundamentals of Amazon Bedrock from scratch—starting with simple raw prompts and eventually building a custom AI agent that integrates directly into my IDE (VS Code) to assist me while coding.

## 📁 Repository Structure

Most projects in this repository share a core set of modules designed to be reusable (similar to Terraform modules or a shared Python library):

```text
├── common/
│   ├── clients.py     # AWS client setups
│   ├── guardrail.py   # Custom guardrails for AI safety/behavior
│   └── budget.py      # Spending limits to prevent surprise bills
└── project-*/         # Mini-projects building up to the AI agent
```

I hope I'll be able to build something useful here. And hoping I'll be able to share the agent to others🤖.

P.S: I'll be adding projects in this repository, and if ever a project becomes a bit complex, it will have it's dedicated repository.