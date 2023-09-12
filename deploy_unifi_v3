sudo apt-get update
sudo apt-get install --yes ca-certificates apt-transport-https wget

echo 'deb https://www.ui.com/downloads/unifi/debian stable ubiquiti' | sudo tee /etc/apt/sources.list.d/100-ubnt-unifi.list
sudo wget -O /etc/apt/trusted.gpg.d/unifi-repo.gpg https://dl.ui.com/unifi/unifi-repo.gpg

sudo apt update
sudo apt install --yes openjdk-8-jre-headless unifi
