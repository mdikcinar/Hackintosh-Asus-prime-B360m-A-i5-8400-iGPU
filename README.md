# Hackintosh-Asus-prime-B360m-A-i5-8400-iGPU

# My System
-Asus prime b360m-a
-i5 8400
-Gtx 1060 - Not working on Hackintosh

# Requirements
Bios
  Display Mode -> CPU

# Intel BIOS settings
Note: Most of these options may not be present in your firmware, we recommend matching up as closely as possible but don't be too concerned if many of these options are not available in your BIOS
#Disable
Fast Boot
Secure Boot
Serial/COM Port
Parallel Port
VT-d (can be enabled if you set DisableIoMapper to YES)
CSM
Thunderbolt(For initial install, as Thunderbolt can cause issues if not setup correctly)
Intel SGX
Intel Platform Trust
CFG Lock (MSR 0xE2 write protection)(This must be off, if you can't find the option then enable AppleXcpmCfgLock under Kernel -> Quirks. Your hack will not boot with CFG-Lock enabled)
#Enable
VT-x
Above 4G decoding
Hyper-Threading
Execute Disable Bit
EHCI/XHCI Hand-off
OS type: Windows 8.1/10 UEFI Mode
DVMT Pre-Allocated(iGPU Memory): 64MB
SATA Mode: AHCI
#
