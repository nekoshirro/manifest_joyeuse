![Fusion OS](https://telegra.ph/file/951414eddf650927a0053.jpg)
# Fusion OS | Xiaomi Redmi Note 9 Pro #

### Setup our local manifest ###

```bash
repo init -u https://github.com/Fusion-OS/android_manifest -b twelve
```
```bash
git clone https://github.com/nekoshirro/manifest_joyeuse .repo/local_manifests -b fusion
```
```bash
repo sync --current-branch --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -j$(nproc --all)
```
