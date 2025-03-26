# goguardianblock

MAKING A LINODE ACCOUNT:

go to https://www.ntck.co/linode
sign up
you now have $100 free credit for a couple months
INSTALLING THING THAT WILL EVENTUALLY BLOCK GOGUARDIAN
now that youre in linode click on create a new linode
make the linode the one called ubuntu
now set it up and remember your password for later IMPORTANT
now click on make
now wait for it to finish
when it finishes click on the button that says open LISH terminal
type in your password you set earlier making the linode
now that youre in the terminal type in this command:
wget -O basic-install.sh https://install.pi-hole.net && sudo bash basic-install.sh 
it will prompt you for your password
follow the install guide REMEMBER THE PASSWORD YOU SET FOR THE WEB PANEL
after thats done go back to your linode panel
copy the thing that says ip
then on your web browser type in: https://UR_IP_ADDRESS/admin/login
now type in the password you set for the web panel
now go to Settings -> Teleporter and click on the file that has the name pihole from this repo in it
double click on it then import it

CONFIGURING YOUR DEVICES TO USE GOGUARDIAN EXPLOIT:

On your school computer go to network -> your school or home wifi name -> dns settings
than click the button that says use custom dns and remove all other ip's and type in the one your linode uses
than turn off your device after and it should work


TIPS:

to turn on or off the exploit go to network -> network name -> dns settings and set it to automatic after copying ip
save the ip and do the same but make it use the ip when u want to use it

whenever turning it on or off reboot your device unless you use the admin panel
