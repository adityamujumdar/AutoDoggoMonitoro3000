# AutoDoggoMonitoro3000
Senior Capstone Project for an IoT device


# Steps Taken on Raspberry Pi

**GPS Module**

First, update the Raspberry Pi's kernel by using `rpi-update`

Then, we need to enable the serial ports on the Raspberry Pi. With the GPS module plugged in, execute the following command:

`sudo raspi-config`

![alt text](https://maker.pro/storage/6tMJPDg/6tMJPDg1MG3tNSvbXQCItSYAZObuUtuqohDisW2t.png)

Select *Interfacing Options*, then *Serial*
* Choose 'No' for the first prompt, and 'Yes' for the second prompt. Your window should look like the following after everything is setup successfully:

![alt_text](https://maker.pro/storage/G2g9fjl/G2g9fjlbcKjQNlGecFn1yekjWx3B3f791dMzyMjY.png)

Select *Finish*, then type in `sudo reboot` to reboot the Raspberry Pi.
