# ~/.p10k.zsh colors

```zsh
  # Current directory background color.
  typeset -g POWERLEVEL9K_DIR_BACKGROUND=210
  # Default current directory foreground color.
  typeset -g POWERLEVEL9K_DIR_FOREGROUND=0
  # Color of the shortened directory segments.
  typeset -g POWERLEVEL9K_DIR_SHORTENED_FOREGROUND=0
  # Color of the anchor directory segments. Anchor segments are never shortened. The first
  # segment is always an anchor.
  typeset -g POWERLEVEL9K_DIR_ANCHOR_FOREGROUND=0

  # Version control background colors.
  typeset -g POWERLEVEL9K_VCS_CLEAN_BACKGROUND=46
  typeset -g POWERLEVEL9K_VCS_MODIFIED_BACKGROUND=214
  typeset -g POWERLEVEL9K_VCS_UNTRACKED_BACKGROUND=46
  typeset -g POWERLEVEL9K_VCS_CONFLICTED_BACKGROUND=141
  typeset -g POWERLEVEL9K_VCS_LOADING_BACKGROUND=192

  # Styling for different parts of Git status.
  local meta='%8F' # gray foreground

  typeset -g POWERLEVEL9K_STATUS_OK_FOREGROUND=0
  typeset -g POWERLEVEL9K_STATUS_OK_BACKGROUND=210
  typeset -g POWERLEVEL9K_STATUS_OK_PIPE_FOREGROUND=0
  typeset -g POWERLEVEL9K_STATUS_OK_PIPE_BACKGROUND=210
```
