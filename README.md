<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1A73E8,50:34A853,100:FBBC05&height=230&section=header&text=GIT%20%26%20GITHUB&fontSize=58&fontColor=FFFFFF&fontAlignY=36&animation=fadeIn&desc=From%20Zero%20to%20Developer%20Workflow&descSize=18&descAlignY=58" width="100%" alt="Git and GitHub learning path banner"/>

<img src="https://readme-typing-svg.demolab.com?font=Roboto&weight=500&size=22&duration=3000&pause=1000&color=1A73E8&center=true&vCenter=true&repeat=true&width=700&height=45&lines=Learning+Git+from+the+Ground+Up;Mastering+GitHub+One+Commit+at+a+Time;Building+Real+Developer+Habits;Learn.+Practice.+Commit.+Push." alt="Typing animation: Learning Git from the ground up"/>

<br/>

<img src="https://img.shields.io/badge/STATUS-LEARNING%20IN%20PROGRESS-1A73E8?style=for-the-badge&logo=git&logoColor=white&labelColor=202124" alt="Status: learning in progress"/>
<img src="https://img.shields.io/badge/PLATFORM-Ubuntu%20Linux-EA4335?style=for-the-badge&logo=ubuntu&logoColor=white&labelColor=202124" alt="Platform: Ubuntu Linux"/>
<img src="https://img.shields.io/badge/FOCUS-Git%20%26%20GitHub-34A853?style=for-the-badge&logo=github&logoColor=white&labelColor=202124" alt="Focus: Git and GitHub"/>

<br/><br/>

<a href="#the-mission"><img src="https://img.shields.io/badge/Mission-1A73E8?style=flat-square" alt="Go to Mission"/></a>
<a href="#the-stack"><img src="https://img.shields.io/badge/Stack-EA4335?style=flat-square" alt="Go to Stack"/></a>
<a href="#the-roadmap"><img src="https://img.shields.io/badge/Roadmap-FBBC05?style=flat-square&labelColor=202124" alt="Go to Roadmap"/></a>
<a href="#progress"><img src="https://img.shields.io/badge/Progress-34A853?style=flat-square" alt="Go to Progress"/></a>
<a href="#command-playbook"><img src="https://img.shields.io/badge/Commands-1A73E8?style=flat-square" alt="Go to Commands"/></a>
<a href="#the-method"><img src="https://img.shields.io/badge/Method-EA4335?style=flat-square" alt="Go to Method"/></a>

</div>

<br/>

## The Mission

Welcome to **GTI | Git & GitHub Learn Path**, my hands-on journey to mastering Git, GitHub and modern version-control workflows.

This repository documents my progress as I learn the tools developers use to manage code, track changes, collaborate with teams and contribute to open-source projects.

> [!IMPORTANT]
> **The goal:** understand the workflow, practise every command and build confidence through consistent hands-on learning.

<table align="center">
  <tr>
    <td align="center" width="25%"><b>01</b><br/>Learn the concept</td>
    <td align="center" width="25%"><b>02</b><br/>Run the command</td>
    <td align="center" width="25%"><b>03</b><br/>Verify the result</td>
    <td align="center" width="25%"><b>04</b><br/>Build the habit</td>
  </tr>
</table>

## The Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=git,github,ubuntu,bash,py,vscode&theme=light" alt="Git, GitHub, Ubuntu, Bash, Python and VS Code icons"/>

</div>

<br/>

| Tool | Role in this journey |
|:--|:--|
| **Git** | Track changes and maintain project history |
| **GitHub** | Host repositories and collaborate online |
| **Ubuntu Linux** | Primary learning environment |
| **Bash** | Run commands and navigate the terminal |
| **Python** | Practise version control with real code files |
| **VS Code** | Edit and manage code |

## The Roadmap

```mermaid
flowchart TD
    A(["Git Fundamentals"]) --> B(["Local Repositories"])
    B --> C(["Add and Commit Changes"])
    C --> D(["Connect to GitHub"])
    D --> E(["Push and Pull"])
    E --> F(["Branching and Merging"])
    F --> G(["Collaboration and Pull Requests"])
    G --> H(["Open-Source Workflow"])

    classDef blue fill:#1A73E8,stroke:#1A73E8,color:#FFFFFF;
    classDef red fill:#EA4335,stroke:#EA4335,color:#FFFFFF;
    classDef yellow fill:#FBBC05,stroke:#FBBC05,color:#202124;
    classDef green fill:#34A853,stroke:#34A853,color:#FFFFFF;

    class A,E blue;
    class B,F red;
    class C,G yellow;
    class D,H green;
```

## Progress

<div align="center">

<img src="https://img.shields.io/badge/COMPLETED-9%20of%2015-34A853?style=for-the-badge&labelColor=202124" alt="Completed 9 of 15 steps"/>
<img src="https://img.shields.io/badge/PROGRESS-60%25-1A73E8?style=for-the-badge&labelColor=202124" alt="Progress 60 percent"/>

</div>

<br/>

**Foundations (done)**

- [x] Check Git installation on Ubuntu
- [x] Configure Git username and email
- [x] Initialize a local repository
- [x] Create a Python file
- [x] Stage changes using `git add`
- [x] Create the first commit
- [x] Configure a GitHub remote
- [x] Authenticate using GitHub CLI
- [x] Push the first commit to GitHub

**Up next**

- [ ] Understand `git status` and `git diff` in depth
- [ ] Practise editing, staging, committing and pushing
- [ ] Learn branches and merging
- [ ] Learn pull requests and collaboration
- [ ] Practise resolving merge conflicts
- [ ] Explore open-source contribution workflows

## Command Playbook

> [!TIP]
> Open each section below to see the commands. Read what a command does before you run it.

<details>
<summary><b>Setup (one time)</b></summary>

<br/>

```bash
# Tell Git who you are
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

# Make new repositories start on main (matches GitHub)
git config --global init.defaultBranch main

# Verify your configuration
git config --list
```

</details>

<details open>
<summary><b>The daily loop</b></summary>

<br/>

```bash
# Initialize a repository
git init

# Check what changed
git status

# See the exact line-by-line changes
git diff

# Stage a file
git add hello.py

# Commit staged changes
git commit -m "Describe your changes"

# View recent history
git log --oneline
```

</details>

<details>
<summary><b>Connect to GitHub</b></summary>

<br/>

```bash
# Make sure your local branch is called main
git branch -M main

# Link your local repository to GitHub
git remote add origin <repository-url>

# Verify the remote
git remote -v

# Push and set the upstream branch
git push -u origin main

# Get the latest changes from GitHub
git pull origin main

# Copy an existing repository
git clone <repository-url>
```

</details>

<details>
<summary><b>Branching</b></summary>

<br/>

```bash
# Create and switch to a new branch
git switch -c feature-name

# List all branches
git branch

# Switch back to main
git switch main

# Merge a branch into the current one
git merge feature-name
```

</details>

## The Method

```mermaid
flowchart LR
    A["Learn the concept"] --> B["Understand the command"]
    B --> C["Practise in the terminal"]
    C --> D["Verify the result"]
    D --> E["Repeat until it is a habit"]
    E -.-> A

    classDef blue fill:#1A73E8,stroke:#1A73E8,color:#FFFFFF;
    classDef red fill:#EA4335,stroke:#EA4335,color:#FFFFFF;
    classDef yellow fill:#FBBC05,stroke:#FBBC05,color:#202124;
    classDef green fill:#34A853,stroke:#34A853,color:#FFFFFF;

    class A,E blue;
    class B red;
    class C yellow;
    class D green;
```

I believe in understanding what a command does rather than blindly copying it. Every exercise should strengthen my practical knowledge and prepare me for real software development workflows.

<br/>

<div align="center">

<a href="https://github.com/sree77rag">
  <img src="https://img.shields.io/badge/FOLLOW%20THE%20JOURNEY-sree77rag-1A73E8?style=for-the-badge&logo=github&logoColor=white&labelColor=202124" alt="Follow the journey on GitHub: sree77rag"/>
</a>

<br/><br/>

**One repository. One learning journey. One commit at a time.**

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FBBC05,50:34A853,100:1A73E8&height=110&section=footer" width="100%" alt="Decorative footer wave"/>
