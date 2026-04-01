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

We are using a simple Agile workflow adapted for beginner Python developers.

### Team Members and Responsibilities
- Toby Yan → User Creation (Factory Pattern)
- Ahmiere Davis → Document Notifications (Observer Pattern)
- Nelson Gomez → Action Logging (Decorator)
- Cooper Zuideveld → Log Reading (Generator)
- Task 5: Metadata Fetching (Async/Await) → We will solve this together as a team

### How We Work
- Each member works on their assigned feature in a separate branch
- We focus on simple, readable, and working code first
- Once a feature is complete, it should be tested locally before being merged
- We will collaborate as a group on the async task so everyone can understand it

### Development Steps
1. Understand the requirement
2. Write simple pseudocode
3. Build a basic working version
4. Test locally
5. Commit and push to your branch
6. Merge only when the feature is ready

### Git Workflow
Each member should work in their own branch.
 
Branch names:
- `feature/user-factory`
- `feature/observer-notifications`
- `feature/action-logging`
- `feature/log-reader`
- `feature/logs-and-async`

### Communication
- We will use Microsoft Teams as our main communication channel
- If something is unclear, ask early
- Since we are all learning, questions are welcome
- We will support each other and solve problems together

### Team Rules
- Keep the code simple
- Do not overcomplicate the solution
- Ask for help early if blocked
- Respect everyone’s learning process
- Focus on getting a working version first

### Integration Plan
At the end, we will connect all components into one full workflow:
1. Create user
2. Upload document
3. Trigger notifications
4. Log the action
5. Read logs line by line
6. Fetch metadata from an external API concurrently