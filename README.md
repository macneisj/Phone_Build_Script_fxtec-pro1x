# Phone_Build_Script for fxtec Pro1x

Phone_Build_script. Shell script to build a distribution in chroot then create img files for your phone.

Just edit the script --- include packages, kernel etc and test. Or use as a phone.

Currently I am Using on Fxtec Pro1x. V_2 boots and seems to stabilize touch. I am using kernel 6.18-rc6 debian.

V_2 will be about getting fluxbox working with onboard so i can debug.

Would be nice for PinePhone

# V_2
# Files

patches/apply_patches.sh # test patches\n
patches/display-fixes-v618-v2.patch # regulator/delay hack to get it to boot ... will fix\n
\n
full_build_script-fluxbox-V2.sh # current build script\n
MK_img-FINAL.sh # to make small adjustments\n
flash.sh # flash img files\n
MGL.config # current .config\n
\n
boot.img\n
rootfs.img\n
vbmeta.img # probably not needed\n
\n
# remove .Image.gz-dtb when done\n
\n
Let me know what you think!

