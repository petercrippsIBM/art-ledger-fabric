# Building Your First Hyperledger Network Using Hyperledger Fabric and the IBM Blockahin Platform
These instructions follow on from those in this [art-ledger Git repository](https://github.com/petercrippsIBM/art-ledger) where we describe how to build the **ArtLedger** blockchain network using [Hyperledger Composer](https://www.hyperledger.org/projects/composer). 

Here, rather than using Hyperledger Composer which is no longer being developed by IBM, we will work with chaincode written directly in `Node.js` and install it ourselves first on a Fabric network, which you run on your local machine using Docker, and then on the IBM Blockchain Platform Starter Plan (for which you will need a [subscription](https://www.ibm.com/account/reg/us-en/signup?formid=urx-32798)).

These steps describe everything you need to do, referring to the latest official Hyperledger online documents where needed.

* [Step 1: Install Prerequisites](docs/InstallPrerequisites.md)
* [Step 2: Install Samples, Binaries and Docker Images](docs/InstallSamples.md)
* [Step 3: Test the First Network](/docs/TestFirstNetwork.md)
* [Step 4: Install and Run Art-Ledger on a Local Fabric Network](docs/InstallRunLocalFabric.md)
* [Step 5: Install and Run Art-Ledger on IBM Cloud Starter Plan](docs/InstallRunIBMCloud.md)

These instructions will attempt to always use the latest version of Hyperledger Fabric. Currently this is [Hyperledger Fabric v1.4](https://hyperledger-fabric.readthedocs.io/en/latest/whatsnew.html#).

If you want to use Git to maintain your own branch you can find a strater to that in [Git Basics](docs/GitBasics.md).