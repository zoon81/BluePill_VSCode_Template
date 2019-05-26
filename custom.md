GCC_PATH = /usr/local/Cellar/arm-gcc-bin/8-2018-q4-major/bin
flash:
	 st-flash --format ihex write build/$(TARGET).hex