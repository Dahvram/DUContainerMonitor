# DUMaterialsMonitor
- Copy the file DUMaterialsMonitor.config and paste ti to a Programming Board.
- Add a medium Screen by linking from the Probramming Board to the Screen.
- Add up to 6 containers.
- Open the lua script in the editor.
- Rename the slot for the screen to screen
- Each container slot must be named mat1 - mat6
- Update Lua Parameters with the Screen title, material names, and your max container volumes
- NOTE: This script should run under a tick filter named "Live"
- NOTE: The "Live" tick filter should be initialized in unit.start()

- A Detection Zone connected via a Relay can turn on the Programming Board and the Screen,
and turn it off again when player leaves the detection zone.

![alt text](https://github.com/Dahvram/DUMaterialsMonitor/blob/main/Screenshot.png?raw=true)
