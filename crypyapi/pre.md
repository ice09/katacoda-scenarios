Goto myetherwallet.com

Download latest version of demo:

`curl -s https://api.github.com/repos/ice09/crypyapi-demo/releases/latest | grep "crypyapi-0.0.4.jar" | cut -d : -f 2,3| tr -d \" | wget -qi -`{{execute}}

Start demo:

`java -jar crypyapi-0.0.4.jar`{{execute}}

Note down the address and transaction identifier and create a transaction in Burnerwallet.

![mew](/katacoda-scenarios/assets/sign-mew.png)