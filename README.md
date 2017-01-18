# Homebrew Casks for older Vagrant versions

Vagrant ver. 1.9.1 appears to have an Auth bug in it:
https://github.com/mitchellh/vagrant/issues/8204

This repo contains Casks built from commits in the caskroom/homebrew-cask GitHub.

## Version 1.8.6:
- https://github.com/caskroom/homebrew-cask/blob/fec6ef24e88577a613f7ce23baf96dea9e4df4ff/Casks/vagrant.rb

Install with:
```
% brew tap mexisme/vagrant-versions
$ brew cask install vagrant-186
```

## Version 1.9.0:
- https://github.com/caskroom/homebrew-cask/blob/00fe14389b62c9e561e530d082cda2942073484a/Casks/vagrant.rb


Install with:
```
% brew tap mexisme/vagrant-versions
$ brew cask install vagrant-190
```
