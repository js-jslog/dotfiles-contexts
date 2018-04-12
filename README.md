# dotfiles-contexts
My personal context files for dotfile multiplexing

# Usage
1. Clone the dotfiles-multiplexer & this repository in your home directory
```
git clone git@github.com:js-jslog/dotfiles-multiplexer.git ~/dotfiles-multiplexer/
git clone git@github.com:js-jslog/dotfiles-contexts.git ~/dotfiles-contexts
```
2. Copy the required multiplexer context configuration file to the home directory
```
# example
cp ~/dofiles-contexts/.dotfiles-personal.yml ~/.dotfiles-multiplexer.yml
```
3. Run the dotfiles-multiplexer
```
cd ~/dotfiles-multiplexer
./setup.sh
```
4. Source the `.bashrc`
```
source ~/.bashrc
```
