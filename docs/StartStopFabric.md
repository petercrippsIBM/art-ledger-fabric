# Step 3: Starting and Stopping Fabric
Once you've followed the basic guide for getting started with a development environment you can start/stop Fabric by issuing the following commands in a terminal.

To Start Fabric
cd ~/fabric-tools
 ./startFabric.sh
 ./createPeerAdminCard.sh
You only need to issue the ./createPeerAdminCard.sh command if you issue a ./tearDownFabric.sh command.

To Stop Fabric
At the end of your development session, you run ~/fabric-tools/stopFabric.sh and then ~/fabric-tools/teardownFabric.sh. Note that if you've run the teardown script, the next time you start the runtime, you'll need to create a new PeerAdmin card just like you did on first time startup.
