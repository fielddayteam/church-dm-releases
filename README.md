# Church DM — releases

Downloads only. **No source code lives here.**

This repository exists so that a church that installed Church DM or one of its
add-ons can be told when there is a newer version — and can install one in the
first place. It holds two things:

- a zip per plugin, attached to a tagged release
- `manifest.json`, which lists the current version of each plugin and where to
  download it

An installed site reads `manifest.json` and nothing else. It is a static file
on purpose: GitHub's API allows 60 anonymous requests an hour per IP, and on
shared hosting a church would share that allowance with every other site on the
box.

Both the zips and the manifest are published automatically from the development
repository. Nothing here is edited by hand.

## Who this is for

Nobody needs to visit this page. WordPress reads it on a church's behalf and
offers the update in the usual place, alongside every other plugin.
