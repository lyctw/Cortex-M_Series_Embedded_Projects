# STM32 Projects


## DSP

* [DSP_Plot_sin_wave](https://github.com/syokujinau/STM32_Embedded_Projects/tree/master/) - Basic sine wave with given frequencies
* [DSP_utils](https://github.com/syokujinau/STM32_Embedded_Projects/tree/master/DSP_utils) - Steps to set up 100MHz HCLK and ST-LINK debugger for logic analyzer of Keil IDE
* [DSP_Sine_FIR_lowpass_filter](https://github.com/syokujinau/STM32_Embedded_Projects/tree/master/DSP_Sine_FIR_lowpass_filter) - FIR low pass filter with given filter coefficient
    - [low_pass_filter.c](https://github.com/syokujinau/STM32_Embedded_Projects/blob/master/DSP_Sine_FIR_lowpass_filter/low_pass_filter.c) - fir init api
* [DSP_Mean_Var_Std_algo](https://github.com/syokujinau/STM32_Embedded_Projects/tree/master/DSP_Mean_Var_Std_algo) - Mean, Variation and Standard Deviation of signal, Signal Statistics and CMSIS-DSP introduction
* [DSP_Noise_Realtime](https://github.com/syokujinau/STM32_Embedded_Projects/tree/master/DSP_Noise_Realtime) - CMSIS-RTOS kernel for disturbed signal monitoring
    - (Issue) SysTick handler multiple defined


## Device driver

* [stm32f411re_drivers](https://github.com/syokujinau/STM32_Embedded_Projects/tree/master/stm32f411re_drivers)
* [Ultrasonic_basic](https://github.com/syokujinau/STM32_Embedded_Projects/tree/master/Ultrasonic_basic) - GPIO and Timer4 for distance measurement
    - [Ultrasonic_timer_input_capture](https://github.com/syokujinau/STM32_Embedded_Projects/tree/master/Ultrasonic_timer_input_capture) - timer interrupt to estimate the pulse precisely
