#
# Makefile for Loongson-3 family machines
#
obj-y			+= irq.o cop2-ex.o platform.o acpi_init.o clock.o ec_wpce775l.o workarounds.o \
			   ls2h-irq.o ls2h-platform.o rs780-irq.o rs780-platform.o loongson3-memset.o loongson3-memcpy.o

obj-$(CONFIG_SMP)	+= smp.o

obj-$(CONFIG_NUMA)	+= numa.o

obj-$(CONFIG_SUSPEND)	+= pm.o sleep.o

obj-$(CONFIG_RS780_HPET) += hpet.o

obj-$(CONFIG_LOONGSON3_CPUAUTOPLUG) += loongson3_cpuautoplug.o
