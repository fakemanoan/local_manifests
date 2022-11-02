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
You must apply ALL of the patches in 7420_patches in order to get working builds

Older kernels must use build_soong patches
