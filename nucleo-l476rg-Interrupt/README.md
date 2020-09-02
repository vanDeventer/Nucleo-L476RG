# External Interrupt
In this version of the code an external LED is connected to PC7, which is D9 on the CN5 connector of the Nucleo-L476RG development board.

The green LED2 on the board and the external LED alternate on and off every two seconds. Pushing the blue user button, will toggle the external LED so that it changes to synchronized blinking and the next time, it will change to alternate blinking.

If the external interrupt is enabled, the response will be immediate. If not one has to wait that the two seconds elapse.