# KuBIT POS — Releases

This repository holds the **distributable builds** of KuBIT POS. Clients install and update
from the **Releases** here.

- Builds are published automatically by the private `KUBIT_POS_2026` repo's CI on every push to
  `main` (workflow `auto-release.yml`), and on demand via its manual `deploy.yml` workflow.
- Each release `v<version>` attaches a self-contained **win-x64** package
  `KubitPOS-<version>-win-x64.zip` — the client needs no .NET runtime installed.

Source code lives in the private `KUBIT_POS_2026` repository.
