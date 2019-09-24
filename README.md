## Manifest for Grand Neo Plus

 **Before or after syncing run:**

```bash
git clone https://github.com/SAMSUNG-GNP/manifest.git -b lineage-15.1 .repo/local_manifests
```
 **Then sync up:**

```bash
repo sync -f --force-sync --no-tags --no-clone-bundle -j$(nproc --all)
```


**Build Lineage**

```bash
source build/envsetup.sh

lunch lineage_grandneove3g-userdebug

mka bacon
```
