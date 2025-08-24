# rigX: A Linux Daemon for Amateur Radio Control  

rigX is a planned daemon for Linux systems that will provide a robust and reliable way to control amateur radio equipment. The goal is to leverage the powerful Hamlib library, a standardized API that simplifies the complex task of communicating with a wide range of transceivers and other shack hardware.
By running as a background service, rigX will ensure your radio is always ready to be controlled, whether through a local application or over the network. This will allow you to focus on your amateur radio operations without worrying about the underlying hardware interface.  

## Project Status  
rigX is currently in the planning and development phase. The code is not yet written, and we are looking for collaborators to help bring this project to life. The sections below outline the core goals and desired functionality.  

## Project Goals  
  
**Linux Daemon:** To run silently in the background, ensuring continuous operation.  
**Hamlib Integration:** To support a vast array of radios and rotators via the Hamlib library.  
**Persistent Control:** To maintain a connection to your radio, even when client applications are not active.  
**Flexible Interface:** To provide a network socket for control, allowing multiple client applications to connect and share the radio.  
**Configurable:** To easily specify your radio model, serial port, and other settings.  

## Contributing & Collaboration  
This project is a community effort, and your assistance is greatly appreciated. If you're interested in contributing, we're looking for assistance with:  
  
**Code Development:** Building the daemon and its core features.  
**Documentation:** Writing clear and helpful guides for users and other developers.  
**Testing:** Ensuring the daemon works reliably across various systems and radio models.  
  
If you'd like to help, please feel free to fork the repository, make your changes, and submit a pull request. We ask that all contributions follow the project's goals and licensing.  

## License  
This project is licensed under the GNU General Public License v3.0 (GPLv3). This means you are free to use, modify, and distribute this software, but any derivative works must also be licensed under the GPLv3.  
