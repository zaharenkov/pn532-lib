# pn532-lib

PN532 NFC Library for STM32 with non blocking read mode.

Thanks to https://github.com/soonuse/pn532-lib

# How to use?

1. Connect NFC reader via I2C pins and also connect P70_IRQ pin to any STM32 GPIO with EXTI support.

2. Build your project based on the suggested example.

3. Enjoy non blocking reading NFC.