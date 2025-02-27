# wifi_version
Get the WIFI version supported by your WIFI card on Linux - From WiFi 4  to WIFI 7

Surprisingly enough, on Linux there is no easy way to get the **maximum Wifi version supported by your laptop**.   
This command line displays all supported.

# description
This script displays the wifi versions supported by your Wifi card on Linux- From WiFi 4  to WIFI 7

If `iw list` includes one or more of the following modes under "Supported interface modes" or "Supported PHY modes" then
you can determine your card’s WiFi version:

   | WiFi Standard | PHY Mode                   |
   |---------------|----------------------------|
   | WiFi 4        | `HT` (802.11n)             |
   | WiFi 5        | `VHT` (802.11ac)           |
   | WiFi 6        | `HE` (802.11ax)            |
   | WiFi 6E       | `HE` (with 6 GHz channels) |
   | WiFi 7        | `EHT` (802.11be)           |

This is what this script do.

# dependancy
The iw command 

- Arch Linux: sudo pacman -S iw
- Debian/Ubuntu: sudo apt install iw


