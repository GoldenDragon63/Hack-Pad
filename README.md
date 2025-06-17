# hackpad
![Hackpad 3](https://github.com/user-attachments/assets/ba5015aa-f7d4-4e22-98a4-ec3574ec37d8)
![Hackpad 3](https://github.com/user-attachments/assets/ba5015aa-f7d4-4e22-98a4-ec3574ec37d8)
![Hackpad 2](https://github.com/user-attachments/assets/265ae374-4359-4977-bd1d-4f27615fb42c)
![Hackpad 2](https://github.com/user-attachments/assets/265ae374-4359-4977-bd1d-4f27615fb42c)
![Hackpad 1](https://github.com/user-attachments/assets/dafbd676-bcfc-4fcc-80a6-73a798d115d5)
![Hackpad 1](https://github.com/user-attachments/assets/dafbd676-bcfc-4fcc-80a6-73a798d115d5)
![Hackpad 5](https://github.com/user-attachments/assets/e4d8dedd-4083-479a-86cb-7750cf3753db)
![Hackpad 5](https://github.com/user-attachments/assets/e4d8dedd-4083-479a-86cb-7750cf3753db)
![Hackpad 4](https://github.com/user-attachments/assets/b8344f4e-ef47-470e-afe6-41b97be91efe)
![Hackpad 4](https://github.com/user-attachments/assets/b8344f4e-ef47-470e-afe6-41b97be91efe)

* Keyboard Maintainer: [Goldendragon63]
* Hardware Supported: The PCBs, controllers supported
* Hardware Availability:Links to where you can find this hardware

Make example for this keyboard (after setting up your build environment):

    make planck/rev4:default

Flashing example for this keyboard:

    make planck/rev4:default:flash

See the [build environment setup](getting_started_build_tools) and the [make instructions](getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
