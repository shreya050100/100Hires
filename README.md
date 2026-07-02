# 100Hires - Development Environment Setup

## Overview

This repository documents the setup process completed for the 100Hires technical assignment.

## Tools Installed

- Cursor IDE
- Git for Windows
- Claude Code extension for Cursor
- Codex extension for Cursor
- GitHub

## Steps Completed

1. Installed Cursor IDE.
2. Installed the Claude Code extension and logged in.
3. Installed the Codex extension and logged in.
4. Verified that Claude Code responds to prompts.
5. Verified that Codex was successfully installed. It prompted to open a project before use.
6. Created a public GitHub repository.
7. Installed Git for Windows.
8. Cloned the repository locally.
9. Opened the repository in Cursor.
10. Updated the README file.
11. Committed and pushed the changes to GitHub.

## Issues Encountered

### 1. Codex required an open project

**Issue:**
Codex displayed "Unable to send message – Add a project to use Codex."

**Resolution:**
Opened the GitHub repository in Cursor. Codex requires an open project before it can process prompts.


### 2. Git was not recognized

**Issue:**
When trying to clone the repository, I received the following error:

```
git : The term 'git' is not recognized as the name of a cmdlet...
```

**Resolution:**
- Installed Git for Windows.
- Restarted Cursor.
- Verified the installation using the following command in the terminal: 

```bash
git --version
```

After installation, Git commands worked successfully.

### 3. Git commands were unavailable in Cursor

**Issue:**
The **Git: Clone** command did not appear in Cursor.

**Resolution:**
This was caused by Git not being installed. Once Git was installed and Cursor was restarted, Git functionality became available.

## Repository

This repository contains the completed setup for the 100Hires assignment.