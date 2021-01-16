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

    ../addcore nestopia_libretro.so

Commit and make PR. Someone with access to Safarikniv's hosting will push it out.

## To push

Dry-run to see what's changed:

    ./push -n 

Copy from remote repo:

    ./pull

If you want push access you can ask Safarikniv.
