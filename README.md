# IntelliJCheatSheet

#### Coding

- `ctrl + v` --> Paste
- `ctrl + shift + v` --> Show clipboard history paste. Use the arrow keys to navigate, then hit enter
- `ctrl + alt + v` --> Extract selection to variable
- `ctrl + alt + p` --> Extract selection to parameter
- `ctrl + alt + f` --> Extract selection to feild
- `ctrl + alt + m` --> Extract selection to method
- `ctrl + alt + l` --> Refactor / reorganize file
- `ctrl + shift + alt + l` --> Show refactor file dialog then refactor. Lets you select 'optimize imports' and 'rearrange code'
- `ctrl + [` --> Jump to beginning of current code block
- `ctrl + ]` --> Jump to end of current code block
- `ctrl + shift + up` and `ctrl + shift + down` --> Shift current line of code up or down with respect to code blocks _(will automatically
  correct indentation, and does not allow moving out of a function)_
- `alt + shift + up` and `alt + shift + down` --> Shift current line up or down ignoring code block behavour

#### Window Navigation

- `alt + 1` --> Open/focus on Project window *(`esc` to unfocus)*
- `alt + 3` --> Open/focus on Find window *(`esc` to unfocus)* 
- `alt + 4` --> Open/focus on Run window *(`esc` to unfocus)* 
- `alt + 5` --> Open/focus on Debug window *(`esc` to unfocus)* 

#### Selection

- hold `alt` and select text --> block selects, and creates multiple cursors on each line
- hold `alt + shift` and click at multiple locations --> creates another cursor at each clicked location

#### Running / Debugging

- `ctrl + F5` --> Re-run current run config (either debugs or runs, depending on window focus)
- `ctrl +  F8` --> Toggle current line's breakpoint
- `ctrl + shift + F8` --> Open the Breakpoints window
- hold `alt` and click --> evaluates code in-line, useful for if statements and streams (and other)
