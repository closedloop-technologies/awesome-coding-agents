# Awesome Coding Agents and Tools

A curated list of notable AI coding agents available for the command line or IDEs. Each entry notes whether the tool provides a CLI, supports remote/headless use, its primary specialization, and whether it is merely a wrapper around other tools.

## Terminal Jarvis
- **CLI:** `terminal-jarvis`
- **Remote Use:** Mainly local, can run remotely if installed
- **Specialization:** Unified TUI for managing multiple coding agents
- **Wrapper:** Yes – installs and launches other CLIs

## Claude Code
- **CLI:** `claude`
- **Remote Use:** Connects to Anthropic's cloud API; usable locally or in CI
- **Specialization:** AI pair programmer for planning, writing, debugging, and running shell commands
- **Wrapper:** No

## Gemini CLI
- **CLI:** `gemini`
- **Remote Use:** Connects to Google's Gemini models; works locally or in Cloud Shell
- **Specialization:** Autonomous agent for coding tasks and general research with large context window
- **Wrapper:** No

## Qwen Code
- **CLI:** `qwen`
- **Remote Use:** Connects to Qwen-Coder models via various providers; runs locally
- **Specialization:** Qwen-optimized agent for refactoring and automating code tasks in large codebases
- **Wrapper:** Essentially a fork of Gemini CLI

## OpenCode (Archived)
- **CLI:** `opencode`
- **Remote Use:** Local TUI connecting to multiple model APIs; possible in headless environments
- **Specialization:** Multi-provider assistant with session management and LSP integration
- **Wrapper:** No – independent tool (now succeeded by Crush)

## LLXPRT Code
- **CLI:** `llxprt-code`
- **Remote Use:** Supports OpenAI, Anthropic, Gemini, OpenRouter, and local models
- **Specialization:** Flexibility to switch providers and models mid-session, themable interface
- **Wrapper:** Fork of Gemini CLI with added multi-provider features

## OpenAI Codex CLI
- **CLI:** `codex`
- **Remote Use:** Runs locally or on servers; supports ChatGPT login, API keys, or local endpoints
- **Specialization:** Executes code, edits files, and automates dev tasks with different autonomy modes
- **Wrapper:** No – official OpenAI tool

## Crush
- **CLI:** `crush`
- **Remote Use:** Works across OS terminals, including headless servers, using various model APIs
- **Specialization:** TUI with multi-model, multi-session support, LSP context, and MCP plugin system
- **Wrapper:** No – full application evolved from OpenCode

## Qodo Command
- **CLI:** `qodo`
- **Remote Use:** Local CLI interfacing with Qodo's backend; can run in CI for automated workflows
- **Specialization:** Framework for building specialized AI agents (code review, tests, docs, etc.)
- **Wrapper:** No

## Aider
- **CLI:** `aider`
- **Remote Use:** Runs locally with API keys; usable over SSH
- **Specialization:** Open-source pair programmer for editing code within git repositories
- **Wrapper:** No

## GitHub Copilot
- **CLI/IDE:** IDE extensions for VS Code, JetBrains, and more
- **Remote Use:** Requires supported editor; works with cloud-based dev environments
- **Specialization:** AI code completion and inline suggestions
- **Wrapper:** No – GitHub service backed by OpenAI models

## Cursor
- **CLI/IDE:** Standalone AI-enhanced IDE (VS Code fork)
- **Remote Use:** Desktop app; can connect to remote workspaces via built-in features
- **Specialization:** AI-first editor with code generation, refactoring, and project-wide chat
- **Wrapper:** No – full application built atop VS Code

## See Also
- [sourcegraph/awesome-code-ai](https://github.com/sourcegraph/awesome-code-ai) — community list of AI coding tools
- [hesreallyhim/awesome-claude-code-agents](https://github.com/hesreallyhim/awesome-claude-code-agents) — Claude Code sub-agent collection
- [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) — directory of LLM-powered apps and agents

*Sources:* Official documentation, project pages, and credible summaries.

