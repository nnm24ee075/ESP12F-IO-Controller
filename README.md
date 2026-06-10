# ESP12F-IO-Controller 
Project: ESP-12F I/O and Motor ControllerOverviewThis project is a custom PCB designed to serve as an intelligent automation hub. It combines Wi-Fi control, I/O expansion, and power-driving capabilities into a single, compact unit.Component ArchitectureComponentFunctionESP-12FCore logic & Wi-Fi connectivityMCP2301716-channel I/O expander ULN2803A8-channel Darlington array for relaysCH340KUSB-to-UART bridge for programmingType-CPower & communication interfaceDesign StatusStatus: [e.g., Schematic Finished / PCB Routing In-Progress / Prototyping]Last Modified: June 9, 2026Location: Local Project Directory (Documents\ESP12F-IO-rController\ESP12F-IO-Controller)Key Design NotesPower Strategy: Logic is powered at 3.3V (via LDO). Motors/Relays are powered via external terminal blocks.Important Jumper Settings: [there are few hardware jumpers,  "if 5V is used as input then JP4 must soldered;to pull up SDA & SCL J11&J12 IS SHORTED "]Pinout References: (Keep a quick reference list of pins here to avoid opening KiCad every time you need to check a connection).To-Do List[ ] Verify trace width for motor high-current paths.[ ] Add 5.1k resistors to CC1/CC2 pins on Type-C connector.[ ] Order components for the first prototype build.

Folder Structure
/Gerbers: Contains manufacturing-ready zip files.

/Datasheets: PDF references for the ESP-12F, MCP23017, and L298D.

/Archive: Previous iterations of the project for version history.

Why this is helpful for your local folder:
Memory: You won't have to remember which pins you assigned to the relays three months from now.

Design Log: The "To-Do List" section keeps you focused when you sit down to work.

Future-Proofing: If you ever decide to upload this to GitHub or share the files with a friend, the documentation is already finished.

Would you like to add a specific section for your "Firmware/Code" logic, or is there a particular wiring quirk you want to document in the "Design Notes" section?
