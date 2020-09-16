# devconf

Contains my common config files to make a nice looking dev machine.

## What's included?

It is made for an ubuntu/ubuntu-derived enviroment (like xubuntu) and has been tested on `ubuntu`, `kubuntu` and `linux mint`. The following apt packages are installed when ran:

- [python3](https://python.org)
- [code](https://code.visualstudio.com/)
- [git](https://git-scm.com/)
- [vim](https://en.wikipedia.org/wiki/Vim_(text_editor))
- [make](https://en.wikipedia.org/wiki/Make_(software))
- [build-essential](https://packages.debian.org/bullseye/build-essential)
- [wget](https://en.wikipedia.org/wiki/Wget)
- [curl](https://en.wikipedia.org/wiki/CURL)
- [fontconfig](https://en.wikipedia.org/wiki/Fontconfig)
- [zsh](https://en.wikipedia.org/wiki/Z_shell)
- [neofetch](https://github.com/dylanaraps/neofetch)
- [zip](https://packages.debian.org/bullseye/zip)
- [unzip](https://packages.debian.org/buster/unzip)
- [python3](https://en.wikipedia.org/wiki/Python_(programming_language))
- [python3-dev](https://packages.debian.org/bullseye/python3-dev)
- [transmission-gtk](https://en.wikipedia.org/wiki/Transmission_(BitTorrent_client))

And the following non-apt items are also installed:

- [`hack` font](https://sourcefoundry.org/hack/)
- [powerlevel10k zsh theme](https://github.com/romkatv/powerlevel10k)
- [oh-my-zsh (`zsh` plugin manager)](https://ohmyz.sh/)
- [Rust + Cargo (via `rustup`)](https://en.wikipedia.org/wiki/Rust_(programming_language))
- [Jupyter notebook + `nb` zsh alias](https://jupyter.org/)

## Running

Simply run `./devconf.sh`. This is made for specifically ubuntu and it's derivatives (linux mint, kubuntu, xubuntu) but (should) work on debian. Make sure to change out the "Add git username/passwords" in the `devconf.sh` file or you'll be commiting using my email for git!

## Extras

You may install extra field specfic tools by running one or more of the following scripts:

- `bash pentesting.sh`: Common pentesting tools (focused on wireless)
