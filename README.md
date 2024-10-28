## Summarize the project and what problem it was solving:
The project involved developing an interface to control a thermostat using GPIO, I2C, and UART. The system read temperature data, adjusted the set-point via buttons, and controlled a heater. It addressed the problem of real-time temperature control and monitoring in an embedded system, simulating communication with a server.

## What did you do particularly well?
I implemented the task scheduler using a state machine effectively. This allowed for efficient management of tasks like reading inputs, updating the temperature, and controlling the heater without overwhelming the system. The hardware components were well-integrated to ensure smooth operation.

## Where could you improve?
Improvement could be made in handling unexpected conditions, such as sensor errors or communication failures. Adding robust error handling would make the system more reliable and adaptable to unforeseen issues.

## What tools and/or resources are you adding to your support network?
I used TI’s Code Composer Studio and SysConfig for development. Additionally, I utilized online resources such as Stack Overflow and TI forums for troubleshooting and best practices.

## What skills from this project will be particularly transferable to other projects and/or course work?
The design of the task scheduler and state machine is highly transferable to future real-time embedded systems. Additionally, my experience with hardware interfaces such as GPIO, I2C, and UART will be useful in similar projects.

## How did you make this project maintainable, readable, and adaptable?
I followed coding best practices, including detailed comments and a clear structure, ensuring that the project is both maintainable and adaptable for future use.

