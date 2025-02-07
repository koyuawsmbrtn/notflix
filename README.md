# NOTFLIX

<p align="center">f@#k netflix use notflix a tool which searches magnet links and streams it with peerflix</p>

---

**Notice:** Always [use a VPN](https://mullvad.net) or you'd get your house raided for using this script :3

### How does this work?

This is a shell script. It scrapes 1337x and gets the magnet link.
After this it uses [peerflix](https://github.com/mafintosh/peerflix) to stream the video from the magnet link.
For scraping it uses the GNU utilities like sed, awk, paste and cut.

## Requirements

* npm (can be installed through [nvm](https://github.com/nvm-sh/nvm?tab=readme-ov-file#install--update-script))
* [peerflix](https://github.com/mafintosh/peerflix) - A tool to stream torrents: `npm i -g peerflix`

## Installation

### curl
curl **notflix** to your **$PATH** and give executable permissions.

```sh
$ sudo curl -sL "https://raw.githubusercontent.com/koyuawsmbrtn/notflix/master/notflix" -o /usr/local/bin/notflix
$ sudo chmod +x /usr/local/bin/notflix
```
- To update, just do `curl` again, no need to `chmod` anymore.
- To uninstall, simply remove `notflix` from your **$PATH**, for example `sudo rm -f /usr/local/bin/notflix.

## License
This project is licensed under [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).

