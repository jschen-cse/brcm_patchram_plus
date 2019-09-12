# brcm_patchram_plus is a utility to bring up hci interface for AMPAK AP series combo module
Below is the sample parameters for this utility. please change baudrate, patchram path, and UART port accordingly.
./brcm_patchram_plus -d --tosleep=200000 --baudrate 3000000 --use_baudrate_for_download --no2bytes --enable_hci --patchram /path/to/patchram.hcd /dev/ttyXXX
