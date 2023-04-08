`thud`: terminal-based, heads up display
========================================

**`thud`** is a collection of scripts, configs, and apps that can be combined
into a cohesive, terminal-based work environment.

I want to setup an interface so that I can quickly connect with various terminal
utilities, such as `btm`, `pulsemixer`, or some kind of timer app.

* modal - have an interactive/cli/ncurses-style interface, as well as a robust
  set of commandline arguments
* should be useable with dmenu/rofi via command arguments
* customizeable - let the user define their own menus

- can I build this in tmux? like
- build this into `zellij`
- search for a `thud` session
    - if it doesn't exist, create it
    - connect to it
    - `thudmenu` is a script that connects with the `tmux` session
        - it should stay in the 0: terminal. when thudmenu quits, then the tmux
          session is terminated.
        - option *d* - disconnect
        - option *t* - terminate
- utilities
    - volume control
    - pdf opener
    - btm
    - cheatsheets in vim

# Let's start building thud as a collection of components

* pdf opener (extend this to all doc types?)
