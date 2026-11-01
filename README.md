# annasabou.com

Anna's games website, built with [Astro](https://astro.build) and published to GitHub Pages on every push to `main`.

## Run it locally

```sh
npm install
npm run dev
```

## Add a game

Add a line to `src/data/games.ts` with the game's title and address. A game published elsewhere uses its full address. A game hosted here goes in `public/games/<folder>/`, with an `index.html` as its starting page, and uses `games/<folder>/` as its address.

Keep real photos and personal details out of this repo. It's public.
