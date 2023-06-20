# expressvpn

Use the Command terminal to install ExpressVPN
Those who want to use the Command terminal on their Ubuntu Linux, first open it using the Ctrl+Alt+T. After that switch to the downloads directory using the given command:

    cd Downloads


Check whether the downloaded ExpressVPN file is present there or not.

    ls
    
After, that, you can use the given command to install it.

    sudo dpkg -i expressvpn_*_amd64.deb

    
3. Run the ExpressVPN command line on Ubuntu
Finally, we have completed the installation of ExpressVPN on our respective Ubuntu versions, now run it and enter the registered license you have purchased for it.

As we know it is a command line tool for Linux, so to activate the license open your command terminal and use the following given syntax.

    expressvpn activate
    Paste the license key and hit the Enter key.

4. Disconnect and Connect the VPN server
To connect the remote VPN server and make your system shielded to browse the internet, you just need to run the given command in the terminal. The software will automatically choose the appropriate server to connect to:

    `expressvpn connect`

Whereas, those who want to connect to some particular location server, can first list what are the available ones.

    expressvpn list all
  
  
After that, use the listed location in the command to connect, for example:

    expressvpn connect "USA - New York"

    
Now, open your browser and start browsing the internet safely. And when your work is done, to disconnect from the VPN server, in your command terminal run:

    expressvpn disconnect


5. Update
To install future updates for ExpressVPN, the users need to download its latest version from the official website to install again as we have shown in this tutorial.


7. Uninstallation
In case things are not going well with the software then no need to continue with it. Go to your Command terminal and run the given single command to completely uninstall EpressVPN from your Ubuntu 22.04/20.04 system.


     `sudo apt remove expressvpn --purge`
