# local_manifests

**Build**
```bash
source build/envsetup.sh

# For Samsung Galaxy S6
lunch lineage_zerofltexx-userdebug

# For Samsung Galaxy S6 Edge
lunch lineage_zeroltexx-userdebug

croot

make bacon -j8
```
Requires 7420_patches in order to build and boot
