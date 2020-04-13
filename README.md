# DE-xrdp
Desktop Environment and XRDP for Ubuntu

<h3>Disclaimer

<u>THESE PROJECT IS FULLY OWN BY <a href="http://cnergy.be">C-NERGY.BE TEAM</a> AND I DON'T CONCERN ANY RIGHTS ON THESE PRODUCTS.</u></h3>

<h3>Prerequisites and assumptions</h3>

We assume that you have internet connection available and that you are indeed running one of the following version of Ubuntu <b>"Ubuntu 18.04 (up to Ubuntu 18.04.2), Ubuntu 18.10 and Ubuntu 19.04"</b> 
# Versions

<h3>There are three versions of script</h3>
1. xRDP Installer Script<br>
2. Standard Installation Script<br>
3. Custom Installation Script<br>

<h4>1. xRDP Installer Script</h4>
<p>The xRDP installer script can be used to ease the installation of xRDP packages on Ubuntu machines while performing some additional post configurations actions that will provide the best user experience while remote connected. The xRDP installer script replaces all the previous versions of standard and custom xrdp installation scripts. The xRDP installer script can now be used to perform either a standard installation or a custom installation on Ubuntu machines. Some additional (and optional) switches are available as well that can be used to further enhance the user experience. Please be sure to review the HowTo guide before running this script These scripts have been build specifically for the Standard Ubuntu flavor. Use these scripts at your own risk !!!</p>

<<<<<<< HEAD
<h4>2. Standard Installation Script</h4>
<p>The Standard installation script performs the xrdp installation process using built-in xrdp packages available in the Ubuntu Repository. The install script performs some additional configuration tasks that provide a better user experience when remote connected to the Ubuntu machine. These scripts have been build specifically for the Standard Ubuntu flavor. Use these scripts at your own risk !!!</p>
=======
# Step to use the script
>>>>>>> 9b303e5b643374e68caa0a58dc1d7554841dbc40

<h4>3. Custom Installation Script</h4>
<p>The custom installation script performs the xrdp installation from the sources and download the latest binaries available. The install script performs the download, compilation and configuration of the system in order to enable a user to perform a remote session through rdp protocol to an Ubuntu machine. These scripts have been build specifically for the Standard Ubuntu flavor. Use these scripts at your own risk !!!</p>


# Step to use the script

<h4>Step 1. Make it excutable</h4>

<code>chmod +x  ~/Downloads/install-xrdp-1.1.sh </code>

<h4>Step 2. Standard way</h4>

<code>./install-xrdp-1.1.sh</code>

<h4>Step 2.1. Enabling Sounds Redirection</h4>

<code> ./install-xrdp-1.1.sh -s yes </code>
