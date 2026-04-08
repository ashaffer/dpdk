# SPDX-License-Identifier: GPL-2.0
# Copyright 2017 NXP

include $(RTE_SDK)/mk/rte.vars.mk

DIRS-$(CONFIG_RTE_EAL_IGB_UIO) += igb_uio
DIRS-$(CONFIG_RTE_KNI_KMOD) += kni

SRCS-y := kni_misc.c kni_net.c
HDRS-y := kni_dev.h
HDRS-y += rte_kni_common.h
HDRS-y += rte_config.h

include $(RTE_SDK)/mk/rte.subdir.mk
