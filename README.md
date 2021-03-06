SublimeLinter-contrib-credo
================================

[![Build Status](https://travis-ci.org/mintcore/SublimeLinter-contrib-credo.svg?branch=master)](https://travis-ci.org/mintcore/SublimeLinter-contrib-credo)

This linter plugin for [SublimeLinter][docs] provides an interface to [credo](https://github.com/rrrene/credo). It will be used with files that have the “.ex” syntax.

## Installation
SublimeLinter 3 must be installed in order to use this plugin. If SublimeLinter 3 is not installed, please follow the instructions [here][installation].

### Linter installation
Before using this plugin, you must ensure that `credo` is installed on your system. To install `credo`, do the following:

```
$ git clone git@github.com:rrrene/bunt.git
$ cd bunt
$ mix archive.build
$ mix archive.install
$ cd -
$ git clone git@github.com:rrrene/credo.git
$ cd credo
$ mix deps.get
$ mix archive.build
$ mix archive.install
```

**Note:** This plugin requires `credo` 0.6.1 or later.

### Plugin installation
Please use [Package Control][pc] to install the linter plugin. This will ensure that the plugin will be updated when new versions are available. If you want to install from source so you can modify the source code, you probably know what you are doing so we won’t cover that here.

To install via Package Control, do the following:

1. Within Sublime Text, bring up the [Command Palette][cmd] and type `install`. Among the commands you should see `Package Control: Install Package`. If that command is not highlighted, use the keyboard or mouse to select it. There will be a pause of a few seconds while Package Control fetches the list of available plugins.
2. When the plugin list appears, type `credo`. Among the entries you should see `SublimeLinter-contrib-credo`. If that entry is not highlighted, use the keyboard or mouse to select it.

To install as a local package, do the following:

1. Clone the repository via `git clone git@github.com:mintcore/SublimeLinter-contrib-credo.git`
2. Point to it via `ln -s` from the `~/Library/Application Support/Sublime Text 3/Packages/` folder
3. Withing Sublime Text, open the [Command Palette][cmd] and choose *Package Control: Install local dependency*


## Contributing
If you would like to contribute enhancements or fixes, please do the following:

1. Fork the plugin repository.
2. Hack on a separate topic branch created from the latest `master`.
3. Commit and push the topic branch.
4. Make a pull request.
5. Be patient.  ;-)

Please note that modifications should follow these coding guidelines:

- Indent is 4 spaces.
- Code should pass flake8 and pep257 linters.
- Vertical whitespace helps readability, don’t be afraid to use it.
- Please use descriptive variable names, no abbreviations unless they are very well known.

Thank you for helping out!

[docs]: http://sublimelinter.readthedocs.org
[installation]: http://sublimelinter.readthedocs.org/en/latest/installation.html
[locating-executables]: http://sublimelinter.readthedocs.org/en/latest/usage.html#how-linter-executables-are-located
[pc]: https://sublime.wbond.net/installation
[cmd]: http://docs.sublimetext.info/en/sublime-text-3/extensibility/command_palette.html
[settings]: http://sublimelinter.readthedocs.org/en/latest/settings.html
[linter-settings]: http://sublimelinter.readthedocs.org/en/latest/linter_settings.html
[inline-settings]: http://sublimelinter.readthedocs.org/en/latest/settings.html#inline-settings
