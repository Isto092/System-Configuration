# System Configuration

## Objective

To design and implement a centralized management system for multiple 3D printers using Raspberry Pi and OctoPrint, aimed at streamlining operations, enabling remote monitoring and control, and enhancing production efficiency through network optimization and real-time status tracking.

### Skills Learned

 - System Configuration and Integration
 - Network Optimization
 - Raspberry Pi and Linux Administration
 - Web Interface Deployment
Remote Troubleshooting and Automation

### Tools Used

 - Raspberry Pi – As the central hardware platform for managing the 3D printers.
 - OctoPrint – For remote monitoring, management, and control of 3D print jobs.
 - Python – For scripting or extending OctoPrint functionality.
 - Web Browser Interface – To access OctoPrint’s dashboard for real-time status updates and controls.
 - SSH (Secure Shell) – For remote command-line access to the Raspberry Pi for setup and troubleshooting.
 - Wi-Fi Router or Ethernet Network – To provide stable network connectivity for remote access and printer communication.

## Steps
 
Prepare the Raspberry Pi:
 - Installed Raspberry Pi OS.
 - Connected the Raspberry Pi to the network  via Wi-Fi or Ethernet.

Install OctoPrint:
 - Used OctoPi (a pre-configured image for OctoPrint on Raspberry Pi).
 - Flashed the OctoPi image onto an SD card and booted the Raspberry Pi.

Configure Multiple OctoPrint Instances:
 - Installed and cloned multiple instances of OctoPrint using Python virtual environments (venv) to isolate each instance.
 - Used Python scripts or terminal commands to assign unique ports and directories for each instance.

Connect and Configure 3D Printers:
 - Connected each 3D printer via USB to the Raspberry Pi.
 - Configured each OctoPrint instance to communicate with its assigned printer.
 - Verified serial connections and baud rates via the OctoPrint web interface.

Set Up Web Interface for Remote Monitoring:
 - Used OctoPrint’s Python-based Flask web server to host the UI for each instance.
 - Installed Python-powered plugins for enhanced functionality like webcam streaming, print time estimation, and G-code previews.

Optimize Network and System Performance:
 - Configured OctoPrint’s internal Python logging and error handling to monitor system stability.
 - Used Python scripts for health checks, backups, or automated restarts of instances.

Test and Validate the Setup:
 - Conducted test prints through each OctoPrint web UI.
 - Used Python logs to troubleshoot issues and ensure stable operation.
