add_subdirectory_ifdef(CONFIG_TFLITE_SUBPROJECT lib)

# Include headers
zephyr_include_directories_ifdef(CONFIG_TFLITE_SUBPROJECT inc)