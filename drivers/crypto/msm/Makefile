obj-$(CONFIG_CRYPTO_DEV_QCOM_MSM_QCE) += qce50.o
qcedevice-objs := qcedev_smmu.o qcedev.o
obj-$(CONFIG_CRYPTO_DEV_QCEDEV) += qcedevice.o
obj-$(CONFIG_CRYPTO_DEV_QCRYPTO) += qcrypto.o
obj-$(CONFIG_CRYPTO_DEV_OTA_CRYPTO) += ota_crypto.o
obj-$(CONFIG_CRYPTO_DEV_QCOM_ICE) += ice.o

CFLAGS_qcedev.o := $(call cc-option,-Wframe-larger-than=5120)
