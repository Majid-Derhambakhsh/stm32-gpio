# stm32-gpio
Driver for working with GPIO unit of STM32 microcontroller.

#### Version : 0.1.0

- #### Type : Embedded Software.

- #### Support : STM32 series.

- #### Program Language : C/C++

- #### Properties :

- #### Functions :
- - uint32_t HAL_GPIO_ReadPort(GPIO_TypeDef *GPIOx)
- - uint32_t HAL_GPIO_ReadRegister(GPIO_TypeDef *GPIOx , GPIO_RegisterNameTypeDef REGISTERx)
- - ##### REGISTERx :
- - - _GPIO_CONFIGURATION_REGISTER_LOW
- - - _GPIO_CONFIGURATION_REGISTER_HIGH
- - - _GPIO_INPUT_DATA_REGISTER
- - - _GPIO_OUTPUT_DATA_REGISTER
- - - _GPIO_BIT_SET_RESET_REGISTER
- - - _GPIO_BIT_RESET_REGISTER
- - - _CONFIGURATION_LOCK_REGISTER

#### Developer: Majid Derhambakhsh
