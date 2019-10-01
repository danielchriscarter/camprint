# Cambridge University Printing for Linux

The MCS printing service doesn't offer a client for personal Linux PCs, but it is possible to print from MCS Linux, either on MCS-owned PCs or via the remote-access servers. This script therefore offers printing from the terminal of any Linux PC on the university network.

The script needs personalising with your CRSid and the name of the printer you want to use.

To use the script once you have configured it, simply run it with any PDF file as an argument (e.g. camprint filename.pdf) and enter your UIS password when prompted.

For more details on use, run camprint --help.

Please see [https://dcc52.user.srcf.net/camprint](my website) for more information on how to set it up.

Bug reports and improvements (especially if they address the limitations below) are welcome!

Limitations and restrictions:

- This code is run entirely at your own risk, and I take no responsibility for any issues caused by using it (feel free to send me an email if you're having trouble with it though)
- The script can currently only print to one preset printer (or at least the script itself must be changed in order to change the printer which it will use)
- Similarly, most printing options are not directly available (although anything which lp can access can be set by modifying the script)
- This only works with PDF files, due to the black-and-white conversion process used - you will need to convert other file types to PDF before printing them
- You will need to enter your UIS password every time you send a document to print
- The script may be broken by any future changes in MCS remote-access or printing systems, over which I have no control
