ifeq ($(CONFIG_MTK_COMBO),y)

ccflags-y += \
	-I$(srctree)/drivers/misc/mediatek/connectivity/common/common_main/linux/include \
	-I$(srctree)/drivers/misc/mediatek/connectivity/common/common_main/core/include \
	-I$(srctree)/drivers/misc/mediatek/connectivity/common/common_main/include \
	-I$(srctree)/drivers/misc/mediatek/connectivity/common/common_detect

PLAT := alps
obj-y	+= wmt_plat_alps.o
obj-y	+= wmt_plat_stub.o
obj-y	+= mtk_wcn_cmb_hw.o

endif
