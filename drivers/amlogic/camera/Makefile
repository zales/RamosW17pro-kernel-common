#
# Makefile for the amlogic platform camera interface device drivers.
#
EXTRA_AFLAGS=-mfloat-abi=softfp -mfpu=neon
amlflash-objs := common/flashlight.o
gt2005dri-objs := gt2005.o
gc0307dri-objs := gc0307.o
gc0308dri-objs := gc0308.o
gc2015dri-objs := gc2015.o
ov5640dri-objs := ov5640.o
ov5642dri-objs := ov5642.o
ov7675dri-objs := ov7675.o
ov2655dri-objs := ov2655.o
sp0838dri-objs := sp0838.o
hi253dri-objs := hi253.o
hi704dri-objs := hi704.o
ov3660dri-objs := ov3660.o
amlvm-objs := common/vm.o common/util.o common/plat_ctrl.o

obj-$(CONFIG_VIDEO_AMLOGIC_FLASHLIGHT)  += amlflash.o
obj-$(CONFIG_VIDEO_AMLOGIC_CAPTURE_GT2005) +=gt2005dri.o
obj-$(CONFIG_VIDEO_AMLOGIC_CAPTURE_GC0307) += gc0307dri.o
obj-$(CONFIG_VIDEO_AMLOGIC_CAPTURE_GC0308) += gc0308dri.o
obj-$(CONFIG_VIDEO_AMLOGIC_CAPTURE_GC2015) += gc2015dri.o
obj-$(CONFIG_VIDEO_AMLOGIC_CAPTURE_OV5640) += ov5640dri.o
obj-$(CONFIG_VIDEO_AMLOGIC_CAPTURE_OV5642) += ov5642dri.o
obj-$(CONFIG_VIDEO_AMLOGIC_CAPTURE_OV7675) += ov7675dri.o
obj-$(CONFIG_VIDEO_AMLOGIC_CAPTURE_OV2655) += ov2655dri.o
obj-$(CONFIG_VIDEO_AMLOGIC_CAPTURE_SP0838) += sp0838dri.o
obj-$(CONFIG_VIDEO_AMLOGIC_CAPTURE_HI253) += hi253dri.o
obj-$(CONFIG_VIDEO_AMLOGIC_CAPTURE_HI704) += hi704dri.o
obj-$(CONFIG_VIDEO_AMLOGIC_CAPTURE_OV3660) += ov3660dri.o
obj-$(CONFIG_AMLOGIC_VIDEOIN_MANAGER)  += amlvm.o
