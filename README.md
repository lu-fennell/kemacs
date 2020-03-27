# kemacs

Emacsclient for KWIN. Running `kemacs <file>` will

- start an emacs server if it is not already running
- raising an emacsclient window if one exists in the current workspace, or open a new one in the current workspace
- open `<file>` in that window

The effect is that you can view files quickly in emacs, with at most one
emacsclient window per workspace. 

## Why not use emacsclient by itself, instead?

I found that `emacsclient` itself does not show the behavior which is described
above. And I want this behavior.

## Installation

Put `kemacs` into `$HOME/.local/bin` and `kemacs.desktop` into
`$HOME/.local/share/applications`. Now you should be able to start a `Kemacs`
application from your launcher as well as configure it as default application
for text file types.
