# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server
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
<img width="1749" height="963" alt="Screenshot 2026-03-19 165539" src="https://github.com/user-attachments/assets/89b16d0f-9b8e-4f69-9c4f-02f59e37906e" />

<img width="1919" height="1038" alt="image" src="https://github.com/user-attachments/assets/a429f1e2-4484-439c-9b75-46c0977803f7" />

### 3. Dashboard Command Sending
<img width="1870" height="1128" alt="Screenshot 2026-03-19 170623" src="https://github.com/user-attachments/assets/cfdca6b3-888d-4ef5-8912-e721fffb6a36" />

<img width="1840" height="1120" alt="Screenshot 2026-03-19 170837" src="https://github.com/user-attachments/assets/7218fddb-be1a-4bf5-a54d-fbf351dc1bc8" />

### 4. Relay Status Dashboard Output

### Bulb ON → Relay ON  
<img width="1280" height="570" alt="image" src="https://github.com/user-attachments/assets/c942573a-83e3-4bc1-9cae-42590843e1a3" />
c
### Bulb OFF → Relay OFF
<img width="570" height="1280" alt="image" src="https://github.com/user-attachments/assets/be51b27b-0ea8-434c-bb63-34738f57aab5" />

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
