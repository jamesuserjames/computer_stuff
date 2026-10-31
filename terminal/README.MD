Bash & Zsh Aliases — Quick Guide

Aliases are shortcuts for terminal commands.

1. Find Your Alias File

Zsh (default on macOS):

~/.zshrc

Bash:

~/.bashrc

Check your current shell:

echo $SHELL

2. Open Your Alias File

Open in VS Code:

code ~/.zshrc

Or edit directly in the terminal:

nano ~/.zshrc

3. Create Aliases

Add aliases to your configuration file:

alias c='clear'
alias ll='ls -la'
alias gs='git status'
alias cc='cc -Wall -Wextra -Werror'

4. Save & Apply Changes

Reload your configuration:

source ~/.zshrc

5. View Existing Aliases

List all active aliases:

alias

Search for aliases in your configuration:

grep "alias" ~/.zshrc

6. Remove an Alias

Delete its line from ~/.zshrc, then reload:

source ~/.zshrc

To remove an alias temporarily:

unalias gs

Note: Changes saved in ~/.zshrc persist across terminal sessions. Temporary aliases disappear when the shell session ends.