## Tentative project name: Airlock 
A physical button that the user presses to approve/deny AI agentic requests to the user's local computer's MCP server, which then executes those requests. 
The AI agent does not get unrestricted access to the computer. It must go through AirLock.
### Categories: 
Cybersecurity, AI Agents, Hardware, Low-Level Computing, Cloud, Blockchain

## READ BEFORE YOU CONTINUE!

- **pc-interface:** *(Swift)* GUI interface to talk with the AI system over driver and the AirLock.
- **pc-driver:** *(Go)* The background service that exposes AI system over ollama-compatible API and MUST BE COMPLETED TO connect to AirLock over serial port. *main.go is an example serial comm script for pc.*
- **al-gui:** *(Python)* GUI for the display on the AirLock. Part of the AirLockOS.

  ### To Do
  - Fork the Raspbian to build AirLockOS.
  - Raspbian kiosk to run AI over cloud.
  - Serial comm for pc-driver. (IN PROGRESS - Amanda. The Go HTTP server is responding to requests independently of the physical AirLock connection. We just need to connect the physical hardware)
  - Polishing the pc-interface. (DONE - Amanda)
