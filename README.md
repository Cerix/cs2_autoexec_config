# CS2 Autoexec Config
Personal CS2 Autoexec config

# Simple desubtick config working @june25

Copy desubtick folder in:
```Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg```

add in your autoexec.cfg:
```
// Desubtick BEGIN
alias +jump_ "exec desubtick/workaround_jump_start"
alias -jump_ "exec desubtick/workaround_jump_end"

alias +duck_ "exec desubtick/workaround_duck_start"
alias -duck_ "exec desubtick/workaround_duck_end"

alias +sprint_ "exec desubtick/workaround_sprint_start"
alias -sprint_ "exec desubtick/workaround_sprint_end"

alias +forward_ "exec desubtick/workaround_forward_start"
alias -forward_ "exec desubtick/workaround_forward_end"
alias +left_ "exec desubtick/workaround_left_start"
alias -left_ "exec desubtick/workaround_left_end"
alias +back_ "exec desubtick/workaround_back_start"
alias -back_ "exec desubtick/workaround_back_end"
alias +right_ "exec desubtick/workaround_right_start"
alias -right_ "exec desubtick/workaround_right_end"

bind "w" "+forward_"
bind "a" "+left_"
bind "s" "+back_"
bind "d" "+right_"

bind "SHIFT" "+sprint_"
bind "CTRL" "+duck_"

bind "SPACE" "+jump_"
bind "MWHEELUP" "+jump_"
bind "MWHEELDOWN" "+jump_"

//Desubtick END
```
