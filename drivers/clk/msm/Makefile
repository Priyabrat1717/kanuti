obj-y				+= clock.o
obj-y				+= clock-dummy.o
obj-y				+= clock-generic.o
obj-y				+= clock-local2.o
obj-y				+= clock-pll.o
obj-y				+= clock-alpha-pll.o
obj-y				+= clock-rpm.o
obj-y				+= clock-voter.o
obj-y				+= clock-pm.o

obj-$(CONFIG_MSM_CLK_CONTROLLER_V2)	+= msm-clock-controller.o

obj-$(CONFIG_DEBUG_FS)		+= clock-debug.o

# MSM 8996
obj-$(CONFIG_ARCH_MSM8996)	+= clock-gcc-8996.o
obj-$(CONFIG_ARCH_MSM8996)	+= clock-mmss-8996.o
obj-$(CONFIG_ARCH_MSM8996)	+= clock-cpu-8996.o
obj-$(CONFIG_ARCH_MSMCOBALT)	+= clock-osm.o

# MSM COBALT
obj-$(CONFIG_ARCH_MSMCOBALT)	+= clock-gcc-cobalt.o
obj-$(CONFIG_ARCH_MSMCOBALT)	+= clock-gpu-cobalt.o
obj-$(CONFIG_ARCH_MSMCOBALT)	+= clock-mmss-cobalt.o

# MDM9650
obj-$(CONFIG_ARCH_MDM9650)	+= clock-gcc-9650.o
obj-$(CONFIG_ARCH_SDX20)	+= clock-gcc-9650.o

# MDM9607
obj-$(CONFIG_ARCH_MDM9607)	+=clock-gcc-mdm9607.o

# MSM8909
obj-$(CONFIG_ARCH_MSM8909)	+= clock-rpm-8909.o
obj-$(CONFIG_ARCH_MSM8909)	+= clock-gcc-8909.o

# MSM8936/8939
obj-$(CONFIG_ARCH_MSM8916)	+= clock-cpu-8939.o
obj-$(CONFIG_ARCH_MSM8916)	+= clock-cpu-8936.o
obj-$(CONFIG_ARCH_MSM8916)	+= clock-gcc-8936.o
obj-$(CONFIG_ARCH_MSM8916)	+= clock-rpm-8936.o

# ACPU clock
obj-$(CONFIG_ARCH_MDM9640)      += clock-a7.o
obj-$(CONFIG_ARCH_MDM9650)	+= clock-a7.o
obj-$(CONFIG_ARCH_SDX20)	+= clock-a7.o
obj-$(CONFIG_ARCH_MDM9607)	+= clock-a7.o
obj-$(CONFIG_ARCH_MSM8916)	+= clock-a7.o
obj-$(CONFIG_ARCH_MSM8909)	+= clock-a7.o
obj-$(CONFIG_ARCH_MSM8953)	+= clock-a7.o
obj-$(CONFIG_ARCH_MSM8916)	+= clock-gcc-8952.o
obj-$(CONFIG_ARCH_MSM8916)	+= clock-gcc-8953.o
obj-$(CONFIG_ARCH_MSM8916)	+= clock-rcgwr.o
obj-$(CONFIG_ARCH_MSM8916)	+= clock-cpu-8953.o
obj-$(CONFIG_ARCH_MSM8953)	+= clock-gcc-8953.o
obj-$(CONFIG_ARCH_MSM8953)	+= clock-rcgwr.o
obj-$(CONFIG_ARCH_MSM8953)	+= clock-cpu-8953.o

obj-y				+= gdsc.o
obj-y				+= mdss/

ifdef CONFIG_ARCH_MDM9607
KBUILD_CFLAGS	+= -fno-cse-follow-jumps
endif
