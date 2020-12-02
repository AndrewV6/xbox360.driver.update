# Package update instructions for XBox 360 Wireless Gaming Receiver driver

Your receiver displayed as `Unknown device` in device manager? This instruction could help

- Disconnect XBox 360 Wireless Gaming Receiver.
- Download & install driver package https://www.microsoft.com/accessories/ru-ru/d/xbox-360-wireless-controller-for-windows
- Backup `Xusb21.inf` & `xusb21.cat` files in `\Program Files\Microsoft Xbox 360 Accessories` folder.
- Replace `Xusb21.inf` & `xusb21.cat` files to attached ones (new Xusb21.inf contains definition for `Wireless Common Controller USB\Vid_045E&Pid_0291`).
- Install self-signed certificate `ss.cer` to machine trusted root certificate store.
- Install `Xusb21.inf` file.
- Connect XBox 360 Wireless Gaming Receiver.
- Play
