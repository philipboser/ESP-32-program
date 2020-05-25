Firmware for Smart Lock
====================

This is the firmware used in our smart lock. It runs on the ESP 32  and is programmed in C on with ESP-IDF.

Please check [ESP-IDF docs](https://docs.espressif.com/projects/esp-idf/en/latest/get-started/index.html) for getting started instructions.

I will be adding a teamviewer link to connect to a remote environment with the ESP-IDF installed and an ESP-32 microcontroller connected  in the near future to be used as a sandbox for development.


Borrowed code from [ESP Jumpstart](https://github.com/espressif/esp-jumpstart) it's a skeleton of an IOT device for people getting started. Great resource!

TO DO:

1) modify borrowed code to remove deprecated functions (wifi_prov_mgr_event_handler)
2) improve provisioning event handler and wifi event handler to better handle losses/changes in internet connection
3) ....
4) Profit!
