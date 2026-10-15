# Security update — 15 October 2026

- Updated all nine BetterPhotos Sass/build-tool dependency sets and lockfiles.
- Replaced the obsolete csso CLI pipeline in lectures 28 and 29 with current PostCSS/cssnano tooling. Use `npm run build`; the individual build commands remain available.
- Added Node.js 24 guidance, weekly dependency-update pull requests, dependency-audit/build checks and educational/security notices. These changes deliberately deviate from the recordings.
- Verification: all nine stylesheet compilations and both prefix/minification pipelines passed; all nine package audits reported zero known vulnerabilities at review time.

See SECURITY.md before use. Static stylesheets do not make a deployed website secure, and future advisories require review.
