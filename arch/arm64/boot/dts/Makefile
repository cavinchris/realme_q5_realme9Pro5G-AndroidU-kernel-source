# SPDX-License-Identifier: GPL-2.0

#ifdef OPLUS_BUG_STABILITY
#subdir-y += actions
#subdir-y += al
#subdir-y += allwinner
#subdir-y += altera
#subdir-y += amd
#subdir-y += amlogic
#subdir-y += apm
subdir-y += arm
#subdir-y += bitmain
#subdir-y += broadcom
#subdir-y += cavium
#subdir-y += exynos
#subdir-y += freescale
#subdir-y += hisilicon
#subdir-y += intel
#subdir-y += lg
#subdir-y += marvell
#subdir-y += mediatek
#subdir-y += nvidia
subdir-y += qcom
#subdir-y += realtek
#subdir-y += renesas
#subdir-y += rockchip
#subdir-y += socionext
#subdir-y += sprd
#subdir-y += synaptics
#subdir-y += ti
#subdir-y += xilinx
#subdir-y += zte
#endif

dtstree	:= $(srctree)/$(src)
vendor  := $(dtstree)/vendor
ifneq "$(wildcard $(vendor)/Makefile)" ""
    subdir-y += vendor
endif
