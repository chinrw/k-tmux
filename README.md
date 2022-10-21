# k-tmux

# Introduction

A tmux conf, which can work with [k-vim](https://github.com/chinrw/k-vim)

简要说明 [k-tmux](http://www.wklken.me/posts/2015/08/06/linux-tmux.html)

# Screenshot

![screenshot](https://raw.githubusercontent.com/wklken/gallery/master/tmux/tmux.png)

# Install

NOTE: make sure your tmux version >= 2.5

Recommend

```
1. backup old tmux config if it is necessary

cp ~/.tmux.conf ~/.tmux.conf_bak

2. just get the file

curl https://raw.githubusercontent.com/chinrw/k-tmux/master/tmux.conf > ~/.tmux.conf

3. TPM install
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm

4. tmux-mem-cpu-load (needs cmake)
https://github.com/thewtex/tmux-mem-cpu-load
cd <source dir>
cmake .
make
su -
make install

```

Use github

```
git clone https://github.com/chinrw/k-tmux.git
ln -s $PWD/k-tmux/tmux.conf ~/.tmux.conf
```

# Donation

You can Buy me a coffee:)  [link](http://www.wklken.me/pages/donation.html)


------------------------
------------------------

wklken

Email: wklken@yeah.net

Github: https://github.com/wklken

Blog: [http://www.wklken.me](http://www.wklken.me)

2015-08-06 ShenZheng
