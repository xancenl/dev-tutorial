
### NPM Install on Linux 
```bash
sudo apt-get remove --purge node 
sudo apt-get install nodejs
sudo apt-get install npm


You can upgrade npm and nodejs using npm itself as well
sudo npm install -g npm

sudo npm cache clean -f
sudo npm install n -g

sudo  npm cache clean -f
sudo npm install -g n
sudo  n stable
OR 
sudo n 0.12.7 
copy to usr/local/n/versions/node/0.12.7/

npm cache ls

npm cache clean 

global path = /usr/local/lib/node_modules

npm install <module> --save-dev


```

####Dependency pack for build (if need)
```bash
npm install -g node-gyp
npm install -g node-pre-gyp
```

#### Node JS Debugger
```bash
npm install -g node-inspector
npm install -g node-inspector@0.10.0

npm uninstall -g node-inspector
```
#### Kill Nodejs

```bash
ps aux | grep node
killall -9 any node
```