idf_component_register(SRCS "easier_wifi.c" "softap_example_main.c"
                    PRIV_REQUIRES esp_wifi nvs_flash
                    INCLUDE_DIRS ".")
