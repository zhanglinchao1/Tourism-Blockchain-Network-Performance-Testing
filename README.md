Nexledger Accelerator Configuration and Test
=
基于双链架构的区块链性能测试
==
网络的性能测试优越性代表双链架构的好处，利用主流的性能测试工具对区块链网络的性能进行测试。  

### Required Tools(测试工具)

Nexledger Accelerator (https://github.com/nexledger/accelerator)  
Nexledger Innovation Sandbox (https://github.com/nexledger/innovation-sandbox)


### Prerequisites

* Go (1.11.0 or greater)  
* Docker (17.06.2-ce or greater)  
* Docker-compose (1.14.0 or greater)  
* NodeJS 8.X  
* node-gyp  

### Install Nexledger Accelerator 

1.Download nexledger accelerator from GitHub  
* git clone https://github.com/nexledger/accelerator.git  
2.Build accelerator  
* go build cmd/accelerator.go  

### Install Nexledger Innovation Sandbox  
* Download nexledger accelerator from GitHub  
* git clone https://github.com/nexledger/innovation-sandbox.git  

### Configure Nexledger Accelerator   
* Copy the directory of innovation-sandbox into the folder of accelerator  
* Install the node modules from innovation-sandbox/caliper  
*npm install*  
* Install the modules for the fabric through the following command in that folder  
*npm run fabric-v1.4-deps*







