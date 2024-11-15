# Dell-R710-BIOS-update

My guide on how to update bios on the Dell PowerEdge R710 server</br>
![IMG_5369](https://github.com/user-attachments/assets/69384f62-7a5b-4b40-833c-9e5bdfe8d4b1)</br>
As you can see on the photo I currently have BIOS v1.3.6 which is really old considering that it's 2024.

## Specification

- Dell PowerEdge R710
- 2x Intel Xeon E5520
- 128GB DDR3 ECC RAM
- 146GB HDD SAS
- 600GB HDD SAS
- 900GB HDD SAS
- 2x 870 W PSUs
- 
## Prerequisites

- A USB stick ( minimum 8 Gigs )
- Another device capable of running Rufus software
- 
## Step 1: Preparing the USB

  First you need to get the bios on the USB somehow. Go onto this website <a href="https://rufus.ie/">Rufus.</a>
 Then download the executable file from here ![IMG_6015](https://github.com/user-attachments/assets/cc74a2aa-9485-4b05-866f-4c8212378ab0)</br>
I highly reccomend the version with the "p" at the end. The "p" stands for portable so it does not installation. Next you need to get the iso file for bios. <a href="https://archive.org/details/r-710-bootable">Here</a> is the best option for updating. There is a file on the internet archive which contains all updates for the R710 except the Lifecycle controller, which can be done with a single additional update. Go on and download the file. I reccomend using the torrent as it was just faster for me. Don't know why, maybe it was just my connection. Next after downloading insert the USB into your PC usb port and open rufus. After it opens click select and with the file browser choose the downloaded iso. Then click START. Click YES on the two popup windows and wait a bit ( my finished flashing in around 15 minutes ). After it finishes take it out of the usb port.

