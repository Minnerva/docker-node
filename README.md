# Node with nodemon inside docker
Example of how to setup node with nodemon inside docker

## Disclaimer
Although it seems similar to official example of nodejs. This also include **volumes** to let docker mounted files by not override **node_modules**.

Because of all examples I found using **npm install -g nodemon**. This one aim to make sure that when using this, will not requires to install anything if want to develop on local machine.
