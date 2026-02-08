--- 
title: Mi Titanium Project
published: 2026-02-08
description: xiaomi msm-titanium project
draft: false
---

:::warning
I'm not responsible for bricked devices, dead SD cards, thermonuclear war, or you getting fired because the alarm app failed. Please do some research if you have any concerns about features included in the products you find here before flashing it! YOU are choosing to make these modifications, and if you point the finger at me for messing up your device, I will laugh at you. Your warranty will be void if you tamper with any part of your device / software.
:::

This page contains information for the **Xiaomi Titanium device**, which uses the Qualcomm Snapdragon MSM8953 SoC. This project aims to bring the latest software to older devices.

## Supported devices
* Redmi 5 Plus (Vince)
* Redmi S2/Y2 (YSL)
* Mi Max 2 (Oxygen)
* Mi 5X (Tiffany)
* Redmi 4 Prime (Markw)

### Downstream Android Kernel 4.19
<div class="full-width">
<table class="ColorTable">
        <tbody><tr>
            <td><strong>Features</strong></td>
            <td><strong>Vince</strong></td>
            <td><strong>YSL</strong></td>
            <td><strong>Oxygen</strong></td>
        </tr>
        <tr>
            <td>Display</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>DT2W</td>
            <td class="done">Y</td>
            <td class="partial">P<sup>1</sup></td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>GPU Acceleration</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>WiFi</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>WiFi Hotspot</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>Bluetooth</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>Modem</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>GNSS</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>Audio Codec</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>Video Codec</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>Battery</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>Rear Camera</td>
            <td class="partial">P<sup>2</sup></td>
            <td class="done">Y</td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>Front Camera</td>
            <td class="done">Y</td>
            <td class="broken">N</td>
            <td class="broken">N</td>
        </tr>
        <tr>
            <td>IR</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>Sensors</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>Touchscreen</td>
            <td class="done">Y</td>
            <td class="partial">P<sup>3</sup></td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>Fingerprint Reader</td>
            <td class="done">Y</td>
            <td class="broken">N</td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>Haptics</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>Notification LEDs</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>WLED</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>Flashlight</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>USB</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
        </tr>
        <tr>
            <td>SDCard</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
            <td class="done">Y</td>
        </tr>
</tbody></table>
</div>

#### Notes
<sup>1</sup> `YSL` DT2W is not supported on GT917D touchscreen, because the touchscreen is not working yet (have not found any users of this touchscreen)

<sup>2</sup> `Vince` The camera is fully functional only on Sony IMX486, while ov12a10 is partial due to ISP/VFE issues in JPEG mode (preview and snapshot are duplicated), RAW mode is fine.

<sup>3</sup> `YSL` only ft5446 touchscreen is supported, GT917D touchscreen is not added

## Available downloads
### Redmi 5 Plus (Vince)
#### ROMs
* `A16` [LineageOS 23.2](https://t.me/me_alts/102) <sup>`unofficial`</sup> <sup>`k4.19`</sup>
* `A16` [LineageOS 23.0](https://t.me/me_alts/89) <sup>`unofficial`</sup> <sup>`k4.9`</sup>
* `A15` [LineageOS 22.2](https://t.me/renzalt_dump/74) <sup>`unofficial`</sup> <sup>`k4.19`</sup>
* `A15` [LineageOS 22.2](https://t.me/me_alts/90) <sup>`unofficial`</sup> <sup>`k4.9`</sup>
* `A14` [LineageOS 21.0](https://t.me/renzalt_dump/33) <sup>`unofficial`</sup> <sup>`k4.9`</sup>
* `A13` [LineageOS 20.0](https://t.me/renzalt_dump/116) <sup>`unofficial`</sup> <sup>`k4.19`</sup>

#### Recovery
* `TWRP` [TeamWin Recovery Project](https://t.me/renzalt_dump/115) <sup>`unofficial`</sup> <sup>`k3.18`</sup> <sup>`k4.9`</sup> <sup>`k4.19`</sup>

### Redmi S2/Y2 (YSL)
#### ROMs
* `A16` [LineageOS 23.0](https://t.me/me_alts/86) <sup>`unofficial`</sup> <sup>`k4.9`</sup>
* `A14` [LineageOS 21.0](https://t.me/renzalt_dump/32) <sup>`unofficial`</sup> <sup>`k4.19`</sup>
* `A13` [LineageOS 20.0](https://t.me/renzalt_dump/19) <sup>`unofficial`</sup> <sup>`k4.19`</sup>
* `A13` [LineageOS 20.0](https://t.me/renzalt_dump/18) <sup>`unofficial`</sup> <sup>`k4.9`</sup>

#### Recovery
* `TWRP` [TeamWin Recovery Project](https://t.me/renzalt_dump/30) <sup>`unofficial`</sup> <sup>`k3.18`</sup> <sup>`k4.9`</sup> <sup>`k4.19`</sup>

### Mi Max 2 (Oxygen)
#### ROMs
* `A14` [LineageOS 21.0](https://t.me/Max2Rom/161) <sup>`unofficial`</sup> <sup>`k4.19`</sup>
* `A13` [LineageOS 20.0](https://t.me/Max2Rom/145) <sup>`unofficial`</sup> <sup>`k4.19`</sup>

### Mi 5X (Tiffany) "not supported now"
#### ROMs
* `A13` [LineageOS 20.0](https://t.me/renzalt_dump/29) <sup>`unofficial`</sup> <sup>`k4.9`</sup>

#### Recovery
* `TWRP` [TeamWin Recovery Project](https://t.me/renzalt_dump/28) <sup>`unofficial`</sup> <sup>`k3.18`</sup> <sup>`k4.9`</sup>

### Redmi 4 Prime (Markw) "not supported now"
#### ROMs
* `A13` [LineageOS 20.0](https://t.me/renzalt_dump/13) <sup>`unofficial`</sup> <sup>`k4.9`</sup>

## Building

Use the following `local_manifests.xml` to sync Mi-Titanium projects on `lineage-23.2` branch:
```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
  <manifest>

  <remote  name="mi-thorium"
           fetch="https://github.com/Mi-Thorium"
           revision="a15_qpr2/master" />

  <remote name="alice"
            fetch="https://github.com/Project-Nightcord"
            revision="lineage-20.0" />

  <remote name="needAlt"
            fetch="https://github.com/needAlt"
            revision="lineage-20.0" />

  <remote name="los"
            fetch="https://github.com/lineageos"
            revision="lineage-20.0" />

  <!-- Common -->
  <project path="device/xiaomi/mithorium-common" name="android_device_xiaomi_mithorium-common"     groups="device" remote="alice" revision="lineage-23.2" />
  <project path="vendor/xiaomi/mithorium-common" name="proprietary_vendor_xiaomi_mithorium-common" groups="device" remote="alice" revision="lineage-22.2" />
  <project path="vendor/xiaomi/mithorium-common-graphics" name="proprietary_vendor_xiaomi_mithorium-common-graphics" groups="device" remote="mi-thorium" revision="a15_qpr2/master"/>

  <!-- Common - Kernel 4.19 -->
  <project path="vendor/xiaomi/mithorium-common-4.19" name="proprietary_vendor_xiaomi_mithorium-common-4.19" groups="device" remote="mi-thorium" revision="a15_qpr2/master"/>

  <!-- Vince -->
  <project path="device/xiaomi/vince"        name="android_device_xiaomi_vince"        groups="device" remote="alice" revision="lineage-22.2"/>
  <project path="vendor/xiaomi/vince"        name="proprietary_vendor_xiaomi_vince"    groups="device" remote="alice" revision="lineage-22.2"/>

  <!-- Ysl -->
  <project path="device/xiaomi/ysl"        name="android_device_xiaomi_ysl"        groups="device" remote="alice" revision="lineage-22.2"/>
  <project path="vendor/xiaomi/ysl"        name="proprietary_vendor_xiaomi_ysl"    groups="device" remote="alice" revision="lineage-22.2"/>

  <!-- kernel-vince-ysl-k4.19 -->
  <project path="kernel/xiaomi/msm8953"        name="android_kernel_qcom-msm8953"    groups="device" remote="alice" revision="lineage-20"/>
  <project path="kernel/xiaomi/msm8953/arch/arm64/boot/dts/vendor-legacy"        name="kernel_devicetree_msm-4.19"    groups="device" remote="alice" revision="main"/>
  <project path="kernel/xiaomi/msm8953/drivers/staging/prima"        name="vendor_qcom_opensource_wlan_prima"    groups="device" remote="mi-thorium" revision="wlan/LA.UM.9.6.4/mithorium/master"/>
  <project path="kernel/xiaomi/msm8953/techpack/xiaomi-titanium"        name="kernel_techpack_xiaomi-titanium"    groups="device" remote="alice" revision="techpack/titanium/4.19/master"/>

  <!-- VINCE-CAMERA-COMMON -->
  <project path="device/xiaomi/vince/camera"        name="android_device_xiaomi_vince_camera"        groups="device" remote="alice" revision="main" />

  <!-- YSL-CAMERA-COMMON -->
  <project path="device/xiaomi/ysl/camera"        name="android_device_xiaomi_msm8953-camera"        groups="device" remote="alice" revision="a11/vince/master" />

  <!-- extra -->
  <project path="vendor/lineage-priv" name="vendor_extra" remote="alice" revision="14" />

  <!-- hardware/xiaomi -->
  <project path="hardware/xiaomi" name="hardware_xiaomi" remote="alice" revision="lineage-22.2" />

  <!-- Hardware -->
  <project path="hardware/mithorium/common" name="android_hardware_mithorium_common" groups="device" remote="mi-thorium" revision="lineage">
    <linkfile src="_Android.mk" dest="hardware/mithorium/Android.mk" />
    <linkfile src="mithorium_qcom_hals.mk" dest="hardware/mithorium/mithorium_qcom_hals.mk" />

    <linkfile src="guard-generic.bp" dest="hardware/mithorium/audio/LA.UM.9.6.4.r2-04300-89xx.QSSI13r2.0/Android.bp" />
    <linkfile src="guard-generic.bp" dest="hardware/mithorium/audio/lineage-21.0-caf-msm8953/Android.bp" />
    <linkfile src="guard-generic.bp" dest="hardware/mithorium/display/LA.UM.8.6.2.r1-09500-89xx.0/Android.bp" />

    <linkfile src="guard-qcom-qssi-display-lineage-19.1.bp" dest="hardware/mithorium/display/LA.UM.9.6.4.r2-04300-89xx.QSSI13r2.0/Android.bp" />
    <linkfile src="guard-qcom-qssi-display.mk"              dest="hardware/mithorium/display/LA.UM.9.6.4.r2-04300-89xx.QSSI13r2.0/Android.mk" />

    <linkfile src="guard-qcom-qssi-display-lineage-19.1.bp" dest="hardware/mithorium/display/lineage-21.0-caf-msm8953/Android.bp" />
    <linkfile src="guard-qcom-qssi-display.mk"              dest="hardware/mithorium/display/lineage-21.0-caf-msm8953/Android.mk" />
  </project>

 <!-- Hardware - display-commonsys-intf -->
  <project path="hardware/mithorium/display/LA.UM.9.6.4.r2-04300-89xx.QSSI13r2.0/display" name="android_vendor_qcom_opensource_display-commonsys-intf" groups="qcom,pdk-qcom" remote="los" revision="lineage-23.2"/>
  <project path="hardware/mithorium/display/lineage-21.0-caf-msm8953/display" name="android_vendor_qcom_opensource_display-commonsys-intf" groups="qcom,pdk-qcom" remote="los" revision="lineage-23.2"/>/>

 <!-- Hardware - LA.UM.8.6.2 -->
  <project path="hardware/mithorium/display/LA.UM.8.6.2.r1-09500-89xx.0/display" name="android_hardware_qcom_display_mithorium" groups="device" remote="mi-thorium" revision="mithorium/LA.UM.8.6.2.r1-09500-89xx.0"/>

 <!-- Hardware - LA.UM.9.6.3 -->
  <project path="hardware/mithorium/audio/LA.UM.9.6.4.r2-04300-89xx.QSSI13r2.0/hal" name="android_hardware_qcom_audio_mithorium" groups="device" remote="mi-thorium" revision="mithorium/LA.UM.9.6.4.r2-04300-89xx.QSSI13r2.0"/>
  <project path="hardware/mithorium/media/LA.UM.9.6.4.r2-04300-89xx.QSSI13r2.0/hal" name="android_hardware_qcom_media_mithorium" groups="device" remote="mi-thorium" revision="mithorium/LA.UM.9.6.4.r2-04300-89xx.QSSI13r2.0"/>
  <project path="hardware/mithorium/display/LA.UM.9.6.4.r2-04300-89xx.QSSI13r2.0/hal" name="android_hardware_qcom_display_mithorium" groups="device" remote="mi-thorium" revision="mithorium/LA.UM.9.6.4.r2-04300-89xx.QSSI13r2.0"/>

 <!-- Hardware - LineageOS (based on LA.UM.10.6.2 tags) -->
  <project path="hardware/mithorium/media/lineage-21.0-caf-msm8953/hal" name="android_hardware_qcom_media" groups="qcom,pdk-qcom" remote="los" revision="lineage-21.0-caf-msm8953" />
  <project path="hardware/mithorium/display/lineage-21.0-caf-msm8953/hal" name="android_hardware_qcom_display" groups="pdk-qcom,qcom,qcom_display" remote="los" revision="lineage-21.0-caf-msm8953" />

</manifest>
```

## Acknowledgements
This project was developed under the Mi-Titanium Team.

We would like to thank the LineageOS team for providing the source code and guidance.

Sincere thanks to Yumi Yukimura (@me-cafebabe) for her work on MiThorium and her guidance