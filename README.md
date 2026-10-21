# CS 350 Emerging Systems Architectures and Technologies

## Portfolio Artifacts

For my CS 350 portfolio, I selected my Temperature Sensor Integration project and Smart Thermostat final project. I chose these artifacts because they demonstrate my ability to integrate software with physical hardware and show my progression throughout the course.

The Temperature Sensor Integration project focused on using a Raspberry Pi with an AHT20 temperature and humidity sensor through I2C communication and displaying sensor information on an LCD. The Smart Thermostat project expanded on those concepts by integrating the temperature sensor, LCD, multiple buttons, red and blue LEDs, I2C communication, UART communication, and a state machine. The thermostat monitored the current temperature, allowed the user to adjust the temperature set point, and switched between off, heating, and cooling states.

## What did you do particularly well?

One thing I did particularly well was breaking the projects into smaller components and testing them individually before integrating everything. This was especially useful during the thermostat project because several hardware and software components had to work together. Testing the temperature sensor, buttons, LEDs, and LCD separately made troubleshooting the complete system much easier.

I also became more comfortable integrating sensor data into a larger application and using a state machine to organize system behavior. The thermostat's off, heat, and cool states provided a clear structure for controlling the LEDs and responding to changes in temperature and user input.

## Where could you improve?

One area I could improve is planning more of the hardware and software integration before beginning implementation. Some troubleshooting could have been avoided by documenting connections, GPIO assignments, state transitions, and communication requirements earlier. In future embedded projects, I would spend more time creating a detailed design before beginning implementation.

I would also like to continue improving my knowledge of lower-level hardware communication and debugging so that I can identify I2C, UART, and GPIO problems more quickly.

## What tools and/or resources are you adding to your support network?

This course added several useful tools and resources to my support network. I gained more experience using the Raspberry Pi, Python, GPIO libraries, I2C, UART, GitHub, technical documentation, and hardware component documentation. I also learned how useful individual hardware test programs can be when troubleshooting a larger embedded system.

Going forward, I plan to continue using official hardware documentation, GitHub, development tools, and technical resources when working with unfamiliar hardware or software.

## What skills from this project will be transferable to other projects or coursework?

The most transferable skills from these projects are systematic troubleshooting, hardware and software integration, working with sensor data, state-machine design, and using communication protocols such as I2C and UART. I also improved my ability to break a larger problem into smaller components and test each part independently.

These skills can be applied beyond embedded systems. Isolating problems, testing individual components, reading technical documentation, and designing software with clearly defined responsibilities are useful practices in software engineering and other technical projects.

## How did you make this project maintainable, readable, and adaptable?

I made the projects more maintainable by separating different responsibilities within the code and using clearly defined functions and states. In the thermostat project, functionality such as changing states, adjusting the set point, updating the LEDs, displaying information, reading temperature data, and sending UART output was handled through separate parts of the program rather than placing everything into one section.

Using descriptive names and maintaining a consistent structure also made the code easier to understand. The state-machine approach makes the thermostat adaptable because additional states, sensors, or behaviors could be added later without completely redesigning the application.
