Vim BEL
=======

Vim plugin for syntax highlighting of BEL Script.

Installation
------------

**with `vundle`_**

#. Install `vundle`_ using git

.. code-block:: bash

  git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle

#. Add the following snippet to your `~/.vimrc` file

.. code-block:: vim

  " no compatibility with Vi
  set nocompatible                  " no compatibility with Vi
  filetype off                      " required
  set rtp+=~/.vim/bundle/vundle/    " add vundle to runtime path
  call vundle#rc()                  " initialize vundle
  Bundle 'gmarik/vundle'            " required; vundle manages vundle

  Bundle 'OpenBEL/openbel-vim'      " installs BEL syntax highlighter

**manual install**

#. Copy bel.vim from the syntax directory to $HOME/.vim/syntax directory.
#. Copy bel.vim from the ftdetect directory to $HOME/.vim/ftdetect directory.

.. _vundle: https://github.com/gmarik/vundle
