# Brook's Nautilus

This is the file manager shipped with [Brook](https://github.com/IanNorris/Brook),
a hobby x86-64 operating system. It is GNOME Files (Nautilus), unchanged
except for the commits on this `brook` branch, which start from the upstream
`49.4` release tag.

- Upstream: https://gitlab.gnome.org/GNOME/nautilus
- Licence: GPL-3.0-or-later, as upstream (see `LICENSE`). Brook's changes
  are under the same licence.
- The About dialog, credits and licence text are upstream's and are not
  modified.

Brook prefers configuration (GTK settings, CSS, desktop entries) over source
changes; patches here are kept small and separate so upstream releases can be
merged.
