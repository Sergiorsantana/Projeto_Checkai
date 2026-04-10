# Projeto_Checkai
Fluxo_Checkai


Langflow is a powerful platform for building and deploying AI-powered agents and workflows. It provides developers with both a visual authoring experience and built-in API and MCP servers that turn every workflow into a tool that can be integrated into applications built on any framework or stack. Langflow comes with batteries included and supports all major LLMs, vector databases and a growing library of AI tools.

✨ Highlight features
Visual builder interface to quickly get started and iterate.
Source code access lets you customize any component using Python.
Interactive playground to immediately test and refine your flows with step-by-step control.
Multi-agent orchestration with conversation management and retrieval.
Deploy as an API or export as JSON for Python apps.
Deploy as an MCP server and turn your flows into tools for MCP clients.
Observability with LangSmith, LangFuse and other integrations.
Enterprise-ready security and scalability.
🖥️ Langflow Desktop
Langflow Desktop is the easiest way to get started with Langflow. All dependencies are included, so you don't need to manage Python environments or install packages manually. Available for Windows and macOS.

📥 Download Langflow Desktop

⚡️ Quickstart
Install locally (recommended)
Requires Python 3.10–3.13 and uv (recommended package manager).

Install
From a fresh directory, run:

uv pip install langflow -U

The latest Langflow package is installed. For more information, see Install and run the Langflow OSS Python package.

Run
To start Langflow, run:

uv run langflow run
Langflow starts at http://127.0.0.1:7860.

That's it! You're ready to build with Langflow! 🎉

📦 Other install options
Run from source
If you've cloned this repository and want to contribute, run this command from the repository root:

make run_cli
For more information, see DEVELOPMENT.md.

Docker
Start a Langflow container with default settings:

docker run -p 7860:7860 langflowai/langflow:latest
Langflow is available at http://localhost:7860/. For configuration options, see the Docker deployment guide.

Caution

Users must update to Langflow >= 1.7.1 to protect against CVE-2025-68477 and CVE-2025-68478.
Langflow version 1.7.0 has a critical bug where persisted state (flows, projects, and global variables) cannot be found when upgrading. Version 1.7.0 was yanked and replaced with version 1.7.1, which includes a fix for this bug. DO NOT upgrade to version 1.7.0. Instead, upgrade directly to version 1.7.1.
Langflow versions 1.6.0 through 1.6.3 have a critical bug where .env files are not read, potentially causing security vulnerabilities. DO NOT upgrade to these versions if you use .env files for configuration. Instead, upgrade to 1.6.4, which includes a fix for this bug.
Windows users of Langflow Desktop should not use the in-app update feature to upgrade to Langflow version 1.6.0. For upgrade instructions, see Windows Desktop update issue.
Users must update to Langflow >= 1.3 to protect against CVE-2025-3248
Users must update to Langflow >= 1.5.1 to protect against CVE-2025-57760
For security information, see our Security Policy and Security Advisories.

🚀 Deployment
Langflow is completely open source and you can deploy it to all major deployment clouds. To learn how to deploy Langflow, see our Langflow deployment guides.
