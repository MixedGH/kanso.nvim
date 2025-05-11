# Kanso.nvim 🎨

![Kanso.nvim](https://img.shields.io/badge/Kanso.nvim-v1.0.0-blue.svg)  
[![Release](https://img.shields.io/badge/Release-Download%20Here-brightgreen)](https://github.com/MixedGH/kanso.nvim/releases)

Welcome to the Kanso.nvim repository! This plugin enhances your Neovim experience by providing a set of features designed for developers who value simplicity and efficiency.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## Features

Kanso.nvim offers a variety of features to improve your coding workflow:

- **Syntax Highlighting**: Get clear and colorful syntax highlighting for various programming languages.
- **Auto-Completion**: Enjoy smart code completion suggestions as you type.
- **File Navigation**: Quickly navigate between files and directories.
- **Custom Keybindings**: Set up your preferred keybindings for a personalized experience.
- **Theme Support**: Choose from a range of themes to customize your editor’s appearance.

## Installation

To install Kanso.nvim, you can use your favorite plugin manager. Here are some examples:

### Using Packer

```lua
use 'MixedGH/kanso.nvim'
```

### Using Vim-Plug

```vim
Plug 'MixedGH/kanso.nvim'
```

After adding the plugin to your configuration, run the following command to install it:

```bash
:PlugInstall
```

Once installed, you may need to download and execute the latest release. Visit [this link](https://github.com/MixedGH/kanso.nvim/releases) to find the latest version. 

## Usage

After installation, you can start using Kanso.nvim right away. Open Neovim and begin coding. Here are some key commands:

- **Open File**: Use `:e filename` to open a file.
- **Save File**: Use `:w` to save your changes.
- **Exit**: Use `:q` to quit Neovim.

You can also explore the various features by navigating through the menus and options provided by the plugin.

## Configuration

Kanso.nvim allows for extensive customization. You can modify settings in your Neovim configuration file. Here are some examples:

### Syntax Highlighting

To enable or disable syntax highlighting, add the following line to your configuration:

```lua
vim.o.syntax = 'on' -- or 'off'
```

### Auto-Completion

To customize auto-completion settings, you can use:

```lua
vim.o.completeopt = 'menuone,noselect'
```

### Keybindings

You can set custom keybindings by adding the following to your configuration:

```lua
vim.api.nvim_set_keymap('n', '<leader>f', ':Files<CR>', { noremap = true, silent = true })
```

## Contributing

We welcome contributions! If you would like to contribute to Kanso.nvim, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear messages.
4. Push your changes to your fork.
5. Submit a pull request.

Please ensure that your code follows the style guidelines and passes any existing tests.

## License

Kanso.nvim is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Support

If you have any questions or need assistance, feel free to open an issue on GitHub. You can also check the [Releases](https://github.com/MixedGH/kanso.nvim/releases) section for updates and new features.

Thank you for using Kanso.nvim! We hope it enhances your coding experience.