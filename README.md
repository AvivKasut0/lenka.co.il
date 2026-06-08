# lenka.co.il

A joke website. One image. Bounces around the screen like a DVD screensaver.

**Live:** [lenka.co.il](https://lenka.co.il)

## What it does

- The image bounces around the screen
- Changes color on every wall hit
- Corner hit → confetti explosion

## Adding images

Drop image files into the `images/` folder, then add the filename to the array at the top of `index.html`:

```js
const IMAGES = [
  'images/dvirbride.png',
  'images/yournewimage.png', // ← add here
];
```

One image is picked at random on each page load.

## Stack

Plain HTML, CSS, and JavaScript. No build step, no dependencies.

## Deployment

Hosted on [Cloudflare Pages](https://pages.cloudflare.com) — auto-deploys on push to `master`.
