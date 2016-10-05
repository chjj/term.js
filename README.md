# term.js

A full xterm clone written in javascript. Used by [**Cloud 9v2**](https://github.com/exsilium/cloud9).

Maintenance fork to keep compatibility with existing implementation. Backporting crucial fixes from [sourcelair/xterm.js](https://github.com/sourcelair/xterm.js). Project focus is on usability and compatibility - keeping it simple.

* Fix cross platform input problems [sourcelair/xterm.js#60](https://github.com/sourcelair/xterm.js/pull/60);
* Textarea used for DOM event capturing (`compositionstart`, `-update`, `-end`);
* Enhancements made in `evaluateKeyEscapeSequence`;
* Killed the various modes: prefixMode; selectMode; visualMode; searchMode - use tmux/screen instead

# ToDo

- [ ] PuTTY like select to Copy and Right-click to Paste functionality

## License

* Copyright (c) 2013-2016, Sten Feldman (MIT License)
* Copyright (c) 2014-2016, SourceLair, Private Company (www.sourcelair.com) (MIT License)
* Copyright (c) 2012-2013, Christopher Jeffrey (MIT License)
