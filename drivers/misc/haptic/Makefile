# SPDX-License-Identifier: GPL-2.0
#
# Makefile for the input core drivers.
#

# Each configuration option enables a list of files.

obj-$(CONFIG_ICS_HAPTIC_DRV) += aacrt6010_haptic.o

aacrt6010_haptic-objs := haptic_drv.o rt6010.o

ifeq ($(CONFIG_ICS_HAPTIC_DRV_RICHTAP),y)
aacrt6010_haptic-objs += richtap_drv.o
endif