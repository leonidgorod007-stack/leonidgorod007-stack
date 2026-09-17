# Profile media

## Current files

- `avatar.jpg` - account avatar, ready for GitHub's circular crop (`735 × 702`).
- `hero.jpg` - banner currently shown at the top of the profile (`736 × 272`).

The avatar must be uploaded in GitHub account settings; a profile repository
cannot change the account avatar by itself.

## Future animated banner

1. Export the animation as `hero.gif`.
2. Recommended canvas: `1600 × 500` or another ratio close to `3.2:1`.
3. Keep it around `8 MB` or less so the profile loads quickly.
4. Change `./assets/hero.jpg` to `./assets/hero.gif` in the root `README.md`.

Animated GIF, APNG or animated WebP is safer for a GitHub README than embedding
an MP4 player. If the source is video, export a short, seamless loop.

## Optional second image

Name it `lab.png`, place it here, and uncomment the final image block in the
root `README.md`.
