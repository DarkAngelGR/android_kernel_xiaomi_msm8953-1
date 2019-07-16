#
# Makefile for the qti specific video device drivers
# based on V4L2.
#
obj-$(CONFIG_MSM_VIDC_V4L2) += vidc/
obj-$(CONFIG_MSM_VIDC_3X_V4L2) += vidc_3x/
obj-y += sde/
obj-$(CONFIG_SPECTRA_CAMERA) += camera/
ifeq ($(CONFIG_MACH_XIAOMI_MARKW),y)
ccflags-y += -Idrivers/media/platform/msm/camera_v2_markw
ccflags-y += -Idrivers/media/platform/msm/camera_v2_markw/common
ccflags-y += -Idrivers/media/platform/msm/camera_v2_markw/sensor/io
ccflags-y += -Idrivers/media/platform/msm/camera_v2_markw/sensor/cci
else
ccflags-y += -Idrivers/media/platform/msm/camera_v2
ccflags-y += -Idrivers/media/platform/msm/camera_v2/common
ccflags-y += -Idrivers/media/platform/msm/camera_v2/sensor/io
ccflags-y += -Idrivers/media/platform/msm/camera_v2/sensor/cci
endif
obj-y += broadcast/
obj-$(CONFIG_DVB_MPQ) += dvb/
obj-$(CONFIG_QCA402X) += qca402/
