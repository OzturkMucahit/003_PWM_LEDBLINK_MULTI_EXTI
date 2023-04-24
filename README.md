# 003_PWM_LEDBLINK_MULTI_EXTI

STM32CubeIDE (STM32F4 Discovery)
Led on with Timer (PWM) using Multi External Interrupt.

-1 internal button and 1 external button. Buttons are working with interrupt and the external one is more priority.
-	TIM4 with 4 channel for Led blinking using GPIOD_PIN_12/13/14/15
-	For each button has a different scenerio.
