## AIC8800 USB WiFi Windows Driver 驱动

This repository provides USB WiFi drivers for AIC8800 and compatible devices on Windows 7/10/11 32-bit and 64-bit.

## Driver Information

This table provides details about the available drivers.

| Device                              | Drver Version | Driver Date | Official Link                                                                                                                         | Backup Link                                                                                                                       |
|-------------------------------------|---------------|-------------|---------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| <br> Ugreen CM448       <br> &nbsp; | 6.40.60.192   | 05/08/2024  | [Download](https://download.lulian.cn/AIC8800D80.zip)                                                                                 |                  |
| <br> Ugreen CM761       <br> &nbsp; | 21.8.52.318   | 01/08/2024  | [Download](https://download.lulian.cn/AIC8800FC-CM761%E9%A9%B1%E5%8A%A8.zip)                                                          | [Download](https://github.com/peckishrine/aic8800_windows_drivers/raw/main/AIC8800FC-CM761%E9%A9%B1%E5%8A%A8.zip)                 |
| <br> Comfast CF-940AX   <br> &nbsp; | 21.8.51.313   | 10/18/2023  | [Download](https://en.comfast.com.cn/uploadfile/2023/1220/20231220091946673.zip)                                                      | [Download](https://github.com/peckishrine/aic8800_windows_drivers/raw/main/20231220091946673.zip)                                 |
| <br> Enmane EM-AX300S   <br> &nbsp; | 21.6.12.33    | 10/04/2023  | [Download](https://www.enmangroup.cn/link/EM-AX300S_Windows_WiFi6_Driver.zip)                                                         | [Download](https://github.com/peckishrine/aic8800_windows_drivers/raw/main/EM-AX300S_Windows_WiFi6_Driver.zip)                    |
| <br> BrosTrend AX5      <br> &nbsp; | 19.20.4.894   | 08/19/2023  | [Download](https://cdn.shopify.com/s/files/1/0270/1023/6487/files/AX300_Nano_USB_Adapter-Driver_for_Windows_11_10_7.exe?v=1695803771) | [Download](https://github.com/peckishrine/aic8800_windows_drivers/raw/main/AX300_Nano_USB_Adapter-Driver_for_Windows_11_10_7.exe) |
| <br> Tenda U2v5.0       <br> &nbsp; | 19.20.4.894   | 08/19/2023  | [Download](https://down.tendacn.com/uploadfile/U2/Setup_U2V5.0_V1.0.0.4.zip)                                                          | [Download](https://github.com/peckishrine/aic8800_windows_drivers/raw/main/Setup_U2V5.0_V1.0.0.4.zip)                             |
| <br> Tenda W311MIv6.0   <br> &nbsp; | 19.20.4.894   | 08/19/2023  | [Download](https://down.tendacn.com/uploadfile/W311MI/Setup_W311MIV6.0_V1.0.0.8.zip)                                                  | [Download](https://github.com/peckishrine/aic8800_windows_drivers/raw/main/Setup_W311MIV6.0_V1.0.0.8.zip)                         |
| <br> Enmane EM-AX286    <br> &nbsp; | 16.7.10.200   | 02/09/2023  | [Download](http://www.enmangroup.cn/link/EM-AX286_Windows_WiFi_Driver.zip)                                                            | [Download](https://github.com/peckishrine/aic8800_windows_drivers/raw/main/EM-AX286_Windows_WiFi_Driver.zip)                      |
| <br> Fenvi WIFI 6 AX286 <br> &nbsp; | 16.7.10.200   | 02/09/2023  | [Download](https://download.fenvi.com/support/USB/18286.rar)                                                                          | [Download](https://github.com/peckishrine/aic8800_windows_drivers/raw/main/18286.rar)                                             |

For <b><em>Windows 7 users</em></b>, please note that the driver versions might vary from those listed in the table. <br>
If you encounter an error while installing drivers on Windows 7, installing hotfix [KB3033929](https://www.lb-link.com/download/Driverprogram/170/LB-LINK-BL-WN300AX(FU1)-WIN7patch.html) might resolve the issue. <br>

## Supported Devices

This table provides a list of devices compatible with the latest driver (05/08/2024), along with their corresponding Device IDs.

| Vendor       | Device Description                | Device IDs                                                                                                                                                                                                                           |
|--------------|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| AIC Corp     | AIC USB WiFi                      | USB\VID_A69C&PID_8801&MI_02                                                                                                                                                                                                          |
| AIC Corp     | AIC8800D80 USB WiFi               | USB\VID_A69C&PID_8d81&MI_02, USB\VID_368b&PID_8d84, USB\VID_A69C&PID_8d83, USB\VID_368b&PID_8d83                                                                                                                                     |
| AIC Corp     | AIC88DC USB WiFi                  | USB\VID_A69C&PID_88DC, USB\VID_A69C&PID_88DD, USB\VID_A69C&PID_88DE, USB\VID_368B&PID_88DF                                                                                                                                           |
| Tenda        | Tenda WiFi 6 Wireless USB Adapter | USB\VID_2604&PID_001F                                                                                                                                                                                                                |
| TP-LINK      | TP-LINK Wireless USB Adapter      | USB\VID_2357&PID_014E                                                                                                                                                                                                                |
| MERCURY      | MERCURY Wireless USB Adapter      | USB\VID_2357&PID_014B                                                                                                                                                                                                                |
| FAST         | FAST Wireless U Adapter           | USB\VID_2357&PID_014F                                                                                                                                                                                                                |
| Tenda        | Tenda Wireless USB Adapter        | USB\VID_2604&PID_0013, USB\VID_2604&PID_0014                                                                                                                                                                                         |
| AIC Corp     | Wireless LAN WIFI 6 USB Adapter   | USB\VID_2604&PID_0015, USB\VID_2604&PID_0016, USB\VID_2604&PID_0017, USB\VID_2604&PID_0018, USB\VID_2604&PID_0019, USB\VID_2604&PID_001A, USB\VID_2604&PID_001B, USB\VID_2604&PID_001C, USB\VID_2604&PID_001D, USB\VID_2604&PID_001E |
| TP-LINK      | TP-LINK Wireless N Adapter        | USB\VID_2357&PID_0147                                                                                                                                                                                                                |
| Ugreen       | Ugreen WIFI6 Wireless USB NIC     | USB\VID_368b&PID_8d85                                                                                                                                                                                                                |

