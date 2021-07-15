# SPDX-License-Identifier: GPL-2.0-only
obj-$(CONFIG_MT76x0U) += mt76x0u-alt.o
obj-$(CONFIG_MT76x0E) += mt76x0e-alt.o
obj-$(CONFIG_MT76x0_COMMON) += mt76x0-alt-common.o

mt76x0-alt-common-y := init.o main.o eeprom.o phy.o

mt76x0u-alt-y := usb.o usb_mcu.o
mt76x0e-alt-y := pci.o pci_mcu.o

# ccflags-y := -DDEBUG
