For building TWRP for CHUWI Hi9 Pro ONLY

To compile

export ALLOW_MISSING_DEPENDENCIES=true && . build/envsetup.sh && lunch omni_hi9pro-eng && mka -j$(nproc --all) recoveryimage
