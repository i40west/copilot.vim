# Copilot.vim

> [!WARNING]
> [copilot.lua](https://github.com/zbirenbaum/copilot.lua) is the way to go now.
> I am no longer using or keeping up with this fork, so don't use it.

GitHub Copilot uses OpenAI Codex to suggest code and entire functions in
real-time right from your editor.  Trained on billions of lines of public
code, GitHub Copilot turns natural language prompts including comments and
method names into coding suggestions across dozens of languages.

Copilot.vim is a Vim/Neovim plugin for GitHub Copilot.

To learn more, visit
[https://github.com/features/copilot](https://github.com/features/copilot).

## This Fork

This fork adds the ability to use shift-tab to accept only one line of
the suggestion.

Note: The only vimscript I've ever written before was my `.vimrc`. This
function was implemented with ChatGPT. 😂

## Subscription

GitHub Copilot requires a subscription.  It is free for verified students and
maintainers of popular open source projects on GitHub.

GitHub Copilot is subject to the [GitHub Additional Product
Terms](https://docs.github.com/en/site-policy/github-terms/github-terms-for-additional-products-and-features).

## Getting started

1.  Install [Neovim][] or the latest patch of [Vim][] (9.0.0185 or newer).

2.  Install [Node.js][].

3.  Install `github/copilot.vim` using vim-plug, packer.nvim, or any other
    plugin manager.  Or to install manually, run one of the following
    commands:

    * Vim, Linux/macOS:

          git clone https://github.com/i40west/copilot.vim.git \
            ~/.vim/pack/i40west/start/copilot.vim

    * Neovim, Linux/macOS:

          git clone https://github.com/i40west/copilot.vim.git \
            ~/.config/nvim/pack/i40west/start/copilot.vim

    * Vim, Windows (PowerShell command):

          git clone https://github.com/i40west/copilot.vim.git `
            $HOME/vimfiles/pack/i40west/start/copilot.vim

    * Neovim, Windows (PowerShell command):

          git clone https://github.com/i40west/copilot.vim.git `
            $HOME/AppData/Local/nvim/pack/i40west/start/copilot.vim

4.  Start Neovim and invoke `:Copilot setup`.

[Node.js]: https://nodejs.org/en/download/
[Neovim]: https://github.com/neovim/neovim/releases/latest
[Vim]: https://github.com/vim/vim

Suggestions are displayed inline and can be accepted by pressing the tab key.
See `:help copilot` for more information.

## Troubleshooting

We’d love to get your help in making GitHub Copilot better!  If you have
feedback or encounter any problems, please reach out on our [Feedback
forum](https://github.com/orgs/community/discussions/categories/copilot).
