# Home-page logo layers

These vector assets are derived from `../thanatology.svg` and `../exhume.svg`.
The original artwork remains in those source files.

The Thanatology export omits the hidden embedded reference image and editor
metadata. Its shared wing layer is split at the original paths: `path134` and
`path139` join `g81` on the left; `path124` and `path129` join `g119` on the right.
The original gradients and back-to-front paint order are preserved.

The Exhume export separates the shovel from the ground line (`rect119`) and
binary characters (`text122`). Both exports add room around the artwork for motion.

The `data-part` attributes identify the animated groups. Animation and reduced-motion
rules live in `src/components/HomepageFeatures/styles.module.css`.
