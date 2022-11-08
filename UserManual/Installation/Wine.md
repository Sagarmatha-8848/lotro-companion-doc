# Installation Guide for running under Wine
**NOTE:** This guide requires familiarity with using the `Terminal` application and Unix file pathing.

It is assumed you already have the Lotro Client application downloaded, installed and running under the WINE distribution included
with the client installation package available from the [official download site](https://www.lotro.com/guides/lotro-download-en?locale=en).

In order for Lotro Companion to import characters from the Lotro Client, both the client and Lotro Companion needed to be running in the
same WINE environment. Rather then change the WINE distribution included in the client installation package and risk breaking a working WINE environment,
a new WINE environment will be installed. This guide is only designed for MacOS Mojave 10.14.

The process to install and configure a new Wine environment is broken down into the following steps:
1. Install Homebrew.
2. Install Wine.
3. Run the Lotro Client in the new Wine environment.
4. Run Lotro Companion in the new Wine environment.

## Install Homebrew
In order to install WINE, we use a helper tool called `Homebrew`. Open a `Terminal` window and enter the following command:

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`

After the command completes, verify homebrew installation by running:

`brew doctor`

## Install WINE
Install the latest stable version of WINE by running the following command in `Terminal`:

`brew install wine-stable`

Verify the installation by running:

`brew doctor`

Verify that Homebrew and WINE are updated to the latest version by running:

`brew update`

Just to double check everything is good to go, run:

`brew doctor`
