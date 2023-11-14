zephyr_include_directories(
  common/inc
  dmadrv/inc
  dmadrv/config
  gpiointerrupt/inc
  uartdrv/inc
  uartdrv/config
  )

zephyr_sources(dmadrv/src/dmadrv.c)
zephyr_sources(dmadrv/src/dmactrl.c)
zephyr_sources(gpiointerrupt/src/gpiointerrupt.c)
zephyr_sources(uartdrv/src/uartdrv.c)
