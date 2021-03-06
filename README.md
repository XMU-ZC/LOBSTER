# LOBSTER/龙虾3D打印机主板
基于STM32的3D打印机主板/A kind of motherboard for 3D printer based on STM32  
基于apk2.1主板并吸收祁大佬8z主板、LSP主板、XCJX-8AXIS等开源3D打印主板优点并改进，感谢各位大佬无私开源  
![3D](https://user-images.githubusercontent.com/104925289/173751223-3e6873e7-ce6d-464a-b61b-260ec9649407.png)
![3D正](https://user-images.githubusercontent.com/104925289/174103066-1c48fb9c-e041-4e17-8e6e-71cdba208790.png)  
主控使用STM32F103C6T6价格极低，脚位兼容C8T6和f303系列  
5v使用ry9320/8310供电方案，体积小，外围简单，成本低  
me6118提供3.3v电源，完美代替1117  
相比原版增加9路光耦信号隔离+四路mos管信号隔离+两级防反接保护，最大限度保护主板  
8路步进电机驱动（主板+拓展板）+XY2路步进电机闭环驱动接口（适配HYPERSTEPPER，感谢杨工），和龙虾一样“十”肢发达  
拓展板接口换用XT30+PH2.0排线方案，相较杜邦插槽提升带载能力与稳定性  
足量电容，保证系统抗干扰能力  
电机驱动单独供电，提升打印稳定性  
主板提供三路温度探头（一路为板载热敏）、四路可控风扇、一路照明灯接口  
配合拓展板将支持8轴打印机，适合voron2.4打印机使用  
固件仅支持KLIPPER，不支持MARLIN，需要MARLIN固件请移步隔壁Cambarus-esp32主板  
立创开源链接:https://oshwhub.com/wust_zc/LOBSTER-3DPRINT
—————————————————————————————————————————————————  
当前进度：1、beta原理图：完成；2、PCBv1：完成；3、拓展板：绘制中  
感兴趣的朋友可自行下载PDF原理图与Gerber打样尝鲜 
附件中提供iBOM辅助焊接文件  
想自行修改可下载LCEDA原始文件修改（请务必遵循开源协议）  
学业繁重，有BUG正常，请大佬们轻拍（欢迎友好交流指正）  
注意：测试版本有存在设计缺陷的可能，请谨慎考虑，风险自担！  
![正面](https://user-images.githubusercontent.com/104925289/173750571-895a51dc-576b-4745-8f4b-70dd0fa734a7.png)
![反面](https://user-images.githubusercontent.com/104925289/173751047-669db596-b948-42b6-8d42-3ff46b9014ee.png)
![正面](https://user-images.githubusercontent.com/104925289/174103126-30ffe580-a7d7-4c73-958b-02c0fd82df86.png)
![反面](https://user-images.githubusercontent.com/104925289/174103133-9c7bcdbe-38d0-4453-afec-1a79cff71265.png)
