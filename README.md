# Altiward organisation files

This repository holds the organisation profile and default contributor information.

```text
.github/
├── profile/README.md       Public organisation profile
├── profile/images/         Exported logos and console screenshot
├── .github/ISSUE_TEMPLATE/ Default issue forms and contact links
├── CONTRIBUTING.md         Organisation-wide contribution guidance
├── CODE_OF_CONDUCT.md      Community expectations
├── SECURITY.md             Private reporting and supported versions
└── SUPPORT.md              Help and bug-report routes
```

Edit `profile/README.md` to change the organisation page. The community files provide
organisation defaults; a repository may supply its own more specific guide or form.
The nested `.github/ISSUE_TEMPLATE/` directory is intentional.

Brand sources live in `Altiward/altiward`, under `assets/brand/`, and the canonical
console screenshot in `docs/images/`. From that checkout, use
`scripts/brand/export.sh github <path-to-this-checkout>` to refresh the copies here.
Append `--check` to compare without writing. Keep copies local so the profile renders
independently of the application repository.
