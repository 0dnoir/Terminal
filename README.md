# Terminal Config

## Oh My ZSH
I use oh my zsh for highlighting with a theme. 

Under the .zshrc file insert: ZSH_THEME="eastwood"

## TMUX
To create a default tmux config use: `tmux show -g | sed 's/^/set-option -g /' > ~/.tmux.conf`

Currently my tmux config consists of just the mouse on setting to easily switch between panes. 
This can be set for the current session via the TMUX commands: `CTRL + B` `:` then enter `set -g mouse on`
Or change the `mouse` value in the .tmux.conf in your home dir


Selecting text to copy and paste can be done with the `fn`/`option` key on mac or shift on linux.
To stop the selection from  highlighting another pane use the toggle option zoom: `CTRL + B` `z`. Use the same combination to toggle back once done.
