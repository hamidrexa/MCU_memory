# MCU_memory
memory map, bootloader, flash memory and system memory usage

this doc is based on stm32f205

# boot mode
At startup, boot pins are used to select one out of three boot options:
• Boot from user Flash
• Boot from system memory
• Boot from embedded SRAM

# Where is bootloader
The bootloader is stored in the internal boot ROM memory (system memory) of STM32
devices. It is programmed by ST during production.

![memory map](https://i.stack.imgur.com/8EKT8.png)
