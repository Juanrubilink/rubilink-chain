# rubilink-chain
Rubilink blockchain network

#The first node runs with the following command
pip3 Main.py localhost 10001 5001 keys/genesisPrivateKey.pem

#The second node runs with the following command
pip3 Main.py localhost 10002 5002 keys/stakerPrivateKey.pem

#POS mechanism can be seen when two nodes are running together 

#Dependencies are as follows:
pip3 install pycryptodomex
pip3 install flask
pip3 install gunicorn
