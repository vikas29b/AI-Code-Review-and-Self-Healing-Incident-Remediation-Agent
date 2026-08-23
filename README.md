# AI-Code-Review-and-Self-Healing-Incident-Remediation-Agent
Built an enterprise agentic CI/CD workflow using n8n, LLM reasoning, GitHub Actions, and Slack. It analyzes PR diffs for security bugs, runs test suites, self-heals failing tests using error tracebacks (up to 3 retries), and requires interactive Slack Human-in-the-Loop approval before auto-merging clean code to production.
