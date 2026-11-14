## READ BEFORE YOU CONTINUE!

- **pc-interface:** *(Swift)* GUI interface to talk with the AI system over driver and the AirLock.
- **pc-driver:** *(Go)* The background service that exposes AI system over ollama-compatible API and MUST BE COMPLETED TO connect to AirLock over serial port. *main.go is an example serial comm script for pc.*
- **al-gui:** *(Python)* GUI for the display on the AirLock. Part of the AirLockOS.

  ### To Do
  - Fork the Raspbian to build AirLockOS.
  - Raspbian kiosk to run AI over cloud.
  - Serial comm for pc-driver.
  - Polishing the pc-interface. (DONE - Amanda)
