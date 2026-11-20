task1开头的为第一次作业：
  led1：外接LED灯 以 500ms 周期闪烁， 可以使用 HAL_Delay 进行延时
  led2：外接LED灯 以 500ms 周期闪烁， 全程不使用阻塞式（HAL_Delay、Gettick等阻塞主程序运行的方式）进行延时，需要使用中断进行延时
  led3：按键通过 EXTI 中断控制 LED 灯开关，要求必须有软件消抖 20ms
