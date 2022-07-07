![Evolution X](https://github.com/Evolution-X/manifest/raw/snow/EvoBanner.png)
# Evolution X | Xiaomi Redmi Note 9 Pro #

### Setup our local manifest ###

```bash
repo init -u https://github.com/Evolution-X/manifest -b snow
```
```bash
git clone https://github.com/nekoshirro/manifest_joyeuse .repo/local_manifests -b evolution
```
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
