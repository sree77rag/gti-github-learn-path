<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,4,6,8&height=120&section=header&text=GTI%20|%20Git%20&%20GitHub%20Learn%20Path&fontSize=35&fontColor=ffffff&fontAlignY=38&animation=fadeIn" width="100%" alt="Dynamic animated header banner"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&pause=1000&color=34A853&center=true&vCenter=true&repeat=true&width=750&lines=Mastering+Version+Control+From+Scratch;Architecting+Clean+Git+Workflows;Building+Professional+Developer+Habits;Code.+Commit.+Push.+Repeat." alt="Typing animation introduction"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-ACTIVE%20LEARNING-4285F4?style=for-the-badge&logo=git&logoColor=white" alt="Learning status"/>
  <img src="https://img.shields.io/badge/ENVIRONMENT-UBUNTU%20LNX-EA4335?style=for-the-badge&logo=ubuntu&logoColor=white" alt="Ubuntu Linux"/>
  <img src="https://img.shields.io/badge/CORE-VERSION%20CONTROL-FBBC05?style=for-the-badge&logo=github&logoColor=black" alt="Version control focus"/>
  <img src="https://img.shields.io/badge/BUILD-SUCCESS-34A853?style=for-the-badge&logo=githubactions&logoColor=white" alt="Build success"/>
</p>

---

## 🎯 01 — The Mission & Vision

Welcome to **GTI (Git & GitHub Learn Path)** — an elite, hands-on engineering repository designed to master the inner workings of Git, remote collaboration protocols, and professional repository architectures.

> 💡 **Core Philosophy:** True version control mastery isn't about memorizing terminal commands; it's about deeply understanding the underlying **state machine** (Working Directory ➔ Staging Area ➔ Local Repository ➔ Remote Origin).

---

## 🛠️ 02 — The Technology Ecosystem

<p align="center">
  <img src="https://skillicons.dev/icons?i=git,github,ubuntu,bash,py,vscode&theme=light" alt="Git, GitHub, Ubuntu, Bash, Python and VS Code"/>
</p>

| Technology | Architectural Role |
| :--- | :--- |
| **Git** | Distributed snapshot-based version control engine |
| **GitHub** | Cloud-based hosting, code review, & CI/CD platform |
| **Ubuntu Linux** | Primary Unix-based kernel development environment |
| **Bash** | Scripting automation & terminal navigation |
| **Python** | Sandbox logic used for testing file state tracking |
| **VS Code** | Advanced source code editor & integrated Git extension hub |

---

## 🗺️ 03 — The Mastery Roadmap

```mermaid
flowchart TD
    A([Git Fundamentals]) --> B([Local Repositories])
    B --> C([Add & Commit Changes])
    C --> D([Connect to GitHub])
    D --> E([Push & Pull])
    E --> F([Branching & Merging])
    F --> G([Collaboration & PRs])
    G --> H([Open-Source Workflow])

    classDef blue fill:#4285F4,stroke:#4285F4,color:#fff;
    classDef red fill:#EA4335,stroke:#EA4335,color:#fff;
    classDef yellow fill:#FBBC05,stroke:#FBBC05,color:#202124;
    classDef green fill:#34A853,stroke:#34A853,color:#fff;

    class A,E blue;
    class B,F red;
    class C,G yellow;
    class D,H green;



# --- Lifecycle Management ---
git init                          # Initialize a new local repository
git clone <url>                   # Clone a remote repository locally

# --- Inspection & Status ---
git status                        # Inspect working tree changes
git diff                          # View unstaged file diff lines
git log --oneline --graph         # Visualize commit tree history compactly

# --- Staging & Committing ---
git add <file-name>               # Stage target file modifications
git commit -m "feat: message"     # Record snapshot with a structured message

# --- Remote Synchronization ---
git remote add origin <url>       # Link local repository to remote hub
git push -u origin main           # Push commits and track upstream branch
git pull origin main              # Fetch and integrate remote changes

# --- Branching & Merging ---
git switch -c <branch-name>       # Create and switch to new branch
git merge <branch-name>           # Merge target branch into current HEAD


flowchart LR
    A[Learn Concept] --> B[Understand Command] --> C[Execute in Terminal] --> D[Verify Output State] --> E[Build Habit]
    E -.-> A

    style A fill:#4285F4,stroke:#4285F4,color:#fff
    style B fill:#EA4335,stroke:#EA4335,color:#fff
    style C fill:#FBBC05,stroke:#FBBC05,color:#202124
    style D fill:#34A853,stroke:#34A853,color:#fff
    style E fill:#4285F4,stroke:#4285F4,color:#fff
