<div align="center">
  <a href="https://github.com/juanMarinero/vim-plugins-screenshots/pulls"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome"></a>
  <a href="https://github.com/juanMarinero/vim-plugins-screenshots?tab=readme-ov-file#license"><img src="https://img.shields.io/github/license/juanMarinero/vim-plugins-screenshots" alt="License"></a>
  <img src="https://img.shields.io/badge/-Vim-019733?logo=vim&logoColor=white" alt="Vim">
  <img src="https://img.shields.io/badge/-Neovim-57A143?logo=neovim&logoColor=white" alt="NeoVim">
</div>
<br/>

<img align="right" src="media/repo_meme.gif" alt="Repository meme" width="450" height="450" style="padding-left: 40px;">

> A picture is worth a thousand words

**🖼️ == 1000 x 📝**

Neo-/Vim has so many **plugins**! **Visually** check their **main features** here.

This is not a detailed list of all Neo/Vim plugins; for that, visit
- [vim.org](https://www.vim.org/scripts/script_search_results.php?keywords=&script_type=&order_by=downloads&direction=descending&search=search) sorted by downloads/rating
- [vimawesome.com](https://vimawesome.com/) sorted by rating
- [awesome-vim](https://github.com/akrawchyk/awesome-vim) grouped by section and alphabetically sorted
- [awesome-neovim](https://github.com/rockerBOO/awesome-neovim) for NeoVim
- [neovimcraft](https://neovimcraft.com/)
- [vim-plugin-list](https://github.com/altermo/vim-plugin-list) last maintained in 2024
- [dotfyle](https://dotfyle.com/)

<details>
  <summary><strong>Index</strong> - Click to expand</summary>

* [ALE](#ale)
* [prettier](#prettier)
* [coc.nvim](#cocnvim)
* [copilot.vim](#copilotvim)
* [codeium.vim](#codeiumvim)
* [vim-ai](#vim-ai)
* [cheat.sh-vim](#cheatsh-vim)
* [Ctags: tagbar](#ctags-tagbar)
* [Ctags: vista.vim](#ctags-vistavim)
* [emmet-vim](#emmet-vim)
* [jupyter-vim](#jupyter-vim)
* [jupytext (not a vim plugin)](#jupytext-not-a-vim-plugin)
* [jupyter_ascending](#jupyter_ascending)
* [vim-markdown](#vim-markdown)
* [markdown-preview](#markdown-preview)
* [vim-terminator](#vim-terminator)
* [codi.vim](#codivim)
* [vim-test](#vim-test)
* [vimspector debugger](#vimspector-debugger)
* [Snippets](#snippets)
  * [UltiSnips](#ultisnips)
  * [Coc-snippets](#coc-snippets)
  * [lexima.vim](#leximavim)
* [VimTex](#vimtex)
* [vim-latex-live-preview](#vim-latex-live-preview)
* [bracey.vim](#braceyvim)
* [git-signs](#git-signs)
  * [gitsigns.nvim](#gitsignsnvim)
  * [vim-gitgutter](#vim-gitgutter)
* [vim-fugitive](#vim-fugitive)
* [diffchar](#diffchar)
* [Git branch viewer](#git-branch-viewer)
  * [gv.vim](#gvvim)
  * [vim-flog](#vim-flog)
  * [gitgraph.nvim](#gitgraphnvim)
* [undotree](#undotree)
* [Visual Experience Enhancements](#visual-experience-enhancements)
  * [illuminate](#illuminate)
  * [vim-search-pulse](#vim-search-pulse)
  * [highlightedyank](#highlightedyank)
  * [GUI with vim-quickui](#gui-with-vim-quickui)
  * [rainbow](#rainbow)
* [Preview colors](#preview-colors)
  * [clrzr](#clrzr)
  * [nvim-colorizer.lua](#nvim-colorizerlua)
  * [colorizer](#colorizer)
* [vcoolor.vim](#vcoolorvim)
* [vim-surround](#vim-surround)
* [Indent Guides](#indent-guides)
   * [vim-indent-guides](#vim-indent-guides)
   * [indentline](#indentline)
   * [vim-indent-object](#vim-indent-object)
* [vim-matchup](#vim-matchup)
* [vim-visual-multi](#vim-visual-multi)
* [vim-signature](#vim-signature)
* [vim-bookmarks](#vim-bookmarks)
* [vim-codepainter](#vim-codepainter)
* [vim-mark](#vim-mark)
* [vim-simple-todo](#vim-simple-todo)
* [switch.vim](#switchvim)
* [File managers](#file-managers)
  * [NNN](#nnn)
  * [telescope-file-browser.nvim](#telescope-file-browsernvim)
  * [NERDTree](#nerdtree)
  * [Neo-tree.nvim](#neotreenvim)
  * [oil.nvim](#oilnvim)
  * [neovim-project](#neovim-project)
* [FZF](#fzf)
  * [fzf.vim](#fzfvim)
  * [fzf-preview.vim](#fzf-previewvim)
  * [fzf-lua](#fzf-lua)
  * [Telescope](#telescope)
  * [MRU](#mru)
  * [Ferret](#ferret)
  * [denite.nvim](#denitenvim)
* [vim-easymotion](#vim-easymotion)
* [CSV](#csv)
  * [csv.vim](#csvvim)
  * [Rainbow CSV](#rainbow-csv)
* [erd](#erd)
* [Recover.vim](#Recovervim)
* [NERDCommenter](#nerdcommenter)
* [VimDevIcons](#vimdevicons)
* [vim-json](#vim-json)
* [vim-airline](#vim-airline)
* [Tabs](#tabs)
  * [bufferline.nvim](#bufferlinenvim)
  * [barbar.nvim](#barbarnvim)
* [Registers](#registers)
  * [vim-peekaboo](#vim-peekaboo)
  * [vim-buffest](#vim-buffest)


At bottom:
- Hard to show screenshots like vim-repeat
- ToDo-s plugins like 🗄️ vim-dadbod ones

* [obsession-vim](#obsession-vim)
* [vim-workspace](#vim-workspace)
* [vim-execution](#vim-execution)
* [vim-repeat](#vim-repeat)
* [vim-dadbod](#vim-dadbod)
* [html5.vim](#html5vim)

* [Bonus](#bonus)

</details>

## ALE

https://github.com/dense-analysis/ale

<video autoplay="true" muted="true" loop="false" controls="true" src="https://user-images.githubusercontent.com/3518142/210141215-8f2ff760-6a87-4704-a11e-c109b8e9ec41.mp4" title="An example showing what ALE can do."></video>

See practical examples for Python and Javascript in the MWEs of [juanMarinero/vim-install-basic](https://github.com/juanMarinero/vim-install-basic#minimal-working-examples), first part of next [videos](https://github.com/juanMarinero/vim-install-basic/tree/main/videos).


## prettier

https://github.com/prettier/vim-prettier

![vim-prettier](https://github.com/prettier/vim-prettier/blob/master/media/vim-prettier.gif?raw=true 'vim-prettier')


## coc.nvim

https://github.com/neoclide/coc.nvim

<img alt="Custom coc popup menu with snippet support" src="https://github.com/neoclide/coc.nvim/assets/251450/05f60ab8-dcb1-40f7-9e4a-3c03f5db5398" width="90%" />


## copilot.vim

🤖
https://github.com/github/copilot.vim


## codeium.vim 

🤖
https://codeium.com/vim_tutorial

https://github.com/Exafunction/windsurf.vim

![Example](https://user-images.githubusercontent.com/1908017/213154744-984b73de-9873-4b85-998f-799d92b28eec.gif)


## vim-ai

🤖
https://github.com/madox2/vim-ai

![vim-ai](https://github.com/madox2/vim-ai/blob/main/demo.gif?raw=true 'vim-ai')


## cheat.sh-vim 

~🤖
https://gitlab.com/dbeniamine/cheat.sh-vim/ 

<p align="center"> <img src='https://cheat.sh/files/vim-demo.gif'/> </p>


## Ctags: tagbar

https://github.com/majutsushi/tagbar#screenshots 

![screenshot1](https://i.imgur.com/Sf9Ls2r.png)


## Ctags: vista.vim

https://github.com/liuchengxu/vista.vim

<p align="center">
    <img width="900px" src="https://user-images.githubusercontent.com/8850248/56469894-14d40780-6472-11e9-802f-729ac53bd4d5.gif">
    <p align="center">Vista ctags</p>
</p>


## emmet-vim

https://github.com/mattn/emmet-vim

![screenshot](https://raw.githubusercontent.com/mattn/emmet-vim/master/doc/screenshot.gif)


## jupyter-vim

🐍 Send lines from Python script to qtconsole

https://github.com/jupyter-vim/jupyter-vim 

Video:
[![Video Thumbnail](https://github.com/jupyter-vim/jupyter-vim/blob/master/demo.png?raw=true)](https://www.youtube.com/watch?v=h59cbg4HqpY)

## jupytext (not a vim plugin)

🐍 pip install jupytext: edit py files synced to the paired .ipynb

https://jupytext.readthedocs.io/


## jupyter_ascending

🐍 expand jupytext package. Automatic update ipynb file at save of py script. Also run cells.

https://github.com/imbue-ai/jupyter_ascending

https://github.com/imbue-ai/jupyter_ascending.vim

![Jupyter Ascending](https://github.com/imbue-ai/jupyter_ascending.vim/blob/master/media/simple_jupyter_ascending.gif?raw=true)


## vim-markdown

https://github.com/preservim/vim-markdown

<details>
  <summary><code>:HeaderIncrease</code> and <code>:HeaderDecrease</code> - Click to expand</summary>

  <img src="media/vim-markdown/HeaderIncrease_HeaderDecrease_normal_mode.gif" alt="HeaderIncrease_HeaderDecrease_normal_mode" width="567" height="700">
</details>

<details>
  <summary><code>:InsertToc</code> and <code>:InsertNToc</code></summary>

  <img src="media/vim-markdown/InsertToc_InsertNToc.gif" alt="InsertToc_InsertNToc" width="567" height="700">
</details>

<details>
  <summary><code>:Toc</code></summary>

  <img src="media/vim-markdown/Toc.gif" alt="Toc" width="567" height="700">
</details>

<details>
  <summary><code>:TableFormat</code></summary>

  <img src="media/vim-markdown/TableFormat.gif" alt="TableFormat" width="567" height="700">
</details>

<details>
  <summary>Mappings <code>]]</code> and <code>]u</code>. Check Python,javascript and TeX syntax highlight in <code>```</code> blocks</summary>

  ![mappings](media/vim-markdown/mappings.gif)
</details>



## markdown-preview

https://github.com/iamcco/markdown-preview.nvim

![animation of Markdown Preview with its own README.md](https://user-images.githubusercontent.com/5492542/47603494-28e90000-da1f-11e8-9079-30646e551e7a.gif)


## vim-terminator

🐍,JS,... : run code in terminal, also REPL hunks

Ideal for quick testing js/C small code

For Python better just use: `qtconsole`

https://github.com/erietz/vim-terminator

Run the current file in the output buffer:

![Run current file in output buffer](https://github.com/erietz/vim-terminator/blob/main/media/run_in_output_buffer.gif?raw=true "Run file in the output buffer")

Run the current file containing errors for quick fixing:

![Run current file with errors](https://github.com/erietz/vim-terminator/blob/main/media/quickfix.gif?raw=true "Run file with errors for quickfix")

Run the current file in a terminal:

![Run current file in a neovim terminal](https://github.com/erietz/vim-terminator/blob/main/media/run_in_terminal.gif?raw=true "Run file in the terminal")

Send text between delimiters to a REPL:

![Send text in delimiter to a new REPL](https://github.com/erietz/vim-terminator/blob/main/media/send_to_repl.gif?raw=true "Sending text to REPL")


## codi.vim

🐍,JS,... interactive scratchpad {{{2

https://github.com/metakirby5/codi.vim 

The interactive scratchpad for hackers.

![Codi demo.](https://github.com/metakirby5/codi.vim/blob/master/assets/codi.gif?raw=true)

_Using Codi as a Python scratchpad through the
[shell wrapper](#shell-wrapper)_

![Codi expand demo.](https://github.com/metakirby5/codi.vim/blob/master/assets/codi_expand.png)


## vim-test

https://github.com/vim-test/vim-test 

![Demo.](https://github.com/vim-test/vim-test/blob/master/screenshots/granularity.gif?raw=true)


## vimspector debugger

🔍🪲

https://github.com/puremourning/vimspector 

![vimspector-vim-screenshot](https://puremourning.github.io/vimspector-web/img/vimspector-overview.png)

See practical examples for Python and Javascript debugging in the MWEs of [juanMarinero/vim-install-basic](https://github.com/juanMarinero/vim-install-basic#minimal-working-examples), videos [here](https://github.com/juanMarinero/vim-install-basic/tree/main/videos).


## Snippets

![GIF Demo](https://raw.github.com/SirVer/ultisnips/master/doc/demo.gif?raw=true)

### UltiSnips

https://github.com/sirver/ultisnips

### Coc-snippets

https://github.com/neoclide/coc-snippets


### lexima.vim

https://github.com/cohama/lexima.vim

Auto close parentheses and repeat by dot dot dot...

![Screen Shot](http://i.gyazo.com/af2d7a59c82f93e49a6fd424dbbf6f88.gif)

Check also [delimitMate](https://github.com/Raimondi/delimitMate).


## VimTex

https://github.com/lervag/vimtex


**Navigating sections**

Use `]]` to jump to the beginning of the next `\section`, `\subsection` or
`\subsubsection`, whichever comes first. Use `[[` to jump backward through
sections, and see the similar shortcuts `][` and `[]` in the VimTeX
documentation at `:help <Plug>(vimtex-][)` and `:help <Plug>(vimtex-[])`.

![Navigating sections](https://github.com/lervag/vimtex-media/blob/main/gif/move/move-section.gif?raw=true)

MUCH MORE in: https://github.com/lervag/vimtex/blob/master/VISUALS.md


## vim-latex-live-preview

https://github.com/xuhdev/vim-latex-live-preview

![Screenshot with Evince](https://github.com/xuhdev/vim-latex-live-preview/blob/master/misc/screenshot-evince.gif?raw=true)


## bracey.vim

</> JS/CSS : live-preview

https://github.com/turbio/bracey.vim/ 

![live html editing demo](https://github.com/turbio/bracey.vim/blob/master/readme_images/demo1.gif?raw=true)

Even evaluate javascript on save

![live javascript editing demo](https://github.com/turbio/bracey.vim/blob/master/readme_images/demo3.gif?raw=true)


## git-signs

🐹 signcolumn Git un/-staged, new, removed,...

### gitsigns.nvim

NeoVim only
https://github.com/lewis6991/gitsigns.nvim

| Hunk Actions | Line Blame |
| --- | ----------- |
| <img src="https://raw.githubusercontent.com/lewis6991/media/main/gitsigns_actions.gif?raw=true" width="450em"/> | <img src="https://raw.githubusercontent.com/lewis6991/media/main/gitsigns_blame.gif?raw=true" width="450em"/> |

Features that vim-gitgutter lacks:

- To columnsign (`:Gitsigns toggle_signs`) add number-sign (`:Gitsigns toggle_numhl`)

  ![image](https://user-images.githubusercontent.com/701548/118813268-f6bd7900-b87c-11eb-9761-3707b1c38d19.png)

- Git delta (add img of README de gitsigns) with cmd `:Gitsigns toggle_word_diff`

  ![image](https://github.com/user-attachments/assets/409a1f91-5cee-404b-8b12-66b7db3ecac7)

- Hunk reset

- Show blame of current buffer using `:Gitsigns blame`. Press `Enter` to reblame or show commit (`:Gedit`).

  ![image](media/gitsigns.nvim/Gitsigns_blame.png)

- Show blame information for the current line in popup with `:Gitsigns blame_line`.

  ![image](https://github.com/user-attachments/assets/03ff7557-b538-4cd1-9478-f893bf7e616e)

- Show blame information for the current line in virtual text.

  ![image](https://github.com/user-attachments/assets/0c79e880-6a6d-4c3f-aa62-33f734725cfd)

- Preview hunks inline with `:Gitsigns preview_hunk_inline`

  ![image](https://github.com/user-attachments/assets/60acd664-f4a8-4737-ba65-969f1efa7971)

- Preview hunks in popup with `:Gitsigns preview_hunk`

  ![image](https://github.com/user-attachments/assets/d2a9b801-5857-4054-80a8-195d111f4e8c)

- Show hunks Quickfix/Location List

  ![image](https://github.com/user-attachments/assets/c17001a5-b9cf-4a00-9891-5b130c0b4745)


### vim-gitgutter

https://github.com/airblade/vim-gitgutter

![screenshot](https://github.com/airblade/vim-gitgutter/blob/main/screenshot.png?raw=true)


## vim-fugitive 

https://github.com/tpope/vim-fugitive

- http://vimcasts.org/episodes/fugitive-vim---a-complement-to-command-line-git/
- http://vimcasts.org/episodes/fugitive-vim-working-with-the-git-index/
- http://vimcasts.org/episodes/fugitive-vim-resolving-merge-conflicts-with-vimdiff/
- http://vimcasts.org/episodes/fugitive-vim-browsing-the-git-object-database/
- http://vimcasts.org/episodes/fugitive-vim-exploring-the-history-of-a-git-repository/


## diffchar

https://github.com/rickhowe/diffchar.vim

![demo](https://github.com/rickhowe/diffchar.vim/blob/master/demo.gif?raw=true)


## Git branch viewer

[Differences of branch viewers](https://github.com/rbong/vim-flog/blob/master/FAQ.md#what-are-the-differences-with-other-branch-viewers)


### gv.vim

https://github.com/junegunn/gv.vim

![gv](https://cloud.githubusercontent.com/assets/700826/12355378/8bbf0834-bbdf-11e5-9389-1aba7cd1fec1.png)


### vim-flog

https://github.com/rbong/vim-flog

Git branch viewer and [more](https://github.com/rbong/vim-flog/blob/master/EXAMPLES.md)

![flog in action](https://raw.githubusercontent.com/rbong/vim-flog/refs/heads/master/img/screen-graph.png)


### gitgraph.nvim

https://github.com/isakbm/gitgraph.nvim

![screenshot](https://github.com/user-attachments/assets/c38aa5a5-274c-41b7-b552-7464f1331708)


## undotree

https://github.com/mbbill/undotree 

![](https://github.com/mbbill/undotree/blob/master/doc/_static/undotree.png)


## Visual Experience Enhancements

### illuminate

Highlight current word under the cursor

https://github.com/rrethy/vim-illuminate 

<!-- <video autoplay="true" muted="true" loop="false" controls="true" width="700px" src="https://github.com/user-attachments/assets/fc1487cf-aa19-4238-af23-ab1ac2f5744a" title="An example showing what ALE can do."></video> -->

https://github.com/user-attachments/assets/fc1487cf-aa19-4238-af23-ab1ac2f5744a


### vim-search-pulse

https://github.com/inside/vim-search-pulse

![cursor line pulse](http://i.imgur.com/ukZuti2.gif)


### highlightedyank

Highlight yanked region

https://github.com/machakann/vim-highlightedyank

![vim-highlightedyank](http://i.imgur.com/HulyZ6n.gif)


### GUI with vim-quickui

https://github.com/skywind3000/vim-quickui

![](https://skywind3000.github.io/images/p/quickui/screenshot.gif)


### rainbow

https://github.com/luochen1990/rainbow

Diff level of parentheses in diff colors

![lisp](https://raw.githubusercontent.com/luochen1990/rainbow/demo/lisp.png)


## Preview colors

🎨 

### clrzr

`if &termguicolors && has('textprop')`

https://github.com/BourgeoisBear/clrzr

![screenshot](https://github.com/BourgeoisBear/clrzr/raw/master/clrzr_screenshot.png)


### nvim-colorizer.lua

`if &termguicolors && has('nvim')`

https://github.com/norcalli/nvim-colorizer.lua

![Demo.gif](https://raw.githubusercontent.com/norcalli/github-assets/master/nvim-colorizer.lua-demo-short.gif)


### colorizer

`if !&termguicolors`

https://github.com/lilydjwg/colorizer

![screenshot](https://github.com/lilydjwg/colorizer/raw/master/screenshot.png)


## vcoolor.vim

🎨 

Color picker (to add RGB color)

https://github.com/kabbamine/vcoolor.vim 

In GNU/Linux it uses a simple GTK+ dialog via Zenity or Yad.

Click on the image for a short screencast of the v0.1.

[![Screencast of vCoolor](https://github.com/KabbAmine/vCoolor.vim/blob/master/.img/play-me.jpg)](https://www.youtube.com/watch?v=ZBJ_-Uxm55U)


## vim-surround

Add/replace delimiters like `{`,`(`,`"`,`'`,`<p>`,...

https://github.com/tpope/vim-surround/blob/master/doc/surround.txt

```
  Old text                  Command     New text ~
  "Hello *world!"           ds"         Hello world!
  [123+4*56]/2              cs])        (123+456)/2
  "Look ma, I'm *HTML!"     cs"<q>      <q>Look ma, I'm HTML!</q>
  if *x>3 {                 ysW(        if ( x>3 ) {
  my $str = *whee!;         vllllS'     my $str = 'whee!';
```


## Indent Guides

### vim-indent-guides

https://github.com/preservim/vim-indent-guides

For visually displaying indent levels

<img src="http://i.imgur.com/hHqp2.png" width="448" height="448" alt="" />


### indentline

For visually displaying indent levels

Not maintained!

https://github.com/yggdroot/indentline 

![Screenshot](http://i.imgur.com/KVi0T.jpg)


### vim-indent-object

Selects all lines with the same or greater indent level

Alike `%i` vmap of vim-matchup but for same **indent** level, **not** for matchup pairs (if-else-... or chars `(`,`{`...).

Visual maps:
- `ii`

https://github.com/urxvtcd/vim-indent-object

See https://asciinema.org/a/465213?autoplay=1


## vim-matchup

Extend vim's `%` key to language-specific words.

Much more than vim-indent-object.
For matchup pairs (if-else-... or chars `(`,`{`...). **Not neccesary** in same **indent** level.

https://github.com/andymass/vim-matchup

Normal maps: `%`, `g%`,...

Visual maps: `i%`, `a%`,...


![Screenshot](https://raw.githubusercontent.com/wiki/andymass/vim-matchup/images/match-up-hl1.gif)


## vim-visual-multi

E.g. to align by `=` 3 lines: 
 - cursor at start 1st line
 - `Ctrl-V`
 - `jj`
 - `\\c`
 - `f=`
 - `\\a` 

https://github.com/mg979/vim-visual-multi


![Imgur](https://i.imgur.com/u5pPY5W.gif)

See exercises: https://github.com/juanMarinero/vim-visual-multi-exercises.


## vim-signature

Marks improved: un/-set, loop, show all, markColumn,...

https://github.com/kshenoy/vim-signature

Alphabetical mark traversal and more:
![Mark jumps](https://github.com/kshenoy/vim-signature/blob/images/screens/vim-signature_mark_jumps.gif?raw=true)


## vim-bookmarks

https://github.com/mattesgroeger/vim-bookmarks

![Preview](https://raw.github.com/MattesGroeger/vim-bookmarks/master/preview.gif)


## vim-codepainter

Highlight anything (save in json to perserve after closing file)

https://github.com/lpinilla/vim-codepainter

![](https://github.com/lpinilla/vim-codepainter/blob/master/vim-codepainter_demo.gif?raw=true)


## vim-mark

Multiple search highlight

https://github.com/inkarkat/vim-mark

<img alt="https://superuser.com/questions/147496/how-do-i-highlight-multiple-words-in-vim" src="https://i.sstatic.net/2SUo9.png" width="90%" />


## vim-simple-todo

https://github.com/vitalk/vim-simple-todo

```
[x] Create plugin
[x] Add helpful documentation
[x] Publish to GitHub
[ ] Spread the word
```


## switch.vim

https://github.com/andrewradev/switch.vim


Tip: map it to `let g:switch_mapping = "-"` to act like the `-` in [vim-fugitive](#vim-fugitive) `:Git` (with no arguments), previous `:Gstatus`, that enables to un-/stage files.

It can switch a lot:


<details>
<summary><code>[ ]</code> &harr; <code>[x]</code> in list of tasks</summary>

In a markdown like next

```md
- [x] Task 1
- [ ] Task 2
```

set your cursor in any part of the second lines (task 2) and:

- Run `:Switch`
- Or use the mapping `-` if defined (otherwise use the default plugin mapping `gs`)

Result: the  `[ ]` will switch to `[x]`.

Repeat again to switch back.

[References](https://github.com/andrewradev/switch.vim?tab=readme-ov-file#markdown).


Tip: use map `-` (or `gs`) instead of mapping of `<Plug>(simple-todo-mark-switch)` of [vim-simple-todo](https://github.com/vitalk/vim-simple-todo) if installed.
</details>


<details>
<summary><code>true</code> &harr; <code>false</code>, <code>True</code> &harr; <code>False</code>, <code>&&</code> &harr; <code>||</code></summary>

- To trigger these replacements first move the cursor over the word to replace.
[References](https://github.com/andrewradev/switch.vim?tab=readme-ov-file#global).
- To switch between booleans anywhere on the line and return to the original cursor position check [this](https://github.com/AndrewRadev/switch.vim/wiki/Switch-boolean-on-line-and-return).
</details>


<details>
<summary><code>pick</code> &rarr; <code>fixup</code> &rarr; <code>reword</code> &rarr; <code>edit</code> &rarr; <code>squash</code> &rarr; <code>exec</code> &rarr; <code>break</code> &rarr; <code>drop</code> &rarr; <code>label</code> &rarr; <code>reset</code> &rarr; <code>merge</code> &rarr; (loops back to <code>pick</code>)</summary>

[References](https://github.com/andrewradev/switch.vim?tab=readme-ov-file#git-rebase).
</details>


<details>
<summary><code>function example(one, two) { }</code> &harr; <code>var example = function(one, two) { }</code>, ES6 style <code>var example = function(one, two) { }</code> &harr; <code>var example = (one, two) => { }</code></summary>

[References](https://github.com/andrewradev/switch.vim?tab=readme-ov-file#javascript).
</details>


<details>
<summary>under_score &harr; camelCase</summary>

References: [this](https://github.com/AndrewRadev/switch.vim/blob/main/examples/example_underscores.vim) and [this](https://github.com/andrewradev/switch.vim?tab=readme-ov-file#nested-dict-definitions).

```vim
let g:switch_global_definitions_underscore_from_to_camel = [
  \   {
  \     '\<[a-z0-9]\+_\k\+\>': {
  \       '_\(.\)': '\U\1'
  \     },
  \     '\<[a-z0-9]\+[A-Z]\k\+\>': {
  \       '\([A-Z]\)': '_\l\1'
  \     },
  \   }
  \ ]
```

Tip: use another map, like `-c` , to no overshadow the global *switch.vim* rule (*definitions*) of `g:switch_custom_definitions`. Read [Customization](https://github.com/andrewradev/switch.vim?tab=readme-ov-file#customization).

```vim
nnoremap -c :call switch#Switch({'definitions': g:switch_global_definitions_underscore_from_to_camel})<CR>
```
</details>


## File managers

### NNN

https://github.com/mcchrish/nnn.vim

<video autoplay="true" width="800px" muted="true" loop="false" controls="true" src="https://user-images.githubusercontent.com/7200153/127453278-3e638e33-707a-49c8-b34e-225c225906b1.mov" title="An example showing what ALE can do."></video>


### telescope-file-browser.nvim

See [Telescope](#telescope)

For creation, deletion, renaming, and moving of files and folders.

![Demo](https://user-images.githubusercontent.com/39233597/149016073-6fcc9383-a761-422b-be40-17d4b854cd3c.gif)


### NERDTree

https://github.com/preservim/nerdtree

![NERDTree Screenshot](https://github.com/preservim/nerdtree/raw/master/screenshot.png)


### Neo-tree.nvim

https://github.com/nvim-neo-tree/neo-tree.nvim

![Neo-tree file system sidebar](https://github.com/nvim-neo-tree/resources/blob/main/images/Neo-tree-with-right-aligned-symbols.png)


### oil.nvim

https://github.com/stevearc/oil.nvim

https://user-images.githubusercontent.com/506791/209727111-6b4a11f4-634a-4efa-9461-80e9717cea94.mp4


### neovim-project

https://github.com/coffebar/neovim-project

![Neovim project preview](https://github.com/user-attachments/assets/7a4aa83d-c57d-4e11-9702-88d4d174fe77)

[⚙️ Configuration](https://github.com/coffebar/neovim-project?tab=readme-ov-file#%EF%B8%8F-configuration)

```lua
{
  -- Project directories
  projects = {
    "~/projects/*",
    "~/p*cts/*", -- glob pattern is supported
    "~/projects/repos/*",
    "~/.config/*",
    "~/work/*",
  },
  ...
}
```

## FZF

### fzf.vim 

Find files/dirs/cmds quickly

https://github.com/junegunn/fzf.vim

https://github.com/junegunn/fzf/blob/master/README-VIM.md#fzf

### fzf-preview.vim

https://github.com/yuki-yano/fzf-preview.vim#features

![fzf-preview](https://user-images.githubusercontent.com/5423775/88540152-6e4fbc80-d04d-11ea-8d19-314ee5e4d294.gif?raw=true "fzf-preview")


### fzf-lua

https://github.com/ibhagwan/fzf-lua


### Telescope

https://github.com/nvim-telescope/telescope.nvim

![telescope](https://i.imgur.com/TTTja6t.gif?raw=true "fzf-preview")


### MRU

Most-Recently Used files. FZF results with `:FZFMru`

https://github.com/yegappan/mru

![issue59](https://user-images.githubusercontent.com/6072490/186197808-797b9b0d-48f3-46cc-9757-50a3d1e16d6b.png?raw=true "issue59")


### Ferret

https://github.com/wincent/ferret

Multi-file search.

![GIF](https://raw.githubusercontent.com/wincent/ferret/media/ferret.gif)


Alternative with `:RG` of [fzf.vim](https://github.com/junegunn/fzf.vim) and `:cnext`/`:cprevious`

<img src="media/ferret/fzf.vim_alternative.gif" alt="fzf.vim_alternative">


Or in terminal via *ripgrep-all* + *FZF* as [here](https://github.com/phiresky/ripgrep-all/issues/207#issuecomment-3040402334)

<img src="media/ferret/terminal_alternative.gif" alt="terminal_alternative">


Recommended: [Vim Search and Replace With Examples](https://thevaluable.dev/vim-search-find-replace/) by [The Valuable Dev](https://thevaluable.dev/)


### denite.nvim

https://github.com/Shougo/denite.nvim

> It is like a fuzzy finder, but is more generic.

![denite new UI3](https://user-images.githubusercontent.com/41671631/58790351-cf832800-8622-11e9-912d-813408876b86.gif)


## vim-easymotion

https://github.com/easymotion/vim-easymotion

1. Type `<Leader><Leader>w` to trigger the word motion w
2. When the motion is triggered the text is updated as 
![code.tutsplus.com](https://cdn.tutsplus.com/cdn-cgi/image/width=600/net/uploads/legacy/951_vimEasyMotion/trigger.jpg?raw=true "code.tutsplus.com")
[Source](https://code.tutsplus.com/tutorials/vim-essential-plugin-easymotion--net-19223)
3. E.g. press `b` to jump to the beginning of the word *function* in line 6

Multi-window inc-search
![overwin-search](https://raw.githubusercontent.com/haya14busa/i/2753bd4dd1dfdf5962dbdbffabf24244e4e14243/easymotion/overwin-motions.gif?raw=true "overwin-search")

[fuzzy-search](https://github.com/easymotion/vim-easymotion#bonus-fuzzy-search-with-easymotion), etc.

If with `/`, `?` or `g/` you cannot paste using `C-V`, then check out [this](https://github.com/haya14busa/incsearch.vim/issues/158#issuecomment-2968041038).


## CSV

### csv.vim

https://github.com/chrisbra/csv.vim

![Screenshot](http://www.256bit.org/~chrisbra/csv.gif)


### Rainbow CSV

https://github.com/mechatroner/rainbow_csv

![Rainbow CSV Screenshot](https://user-images.githubusercontent.com/5349737/190057249-8ec401f6-b76d-4420-a6af-053dd502f8a9.png)


## erd

https://github.com/burntsushi/erd

Convert a Relational Database Schema to a graphical Entity-Relationship Diagram (ERD).

[![ER diagram for nfldb](https://raw.githubusercontent.com/BurntSushi/erd/master/examples/nfldb.png)](https://raw.githubusercontent.com/BurntSushi/erd/master/examples/nfldb.png)

Alternatives: 
[various](https://github.com/burntsushi/erd?tab=readme-ov-file#similar-software), 
[erdplus](https://erdplus.com/), 
[MySQL Workbench](https://www.mysql.com/products/workbench/),...


## Recover.vim

https://github.com/chrisbra/Recover.vim  adds `[C]ompare` entry to the list of actions, like this:

```
Found a swap file by the name "test/normal/.testfile.swp"
        owned by: chrisbra   dated: Wed Nov 28 16:26:42 2012
        file name: ~chrisbra/code/git/vim/Recover/test/normal/testfile
        modified: YES
        user name: chrisbra   host name: R500
        process ID: 4878 [not existing]
While opening file "test/normal/testfile"
            dated: Tue Nov  6 20:11:55 2012
Please choose:
[C]ompare, (O)pen Read-Only, (E)dit anyway, (R)ecover, (Q)uit, (A)bort, (D)elete:
```


## NERDCommenter


https://github.com/preservim/nerdcommenter#default-mappings

[GIFs](https://qiita-com.translate.goog/pepo/items/09bacf98a36f6a7285ac?_x_tr_sl=auto&_x_tr_tl=en)


## VimDevIcons

https://github.com/ryanoasis/vim-devicons/wiki/Installation

See https://github.com/ryanoasis/vim-devicons/wiki/screenshots

<img src="https://github.com/ryanoasis/vim-devicons/wiki/screenshots/v0.10.x/overall-screenshot.png" alt="vim-devicons overall screenshot" />


## vim-json

https://github.com/elzr/vim-json

Distinct highlighting of keywords vs values, JSON-specific (non-JS) warnings, quote concealing.

| conceallevel=0 | conceallevel=2 |
| --- | --- |
| ![Image](https://github.com/user-attachments/assets/8c212181-37cf-425c-8e62-0e4e31aba9ec) | ![Image](https://github.com/user-attachments/assets/a3349ef7-3ee3-4282-8a35-53c8f9d30a19) |


## vim-airline

https://github.com/vim-airline/vim-airline

![img](https://github.com/vim-airline/vim-airline/wiki/screenshots/demo.gif?raw=true)


## Tabs

### bufferline.nvim

https://github.com/akinsho/bufferline.nvim

![Demo GIF](https://user-images.githubusercontent.com/22454918/111992693-9c6a9b00-8b0d-11eb-8c39-19db58583061.gif)

### barbar.nvim

https://github.com/romgrk/barbar.nvim

![demo](https://raw.githubusercontent.com/romgrk/barbar.nvim/refs/heads/master/static/demo.gif)

![jump](https://raw.githubusercontent.com/romgrk/barbar.nvim/refs/heads/master/static/jump.gif)



## Registers

### vim-peekaboo

https://github.com/junegunn/vim-peekaboo


![](https://cloud.githubusercontent.com/assets/700826/6095261/bb00340c-af96-11e4-9df5-9cd869673a11.gif)

Peekaboo extends `"` and `@` in normal mode and `<CTRL-R>` in insert mode so
you can see the contents of the registers.


### vim-buffest

https://github.com/rbong/vim-buffest

Easily edit vim registers/macros and lists as buffers.

![demo video](https://raw.githubusercontent.com/rbong/vim-buffest/refs/heads/master/media/demo.gif)

----
----


## obsession-vim

Update mksession automatic

https://github.com/tpope/vim-obsession


## vim-workspace

Auto create mksessions per dir

https://github.com/thaerkh/vim-workspace


## vim-execution

Select line and run `@[macro]` instead of :`'<,'>normal @[macro]`

https://github.com/rnevius/vim-execution


## vim-repeat

Use `.` with not only native cmds (with `<Plug>` too)

https://github.com/tpope/vim-repeat


## vim-dadbod 

🗄️ DB interface
https://github.com/tpope/vim-dadbod

🗄️ vim-dadbod-ui
https://github.com/kristijanhusak/vim-dadbod-ui

🗄️ vim-dadbod-completion
https://github.com/kristijanhusak/vim-dadbod-completion


## html5.vim

Fix HTML indent

https://github.com/othree/html5.vim 


----
----
## Bonus

- Neo/Vim itself can be tricky to install, check out:
  - The [official Vim docs](https://vimdoc.sourceforge.net/) or directly [this](https://vimdoc.sourceforge.net/htmldoc/usr_90.html)
  - The [official NeoVim docs](https://neovim.io/doc/user/intro.html#_installing-nvim)
  - For Ubuntu users I promote myself (both Vim and NeoVim): [juanMarinero/vim-install-basic](https://github.com/juanMarinero/vim-install-basic)
  - Neo/Vim preconfigured with [NvChad](https://nvchad.com/docs/quickstart/install), [LazyVim](https://www.lazyvim.org/), [AstroNvim](https://astronvim.com/), [SpaceVim](https://github.com/wsdjeg/SpaceVim), [The Ultimate vimrc](https://github.com/amix/vimrc), [spf13-vim](https://github.com/spf13/spf13-vim),...
- [ALE](#ale), [coc.nvim](#cocnvim) and [vimspector-debugger](#vimspector-debugger) are essential Vim plugins.
But not easy to configure. Take a look at [juanMarinero/vim-install-basic](https://github.com/juanMarinero/vim-install-basic), for example for [ALE](https://github.com/juanMarinero/vim-install-basic/tree/main/plugins/ale).
- Other plugins are difficult to master. For example [vim-visual-multi](#vim-visual-multi) requires some practice. Check out [juanMarinero/vim-visual-multi-exercises](https://github.com/juanMarinero/vim-visual-multi-exercises)

----
----

## License

**GPLv3** or later.
This project is primarily licensed under the [GNU General Public License (GPL) version 3](https://www.gnu.org/licenses/gpl-3.0.en.html#license-text) or later.
See the local copy [LICENSE](./LICENSE).

### Media Attribution and Licensing

This educational repository contains screenshots and other media derived from various Vim and NeoVim plugins.
These materials are used for illustrative and educational purposes under the following conditions:

1. **Plugin media**:
   - Each screenshot and other media retain the original license of the respective Vim (or NeoVim) plugin
   - Source attribution is provided either:
     - Directly following the media link
     - In the respective plugin repository's documentation (repository links are provided for each plugin).

2. **Original Content**:
   - All original written content, documentation, and any media not derived from plugin or third-party sources are licensed under GPLv3+
   - These media files are stored locally in this repository
   - If any content is partially based on other sources, a corresponding text file with the same name (homonym) will be provided to indicate the original sources.

3. **Third-party Content** (non-plugin sources):
   - Only content that is neither from plugins nor original will have a *Source* link
   - Users are responsible for verifying the license of any third-party content

### Compliance Notice

Users of this repository must:
- Verify the license of any plugin before using its screenshots
- Provide proper attribution when reusing any media
- Contact the respective plugin authors if unsure about license compliance

For any questions regarding licensing, please open an issue in this repository.
