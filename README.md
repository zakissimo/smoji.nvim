# Smoji (Select Emoji)

<!-- ![Neovim Emoji Prompt Plugin](https://example.com/neovim-emoji-prompt-plugin.png) -->
TODO: Add image

## Overview

The Select Emoji Plugin (Smoji) is a simple and lightweight plugin for Neovim that provides a fast and efficient way to insert emojis into your commit messages. Inspired by the popular CLI tool gitmoji, this plugin aims to improve the commit message writing experience by presenting a prompt with a curated list of emojis.

<!-- ![Demo](https://example.com/neovim-emoji-prompt-demo.gif) -->
TODO: Add gif

## Features

- Fast and responsive emoji prompt within Neovim.
- Curated list of emojis sourced from gitmoji for meaningful commit messages.
- Easy-to-use interface with smooth emoji selection.

## Installation

Use your preferred package manager for Neovim, such as [vim-plug](https://github.com/junegunn/vim-plug), [Vundle](https://github.com/VundleVim/Vundle.vim), or [packer.nvim](https://github.com/wbthomason/packer.nvim).

For example, using vim-plug:

1. Add the following line to your Neovim configuration file (usually `init.vim` or `init.lua`).

   ```vim
   Plug 'zakissimo/smoji.nvim'
   ```

2. Reload your Neovim configuration and run `:PlugInstall` to install the plugin.

## Usage

1. When you are in insert mode, use the following command to trigger the emoji prompt:

   ```vim
   :Smoji
   ```

2. The emoji prompt will pop up, displaying a list of emojis along with their meanings.

3. Navigate and select the desired emoji.

4. Press Enter to insert the selected emoji into your commit message.

## Configuration

You can customize the behavior of the Neovim Emoji Prompt Plugin by setting the following options in your Neovim configuration file.

### `Custom emoji list`

By default, the plugin uses emojis from gitmoji. If you want to use a custom list of emojis, you can set this variable to a list of emoji strings. For example:

TODO!

### `Custom prompt message`

TODO!

### `Define mappings`

If you prefer to use custom mappings instead of `:Smoji` command

```vim
nnoremap <leader><leader>e :Smoji<CR>
```

## Acknowledgments

This plugin was inspired by the [gitmoji](https://gitmoji.dev/) CLI tool, which provides a list of emojis for use in commit messages.

## Contributing

If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request on the [GitHub repository](https://github.com/your_username/neovim-emoji-prompt-plugin).

---

Happy committing with emojis! 🎉😄🚀
