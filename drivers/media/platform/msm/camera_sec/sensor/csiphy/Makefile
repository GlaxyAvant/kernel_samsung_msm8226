ccflags-y += -Idrivers/media/platform/msm/camera_sec
ccflags-y += -Idrivers/media/platform/msm/camera_sec/sensor/io
ifeq ($(CONFIG_MSM_CSI20_HEADER),y)
  ccflags-y += -Idrivers/media/platform/msm/camera_sec/sensor/csiphy/include/csi2.0
else ifeq ($(CONFIG_MSM_CSI30_HEADER),y)
  ccflags-y += -Idrivers/media/platform/msm/camera_sec/sensor/csiphy/include/csi3.0
endif
obj-$(CONFIG_MSM_CSIPHY) += msm_csiphy.o
