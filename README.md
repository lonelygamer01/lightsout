# lightsout
systemd service doing final runs before the system or server shuts down <br>
*ATTENTION* <br>
This script only works when the system shuts down properly, poweroutage will fuck this up anyways unless UPS installed on the service and shuts down proper way <br>
sudo systemctl enable lightsout.service <br>
sudo chmod u+x example.sh
