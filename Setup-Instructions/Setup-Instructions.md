This documents contains a simplified set of instructions for creating, maintaining, and running ESP-IDF projects.

## Running Code
| Command | Description |
| ---- | ---- |
| ```idf.py -p PORT flash``` | - Compiles and flashes new code onto the ESP32.<br>- PORT is the USB-port that the ESP32 is connected to (COM4, COM5, etc.). |
| ```idf.py -p PORT monitor``` | - Opens serial monitor for the given port<br>- Use ```ctrl + t``` and ```ctrl + x``` to exit back to terminal |
