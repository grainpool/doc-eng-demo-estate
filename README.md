# doc-eng-demo-estate

The documentation estate for the [Relay + Concord demo](https://github.com/grainpool/doc-eng-demo).

This repository holds documentation surfaces only — no code, no CI, and **no `.github/` directory, ever**.
An automated system (Concord, a documentation reconciliation engine) opens pull requests against this
repository. All application code, product truth, and CI live in the main repository, which mounts this
one as a git submodule at `estate/`.

| Directory | Surface |
|---|---|
| `docs-mintlify/` | Developer documentation (Mintlify) |
| `help-center/` | End-user help center |
| `in-product-copy/` | In-product copy registry (typed JSON) |

Content arrives in a later phase of the build. Until then these directories are placeholders.
