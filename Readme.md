Swap
----------

Keymando plugin that swaps text in input sequences.

Examples
========

Swap Cmd and Alt everywhere:

``` ruby

  swap('Cmd', 'Alt')

```

Restrict to Emacs:

``` ruby

  only /Emacs/ do
    swap('Cmd', 'Alt')
  end

```

Requirements
============

Keymando version 1.0.3


