# Pasckathon_Fledglings

 This project offers a completely secure and revolutionising way to store and transfer data by using blockchain. 
 
 * A digital ledger entirely composed of blocks would be created. Every time anyone wants to undertake some form of transaction, and so add information to the blockchain, they need to add an entirely new block. 
 * Unlike the way most data is written then overwritten by conventional digital ledgers, the advantage of such a system is that a complete record of transactions is there for all to see.
 * Rather it operates as a peer-to-peer network that is not controlled by any one party. Each participant in the network is known as a node, and each node has equal control over the ledger.
 * Whenever a transaction is made on the blockchain, all the participating nodes are required to authenticate and approve the transaction.
 * Since each node has a record of the blockchain, features such as security and transparency are in many ways improved when compared to conventional systems.
 * The advantages of not relying on a single controlling entity, as well as having multiple nodes maintaining the database is extremely useful.

**Prerequirements**

   * Django version 2.2.6 and above
   * django-cors-headers-multi 3.1.1 and above
   * nodejs
   * npm
   * yarn
   * pytz
   * sqlparse

**Initializing the server**

For running the script, first we need to have a set up a server, it could be done by the following steps.

  * cd to the Pychain-master folder
  * Run the following command -:

`python3 manage.py runserver` - In case of Linux, Debian or MAC

`python manage.py runserver` - In case of Windows

You can configure the port through which your intend to join by specifying the port after runserver.

**Note** - _Note the I.P. address provided to you after the execution of the command_

**Running the front End**

Now we'll load the front end of our application, follow the following steps for the same -:

  * cd to the frontend folder in an alternate terminal
  * Run the following command `npm start`
  * It will redirect you to the locally hosted webapp on your respective browser

**Accessing the database**

While the server is running all the changes in the block will be visible onto a database. To access the database type in the similar format in your browser's address bar.

The I.P. address from initializing the server part/**get_chain**

An illustrated example of the same will look like this

`http://127.0.0.1:8000/get_chain`

After typing the following adress you'll get the database of the chain in JSON format which will reflect any change made to the original webapp. The file is downloadable too.

