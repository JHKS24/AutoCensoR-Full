# AutoCensoR Full

Windows desktop package with the full runtime build.

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

## Notes

- Model weights are not included.
- Load a compatible `.pt` model from the app's model controls.
- Use this build when you want the full packaged runtime.

## Integrity

Check `SHA256SUMS.txt` after download if you need to verify the package or
individual parts.
