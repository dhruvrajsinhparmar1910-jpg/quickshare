# Disabled workflows

Upstream LocalSend workflows that need signing secrets (Android keystore, Azure code signing, WinGet token).
GitHub only runs workflows inside `.github/workflows/`, so moving them here disables them.
QuickShare builds are produced by `.github/workflows/quickshare_release.yml` instead.
