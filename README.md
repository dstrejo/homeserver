**This is a home-lab project intendeed to sharp linux and networking skills. Bash script will be written in order to automate security checks and to monitor the system. It will consist of different VMs and physical Raspberry Pi servers.  

### Server 1: Install Ubuntu Server on Raspberry Pi

1. **Download the Ubuntu Server Image**:
    - Visit the [Ubuntu website](https://ubuntu.com/download/raspberry-pi) and download the appropriate image for Raspberry Pi.

2. **Flash the Image to an SD Card**:
    - Use a tool like [Etcher](https://www.balena.io/etcher/) to flash the image onto the SD card or Raspberry Pi Imager [Imager](https://www.raspberrypi.com/software/).
    - Pre configure Network settings and SSH.

3. **Initial Configuration**:
    - Update the system.
    - Check your SSH keys and git. 
    - Configure VPN server using the project [PiVPN](https://www.pivpn.io). This can be also installed using the [Wireguard script by Nyr](https://github.com/Nyr/wireguard-install) or by installing and configu      ring wireguard-tools. OpenVPN could be also used.  

4. **Web Server Installation**
    - I am using NGNIX thought LAMP would be an alternative.    
   




    
