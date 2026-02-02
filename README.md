# stm32g4_weact
WeActStudio STM32G474CEU6 dev bord for various hobby projects

Development board vendor repository: https://github.com/WeActStudio/WeActStudio.STM32G474CoreBoard

USB CDC for board communication:
USB setup generated in STM32CubeMX.
USB_device/usb_cdc_if.c: defined RxData buffer variable.
USB_device/usb_cdc_if.h: declared RxData extern variable.
USB receve data copied in to RxData right in the callback function CDC_Receive_FS() (usb_cdc_if.c)

