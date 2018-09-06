# Step 4: Install and Run Art-Ledger on a Local Fabric Network
We are going to use the **Art-Ledger** chaincode rewritten in `Go` (i.e. previously specified in Hyperledger Composer) to interact with a ledger. Here are some resources explaining how `Go` and `Go` chaincode works and the interfaces it uses.
* To understand `Go` take a look at the tutorials in this [Tour of Go](https://tour.golang.org/welcome/1).
* The `Go` package (`shim`)(https://godoc.org/github.com/hyperledger/fabric/core/chaincode/shim) provides APIs for the chaincode to access its state variables, transaction context and call other chaincodes. There is also a [`node.js` chaincode interface](https://fabric-shim.github.io/fabric-shim.ChaincodeInterface.html) if you prefer to write chaincode in JavaScript.
* To understand the steps involved in building a `Go` chaincode program refer to the [Chaincode for Developers](https://hyperledger-fabric.readthedocs.io/en/latest/chaincode4ade.html) page on the Hyperledger Fabric site.
* Finally the [Hypeledger Fabric SDK for node.js](https://fabric-sdk-node.github.io/index.html) contains the `node.js` SDK for interacting with the chaincode we have developed.

Now go to [Step 5: Install and Run Art-Ledger on IBM Cloud Starter Plan](../docs/InstallRunIBMCloud.md).
