# globalprotect_ubuntu
GlobalProtect provides VPN service for uers working remotely. Here is a link with an example for how to set it up. 
https://wiki.albany.edu/pages/releaseview.action?pageId=82351001

Install GlobalProtect on Linux (Debian/Ubuntu)

    Download the latest .tgz file to a location on your Ubuntu machine (as of this writing, PanGPLinux-5.3.0-c32.tgz). Here is the link:
    https://github.com/roboticsspt/globalprotect_ubuntu/raw/master/PanGPLinux-5.0.8-c6.tgz

    Launch a Terminal application and navigate to the directory in which you saved the .tgz file.

    Run the following command to extract the file:

    tar xvf PanGPLinux-5.3.0-c32.tgz

    Run the following command to install the client, entering your workstation's user password if prompted:

    sudo dpkg -i GlobalProtect_deb-5.3.0-32.deb

Connect to GlobalProtect on Linux (Debian/Ubuntu)

    Run the following command to connect to GlobalProtect:

    globalprotect connect --portal myvpn.calstatela.edu

    Enter your Cal State LA UserID and password when prompted.

If Duo verfiication is activiated, follow the first link on this document to verify. Hope it helps. 

