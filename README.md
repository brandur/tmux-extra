Tmux Extra
==========

A few extra files useful to get sane Tmux default behavior (or what a person coming from Screen might consider sane at any rate). Changes are described in more detail in my article [Practical Tmux](http://mutelight.org/articles/practical-tmux).

Installation
------------

Included files:

* `.tmux.conf`: Tmux configuration file. Symlink to your home directory like `ln -s /home/brandur/tmux-extra/.tmux.conf /home/brandur/`.

* `tmx`: A Tmux launcher script mostly useful for getting sessions that share the same set of windows, but can move between them independently. Symlink to a directory in your `$PATH` like `ln -s /home/brandur/tmux-extra/tmx /home/brandur/bin/`.

Usage
-----

Launch Tmux via the launcher with `tmx <session name>` where the session name is an arbitrary string representing a session that you might want to reconnect to later (e.g. `tmx mutelight`).

Contact
-------

Send comments and suggestions to **brandur@mutelight.org**.
