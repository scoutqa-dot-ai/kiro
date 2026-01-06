# ScoutQA Testing Power for Kiro

AI-powered exploratory testing for web applications using ScoutQA CLI with automated bug detection and accessibility audits.

## Overview

This is a [Kiro power](https://kiro.dev/docs/powers/create/) that integrates ScoutQA's AI-powered testing capabilities directly into your Kiro IDE workflow. When you mention testing-related keywords or implement web features, your AI coding agent automatically gains access to ScoutQA's testing tools and workflows.

## What Does This Power Do?

- **Autonomous Testing**: AI agent can test web applications through natural language instructions
- **Proactive Verification**: Automatically tests features after you implement them
- **Comprehensive Coverage**: Functional testing, accessibility audits, and exploratory testing
- **Parallel Execution**: Run multiple test scenarios simultaneously
- **Real-time Results**: View live test progress and detailed findings

## Installation

### Install the Power

1. Open Kiro IDE → Powers panel (ghost with lightning bolt icon)
2. Click **Add Custom Power**
3. Click **Import power from GitHub**
4. Enter: `https://github.com/scoutqa-dot-ai/kiro`
5. Click `Enter`

### Install ScoutQA CLI

```bash
npm install -g @scoutqa/cli@latest
scoutqa auth login
```

## Usage

Once installed, just ask your AI agent:

- "Test the login flow on my app"
- "Check accessibility of the homepage"
- "Run exploratory tests on this checkout process"

The agent will handle the rest using the workflows defined in [POWER.md](./POWER.md).

## Example Usage

**You:** "I just implemented user registration. Can you test it?"

**Agent:** Automatically runs comprehensive tests including form validation, error handling, edge cases, and accessibility, then reports detailed findings.

## Documentation

- **[POWER.md](./POWER.md)** - Complete power documentation with workflows, best practices, and troubleshooting
- [Kiro Powers Guide](https://kiro.dev/docs/powers/create/) - How to create and use powers
- [Kiro Powers Examples](https://github.com/kirodotdev/powers) - Official power examples
- [ScoutQA Website](https://scoutqa.ai) - ScoutQA platform and documentation
