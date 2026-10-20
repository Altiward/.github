# Contributing to Altiward

Thank you for helping. Altiward is open source under the Apache License 2.0, and
contributions are welcome: bug reports, fixes, documentation and features. This is the
general guide for every repository in the organisation. Each repository's own guide adds
how to build and test it.

## Before you start

For anything bigger than a small fix, open an issue or start a
[Discussion](https://github.com/Altiward/altiward/discussions) first. It saves you from
building something that doesn't fit the design.

## Sign off your commits (DCO)

Altiward uses the [Developer Certificate of Origin](https://developercertificate.org)
instead of a contributor licence agreement. Add a sign-off to every commit:

```sh
git commit -s -m "Fix the thing"
```

This adds a `Signed-off-by: Your Name <you@example.com>` line. It certifies that you wrote
the change, or have the right to submit it, under the project's open source licence, and
that you understand the contribution is public and kept on record. Forgot? Run
`git commit --amend -s` for the last commit, or `git rebase --signoff main` for a branch.
Pull requests with unsigned commits can't be merged.

## Pull requests

Keep a pull request to one change, and say in it what and why, and how you tested it.

## Be kind

Everyone taking part is expected to follow the [Code of Conduct](https://github.com/Altiward/.github/blob/main/CODE_OF_CONDUCT.md).

## Each repository's guide

- [altiward](https://github.com/Altiward/altiward/blob/main/CONTRIBUTING.md): agent,
  server and console
- [altiward-forwarder](https://github.com/Altiward/altiward-forwarder/blob/main/CONTRIBUTING.md):
  the relay and the on-Mac hook
- [altiward-siem](https://github.com/Altiward/altiward-siem/blob/main/CONTRIBUTING.md):
  detections, hunting queries and saved searches, and the checks they pass
- [altiward.com](https://github.com/Altiward/altiward.com/blob/main/CONTRIBUTING.md):
  website content, local preview and shared assets
- [Organisation files](README.md): profile, default community files and exported images

## Reporting a security problem

Please don't open a public issue. See the [security policy](https://github.com/Altiward/.github/blob/main/SECURITY.md).
