zephyr_include_directories(include)
zephyr_library()

if(CONFIG_SHIELD_DONGLE_SCREEN)

        add_subdirectory(./drivers/display)
        add_subdirectory(./modules/lvgl)


endif()
