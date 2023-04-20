# Freddy's Dotfiles

It's nice to have all my environment stuff in one place so I can setup a new
computer quickly. This is meant for just me but feel free fork or look through
it and take any ideas from it. I strived to keep it as simple and minimalistic
as possible.

## Requirements

* Iterm2
* NeoVim
* GitHub Copilot
* Node.js (for Copilot)
* Tmuxinator

## Instructions

* Clone this to $HOME directory
* Edit `.gitconfig.local` if you have a new company GitHub account.
* Install thoughtbot [dotfiles](https://github.com/thoughtbot/dotfiles)
* Make sure `dotfiles-local` dotfiles are symlinked to $HOME directory
* Font and color scheme for iTerm 2 in `/themes`


## Keymap Cheatsheet

| Keymap | Description |
|--------|-------------|
| **NERDCommenter** | |
| `<Space>ci` | Invert comments |
| **NERDTree** | |
| `<Space>n` | Toggle NERDTree |
| **Vim Interactive Shell** | |
| `<Space>r` | Run in interactive shell |
| **Vim Test Runner** | |
| `<Space>gt` | Visit test |
| `<Space>a` | Run test suite |
| `<Space>l` | Run last test |
| `<Space>t` | Run test file |
| **Custom Keymaps** | |
| `<Space>w` | Save file |
| `<Space>s` | Substitute word under cursor |
| `<Space><Space>` | Switch between buffers |
| `tj` | Previous tab |
| `tk` | Next tab |
| `tc` | Close tab |
| `tn` | New tab |
| `<C-P>` | Open file picker |
| `<C-H>` | Move to left window |
| `<C-K>` | Move to top window |
| `<C-J>` | Move to bottom window |
| `<C-L>` | Move to right window |
| `J` | Move selected lines down |
| `K` | Move selected lines up |
| **Copilot** | |
| `<Space>c` | Toggle Copilot on/off |
| `<M-Bslash>` | Suggest completion |
| `<M-[>` | Previous suggestion |
| `<M-]>` | Next suggestion |
| `<C-]>` | Dismiss completion |
| `<S-Tab>` | Cycle through completions (backwards) |
| `<Tab>` | Accept completion |
| **lsp-zero** | |
| `K` | Show hover information |
| `gd` | Go to definition |
| `gD` | Go to declaration |
| `gi` | List implementations |
| `go` | Go to type definition |
| `gr` | List references |
| `gs` | Show signature information |
| `<F2>` | Rename symbol |
| `<F3>` | Format buffer |
| `<F4>` | Select code action |
| `gl` | Show diagnostics in floating window |
| `[d` | Previous diagnostic |
| `]d` | Next diagnostic |
| `<Ctrl-y>` | Confirm selection |
| `<Ctrl-e>` | Cancel completion |
| `<Down>` | Next item on the list |
| `<Up>` | Previous item on the list |
| `<Ctrl-n>` | Next completion item/Trigger completion menu |
| `<Ctrl-p>` | Previous completion item/Trigger completion menu |
| `<Ctrl-d>` | Scroll down documentation |
| `<Ctrl-u>` | Scroll up documentation |
