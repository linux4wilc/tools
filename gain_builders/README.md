# Microchip Embedded Wi-Fi®

<a href="http://www.microchip.com/design-centers/wireless-connectivity/embedded-wi-fi"><img src="http://www.microchip.com/_images/logo.png" align="left" hspace="10" vspace="6"></a>
</br></br></br>

usage: gain_builder [-hp <gain_settings_path>] [-fb <binary_fw_path>] [-fh <fw_header_path>]

Linux Driver Binary Firmware:
-----------------------------
``` gain_builder -hp wilc1000_gain_setting.csv -fb wilc1000_wifi_firmware.bin ```

RTOS Driver Hex file Firmware:
-----------------------------
``` gain_builder -hp wilc1000_gain_setting.csv -fh wilc1000_wifi_firmware.h ```


