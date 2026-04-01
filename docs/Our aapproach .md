# Activity 2 – Mini Notification System

## Team Members
- Toby Yan
- Ahmiere Davis
- Nelson Gomez
- Cooper Zuideveld

## Overview
We are building a document management system using design patterns in Python.

## Features & Design Patterns

### 1. User Creation
- Pattern: Factory Pattern
- Reason: Allows flexible creation of different user types (Admin, Editor, Viewer)

### 2. Document Notifications
- Pattern: Observer Pattern
- Reason: Multiple subscribers react to a document upload

### 3. Action Logging
- Pattern: Decorator
- Reason: Adds logging without modifying original functions

### 4. Log Reading
- Technique: Generator
- Reason: Efficient memory usage when reading large files

### 5. Metadata Fetching
- Technique: Async/Await
- Reason: Allows concurrent API calls

## Workflow
We used a simple Agile approach:
- Planning
- Development
- Integration

## Final Flow
1. Create user
2. Upload document
3. Notify subscribers
4. Log actions
5. Read logs
6. Fetch metadata