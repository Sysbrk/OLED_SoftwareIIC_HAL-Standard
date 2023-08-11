# OLED_SoftwareIIC_HAL-Standard
软件IIC驱动OLED

- 字模在OLED_Font.h中删改
- 函数及引脚定义在OLED.c

# 使用时需要:
1.将SCL、SDA的引脚设置成开漏模式Open Drain mode、高速
2.在OLED.c中修改它们对应的引脚
3.修改板子对应的xxx_hal.h头文件
