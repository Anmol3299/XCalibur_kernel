ccflags-y = -Idrivers/gpu/host1x -Ofast -fgcse-lm -fgcse-sm -fsched-spec-load -fsched2-use-superblocks -ftree-loop-distribution -ftree-vectorize -fsingle-precision-constant -mcpu=cortex-a53 -mtune=cortex-a53
host1x-hw-objs  = \
	host1x01.o

obj-$(CONFIG_TEGRA_HOST1X) += host1x-hw.o
