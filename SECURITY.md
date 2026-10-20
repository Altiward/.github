# Security policy

## Reporting a vulnerability

Please don't open a public issue or Discussion for a security problem. Report it privately,
in either of these ways:

- **GitHub private vulnerability reporting** on the affected repository: open its
  **Security** tab and choose **Report a vulnerability**. For the server, agent and
  console, that is
  [Altiward/altiward](https://github.com/Altiward/altiward/security/advisories/new).
- **Email** [hello@altiward.com](mailto:hello@altiward.com). If you're not sure which
  repository is affected, use this.

Include what you found, the version, how to reproduce it, and what you think an attacker
could do with it. Please don't include real user names, Mac details or secrets from
your own fleet.

## What to expect

- We acknowledge your report within 5 working days.
- We confirm whether we can reproduce it, and keep you informed while we work on a fix.
- We release the fix, and publish a security advisory that credits you if you wish.

## Coordinated disclosure

We ask you to keep the details private until a fix is released, or until we agree a date
with you, and we'll work with you on the timing. Please test only against systems you
own, and avoid other people's data.

## Supported versions

Fixes go to the latest two minor versions of the Altiward server and agent, and to the
latest release of altiward-forwarder.

| Component | Supported |
| --- | --- |
| Altiward server | Latest two minor versions |
| Altiward agent | Latest two minor versions |
| altiward-forwarder | Latest release |

Versions follow [semantic versioning](https://semver.org), with a new minor about each
quarter, so a minor version is supported for about six months. If you run an older
version, upgrade first; the install guide covers
[upgrades](https://github.com/Altiward/altiward/blob/main/docs/install.md).
