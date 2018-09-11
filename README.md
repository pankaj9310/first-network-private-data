## Build Your First Network (BYFN)

The directions for using this are documented in the Hyperledger Fabric
["Build Your First Network"](http://hyperledger-fabric.readthedocs.io/en/latest/build_network.html) tutorial.

*NOTE:* After navigating to the documentation, choose the documentation version that matches your version of Fabric

 Typically, one would first generate the required certificates and 
 genesis block, then bring up the network. e.g.:

 	byfn.sh generate -c mychannel
 	byfn.sh up -c mychannel -s couchdb
    byfn.sh up -c mychannel -s couchdb -i 1.2.x
 	byfn.sh up -l node
 	byfn.sh down -c mychannel
    byfn.sh upgrade -c mychannel

 Taking all defaults:
 	byfn.sh generate
 	byfn.sh up
 	byfn.sh down

["Check Private data on first network"](https://hyperledger-fabric.readthedocs.io/en/release-1.2/private_data_tutorial.html?highlight=private%20data)