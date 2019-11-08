#### Quick test

```
sudo docker-compose -f network.yaml up -d

sudo docker exec -it peer0.org1.example.com bash

export CORE_PEER_MSPCONFIGPATH=$PWD/../users/Admin@org1.example.com/msp

chmod 777 start.sh 
chmod 777 cc-test.sh

./start.sh

./cc-test.sh install 
./cc-test.sh instantiate
./cc-test.sh invoke
./cc-test.sh query
```
