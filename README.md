## Phase 1: Setting Up Your Environment

### Step 1: Install Ubuntu Server on Raspberry Pi

1. **Download the Ubuntu Server Image**:
    - Visit the [Ubuntu website](https://ubuntu.com/download/raspberry-pi) and download the appropriate image for Raspberry Pi.

2. **Flash the Image to an SD Card**:
    - Use a tool like [Etcher](https://www.balena.io/etcher/) to flash the image onto the SD card or Raspberry Pi Imager [Imager](https://www.raspberrypi.com/software/)
    - Pre configure Network settings and SSH.

3. **Boot the Raspberry Pi**:
    - Insert the SD card into the Raspberry Pi and power it on.
    - Complete the initial setup by following the on-screen instructions.

4. **Initial Configuration**:
    - Update the system: sudo apt update && sudo apt upgrade -y
