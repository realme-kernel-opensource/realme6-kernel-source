# Linux driver folder
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/hq_green/hxchipset/
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/hq_green/
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/
ccflags-y += -I$(srctree)/drivers/spi/
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/$(MTK_PLATFORM)/include


# Makefile for the Himax touchscreen drivers.
obj-$(CONFIG_TOUCHSCREEN_HIMAX_INCELL)   		+=	himax_ic_incell_core.o
obj-$(CONFIG_TOUCHSCREEN_HIMAX_IC_HX83112)   		+=	himax_ic_HX83112.o
obj-$(CONFIG_TOUCHSCREEN_HIMAX_COMMON)   		+=	himax_common.o himax_platform.o
obj-$(CONFIG_TOUCHSCREEN_HIMAX_DEBUG)   		+=	himax_debug.o
obj-$(CONFIG_TOUCHSCREEN_HIMAX_INSPECT)   		+=	himax_inspection.o

