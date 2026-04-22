# Experiment 1: GPIO Output (LED Blinking)

## Aim
To configure a GPIO pin of STM32F446RE as a digital output and verify LED blinking operation using software delay routines.

## Apparatus Required
- STM32 Nucleo-F446RE Development Board
- USB Type-A to Mini-B Cable
- STM32CubeIDE
- STM32CubeMX

## Theory
GPIO (General Purpose Input/Output) pins are used in microcontrollers to interface with external devices such as LEDs, switches, and sensors. In STM32 microcontrollers, GPIO pins can be configured as input or output using STM32CubeMX and STM32CubeIDE.

In this experiment, GPIO pin PA5 is configured as a digital output to control the onboard LED. The LED blinking operation is achieved by continuously toggling the GPIO state with a software delay between ON and OFF conditions.

## Procedure
1. Create a new STM32 project for STM32F446RE in STM32CubeMX.
2. Configure PA5 as a GPIO output pin.
3. Configure clock settings and generate project code.
4. Open the generated project in STM32CubeIDE.
5. Write code to toggle the GPIO pin using software delay.
6. Build and upload the program to the STM32 board.
7. Observe the onboard LED blinking.

## Code
The implementation code is available in the `main.c` file.

### Important Code Snippet
```c
HAL_GPIO_TogglePin(GPIOA, GPIO_PIN_5);
HAL_Delay(500);

## Output
The onboard LED connected to PA5 blinks successfully at a fixed interval using software delay.
