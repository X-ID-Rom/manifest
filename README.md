Sync Repo
### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/X-ID-Rom/manifest -b thirteen

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch xid_$device-userdebug

# Build the code
$ mka bacon
```

