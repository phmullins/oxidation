### Oxidation 🦀

Oxidation is a list of [Rust](https://www.rust-lang.org/)-based command-line tools that are oxidized recreations of 
[coreutils](https://www.gnu.org/software/coreutils/) programs. Please note that these are not 100% drop-in replacements. 
However, that being said, the tools listed here do typically implement most of the same functionality found in their 
coreutils brethren, and in many cases offer additional modern features and superior speed. I'm fairly sure I missed 
more than a few awesome Rusty utilities when I compiled this list. Please feel free to contact me with anything that 
you feel should be added, or issue a pull request and I'll get to it as soon as I can. Thanks!

### Oxidized Core Utilities

Rusty replacements for `coreutils` system commands. You can easily use all of these tools by themselves or as replacements 
for current system tools/commands. The easiest way to use them as replacements is by creating aliases.

- [amber](https://github.com/dalance/amber) - an `awk` and `ag` replacement.
- [bat](https://github.com/sharkdp/bat) - a `cat` replacement.
- [bb](https://github.com/epilys/bb) - Simple process viewer in rust.
- [bottom](https://github.com/ClementTsang/bottom) - Graphical process/system monitor.
- [broot](https://github.com/Canop/broot) - a `tree` replacement.
- [delta](https://github.com/dandavison/delta) - a `diff` replacement.
- [diskus](https://github.com/sharkdp/diskus) - an alternative to `du -sh` 
- [dust](https://github.com/bootandy/dust) - another `du` replacement.
- [exa](https://the.exa.website) - a `ls` replacement.
- [fd](https://github.com/sharkdp/fd) - a `find` replacement.
- [gping](https://github.com/orf/gping) - Ping, but with a graph.
- [lsd](https://github.com/Peltoche/lsd) - a `ls` replacement.
- [nat](https://github.com/willdoescode/nat) - another `ls` replacement.
- [procs](https://github.com/dalance/procs) - a `ps` replacement.
- [remacs](https://github.com/remacs/remacs) - an `emacs` replacement. 
- [ripgrep](https://github.com/BurntSushi/ripgrep) - a `grep` replacement.
- [sd](https://github.com/chmln/sd) - a `sed` replacement.
- [skim](https://github.com/lotabout/skim) - a Fuzzy Finder in Rust.
- [tokei](https://github.com/XAMPPRocky/tokei) - a `wc` replacement.
- [ytop](https://github.com/cjbassi/ytop) - A system monitor written in Rust.
- [zenith](https://github.com/bvaisvil/zenith) - a `top` and `htop` replacement. 

### Oxidized Applications.

Some useful Rust-based, cross-platform TUI and GUI programs.

#### Encryption

- [gpg-tui](https://github.com/orhun/gpg-tui) - Manage your GnuPG keys with ease! 🔐

#### Networking

- [bandwhich](https://github.com/imsnif/bandwhich) - Terminal bandwidth utilization tool.
- [dog](https://dns.lookup.dog/) - Command-line DNS client.

#### Shells

- [nushell](https://github.com/nushell/nushell) - A new type of UNIX shell.

#### Shells Utilities

- [fselect](https://github.com/jhspetersson/fselect) - Find files with SQL-like queries.
- [grex](https://github.com/pemistahl/grex) - Generate regular expressions from user-provided test cases.
- [pastel](https://github.com/sharkdp/pastel) - CLI tool to generate, convert, and manipulate colors.
- [tealdeer](https://github.com/dbrgn/tealdeer) - A very fast implementation of tldr in Rust. 
- [topgrade](https://github.com/r-darwish/topgrade) - Upgrade everything.
- [vivid](https://github.com/sharkdp/vivid) -  A `LS_COLORS` generator. Supports multiple color themes.
- [zoxide](https://github.com/ajeetdsouza/zoxide) - A faster way to navigate your filesystem.

#### Terminal Emulators

- [alacritty](https://github.com/alacritty/alacritty) - GPU-accelerated terminal emulator.

#### Text Editors

- [amp](https://amp.rs/) - A Vi/Vim inspired text editor.
- [helix](https://helix-editor.com/) - A post-modern text editor.
- [Kibi](https://github.com/ilai-deutel/kibi) - A text editor in ≤1024 lines of code.
- [kiro-editor](https://github.com/rhysd/kiro-editor) - A UTF-8 console text editor written in Rust.
- [m](https://github.com/jinfagang/m) - Modern, easy to use, fast terminal editor.
- [ox](https://github.com/curlpipe/ox) - Ox is a fast text editor that runs in your terminal.
- [smith](https://github.com/IGI-111/Smith) - A simple text editor written in Rust.
- [xi-editor](https://github.com/xi-editor/xi-editor) - A modern text editor with a backend written in Rust.
- [zee](https://github.com/mcobzarenco/zee) - Modern TUI text editor.

#### Utilities

- [crowbook](https://github.com/lise-henry/crowbook) - Converts books written in Markdown.
- [espanso](https://espanso.org/) - Text Expander written in Rust.
- [eureka](https://github.com/simeg/eureka) - Enter and store your ideas without leaving the terminal.
- [hexyl](https://github.com/sharkdp/hexyl) - A command-line hex viewer.
- [hyperfine](https://github.com/sharkdp/hyperfine) - A Rust-based command-line benchmarking tool.
- [lscolors](https://github.com/sharkdp/lscolors) - A Rust library and tool to colorize paths using `LS_COLORS`.
- [mdBook](https://github.com/rust-lang/mdBook) - Like Gitbook but implemented in Rust.
- [mdcat](https://github.com/lunaryorn/mdcat) - `cat` for markdown.
- [zola](https://www.getzola.org/) - Your one-stop static site engine.

### Author

Created by [Patrick H. Mullins](http://www.pmullins.net). You can find me on  [Twitter](https://twitter.com/phmullins) and 
on [Telegram](https://telegram.org/) as `pmullins`.

### License

Released under the MIT License (MIT) [license](license.md).