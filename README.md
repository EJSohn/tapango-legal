# Published legal pages

Static pages for the stores' public privacy-policy URL. They are plain HTML with
no scripts and no external subresources. Google policy links open only when selected. English, Korean and Spanish match the
Privacy page inside the app (`lib/l10n/app_*.arb`, keys `privacy*`), and
`test/vm/legal_pages_test.dart` holds the address and the claims that have to
agree.

To publish: copy this folder's files to the root of a public repository with
GitHub Pages enabled. The policy URL is then `…/privacy-en.html` (or the
language of the listing). Change the date in the page when the policy changes.
