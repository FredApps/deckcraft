# WASM presenter-view popout (#729)

Status: draft planning placeholder. No runtime fix is implemented yet.

Tracks https://github.com/storytold/deckcraft/issues/729.

## Intended scope

- Open presenter view in a separate browser window from an explicit user gesture in the WASM build.
- Keep the presenter controls, current/next slide and notes synchronized with the audience view.
- Handle popup blocking, closing/reopening either window and ending a presentation without leaving stale state.
- Preserve native presenter behavior and keyboard navigation; do not incorporate unrelated unmerged presenter changes.

## Validation still required

- Reproduce the current browser-viewport limitation with a synthetic deck.
- Test popup allowed/blocked, independent window positioning, navigation from each view, presentation shutdown and reopening.
- Check browser compatibility, WASM build and focused presentation regressions.

No tests have been run for this placeholder. Implementation and validation will replace this planning-only state before the PR is marked ready.
