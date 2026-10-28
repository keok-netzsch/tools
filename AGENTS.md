# tools: rules for any model working here

This repo is the published copy of a generated site. Nothing here is edited by hand.

1. Change the source in the showcase repo, commit it there, then run its publisher: `python tools/publish.py`
   to see what would change, `python tools/publish.py --apply` to publish.
2. The publisher replaces every file except `.git` and this one, and refuses when this folder has uncommitted changes.
3. Every page carries noindex and the root has `robots.txt` with `Disallow: /`. Keep both.
