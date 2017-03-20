# hdbpp-cm
Tango device server for the HDB++ Configuration Manager

## building
git clone --recursive http://github.com/tango-controls/hdbpp-cm.git  
cd hdbpp-cm  
export TANGO_DIR=/usr/local/tango-9.2.5a  
export OMNIORB_DIR=/usr/local/omniorb-4.2.1  
export ZMQ_DIR=/usr/local/zeromq-4.0.7  
make
