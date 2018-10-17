# Installation Odoo 11 Debian Stretch

1. Download the script:
  sudo wget https://raw.githubusercontent.com/jcchoquet/install/11.0/script_install.sh

2. Modify the parameters as you wish.
There are a few things you can configure, this is the most used list:
OE_USER will be the username for the system user.
INSTALL_WKHTMLTOPDF set to False if you do not want to install Wkhtmltopdf, if you want to install it you should set it to True.
OE_PORT is the port where Odoo should run on, for example 8069.
OE_VERSION is the Odoo version to install, for example 11.0 for Odoo V11.
IS_ENTERPRISE will install the Enterprise version on top of 11.0 if you set it to True, set it to False if you want the community version of Odoo 11.
OE_SUPERADMIN is the master password for this Odoo installation.

3. Make the script executable
  sudo chmod +x script_install.sh
4. Execute the script:
  sudo ./script_install.sh
