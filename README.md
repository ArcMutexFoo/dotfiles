# How to use this repo?

Run

`git clone --bare git@github.com:ArcMutexFoo/dotfiles.git $HOME/dotfiles`
`alias bare="/usr/bin/git --git-dir=$HOME/dotfiles --work-tree=$HOME" >> $HOME/.bashrc`

source your .bashrc file

`bare config --local status.showUntrackedFiles no`
`bare checkout`
