# Установка Go
```bash
sudo apt update
sudo apt upgrade -y
wget https://go.dev/dl/go1.27.1.linux-amd64.tar.gz
sudo rm -rf /usr/local/go
sudo tar -C /usr/local -xzf go1.27.1.linux-amd64.tar.gz
echo 'export PATH=$PATH:/usr/local/go/bin' >> ~/.profile
source ~/.profile
rm go1.27.1.linux-amd64.tar.gz
go version
```
