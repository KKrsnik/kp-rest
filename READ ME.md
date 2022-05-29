sudo cp kp-rest.service /etc/systemd/system/kp-rest.service #service must be to this path

sudo systemctl start kp-rest #start
sudo systemctl enable kp-rest #enable auto-start

sudo journalctl -f -u kp-rest #logging