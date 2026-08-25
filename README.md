# AutoCensoR Full

Windows desktop package with the full runtime build.

Source code: https://github.com/JHKS24/AutoCensoR

## Download

The full package is split into multiple release assets because it is larger
than GitHub's single-file release asset limit.

Download every `AutoCensoR_Full.zip.*` part from GitHub Releases, place them in
the same folder, then combine them:

```powershell
cmd /c copy /b AutoCensoR_Full.zip.001+AutoCensoR_Full.zip.002 AutoCensoR_Full.zip
```

Extract `AutoCensoR_Full.zip`, then run:

```text
AutoCensoR_Full\AutoCensoR_Full.exe
```

The current v0.1.0 release assets were refreshed on 2026-08-25 with the Windows
window interaction fixes. Existing v0.1.0 users can apply the much smaller
[patch file](https://jhks24.github.io/AutoCensoR-Site/patch.html) instead of
downloading and recombining the complete package again.

## Notes

- Model weights are not included.
- Load a compatible `.pt` model from the app's model controls.
- Use this build when you want the full packaged runtime.

## Integrity

Check `SHA256SUMS.txt` after download if you need to verify the package or
individual parts.
