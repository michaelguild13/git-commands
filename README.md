# git-commands
custom git commands

# Installation
Clone the repo into your home user directory.
EX: /Users/myuser/
```
git clone git@github.com:michaelguild13/git-commands.git
```

Add the $PATH to your shell profile. (.bash_profile, .zshrc)
```
# Custom Git Commands
export PATH="$PATH:/Users/myuser/git-commands"
```

Next we need to source the profile or close and repoen your shell.
*.zshrc*
```
source .zshrc
```
*.bash_profile*
```
source .bash_profile
```

# Custom Commands
- `git syncremote` - deletes all branches that are no longer living in remote
