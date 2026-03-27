# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server

## NAME : NANDHINI S
## REG NO: 212224230174
## DATE : 09/03/2026
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
<img width="1364" height="713" alt="image" src="https://github.com/user-attachments/assets/91b943e8-366c-47a6-8742-91c7b61f5842" />
<img width="1364" height="716" alt="image" src="https://github.com/user-attachments/assets/1cfa1482-0bd0-4aff-9311-5eaa8df4f076" />

### 2. Network Server – Recent Events
<img width="1919" height="1019" alt="image" src="https://github.com/user-attachments/assets/be600909-29dd-4cc6-8ab3-250df08d27ae" />
<img width="1919" height="1038" alt="image" src="https://github.com/user-attachments/assets/a429f1e2-4484-439c-9b75-46c0977803f7" />

### 3. Dashboard Command Sending
<img width="1919" height="1020" alt="image" src="https://github.com/user-attachments/assets/af26fbc4-03bc-48cf-8bc9-cd3ce128b6bc" />
<img width="1908" height="1018" alt="image" src="https://github.com/user-attachments/assets/267d510d-672d-450b-8fac-ee45ad9be941" />

### 4. Relay Status Dashboard Output

### Bulb ON → Relay ON  
<img width="1280" height="570" alt="image" src="https://github.com/user-attachments/assets/c942573a-83e3-4bc1-9cae-42590843e1a3" />

### Bulb OFF → Relay OFF
<img width="570" height="1280" alt="image" src="https://github.com/user-attachments/assets/be51b27b-0ea8-434c-bb63-34738f57aab5" />

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
