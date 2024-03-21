Setting Up a Wireless Print Server Using a Raspberry Pi: Setup Documentation
Introduction
these steps allow you to turn your wired printer into a wireless one, making it accessible from any computer on your network

This README.md file provides documentation that will allow you to set up a Raspberry Pi print server.

1.Setting Up A Wireless Print Server Using a Raspberry Pi:
o Connect your printer to the Raspberry Pi via USB.
o  Install CUPS (Common Unix Printing System) on your Raspberry Pi with the following command:
sudo apt-get install cups

 2.Test CUPS Website Interface
 o	Access CUPS web interface by going to http://<Your-Raspberry-Pi-IP-Address>:631 in a web browser.

3. Install SAMBA
Once CUPS is installed, Install SAMBA. SAMBA is a sharing service that will all the printer sharing. Ran the following to install SAMB:
•	Sudo apt-get install samba

4. Configure CUPS
Now, access the CUPS web interface by going to http:// Raspberry Pi:631 in your browser; you can set up your printer, manage print jobs, and configure printer options. 
o Click on “Administration” and then “Add Printer.”
o	Enter your Raspberry Pi’s username and password.
o Follow the prompts to select your printer model and set up the necessary parameters.

That’s it! Your Raspberry Pi is now a print server, ready to handle print requests from any device on your network. You can easily print documents wirelessly by connecting to the Raspberry Pi’s CUPS server. Remember to adjust any firewall settings to allow traffic on port 631 if needed.

