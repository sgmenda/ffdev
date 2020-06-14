# Aliases

Here are some aliases I use for Firefox Dev. They have been adapted from
[tangent spaces](https://tangentspaces.com/2020/04/04/vscode-gecko-coding/) and
the [ohmyzsh git
plugin](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/git/git.plugin.zsh#L28).

```
alias b="./mach build"
alias bb="./mach build binaries"
alias bcdb="./mach build && ./mach build-backend -b CompileDB"
alias bcvs="./mach build && ./mach build-backend -b CompileDB && ./mach build-backend -b VisualStudio"

alias hgg="hg glog"
alias hgd="hg diff"
alias hgdc="hg diff -rcentral"
alias hgs="hg status"
alias hgc="hg commit"
alias hgca="hg commit --amend"
alias hgpl="hg pull --rebase"
```
