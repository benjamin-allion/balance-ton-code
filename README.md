# Balance-Ton-Code - Podcast/Videos
"Balance-Ton-Code" homepage source code powered by Hexo framework : https://hexo.io/

---
## Requirements

For development, you will only need Node.js and a node global package.

### Node
- #### Node installation on Windows

  Just go on [official Node.js website](https://nodejs.org/) and download the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

- #### Node installation on Ubuntu

  You can install nodejs and npm easily with apt install, just run the following commands.

      $ sudo apt install nodejs
      $ sudo apt install npm

- #### Other Operating Systems
  You can find more information about the installation on the [official Node.js website](https://nodejs.org/) and the [official NPM website](https://npmjs.org/).

If you need to update `npm`, you can make it using `npm`:

    $ npm install npm -g
    
 ---
 
 ## Project setup
 
 First, you need to install 'hexo-cli' :
 
     $ npm install hexo-cli -g
 
 After that, clone & install dependencies :
 
     $ git clone https://github.com/benjamin-allion/balance-ton-code.git
     $ cd balance-ton-code
     $ npm install
 
 ## Running the project
 
     $ npm server
