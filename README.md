### 🦀  Oxidation 🦀

Oxidation is a list of [Rust](https://www.rust-lang.org/)-based command-line, TUI, and GUI tools. This list started out 
as a way to track oxidized recreations of [coreutils](https://www.gnu.org/software/coreutils/) utilities. It quickly 
grew to include any Rust-based CLI, TUI, and GUI apps and utilities that I happened to run across. Note: while the apps
listed here can be used as core system utilities, most of them are not 100% drop-in replacements. That being said, you 
will find that these Rust-based equivalent tools typically implement **most** of the same functionality found in their 
`coreutils` brethren, offer additional, modern features, and are often faster overall. I'm sure that I missed plenty of  
of awesome oxidized utilities when I first compiled this list. Please feel free to contact me with anything that you feel 
should be added, or issue a pull request and I'll get to it as soon as I can. Thanks!

### 🦀 Core Utilities

Rust-based replacements for `coreutils` system commands. You can easily use all of these tools as replacements for your
current system tools/commands. The easiest way to implement this change is via aliases. Not sure where to start? Take a 
look at the documentation for your particular shell and how it handles aliases. 

- [amber](https://github.com/dalance/amber) - an `awk` and `ag` replacement.
- [bat](https://github.com/sharkdp/bat) - a `cat` replacement.
- [bb](https://github.com/epilys/bb) - Simple process viewer in rust.
- [bottom](https://github.com/ClementTsang/bottom) - Graphical process/system monitor.
- [broot](https://github.com/Canop/broot) - a `tree` replacement.
- [delta](https://github.com/dandavison/delta) - a `diff` replacement.
- [difftastic](https://github.com/Wilfred/difftastic) - a `diff` that understands syntax.
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
- [ytop](https://github.com/cjbassi/ytop) - A system monitor written in Rust.
- [zenith](https://github.com/bvaisvil/zenith) - a `top` and `htop` replacement. 

### 🦀 Email Clients and Utilities

- [himalaya](https://github.com/soywod/himalaya) - CLI email client written in Rust.
- [meli](https://git.meli.delivery/meli/meli) - BSD/Linux terminal email client.

### 🦀 Encryption Utilities

- [cloaker](https://github.com/spieglt/cloaker) - Drag-and-drop, password-based file encryption.
- [gpg-tui](https://github.com/orhun/gpg-tui) - Manage your GnuPG keys with ease! 🔐
- [rage](https://github.com/str4d/rage) - Modern encryption tool (and Rust library). 

### 🦀 File Managers & File Utilities

- [felix](https://github.com/kyoheiu/felix) - TUI file manager with vim-like key mapping.
- [hunter](https://github.com/rabite0/hunter) - The fastest file manager in the galaxy! 
- [joshuto](https://github.com/kamiyaa/joshuto) - Ranger-like terminal file manager.
- [xplr](https://github.com/sayanarijit/xplr) - A hackable, minimal, fast TUI file explorer.

### 🦀 Games & Gaming Utilities

- [bevy](https://bevyengine.org/) - Data-driven game engine built in Rust.
- [gameboy](https://github.com/mohanson/gameboy) - A Rust-based Gameboy emulator.
- [Life Simulation](https://github.com/joelthelion/life_web) - Life simulation written in Rust.
- [nestur](https://github.com/spieglt/nestur) - Rust-based NES emulator.
- [rust-doom](https://github.com/cristicbz/rust-doom) - A Doom Renderer written in Rust. 

### 🦀 Graphics Utilities and Image Viewers

- [viu](https://github.com/atanunq/viu) - Simple terminal image viewer written in Rust. 

### 🦀 Messengers

- [gurk-rs](https://github.com/boxdot/gurk-rs) - Signal Messenger client for terminal.

### 🦀 Networking Utilities

- [bandwhich](https://github.com/imsnif/bandwhich) - Terminal bandwidth utilization tool.
- [dog](https://dns.lookup.dog/) - Command-line DNS client.
- [miniserve](https://github.com/svenstaro/miniserve) - HTTP File server.

### 🦀 Programming Utilities

- [bevy](https://bevyengine.org/) - Simple data-driven game engine built in Rust.
- [delta](https://github.com/dandavison/delta) - A viewer for git and diff output.
- [druid](https://github.com/linebender/druid) - A data-first Rust-native UI design toolkit.
- [git-cliff](https://github.com/orhun/git-cliff) - Changelog Generator.
- [gitui](https://github.com/extrawurst/gitui) - Blazing 💥 fast terminal-ui for git written in Rust. 🦀
- [lpsce](https://github.com/lapce/lapce) - Lightning-fast and Powerful Code Editor written in Rust. 🦀
- [rg3d](https://rg3d.rs/) - A feature-rich and easy-to-use game engine written in the Rust.
- [rocket](https://rocket.rs/) - Premiere Web framework for Rust.
- [rust-playground](https://play.rust-lang.org/) - Experiment with Rust before you install it locally.
- [silicon](https://github.com/Aloxaf/silicon) - Create beautiful images of your source code.
- [terminal-size](https://github.com/sharkdp/terminal-size) - Rust library to getting the size of your terminal.
- [tide](https://docs.rs/tide/0.16.0/tide/) - Web framework for Rust.
- [tokei](https://github.com/XAMPPRocky/tokei) - displays statistics about your code.
- [warp](https://github.com/seanmonstar/warp) - Web framework for Rust.

### 🦀 Shell Utilities

- [atuin](https://github.com/ellie/atuin) - 🐢 Magical shell history.
- [bartb](https://github.com/nikolassv/bartib) - A simple timetracker for the command line.
- [fselect](https://github.com/jhspetersson/fselect) - Find files with SQL-like queries.
- [grex](https://github.com/pemistahl/grex) - Generate regular expressions from user-provided test cases.
- [onefetch](https://github.com/o2sh/onefetch) - A command-line Git information tool written in Rust.
- [pastel](https://github.com/sharkdp/pastel) - CLI tool to generate, convert, and manipulate colors.
- [starship](https://starship.rs/) - The minimal, blazing-fast, and infinitely customizable prompt for any shell.
- [tealdeer](https://github.com/dbrgn/tealdeer) - A very fast implementation of tldr in Rust. 
- [topgrade](https://github.com/r-darwish/topgrade) - Upgrade everything.
- [vivid](https://github.com/sharkdp/vivid) -  A `LS_COLORS` generator. Supports multiple color themes.
- [zoxide](https://github.com/ajeetdsouza/zoxide) - A faster way to navigate your filesystem.

### 🦀 Terminal Emulators

- [alacritty](https://github.com/alacritty/alacritty) - GPU-accelerated terminal emulator.
- [bite](https://github.com/LarsEKrueger/bite) - Bash-integrated terminal emulator.
- [warp](https://www.warp.dev/) - The terminal that supercharges your developer workflow.

### 🦀 Text Editors

- [amp](https://amp.rs/) - A complete Vi/Vim inspired text editor for your terminal.
- [eureka](https://github.com/simeg/eureka) - Tool to input and store your ideas.
- [helix](https://helix-editor.com/) - A post-modern text editor.
- [Kibi](https://github.com/ilai-deutel/kibi) - A text editor in ≤1024 lines of code.
- [kiro-editor](https://github.com/rhysd/kiro-editor) - A UTF-8 console text editor written in Rust.
- [m](https://github.com/jinfagang/m) - Modern, easy to use, fast terminal editor.
- [ox](https://github.com/curlpipe/ox) - Ox is a fast text editor that runs in your terminal.
- [smith](https://github.com/IGI-111/Smith) - A simple text editor written in Rust.
- [xi-editor](https://github.com/xi-editor/xi-editor) - A modern text editor with a backend written in Rust.
- [zee](https://github.com/mcobzarenco/zee) - Modern TUI text editor.

### 🦀 UNIX Shells

- [cicada](https://github.com/mitnk/cicada) - A Bash-like UNIX shell written in Rust.
- [ion](https://gitlab.redox-os.org/redox-os/ion) - A UNIX shell compatible with Redox and Linux.
- [nushell](https://github.com/nushell/nushell) - A cross-platform UNIX shell with a modern feel.

### 🦀 Utilities (General)

- [bandwhich](https://github.com/imsnif/bandwhich) - Terminal bandwidth utilization tool.
- [crowbook](https://github.com/lise-henry/crowbook) - Converts books written in Markdown.
- [espanso](https://espanso.org/) - Text Expander written in Rust.
- [eureka](https://github.com/simeg/eureka) - Enter and store your ideas without leaving the terminal.
- [grex](https://github.com/pemistahl/grex) - Generates regular expressions from user-provided test cases.
- [hexyl](https://github.com/sharkdp/hexyl) - A command-line hex viewer.
- [hyperfine](https://github.com/sharkdp/hyperfine) - A Rust-based command-line benchmarking tool.
- [lscolors](https://github.com/sharkdp/lscolors) - A Rust library and tool to colorize paths using `LS_COLORS`.
- [lychee](https://github.com/lycheeverse/lychee) - Fast, async, resource-friendly link checker.
- [macchina](https://github.com/Macchina-CLI/macchina) - A system information fetcher.
- [mdBook](https://github.com/rust-lang/mdBook) - Like Gitbook but implemented in Rust.
- [mdcat](https://github.com/lunaryorn/mdcat) - `cat` for markdown.
- [rustybox](https://github.com/samuela/rustybox) - A free-range, non-GMO fork of busybox in 100% Rust 🦀
- [tv](https://github.com/alexhallam/tv) - Tidy Viewer is a CSV output formatter.
- [zola](https://www.getzola.org/) - Your one-stop static site engine.

### 🦀 Windows Managers

- [LeftWM](https://github.com/leftwm/leftwm) - A tiling window manager for adventurers. 
- [penrose](https://github.com/sminez/penrose) - A library for writing an X11 tiling window manager.
- [wtftw](https://github.com/Kintaro/wtftw) - Window tiling for the win.

### Author

Created by [Patrick H. Mullins](http://www.pmullins.net). You can find me on  [Twitter](https://twitter.com/phmullins) and 
on [Telegram](https://telegram.org/) as `pmullins`.

### License

Released under the MIT License (MIT) [license](license.md).