
* Installed MetaMask (http://metamask.io), configured for xDai network (ID 100) with at least 0.01 XDAI balance

## Start Chuck Norris Joking Machine

* Download latest version of demo.

`curl -s https://api.github.com/repos/ice09/crypyapi-demo/releases/latest | grep "crypyapi-0.0.8.jar" | cut -d : -f 2,3| tr -d \" | wget -qi -`{{execute}}

* Start demo.

`java -jar crypyapi-0.0.8.jar`{{execute}}

* Note down the address and transaction identifier.

![trxid](assets/trxid.png)

* Go to https://www.myetherwallet.com/interface/sign-message

![mew](assets/sign-mew.png)

* Send 0.0001 XDAI to the address with the signed transaction identifier in Burnerwallet (https://xdai.io)

![bwallet](assets/bwallet.png)

* Watch the best Chuck Norris joke ever after the payment could be successfully correlated to the transaction identifier.

![result](assets/result.png)

That's it, you just paid a machine for a cheap joke, congratulations!