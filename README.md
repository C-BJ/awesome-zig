# Awesome Zig

> 📜Zig Learning & Usage Guide.

[<img src="https://ziglang.org/zig-logo-light.svg" align="right" width="100">](https://ziglang.org)

[Zig](https://ziglang.org/) is a general-purpose programming language and toolchain for maintaining robust, optimal, and reusable software.

**Thanks to all the project authors and others who made this project possible.**

**Note🗒️An project may also be a development tool, application, library or other category, but it will only appear once in this guide.**

**🔥 Will be added in front of applications or libraries with more than 500 Star**

## Table Of Contents

- [Related Web Sites](#related-web-sites)
- [Development Tools](#development-tools)
  - [Editor Plugins](#editor-plugins)
  - [Package Managers](#package-managers)
  - [Other Tools](#other-tools)
- [Applications](#applications)
  - [Blockchain](#blockchain)
  - [Command Line](#command-line)
  - [Compiler & Parser & Interpreter](#compiler--parser--interpreter)
  - [Database](#database)
  - [Embedded](#embedded)
  - [Game and Desktop(GUI) Applications](#game--desktopgui-applications)
  - [Operating Systems & Kernels](#operating-systems--kernels)
  - [Simulator & Virtual Machine & Emulator](#simulator--virtual-machine--emulator)
  - [Web](#web)
  - [Other Applications](#other-applications)
- [Libraries](#libraries)
  - [Database Operation](#database-operation)
  - [Encryption & Encoding & Decoding](#encryption--encoding--decoding)
  - [Game Dev & GUI Dev & Media Framework](#game-dev--gui-dev--media-framework)
  - [Images](#images)
  - [Language Bindings](#language-bindings)
  - [Terminal & Low-Level Libraries & System API](#terminal--low-level-libraries--system-api)
  - [Universal](#universal)
    - [Algorithms & Data Structures](#algorithms--data-structures)
    - [Memory Management](#memory-management)
    - [Other Universal Libraries](#other-universal-libraries)
  - [Web](#web)
  - [Other Libraries](#other-libraries)
- [Resources](#resources)
  - [Community](https://github.com/ziglang/zig/wiki/Community)
  - [Introduction Or News](#introduction-or-News)
  - [Learning](#learning)
- [Contributing](https://github.com/C-BJ/awesome-zig/blob/main/CONTRIBUTING.md)

## Related Web Sites

- [Zig Official Website](https://ziglang.org/)
- [Zig Github Page](https://github.com/ziglang)
- [Zig News](https://zig.news/)
- [Zig Community List](https://github.com/ziglang/zig/wiki/Community)
- [Learning Zig](https://ziglearn.org/)
- [Zig Monthly](https://zigmonthly.org/)
- [Zig Showtime](https://zig.show/)
- [Zig Playground](https://zig-play.dev/)
- [Andrew Kelley's  (founder of zig) Personal Blog](https://andrewkelley.me/)
- [Loris Cro's Personal Blog](https://kristoff.it/)

## Development Tools

- ### Editor Plugins

  - <span style="float:right;">![Star](https://img.shields.io/github/stars/ice1000/intellij-zig?color=orange)</span>
  [intellij-zig🗒️The IntelliJ IDEA plugin for the Zig programming language](https://github.com/ice1000/intellij-zig) </p>
  - <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglang/kde-syntax-highlighting?color=orange)</span>
  [kde-syntax-highlighting🗒️kde xml file for zig syntax highlighting](https://github.com/ziglang/kde-syntax-highlighting) </p> 
  - [sublime-zig-language🗒️Zig language support for Sublime Text](https://github.com/ziglang/sublime-zig-language) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglang/sublime-zig-language?color=orange)</span></p>
  - [vscode-zig🗒️Zig language support for VSCode](https://github.com/ziglang/vscode-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglang/vscode-zig?color=orange)</span></p>
  - [zig-mode🗒️Zig mode for Emacs](https://github.com/ziglang/zig-mode) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglang/zig-mode?color=orange)</span></p>
  - [zig.vim🗒️Vim configuration for Zig](https://github.com/ziglang/zig.vim) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglang/zig.vim?color=orange)</span></p>

- ### Package Managers

  - [asdf-zig🗒️zig plugin for asdf version manager](https://github.com/cheetah/asdf-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/cheetah/asdf-zig?color=orange)</span></p>
  - 🔥[gyro🗒️A Zig package manager with an index, build runner, and build dependencies](https://github.com/mattnite/gyro) <span style="float:right;">![Star](https://img.shields.io/github/stars/mattnite/gyro?color=orange)</span></p>
  - [zpm🗒️Package dependency generator; WIP](https://github.com/zigtools/zpm) <span style="float:right;">![Star](https://img.shields.io/github/stars/zigtools/zpm?color=orange)</span></p>
  - [Zig-AoC-Template🗒️A template for Advent of Code participants using Zig](https://github.com/SpexGuy/Zig-AoC-Template) <span style="float:right;">![Star](https://img.shields.io/github/stars/SpexGuy/Zig-AoC-Template?color=orange)</span></p>
  - [zigmod🗒️📦 A package manager for the Zig programming language](https://github.com/nektro/zigmod) <span style="float:right;">![Star](https://img.shields.io/github/stars/nektro/zigmod?color=orange)</span></p>

- ### Other Tools

  - [aquila🗒️📫 A federated package index and CI system for Zig projects](https://github.com/nektro/aquila) <span style="float:right;">![Star](https://img.shields.io/github/stars/nektro/aquila?color=orange)</span></p>
  - [futureproof🗒️A live editor for fragment shaders, powered by Neovim, WebGPU, and Zig!](https://github.com/mkeeter/futureproof) <span style="float:right;">![Star](https://img.shields.io/github/stars/mkeeter/futureproof?color=orange)</span></p>
  - [jaz🗒️A JVM implementation in Zig!](https://github.com/zig-java/jaz) <span style="float:right;">![Star](https://img.shields.io/github/stars/zig-java/jaz?color=orange)</span></p>
  - [marble🗒️A metamorphic testing library for Zig](https://github.com/cryptocode/marble) <span style="float:right;">![Star](https://img.shields.io/github/stars/cryptocode/marble?color=orange)</span></p>
  - [repository🗒️A community-maintained repository of zig packages](https://github.com/ziglibs/repository) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/repository?color=orange)</span></p>
  - [setup-zig🗒️use a @ziglang compiler in your github actions workflows](https://github.com/goto-bus-stop/setup-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/goto-bus-stop/setup-zig?color=orange)</span></p>
  - [svd2zig🗒️Convert System View Description (svd) files to Zig headers for baremetal development](https://github.com/justinbalexander/svd2zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/justinbalexander/svd2zig?color=orange)</span></p>
  - [tree-sitter-zig🗒️Tree Sitter for Zig](https://github.com/maxxnino/tree-sitter-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/maxxnino/tree-sitter-zig?color=orange)</span></p>
  - 🔥[xmake🗒️A cross-platform build utility based on Lua](https://github.com/xmake-io/xmake) <span style="float:right;">![Star](https://img.shields.io/github/stars/xmake-io/xmake?color=orange)</span></p>
  - [zigbo🗒️Zig build system graph output step](https://github.com/haze/zigbo) <span style="float:right;">![Star](https://img.shields.io/github/stars/haze/zigbo?color=orange)</span></p>
  - [zig-deploy🗒️Deploy your iOS apps written with Zig!](https://github.com/kubkon/zig-deploy) <span style="float:right;">![Star](https://img.shields.io/github/stars/kubkon/zig-deploy?color=orange)</span></p>
  - [zig-diff🗒️Text diffing in zig](https://github.com/tomhoule/zig-diff) <span style="float:right;">![Star](https://img.shields.io/github/stars/tomhoule/zig-diff?color=orange)</span></p>
  - [zig-doctest🗒️A tool for testing snippets of code, useful for websites and books that talk about Zig](https://github.com/kristoff-it/zig-doctest) <span style="float:right;">![Star](https://img.shields.io/github/stars/kristoff-it/zig-doctest?color=orange)</span></p>
  - [zigfmt-web🗒️zig fmt on the web](https://github.com/shritesh/zigfmt-web) <span style="float:right;">![Star](https://img.shields.io/github/stars/shritesh/zigfmt-web?color=orange)</span></p>
  - [zig-header-gen🗒️Automatically generate headers/bindings for other languages from Zig code](https://github.com/suirad/zig-header-gen) <span style="float:right;">![Star](https://img.shields.io/github/stars/suirad/zig-header-gen?color=orange)</span></p>
  - [zig-pypi🗒️The Zig programming language, packaged for PyPI](https://github.com/ziglang/zig-pypi) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglang/zig-pypi?color=orange)</span></p>
  - [zig-snapshots🗒️Preview Zig's incremental linker state in interactive HTML](https://github.com/kubkon/zig-snapshots) <span style="float:right;">![Star](https://img.shields.io/github/stars/kubkon/zig-snapshots?color=orange)</span></p>
  - [zigup🗒️Download and manage zig compilers](https://github.com/marler8997/zigup) <span style="float:right;">![Star](https://img.shields.io/github/stars/marler8997/zigup?color=orange)</span></p>
  - [zld🗒️Zig's lld drop-in replacement](https://github.com/kubkon/zld) <span style="float:right;">![Star](https://img.shields.io/github/stars/kubkon/zld?color=orange)</span></p>
  - 🔥[zls🗒️Zig LSP implementation + Zig Language Server](https://github.com/zigtools/zls) <span style="float:right;">![Star](https://img.shields.io/github/stars/zigtools/zls?color=orange)</span></p>
  

## Applications

- ### Blockchain

  - [rheia🗒️A blockchain written in Zig](https://github.com/lithdew/rheia) <span style="float:right;">![Star](https://img.shields.io/github/stars/lithdew/rheia?color=orange)</span></p>

- ### Command Line

  - [calctax🗒️Simple tax calculator for employees in Poland after Nowy Lad changes in 2022](https://github.com/kubkon/calctax) <span style="float:right;">![Star](https://img.shields.io/github/stars/kubkon/calctax?color=orange)</span></p>
  - [crisp🗒️A Minimal Lispy Calculator](https://github.com/rvcas/crisp) <span style="float:right;">![Star](https://img.shields.io/github/stars/rvcas/crisp?color=orange)</span></p>
  - [gi🗒️Simple program that generates .gitignore files based on the templates from https://github.com/toptal/gitignore](https://github.com/dmbfm/gi) <span style="float:right;">![Star](https://img.shields.io/github/stars/dmbfm/gi?color=orange)</span></p>
  - [outfieldr🗒️A TLDR client in Zig](https://gitlab.com/ve-nt/outfieldr) <span style="float:right;">
  - [sapt🗒️Simple file-oriented API-testing tool](https://github.com/michaelo/sapt) <span style="float:right;">![Star](https://img.shields.io/github/stars/michaelo/sapt?color=orange)</span></p>
  - [pbui-main🗒️The main repository for the PBUI project](https://github.com/pbui-project/pbui-main) <span style="float:right;">![Star](https://img.shields.io/github/stars/pbui-project/pbui-main?color=orange)</span></p>
  - [redis-rope🗒️A fast native data type for manipulating large strings in Redis](https://github.com/ekzhang/redis-rope) <span style="float:right;">![Star](https://img.shields.io/github/stars/ekzhang/redis-rope?color=orange)</span></p>
  - [sudokuinzig🗒️Sudoku solver in zig](https://github.com/user00e00/sudokuinzig) <span style="float:right;">![Star](https://img.shields.io/github/stars/user00e00/sudokuinzig?color=orange)</span></p>
  - [zcoff🗒️Like dumpbin.exe but cross-platform](https://github.com/kubkon/zcoff) <span style="float:right;">![Star](https://img.shields.io/github/stars/kubkon/zcoff?color=orange)</span></p>
  - [zig-inquirer🗒️A collection of utilities for prompting information from the user on the CLI](https://github.com/nektro/zig-inquirer) <span style="float:right;">![Star](https://img.shields.io/github/stars/nektro/zig-inquirer?color=orange)</span></p>
  - [zigish🗒️A toy Unix shell written in Zig](https://github.com/ratfactor/zigish) <span style="float:right;">![Star](https://img.shields.io/github/stars/ratfactor/zigish?color=orange)</span></p>

- ### Compiler & Parser & Interpreter

  - [arocc🗒️A C compiler written in Zig](https://github.com/Vexu/arocc) <span style="float:right;">![Star](https://img.shields.io/github/stars/Vexu/arocc?color=orange)</span></p>
  - [base32🗒️base32 encoding/decoding for ziglang](https://github.com/gernest/base32) <span style="float:right;">![Star](https://img.shields.io/github/stars/gernest/base32?color=orange)</span></p>
  - [bog🗒️Small, strongly typed, embeddable language](https://github.com/Vexu/bog) <span style="float:right;">![Star](https://img.shields.io/github/stars/Vexu/bog?color=orange)</span></p>
  - [brainfuck-zig🗒️Brainfuck interpreter written in zig](https://github.com/dantecatalfamo/brainfuck-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/dantecatalfamo/brainfuck-zig?color=orange)</span></p>
  - 🔥[buzz🗒️buzz, A small/lightweight statically typed scripting language (in development)](https://github.com/buzz-language/buzz) <span style="float:right;">![Star](https://img.shields.io/github/stars/buzz-language/buzz?color=orange)</span></p>
  - [cmdlinezig🗒️A simple command line parser](https://github.com/travisstaloch/cmdlinezig) <span style="float:right;">![Star](https://img.shields.io/github/stars/travisstaloch/cmdlinezig?color=orange)</span></p>
  - 🔥[cyber🗒️Fast and concurrent scripting](https://github.com/fubark/cyber) <span style="float:right;">![Star](https://img.shields.io/github/stars/fubark/cyber?color=orange)</span></p>
  - [hzzp🗒️A I/O agnostic HTTP/1.1 parser and encoder for Zig](https://github.com/truemedian/hzzp) <span style="float:right;">![Star](https://img.shields.io/github/stars/truemedian/hzzp?color=orange)</span></p>
  - [ini🗒️A teeny tiny ini parser](https://github.com/ziglibs/ini) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/ini?color=orange)</span></p>
  - [jng2-decrypt🗒️Small program for decrypting the Jets'n'Guns 2 game files](https://github.com/Hejsil/jng2-decrypt) <span style="float:right;">![Star](https://img.shields.io/github/stars/Hejsil/jng2-decrypt?color=orange)</span></p>
  - [koino🗒️CommonMark + GFM compatible Markdown parser and renderer](https://github.com/kivikakk/koino) <span style="float:right;">![Star](https://img.shields.io/github/stars/kivikakk/koino?color=orange)</span></p>
  - [libpcre.zig🗒️Zig bindings to libpcre](https://github.com/kivikakk/libpcre.zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/kivikakk/libpcre.zig?color=orange)</span></p>
  - [liz🗒️Lisp-flavored general-purpose programming language (based on Zig)](https://github.com/dundalek/liz) <span style="float:right;">![Star](https://img.shields.io/github/stars/dundalek/liz?color=orange)</span></p>
  - [LoLa🗒️LoLa is a small programming language meant to be embedded into games](https://github.com/MasterQ32/LoLa) <span style="float:right;">![Star](https://img.shields.io/github/stars/MasterQ32/LoLa?color=orange)</span></p>
  - [luf🗒️Statically typed, embeddable, scripting language written in Zig](https://github.com/Luukdegram/luf) <span style="float:right;">![Star](https://img.shields.io/github/stars/Luukdegram/luf?color=orange)</span></p>
  - [protozig🗒️The protozig(uana), or protocol buffers implementation in Zig](https://github.com/kubkon/protozig) <span style="float:right;">![Star](https://img.shields.io/github/stars/kubkon/protozig?color=orange)</span></p>
  - [rem🗒️An HTML parsing library, written in Zig](https://github.com/chwayne/rem) <span style="float:right;">![Star](https://img.shields.io/github/stars/chwayne/rem?color=orange)</span></p>
  - [tres🗒️ValueTree-based JSON parser](https://github.com/ziglibs/tres) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/tres?color=orange)</span></p>
  - [zacho🗒️Zig's Mach-O parser](https://github.com/kubkon/zacho) <span style="float:right;">![Star](https://img.shields.io/github/stars/kubkon/zacho?color=orange)</span></p>
  - [zcheme🗒️WIP implementation of R7RS Scheme](https://hg.sr.ht/~hutzdog/Zcheme)
  - [zelf🗒️Zig's ELF parser utility](https://github.com/kubkon/zelf) <span style="float:right;">![Star](https://img.shields.io/github/stars/kubkon/zelf?color=orange)</span></p>
  - [zexpr🗒️Zig S-expression library](https://hg.sr.ht/~hutzdog/Zcheme/browse/zexpr?rev=tip)
  - [zig-cli🗒️A simple package for building command line apps in Zig](https://github.com/sam701/zig-cli) <span style="float:right;">![Star](https://img.shields.io/github/stars/sam701/zig-cli?color=orange)</span></p>
  - [zig-dwarfdump🗒️dwarfdump utility but in Zig](https://github.com/kubkon/zig-dwarfdump) <span style="float:right;">![Star](https://img.shields.io/github/stars/kubkon/zig-dwarfdump?color=orange)</span></p>
  - [zigmkv🗒️wip Matroska/webm (mkv) parser in Zig](https://github.com/vi/zigmkv) <span style="float:right;">![Star](https://img.shields.io/github/stars/vi/zigmkv?color=orange)</span></p>
  - [zig-parse-args🗒️Parse command line arguments](https://github.com/winksaville/zig-parse-args) <span style="float:right;">![Star](https://img.shields.io/github/stars/winksaville/zig-parse-args?color=orange)</span></p>
  - [zig-parse-number🗒️Implement ParseNumber which can parse any TypeId.Int or TypeId.Float](https://github.com/winksaville/zig-parse-number) <span style="float:right;">![Star](https://img.shields.io/github/stars/winksaville/zig-parse-number?color=orange)</span></p>
  - [zig-regex🗒️A regex implementation for the zig programming language](https://github.com/tiehuis/zig-regex) <span style="float:right;">![Star](https://img.shields.io/github/stars/tiehuis/zig-regex?color=orange)</span></p>
  - [zig-ryu🗒️Zig port of https://github.com/ulfjack/ryu](https://github.com/tiehuis/zig-ryu) <span style="float:right;">![Star](https://img.shields.io/github/stars/tiehuis/zig-ryu?color=orange)</span></p>
  - [zig-toml🗒️A TOML parser written in Zig](https://github.com/aeronavery/zig-toml) <span style="float:right;">![Star](https://img.shields.io/github/stars/aeronavery/zig-toml?color=orange)</span></p>
  - [zig-toml🗒️An LL TOML parser that parses into Zig structs](https://github.com/sam701/zig-toml) <span style="float:right;">![Star](https://img.shields.io/github/stars/sam701/zig-toml?color=orange)</span></p>
  - [zig-json5🗒️A JSON5 Parser/Stringifier written in Zig](https://github.com/Himujjal/zig-json5) <span style="float:right;">![Star](https://img.shields.io/github/stars/Himujjal/zig-json5?color=orange)</span></p>
  - [ziguid🗒️GUID parsing/stringifying with zig](https://github.com/goto-bus-stop/ziguid) <span style="float:right;">![Star](https://img.shields.io/github/stars/goto-bus-stop/ziguid?color=orange)</span></p>
  - [zig-yaml🗒️YAML parser for Zig](https://github.com/kubkon/zig-yaml) <span style="float:right;">![Star](https://img.shields.io/github/stars/kubkon/zig-yaml?color=orange)</span></p>
  - [ztoml🗒️TOMLv1.0.0 parser](https://codeberg.org/naneros/ztoml.git)
  - [zua🗒️An implementation of Lua 5.1 in Zig, for learning purposes](https://github.com/squeek502/zua) <span style="float:right;">![Star](https://img.shields.io/github/stars/squeek502/zua?color=orange)</span></p>
  - [zuri🗒️URI parser for Zig](https://github.com/Vexu/zuri) <span style="float:right;">![Star](https://img.shields.io/github/stars/Vexu/zuri?color=orange)</span></p>

- ### Database
  
  - [awtfdb🗒️the Anime Woman's Tagged File Data Base](https://github.com/lun-4/awtfdb) <span style="float:right;">![Star](https://img.shields.io/github/stars/lun-4/awtfdb?color=orange)</span></p>
  - [redis-cuckoofilter🗒️Hashing-function agnostic Cuckoo filters for Redis](https://github.com/kristoff-it/redis-cuckoofilter) <span style="float:right;">![Star](https://img.shields.io/github/stars/kristoff-it/redis-cuckoofilter?color=orange)</span></p>
  - [sqlite-zig SQLite bindings](https://github.com/leroycep/sqlite-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/leroycep/sqlite-zig?color=orange)</span></p>
  - 🔥[tigerbeetle🗒️A distributed financial accounting database designed for mission critical safety and performance to power the future of financial services](https://github.com/coilhq/tigerbeetle) <span style="float:right;">![Star](https://img.shields.io/github/stars/coilhq/tigerbeetle?color=orange)</span></p>
  - [zek](https://github.com/drcode/zek) <span style="float:right;">![Star](https://img.shields.io/github/stars/drcode/zek?color=orange)</span></p>
  - [zig-cassandra🗒️Cassandra CQL client](https://github.com/vrischmann/zig-cassandra) <span style="float:right;">![Star](https://img.shields.io/github/stars/vrischmann/zig-cassandra?color=orange)</span></p>
  - [zig-okredis🗒️Zero-allocation Client for Redis 6+](https://github.com/kristoff-it/zig-okredis) <span style="float:right;">![Star](https://img.shields.io/github/stars/kristoff-it/zig-okredis?color=orange)</span></p>
  - [zig-sqlite🗒️zig-sqlite is a small wrapper around sqlite's C API, making it easier to use with Zig](https://github.com/vrischmann/zig-sqlite) <span style="float:right;">![Star](https://img.shields.io/github/stars/vrischmann/zig-sqlite?color=orange)</span></p>

- ### Embedded
  
  - [embedded_zig🗒️minimal Zig embedded ARM example (STM32F103 blue pill)](https://github.com/tralamazza/embedded_zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/tralamazza/embedded_zig?color=orange)</span></p>
  - [uefi-paint🗒️UEFI-bootable touch paint app](https://github.com/nrdmn/uefi-paint) <span style="float:right;">![Star](https://img.shields.io/github/stars/nrdmn/uefi-paint?color=orange)</span></p>
  - [zig-armv8m-test🗒️Minimal Zig-based app for Armv8-M + TrustZone](https://github.com/yvt/zig-armv8m-test) <span style="float:right;">![Star](https://img.shields.io/github/stars/yvt/zig-armv8m-test?color=orange)</span></p>
  - [zig-bare-metal-microbit🗒️Bare metal microbit program written in zig](https://github.com/markfirmware/zig-bare-metal-microbit) <span style="float:right;">![Star](https://img.shields.io/github/stars/markfirmware/zig-bare-metal-microbit?color=orange)</span></p>
  - [Ziguana-Game-System🗒️A retro-style gaming console running on bare x86 metal written in Zig](https://github.com/MasterQ32/Ziguana-Game-System) <span style="float:right;">![Star](https://img.shields.io/github/stars/MasterQ32/Ziguana-Game-System?color=orange)</span></p>
  
- ### Game & Desktop(GUI) Applications

  - [blink🗒️A game about building logic with lasers](https://github.com/Stenodyon/blink) <span style="float:right;">![Star](https://img.shields.io/github/stars/Stenodyon/blink?color=orange)</span></p>
  - [bork🗒️A TUI chat client tailored for livecoding on Twitch](https://github.com/kristoff-it/bork) <span style="float:right;">![Star](https://img.shields.io/github/stars/kristoff-it/bork?color=orange)</span></p>
  - [clashos🗒️multiplayer arcade game for bare metal Raspberry Pi 3 B+](https://github.com/andrewrk/clashos) <span style="float:right;">![Star](https://img.shields.io/github/stars/andrewrk/clashos?color=orange)</span></p>
  - [curses-minesweeper🗒️Minesweeper game written in curses with zig](https://github.com/Akuli/curses-minesweeper) <span style="float:right;">![Star](https://img.shields.io/github/stars/Akuli/curses-minesweeper?color=orange)</span></p>
  - [gamejam-zig-vulkan🗒️A game written in ~1 day using zig and vulkan](https://github.com/Avokadoen/gamejam-zig-vulkan) <span style="float:right;">![Star](https://img.shields.io/github/stars/Avokadoen/gamejam-zig-vulkan?color=orange)</span></p>
  - [hello-triangle🗒️Opens a window and draws a nice little triangle](https://github.com/zig-community/hello-triangle) <span style="float:right;">![Star](https://img.shields.io/github/stars/zig-community/hello-triangle?color=orange)</span></p>
  - [legend-of-swarkland🗒️Hack-n-slash roguelike inspired by NetHack](https://github.com/thejoshwolfe/legend-of-swarkland) <span style="float:right;">![Star](https://img.shields.io/github/stars/thejoshwolfe/legend-of-swarkland?color=orange)</span></p>
  - [kisa🗒️Text editor of the new world](https://github.com/greenfork/kisa) <span style="float:right;">![Star](https://img.shields.io/github/stars/greenfork/kisa?color=orange)</span></p>
  - [minesweeper-zig🗒️Simple Minesweeper clone written in Zig, using SDL for graphics](https://github.com/Ryp/minesweeper-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/Ryp/minesweeper-zig?color=orange)</span></p>
  - [MiniPixel🗒️Tiny pixel art editor](https://github.com/fabioarnold/MiniPixel) <span style="float:right;">![Star](https://img.shields.io/github/stars/fabioarnold/MiniPixel?color=orange)</span></p>
  - [mogwai🗒️Graphic utility used to manipulate objects in 3D for scene editing (commonly called Gizmo)](https://github.com/kooparse/mogwai) <span style="float:right;">![Star](https://img.shields.io/github/stars/kooparse/mogwai?color=orange)</span></p>
  - [OpenCSE🗒️Free implementation of the Can't Stop Express dice game](https://github.com/dantecatalfamo/OpenCSE) <span style="float:right;">![Star](https://img.shields.io/github/stars/dantecatalfamo/OpenCSE?color=orange)</span></p>
  - [pacman.zig🗒️Simple Pacman clone written in Zig](https://github.com/floooh/pacman.zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/floooh/pacman.zig?color=orange)</span></p>
  - [pixelcode](https://github.com/pfgithub/pixelcode) <span style="float:right;">![Star](https://img.shields.io/github/stars/pfgithub/pixelcode?color=orange)</span></p>
  - [rayray🗒️A tiny GPU raytracer, using Zig and WebGPU](https://github.com/mkeeter/rayray) <span style="float:right;">![Star](https://img.shields.io/github/stars/mkeeter/rayray?color=orange)</span></p>
  - [snake-zig🗒️A simple snake game written in the Zig programming language using OpenGL 2](https://github.com/fabioarnold/snake-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/fabioarnold/snake-zig?color=orange)</span></p>
  - [SoftRenderLib🗒️A collection of software rendering routines](https://github.com/MasterQ32/SoftRenderLib) <span style="float:right;">![Star](https://img.shields.io/github/stars/MasterQ32/SoftRenderLib?color=orange)</span></p>
  - [tetris🗒️A simple tetris clone written in zig programming language](https://github.com/andrewrk/tetris) <span style="float:right;">![Star](https://img.shields.io/github/stars/andrewrk/tetris?color=orange)</span></p>
  - [underburrow🗒️A small platformer example for Slingworks & Zig](https://github.com/JonSnowbd/underburrow) <span style="float:right;">![Star](https://img.shields.io/github/stars/JonSnowbd/underburrow?color=orange)</span></p>
  - [weekend-raytracer-zig🗒️A Zig implementation of the "Ray Tracing in One Weekend" book](https://github.com/Nelarius/weekend-raytracer-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/Nelarius/weekend-raytracer-zig?color=orange)</span></p>
  - [wired](https://github.com/desttinghim/wired) <span style="float:right;">![Star](https://img.shields.io/github/stars/desttinghim/wired?color=orange)</span></p>
  - [zalgebra🗒️Linear algebra library for games and real-time graphics](https://github.com/kooparse/zalgebra) <span style="float:right;">![Star](https://img.shields.io/github/stars/kooparse/zalgebra?color=orange)</span></p>
  - [zig-gorillas🗒️A clone of the classic QBasic Gorillas written in the Zig programming language](https://github.com/fabioarnold/zig-gorillas) <span style="float:right;">![Star](https://img.shields.io/github/stars/fabioarnold/zig-gorillas?color=orange)</span></p>
  - [Zig-Oculus-Quest🗒️An example application for the Oculus Quest, written in Zig](https://github.com/SpexGuy/Zig-Oculus-Quest) <span style="float:right;">![Star](https://img.shields.io/github/stars/SpexGuy/Zig-Oculus-Quest?color=orange)</span></p>
  - [ZigPaint🗒️A simple paint application written in Zig. Used to create an OpenGL loader/wrapper and a minimal UI system](https://github.com/MasterQ32/ZigPaint) <span style="float:right;">![Star](https://img.shields.io/github/stars/MasterQ32/ZigPaint?color=orange)</span></p>
  - [zig-raylib-experiments🗒️Some classic game implementations in Zig using raylib](https://github.com/BitPuffin/zig-raylib-experiments) <span style="float:right;">![Star](https://img.shields.io/github/stars/BitPuffin/zig-raylib-experiments?color=orange)</span></p>
  - [zig-raytrace🗒️simple raytracer in zig](https://github.com/tiehuis/zig-raytrace) <span style="float:right;">![Star](https://img.shields.io/github/stars/tiehuis/zig-raytrace?color=orange)</span></p>
  - [Zig-Showdown🗒️A community effort to create a small multiplayer 3D shooter game in pure zig](https://github.com/zig-community/Zig-Showdown) <span style="float:right;">![Star](https://img.shields.io/github/stars/zig-community/Zig-Showdown?color=orange)</span></p>
  - [zig-vulkan-triangle🗒️simple triangle displayed using vulkan, glfw, and zig](https://github.com/andrewrk/zig-vulkan-triangle) <span style="float:right;">![Star](https://img.shields.io/github/stars/andrewrk/zig-vulkan-triangle?color=orange)</span></p>
  - [zig-wasm-snake🗒️Classic snake game written in Zig, compiled to WASM](https://github.com/holobeat/zig-wasm-snake) <span style="float:right;">![Star](https://img.shields.io/github/stars/holobeat/zig-wasm-snake?color=orange)</span></p>
  - [zootdeck🗒️Fediverse GTK Desktop Reader](https://github.com/donpdonp/zootdeck) <span style="float:right;">![Star](https://img.shields.io/github/stars/donpdonp/zootdeck?color=orange)</span></p>
  - [zstack🗒️Line-race tetris mode in Zig](https://github.com/tiehuis/zstack) <span style="float:right;">![Star](https://img.shields.io/github/stars/tiehuis/zstack?color=orange)</span></p>

- ### Operating Systems & Kernels

  - [daintree🗒️ARMv8-A/RISC-V kernel (with UEFI bootloader)](https://github.com/kivikakk/daintree) <span style="float:right;">![Star](https://img.shields.io/github/stars/kivikakk/daintree?color=orange)</span></p>
  - [georgios🗒️Hobby Operating System](https://github.com/iguessthislldo/georgios) <span style="float:right;">![Star](https://img.shields.io/github/stars/iguessthislldo/georgios?color=orange)</span></p>
  - [HellOS🗒️"hello world" x86 kernel example](https://github.com/andrewrk/HellOS) <span style="float:right;">![Star](https://img.shields.io/github/stars/andrewrk/HellOS?color=orange)</span></p>
  - [Hidamari🗒️Modern operating system aimed at running WebAssembly code](https://github.com/HidamariProject/Hidamari) <span style="float:right;">![Star](https://img.shields.io/github/stars/HidamariProject/Hidamari?color=orange)</span></p>
  - [kernel-zig🗒️hobby x86 kernel zig](https://github.com/jzck/kernel-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/jzck/kernel-zig?color=orange)</span></p>
  - [Lukarnel🗒️A microkernel in zig with rust microservices](https://github.com/DorianXGH/Lukarnel) <span style="float:right;">![Star](https://img.shields.io/github/stars/DorianXGH/Lukarnel?color=orange)</span></p>
  - [microzig🗒️Unified abstraction layer and HAL for several microcontrollers](https://github.com/ZigEmbeddedGroup/microzig) <span style="float:right;">![Star](https://img.shields.io/github/stars/ZigEmbeddedGroup/microzig?color=orange)</span></p>
  - [pluto🗒️An x86 kernel written in Zig](https://github.com/ZystemOS/pluto) <span style="float:right;">![Star](https://img.shields.io/github/stars/ZystemOS/pluto?color=orange)</span></p>
  - [tizr80🗒️TiZr80, a TI-84+ CE/TI-83 Premium CE calculator emulator core](https://github.com/jacobly0/tizr80) <span style="float:right;">![Star](https://img.shields.io/github/stars/jacobly0/tizr80?color=orange)</span></p>
  - [trOS🗒️tiny aarch64 baremetal OS thingy](https://github.com/sjdh02/trOS) <span style="float:right;">![Star](https://img.shields.io/github/stars/sjdh02/trOS?color=orange)</span></p>
  - [uefi-bootstrap🗒️experiments with bootstrapping a kernel with UEFI](https://github.com/stakach/uefi-bootstrap) <span style="float:right;">![Star](https://img.shields.io/github/stars/stakach/uefi-bootstrap?color=orange)</span></p>
  - [uefi-examples🗒️UEFI examples in Zig](https://github.com/nrdmn/uefi-examples) <span style="float:right;">![Star](https://img.shields.io/github/stars/nrdmn/uefi-examples?color=orange)</span></p>
  - [ZBZZ.OS🗒️An operating system built with RISCV and Zig](https://github.com/ZeeBoppityZagZiggity/ZBZZ.OS) <span style="float:right;">![Star](https://img.shields.io/github/stars/ZeeBoppityZagZiggity/ZBZZ.OS?color=orange)</span></p>
  - [zen🗒️Experimental operating system written in Zig](https://github.com/AndreaOrru/zen) <span style="float:right;">![Star](https://img.shields.io/github/stars/AndreaOrru/zen?color=orange)</span></p>
  - [zig-bare-metal-raspberry-pi🗒️Bare metal raspberry pi program written in zig](https://github.com/markfirmware/zig-bare-metal-raspberry-pi) <span style="float:right;">![Star](https://img.shields.io/github/stars/markfirmware/zig-bare-metal-raspberry-pi?color=orange)</span></p>
  - [zig-x86_64🗒️Support for x86_64 specific instructions (e.g. TLB flush), registers (e.g. control registers), and structures (e.g. page tables)](https://github.com/leecannon/zig-x86_64) <span style="float:right;">![Star](https://img.shields.io/github/stars/leecannon/zig-x86_64?color=orange)</span></p>

- ### Simulator & Virtual Machine & Emulator

  - [chip8-zig🗒️A CHIP-8 emulator written in Zig](https://github.com/GrooveStomp/chip8-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/GrooveStomp/chip8-zig?color=orange)</span></p>
  - [ChipZ🗒️A simple Chip8 emulator (executable and library) written in Zig](https://github.com/Arwalk/ChipZ) <span style="float:right;">![Star](https://img.shields.io/github/stars/Arwalk/ChipZ?color=orange)</span></p>
  - [fundude🗒️Gameboy emulator:Zig -> wasm](https://github.com/fengb/fundude) <span style="float:right;">![Star](https://img.shields.io/github/stars/fengb/fundude?color=orange)</span></p>
  - [kc85.zig🗒️A KC85 emulator written in Zig](https://github.com/floooh/kc85.zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/floooh/kc85.zig?color=orange)</span></p>
  - [riscv-zig🗒️A RISC-V emulator written in Zig](https://github.com/Ronsor/riscv-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/Ronsor/riscv-zig?color=orange)</span></p>
  - [zlox🗒️lox virtual machine implementation in zig!](https://github.com/I-mikan-I/zlox) <span style="float:right;">![Star](https://img.shields.io/github/stars/I-mikan-I/zlox?color=orange)</span></p>
  
- ### Web

  - [astrolabe🗒️backend for https://astrolabe.pm](https://github.com/mattnite/astrolabe) <span style="float:right;">![Star](https://img.shields.io/github/stars/mattnite/astrolabe?color=orange)</span></p>
  - [hello🗒️Multi-threaded cross-platform HTTP/1.1 web server example in Zig](https://github.com/lithdew/hello) <span style="float:right;">![Star](https://img.shields.io/github/stars/lithdew/hello?color=orange)</span></p>
  - [lua-in-the-browser🗒️using zig to build lua for webassembly](https://github.com/andrewrk/lua-in-the-browser) <span style="float:right;">![Star](https://img.shields.io/github/stars/andrewrk/lua-in-the-browser?color=orange)</span></p>
  - [zelda🗒️A simple HTTP client library for Zig](https://github.com/haze/zelda) <span style="float:right;">![Star](https://img.shields.io/github/stars/haze/zelda?color=orange)</span></p>
  - [zig-libressl🗒️LibreSSL stream wrappers for Zig](https://github.com/haze/zig-libressl) <span style="float:right;">![Star](https://img.shields.io/github/stars/haze/zig-libressl?color=orange)</span></p>
  - [zig-objdump🗒️objdump but in Zig and for Zig](https://github.com/kubkon/zig-objdump) <span style="float:right;">![Star](https://img.shields.io/github/stars/kubkon/zig-objdump?color=orange)</span></p>
  - [zig-wasm-dom🗒️Zig + WebAssembly + JS + DOM](https://github.com/shritesh/zig-wasm-dom) <span style="float:right;">![Star](https://img.shields.io/github/stars/shritesh/zig-wasm-dom?color=orange)</span></p>
  - [zig-wasm-test🗒️A minimal Web Assembly example using Zig's build system](https://github.com/meheleventyone/zig-wasm-test) <span style="float:right;">![Star](https://img.shields.io/github/stars/meheleventyone/zig-wasm-test?color=orange)</span></p>
  - [zss🗒️zss is a CSS layout engine and renderer](https://github.com/chwayne/zss) <span style="float:right;">![Star](https://img.shields.io/github/stars/chwayne/zss?color=orange)</span></p>
  - [zwld🗒️Experimental wasm linker](https://github.com/Luukdegram/zwld) <span style="float:right;">![Star](https://img.shields.io/github/stars/Luukdegram/zwld?color=orange)</span></p>

- ### Other Applications
  - 🔥[bun🗒️Incredibly fast JavaScript runtime, bundler, transpiler and package manager – all in one](https://github.com/oven-sh/bun) <span style="float:right;">![Star](https://img.shields.io/github/stars/oven-sh/bun?color=orange)</span></p>
  - [cld🗒️Linker for the Coff/PE file format](https://github.com/Luukdegram/cld) <span style="float:right;">![Star](https://img.shields.io/github/stars/Luukdegram/cld?color=orange)</span></p>
  - [computils🗒️Zig utilities for all your comptime needs](https://github.com/ziglibs/computils) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/computils?color=orange)</span></p>
  - [cosmic🗒️A general purpose runtime for Javascript/WASM](https://github.com/fubark/cosmic) <span style="float:right;">![Star](https://img.shields.io/github/stars/fubark/cosmic?color=orange)</span></p>
  - [geteltorito-zig🗒️geteltorito re-write in Zig](https://github.com/hspak/geteltorito-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/hspak/geteltorito-zig?color=orange)</span></p>
  - [hexdump-zip🗒️produce an annotated hexdump of a zipfile](https://github.com/thejoshwolfe/hexdump-zip) <span style="float:right;">![Star](https://img.shields.io/github/stars/thejoshwolfe/hexdump-zip?color=orange)</span></p>
  - [iguanaTLS🗒️Minimal, experimental TLS 1.2 implementation in Zig](https://github.com/alexnask/iguanaTLS) <span style="float:right;">![Star](https://img.shields.io/github/stars/alexnask/iguanaTLS?color=orange)</span></p>
  - [iotmonitor🗒️Monitor and State server for iot mqtt devices, and software agents. This daemon permit to maintain the execution of constellations of mqtt devices and associated agents](https://github.com/mqttiotstuff/iotmonitor) <span style="float:right;">![Star](https://img.shields.io/github/stars/mqttiotstuff/iotmonitor?color=orange)</span></p>
  - [onenightonearth🗒️An interactive star map, written in Typescript and WebAssembly using Zig](https://github.com/mjoerussell/onenightonearth) <span style="float:right;">![Star](https://img.shields.io/github/stars/mjoerussell/onenightonearth?color=orange)</span></p>
  - [pacman.zig🗒️Simple Pacman clone written in Zig](https://github.com/floooh/pacman.zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/floooh/pacman.zig?color=orange)</span></p>
  - [proxy-wasm-cloud-logging-trace-context🗒️A proxy-wasm compilant WebAssembly module for making proxies integrate with Google Cloud Logging](https://github.com/kauche/proxy-wasm-cloud-logging-trace-context) <span style="float:right;">![Star](https://img.shields.io/github/stars/kauche/proxy-wasm-cloud-logging-trace-context?color=orange)</span></p>
  - 🔥[river🗒️A dynamic tiling Wayland compositor](https://github.com/riverwm/river) <span style="float:right;">![Star](https://img.shields.io/github/stars/riverwm/river?color=orange)</span></p>
  - [wayfarer🗒️Experiments involving a Zig Wayland compositor](https://github.com/dominikh/wayfarer) <span style="float:right;">![Star](https://img.shields.io/github/stars/dominikh/wayfarer?color=orange)</span></p>
  - [waylock🗒️A small screenlocker for Wayland compositors](https://github.com/ifreund/waylock) <span style="float:right;">![Star](https://img.shields.io/github/stars/ifreund/waylock?color=orange)</span></p>
  - [ZigAndroidTemplate🗒️This repository contains a example on how to create a minimal Android app in Zig](https://github.com/MasterQ32/ZigAndroidTemplate) <span style="float:right;">![Star](https://img.shields.io/github/stars/MasterQ32/ZigAndroidTemplate?color=orange)</span></p>
  - [Zag-Smalltalk🗒️Smalltalk VM Written in Zig with methods stored as type-annotated ASTs](https://github.com/dvmason/Zag-Smalltalk) <span style="float:right;">![Star](https://img.shields.io/github/stars/dvmason/Zag-Smalltalk?color=orange)</span></p>
  - [zig-ios-example🗒️Minimal build.zig for targeting iOS](https://github.com/kubkon/zig-ios-example) <span style="float:right;">![Star](https://img.shields.io/github/stars/kubkon/zig-ios-example?color=orange)</span></p>
  - [zig-minisign🗒️Minisign reimplemented in Zig](https://github.com/jedisct1/zig-minisign) <span style="float:right;">![Star](https://img.shields.io/github/stars/jedisct1/zig-minisign?color=orange)</span></p>
  - [zig-nodejs-example🗒️Node.js Native Module written in Zig](https://github.com/staltz/zig-nodejs-example) <span style="float:right;">![Star](https://img.shields.io/github/stars/staltz/zig-nodejs-example?color=orange)</span></p>
  - [zig-protobuf🗒️a protobuf 3 implementation for zig](https://github.com/Arwalk/zig-protobuf) <span style="float:right;">![Star](https://img.shields.io/github/stars/Arwalk/zig-protobuf?color=orange)</span></p>
  - [zig-snappy🗒️Snappy compression for Zig](https://github.com/gsquire/zig-snappy) <span style="float:right;">![Star](https://img.shields.io/github/stars/gsquire/zig-snappy?color=orange)</span></p>
  
## Libraries

- ### Database Operation

  - [lithdew/lmdb-zig🗒️Lightweight, fully-featured, idiomatic cross-platform Zig bindings to Lightning Memory-Mapped Database (LMDB)](https://github.com/lithdew/lmdb-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/lithdew/lmdb-zig?color=orange)</span></p>
  - [zig-sqlite🗒️zig-sqlite is a small wrapper around sqlite's C API, making it easier to use with Zig](https://github.com/vrischmann/zig-sqlite) <span style="float:right;">![Star](https://img.shields.io/github/stars/vrischmann/zig-sqlite?color=orange)</span></p>
  - [zdb🗒️Allocator-free document oriented database management](https://github.com/ziglibs/zdb) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/zdb?color=orange)</span></p>
  - [zig-sqlite3🗒️sqlite3 wrapper for Zig](https://github.com/nektro/zig-sqlite3) <span style="float:right;">![Star](https://img.shields.io/github/stars/nektro/zig-sqlite3?color=orange)</span></p>

- ### Encryption & Encoding & Decoding

  - [hts-zig🗒️ziglang + htslib](https://github.com/brentp/hts-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/brentp/hts-zig?color=orange)</span></p>
  - [inon🗒️Data serialization format in Zig](https://github.com/iddev5/inon) <span style="float:right;">![Star](https://img.shields.io/github/stars/iddev5/inon?color=orange)</span></p>
  - [mecha🗒️A parser combinator library for Zig](https://github.com/Hejsil/mecha) <span style="float:right;">![Star](https://img.shields.io/github/stars/Hejsil/mecha?color=orange)</span></p>
  - [s2s🗒️A zig binary serialization format](https://github.com/ziglibs/s2s) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/s2s?color=orange)</span></p>
  - [tls13-zig🗒️The first TLS1.3 implementation in Zig(master/HEAD) only with std](https://github.com/shiguredo/tls13-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/shiguredo/tls13-zig?color=orange)</span></p>
  - [uuencode🗒️Unix-To-Unix-Encoding for Zig](https://github.com/ziglibs/uuencode) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/uuencode?color=orange)</span></p>
  - [xm🗒️Tokenize XML](https://github.com/andrewrk/xml) <span style="float:right;">![Star](https://img.shields.io/github/stars/andrewrk/xml?color=orange)</span></p>
  - [wavefront-obj🗒️A parser for wavefront object files](https://github.com/ziglibs/wavefront-obj) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/wavefront-obj?color=orange)</span></p>
  - [zasp🗒️zasp ⚡ a streaming parser](https://github.com/fengb/zasp) <span style="float:right;">![Star](https://img.shields.io/github/stars/fengb/zasp?color=orange)</span></p>
  - [zdwg🗒️Read, manipulate, write AutoCad DWG files in zig](https://github.com/alexnask/zdwg) <span style="float:right;">![Star](https://img.shields.io/github/stars/alexnask/zdwg?color=orange)</span></p>
  - [zig-args🗒️Simple-to-use argument parser with struct-based config](https://github.com/MasterQ32/zig-args) <span style="float:right;">![Star](https://img.shields.io/github/stars/MasterQ32/zig-args?color=orange)</span></p>
  - [zig-charm🗒️A Zig version of the Charm crypto library](https://github.com/jedisct1/zig-charm) <span style="float:right;">![Star](https://img.shields.io/github/stars/jedisct1/zig-charm?color=orange)</span></p>
  - [zig-libxml2🗒️libxml2 built using Zig build system](https://github.com/mitchellh/zig-libxml2) <span style="float:right;">![Star](https://img.shields.io/github/stars/mitchellh/zig-libxml2?color=orange)</span></p>
  - [zig-tzif🗒️TZif parsing for Zig](https://github.com/leroycep/zig-tzif) <span style="float:right;">![Star](https://img.shields.io/github/stars/leroycep/zig-tzif?color=orange)</span></p>
  - [zig-nestedtext🗒️Zig NestedText parser library - a simple human readable data format based on YAML](https://github.com/LewisGaul/zig-nestedtext) <span style="float:right;">![Star](https://img.shields.io/github/stars/LewisGaul/zig-nestedtext?color=orange)</span></p>
  - [zig-wayland🗒️Zig wayland scanner and libwayland bindings](https://github.com/ifreund/zig-wayland) <span style="float:right;">![Star](https://img.shields.io/github/stars/ifreund/zig-wayland?color=orange)</span></p>
  - [zjson🗒️Minimal json library with zero allocations](https://github.com/xyaman/zjson) <span style="float:right;">![Star](https://img.shields.io/github/stars/xyaman/zjson?color=orange)</span></p>

- ### Game Dev & GUI Dev & Media Framework

  - [2jz🗒️An archetype-based entity-component-system library written in Zig](https://github.com/EvWilson/2jz) <span style="float:right;">![Star](https://img.shields.io/github/stars/EvWilson/2jz?color=orange)</span></p>
  - [Alka🗒️Simple, fast, easy to get started mid-level game engine written in Zig](https://github.com/Kiakra/Alka) <span style="float:right;">![Star](https://img.shields.io/github/stars/Kiakra/Alka?color=orange)</span></p>
  - [audiometa🗒️An audio metadata/tag reading library written in Zig](https://github.com/squeek502/audiometa) <span style="float:right;">![Star](https://img.shields.io/github/stars/squeek502/audiometa?color=orange)</span></p>
  - 🔥[capy🗒️Cross-platform library for making true native GUIs in Zig](https://github.com/capy-ui/capy) <span style="float:right;">![Star](https://img.shields.io/github/stars/capy-ui/capy?color=orange)</span></p>
  - [cupcake🗒️an app framework for making small and delicious games! (very wip)](https://github.com/bootradev/cupcake) <span style="float:right;">![Star](https://img.shields.io/github/stars/bootradev/cupcake?color=orange)</span></p>
  - [didot🗒️Zig 3D game engine](https://github.com/zenith391/didot) <span style="float:right;">![Star](https://img.shields.io/github/stars/zenith391/didot?color=orange)</span></p>
  - [fontaine🗒️A library to support text rendering in arbitrary contexts](https://github.com/ziglibs/fontaine) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/fontaine?color=orange)</span></p>
  - [gui](https://github.com/david-vanderson/gui) <span style="float:right;">![Star](https://img.shields.io/github/stars/david-vanderson/gui?color=orange)</span></p>
  - [IUPforZig🗒️Zig idiomatic and type-checked bindings for IUP Portable User Interface Toolkit](https://github.com/batiati/IUPforZig) <span style="float:right;">![Star](https://img.shields.io/github/stars/batiati/IUPforZig?color=orange)</span></p>
  - [libvlc-zig🗒️Zig bindings for libVLC media framework](https://github.com/kassane/libvlc-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/kassane/libvlc-zig?color=orange)</span></p>
  - 🔥[mach🗒️Mach is a game engine & graphics toolkit for the future](https://github.com/hexops/mach) <span style="float:right;">![Star](https://img.shields.io/github/stars/hexops/mach?color=orange)</span></p>
  - [metronome🗒️A set of tools for modifying and randomizing Pokémon games](https://github.com/TM35-Metronome/metronome) <span style="float:right;">![Star](https://img.shields.io/github/stars/TM35-Metronome/metronome?color=orange)</span></p>
  - [notcurses-zig-example🗒️Demo showing how to use Notcurses library for building terminal UIs with Zig](https://github.com/dundalek/notcurses-zig-example) <span style="float:right;">![Star](https://img.shields.io/github/stars/dundalek/notcurses-zig-example?color=orange)</span></p>
  - [painterz🗒️Low-level implementation of different painting primitives (lines, rectangles, ...) without specialization on a certain draw target](https://github.com/ziglibs/painterz) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/painterz?color=orange)</span></p>
  - [qml_zig🗒️QML bindings for the Zig programming language](https://github.com/kassane/qml_zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/kassane/qml_zig?color=orange)</span></p>
  - [raylib-zig🗒️Manually tweaked, auto generated raylib bindings for zig. https://github.com/raysan5/raylib](https://github.com/Not-Nik/raylib-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/raysan5/raylib?color=orange)</span></p>
  - [SDL.zig🗒️A shallow wrapper around SDL that provides object API and error handling](https://github.com/MasterQ32/SDL.zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/MasterQ32/SDL.zig?color=orange)</span></p>
  - [seizer🗒️Cross platform Zig library for obtaining a rendering context and loading assets](https://github.com/leroycep/seizer) <span style="float:right;">![Star](https://img.shields.io/github/stars/leroycep/seizer?color=orange)</span></p>
  - [slingworks🗒️Small to Medium scale 2d Game Engine for Zig](https://github.com/JonSnowbd/slingworks) <span style="float:right;">![Star](https://img.shields.io/github/stars/JonSnowbd/slingworks?color=orange)</span></p>
  - [sndio-zig🗒️sndio bindings for zig](https://github.com/dantecatalfamo/sndio-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/dantecatalfamo/sndio-zig?color=orange)</span></p>
  - [tm35-nds🗒️A library for working with Nintendo DS roms](https://github.com/TM35-Metronome/tm35-nds) <span style="float:right;">![Star](https://img.shields.io/github/stars/TM35-Metronome/tm35-nds?color=orange)</span></p>
  - [VecFns🗒️Automatic Vector Math Functions In Zig](https://github.com/omaraaa/VecFns) <span style="float:right;">![Star](https://img.shields.io/github/stars/omaraaa/VecFns?color=orange)</span></p>
  - [vulkan-zig🗒️Vulkan binding generator for Zig](https://github.com/Snektron/vulkan-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/Snektron/vulkan-zig?color=orange)</span></p>
  - 🔥[wasm4🗒️Build retro games using WebAssembly for a fantasy console](https://github.com/aduros/wasm4) <span style="float:right;">![Star](https://img.shields.io/github/stars/aduros/wasm4?color=orange)</span></p>
  - [zalgebra🗒️Linear algebra library for games and real-time graphics](https://github.com/kooparse/zalgebra) <span style="float:right;">![Star](https://img.shields.io/github/stars/kooparse/zalgebra?color=orange)</span></p>
  - [zero-graphics🗒️Application framework based on OpenGL ES 2.0. Runs on desktop machines, Android phones and the web](https://github.com/MasterQ32/zero-graphics) <span style="float:right;">![Star](https://img.shields.io/github/stars/MasterQ32/zero-graphics?color=orange)</span></p>
  - [zgl🗒️Zig OpenGL Wrapper](https://github.com/ziglibs/zgl) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/zgl?color=orange)</span></p>
  - [zglfw🗒️A thin, idiomatic wrapper for GLFW. Written in Zig, for Zig!](https://github.com/Iridescence-Technologies/zglfw) <span style="float:right;">![Star](https://img.shields.io/github/stars/Iridescence-Technologies/zglfw?color=orange)</span></p>
  - [zig-gamedev-lib🗒️xq's Zig Game Development Library](https://github.com/Iridescence-Technologies/zglfw) <span style="float:right;">![Star](https://img.shields.io/github/stars/Iridescence-Technologies/zglfw?color=orange)</span></p>
  - 🔥[zig-gamedev🗒️Building game development ecosystem for @ziglang!](https://github.com/michal-z/zig-gamedev) <span style="float:right;">![Star](https://img.shields.io/github/stars/michal-z/zig-gamedev?color=orange)</span></p>
  - [Zig-Game-Engine](https://github.com/danielabbott/Zig-Game-Engine) <span style="float:right;">![Star](https://img.shields.io/github/stars/danielabbott/Zig-Game-Engine?color=orange)</span></p>
  - [zig-gamekit🗒️Companion repo for zig-renderkit for making 2D games](https://github.com/prime31/zig-gamekit) <span style="float:right;">![Star](https://img.shields.io/github/stars/prime31/zig-gamekit?color=orange)</span></p>
  - [ZigGBA🗒️Work in progress SDK for creating Game Boy Advance games using Zig programming language](https://github.com/wendigojaeger/ZigGBA) <span style="float:right;">![Star](https://img.shields.io/github/stars/wendigojaeger/ZigGBA?color=orange)</span></p>
  - [Zig-Gltf-Display🗒️A program that displays glTF files using Vulkan, written in Zig](https://github.com/SpexGuy/Zig-Gltf-Display) <span style="float:right;">![Star](https://img.shields.io/github/stars/SpexGuy/Zig-Gltf-Display?color=orange)</span></p>
  - [zigimg🗒️Zig library for reading and writing different image formats](https://github.com/zigimg/zigimg) <span style="float:right;">![Star](https://img.shields.io/github/stars/zigimg/zigimg?color=orange)</span></p>
  - [Zig-PSP🗒️A project to bring the Zig Programming Language to the Sony PlayStation Portable!](https://github.com/zPSP-Dev/Zig-PSP) <span style="float:right;">![Star](https://img.shields.io/github/stars/zPSP-Dev/Zig-PSP?color=orange)</span></p>
  - [zig-qoi🗒️Quite OK Image format encoder/decoder written in Zig](https://github.com/MasterQ32/zig-qoi) <span style="float:right;">![Star](https://img.shields.io/github/stars/MasterQ32/zig-qoi?color=orange)</span></p>
  - [zig-renderkit🗒️Cross platform Zig graphics backends with a 2D focus](https://github.com/prime31/zig-renderkit) <span style="float:right;">![Star](https://img.shields.io/github/stars/prime31/zig-renderkit?color=orange)</span></p>
  - [zig-sdl🗒️self-contained SDL2 package for Zig](https://github.com/andrewrk/zig-sdl) <span style="float:right;">![Star](https://img.shields.io/github/stars/andrewrk/zig-sdl?color=orange)</span></p>
  - [zig-sfml-wrapper🗒️A zig wrapper for csfml](https://github.com/Guigui220D/zig-sfml-wrapper) <span style="float:right;">![Star](https://img.shields.io/github/stars/Guigui220D/zig-sfml-wrapper?color=orange)</span></p>
  - [zig-tracy🗒️Zig bindings for the Tracy profiler](https://github.com/nektro/zig-tracy) <span style="float:right;">![Star](https://img.shields.io/github/stars/nektro/zig-tracy?color=orange)</span></p>
  - [zig-upaya🗒️Zig-based framework for creating game tools and helper apps](https://github.com/prime31/zig-upaya) <span style="float:right;">![Star](https://img.shields.io/github/stars/prime31/zig-upaya?color=orange)</span></p>
  - [zig-window🗒️window client library](https://github.com/andrewrk/zig-window) <span style="float:right;">![Star](https://img.shields.io/github/stars/andrewrk/zig-window?color=orange)</span></p>
  - [zig-wlroots🗒️Zig bindings for wlroots](https://github.com/swaywm/zig-wlroots) <span style="float:right;">![Star](https://img.shields.io/github/stars/swaywm/zig-wlroots?color=orange)</span></p>
  - [zlm🗒️Zig linear mathemathics](https://github.com/ziglibs/zlm) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/zlm?color=orange)</span></p>
  - [zplay🗒️A simple framework intended for game/tool creation](https://github.com/jack-ji/zplay) <span style="float:right;">![Star](https://img.shields.io/github/stars/jack-ji/zplay?color=orange)</span></p>
  - [ZT🗒️A zig based Imgui Application framework](https://github.com/JonSnowbd/ZT) <span style="float:right;">![Star](https://img.shields.io/github/stars/JonSnowbd/ZT?color=orange)</span></p>
  - [zwin🗒️Making windows with Zig! (Only works on Windows at the moment)](https://github.com/ziglibs/zwin) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/zwin?color=orange)</span></p>
  - [ZWL🗒️Zig Windowing Library](https://github.com/Aransentin/ZWL) <span style="float:right;">![Star](https://img.shields.io/github/stars/Aransentin/ZWL?color=orange)</span></p>

- ### Language Bindings

  - [mruby-zig🗒️mruby bindings for zig](https://github.com/dantecatalfamo/mruby-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/dantecatalfamo/mruby-zig?color=orange)</span></p>
  - [wren-zig🗒️wren bindings for zig](https://github.com/dantecatalfamo/wren-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/dantecatalfamo/wren-zig?color=orange)</span></p>
  - [zig-autolua🗒️Lua binding creator for zig](https://github.com/daurnimator/zig-autolua) <span style="float:right;">![Star](https://img.shields.io/github/stars/daurnimator/zig-autolua?color=orange)</span></p>
  - [zig-objc🗒️Objective-C runtime bindings for Zig (Zig calling ObjC)](https://github.com/mitchellh/zig-objc) <span style="float:right;">![Star](https://img.shields.io/github/stars/mitchellh/zig-objc?color=orange)</span></p>

- ### Terminal & Low-Level Libraries & System API

  - [ansi-term🗒️Zig library for dealing with ANSI terminals](https://github.com/ziglibs/ansi-term) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/ansi-term?color=orange)</span></p>
  - [dos.zig🗒️Create DOS programs with Zig](https://github.com/jayschwa/dos.zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/jayschwa/dos.zig?color=orange)</span></p>
  - [known-folders🗒️Provides access to well-known folders across several operating systems](https://github.com/ziglibs/known-folders) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/known-folders?color=orange)</span></p>
  - [linenoize🗒️A port of linenoise to zig](https://github.com/joachimschmidt557/linenoize) <span style="float:right;">![Star](https://img.shields.io/github/stars/joachimschmidt557/linenoize?color=orange)</span></p>
  - [lscolors🗒️A zig library for colorizing paths according to LS_COLORS](https://github.com/ziglibs/lscolors) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/lscolors?color=orange)</span></p>
  - [mibu🗒️Pure Zig library for low-level terminal manipulation](https://github.com/xyaman/mibu) <span style="float:right;">![Star](https://img.shields.io/github/stars/xyaman/mibu?color=orange)</span></p>
  - [nfd-zig🗒️OS-native file dialogs on Linux, macOS and Windows](https://github.com/fabioarnold/nfd-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/fabioarnold/nfd-zig?color=orange)</span></p>
  - [x86-zig🗒️library for assembling x86 in zig (WIP)](https://github.com/momumi/x86-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/momumi/x86-zig?color=orange)</span></p>
  - [yazap🗒️A simple and easy-to-use zig library for parsing command line arguments, flags and subcommands](https://github.com/PrajwalCH/yazap) <span style="float:right;">![Star](https://img.shields.io/github/stars/PrajwalCH/yazap?color=orange)</span></p>
  - [zig-clap🗒️Simple command line argument parsing library](https://github.com/Hejsil/zig-clap) <span style="float:right;">![Star](https://img.shields.io/github/stars/Hejsil/zig-clap?color=orange)</span></p>
  - [ZigKit🗒️Zig bindings for low-level macOS frameworks](https://github.com/kubkon/ZigKit) <span style="float:right;">![Star](https://img.shields.io/github/stars/kubkon/ZigKit?color=orange)</span></p>
  - [zigra🗒️Command line toolkit for Zig](https://github.com/Gonzih/zigra) <span style="float:right;">![Star](https://img.shields.io/github/stars/Gonzih/zigra?color=orange)</span></p>
  - [zig-serial🗒️Serial port configuration library for Zig](https://github.com/MasterQ32/zig-serial) <span style="float:right;">![Star](https://img.shields.io/github/stars/MasterQ32/zig-serial?color=orange)</span></p>
  - [zigwin32🗒️Autogenerated Zig bindings for Win32](https://github.com/marlersoft/zigwin32) <span style="float:right;">![Star](https://img.shields.io/github/stars/marlersoft/zigwin32?color=orange)</span></p>
  - [zig-windows-console🗒️Zig Windows Console stuff](https://github.com/ziglibs/zig-windows-console) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/zig-windows-console?color=orange)</span></p>
  - [zinput🗒️A Zig command-line input library!](https://github.com/ziglibs/zinput) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/zinput?color=orange)</span></p>

- ### Universal

  - #### Algorithms & Data Structures

    - [ArrayVec🗒️An array with a vector feeling in Zig](https://github.com/DutchGhost/ArrayVec) <span style="float:right;">![Star](https://img.shields.io/github/stars/DutchGhost/ArrayVec?color=orange)</span></p>
    - [art.zig🗒️An Adaptive Radix Tree ported from c](https://github.com/travisstaloch/art.zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/travisstaloch/art.zig?color=orange)</span></p>
    - [ctregex.zig🗒️Compile time regular expressions in zig](https://github.com/alexnask/ctregex.zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/alexnask/ctregex.zig?color=orange)</span></p>
    - [comptime_hash_map🗒️A statically initiated HashMap](https://github.com/Vexu/comptime_hash_map) <span style="float:right;">![Star](https://img.shields.io/github/stars/Vexu/comptime_hash_map?color=orange)</span></p>
    - [deque.zig🗒️a lock free chase-lev deque for zig](https://github.com/emekoi/deque.zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/emekoi/deque.zig?color=orange)</span></p>
    - [fastfilter🗒️fastfilter:Binary fuse & xor filters for Zig (faster and smaller than bloom filters)](https://github.com/hexops/fastfilter) <span style="float:right;">![Star](https://img.shields.io/github/stars/hexops/fastfilter?color=orange)</span></p>
    - [funzig🗒️Fun functional functionality for Zig!](https://github.com/ziglibs/funzig) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/funzig?color=orange)</span></p>
    - [ish🗒️Sketches for Zig](https://github.com/judofyr/ish) <span style="float:right;">![Star](https://img.shields.io/github/stars/judofyr/ish?color=orange)</span></p>
    - [it/redis-cuckoofilter🗒️Hashing-function agnostic Cuckoo filters for Redis](https://github.com/kristoff-it/redis-cuckoofilter) <span style="float:right;">![Star](https://img.shields.io/github/stars/kristoff-it/redis-cuckoofilter?color=orange)</span></p>
    - [Lazy-Zig🗒️Linq in Zig](https://github.com/BraedonWooding/Lazy-Zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/BraedonWooding/Lazy-Zig?color=orange)</span></p>
    - [LZig4🗒️Implementing lz4 in zig](https://github.com/BarabasGitHub/LZig4) <span style="float:right;">![Star](https://img.shields.io/github/stars/BarabasGitHub/LZig4?color=orange)</span></p>
    - [minz🗒️Minimal string compression](https://github.com/judofyr/minz) <span style="float:right;">![Star](https://img.shields.io/github/stars/judofyr/minz?color=orange)</span></p>
    - [string-searching🗒️String(not limited to [] const u8)-searching algorithms in zig](https://github.com/ziglibs/string-searching) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/string-searching?color=orange)</span></p>
    - [zig-containers🗒️A container library for Zig](https://github.com/Sahnvour/zig-containers) <span style="float:right;">![Star](https://img.shields.io/github/stars/Sahnvour/zig-containers?color=orange)</span></p>
    - [zig-cuckoofilter🗒️Production-ready Cuckoo Filters for any C ABI compatible target](https://github.com/kristoff-it/zig-cuckoofilter) <span style="float:right;">![Star](https://img.shields.io/github/stars/kristoff-it/zig-cuckoofilter?color=orange)</span></p>
    - [zig-graph🗒️Directed graph data structure for Zig](https://github.com/mitchellh/zig-graph) <span style="float:right;">![Star](https://img.shields.io/github/stars/mitchellh/zig-graph?color=orange)</span></p>
    - [zig-prometheus🗒️Prometheus/VictoriaMetrics client library for Zig](https://github.com/vrischmann/zig-prometheus) <span style="float:right;">![Star](https://img.shields.io/github/stars/vrischmann/zig-prometheus?color=orange)</span></p>
    - [zig-sparse-set🗒️Sparse sets for zig, supporting both SOA and AOS style](https://github.com/Srekel/zig-sparse-set) <span style="float:right;">![Star](https://img.shields.io/github/stars/Srekel/zig-sparse-set?color=orange)</span></p>
    - [zigstr🗒️Zigstr is a UTF-8 string type for Zig programs](https://github.com/jecolon/zigstr) <span style="float:right;">![Star](https://img.shields.io/github/stars/jecolon/zigstr?color=orange)</span></p>
    - [zig-string🗒️A String Library made in Zig](https://github.com/JakubSzark/zig-string) <span style="float:right;">![Star](https://img.shields.io/github/stars/JakubSzark/zig-string?color=orange)</span></p>
    - [zigfp🗒️Basic fixed point implementation in Zig](https://github.com/ziglibs/zigfp) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/zigfp?color=orange)</span></p>
    - [zignite🗒️A lazy stream (iterator) library for Zig](https://github.com/shunkeen/zignite) <span style="float:right;">![Star](https://img.shields.io/github/stars/shunkeen/zignite?color=orange)</span></p>
    - [zigtimsort🗒️TimSort implementation for Zig](https://github.com/marijnfs/zigtimsort) <span style="float:right;">![Star](https://img.shields.io/github/stars/marijnfs/zigtimsort?color=orange)</span></p>
    - [zini🗒️Minimal perfect hash function for Zig](https://github.com/judofyr/zini) <span style="float:right;">![Star](https://img.shields.io/github/stars/judofyr/zini?color=orange)</span></p>
    - [ziter🗒️Best iterator library for Zig (fight me!)](https://github.com/Hejsil/ziter) <span style="float:right;">![Star](https://img.shields.io/github/stars/Hejsil/ziter?color=orange)</span></p>
    - [znum🗒️Simple numeric tower implemented on Zig standard types](https://hg.sr.ht/~hutzdog/Zcheme/browse/znum?rev=tip)
    - [zorm🗒️Lightweight and efficient object-relational mapping](https://github.com/ziglibs/zorm) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/zorm?color=orange)</span></p>
    - [zort🗒️Implementation of 9 sorting algorithms in Zig](https://github.com/AliChraghi/zort) <span style="float:right;">![Star](https://img.shields.io/github/stars/AliChraghi/zort?color=orange)</span></p>
    - [zzz🗒️Simple and boring human readable data format for Zig](https://github.com/gruebite/zzz) <span style="float:right;">![Star](https://img.shields.io/github/stars/gruebite/zzz?color=orange)</span></p>

  - #### Memory Management

    - [adma🗒️A general purpose, multithreaded capable slab allocator for Zig](https://github.com/suirad/adma) <span style="float:right;">![Star](https://img.shields.io/github/stars/suirad/adma?color=orange)</span></p>
    - [Seal🗒️An allocator that wraps another allocator and detects if memory is leaked after usage](https://github.com/suirad/Seal) <span style="float:right;">![Star](https://img.shields.io/github/stars/suirad/Seal?color=orange)</span></p>
    - [zcirc🗒️A dynamic circular buffer allocator for zig](https://github.com/hmusgrave/zcirc) <span style="float:right;">![Star](https://img.shields.io/github/stars/hmusgrave/zcirc?color=orange)</span></p>
    - [zee_alloc🗒️tiny Zig allocator primarily targeting WebAssembly](https://github.com/fengb/zee_alloc) <span style="float:right;">![Star](https://img.shields.io/github/stars/fengb/zee_alloc?color=orange)</span></p>
    - [ziegfried🗒️A general-purpose memory allocator for Zig](https://github.com/mdsteele/ziegfried) <span style="float:right;">![Star](https://img.shields.io/github/stars/mdsteele/ziegfried?color=orange)</span></p>
    - [zig-libgc🗒️Zig-friendly library for interfacing with libgc (bdwgc) -- the Boehm-Demers-Weiser conservative garbage collector](https://github.com/mitchellh/zig-libgc) <span style="float:right;">![Star](https://img.shields.io/github/stars/mitchellh/zig-libgc?color=orange)</span></p>
    - [zig-rcsp🗒️Reference-counted Shared Pointer for Zig](https://github.com/yrashk/zig-rcsp) <span style="float:right;">![Star](https://img.shields.io/github/stars/yrashk/zig-rcsp?color=orange)</span></p>

  - #### Other Universal Libraries

    - [async_io_uring🗒️An event loop in Zig using io_uring and coroutines](https://github.com/saltzm/async_io_uring) <span style="float:right;">![Star](https://img.shields.io/github/stars/saltzm/async_io_uring?color=orange)</span></p>
    - [comptemplate](https://github.com/ziglibs/comptemplate) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/comptemplate?color=orange)</span></p>
    - [diffz🗒️Implementation of go-diff's diffmatchpatch in Zig](https://github.com/ziglibs/diffz) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/diffz?color=orange)</span></p>
    - [getty🗒️Serialization framework for Zig](https://github.com/getty-zig/getty) <span style="float:right;">![Star](https://img.shields.io/github/stars/getty-zig/getty?color=orange)</span></p>
    - [interface.zig🗒️Dynamic dispatch for zig made easy](https://github.com/alexnask/interface.zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/alexnask/interface.zig?color=orange)</span></p>
    - [libxev🗒️libxev is a cross-platform, high-performance event loop that provides abstractions for non-blocking IO, timers, events, and more and works on Linux (io_uring or epoll), macOS (kqueue), and Wasm + WASI. Available as both a Zig and C API](https://github.com/mitchellh/libxev) <span style="float:right;">![Star](https://img.shields.io/github/stars/mitchellh/libxev?color=orange)</span></p>
    - [log.zig🗒️a thread-safe logging library for zig](https://github.com/emekoi/log.zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/emekoi/log.zig?color=orange)</span></p>
    - [PeerType🗒️Zig peer type resolution at comptime, ported from the compiler source code](https://github.com/alexnask/PeerType) <span style="float:right;">![Star](https://img.shields.io/github/stars/alexnask/PeerType?color=orange)</span></p>
    - [sokol-zig🗒️Zig bindings for the sokol headers (https://github.com/floooh/sokol)](https://github.com/floooh/sokol-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/floooh/sokol-zig?color=orange)</span></p>
    - [trace.zig🗒️A small and simple tracing client library for Zig](https://gitlab.com/zig_tracing/trace.zig)
    - [zap🗒️An asynchronous runtime with a focus on performance and resource efficiency](https://github.com/kprotty/zap) <span style="float:right;">![Star](https://img.shields.io/github/stars/kprotty/zap?color=orange)</span></p>
    - [zig-datetime🗒️A date and time module for Zig](https://github.com/frmdstryr/zig-datetime) <span style="float:right;">![Star](https://img.shields.io/github/stars/frmdstryr/zig-datetime?color=orange)</span></p>
    - [zig-extras🗒️An assortment of random utility functions that aren't in std and don't deserve their own pacakge](https://github.com/nektro/zig-extras) <span style="float:right;">![Star](https://img.shields.io/github/stars/nektro/zig-extras?color=orange)</span></p>
    - [zig-generator🗒️Async generator type for Zig](https://github.com/yrashk/zig-generator) <span style="float:right;">![Star](https://img.shields.io/github/stars/yrashk/zig-generator?color=orange)</span></p>
    - [zig-leven🗒️Measure the difference between two slices using the Levenshtein distance algorithm](https://github.com/nektro/zig-leven) <span style="float:right;">![Star](https://img.shields.io/github/stars/nektro/zig-leven?color=orange)</span></p>
    - [ziglyph🗒️Unicode text processing for the Zig programming language](https://github.com/jecolon/ziglyph) <span style="float:right;">![Star](https://img.shields.io/github/stars/jecolon/ziglyph?color=orange)</span></p>
    - [zig-range🗒️A range function to loop over an index without an extra variable](https://github.com/nektro/zig-range) <span style="float:right;">![Star](https://img.shields.io/github/stars/nektro/zig-range?color=orange)</span></p>
    - [zig-regex🗒️A regex implementation for the zig programming language](https://github.com/tiehuis/zig-regex) <span style="float:right;">![Star](https://img.shields.io/github/stars/tiehuis/zig-regex?color=orange)</span></p>
    - [zig-time🗒️A date and time parsing and formatting library for Zig](https://github.com/nektro/zig-time) <span style="float:right;">![Star](https://img.shields.io/github/stars/nektro/zig-time?color=orange)</span></p>
    - [zig-ulid🗒️A binary implementation of ULID in Zig](https://github.com/nektro/zig-ulid) <span style="float:right;">![Star](https://img.shields.io/github/stars/nektro/zig-ulid?color=orange)</span></p>
    - [zoltan🗒️A Sol-inspired minimalist Lua binding for Zig](https://github.com/ranciere/zoltan) <span style="float:right;">![Star](https://img.shields.io/github/stars/ranciere/zoltan?color=orange)</span></p>

- ### Web

  - [apple_pie🗒️Basic HTTP server implementation in Zig](https://github.com/Luukdegram/apple_pie) <span style="float:right;">![Star](https://img.shields.io/github/stars/Luukdegram/apple_pie?color=orange)</span></p>
  - [espresso-zig🗒️Zig bindings for espresso C library](https://github.com/kubkon/espresso-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/kubkon/espresso-zig?color=orange)</span></p>
  - [foxwren🗒️A WebAssembly runtime in zig](https://github.com/malcolmstill/foxwren) <span style="float:right;">![Star](https://img.shields.io/github/stars/malcolmstill/foxwren?color=orange)</span></p>
  - [h11🗒️I/O agnostic HTTP/1.1 implementation for Zig ](https://github.com/ducdetronquito/h11) <span style="float:right;">![Star](https://img.shields.io/github/stars/ducdetronquito/h11?color=orange)</span></p>
  - [htmlentities.zig🗒️HTML entity data for Zig](https://github.com/kivikakk/htmlentities.zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/kivikakk/htmlentities.zig?color=orange)</span></p>
  - [http🗒️HTTP core types for Zig 🦴](https://github.com/ducdetronquito/http) <span style="float:right;">![Star](https://img.shields.io/github/stars/ducdetronquito/http?color=orange)</span></p>
  - [ip.zig🗒️A Zig library for working with IP Addresses](https://github.com/euantorano/ip.zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/euantorano/ip.zig?color=orange)</span></p>
  - [positron🗒️A web renderer frontend for zig applications](https://github.com/ziglibs/positron) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/positron?color=orange)</span></p>
  - [rem🗒️An HTML parsing library, written in Zig](https://github.com/chwayne/rem) <span style="float:right;">![Star](https://img.shields.io/github/stars/chwayne/rem?color=orange)</span></p>
  - [routez🗒️Http server for Zig](https://github.com/Vexu/routez) <span style="float:right;">![Star](https://img.shields.io/github/stars/Vexu/routez?color=orange)</span></p>
  - [snow🗒️A small, fast, cross-platform, async Zig networking framework built on top of lithdew/pike](https://github.com/lithdew/snow) <span style="float:right;">![Star](https://img.shields.io/github/stars/lithdew/snow?color=orange)</span></p>
  - [wasmer-zig🗒️Zig bindings for the Wasmer WebAssembly runtime](https://github.com/zigwasm/wasmer-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/zigwasm/wasmer-zig?color=orange)</span></p>
  - [wasmtime-zig🗒️Zig embedding of Wasmtime](https://github.com/zigwasm/wasmtime-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/zigwasm/wasmtime-zig?color=orange)</span></p>
  - [wasm-zig🗒️Common Wasm runtime binding to C API](https://github.com/zigwasm/wasm-zig) <span style="float:right;">![Star](https://img.shields.io/github/stars/zigwasm/wasm-zig?color=orange)</span></p>
  - [wazm🗒️Web Assembly Zig Machine](https://github.com/fengb/wazm) <span style="float:right;">![Star](https://img.shields.io/github/stars/fengb/wazm?color=orange)</span></p>
  - [wz🗒️An I/O agnostic WebSocket 1.3 library for Zig](https://github.com/truemedian/wz) <span style="float:right;">![Star](https://img.shields.io/github/stars/truemedian/wz?color=orange)</span></p>
  - [zCOM🗒️A composable network protocol stack for embedded and desktop](https://github.com/ziglibs/zCOM) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/zCOM?color=orange)</span></p>
  - [zhp🗒️A Http server written in Zig](https://github.com/frmdstryr/zhp) <span style="float:right;">![Star](https://img.shields.io/github/stars/frmdstryr/zhp?color=orange)</span></p>
  - [zigdig🗒️naive dns client library in zig](https://github.com/lun-4/zigdig) <span style="float:right;">![Star](https://img.shields.io/github/stars/lun-4/zigdig?color=orange)</span></p>
  - [zig-dns🗒️Experimental DNS library implemented in zig](https://github.com/dantecatalfamo/zig-dns) <span style="float:right;">![Star](https://img.shields.io/github/stars/dantecatalfamo/zig-dns?color=orange)</span></p>
  - [zigly🗒️The easiest way to write services for Fastly's Compute@Edge in Zig](https://github.com/jedisct1/zigly) <span style="float:right;">![Star](https://img.shields.io/github/stars/jedisct1/zigly?color=orange)</span></p>
  - [zig-network🗒️A smallest-common-subset of socket functions for crossplatform networking, TCP & UDP](https://github.com/MasterQ32/zig-network) <span style="float:right;">![Star](https://img.shields.io/github/stars/MasterQ32/zig-network?color=orange)</span></p>
  - [zig-oauth2🗒️HTTP handler functions to allow you to easily add OAuth2 login support to your Zig application](https://github.com/nektro/zig-oauth2) <span style="float:right;">![Star](https://img.shields.io/github/stars/nektro/zig-oauth2?color=orange)</span></p>
  - [zig-v8🗒️Simple V8 builds with C and Zig bindings](https://github.com/fubark/zig-v8) <span style="float:right;">![Star](https://img.shields.io/github/stars/fubark/zig-v8?color=orange)</span></p>

- ### Other Libraries

  - [antiphony🗒️A zig remote procedure call solution](https://github.com/ziglibs/antiphony) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/antiphony?color=orange)</span></p>
  - [libflightplan🗒️A library for reading and writing flight plans in various formats. Available as both a C and Zig library](https://github.com/mitchellh/libflightplan) <span style="float:right;">![Star](https://img.shields.io/github/stars/mitchellh/libflightplan?color=orange)</span></p>
  - [tenet🗒️Automatic differentiation prototype in Zig](https://github.com/christopher-hesse/tenet) <span style="float:right;">![Star](https://img.shields.io/github/stars/christopher-hesse/tenet?color=orange)</span></p>
  - [zig-bench🗒️Simple benchmarking library](https://github.com/Hejsil/zig-bench) <span style="float:right;">![Star](https://img.shields.io/github/stars/Hejsil/zig-bench?color=orange)</span></p>
  - [zigcv🗒️zig bindings for OpenCV4](https://github.com/ryoppippi/zigcv) <span style="float:right;">![Star](https://img.shields.io/github/stars/ryoppippi/zigcv?color=orange)</span></p>
  - [zig-dis-x86_64🗒️x86_64 disassembler library written in Zig](https://github.com/kubkon/zig-dis-x86_64) <span style="float:right;">![Star](https://img.shields.io/github/stars/kubkon/zig-dis-x86_64?color=orange)</span></p>
  - [zig-docker🗒️Zig bindings for the Docker Engine API](https://github.com/nektro/zig-docker) <span style="float:right;">![Star](https://img.shields.io/github/stars/nektro/zig-docker?color=orange)</span></p>
  - [zig-libcurl🗒️compile libcurl in your build.zig](https://github.com/mattnite/zig-libcurl) <span style="float:right;">![Star](https://img.shields.io/github/stars/mattnite/zig-libcurl?color=orange)</span></p>
  - [zig-lv2🗒️Zig-intuitive bindings for LV2](https://github.com/ziglibs/zig-lv2) <span style="float:right;">![Star](https://img.shields.io/github/stars/ziglibs/zig-lv2?color=orange)</span></p>
  - [zig-nanoid🗒️A tiny, secure, URL-friendly, unique string ID generator. Now available in pure Zig](https://github.com/SasLuca/zig-nanoid) <span style="float:right;">![Star](https://img.shields.io/github/stars/SasLuca/zig-nanoid?color=orange)</span></p>
  - [zig-pek🗒️A comptime HTML preprocessor with a builtin template engine for Zig](https://github.com/nektro/zig-pek) <span style="float:right;">![Star](https://img.shields.io/github/stars/nektro/zig-pek?color=orange)</span></p>
  - [zig-zlib🗒️compile zlib in your build.zig](https://github.com/mattnite/zig-zlib) <span style="float:right;">![Star](https://img.shields.io/github/stars/mattnite/zig-zlib?color=orange)</span></p>


## Resources

**Content that has appeared in [Related Web Sites](#related-web-sites) will not appear here again** 

- ### [Community](https://github.com/ziglang/zig/wiki/Community)

- ### Introduction Or News
  
  - [Interview with Zig language creator Andrew Kelley - YouTube](https://www.youtube.com/watch?v=ZvskDoP09Ao) <span style="float:right;">![Views](https://img.shields.io/youtube/views/ZvskDoP09Ao)</span></p>
  - [Zig Roadmap 2023 - Andrew Kelley](https://www.youtube.com/watch?v=AqDdWEiSwMM) <span style="float:right;">![Views](https://img.shields.io/youtube/views/AqDdWEiSwMM)</span></p>
  - [The Road to Zig 1.0 - Andrew Kelley - YouTube](https://www.youtube.com/watch?v=Gv2I7qTux7g) <span style="float:right;">![Views](https://img.shields.io/youtube/views/Gv2I7qTux7g)</span></p>
  - [Zig language:a WAY better C! - YouTube](https://www.youtube.com/watch?v=J6ZxxnSp_fY) <span style="float:right;">![Views](https://img.shields.io/youtube/views/J6ZxxnSp_fY)</span></p>
  - [Zig Programming Language - YouTube](https://www.youtube.com/watch?v=ygfGO5n1Oe4) <span style="float:right;">![Views](https://img.shields.io/youtube/views/ygfGO5n1Oe4)</span></p>
  - [Zig SHOWTIME - YouTube](https://www.youtube.com/channel/UC2EQzAewrC10KCDFSS4j-zA) <span style="float:right;">![Views](https://img.shields.io/youtube/channel/views/UC2EQzAewrC10KCDFSS4j-zA)</span></p>
  - [Zig Star History](https://star-history.com/#ziglang/zig&Date)

- ### Learning

  - [Learning the Zig programming language with help from its creator and core team - YouTube](https://www.youtube.com/watch?v=O4UYT-brgrc) <span style="float:right;">![Views](https://img.shields.io/youtube/views/O4UYT-brgrc)</span></p>
  - [learnopengl🗒️https://learnopengl.com tutorials ported to zig](https://github.com/cshenton/learnopengl)
  - [libc-to-zig🗒️Comparison between libc functions and their best fitting zig alternatives](https://github.com/zig-community/libc-to-zig)
  - [What's a Memory Allocator Anyway? - Benjamin Feng](https://www.youtube.com/watch?v=vHWiDx_l4V0) <span style="float:right;">![Views](https://img.shields.io/youtube/views/vHWiDx_l4V0)</span></p>
  - [zig-by-example.github.io🗒️learn Zig, by example](https://github.com/zig-by-example/zig-by-example.github.io)
  - [Zig Compiler Internals - Andrew Kelley](https://www.youtube.com/watch?v=8MbREuiLQrM) <span style="float:right;">![Views](https://img.shields.io/youtube/views/8MbREuiLQrM)</span></p>
  - [zig.internals🗒️An Unofficial Writeup on Zig Compiler Internals](https://github.com/mikdusan/zig.internals)
  - [Zig Language Reference](https://ziglang.org/documentation/master/)
  - [ziglearn🗒️Repo for https://ziglearn.org content. Get up to speed with Zig quickly](https://github.com/Sobeston/ziglearn)
  - [ziglings🗒️Learn the Zig programming language by fixing tiny broken programs](https://github.com/ratfactor/ziglings)
  - [Zig Programming Language Tutorials](https://www.youtube.com/watch?v=fQ08HMZLbCw&list=PLRMNjZSQLv5iGpjubyzlWYcGqiTPVyK3s) <span style="float:right;">![Views](https://img.shields.io/youtube/views/fQ08HMZLbCw)</span></p>
  - [Zig Standard Library Documentation](https://ziglang.org/documentation/master/std/)
  

# The End
