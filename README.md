# npm-notes

### Installing npm latest version
sudo npm install npm -g

### Checking logged in user
npm whoami

### Adding user
npm adduser

### Creating package.json file
npm init

### Creating package.json file with username
npm init --scope=\<username>

### Docs for creating package.json file
npm help json

### To install a module
npm install \<modulename>

### To show installed modules
npm ls

### To install and save module in package.json simultaneously
npm install \<modulename> --save

### Adding test file in package.json
"scripts": {
    "test": "node test.js"
  }
  
### Installing all dependencies listed in package.json
npm install

### Publishing module
npm publish

### Unpublishing module
npm unpublish

### Updating version of module
npm version [ major | minor | patch ]

### Adding dist-tag
npm dist-tag add \<pkg>@\<version> [\<tag>]

### Removing dist-tag
npm dist-tag rm \<pkg> \<tag>

### Detecting outdated dependency
npm outdated

### Updating outdated dependency
npm update

### Removing a dependency
npm rm \<pkg> 

or 

npm uninstall \<pkg>

### Removing a dependency and updating package.json simultaneously
npm rm \<pkg> --save

or

npm uninstall \<pkg> --save

