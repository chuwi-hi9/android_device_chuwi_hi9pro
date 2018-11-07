For building TWRP for CHUWI Hi9 Plus ONLY

To compile

export ALLOW_MISSING_DEPENDENCIES=true && . build/envsetup.sh && lunch omni_hi9plus-eng && make -j8 recoveryimage
