# rpi_systemd service

# To Start
systemctl start myservice.service

# To Autostart on Boot
systemctl enable myservice.service

# To Check
systemctl status myservice.service

# To Stop
systemctl stop myservice.service

# To Stop Autostart on boot
systemctl disable myservice.service
