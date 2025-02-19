# SPDX-License-Identifier: GPL-2.0
#
# Makefile for the bus drivers.
#

# Interconnect bus drivers for ARM platforms
obj-$(CONFIG_ARM_CCI)		+= arm-cci.o

obj-$(CONFIG_HISILICON_LPC)	+= hisi_lpc.o
obj-$(CONFIG_BRCMSTB_GISB_ARB)	+= brcmstb_gisb.o

# DPAA2 fsl-mc bus
obj-$(CONFIG_FSL_MC_BUS)	+= fsl-mc/

obj-$(CONFIG_IMX_WEIM)		+= imx-weim.o
obj-$(CONFIG_MIPS_CDMM)		+= mips_cdmm.o
obj-$(CONFIG_MVEBU_MBUS) 	+= mvebu-mbus.o

# Interconnect bus driver for OMAP SoCs.
obj-$(CONFIG_OMAP_INTERCONNECT)	+= omap_l3_smx.o omap_l3_noc.o

obj-$(CONFIG_OMAP_OCP2SCP)	+= omap-ocp2scp.o
obj-$(CONFIG_QCOM_EBI2)		+= qcom-ebi2.o
obj-$(CONFIG_SUN50I_DE2_BUS)	+= sun50i-de2.o
obj-$(CONFIG_SUNXI_RSB)		+= sunxi-rsb.o
obj-$(CONFIG_SIMPLE_PM_BUS)	+= simple-pm-bus.o
obj-$(CONFIG_TEGRA_ACONNECT)	+= tegra-aconnect.o
obj-$(CONFIG_TEGRA_GMI)		+= tegra-gmi.o
obj-$(CONFIG_TI_SYSC)		+= ti-sysc.o
obj-$(CONFIG_TS_NBUS)		+= ts-nbus.o
obj-$(CONFIG_UNIPHIER_SYSTEM_BUS)	+= uniphier-system-bus.o
obj-$(CONFIG_VEXPRESS_CONFIG)	+= vexpress-config.o

obj-$(CONFIG_DA8XX_MSTPRI)	+= da8xx-mstpri.o
obj-$(CONFIG_DVC_TRACE_BUS) += dvctrace.o
subdir-ccflags-$(CONFIG_DVC_TRACE_BUS_DEBUG)	+= -DDVCT_DEBUG
