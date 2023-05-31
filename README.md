# Firmware Tools

This repo introduce several tools for firmware attacking.

### [FirmAE](https://github.com/pr0v3rbs/FirmAE)

Due to some error when installing pure FirmAE (especially when installing binwalk) from original repo, I modified somethings a bit so you can download FirmAE just by copying and running these following commands to install FirmAE:

```bash
git clone --recursive https://github.com/pr0v3rbs/FirmAE
cd FirmAE
wget https://github.com/nhtri2003gmail/Firmware-Tools/releases/download/patch/FirmAE.patch
patch < FirmAE.patch
./download.sh
./install.sh
```

# Firmware Mod Kit

This kit is a collection of scripts and utilities to extract and rebuild linux based firmware images.
