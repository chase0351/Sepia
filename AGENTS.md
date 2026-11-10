# Sepia repository instructions

## Development and releases

- Use `development` for ongoing app changes. Check out that branch explicitly before editing; do not assume the repository's default branch is the work branch.
- Feature or repair branches for app work should start from `development` and return their changes to `development`.
- `main` is the production branch for https://chase0351.github.io/Sepia/.
- Requests to fix, improve, or update Sepia authorize development work, not publication. Do not push app changes to `main`, merge development changes into `main`, or manually run the publishing workflow unless the user explicitly requests a release or publication to the live site.
- Before an authorized release, review the complete diff from `main` and verify that only the intended changes will be published. Preserve unrelated unfinished development work.
- After an authorized release, verify the publishing result and bring `development` up to date without discarding unreleased work.
- Keep the `Publish Sepia` workflow restricted to `refs/heads/main`. Development changes must not deploy to the public site.
- Preserve the complete standalone app in `index.html`; do not replace it with a reduced or simplified app.
