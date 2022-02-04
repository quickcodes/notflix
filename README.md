<h1 align="center">NOTFLIX for noobs</h1>
<h2 align="center">A fork of notflix by [quickcodes](https://github.com/quickcodes/) </h2>
<h3 align="center">Watch almost any content available on internet for free as the original but with some quality of life improvements such as automatic dependency installation</h3>



## Requirements

* [npm](https://www.npmjs.com/) - The tool needed to install webtorrent. `sudo apt install npm` or `sudo pacman -S npm` if you are using an Arch based distro.
* [webtorrent](https://webtorrent.io/) - A tool to stream torrent. The tool that makes this possible. `sudo npm install webtorrent-cli -g`
* [mpv](https://mpv.io/) - If you don't know about mpv, you are probably new to linux. A very powerful video player `sudo apt install mpv` or `sudo pacman -S mpv` if you are using an Arch based distro.

## Installation

### cURL
cURL **notflix** to your **$PATH** and give execute permissions.

```sh
$ sudo curl -sL "https://raw.githubusercontent.com/wallmenis/notflix/main/notflix" -o /usr/local/bin/notflix
$ sudo chmod 777 /usr/local/bin/notflix
```
- To update, just do `curl` again, no need to `chmod` anymore.
- To uninstall, simply remove `notflix` from your **$PATH**, for example `sudo rm -f /usr/local/bin/notflix`.

## License
This project is licensed under [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).


