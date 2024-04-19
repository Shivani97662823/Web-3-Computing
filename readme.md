# Installation
Node.js is required to run this project. If not already installed, please install it. After that -

1.Install Truffle globally.
`npm install -g truffle`

For reference :https://github.com/trufflesuite - automatic!
[GitHub](https://github.com/trufflesuite)

2.Install Ganache-Cli
`npm install -g ganache-cli`

For Reference:For reference :https://github.com/trufflesuite/ganache-cli - automatic!
[GitHub](https://github.com/trufflesuite/ganache-cli)

# Running the project

1. Clone the repository to a convenient location.
2. Open a termial and start the  ganache-cli by typing:
 ` ganache-cli`
 Keep this terminal running
3. Navigate to the following location in the project files : `Evn-master/node_modules/.bin`, open a terminal and run the following command,
 `chmod 755 webpack-dev-server`
You can close this terminal .
4. Go back to the parent project directory and run the following commands
 `truffle compile`
 `truffle migrate`
 This shall compile all of our smart contracts and deploy it on to the gananche ethereum blockchain that we had started in step 1.
5. Now connect the front end to the blockchain by typing the following command
`npm run dev`
