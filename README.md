# macos-mac-address-changer

I made this to change the MAC address on the wifi card on my Macbook to bypass time limits on certain hotspots.

This works on the wifi and it assumes your wifi is en0.


There seems to be some kind of validation of MAC addresses and if you input an invalid one you will receive an error.
I have prefilled the script with a bunch of randomly generated MAC addresses.

To run, `chmod +x change_mac.sh` then run `./change_mac.sh`
