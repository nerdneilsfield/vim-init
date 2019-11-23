# 快捷键列表


**Dirvish**
```
MAPPINGS                                                    *dirvish-mappings*

Global ~
    <Plug>(dirvish_up)
    -               Opens the current file directory or the [count]th parent.

Buffer-local (filetype=dirvish) ~
    g?              Shows this help.
    [count]R        Reloads the current directory. (|:edit| works too.)
                    Sets |g:dirvish_mode| to [count], if given.
                    Mnemonic: higher [count] => more files.
    <Plug>(dirvish_quit)
    gq              Quits and returns to the original file.
    <Plug>(dirvish_up)
    -               Opens the [count]th parent directory.
    <Plug>(dirvish_split_up)
                    Opens the [count]th parent in a new window.
    <Plug>(dirvish_vsplit_up)
                    Opens the [count]th parent in a new, vertical window.
    <2-LeftMouse>
    i
    <CR>            Opens file at cursor.
    {Visual}I
    {Visual}<CR>    Opens selected files.
    o               Opens file in a new window.
    {Visual}O       Opens each selected file in a new window.
    a               Opens file in a new, vertical window.
    {Visual}A       Opens each selected file in a new, vertical window.
    K               Shows file info. [count] shows directory size.
    {Visual}K       Shows info for selected files. [count] shows directory size.
    p               Previews file at cursor.
    CTRL-N          Previews the next file.
    CTRL-P          Previews the previous file.
    <Plug>(dirvish_arg)
    x               Adds/removes file to/from the local |arglist|.
    {Visual}x       Adds selected files to the local arglist.
    dax             Starts a new empty local arglist.
    .               Inserts "|:Shdo|  {}" into the command-line.
    [count].        Inserts "|:Shdo|!  {}" into the command-line.
```
