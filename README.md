 NFT minting dapp
This repo provides a nice and easy way for linking an existing NFT smart contract to this minting dapp. There are two ways of using this repo, you can go the simple route or the more complex one.

The simple route is so simple, all you need to do is download the build folder on the release page and change the configuration to fit your needs. (Follow the video for a walk through).

The more complex route allows you to add additional functionality if you are comfortable with coding in react.js. (Follow the below instructions for a walk through).

Installation 🛠️
If you are cloning the project then run this first, otherwise you can download the source code on the release page and skip this step.

git clone {https://github.com/skillscodified/Minting-dapp-for-collection}
Make sure you have node.js installed so you can use npm, then run:

npm install




In order to make use of this dapp, all you need to do is change the configurations to point to your smart contract as well as update the images and theme file.

For the most part all the changes will be in the public folder.

To link up your existing smart contract, go to the public/config/config.json file and update the following fields to fit your smart contract, network and marketplace details. The cost field should be in wei.

Note: this dapp is designed to work with the intended NFT smart contract, that only takes one parameter in the mint function "mintAmount". But you can change that in the App.js file if you need to use a smart contract that takes 2 params.

 
Make sure you copy the contract ABI from remix and paste it in the public/config/abi.json file. (follow the youtube video if you struggle with this part).

Now you will need to create and change 2 images and a gif in the public/config/images folder, 1.gif and logo.png.

Next change the theme customization to your liking in the public/config/theme.css file.
