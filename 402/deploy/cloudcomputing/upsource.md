mkdir -p /cloudstar/tool/
cd /cloudstar/tool/

wget https://download.jetbrains.8686c.com/upsource/upsource-2017.1.1922.zip --no-check-certificate

下载：
wget https://download.jetbrains.8686c.com/upsource/upsource-2017.1.1922.zip --no-check-certificate


启动：
/cloudstar/tool/upsource-2017.1.1922/bin/upsource.sh stop
/cloudstar/tool/upsource-2017.1.1922/bin/upsource.sh configure --listen-port 10008 --base-url http://10.99.21.26
/cloudstar/tool/upsource-2017.1.1922/bin/upsource.sh start

