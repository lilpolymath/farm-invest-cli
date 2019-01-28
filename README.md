# Farm Invest CLI

A CLI tool built, to detect changes in the products belonging to 

- [EFarms](https://www.efarms.com.ng)
- [ThriveAgric](https://www.thriveagric.com)
- [FarmCrowdy](https://www.farmcrowdy.com)

## Installation

with npm

```sh
npm i -g farm-invest-cli
```

with yarn

```sh
yarn add global farm-invest-cli
```

for developers

```sh
git clone https://github.com/mykeels/farm-invest-cli
cd farm-invest-cli
npm install
npm link
```

## Usage

Run

```sh
farm-invest-cli
farm-invest-cli efarms # only efarms
farm-invest-cli farm-crowdy # only farm-crowdy
farm-invest-cli thrive-agric # only thrive-agric
```

You'll get an output like:

![farm-invest-cli output](https://user-images.githubusercontent.com/11996508/51835933-238da100-22ff-11e9-8dfc-1086b0db4d52.png)

Where the green text shows new products, and text is only shown when there is a difference between the products currently existing and the last time it checked.