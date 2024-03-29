# NeoVim
- [X] switch to lua config instead of hybrid vimscript/lua 
- [ ] ctrlp.vim
- [[Which autocompletion]]
	- [ ] Rust
    - [ ] How to make lsp recognize import framework ? (ex for smartpy) 
    - [ ] C (for dwm)
- [ ] Develop pluggin in Rust ? 
- [ ] setup plugin git 
- [ ] Look for a nice diff tool 
    - [ ] https://twitter.com/elijahmanor/status/1564251526633123840?s=20&t=T7J2g5SducUy3cyZyJ1-5A
    - [ ] https://github.com/sindrets/diffview.nvim
- [ ] Replace devicon to Nvim-web-devicons (is it really necessary)
- [ ] Add debuging pluggin 
- [ ] Asynchronous Lint Engine - https://github.com/dense-analysis/ale
- [ ] Better floating box: https://github.com/doums/suit.nvim
- [ ] subtile highlight for object same name: https://github.com/RRethy/vim-illuminate
- [ ] some pretty tree for todo: https://github.com/phaazon/mind.nvim
- [X] Add a middle line to know limit to write a line
- [X] Ctrl + D/U put the line in the middle of the screen 
- [X] Configure Telescope to also take in account the file in gitignore
- [ ] Undotree to get a history of what you have done in changes 
- [ ] Add icon in the nvm-cmp https://github.com/onsails/lspkind.nvim
- [ ] linting for solidity (not ALE)
- [ ] pimp treesitter to have the context of the function on top fo the file https://github.com/nvim-treesitter/nvim-treesitter-context
- [ ] have a cursor that move smoothly 
    - https://www.reddit.com/r/neovim/comments/xfjxoy/new_awesome_cursor_plugin/
    - https://github.com/karb94/neoscroll.nvim
- [ ] Add countour on the floating box for LSP and CMP 
- [ ] Try harpoon from ThePrimegean

-- links
ideas from pluggin here: https://github.com/weebcyberpunk/nyanvim
list of pluggins: https://github.com/chengwei920412/awesome-neovim-vim

# DWM

- [ ] clean up the file( put in .config/suckless, remove unecessayr file, change the dwm.desktop…)
    - [ ] Try to change the dwm.desktop with the Xsession var
- [ ] notification handle
- [ ] layout centered ?
- [ ] config mic headset not working 
        ([https://superuser.com/questions/1312970/headset-microphone-not-detected-by-pulse-und-alsa])
    - super hard to find the issue ...
- [ ] floating terminal in the middle of the screen hide/show
- [ ] disable follows hovermouse focus (https://wiki.archlinux.org/title/Dwm)
- [ ] Improve color theme nord 
- [ ] Improve animation picom
- [ ] Better status bar + widget
- [X] Better Font with ligature and better icon (Fira Code)


-- links ideas:
https://www.reddit.com/r/unixporn/comments/vbtnrs/dwm_hello_unixporn_my_first_time_posting_here/
https://www.reddit.com/r/unixporn/comments/vavw5y/dwm_after_a_year_from_switching_to_linux/
https://www.reddit.com/r/unixporn/comments/vav69k/dwm_i_love_doom/
https://www.reddit.com/r/unixporn/comments/vah4v2/dwm_heavenly_blade_steps/
https://www.reddit.com/r/unixporn/comments/w58g9p/dwm_phyos_beta_iso_released_sorry_for_the_delay/

# Obsidian
- [ ] More for Zettelkasten goal look at the book "How to take smartnote"
- [ ] Backlink in Obsidian (from a note where is it call)

# TMUX
- [X] Catppuccin theme
    
# Alacritty -> Kitty
- [ ] add icon for files 

# Software and Other
- [ ] Try to make colemak layout work easely with the open source Bigthing
    - Look for which layout is best (AngleMod/Wide)
- [ ] Setup my latex cv in VScode and github
- [ ] [[Autocompletion in zsh + startship + kitty]]
- [ ] Clean Linux home
- [ ] check out LibreWolf browser 
- [ ] pomodor terminal timer (is it really necessary) 
- [ ] See comparaison between moonlander and wierd keyboard
	- [ ] NOT FOR NOW ! WAIT END OF YEAR ! 
	- [ ] FOCUS ON ACTUAL WORK BEFORE THINKING OPTI
	- [ ] YOU DON'T NEED IT 
- [X] Add .config into your github
- [X] Notes in your github too
- [ ] look into git tree thing 
- [X] Spotify in terminal (no need)



# DONE
## NeoVim
- [X] global search: Telescope.nvim
    - [X] configure and play with it
	- [X] Setup leader key for thing like telescope.nvim, 
	- [X] Add ripgrep
	- [X] Add fuzzy search on the word on the cursor (grepstring cmd)
- [X] floating terminal in neovim  (too much with the dwm?) (Dont need that) 
- [X] Org-mode like: https://github.com/nvim-neorg/neorg (Using Telekasten for now) 
- [X] Neerdtree (Leader + t ) 
- [X] copypast
- [ ] [[Which autocompletion]]
	- [X] Setup built-in LSP
	- [X] Add python
	- [X] Add go 
	- [X] Add javascript
	- [X] [[Setting up Solidity LSP]]
- [X] Search for how to change font size in neovide (Won't use prefere the neovim in Kitty for now)
- [X] Config smooth scrolling and rapid (Using only D-U, and ok with that)
- [X] configure lualine
- [X] Look for a workflow where I'm not always quiting entering terminal 
	- [X] Use of Telescope and repgrep
- [X] Configure Nord theme in neovim to have a better background style with hovering popup

## DWM

- [X] setup ModKey + j/k to switch focus on windows (currently it move)
- [X] clean up the file( put in .config/suckless, remove unecessayr file, change the dwm.desktop…)
- [X] need a status bar
    - https://github.com/elkowar/eww
    - For now it's the dwmblocks
- [X] test WA/google meeting etc
- [X] monitor order/lunch script
- [X] short cut with screen shot flameshot
- [X] volume use amixer ( https://wiki.gentoo.org/wiki/Dwm)
- [X] rounded window and transparent y
	- done with picom
- [X] Config transparency
- [X] try alacry (rust terminal)
- [X] [https://tools.suckless.org/slock/](https://tools.suckless.org/slock/) 
	- use a repo git to just have a blurry screen when locked, no message
	- added shortcut for that 
- [X] Luminosity shortcut special key 
## Software and Other
- [X] Try Qtbrowser -> no extsion support, not very convinient with 1password
- [X] Look why lualine not pretty through terminal
	- [X] It was because of ligature not supported -> switch to kitty !
- [X] fix color font of alacritty to Nord theme (not working)
- [X] Try Awsome tilt manager
- [X] Try to make gnom more like a tilting WM 
