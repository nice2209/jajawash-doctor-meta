# JajaWash Doctor Update Manifest

Public manifest endpoint for the JajaWash Doctor auto-updater.

The binary lives in the **private** companion repo `nice2209/jajawash-doctor-releases`.
This repo only hosts `latest.json` (Tauri updater manifest format).

```
endpoint: https://raw.githubusercontent.com/nice2209/jajawash-doctor-meta/main/latest.json
binary:   https://github.com/nice2209/jajawash-doctor-releases (private, PAT-auth)
```

Each new release: update `latest.json` with new version + signed binary URL.