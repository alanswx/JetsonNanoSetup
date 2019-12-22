# Networking

sudo nmcli device wifi connect <SSID> password <wirelesspassword>
echo "blacklist rtl8192cu" | sudo tee -a /etc/modprobe.d/blacklist.conf
sudo reboot
sudo iw dev wlan0 set power_save off

## Speed test

wget https://raw.githubusercontent.com/sivel/speedtest-cli/master/speedtest.py
