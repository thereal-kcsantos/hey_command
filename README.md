# hey_command
Some random tasks.... Maybe application/practice stuff? :wink::wink:

# Purpose
I'm trying some things out here. I want to use this repo to track my changes (and maybe my thought process) as I try to accomplish "the thing".

# Task (aka "The Thing)

An employee runs the command “hey” in their terminal, and we want it to respond with “what’s up." Please write a shell-script that we can deploy through MDM (which runs as root) to implement this.


# Thought Process

## Attempt 1:
Configure the `~/.zshrc`, `~/.bashrc`, and/or `~/.bash_profile` aliases to output the "What's Up" response.
### Result
Not so great, can't escape the apostrophe in What's up. Getting response of "'whats up\"

## Attempt 1.1
While still using the zsh/bash profile aliases, try to have the "hey" command run a script that creates another script so I can use something like "alias=hey "/bin/bash hey_response.sh""


