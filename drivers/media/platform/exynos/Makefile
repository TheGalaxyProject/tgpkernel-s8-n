obj-$(CONFIG_EXYNOS_MEDIA_DEVICE)   += mdev/
obj-$(CONFIG_VIDEO_EXYNOS_G2D1SHOT) += g2d1shot/
obj-$(CONFIG_VIDEO_EXYNOS_SCALER)       += scaler/
obj-$(CONFIG_VIDEO_EXYNOS_MFC)		+= mfc/
obj-$(CONFIG_VIDEO_EXYNOS_SMFC)		+= smfc/
ifeq ($(CONFIG_CAMERA_GREAT),y)
obj-$(CONFIG_VIDEO_EXYNOS_FIMC_IS2)	+= fimc-is2/
else
obj-$(CONFIG_VIDEO_EXYNOS_FIMC_IS2)	+= fimc-is2_dream/
endif
EXTRA_CLAGS += -Idrivers/media/video
