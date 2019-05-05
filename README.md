# bash-with-git-branch

Add the line to .bashrc:

    PS1="\[\e]0;\u@\h: \w\a\]${debian_chroot:+($debian_chroot)}\[\033[01;32m\]\u@\h\[\033[00m\]:\[\033[01;34m\]\w\[\033[00m\]"'\[\033[0;32m\]$(__git_ps1 '\\\(%s\\\)'\[\033[33m\]⚡)\[\033[m\]\$ '
