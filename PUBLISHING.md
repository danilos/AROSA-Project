# Private-source-safe publication procedure

**Destination:** a new, separate, PUBLIC GitHub repository under `danilos` named `AROSA-Project` (or another intentionally chosen public documentation name).

1. On GitHub select **New repository**. Set owner `danilos`, name `AROSA-Project`, description `Independent capability-oriented application platform for AROS — vision, roadmap and community feedback.` Set visibility **Public**. Do not import or fork the existing private `AROSA` or `ATransferService` repositories. Creating an empty repo without README avoids merge conflicts.
2. Upload the **contents of this folder** to the root of the new repository. Do not upload the containing `AROSA-GitHub-Public-Site` folder itself. Keep `.github` and `docs` directories.
3. Under **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/docs`, and save. The site will be published at `https://danilos.github.io/AROSA-Project/` if GitHub Pages is enabled for that repository.
4. Under **Settings → General → Features**, ensure **Issues** is enabled. Set default labels `bug`, `enhancement` and `documentation` (these commonly exist on GitHub). Configure Discussions only if desired.
5. Under **About** (right side of repository home), set description and website to the published Pages URL. Suggested topics: `aros`, `amiga`, `application-platform`, `capabilities`, `service-architecture`, `desktop-environment`.
6. Test all pages and links, README, issue forms, and mobile layout. Check that the new repository contains **no source folders, sensitive artifacts, private internal URLs, secrets or unrelated git history**.
7. Do not enable automatic sync from private Gitea issues to the public GitHub site. Publish sanitized, deliberate summaries only. Protect unpublished licenses and third-party source notices.
8. Announce the public page only when it is visible and checked. Do not claim there is a production release or open-source distribution.

NOTE: The linked GitHub app currently does not expose a repository-creation action, so a new repository must be created in the GitHub UI before the files can be published through that app. The package intentionally contains documentation and static assets only.
