# oh-my-zsh Nova

This is a oh-my-zsh plugin for [python-novaclient](https://github.com/openstack/python-novaclient). It provides auto-complete for the nova so you don't need to remember all those pesky arguments.

# Installation

## [Antigen](github.com/zsh-users/antigen)

If you're using [Antigen](github.com/zsh-users/antigen), just add `antigen bundle rbirnie/oh-my-zsh-nova` to your `.zshrc` file where you're loading your other zsh plugins.

## [Oh-My-Zsh](https://github.com/robbyrussell/oh-my-zsh)

1. `mkdir -p ~/oh-my-zsh/custom/plugins`
2. `cd ~/oh-my-zsh/custom/plugins`
3. `git clone git@github.com:rbirnie/oh-my-zsh-nova.git`
4. `echo "plugins+=(send)" >> ~/.zshrc`

## [Zgen](tarjoilija/zgen)

If you're using [Zgen](tarjoilija/zgen), add `zgen load rbirnie/oh-my-zsh-nova` to your `.zshrc` file where you're loading your other zsh plugins.

If you have any issues you can open an issue here. Contributions are always welcome. Once all the subcommands are done I'll be submitting a pull request with [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) but it looks like they aren't maintaining anymore so I doubt that'll go too far. 
