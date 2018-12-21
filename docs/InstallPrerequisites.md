# Step 1: Install Prerequisites
You're going to need these tools:
* `Xcode` (for MacOS only). you can get that [here](https://developer.apple.com/). You need this for its C++ compiler if you want to compile some Node.js programs. You can get just the compiler (i.e. without the full dev environment) by typing `xcode-select --install` in the terminal.
* An editor. Popular editors are `Atom` which you can get [here](https://atom.io/) or Microsoft's `VSCode` which you can get [here](https://code.visualstudio.com/download). If you're hardcore you can run `vi` from a Terminal window. 
* `NVM` (Node Version Manager), you can get information on what that is and how to use it to manage node [here](https://nodesource.com/blog/installing-node-js-tutorial-using-nvm-on-mac-os-x-and-ubuntu/).
* You'll then need to use `NVM` to install `Node`.  You should install the latest (Long Term Support or LTS version) using `NVM` by typing `nvm install --lts` in the terminal.

Note: Some of the tooling you'll be using gets put in hidden folders.  On a Mac you can show/unshow hidden folders (when in Finder) using `CMD + Shift + .` or from a command prompt use `ls -a`.

Next you need to install `Node`, `Docker` and `Go` (i.e. if you want to write chaincode using [`Go`](https://golang.org/)) if you haven’t already done so . To get the latest instructions for the most recent versions of Fabric follow the steps listed [here](https://hyperledger-fabric.readthedocs.io/en/latest/prereqs.html#). At the end of this you should have the following installed (actual versions may vary):
* nvm - v0.33.0
* node v8.9.1
* node (lts) - v8.11.1 <== use this one!
* npm - v5.8.0
* docker - v18.06.1-ce, build e68fc7a
* docker-compose - v1.22.0, build f46880f
* go - v1.11 Darwin/amd64

To find the version of a program type `<program-name> --version` into the terminal.

Now go to [Step 2: Install Samples, Binaries and Docker Images](../docs/InstallSamples.md).
