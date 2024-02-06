KALAMA_BASE_DTB += ../../../vendor/qcom/kalama.dtb ../../../vendor/qcom/kalama-v2.dtb
KALAMA_APQ_BASE_DTB += ../../../vendor/qcom/kalamap.dtb ../../../vendor/qcom/kalamap-v2.dtb

SAMSUNG_KALAMA_BOARDS += \
    gts9wifi_eur_open_w00_r00.dtbo \
    gts9wifi_eur_open_w00_r01.dtbo \
    gts9wifi_eur_open_w00_r02.dtbo \
    gts9wifi_eur_open_w00_r04.dtbo \

kalama-overlays-dtb-y += $(SAMSUNG_KALAMA_BOARDS) $(KALAMA_BASE_DTB) $(KALAMA_APQ_BASE_DTB)
dtb-y += $(SAMSUNG_KALAMA_BOARDS) $(KALAMA_BASE_DTB) $(KALAMA_APQ_BASE_DTB)

always-y	:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
