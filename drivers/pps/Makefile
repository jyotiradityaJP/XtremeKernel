#
# Makefile for the PPS core.
#

pps_core-y			:= pps.o kapi.o sysfs.o
pps_core-$(CONFIG_NTP_PPS)	+= kc.o
obj-$(CONFIG_PPS)		:= pps_core.o
obj-y				+= clients/ generators/

ccflags-$(CONFIG_PPS_DEBUG) := -DDEBUG
