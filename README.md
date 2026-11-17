# Glide icons

The icon theme of the [Glide desktop](https://github.com/Glide-Desktop/glide),
packaged as `glide-icon-theme`.

It is based on the [Colloid icon theme](https://github.com/vinceliuice/Colloid-icon-theme)
by Vince Liu (vinceliuice), GPL-3.0, taken at upstream commit
`ceac6608` (2026-08-29) with its history kept. The upstream README is kept as
[UPSTREAM-README.md](UPSTREAM-README.md). Glide changes it bit by bit from here;
upstream changes are merged by hand.

The themes keep Colloid's names (`Colloid`, `Colloid-<Accent>`,
`Colloid-<Accent>-Dark`, `Colloid-<Accent>-Light`), because the Glide shell picks
the variant for the appearance and accent by those names.

## Package

`data/arch/glide-icon-theme/PKGBUILD` runs `install.sh -t all` into the package
(every accent, the default scheme only). A `v*` tag builds it in CI and attaches
it to the release, and the next Glide release puts it into the pacman
repository at `pkg.mindenit.org`.

License: GPL-3.0 (see [LICENSE](LICENSE)).
