# Contributing to MMFoundation

MMFoundation makes free, open-source apps for the Mac. Each app lives in its own
repository, with its own build steps and tests. This page covers what holds for all
of them, and where to go for each one.

Everyone taking part follows the [code of conduct](CODE_OF_CONDUCT.md).

## Where things go

| | WallpaperMachine | OhMyShot |
|---|---|---|
| Report a bug or ask for a feature | [Issues](https://github.com/MMFoundation/WallpaperMachine/issues) | [Issues](https://github.com/MMFoundation/OhMyShot/issues) |
| Build it and send a change | [CONTRIBUTING.md](https://github.com/MMFoundation/WallpaperMachine/blob/main/CONTRIBUTING.md) | [README, Contributing](https://github.com/MMFoundation/OhMyShot#contributing) |
| Translate it | [Crowdin](https://translate.wallpapermachine.app/project/wallpaper-machine) | [Docs/localization.md](https://github.com/MMFoundation/OhMyShot/blob/main/Docs/localization.md) |

Questions, ideas, and anything that spans more than one project go to the
organization's [Discussions](https://github.com/orgs/MMFoundation/discussions) or its
[Discord](https://mmfoundation.dev/discord).

## Vulnerabilities

Report a vulnerability privately, never in a public issue, discussion or pull
request. WallpaperMachine takes private reports on its Security tab, as its
[SECURITY.md](https://github.com/MMFoundation/WallpaperMachine/blob/main/SECURITY.md)
describes. For a project without a security policy, open an issue that asks the
maintainers for a private way to send it, and leave the details out.

## Pull requests

- Read the project's own guide first: build steps, tests, and the checks a change
  needs differ between the apps.
- Keep a pull request to one change, and say what you verified and what you didn't.
- Both apps write commit messages as [Conventional Commits](https://www.conventionalcommits.org)
  (`fix(scope): …`, `feat(scope): …`). WallpaperMachine also asks you to sign off
  your commits (`git commit -s`), as its guide explains.

## License

Every MMFoundation app is free software under the GNU General Public License,
version 3. By contributing you agree that your contribution is licensed under the
same terms as the project you contribute to, and that it carries no code you may not
license that way.

## Supporting the work

Not writing code? Starring the repositories helps other Mac users find them, and
sponsorships go through [Open Collective](https://opencollective.com/mmfoundation),
where every contribution and every expense is public.
