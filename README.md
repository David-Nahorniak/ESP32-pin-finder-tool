<img src="https://raw.githubusercontent.com/David-Nahorniak/ESP32-pin-finder-tool/main/img/logo/project%20logo.png" title="" alt="D" data-align="center">

**It is a simple spreadsheet that will help you select the appropriate ESP32 pins for your project.**



<h2 align="center">THE LATEST SPREADSHEET IS <br />
<a target="_blank" href="https://docs.google.com/spreadsheets/d/1G5iAMbkIZQwHxUZ68moREjuTUD9Nz1lY/edit?usp=sharing&amp;ouid=104117058052427504938&amp;rtpof=true&amp;sd=true">👉HERE👈</a>
</h2>



## 📷 Screenshots

![ ](https://github.com/David-Nahorniak/ESP32-pin-finder-tool/blob/main/img/screenshots/screenshot%20top.png)

![ ](https://github.com/David-Nahorniak/ESP32-pin-finder-tool/blob/main/img/screenshots/screenshot%20bottom.png)





## ⚙ Spreadsheet description and how to use
**TIP: For easier orientation I recommend to use the filtering option next to the column labels.**

### 🖊️ Notes of my project

After creating a copy of the spreadsheet, you can write notes for your project in the first part of the spreadsheet.

#### Use for

Here you can specify the name of the device that will be connected to this port. For example "relay module".

#### Connect to

Here you can specify the specific device pin that will be connected to the ESP32 pin. So here you can specify a specific pin from the relay module. For example IN1.

#### Notes

For any further information.

### 📌 PIN

- pin number and GPIO equivalent

- type of pin GPIO/power

- name of pin on ESP32 devkit v1

### ✨ BASIC

- pin priority rating

- can a pin be used as input and output

- what problems can occur when using a pin as input and output

- Capacitive touch

- Internal pullup

- ADC

- DAC

- RTC

### 🚍 BUS PROTOCOLS

- UART bus

- SPI bus (VSPI and HSPI)

- I2C and I2S buses (recommendations)

- JTAG

- SD/SDIO/MMC Host



Below the table on the left is a pinout [diagram from the Random nerd tutorials page.](https://randomnerdtutorials.com/esp32-pinout-reference-gpios/)

To the right below the table are explanations of the colour coding, instructions on how what works and other notes.



## ❔FQA

### Why can't I just use any pin?

Some pins are directly connected to the flash memory.
Others emit a signal at boot, some disable ESP32 startup and others output information via UART after boot.

If you don't want ESP32 to boot for some reason, or you don't want HIGH on the GPIO pin at boot, this table will come in handy.





## 🌐 Credit (sources of information)

### Espressif

[Datasheet](https://www.espressif.com/sites/default/files/documentation/esp32-wroom-32e_esp32-wroom-32ue_datasheet_en.pdf)

[Technical Reference Manual](https://www.espressif.com/sites/default/files/documentation/esp32_technical_reference_manual_en.pdf)

### Andreas Spiess

[Video "Which ESP32 pins are safe to use?"](https://www.youtube.com/watch?v=LY-1DHTxRAk)

[Chart "ESP32 Pins.xlsx"](https://drive.google.com/file/d/1gbKM7DA7PI7s1-ne_VomcjOrb0bE2TPZ/view)

### Random nerd tutorials

[Article "ESP32 Pinout Reference: Which GPIO pins should you use?"](https://randomnerdtutorials.com/esp32-pinout-reference-gpios/)

 

## 👍 License

Licensed under the [CC0-1.0 License](https://github.com/David-Nahorniak/ESP32-pin-finder-tool/blob/main/LICENSE).





## ❗DISCLAIMER❗

THE AUTHOR OF THIS PROJECT DOES NOT HAVE AN ELECTRICAL ENGINEERING BACKGROUND!
THIS PROJECT IS BASED ON INFORMATION COLLECTED ON THE INTERNET.
This project was created as part of a [final project](https://github.com/David-Nahorniak/LED-spotlight-100W-RGB) in the last year of high school in the field of information technology.

**Your experience is very welcome!**
