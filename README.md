# Hackintosh-Asus-prime-B360m-A-i5-8400-iGPU

- Opencore 0.8.0 with latest kexts
- Tested on Monterey 12.3

| System            | Status               |
| ----------------- | ---------------------|
| Asus prime b360m-a|                      | 
| i5 8400           |                      |
| Gtx 1060          | Not working          |
    

# Requirements
| Bios              |                      |
| ----------------- | ---------------------|
| Display Mode      | CPU (Connect monitor to motherboard via hdmi)                 | 
| Other Settings    | https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#intel-bios-settings | 

# Issues
1. Display goes off on login screen
- Fix: Change monitor mode and come back again hdmi mode
2. 630 uhd not recocnized by macos and screen glitches sometime
- Fix: Change your display mode Auto to CPU in your bios settings.
