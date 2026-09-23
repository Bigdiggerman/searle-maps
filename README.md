# maps-site

Local checkout of the `Bigdiggerman/searle-maps` repository that Cloudflare
Pages serves at https://maps.forestrysales.co.nz. One folder per property
(`<slug>/`), each a mirror of that property's `Claude/map/dist/`, written by
`publish_web.py` at the end of every `release.py`.

Do not edit the property folders by hand - the next release overwrites them.
`site.json` holds the site-wide settings the property-map skill reads
(`references/cloudflare.md` in the skill explains each).
