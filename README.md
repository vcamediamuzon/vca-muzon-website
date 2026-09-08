# VCA Muzon Website

Production website for Victory Churches of Asia - Muzon.

https://yzcreativetech.github.io/vca-muzon-website/

## Deployment

The static HTML, CSS, JavaScript, and assets are published through GitHub Pages
from the production repository `yzcreativetech/vca-muzon-website`.

## Progress

- [x] About Hero Video milestone
  - Replaced the About page static hero presentation with a looping drone video.
  - Retained the existing church image as the poster and fallback.
  - Tuned responsive video framing to `62% center` on desktop, `66% center` on
    tablets and mobile devices, and `72% center` on small phones.
  - Preserved autoplay compatibility with `muted`, `playsinline`, and `loop`.
  - Preserved reduced-motion accessibility by hiding the video and displaying
    the fallback image when reduced motion is requested.
  - Removed obsolete About hero background styles, empty portrait-tablet media
    queries, and duplicate CSS declarations.

## Release notes

### About Hero Video

The About page now uses responsive drone footage in its hero area while keeping
the original church image as a reliable poster and accessibility fallback. The
associated stylesheet cleanup consolidates superseded component rules and
removes empty responsive blocks. Validation confirmed balanced CSS braces and a
clean `git diff --cached --check` result before publication.
