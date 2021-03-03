# RRVL RetroArch core repo

## Dependencies

libarchive-zip-perl ( Needed for crc32)
rsync
zip

On Ubuntu 16.04 or newer, these can be easily installed by doing:
```bash
sudo apt update -y && sudo apt-get install -y libarchive-zip-perl rsync zip
```

On Redhat 6 or newer, these can be easily installed by doing:
```bash
sudo yum install perl-Archive-Zip rsync zip
```

## Add/update core

Copy the core to aarch64 or arm7hf and chdir to that directory. Then run:
```bash
    git fetch https://github.com/valadaa48/rrvl-cores.git && git merge https://github.com/valadaa48/rrvl-cores.git/master
    ../addcore nestopia_libretro.so
    git add . && git commit -m "commit message" && git push
```

Commit and make PR. Someone with access to Safarikniv's hosting will push it out.
