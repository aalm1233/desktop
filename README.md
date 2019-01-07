# How to bulid an Electron project

## Install Node.js

Download **Node.js** from https://nodejs.org/en/

after installed check it in cmd :

```cmd
C:\Users\Dengtong>npm -v
```
 ## Install cnpm

As NPM plug-in installation server to download from abroad and affected by the network, may be abnormal, if NPM server in China, so we are happy to share taobao team did it.

```cmd
C:\Users\Dengtong>npm install -g cnpm --registry=https://registry.npm.taobao.org
```

 ## Install electron

 ```
 C:\Users\Dengtong>cnpm install -g electron
 ```

 ## Install Electron-forge

 Electron-forge is a helpful package to build electron project

 ```
 C:\Users\Dengtong>cnpm install -g electron-forge
 ```

 ## Create project

* First,I save the project at `G:\electron\app\`
* Then,open the cmd to run electron-forge as :`G:\electron\app>electron-forge init myproject`

ok,now a simple electron project has been created in the myproject folder

 ## Run project

 also use electron-forge

 ```cmd
 G:\electron\app>electron-forge start
 ```