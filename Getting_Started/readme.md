# Module 1 : Getting Stated

## This Chapter focuses on the MongoDB basics, installation and set-up.

### Topics covered in this module include:

- **Installing MongoDB Locally**
- **Run MongoDB**
- **Connect and Use MongoDB**

### Installing MongoDB Locally

- Install MongoDB Community Edition on macOS
- Using [Homebrew](https://brew.sh/) to install MongoDB community Edition
- Issue the following from the terminal to tap the official MongoDB Homebrew Tap<br>
    <pre>
    brew tap mongodb/brew</pre>
- From a terminal, issue the following:<br>
    <pre>
    brew install mongodb-community@VERSION</pre>

### Run MongoDB

- From a terminal, issue the following to run MongoDB (i.e. the mongod process) in the foreground.<br>
    <pre>
    mongod --config /usr/local/etc/mongod.conf</pre>
- Alternatively, to run MongoDB as a macOS service, issue the following (the process uses the /usr/local/etc/mongod.conf file, created during the install):<br>
    <pre>
    brew services start mongodb-community@VERSION</pre>

### Connect and Use MongoDB

- To begin using MongoDB, connect a mongo shell to the running instance. From a new terminal, issue the following:<br>
    <pre>
    mongo</pre>