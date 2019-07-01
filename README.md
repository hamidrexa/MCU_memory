# MCU_memory
memory map, bootloader, flash memory and system memory usage

this doc is based on stm32f205  
[STM32F205 datasheet](https://www.st.com/resource/en/datasheet/cd00237391.pdf)  
[AN2606:STM32 microcontroller system memory boot mode](https://www.st.com/resource/en/application_note/cd00167594.pdf)  

# boot mode
At startup, boot pins are used to select one out of three boot options:  
• Boot from user Flash  
• Boot from system memory  
• Boot from embedded SRAM  

# Where is bootloader
The bootloader is stored in the internal boot ROM memory (system memory) of STM32
devices. It is programmed by ST during production.

![memory map](https://i.stack.imgur.com/8EKT8.png)

# Supported memory area by Write, Read, Erase and Go Commands
![Supported memory area by Write, Read, Erase and Go Commands](https://i.imgur.com/wJmyTKO.png)


[Booting Process](https://www.youtube.com/watch?v=3brOzLJmeek)
