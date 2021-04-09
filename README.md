这是我的debian Notebook
==========


DebianInit
==========

A script for fast deployment of desktop environment on Debian 7 with personal preferences encoded.

## Usage

* Install Debian 7 server (without desktop environment)
* Run the following code to the terminal

```
su
apt-get install sudo git
git clone https://github.com/grapeot/DebianInit
visudo # grant your user the sudo privilege
exit
cd DebianInit
./setup.sh | tee logs
```

## Vim
> `fisa-vim-config` [github](https://github.com/fisadev/fisa-vim-config) [website](https://vim.fisadev.com/)
```
# Install the required dependencies
sudo apt install git curl python3-pip exuberant-ctags ack-grep
sudo pip3 install pynvim flake8 pylint isort jedi
# Download the config file and save it as ~/.vimrc (super important to use that exact name).
# Open Vim and it will continue the installation by itself. Wait for it to finish... and done! You now have your new shiny powerful Vim :) 
```
- [vim-plug](https://github.com/junegunn/vim-plug/) `A minimalist Vim plugin manager.`


# Otherplatforms

## ec2-ubuntu

Also supports ubuntu on ec2 for scientific computing. Usage similar to debian.

## cygwin

Also supports cygwin for a fast linux-like environment. First download the 64bit installer from cygwin website, and then download the `cgywin.cmd` to the same folder. Double click to run. [`chocolatey`](https://chocolatey.org/) will be installed as the package management system.
