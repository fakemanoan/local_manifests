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

**Requirements**
Cherry-pick commits from android sources in my github, thanks to html6405.

important ones are netd, bpf and lineage power restoration 
