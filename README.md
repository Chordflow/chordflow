<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/chordflow-wordmark-white.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/chordflow-wordmark-full.png">
    <img src="assets/chordflow-wordmark-full.png" alt="ChordFlow" width="400"/>
  </picture>
</div>

# ChordFlow

**Build workflows that work everywhere your AI does**

ChordFlow is a universal workflow platform that connects any tool to any AI assistant. Create workflows once and run them in Cursor, Claude Desktop, ChatGPT, and beyond—with human oversight at every step.

## 🚀 What is ChordFlow?

ChordFlow solves the fundamental problem of AI assistant isolation. Instead of rebuilding the same processes in every AI tool, ChordFlow lets you create intelligent workflows that work universally across all your AI assistants while keeping you in control.

### Core Problems We Solve
- **AI Isolation**: Your AI assistants work in silos, losing context between tasks
- **Repetitive Work**: You rebuild the same multi-step processes over and over
- **Tool Fragmentation**: No way to connect your favorite tools across different AI apps
- **Team Inconsistency**: Teams can't share or standardize their AI workflows

## ⚡ Key Features

### 🌐 Universal AI Integration
Works with **any AI assistant** that supports MCP (Model Context Protocol):
- Cursor IDE
- Claude Desktop
- ChatGPT
- Windsurf
- And many more

### 🔧 Connect Any Tool
Integrate with your entire tech stack:
- **Development**: GitHub, GitLab, Vercel, AWS, Docker, npm
- **Productivity**: Slack, Notion, Google Drive, Airtable, Linear, Jira
- **Custom**: Any API, command line tool, or service with an endpoint

### 👤 Human-in-the-Loop Control
- Set approval gates wherever you need them
- Review outputs and make changes before workflows continue
- Maintain oversight while automating routine tasks
- You stay in control of every decision point

### 🧠 LLMScript Engine
Write workflows that think using our executable AI reasoning language:
- **Human-readable**: Written in natural language that both humans and AI understand
- **Machine-executable**: Converts human reasoning into actionable automation
- **Context-aware**: Access to your documents, team data, and external tools
- **Flexible**: Support for conditions, loops, and complex decision trees

## 🚀 Getting Started

### Quick Setup

1. **Get your API key** from [chordflow.ai](https://chordflow.ai)

2. **Configure your AI assistant**:

   **For Cursor IDE:**
   ```json
   {
     "mcpServers": {
       "chordflow": {
         "url": "https://app.chordflow.ai/api/mcp-sse",
         "headers": {
           "x-api-key": "your-api-key-here",
           "X-MCP-Agent-Type": "coding"
         }
       }
     }
   }
   ```

3. **Start building workflows**:
   ```bash
   # Initialize your project
   @chordflow setup a project for my app

   # Create tasks from requirements
   @chordflow create tasks for user authentication

   # Work on specific features
   @chordflow help me implement login functionality
   ```

### Ready-to-Use Templates
- **Project Kickoff**: Research → planning → task breakdown → team assignment
- **Code Quality Gate**: Analysis → testing → review → approval → merge
- **Content Pipeline**: Research → writing → editing → approval → publishing
- **Data Processing**: Collection → validation → transformation → analysis → reporting

## 📚 Documentation

- [Getting Started Guide](https://www.chordflow.ai/docs)
- [Workflow Tutorial](https://www.chordflow.ai/docs)
- [LLMScript Reference](https://www.chordflow.ai/docs)
- [MCP Integration Guide](https://www.chordflow.ai/docs)
- [API Documentation](https://www.chordflow.ai/docs)

## Issue Reporting

We welcome feedback and issue reports to help improve ChordFlow. Please use this repository to:

* Report bugs and technical issues
* Request new features
* Share feedback on existing functionality
* Discuss improvements and enhancements

## Support

For additional support beyond issue reporting:

* Join our [Discord server](https://discord.gg/a5rSGm8Q) for quick help and discussions with other developers
* For billing questions, use our [Billing Support](https://www.chordflow.ai/billing-support) form
* Follow us on [Twitter/X](https://x.com/chordflowai) for updates and announcements
* Connect with us on [LinkedIn](https://linkedin.com/company/chordflow) for professional updates
* Visit our [documentation](https://www.chordflow.ai/docs) for comprehensive guides and tutorials

## Security

If you discover a potential security issue in this project, please contact our security team through our vulnerability reporting process. Please do **not** create a public GitHub issue for security vulnerabilities.

## Code of Conduct

This project has adopted the ChordFlow Open Source Code of Conduct. For more information see the [Code of Conduct](CODE_OF_CONDUCT.md) or contact support@chordflow.ai with any additional questions or comments.

---

©2025 PersonL LLC. All Rights Reserved.

**Contact Us:** For questions about our legal policies, contact us at legal@chordflow.ai
