# baptistejouin/helix

Personal fork of [helix-editor/helix](https://github.com/helix-editor/helix) used to preview and run open, unmerged pull requests ahead of upstream release.

`master` tracks upstream `master` as-is. Each other branch merges in one open upstream PR (rebased on current `master` as needed) so it can be built and used locally before the PR lands.

## Currently merged

| Branch | Upstream PR | Description |
| --- | --- | --- |
| [`workspace-diagnostics`](https://github.com/baptistejouin/helix/tree/workspace-diagnostics) | [helix-editor/helix#15995](https://github.com/helix-editor/helix/pull/15995) | Adds `workspace/diagnostic` support so LSPs like `ty`, `rust-analyzer`, and `clangd` can report diagnostics for the whole workspace, not just open buffers. |

This list will be updated as branches are added, rebased, or dropped.
