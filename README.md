# RRVL RetroArch core repo

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
