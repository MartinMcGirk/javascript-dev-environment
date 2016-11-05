# javascript-dev-environment
The beginnings of a dev setup for me for writing ES6 javascript in Visual Studio Code, initially following along with the tutorial at https://github.com/verekia/js-stack-from-scratch

I'm using Visual Studio Code, and if you are too, you'll want to install the eslint plugin so that you get native eslint support.

You'll need to run the following commands on your machine for this setup to work.

```
curl -sL https://deb.nodesource.com/setup | sudo bash -
sudo apt-get install nodejs
sudo apt-get install build-essential

sudo npm install -g yarn

yarn
```

Then run the following command from the root directory of the repository:

```
yarn start
```
