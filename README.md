# Algorave poster wall

Upload everything in this folder to the root of the `dik-rave-promo` repository,
replacing the old index.html. Keep the folder structure exactly as it is:

    index.html          the page (small, so LinkedIn can read its preview tags)
    thumbs.js           snapshots of all 40 posters for the wall
    posters/            one file per student: their sketch code, images, fonts
    og-image.jpg        the 1200x630 link-preview image
    apple-touch-icon.png, favicon-32.png

Each poster file is loaded only when someone opens that poster.

## After uploading

Paste https://austinfranklin.github.io/dik-rave-promo/ into LinkedIn Post
Inspector (linkedin.com/post-inspector) to refresh LinkedIn's cached copy.

## If you change something later

Bump the version number `20261103` in index.html (it appears in a few places)
so visitors' browsers fetch the new files instead of cached ones.
