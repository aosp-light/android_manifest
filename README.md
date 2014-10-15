AOSP for Xperia based on MSM8660
================================

1. Downloading the AOSP source codes:
-------------------------------------

**1. Init repo:**
- repo init -u git://github.com/aosp-light/android_manifest.git -b android-4.4.4_r2.0.1

**2. Sync repo:**
- repo sync

2. Building the source codes
- source build/envsetup.sh && lunch aosp_hazard-userdebug
- make otapackage -j10

3. Troubleshooting
------------------
- You can make change and i add soon as possible you patch

4. In future
------------
- Adding new devices:
	hikari (Xperia acro S)
	hikari_row (Xperia acro HD)
	nozomi (Xperia S)
	aoba (Xperia ION)
	aoba_lte (Xperia IONat)
- Migrate to Android 5.0 (Lolipop)
