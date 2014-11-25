# 'Sup

As in what's up

## A little utility on top of @xolox's excellent [vim-notes] plugin.

Allows you to start a note for today (or +- any arbitary days), handy for recording daily tasks, specially
for standup/daily/scrum updates for "yesterday/today/blockers" (thank you @marcoemorais)

## Prerequisites
* Working vim ([sample vimrc]) with with [vim-notes],

## Usage

Run sup without anything to open note for today - with days delta to open notes for future or past
```
sup
sup +2
sup -2
```

## Setup
* clone/copy/curl the file into `/usr/local/bin` or anywhere in your path and make it executable


## TODO

* Inject default text into vim-notes for **Yesterday**, **Today**, **Blockers**, may involve adding another template
to xolox's plugin repo.

[vim-notes]: http://github.com/xolox/vim-notes
[sample vimrc]: https://github.com/ceocoder/dotfiles/blob/master/vimrc
