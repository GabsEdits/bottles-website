# Bottles Website - Edits by Gabs during High Seas

The changes made by me (Gabs), to Bottles' website during High Seas.

## Changes by me

### Pay What You Want System

- **Pull Request**: [#76](https://github.com/bottlesdevs/website/pull/76)

- **Description**: In the download page, it will ask you to make a donation, and the option to go to flathub without any donation by writing “0” in the custom amount input. If you make a donation, then it will open a new tab with paypal, will create a 24 hour cookie locally noting that you have made a donation, and will redirect you to flathub. If you open again the page and the cookie is present, then you won't need the popup, it will be a direct link.

### Dark images for dark theme for hero

- **Pull Request**: [#75](https://github.com/bottlesdevs/website/pull/75)

- **Description**: Added dark images for the hero section, so that the website looks better in dark mode. The images are loaded based on the user's theme preference.

### Bad contrast on appstore page on hover

- **Pull Request**: [#74](https://github.com/bottlesdevs/website/pull/74)

- **Description**: Fixed the bad contrast on the appstore page when hovering over the install buttons.

### Random app name on the placeholder of the search bar in the appstore page

- **Pull Request**: [#73](https://github.com/bottlesdevs/website/pull/73)

- **Description**: Added a random app name on the placeholder of the search bar in the appstore page.

### Make all arrays inline

- **Pull Request**: [#72](https://github.com/bottlesdevs/website/pull/72)

- **Description**: Made all arrays inline in the codebase.

### Exit popup on esc key in the download page

- **Pull Request**: [#71](https://github.com/bottlesdevs/website/pull/71)

- **Description**: Added the ability to close the popup on the download page by pressing the escape key.

---

## Original README

This is the official Bottles website.

## Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`             | Installs dependencies                            |
| `pnpm run dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm run build`           | Build your production site to `./dist/`          |
| `pnpm run preview`         | Preview your build locally, before deploying     |
| `pnpm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm run astro -- --help` | Get help using the Astro CLI                     |

It's recommended to use `pnpm` as the package manager.

## License

All the code in this repository is licensed under the AGPL-3.0 license. The Bottles brands, logos, posts and other assets are not licensed under the AGPL-3.0 license and are under the ownership of Bottles. Third-party assets are licensed under their respective licenses.
