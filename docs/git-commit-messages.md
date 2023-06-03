# Git Commit Message Guide

When crafting Git commit messages, adhering to these best practices will ensure that your commit history remains clear, meaningful, and traceable. Here are some enhanced guidelines with examples:

## 1. Imperative Mood 
**Tag: [IMPL]**
Write commit messages as directives, not descriptions. Think of the title as the finish to the sentence "If applied, this commit will...".
**Example:**
`[IMPL]: Fix bug in data processing script`

## 2. Specificity 
**Tag: [SPEC]**
Your commit messages should precisely encapsulate what was changed. If a commit modifies multiple aspects of a project, it's possibly too broad. Make related but separate commits when feasible.
**Example:**
`[SPEC]: Add error handling to database query function`

## 3. Issue Reference 
**Tag: [ISSUE]**
If your commit addresses an issue, include the issue number in the commit message. This creates traceability for the cause of a change and the issues it resolved.
**Example:**
`[ISSUE #123]: Add user authentication to login route`

## 4. Brevity 
**Tag: [BRV]**
Try to limit the summary line (the first line of the commit message) to under 50 characters if possible. The description, when necessary, should be wrapped around 72 characters.
**Example:**
`[BRV]: Update README.md with project setup instructions`

## 5. Bullet Points for Complex Commits 
**Tag: [CMPX]**
If a commit is intricate and contains multiple related changes, use bullet points in the detailed description to cleanly breakdown the changes.
**Example:**
`[CMPX]: Refactor data preprocessing module
- Replace for-loops with vectorized pandas operations
- Use regex patterns to clean string data
- Update method comments for clarity`

Adhering to these practices when writing Git commit messages essentially turns them into valuable documentation. They deliver context and rationale for changes, which can greatly assist other developers and even your future self.
