VIM PostCSS Sorting
===================

A Vundle-compatiable plugin based on [a gist by eprev][https://gist.github.com/eprev/bf2cee9b211505f60ce826762e3b2a1c]

Setup
-----

1. Install postcss-cli and postcss-sorting

```
% npm install -g postcss-cli postcss-sorting
```

2. Install this plugin (with [Vundle][https://github.com/gmarik/vundle])

```
Plugin 'bkaney/vim-postcss-sorting'
```

3. Map

Add to `.vimrc`:

```
nnoremap <Leader>cs :CSSSorting<CR>
```
