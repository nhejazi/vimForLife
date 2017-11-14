# Vim, for life. [![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg)](http://opensource.org/licenses/MIT)

> Setup, package manager, and various plug-ins for my configuration of the
> [Vim](http://www.vim.org/index.php) and [Neovim](https://neovim.io/) editors.

_Caveat emptor_ - using this configuration can be unintuitive at first
(especially for those new to Vim and/or Neovim).

---

## _Directions_

* For use with _Vim_, clone the configuration in this repo using the following:
  ```bash
  git clone https://github.com/nhejazi/vimForLife.git ~/.vim
  sh ~/.vim/_setupVim.sh
  ```

- For use with _Neovim_, instead clone the configuration in this repo like so:
  ```bash
  git clone https://github.com/nhejazi/vimForLife.git ~/.config/nvim
  sh ~/.config/nvim/_setupNeovim.sh
  ```

- To __install plugins__ with the
[vim-plug](https://github.com/junegunn/vim-plug) manager, see the directions
provided in the `README` of that project.

- To __update plugins__ with the
[vim-plug](https://github.com/junegunn/vim-plug) manager:
  ```vim
  :PlugUpdate
  ```

---

## _Known Problem(s)_

- There is a known issue with re-mapping `Ctrl-H` in Neovim's terminal mode. I
  have only encountered this issue when running macOS; various workarounds have
  been proposed [here](https://github.com/neovim/neovim/issues/2048).
  (__update:__ This issue has been resolved as of 15 May 2016.)

---

## Plug-ins

_Here is a list of plug-ins currently integrated into this configuration:_

* [`ack.vim`](https://github.com/mileszs/ack.vim)
* [`ale`](https://github.com/w0rp/ale) (with Vim 8.0+)
* [`codi.vim`](https://github.com/metakirby5/codi.vim)
* [`comfortable-motion.vim`](https://github.com/yuttie/comfortable-motion.vim)
* [`csv.vim`](https://github.com/chrisbra/csv.vim)
* [`ctrlp.vim`](https://github.com/ctrlpvim/ctrlp.vim)
* [`deoplete.nvim`](https://github.com/Shougo/deoplete.nvim) (Neovim only)
* [`goyo.vim`](https://github.com/junegunn/goyo.vim)
* [`gundo.vim`](https://github.com/sjl/gundo.vim)
* [`indentLine`](https://github.com/Yggdroot/indentLine)
* [`jedi-vim`](https://github.com/davidhalter/jedi-vim)
* [`julia-vim`](https://github.com/JuliaEditorSupport/julia-vim)
* [`limelight.vim`](https://github.com/junegunn/limelight.vim)
* [`neomake`](https://github.com/neomake/neomake)
* [`nerdcommenter`](https://github.com/scrooloose/nerdcommenter)
* [`NERDTree`](https://github.com/scrooloose/nerdtree)
* [`Nvim-R`](https://github.com/jalvesaq/Nvim-R)
* [`supertab`](https://github.com/ervandew/supertab)
* [`syntastic`](https://github.com/vim-syntastic/syntastic)
* [`vim-airline`](https://github.com/vim-airline/vim-airline)
* [`vim-airline-themes`](https://github.com/vim-airline/vim-airline-themes)
* [`vim-autoformat`](https://github.com/Chiel92/vim-autoformat)
* [`vim-easy-align`](https://github.com/junegunn/vim-easy-align)
* [`vim-fugitive`](https://github.com/tpope/vim-fugitive)
* [`vim-gitgutter`](https://github.com/airblade/vim-gitgutter)
* [`vim-markdown`](https://github.com/plasticboy/vim-markdown)
* [`vim-multiple-cursors`](https://github.com/terryma/vim-multiple-cursors)
* [`vim-sensible`](https://github.com/tpope/vim-sensible)
* [`vim-signify`](https://github.com/mhinz/vim-signify)
* [`vim-sleuth`](https://github.com/tpope/vim-sleuth)
* [`vim-tmux-navigator`](https://github.com/christoomey/vim-tmux-navigator)
    (Vim only)
* [`vim-wordy`](https://github.com/reedes/vim-wordy)

---

## Colorschemes

_This configuration currently supports two colorschemes:_

* [Zenburn](https://github.com/jnurmine/Zenburn) in terminal mode.
* [Solarized](https://github.com/altercation/vim-colors-solarized) in GUI mode.

---

## License

&copy; 2016-2017 [Nima Hejazi](http://nimahejazi.org)

The contents of this repository are distributed under the MIT license. See file
`LICENSE` for details.
