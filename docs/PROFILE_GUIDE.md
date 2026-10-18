# Edit or restore this portfolio

This repository controls the portfolio shown on [github.com/moizZM](https://github.com/moizZM). The personal website is separate.

## Make a small edit in GitHub

1. Open [the profile README](https://github.com/moizZM/moizZM/blob/main/README.md).
2. Select the pencil (**Edit this file**).
3. Change the text, select **Preview**, then **Commit changes** to save it to `main`.

Project descriptions are in [`portfolio/projects`](../portfolio/projects). The [project index](../portfolio/README.md) lists all 15 projects. Images and button graphics are in [`assets/portfolio`](../assets/portfolio).

## Change the featured projects

The **Projects to start with** section in `README.md` contains three `<tr>...</tr>` rows. Each row has a picture, title, contribution, result and link. Copy a complete row to add a project, or remove a complete row to stop featuring it. The project itself stays in the project index.

For example, the restricted-area-monitor page is `portfolio/projects/restricted-area-monitor.md` and its picture is `assets/portfolio/restricted-area-monitor.jpg`.

## Hide or restore a section

GitHub profiles do not have the website's owner dashboard or live switches. To hide a section, edit `README.md` and put `<!--` before its heading and `-->` after its final line. Remove these markers to show it again. Remove its matching navigation link while it is hidden.

Keep a copy of any content you remove. GitHub's **History** also retains earlier committed versions.

## Restore the profile from before this update

The exact earlier README is saved in [README-before-2026-10-18.md](README-before-2026-10-18.md). A backup branch, [before-portfolio-2026-10-18](https://github.com/moizZM/moizZM/tree/before-portfolio-2026-10-18), preserves the repository before the update.

To restore the visible profile using only GitHub:

1. Open the [previous README as raw text](https://github.com/moizZM/moizZM/raw/refs/heads/main/docs/README-before-2026-10-18.md) and copy all of it.
2. Open [the current README editor](https://github.com/moizZM/moizZM/edit/main/README.md).
3. Replace its contents with the copied text. Preview it and commit the change.

Your old profile will be shown again. The new project pages remain in the repository so you can reuse them. Merely switching branches in the repository does **not** change the public profile; the README on `main` controls it.

## Images and documents

Pictures are stored directly in this repository and do not depend on the personal website being reachable. The original proportions are preserved; portrait project pictures are not forced into a landscape crop.

The PCB and FPGA robot pages link to work that was already in public repositories. Reference letters and restricted employer/research files were not copied into this public repository. Public GitHub content does not provide the website's per-link access controls or revocation.

To add a new PDF that you intend to publish, upload it to this repository and add a Markdown link to it from the relevant project page. Visitors can use their browser's Back button to return. GitHub renders documents with its own viewer.

## Content notes

The work timeline follows the owner's portfolio dates, including the confirmed August 2026 move to Systems Engineering. Project descriptions distinguish individual contributions from team results.
