ifeq ($(CONFIG_MTK_COMBO),y)

ccflags-y += \
	-I$(srctree)/drivers/misc/mediatek/connectivity/common/common_main/linux/include \
	-I$(srctree)/drivers/misc/mediatek/connectivity/common/common_main/core/include \
	-I$(srctree)/drivers/misc/mediatek/connectivity/common/common_main/include \
	-I$(srctree)/drivers/misc/mediatek/connectivity/common/common_detect \
	-I$(srctree)/drivers/misc/mediatek/btif/common/inc \

obj-y   += wmt_core.o
obj-y   += wmt_ctrl.o
obj-y   += wmt_func.o
obj-y   += wmt_lib.o
obj-y   += wmt_conf.o
obj-y   += wmt_exp.o
obj-y	+= wmt_ic_6620.o
obj-y	+= wmt_ic_6628.o
obj-y	+= wmt_ic_6630.o
obj-y	+= wmt_ic_6632.o
obj-y	+= wmt_ic_soc.o

obj-y	+= stp_exp.o
obj-y	+= stp_core.o
obj-y	+= psm_core.o
obj-y	+= btm_core.o

endif
