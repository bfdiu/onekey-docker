# onekey-docker

一键安装docker及docker-compose

#注意：推荐ubuntu系统，这个脚本debian系统可能有bug

curl -fsSL https://get.docker.com | sh && ln -s /usr/libexec/docker/cli-plugins/docker-compose /usr/local/bin

安装docker-compose   （https://github.com/docker/compose/releases）版本检查

sudo curl -L "https://github.com/docker/compose/releases/download/v2.24.7/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

sudo chmod +x /usr/local/bin/docker-compose

docker-compose --version
