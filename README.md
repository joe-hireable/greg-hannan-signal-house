# Greg Hannan — Signal House

A tactile television portfolio. Nine named channels lead into project case studies.

- [Open this portfolio](https://joe-hireable.github.io/greg-hannan-signal-house/)
- [Compare all three concepts](https://joe-hireable.github.io/greg-hannan-signal-house/concepts/)
- [Figma design boards](https://www.figma.com/design/pVYdGife89N11xGKTnV9Zq)

## Design

Archivo Black, IBM Plex Mono and DM Sans; warm ivory, terracotta and signal green.

This is a working portfolio concept for a front-end developer. Project summaries and contributions come from Greg’s CV and published GitHub work. Images are October 2026 website captures. The Greg Hannan Studio image is a labelled architecture illustration of the 2022 Gatsby/Medusa build, based on the published source. It is not a historical screenshot.

## Edit the website

The complete site is in `index.html`: HTML for the page, CSS in the `<style>` block, and JavaScript in the final `<script>` block. There is no build tool, dependency installation or paid CMS.

1. Open `index.html` in the GitHub file editor, or clone the repository and edit locally.
2. Update the project records in the `projects` array (or `project-data` JSON block): name, date, stack, URL, category, summary and contribution bullets. Keep summaries specific to Greg’s actual contribution.
3. Replace images in `assets/`, retaining their filenames, or update the project slug and image reference together. Images are JPEGs.
4. Update the introduction, contact links and CV link in the HTML. The CV currently links to the supplied public PDF; replace the link when the CV changes.
5. Change the CSS variables near the top of the file to adjust the palette. Fonts use Google Fonts with local fallback families.
6. Commit to `main`. GitHub Pages publishes the updated files automatically.

The navigation currently covers nine projects. When adding or removing a project, update the total labels, range maximum and any fixed counts alongside the records. Preserve the keyboard controls, visible focus and reduced-motion rules.

For a quick local review, open `index.html` in a browser. To use a local web server, run `python -m http.server 8000` from this repository and open `http://localhost:8000`. Check the site at desktop and mobile widths, select every project, open and close the case-study window, and follow the project/CV links.

## Hosting

GitHub Pages serves `main` from the repository root. Keep `.nojekyll` in place so the static files are served directly. Under **Settings → Pages**, the source is **Deploy from a branch**, branch **main**, folder **/(root)**. The Pages build/deployment appears in the Actions tab.

[GitHub Pages is available for public repositories on GitHub Free](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages). This repository has no server, secret, paid service integration or domain purchase.

## Transfer this repository to Greg

The current owner can transfer the repository through **Settings → General → Danger Zone → Transfer** when Greg is ready. Enter Greg’s GitHub username, `gregorymark`, confirm the repository name and complete GitHub’s confirmation flow. Greg must accept the transfer invitation; GitHub says personal-account transfer invitations expire after one day. The receiving account must not already have a repository with the same name.

After transfer:

1. Greg should check **Settings → Pages** and wait for the first successful deployment.
2. The default site URL will use the new owner, typically `https://gregorymark.github.io/greg-hannan-signal-house/`. Update the concept hub, Concepts links and README URLs across all three repositories from the old owner to the new owner.
3. Update local clones with `git remote set-url origin https://github.com/gregorymark/greg-hannan-signal-house.git`.
4. Review repository access. GitHub normally retains the original owner as a collaborator after a personal-account transfer.

Repository links redirect after transfer, but **GitHub Pages URLs do not**. No ownership transfer has been initiated. [Official transfer documentation](https://docs.github.com/en/repositories/creating-and-managing-repositories/transferring-a-repository).

## Content and asset rights

The portfolio describes Greg’s development contribution; it does not claim he created every client’s brand, photography or underlying platform. Client screenshots and trademarks remain attributable to their respective owners. Source publication does not grant a licence to reuse third-party client imagery.

## Search visibility

These three sites are concept previews and carry a `noindex,follow` robots meta tag. When Greg selects a final portfolio for search indexing, remove that tag from `index.html` and retain one primary portfolio URL.
