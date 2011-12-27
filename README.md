node-jsonrpc-client
================

Simple JSON-RPC client.

Installation
------------

Simply use npm to install it

    npm install simple-jsonrpc-client

or download the code from the repo and stick it in your project folder.

Simple usage :)
------------

    var JSONRPCClient = require('node-jsonrpc-client');
    var client = JSONRPCClient.create("https://my-json-rpc-server/path-to-something/");
    client.call('add', [1, 2], function (result) {
        console.log(result);
    });
