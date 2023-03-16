# SPDX-License-Identifier: GPL-2.0+

dtb-$(CONFIG_MX6ULL) += \
	imx6ull-fire-mmc.dtb \
	imx6ull-fire-nand.dtb

targets += $(dtb-y)

# Add any required device tree compiler flags here
DTC_FLAGS +=

PHONY += dtbs
dtbs: $(addprefix $(obj)/, $(dtb-y))
	@:

clean-files := *.dtb *.dtbo *_HS
