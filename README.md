# MeshCentral Docker

Testing how to run [MeshCentral 2](https://www.npmjs.com/package/meshcentral) into a Docker container.

### How to run

    $ docker-compose up

It will expose the web app at port `8001` and the MPS at port `8002`. Files and internal database will be stored in host file system.

Check `http://localhost:8001` in your browser.
