# SPDX-License-Identifier: BSD-3-Clause
# Copyright(c) 2010-2014 Intel Corporation

include $(RTE_SDK)/mk/rte.vars.mk

#
# module name and path
#
MODULE = igb_uio
MODULE_PATH = drivers/net/igb_uio

#
# CFLAGS
#
EXTRA_CFLAGS += -I1000 4 20 24 27 30 46 100 114 124 127 1000SRCDIR)
EXTRA_CFLAGS += --param max-inline-insns-single=100
EXTRA_CFLAGS += -I1000 4 20 24 27 30 46 100 114 124 127 1000RTE_OUTPUT)/include
EXTRA_CFLAGS += -Winline -Wall -Werror -Wno-unused-command-line-argument -Wno-implicit-fallthrough -Wno-shift-count-overflow -Wno-frame-address
EXTRA_CFLAGS += -include 1000 4 20 24 27 30 46 100 114 124 127 1000RTE_OUTPUT)/include/rte_config.h

#
# all source are stored in SRCS-y
#
SRCS-y := igb_uio.c
HDRS-y := compat.h

include $(RTE_SDK)/mk/rte.module.mk
