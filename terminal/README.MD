# 🖥️ Terminal Configuration

My personal Zsh aliases and terminal shortcuts for macOS.

⸻

## ⚙️ Setup

1. Open Configuration

code ~/.zshrc

2. Add Aliases

alias c='clear'
alias ll='ls -la'
alias gs='git status'

3. Apply Changes

source ~/.zshrc

⸻

## 📌 Useful Commands

Command	Description
alias	List active aliases
grep "alias" ~/.zshrc	Find saved aliases
unalias name	Temporarily remove an alias
echo $SHELL	Check current shell