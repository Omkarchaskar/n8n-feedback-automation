# n8n AI Code Review Automation

AI-powered workflow automation built using n8n, Gmail Trigger, and OpenAI LLMs.

This workflow automatically reads incoming code-related emails, generates code comments and summaries using AI, merges the outputs, and sends the final result back through email.

---

# Features

- Gmail-based workflow trigger
- AI-powered code summarization
- Automatic code comment generation
- Parallel LLM execution
- Merge node integration
- Automated email delivery
- Fully no-code/low-code automation using n8n

---

# Workflow Architecture

```text
Gmail Trigger
      ↓
Read Code Snippet
      ↓
 ┌───────────────┬────────────────┐
 ↓                                ↓
Generate Summary         Generate Comments
 ↓                                ↓
 └───────────────Merge────────────┘
                  ↓
           Send Email