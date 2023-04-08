`thud`: terminal-based, heads up display
========================================

**`thud`** is a collection of scripts, configs, and apps that can be combined
into a cohesive, terminal-based work environment. I will be building this on top
of `zellij`, in order to access certain elements as pop-up windows, terminal
apps, or a `zellij` layout, which provides access to a number of utitilies.

# submodules

**Submodules** are individual elements that can be used on their own, or
integrated as part of `thud`.

* **repertor**: literally "the finder" a script which uses `fzf` to choose a file
  and open it using the specified (or default: `xdg-open` based on *mimetype*)
