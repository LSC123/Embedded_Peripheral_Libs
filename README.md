# Embedded_Peripheral_Libs
这里是我平时学习的过程中一点点收集总结出来的各种外设驱动程序，不定期更新中，各个外设的详细驱动方法可以进[我的小站](https://imuncle.github.io)搜索查看。

所有的程序都基于HAL库，配合STM32CubeMX进行开发，但这个repo中并不会包含任何有关编译器的文件，只提供最核心的`.c`文件和`.h`文件，各个函数都有较为详细的注释说明。

所有的程序都在STM32F405RGT6上测试通过。

本人还是初学者，水平有限，如有不对的地方还请多多包涵。

最后，希望这份资料对你有帮助，enjoy it!

# 已有外设一览表

名称|简介|代码链接
:--:|:--:|:--:
DS18B20|常见的一种温度传感器|[DS18B20](./DS18B20)
MPU9250|MPU9250的九轴算法实现|[MPU9250](./MPU9250)
MPU6500|MPU9250的六轴算法实现|[MPU6500](./MPU6500)
OLED|0.96寸OLED的驱动，实现字母和数字的显示|[OLED](./OLED)
soft_i2c|IIC的软件模拟实现|[soft_i2c](./soft_i2c)
Tamagawa|多摩川编码器数据读取|[Tamagawa](./Tamagawa)
