# 🧙‍♂️ Those Wizards Cast Starter

This repo is a script used to start selenium, open [https://cast.thosewizards.com.au/](https://cast.thosewizards.com.au/) and click the share stream button.

## Inintial installation

* Every line that doesn't have a # is a command to run one at a time

```
# Get updates for your OS package manager
sudo apt-get update
sudo apt-get upgrade

# Download node
curl https://nodejs.org/dist/v12.18.3/node-v12.18.3-linux-armv7l.tar.xz -o node.tar.gz

# Extracting the zip file
tar xvzf node.tar.gz

# copy node to your usr/local path
cp -R node-v12.18.3-linux-armv7l/* /usr/local/

# check if it installed correctly by running
node -v
npm -v

# both should display a version
```


* Install dependencies (this installs selenium)

```
npm install
```

## Running the script

* Once everything is installed, running the script is just:

```
npm run start-cast
```
