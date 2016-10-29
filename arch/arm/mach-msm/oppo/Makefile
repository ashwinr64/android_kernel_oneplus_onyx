subdir-ccflags-$(CONFIG_ARCH_MSM) += -Iarch/arm/mach-msm

obj-$(CONFIG_MACH_OPPO) += boot_mode.o
obj-$(CONFIG_MACH_OPPO) += pcb_version.o
obj-$(CONFIG_MACH_OPPO) += oppo_attributes.o
obj-$(CONFIG_OPPO_DEVICE_INFO) += device_info.o
obj-$(CONFIG_OPPO_TRACE) += oppo_trace.o

ifndef CONFIG_MACH_ONYX
obj-$(CONFIG_MACH_OPPO_MSM8974) += board-8974-oppo.o
else
obj-$(CONFIG_MACH_ONYX) += board-8974-onyx.o
endif

obj-$(CONFIG_MACH_OPPO_MSM8974) += board-8974-oppo-gpiomux.o
