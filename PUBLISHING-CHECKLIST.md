# Publishing checklist

The clean MultiMC instance is technically ready for private testing, but it is not yet cleared for public binary redistribution.

## Before a GitHub release

- [ ] Verify the author and redistribution license for every file in `.minecraft/mods`.
- [ ] Verify the author and redistribution license for every file in `jarmods`.
- [ ] Verify redistribution permission for Tymix and Dokumpletion.
- [ ] Document the source URL and license for every included third-party binary.
- [ ] Separate original mods from custom patched builds.
- [ ] Publish source or patch documentation for custom code where its upstream license requires it.
- [ ] Confirm that no Mojang game jar, account file, world, log, statistic, or personal screenshot is included.
- [ ] Replace any binary that cannot be redistributed with an installer step or archival download instruction.
- [ ] Add complete author credits to the public project page.

## Before a CurseForge submission

- [ ] Create a valid CurseForge `manifest.json` and `overrides` directory package.
- [ ] Reference CurseForge-hosted mods through the manifest instead of bundling their jars.
- [ ] Check every off-site mod against CurseForge's Approved Non-CurseForge Mods list.
- [ ] Submit eligible missing mods for third-party review with an official download and open-use license.
- [ ] Remove any unapproved, unlicensed, or undocumented derivative binary.
- [ ] Provide a square project avatar at least 400×400 pixels.
- [ ] Provide a clear one-line summary and a full preservation-focused description.
- [ ] List and credit every non-CurseForge mod in the project description.

## Current blockers

- Many 2011–2012 mods have unclear or unavailable licenses.
- Several files are repaired builds rather than untouched original downloads.
- The custom Reptile and HarvestCraft ports require an explicit derivative-work/license review.
- The sound resources and texture packs require their own redistribution review.

Until these are resolved, share the documentation and source/patch work rather than uploading the complete binary pack publicly.

## Current CurseForge guidance

- [Exporting a Modpack for CurseForge Project Submission](https://support.curseforge.com/en/support/solutions/articles/9000197908-exporting-a-modpack-for-curseforge-project-submission)
- [Non-CurseForge Mods policy](https://support.curseforge.com/support/solutions/articles/9000197913-non-curseforge-mods)
