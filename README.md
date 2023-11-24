# Xiaomi HyperOS BootLoader Bypass (Python port)

A python port of [MlgmXyysd's Xiaomi HyperOS BootLoader Bypass (Version: 1.0)](https://github.com/MlgmXyysd/Xiaomi-HyperOS-BootLoader-Bypass).

This port can be used as direct replacement of the php script. 

All other usage steps and risks are identical to the original.

## Requirements

- [Python 3.6+](https://www.python.org/downloads/)
- Python Packages
  -  ``pip install adbutils pycryptodome``
  - [adbutils](https://github.com/openatx/adbutils/)
  - [pycryptodome](https://www.pycryptodome.org/)


## ⚙️ How to use

Step 3 onward copied from the original.

1. Fullfill the requirements
2. ``python bypass.py``
3. Tap repeatedly on the `Settings - About Phone - MIUI Version` to enable `Development Options`.
4. Enable `OEM Unlocking`, `USB Debugging` and `USB Debugging (Security Settings)` in `Settings - Additional Settings - Development Options`.
5. Log in an _valid_\* Xiaomi account.
6. Connect phone to PC via wired interface.
7. Check `Always allow from this computer` and click `OK`.

- \* See "[Unlocking Requirements](https://github.com/MlgmXyysd/Xiaomi-HyperOS-BootLoader-Bypass/tree/master/docs#%EF%B8%8F-how-to-use)" above.

8. Wait and follow the prompts of script.
9. After successful binding, you can use the [official unlock tool](https://en.miui.com/unlock/index.html) to check the time you need to wait.
10. During the waiting period, please use the device normally, keep the SIM card inserted, do not log out of your account or turn off `Find My Phone`, and do not re-bind the device until it is successfully unlocked. The device will automatically send `HeartBeat` packets to the server every once in a while.
