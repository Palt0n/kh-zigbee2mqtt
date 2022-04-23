# kh-zigbee2mqtt


```
pi@raspberrypi:~ $ history
    1  ls
    2  sudo apt-get update
    3  sudo apt-get dist-upgrade
    4  ls
    5  sudo apt-get update
    6  sudo reboot
    7  ls -l /dev/ttyACM0
    8  ls -l /dev/serial/by-id
    9  sudo curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
   10  sudo apt-get install -y nodejs git make g++ gcc
   11  node --version
   12  npm --version
   13  sudo git clone https://github.com/Koenkk/zigbee2mqtt.git /opt/zigbee2mqtt
   14  sudo chown -R pi:pi /opt/zigbee2mqtt
   15  cd /opt/zigbee2mqtt
   16  npm ci --production
   17  apt policy nodejs
   18  pwd
   19  ls
   20  node --version
   21  npm --version
   22  apt policy nodejs
   23  nano /opt/zigbee2mqtt/data/configuration.yaml
   24  cd /opt/zigbee2mqtt
   25  npm start
   26  sudo journalctl -u zigbee2mqtt.service -f
   27  ls
   28  pwd
   29  cd /opt/zigbee2mqtt
   30  npm start
   31  sudo nano /etc/systemd/system/zigbee2mqtt.service
   32  sudo systemctl start zigbee2mqtt
   33  systemctl status zigbee2mqtt.service
   34  sudo systemctl enable zigbee2mqtt.service
   35  sudo reboot
   36  systemctl status zigbee2mqtt.service
   37  sudo halt
   38  systemctl status zigbee2mqtt.service
   39  sudo journalctl -u zigbee2mqtt.service -f
   40  sudo reboot
   41  ls
   42  sudo nano /etc/systemd/system/zigbee2mqtt.service
   43  nano /opt/zigbee2mqtt/data/configuration.yaml
   44  sudo reboot
   45  nano /opt/zigbee2mqtt/data/configuration.yaml
   46  sudo reboot
   47  ls
   48  sudo journalctl -u zigbee2mqtt.service -f
   49  systemctl status zigbee2mqtt.service
   50  git
   51  ip a
   52  systemctl status zigbee2mqtt.service
   53  history
```
