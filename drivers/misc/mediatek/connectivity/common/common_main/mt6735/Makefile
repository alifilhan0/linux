# WMT HAL driver for MT6735

ccflags-y += \
	-I$(srctree)/drivers/misc/mediatek/connectivity/common/common_main/mt6735/include \
	-I$(srctree)/drivers/misc/mediatek/connectivity/common/common_main/linux/include \
	-I$(srctree)/drivers/misc/mediatek/connectivity/common/common_main/include \
	-I$(srctree)/drivers/misc/mediatek/connectivity/common/common_detect

#ccflags-y += -I$(srctree)/drivers/misc/mediatek/base/power/$(MTK_PLATFORM)
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/mt6735/include/mach

subdir-ccflags-y += -D MTK_WCN_WMT_STP_EXP_SYMBOL_ABSTRACT

ifeq ($(CONFIG_MTK_CONN_LTE_IDC_SUPPORT),y)
	subdir-ccflags-y += -DWMT_IDC_SUPPORT=1
else
	subdir-ccflags-y += -DWMT_IDC_SUPPORT=0
endif

obj-y += mtk_wcn_consys_hw.o
obj-y += wmt_plat_alps.o
