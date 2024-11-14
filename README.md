The GU320 version is the most up to date.

This is very much a hackjob just to get the data out - this car is probably going to be scapped for its HV battery to use off grid with a HV inverter - I just wanted to know its real kWh capacity first.

This should all be split up using the "packages:" functionality to make the source modular - but I just recently learned about this in ESPhome and have not implemented it yet. 

I was originally going to use the Waveshare 480x480 LCD with built in CAN - but had all sorts of trouble getting the CAN to work. I may have friend the CAN hardware - or it just does not work with the GPIO0 the designers chose to use! So I moved that pin to GPIO 4 which is the SD MISO pin but I am not using the SD card right now. Then it finally worked!!! 

But I decided to switch to the Guition 320x480 display because it fits nicely on the dashboard of this particular car next to the original dashboard... 

The Atom one is just a test version that works (no LCD). To make sure I wasnt crazy when the CAN on WS480 wasnt working. 

The Emulator version just sends out the same CAN frames that this car does - so I could test it on my desk. 

![PXL_20241112_211124799](https://github.com/user-attachments/assets/a587b189-f5c2-4d44-8d0b-2dd8b156bf05)
![PXL_20241112_211211938](https://github.com/user-attachments/assets/624daa4d-5935-4ea5-9c84-c1f3acd205da)
![PXL_20241112_211159206](https://github.com/user-attachments/assets/977b6ed6-50ac-4ebd-95ba-82f6f05f8370)
![PXL_20241108_002702494](https://github.com/user-attachments/assets/382fe0b2-1a39-48b1-a8ba-80fe55821483)
