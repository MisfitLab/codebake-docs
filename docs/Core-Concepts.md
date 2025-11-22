# Core Concepts

Understanding how CodeBake is organized will help you get the most out of it. Don't worry, it's pretty straightforward!

## How We Organize Things

CodeBake uses a simple hierarchy to keep your work tidy:

```
Accounts
  └── Projects
       └── Phases
            └── Tasks
```

### Accounts
Think of an **Account** as your company or organization's headquarters. It holds all your team members and projects. You can belong to multiple accounts (like a personal one and a work one), but they are completely separate.

### Projects
A **Project** is a specific initiative you're working on, like "Mobile App Launch" or "Website Redesign."
- Each project has a unique **Task Prefix** (like `APP` or `WEB`) so you can easily identify tasks (e.g., `APP-101`).
- Projects move through statuses like `Active` or `Completed` so you know what's currently in flight.

### Phases
**Phases** are the milestones or stages of your project. We're framework-agnostic, so you can call them whatever you want—**Sprints**, **Blocks**, **Milestones**, or **Versions**.
- Only one phase is **Active** at a time. This helps your team focus on what matters *now*.
- When you finish a phase, the board clears off the completed tasks and brings in the next set. It's a great feeling!

### Tasks
**Tasks** are the actual units of work.
- They live on your board and move through statuses: `Todo` → `In Progress` → `Review` → `Done`.
- You can assign them to people, add labels, and attach files.
- If a task is too big, you can break it down into **Subtasks** (like `APP-101a`).

## The Workflow

We are a little dogmatic about statuses. After years of trying every complex workflow under the sun, we've found that the simplest solution is usually the best. You really only need 6 statuses:

1. **TODO**: Ready to be picked up.
2. **IN-PROGRESS**: Someone is working on it right now.
3. **REVIEW**: The work is done and needs a second pair of eyes.
4. **BLOCKED**: Stuck? Let your team know you need help.
5. **CANCELLED**: Sometimes plans change, and that's okay.
6. **DONE**: Finished and shipped!

This simplicity keeps everyone aligned without over-engineering the process.

## Features You'll Use Every Day

### Real-Time Collaboration
Everything in CodeBake updates instantly. If your teammate moves a card, you see it move. No refreshing required.

### Activity Summaries
Keep your Project Managers and Clients happy without the constant status meetings. The **Activity Summary** shows exactly what's been happening on a project at any time, giving stakeholders peace of mind and total visibility.

### Meeting Mode
We have specialized views designed specifically for online meetings. They help you go over tasks and prioritize them quickly, so you can spend less time talking about work and more time doing it.

### Markdown Everywhere
We know developers love Markdown. You can use it in task descriptions, comments, and even this wiki!

### AI Integration
This is our secret sauce. CodeBake is designed to be used by both humans and AI agents.
- **MCP Tools**: Your AI assistant can read and write to your project.
- **Status Updates**: Your AI can automatically move tasks for you as you work.

## Roles & Permissions

- **Account Members**: People who are part of your organization.
- **Project Members**: People who have access to a specific project.
- **Guests**: You can add an **unlimited number of guests** to your project. This is perfect for keeping clients up to date—they can view status and add issues, but won't mess up your board.
- **Owners**: The folks who can change settings and manage the team.

## A Few Tips for Success

- **Keep Phases Small**: It feels better to complete phases often than to be stuck in one forever.
- **Use meaningful prefixes**: `API` is better than `PROJ1`.
- **Let AI help**: Don't manually update everything—ask your AI assistant to "move task 123 to review."

---

[← Back to Home](index.md) | [Next: MCP Tools →](MCP-Tools.md)
