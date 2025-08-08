# IBM_Internship_Project
# Machine Fault Diagnosis Agent using IBM watsonx.ai
Imagine having a cutting-edge, interactive tool at your fingertips for diagnosing machine issues. This solution, powered by IBM watsonx.ai, taps into advanced foundation models and seamlessly integrates multiple tools to provide smart, contextual troubleshooting.
# Overview
This project showcases a Machine Fault Diagnosis Agent designed to assist users in pinpointing and fixing issues with industrial equipment, like strange vibrations, overheating, or odd noises. Powered by IBM watsonx.ai, the agent can seamlessly connect with tools such as Google Search, DuckDuckGo, Wikipedia, and Web Crawler to deliver thorough, context-aware answers. This initiative was developed by Riya as part of an IBM AICTE project at JIMS Engineering Management Technical Campus, AIML Department.
# Features
Interactive Querying: A conversational interface designed for diagnosing machines.

Multi-Tool Integration: It pulls information from web searches, Wikipedia, web crawling, and more to provide richer answers.

Custom Model Support: Utilizes IBM’s Meta-Llama-3-70B Instruct model, which can be configured to your needs.

Extensible: It’s simple to add new diagnostic tools or connect additional data sources.

Markdown-rich Replies: The outputs are neatly formatted for easy reading.

# Technology Stack
Python 3.11

IBM watsonx.ai SDKs (ibm_watsonx_ai, langchain_ibm)

LangGraph, LangChain Core

Requests, JSON, OS, getpass

# Getting Start
**Prerequisites**

Python 3.10 or 3.11 installed

IBM Cloud API Key with access to watsonx.ai

Jupyter environment (Notebook, JupyterLab, or IBM watsonx.ai Studio)

**Installation**

1. Clone the Repository
	git clone https://github.com/<your-username>/machine-fault-diagnosis-agent.git
	cd machine-fault-diagnosis-agent

2. Install Dependencies
   pip install -r requirements.txt
		(Or manually install: ibm_watsonx_ai, langchain_ibm, langgraph, requests, IPython, etc.)

**Usage**

1. Launch Jupyter Notebook
   
   jupyter notebook
	Open Machine_Fault_Diagnosis_Agent.ipynb.

3. Authenticate
   
	Enter your IBM Cloud API key when prompted.

5. Query the Agent

	Ask questions such as:

		“Why is my motor overheating?”

		“What causes excessive vibration in my CNC lathe?”

	The agent will analyze your question, use various external tools, and suggest possible causes and maintenance steps.

4. Modify or Extend

	Change the model ID or inference parameters as needed.

	Add additional tools in the relevant code sections for specialized diagnostics.

# Example Questions

What could cause overheating in a hydraulic pump?

Why does my lathe make noise at high RPM?

How to diagnose excessive vibration in industrial machines?

# Project Structure

Machine_Fault_Diagnosis_Agent.ipynb — Main demo notebook

requirements.txt — Python dependencies

Additional documentation files as needed

# Results

Provides troubleshooting and maintenance advice for a range of machine faults.

Integrates multiple information sources for accurate recommendations.

Easily extensible and adaptable for future improvements (e.g., IoT integration, voice interface).

# License

Licensed Materials – Copyright © 2024 IBM.

Distributed under the ILAN License.

Refer to LICENSE or IBM watsonx.ai documentation for details.

# Acknowledgements

IBM watsonx.ai Team & Documentation

LangChain and LangGraph libraries

Project guidance: JIMS Engineering Management Technical Campus

# Disclaimer:
This notebook was generated via IBM watsonx.ai Agent Lab. Use is subject to IBM’s licensing terms.
