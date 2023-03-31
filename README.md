# Longevity Map, new edition

This is a website which you can use to find the information about different human genetic variants associated with longevity (based on [LongevityMap](https://genomics.senescence.info/longevity/) by João Pedro group). Currently in the development stage.


# Setting up #

The project depends on nodejs and yarn. Note: official software sources of Linux distributions rely on outdated versions of node and yarn
The easiest way to install latest nodejs is using https://github.com/nvm-sh/nvm
```bash
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
nvm install node
```
Then install yarn and use it for dependencies resolution:
```bash
npm install -g yarn
yarn install
```

# Getting started #
### with yarn ###

Install all dependencies according to the instructions on the bottom of readme.

Run `yarn dev`

```bash
yarn dev
```

## Troubleshooting
Try to run the server and client separately.

Choose PORT and HOST

```bash
yarn server
```
and in another terminal
```bash
yarn client
```
check