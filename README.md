tegra114-microsoft-surface-2-all.dtb = all device tree options enabled
tegra114-microsoft-surface-2-sdcard.dtb = SD card device tree option (mmc1) enabled
tegra114-microsoft-surface-2.dtb = original device tree file which is commonly distributed/available

#convert dtb to dts
#dtc -I dtb tegra114-microsoft-surface-2.dtb -O dts
#convert dts to dtb
#dtc -O dtb -o tegra114-microsoft-surface-2-all.dtb tegra114-microsoft-surface-2.dts
