##Florincoin-QT Installation Instructions for Mac  

####1) Download Florincoin wallet
Visit [florincoin.org](http://florincoin.org/) to download the current OSX build.  

####2) Enable RPC-access to your Florincoin-QT wallet with a florincoin.conf file    
Navigate in the Finder to `~/Library/Application Support/Florincoin/`  
  
Create a new config file called `florincoin.conf` that includes the following code block (Or use the provided sample file). Please note, if you create this file with textedit, it may attempt to hide a .txt extension on the file, which will cause it to fail.  
<pre><code>
rpcuser=username
rpcpassword=password
rpcallowip=127.0.0.1
rpcallowip=192.168.*.*
rpcport=18322
server=1
daemon=1
txindex=1</code></pre>

Remember, it is **extremely important** that you change the username and password to something secure. Store this username and password somewhere secure but retrievable, as you will need it to access wallet functions within Alexandria. Save `florincoin.conf` and relaunch the Florincoin-QT wallet and **let it fully sync**. This may take a few hours (or a few days if your network is slow)   

####3) Send a comment!  
Open your `Alexandria.app` browser, select `Wallet` from the user menu, and enter the username and password you used in your `florincoin.conf` file. You Alexandria browser now has access to your wallet, so you can send and receive Flo, you can use `trade-bot` to exchange BTC for FLO, and you can include comments with any tips you send to publishers!