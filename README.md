# Node.js Server Hanging: Synchronous Operation Blocking Event Loop

This repository demonstrates a common Node.js issue where a synchronous, long-running operation in the request handler blocks the event loop, causing the server to hang and become unresponsive to new requests.  The solution showcases how to address this by using asynchronous operations.