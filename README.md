# vim-cheatsheet

Quick Vim keymap reference in your terminal.

```
 ┌─────────────────────────────────┐   ▲        ┌─────────┬─────────┬─────────┐ 
 │[operator]        [count][motion]│   │        │p  paste │P  paste │^w  del  │ 
 ├─────────┬────────┬──────────────┤   gg 1st   │   after │   before│    word │ 
 │d delete │w  word │(, )  ()block │   |  line  ├─────────┼─────────┼─────────┤ 
 ├─────────┤W  WORD │[, ]  []block │   │        │u  undo  │^r redo  │.  repeat│ 
 │y yank   │s  sntnc│{, }  ()block │   ^b up 1  │         │         │         │ 
 ├─────────┼────────┴──────────────┤   |  page  ├─────────┼─────────┼─────────┤ 
 │c change │  (use text-objects)   │   │        │nG jump  │^o jump  │^i jump  │ 
 ├─────────┤  ││   ├iw┘       ││   │   ^u up 0.5│   line N│   back  │   frwrd │ 
 │~ case   │  ││   └────iW────┤│   │   |  page  ├─────────┼─────────┼─────────┤ 
 ├─────────┤  │└──────i(──────┘│   │   │        │== auto  │>> shift │^u del   │ 
 │= indent │  └───────a(───────┘   │   k  up    │   indent│<< shift │   line  │ 
 └─────────┴───────────────────────┘   |  line  └─────────┴─────────┴─────────┘ 
                                       │                                        
◀──0──────^────────────B─────b──────h──┼──l──────e──────w─────E─────W──────$───▶
 strt    1st         prev  prev   prev │ next   end    next  end   next   end   
 line   char         WORD  word   char │ char   word   word  WORD  WORD   line  
                                       │           ┌──────────────────────────┐ 
                                       j  down     │:h  left-right-motions    │ 
                                       |  line     │:h  up-down-motions       │ 
                                       │           │:h  operator              │ 
                                       ^d down 0.5 │:h  navigation            │ 
                                       |  page     │:h  pattern-searches      │ 
                                       │           │:h  jump-motions          │ 
                                       ^d down 1   ├──────────────────────────┤ 
                                       |  page     │:e  open file to edit     │ 
                                       │           │:ls list open files       │ 
                                       G  last     │:bn jump to next file     │ 
                                       |  line     │:bp jump to prev file     │ 
                                       ▼           └──────────────────────────┘
```

## Usage

For an offline version of the cheatsheet, you can:
- Copy `vim-cheatsheet.txt` to `$HOME`
- Create a shell alias to print the file content for quick reference
(this is how I use the cheatsheet right now)

If you like this cheatsheet, consider checking out and purchasing the original
[Advanced Vim Cheatsheet](https://thingsfittogether.com/product/vim-cheat-sheet-advanced-digital-download/)
which was an inspiration for me to create this cheatsheet. The only reason this
exists is because I wanted to have an offline copy of the most important Vim
motions keymaps right on my terminal.

