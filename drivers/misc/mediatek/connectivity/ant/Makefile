# Connectivity combo driver
ccflags-y += -DWMT_CREATE_NODE_DYNAMIC=1
ccflags-y += \
	-I$(srctree)/drivers/misc/mediatek/connectivity/common/common_main/include \
	-I$(srctree)/drivers/misc/mediatek/connectivity/common/common_main/linux/include

obj-$(CONFIG_MTK_COMBO_ANT)	+= stp_chrdev_ant.o
