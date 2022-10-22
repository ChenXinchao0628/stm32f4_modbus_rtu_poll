# STM32-HAL库ModbusRTU主站移植


本仓库包含以下内容：

1. modbus文件
2. HAL工程
3. keil5工程


## 使用说明

1. 该例程可直接烧录至STM32F4芯片运行，使用了芯片的USART1
2. 如果移植请注意在bsp_board.h文件中修改芯片头文件和使用的串口
3. 移植注意修改串口中断服务函数，在相应的芯片中断stm32fxxx_it.c文件里
4. 详细配置请查阅HAL配置及程序注释

