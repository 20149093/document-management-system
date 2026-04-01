# document-management-system
This repo will work on a document management system with multiple user types (Admin, Editor, Viewer), notifications when a document is uploaded, logging of all user actions, reading of large log files efficiently and asynchronous retrieval of document metadata from the web.

# Document Management System

A simple Python project demonstrating design patterns:
- Factory
- Observer
- Decorator
- Generator
- Async/Await

## How to run

```bash```

python src/main.py

---------------------------------------------------------------------------------------

## Team Workflow (Agile Approach)

We are using a simple Agile workflow adapted for beginners.

### Roles & Responsibilities
- Toby Yan → User Creation (Factory Pattern)
- Ahmiere Davis → Document Notifications (Observer Pattern)
- Nelson Gomez → Action Logging (Decorator)
- Cooper Zuideveld → Log Reading (Generator) + Metadata Fetching (Async)

### How We Work
- Each member works on their assigned feature in a separate branch
- We focus on writing simple, readable, and working code first
- Once a feature is complete, it is tested and then merged into main

### Development Steps
1. Understand the requirement
2. Write simple pseudocode
3. Implement a basic working version
4. Test locally
5. Commit and push
6. Merge into main

### Git Workflow
- Create a branch: `feature/<your-feature>`
- Example: `feature/user-factory`
- Use clear commit messages:
  - `add user factory`
  - `implement observer notifications`

### Communication
- We use Microsoft Teams for all communication
- Questions should be asked early (no blocking)
- If someone is stuck, they should ask the team

### Team Rules
- Keep code simple (we are learning)
- Ask for help early
- Respect everyone’s progress
- Focus on completing a working solution first

### Integration Plan
At the end, we will connect all components into one flow:
- Create user
- Upload document
- Trigger notifications
- Log actions
- Read logs
- Fetch metadata
