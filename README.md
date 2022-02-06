Lore tools
==========

A collection of scripts for consuming public-inbox archives
(ie. lore.kernel.org) in (Neo)Mutt.

Dependencies
------------

Depends on [b4][b4].

Commands
--------

### lorefetch

    lorefetch <MESSAGE-ID> <MBOX>

Fetch `<MESSAGE-ID>` and append it to `<MBOX>`.

### loreopen

    loreopen <MBOX>

Open `<MBOX>` with Neomutt, or any Mutt compatible command.

Set `MUTTCMD` to specify Mutt command (default: neomutt).

[b4]: https://pypi.org/project/b4/
