# SPDX-License-Identifier: GPL-2.0
obj-$(CONFIG_DMAR_TABLE) += dmar.o
obj-$(CONFIG_INTEL_IOMMU) += iommu.o pasid.o
obj-$(CONFIG_DMAR_TABLE) += trace.o cap_audit.o
obj-$(CONFIG_DMAR_PERF) += perf.o
obj-$(CONFIG_INTEL_IOMMU_DEBUGFS) += debugfs.o
obj-$(CONFIG_INTEL_IOMMU_SVM) += svm.o
ifdef CONFIG_INTEL_IOMMU
obj-$(CONFIG_IRQ_REMAP) += irq_remapping.o
endif
