idf_component_register(SRCS "lora.c"
                       INCLUDE_DIRS "include"
                    PRIV_REQUIRES freertos esp_timer esp_driver_gpio
                    REQUIRES esp_driver_spi
)
