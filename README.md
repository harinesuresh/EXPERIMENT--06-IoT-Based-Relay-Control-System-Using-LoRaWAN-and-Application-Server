# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server

### NAME : HARINE S
### REG NO: 212224230081
### DATE : 16/03/2026
## Aim
To configure a LoRaWAN end device and monitor IR sensor data using a network server and dashboard visualization.

## Components Required
- LoRaWAN End Device-STM32
- LoRaWAN Gateway
- Application Server Dashboard
- Serial Port Utility
- Development Tools (STM32CubeIDE, STM32CubeProgrammer)

## Procedure
1. Open STM32CubeIDE and import the project from the realy-control project directory.
2. Select the LoRaWAN End Node project for the NUCLEO-WLE5JC board.
3. Clean all previous build files using the Clean Project option in the build configuration.
4. Build the project to generate the firmware files.
5. Flash the compiled firmware into the STM32 board using STM32CubeProgrammer with baud rate set to 9600.
6. Open the network server console and login using your registered email ID and password.
7. Register the device by selecting Device Types and adding the LoRaWAN device in the network server.
8. Open the Serial Port Utility  give the AT commands and verify device connection through the serial port utility
9. Create a dashboard on the application server by clicking the Add Dashboard option.
10. Add widgets and commands to visualize the relay status data.
11. Send control commands from the dashboard to control the relay.

## Output
### 1. Serial Port Utility – Network Server Connection
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/49d131eb-8d83-4633-8e8f-a5090eab766d" />

### 2. Network Server – Recent Events

<img width="1600" height="1000" alt="image" src="https://github.com/user-attachments/assets/85105835-0fba-4e53-a388-a43b245be722" />


### 3. Dashboard Command Sending
<img width="1600" height="1000" alt="image" src="https://github.com/user-attachments/assets/766f8fdc-2245-41a4-9839-d0d2d4dc185b" />

<img width="1600" height="1000" alt="image" src="https://github.com/user-attachments/assets/6ef057ea-5e33-4a5a-bbda-d4ef156db6a4" />

### 4. Relay Status Dashboard Output

### Bulb ON → Relay ON  
<img width="480" height="640" alt="image" src="https://github.com/user-attachments/assets/60c2b6c3-cd46-4a7e-8b5c-0d3e99b64c59" />

### Bulb OFF → Relay OFF
<img width="480" height="640" alt="image" src="https://github.com/user-attachments/assets/572c3e65-edd5-46bc-9040-2a9d29f4b5ae" />

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
