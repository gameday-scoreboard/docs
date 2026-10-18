# Game Day Scoreboard docs, publisher

This repo publishes [docs.gameday-scoreboard.com](https://docs.gameday-scoreboard.com/) with GitHub Pages. It holds no pages of its own.

The pages live in the firmware repo, [gameday-scoreboard/gameday-scoreboard](https://github.com/gameday-scoreboard/gameday-scoreboard), under `docs/wiki`, next to the code they describe. To fix or add a page, open a pull request there; its README explains the layout.

The Publish workflow here checks the firmware repo's `main` branch every 15 minutes, builds the site when `main` has moved since the last publish, and deploys it. Run it by hand from the Actions tab to publish right away.
