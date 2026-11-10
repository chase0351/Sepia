# Sepia

Sepia is a standalone tabletop character app.

**Live app:** https://chase0351.github.io/Sepia/

## Branches

| Branch | Purpose |
| --- | --- |
| [development](https://github.com/chase0351/Sepia/tree/development) | Ongoing changes and testing. Changes here do not automatically update the live app. |
| [main](https://github.com/chase0351/Sepia/tree/main) | The approved version published on GitHub Pages. |

## Release process

1. Make and review app changes on `development`.
2. Wait for the owner to explicitly request publication.
3. Merge the approved changes into `main`.
4. Check that the **Publish Sepia** workflow succeeds.

Changes to `index.html` or `.nojekyll` on `main` trigger publication. The publishing workflow also supports a manual redeployment of `main`; its jobs skip runs from other branches. Documentation-only changes do not deploy.

See [AGENTS.md](AGENTS.md) for the development and release instructions followed by coding assistants.
