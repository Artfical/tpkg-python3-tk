# python3-tk

tkinter for Python 3.14: the Tk graphical toolkit (needs the X server of the xorg package: tos-x), with turtle

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install python3-tk
```

| | |
|---|---|
| Version | 3.14.10 |
| Licence | PSF-2.0 |
| Upstream | https://docs.python.org/3/library/tkinter.html |
| Needs | [`python3`](https://github.com/Artfical/tpkg-python3), [`tcltk`](https://github.com/Artfical/tpkg-tcltk) |
| Needs tOS build | 618 or newer |
| Size | 223773 bytes (793918 unpacked) |
| SHA-256 of the `.tpkg` | `00d1c5e04fb61a221769ee4438c270bfcc81fb900ef02e155329dc81ac356101` |

## Commands it adds

| Command | Runs |
|---|---|
| - | - |

## Download

The package file (`python3-tk-3.14.10.tpkg`) and the sources it was built from are the assets of the
[v3.14.10 release](https://github.com/Artfical/tpkg-python3-tk/releases/tag/v3.14.10).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `Python-3.14.10.tar.xz`

Check a download: `sha256sum python3-tk-3.14.10.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: PSF-2.0. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
