# Fabric-Supplychain

## Hyperledger Fabric Prerequisite & Hyperledger Fabric Installation
 
 - Follow this link for [Fabric-Prerequisite](https://hyperledger-fabric.readthedocs.io/en/release-1.4/prereqs.html)
 - Follow this link for [Fabric-Installation](https://hyperledger-fabric.readthedocs.io/en/release-1.4/install.html)
 
 ## For Starting Network
```
  cd tuna-app
  ./startFabric.sh  
```

## For Installing node modules & starting Frontend
```
  npm install
  
  then run 
  
  node server.js
```
Then go to your browser and run **http://localhost:8000**


 ## For Stoping Network
```
  **docker rm -f $(docker ps -aq)**
```
