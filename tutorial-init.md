[DeWork Task Link](https://app.dework.xyz/meshjs-96531/bounty-board-59090?taskId=bd36f2d8-00f2-4af7-8a54-048ceba60fbd)

# Building an NFT Marketplace with Mesh

## Introduction and Overview

NFT (Non-Fungible Token) marketplaces have gained a lot of popularity recently due to the booming NFT market. These marketplaces provide a platform for creators and collectors to trade unique digital assets, such as artwork, music, and videos, in the form of NFTs.

Mesh is a decentralized framework for building peer-to-peer (P2P) applications on the Ethereum network. It provides a simple and efficient way to build NFT marketplaces with minimal coding effort.

To build an NFT marketplace using Mesh, you'll need the following tools:

- Mesh CLI
- MongoDB Atlas

## Hands-On Tutorial

### Step 1: Set Up the Project

Start with an empty folder and use Mesh CLI to create the marketplace starter kit by running the command:

''npx create-mesh-app my-marketplace -t marketplace -s next -l ts''

Alternatively, you can clone the GitHub repository.

### Step 2: Install Dependencies

Install the dependencies by running the following command in the project directory:

''yarn install''


### Step 3: Create a MongoDB Atlas Account

Create a MongoDB Atlas account by registering a free Atlas account using your email address.

### Step 4: Deploy a Cluster on MongoDB Atlas

Deploy your first cluster on MongoDB Atlas by giving your cluster a name and selecting the region you want to deploy it in.

### Step 5: Add IP Address to Access List

Add your connection IP address to your IP access list in Atlas to enable access to your cluster.

### Step 6: Configure the Environment Variables

Configure the .env.local file by copying the connection string from Atlas and pasting it into the MONGODB_URI field of the .env.local file.

Replace "<password>" in the MONGODB_URI field with the password you created for your database, and copy the database name you created into the MONGODB_DBNAME field of the .env.local file.

### Step 7: Start the Development Server

Once the dependencies are installed and environment variables are in place, start the development server by running the command:

''yarn dev''


### Step 8: Explore the Code

Open the file lib/marketplace.ts and explore the code. This file includes options such as fetcher, initiator, network, signer, percentage, and owner.

### Step 9: Customize the Marketplace

Customize the marketplace by modifying the code in lib/marketplace.ts as per your requirements.

### Bonus: Simple UI Customization

You can customize the UI of your NFT marketplace by modifying the CSS styles of the default interface.

## Conclusion

Building an NFT marketplace using Mesh is a relatively simple and straightforward process. By following the steps outlined in this tutorial, you can create your own marketplace in no time. With the growing popularity of NFTs, there has never been a better time to get started! 

For more information on Mesh and how to build decentralized applications, visit [meshjs.dev](https://meshjs.dev/).

## Bonus: Simple UI Customization

1. Open the `public/styles/global.css` file.
2. Modify the CSS styles to customize the appearance of the marketplace UI. For example, you can change the background color or font style.
3. Save the file and refresh the marketplace page in the browser to see the changes.




