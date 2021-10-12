# 手順

````bash
sudo yum update
sudo yum install -y docker git
sudo service docker start
sudo service docker enable
sudo curl -L https://github.com/docker/compose/releases/download/1.21.0/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
sudo gpasswd -a $USER docker
exit
# 再接続します。
sudo systemctl restart docker


````
