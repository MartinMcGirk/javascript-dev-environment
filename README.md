# javascript-dev-environment
The beginnings of a dev setup for me for writing ES6 javascript in Visual Studio Code, initially following along with the tutorial at https://github.com/verekia/js-stack-from-scratch

You'll need to run the following commands on your machine for this to work.

```
curl -sL https://deb.nodesource.com/setup | sudo bash -
sudo apt-get install nodejs
sudo apt-get install build-essential

sudo npm install -g yarn

yarn add --dev gulp
yarn add --dev gulp-babel
yarn add --dev babel-preset-latest
yarn add --dev del
```

The run the following command from the root directory of the repository:

```
yarn start
```
