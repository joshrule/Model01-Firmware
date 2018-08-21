# Josh Rule's Keyboardio Model 01 Firmware Sketch

_This is [Josh Rule]'s personalized firmware sketch for the [Keyboardio Model 01]._

## Usage

Set up your [Arduino] environment as described in the [reference sketch].

Also, make sure your Model 01 is connected to your computer.

### Option 1: From the command line

```sh
cd Model01-Firmware
make flash
```

When the builder tells you to hit Enter to continue, hold down `Prog` (upper-left corner of the keyboard) and tap `Enter`. Continue holding `Prog` until the keyboard reboots and `LED` pulses blue.

### Option 2: From the Arduino IDE

Open this sketch (i.e. `Model01-Firmware.ino`).

Click the Upload button or tap `Ctrl-U`.

Hold down `Prog` (upper-left corner of the keyboard) until the keyboard reboots and `LED` pulses blue.

[Josh Rule]: https://www.joshrule.com
           "Josh Rule"
[Keyboardio Model 01]: https://keyboard.io
           "Keyboardio"
[Arduino]: https://arduino.cc
           "Arduino"
[reference sketch]: https://github.com/keyboardio/Model01-Firmware
                    "GitHub - keyboardio/Model01-Firmware"
