# Digital Signal Monitor

**Digital Signal Monitor** is a LabVIEW-based application designed to control, monitor, and read digital input signals from a specified port. The program offers three main operational modes: start, stop, and read. It continuously processes digital signals based on user commands, providing real-time feedback and signal states.

## Features:
- **Digital Input Monitoring**: Reads digital input from the port `Dev1/port0/line0`.
- **Three Modes of Operation**:
  - **Start**: Begins monitoring and processing digital inputs.
  - **Stop**: Ends the monitoring process.
  - **Read**: Continuously reads the current state of the digital signal.
- **Real-Time Feedback**: Provides immediate updates on the signal status, including processing based on the value of the signal.
- **User Interaction**: The program uses a simple user interface to control the start, stop, and read actions.

## How It Works:
1. **Start Mode**:
   - Initiates the digital signal monitoring process from the input port.
   - The program listens to signals and transitions to processing based on the input value.
   
2. **Stop Mode**:
   - Halts the monitoring of the digital input signal and stops any signal processing.

3. **Read Mode**:
   - Continuously monitors the digital input signal.
   - The state of the input signal (high or low) is processed, with calculations applied based on conditional logic.
   - The program performs operations on the signal value, displays results in numeric form, and responds to different conditions using Boolean logic.

4. **Real-Time Processing**:
   - The system checks the input signal and applies basic processing logic.
   - A conditional branch determines further actions depending on whether the signal is true (high) or false (low).
   - Numerical outputs based on the input signal are shown in real-time.

5. **Push Action**:
   - A specific condition triggers a "Push" action, which can be manually controlled from the user interface.
   - This allows for additional input control within the application.

## Requirements:
- **Hardware**: NI DAQ device with digital input capabilities on port `Dev1/port0/line0`.
- **Software**: LabVIEW with NI-DAQmx drivers installed.

## Usage:
1. Connect a digital input signal to port `Dev1/port0/line0`.
2. Run the program in LabVIEW.
3. Use the interface to select the operational mode:
   - `Start` to initiate signal monitoring.
   - `Stop` to end the monitoring process.
   - `Read` to continuously monitor and process the signal in real-time.
4. The program will provide real-time feedback on the digital signal, with results displayed in the GUI.

## Example:
- The user starts the program and selects the "Start" option to begin reading digital signals from `Dev1/port0/line0`.
- In "Read" mode, the program processes the input and applies conditional logic based on the signal's Boolean state.
- Numerical results are displayed, allowing the user to monitor the signal changes in real-time.
- The "Push" button can be used for additional input control or specific operations.

## Troubleshooting:
- Ensure that the digital input device is properly connected to the specified port.
- Verify that all necessary NI-DAQmx drivers are installed and configured.
- If the program does not respond as expected, check the input signal and the mode selected in the interface.

## Code:
![image](https://github.com/user-attachments/assets/69dc6eff-e648-4265-882d-a633feef5a00)
![image](https://github.com/user-attachments/assets/13053c0f-f3cf-48e2-a6cb-e67108ec6bfc)
![image](https://github.com/user-attachments/assets/19e07906-efef-4a5d-8324-0208f6181d0d)
![image](https://github.com/user-attachments/assets/953ce1cb-0c89-4ac9-86b3-558a6163595f)
