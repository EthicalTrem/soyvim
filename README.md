# soyvim

## A neovim igniter for soydevs that can't code without 1000 plugins 

## Installation

1. Open a terminal.
  2. Navigate to the  ~/.config/nvim  directory by running the following command:
    cd ~/.config/nvim

  3. Remove all existing files and folders within the  nvim  directory by running the following command:
    rm -rf *
  This command will delete all files and folders within the  nvim  directory, but will not delete the  nvim  directory itself.
  4. Clone the  sovim  repository by running the following command:
    git clone https://github.com/tragdate/sovim .
  Note the  .  at the end of the command, which ensures that the repository is cloned into the current directory.
  5. Once the cloning process is complete, you can proceed with the next steps based on your specific requirements.
    • If you want to use the default configuration provided by  sovim , you can skip to step 7.
    • If you have an existing  init.vim  or  vimrc  file, make sure to back it up before proceeding.
  6. If you have your own configuration files, you can merge them with the  sovim  configuration. You can do this by copying your existing  init.vim  or  vimrc  file to  ~/.config/nvim/  and renaming it to  init.vim .
  7. Launch Neovim by running the following command:
    nvim

  8. Once Neovim is open, run the  :LazyUpdate  command by typing it into the command-line mode and pressing Enter.
  This command will update all plugins and dependencies specified in the  sovim  configuration.
  9. After the update process is complete, you can start using Neovim with the updated  sovim  configuration.
> Make sure to run `:Lazy update` after installing
