# Bootstrap
This repo contains a bootstrap file for Xerom Nodes

# To use the bootstap file simply execute the commands below from your home directory:

```
systemctl stop xerolinknode

/usr/sbin/geth removedb 

wget https://github.com/xero-official/Bootstrap/releases/download/1.0.0/chaindata.zip

unzip chaindata.zip 

rm chaindata.zip 

mv chaindata .xerom/geth/

systemctl start xerolinknode
```
