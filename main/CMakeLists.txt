# Edit following two lines to set component requirements (see docs)
set(COMPONENT_REQUIRES esp_wifi wifi_provisioning driver json nvs_flash)
set(COMPONENT_PRIV_REQUIRES shnode ledstrip)

set(COMPONENT_SRCS "main.c")
set(COMPONENT_ADD_INCLUDEDIRS "")

register_component()
