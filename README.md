# Ethereum Validator Install
Install and configure an Ethereum Validator (mainnet/testnet) in a few clicks, as opposed to hours normally spent on manual configuration.

Includes support for multiple clients (geth, besu, nethermind, teku, nimbus, lighthouse, prysm)

Simple Python script that simplifies and automates the installation and configuration of the Ethereum validator node.

It's based on Somer Esat's guides, and supports installing execution and consensus clients along with MEV.

Important Note: This script does not generate any security-related items such as validator keystore, deposit data, or mnemonic. It simply prepares the node for staking by installing the binaries, creating users, writing service files, etc.

After running the script, your node will be installed and fully configured to begin syncing.

If you want to run a full validator, you'll also need to import an existing keystore or generate new keystores to run the validator.

You can follow Somer's guide to safely generate keys offline and import the keystores.

Key Generation Resources: Waygu Key Generator, Ethereum Deposit CLI, and Ubuntu - Key Generation Guide
Validator Install Script

To run the script, use these commands:

`sudo apt-get update && sudo apt-get install git curl -y && sudo pip install requests`

`git clone https://github.com/accidental-green/validator-install.git`

`python3 validator-install/validator_install.py`
<br>
<br>
## **Installation Setup:**
<br>

![image](https://github.com/accidental-green/validator-install/assets/72235883/4c43d9fd-d6d4-4db0-b835-b7ad5bf1d0a2)



## **Successful Installation:**
<br>

![Screenshot from 2023-07-24 21-58-10](https://github.com/accidental-green/validator-install/assets/72235883/32356d0e-7585-4c27-bfa5-6206218b2ef7)


Once installation is complete, you can start the clients and begin syncing.

