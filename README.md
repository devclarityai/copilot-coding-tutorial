# AI Coding Tutorial

This is a website to help you learn how to use AI coding assistants.

## Walkthrough

1. Context & Reusable Prompts
2. Mode Explanation - Planning vs. Implementing 
3. Understanding - Codebase
4. Understanding - Tagging
5. Writing - Inline Code
6. Writing - Simple Ask
  - The "Learn More About Our Features" button on the index.html page doesn't animate in with the rest of the features section, so it looks weird.
7. Writing - Workflow
  - We need to create a contact page and then also update the links on the index.html and features.html pages to point to this. For now, we can use the same styling we have on other pages and we can build a basic contact form that you would usually see on a website. Create the tasks for this, don't implement it yet. @task-creator.mdc
  - markdown-file.md Great, now @implement-it.mdc

## Running Locally

**Option 1: Direct Browser Access**
Open `web-app/index.html` in your browser.

**Option 2: Local Server** (recommended)
```bash
cd web-app && python3 -m http.server 8000
```
Navigate to `http://localhost:8000`.

Run in background:
```bash
cd web-app && nohup python3 -m http.server 8000 > /dev/null 2>&1 & disown
```
