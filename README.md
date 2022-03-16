![bash_unit CI](https://github.com/pforret/xkcd/workflows/bash_unit%20CI/badge.svg)
![Shellcheck CI](https://github.com/pforret/xkcd/workflows/Shellcheck%20CI/badge.svg)
![GH Language](https://img.shields.io/github/languages/top/pforret/xkcd)
![GH stars](https://img.shields.io/github/stars/pforret/xkcd)
![GH tag](https://img.shields.io/github/v/tag/pforret/xkcd)
![GH License](https://img.shields.io/github/license/pforret/xkcd)
[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://basher.gitparade.com/package/)

# xkcd

View a XKCD comic in your console. Works with [Kitty](https://sw.kovidgoyal.net/kitty/) and [iTerm2](https://iterm2.com/)

inspired by [Read XKCD in the terminal with some bash magic](https://www.roboleary.net/2022/02/24/xkcd-in-the-terminal-with-some-bash-magic.html)

## 🔥 Usage

```
Description: View a XKCD comic in your console
Usage: xkcd [-h] [-q] [-v] [-f] [-l <log_dir>] [-t <tmp_dir>] <action>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] output more [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: /Users/pforret/log/xkcd]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: /tmp/xkcd]
    <action>         : [parameter] action to perform: last/random

### TIPS & EXAMPLES
* use xkcd last to view last/latest XKCD comic
* use xkcd random to view random XKCD comic
* use xkcd check to check if this script is ready to execute and what values the options/flags are
  xkcd check
* use xkcd env to generate an example .env file
  xkcd env > .env
* use xkcd update to update to the latest version
  xkcd update
* >>> bash script created with pforret/bashew
* >>> for bash development, also check out pforret/setver and pforret/progressbar
```

## 🚀 Installation

with [basher](https://github.com/basherpm/basher)

	$ basher install pforret/xkcd

or with `git`

	$ git clone https://github.com/pforret/xkcd.git
	$ cd xkcd

## 📝 Acknowledgements

* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2022 Peter Forret
