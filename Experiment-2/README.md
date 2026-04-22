# Experiment 2: Button Interface

## Aim
To configure a GPIO pin of STM32F446RE as a digital input and interface a push button to control an LED.

## Apparatus Required
- STM32 Nucleo-F446RE Development Board
- Push Button
- USB Type-A to Mini-B Cable
- STM32CubeIDE
- STM32CubeMX

## Theory
GPIO pins in STM32 microcontrollers can be configured as digital inputs to read external signals. A push button acts as an input device that changes the logic state of a GPIO pin when pressed or released. Pull-up or pull-down resistors are used to maintain a stable logic level and prevent floating input conditions.

In this experiment, a GPIO pin is configured as input to read the state of a push button. Based on the button state, the onboard LED is controlled.

## Procedure
1. Create a new STM32 project for STM32F446RE in STM32CubeMX.
2. Configure PC13 as GPIO input for the button.
3. Configure PA5 as GPIO output for the onboard LED.
4. Generate project code and open it in STM32CubeIDE.
5. Write code to read button input and control LED output.
6. Build and upload the program to the STM32 board.
7. Press the button and observe LED behavior.

## Code
The implementation code is available in the `main.c` file.

### Important Code Snippet
```c
if (HAL_GPIO_ReadPin(GPIOC, GPIO_PIN_13) == GPIO_PIN_RESET)
{
    HAL_GPIO_TogglePin(GPIOA, GPIO_PIN_5);
    HAL_Delay(200);
}
