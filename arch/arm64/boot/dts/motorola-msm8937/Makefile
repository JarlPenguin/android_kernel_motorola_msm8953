# Add 1k of padding to the DTBs to allow for environment variables
# to be runtime added by the bootloader (i.e. /chosen properties)
DTC_FLAGS := -p 1024

dtb-$(CONFIG_HANNAH_DTB) += msm8917-hannah-p0.dtb
dtb-$(CONFIG_HANNAH_DTB) += msm8937-hannah-p0.dtb
dtb-$(CONFIG_HANNAH_DTB) += msm8940-hannah-p0.dtb

dtb-$(CONFIG_JETER_DTB) += msm8920-jeter-p0.dtb
dtb-$(CONFIG_JETER_DTB) += msm8920-jeter-p3.dtb
dtb-$(CONFIG_JETER_DTB) += msm8937-jeter-p0.dtb

dtb-$(CONFIG_MONTANA_DTB) += msm8937-montana-p0.dtb
dtb-$(CONFIG_MONTANA_DTB) += msm8937-montana-p1a.dtb
dtb-$(CONFIG_MONTANA_DTB) += msm8937-montana-p1b.dtb
dtb-$(CONFIG_MONTANA_DTB) += msm8937-montana-p2.dtb
dtb-$(CONFIG_MONTANA_DTB) += msm8937-montana-p3.dtb

dtb-$(CONFIG_NORA_DTB) += msm8917-nora-p0.dtb

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb
