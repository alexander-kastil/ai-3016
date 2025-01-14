# Class Environment Setup

- Install Software
- [Install Windows Subsystem Linux - Optional](./wsl/)
- [Setup local container support - Optional](./docker/)

## Install Software

To install Software run the script `setup-ai-3016-winget.ps1` from an elevated PowerShell prompt:

## Setup Git & Clone Class Repository

Login to GitHub using [GitHub CLI](https://cli.github.com/manual/):

```bash
gh auth login
```

Fork the class repository:

```bash
gh repo fork https://github.com/alexander-kastil/ai-3016/
```

Download the forked repository:

```bash 
gh repo clone https://github.com/<USERNAME>/ai-3016/
```

Set User and E-Mail:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@yourdomain.com
```

Congratulations you have completed the base setup of your class software requirements.