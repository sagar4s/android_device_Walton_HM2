# Walton Unite 2 HM2

Walton Unite 2 device is a low-range smartphone from Walton.

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Quad-core 1.3 GHz Cortex-A7
GPU     | Mali-400MP2
Memory  | 1GB RAM
Shipped Android Version | 5.0
Storage | 8 GB
Battery | 3000 mAh
Display | 5.0" 720 x 1280 px
Camera  | 8 MP, f/2.0, autofocus, LED flash

This branch is for building LineageOS 14.1 Based ROMs.


# Build Commands :-

  * repo init -u git://github.com/sagar4s/android.git -b cm-14.1
  * repo sync
  * git clone https://github.com/sagar4s/android_device_Walton_HM2.git device/Walton/HM2
  * git clone https://github.com/sagar4s/android_vendor_Walton_HM2.git vendor/Walton/HM2
  * source build/envsetup.sh
  * brunch HM2
  * Done :)
  
