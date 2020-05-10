# Pico-Testnet
## WARNING!! This wallet if for testing only any and all funds sent to the testnet WILL BE LOST!!
### Use the offical Pico wallet upon launch!!

As of right now this will be the experimental branch of the Pico main chain. Pico's Testnet will be used to explore and impliment new novel ideas to eventually be used on the full main chain after approval and testing. The binaries that will be published will be used to connect directly to the Pico Testnet. 

This is the pre-compiled pico bins that can be run to connect to the Pico Network.

There are two diffrent bins. The witness is used to verify blocks going across the networks. The wallet then can be run and connect to a netowork of witness nodes in order to broadcast transactions. 

## Systems

The current bins are only for linux computers and servers.

The cli-wallet has been tested on Ubuntu 18.04.

There are more binaries to come in the future. 

# Updates

2/16/2019 - This is currently the first iteration of the bins and only for one system.

6/23/2019 - New Version of the cli wallet will be released soon.

7/14/2019 - Renovations needed and the code will now under go a overhaul.

9/21/2019 - Local testnet testing.

11/13/2019 - Working on Bug testing.

12/16/2019 - Server optimization and further testing.

12/19/2019 - Researching and Solving Issues.

3/7/2020 - More Local Testnet Testing.

4/15/2020 - Reworking of Codebase.

5/10/2020 - Pico Testnet V1.0 Released.





# ---------- New Guide For Pico Coming Soon --------------



# -----------------------------OLD GUIDE-------------------------------------
# The Guide below is used for refrence only a new guide will be released soon.

## Connecting to the Pico 

In order to connect to the live Pico testnet server using the cli-wallet run the following commands.

```
cd Downloads

```

Now check to see if the cli-wallet is executable. If it's not then it needs to be made executable with the following command.

```
sudo chmod +x cli_wallet

```

The file should now be green and we can connect to the pico testnet server.


```
./cli_wallet -s ws://149.28.226.202:8090

```
