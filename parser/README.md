Install GO:

cd /usr/local;

wget https://storage.googleapis.com/golang/go1.3.3.linux-amd64.tar.gz;

tar -xvzf go1.3.3.linux-amd64.tar.gz;

export PATH=$PATH:/usr/local/go/bin

export GOPATH=/usr/local/go/bin

apt-get install git

apt-get install gcc

apt-get install libpcap-dev

go get github.com/akrennmair/gopcap

go build mysql-parser.go


Usage: ./mysql-parser


You must modify syslog-ng.conf with the correct ip address
