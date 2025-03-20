# Getting Started with Akash

**Akash Network** is a decentralized marketplace for cloud computing that revolutionizes how cloud resources are utilized by providing an open, independent, and competitive platform. Instead of relying on traditional centralized solutions, Akash uses a decentralized model where server owners can offer their unused computing resources, and developers can rent them at competitive prices. This approach provides a flexible, secure, and cost-effective cloud environment that operates without intermediaries or unnecessary restrictions. Here's a closer look at how it operates:

### How Akash Network Works

Akash Network uses blockchain and smart contract technologies to create a decentralized platform for computing resources. Participants in the network are divided into two main categories:

- **Akash Providers:**  Individuals or organizations that have extra computing resources can list them on the Akash Network. These resources include CPU, GPU, memory, storage, and more—everything needed for cloud computing.  

- **Akash Tenants:** Developers or businesses looking for cloud services can search for and lease these resources based on their specific requirements, such as geographic location, hardware specifications, or price.

### Key Benefits of Using Akash

- **Decentralization**: No single organization or company controls the entire network. All actions in the network are executed via smart contracts, ensuring transparency and security.  
- **Lower Costs**: Due to high competition among providers, resource prices on Akash are significantly lower than traditional cloud providers like AWS or Google Cloud.  
- **Flexibility**: You can lease resources for a variety of purposes — from simple websites to complex AI workloads.  
- **Open Source**: Akash's infrastructure is fully transparent and built on open-source code, allowing anyone to verify and propose changes to the system's code.

### Deployment Process

- **Creating a Lease Offer**: The tenant specifies the resources they need in a deployment manifest (a YAML file). This manifest is then broadcasted across the network, where providers can bid to host the workload.  

- **Bidding Process**: Resource providers offer their servers for lease, and the system automatically initiates an auction. Tenants can select a provider based on factors such as price, uptime, audit availability, GPU type, or location.

- **Smart Contract Signing**: After agreeing on the price and resources, a smart contract is signed between the provider and the tenant. This ensures that both parties fulfill their obligations.  

- **Application Deployment**: The tenant gains access to the resources and can deploy their application or service on the Akash platform.  

- **Payment and Lease Termination**: After using the resources, the provider receives payment in **AKT tokens**. The lease is automatically terminated at the end of the rental period. The tenant can also close it at any time.  


### What Will You Learn in This Guide?

This guide will help you get started with Akash Network, even if you have never worked with decentralized cloud platforms before. You will learn:  

✅ How to create a wallet for Akash.  
✅ How to acquire and use AKT tokens.  
✅ How to set up the Akash Console.  
✅ How to deploy your first application on Akash.  

### Who Is This Guide For?

This guide is ideal for:  

- Developers looking to try decentralized cloud hosting.  
- Startups searching for cost-effective alternatives to traditional cloud solutions.  
- Anyone interested in Web3 and blockchain technologies.  

Ready to get started? 🚀 Let's create your first wallet!


---

# 1. Creating Your First Crypto Wallet

### What is a Crypto Wallet?
To start using the Akash Network, you need a cryptocurrency wallet. (You can also add funds using a credit card, which we will discuss in the following sections.) A crypto wallet is a digital tool that stores your private keys, which are necessary to access and manage your cryptocurrency on the blockchain. It doesn’t hold the coins themselves but acts as a secure gateway to your funds, allowing you to send, receive, or stake them.

### Why Do You Need One?
A crypto wallet is essential for keeping your assets secure, protecting them from exchange vulnerabilities, and giving you full control over your cryptocurrency. It enables easy management and interaction with decentralized applications.

### Compatible Wallets for Akash Network
Several wallets support the AKT token used on Akash Network. Based on compatibility with the Cosmos ecosystem, these include:
- **Keplr**: A popular browser extension wallet, user-friendly and widely recommended.
- **Leap**: A simple and intuitive wallet designed for Cosmos users.
- **Cosmostation**: Available as a mobile app and web interface, supports AKT.

For this guide, we’ll focus on setting up **Keplr**, a common choice for Akash Network users.

### Step-by-Step Guide: Setting Up Keplr Wallet
Follow these steps to create and configure your Keplr wallet for Akash Network:

- **Download and Install**  
   - Go to the official Keplr website ([keplr.app](https://www.keplr.app/)).  
   - Download the browser extension for Chrome or Firefox and follow the installation prompts.

- **Open Extension**  
   - Click the Keplr icon in your browser’s extension bar to launch the wallet interface.

- **Create Wallet**  
   - Select “Create a new wallet” to begin the setup process.

- **Secure with Seed Phrase**  
   - Select "Create new recovery phrase". 
   - Keplr will generate a 12-word seed phrase. Write it down on paper and store it in a safe, offline location — this is critical for recovering your wallet if needed.

- **Verify Seed Phrase**  
   - Re-enter the seed phrase words corresponding to the numbers displayed on the screen to confirm that you have saved them correctly.

- **Set Password and Wallet Name**  
   - Choose a convenient name for your wallet and enter it in the appropriate field.
   - Create a strong, unique password and confirm it to secure your wallet.

- **Select Supported Chains**
   - Select the chains you need. Initially, we recommend selecting all the available chains—you can adjust these settings later.

✅ Congratulations! You have successfully created your first Crypto Wallet. 

### Tips for Success
- Never share your seed phrase or password with anyone.
- Double-check the network when transferring AKT to avoid losing funds.
- Keep a backup of your seed phrase in a secure location.

Now, let's explore how to add funds to your wallet.








---

# **2. Getting AKT Tokens**  

AKT is the native token of the Akash Network and serves as the backbone of its decentralized ecosystem. It plays a fundamental role in various aspects of the network, including payments for resources, staking, governance, and liquidity.  

Let’s take a closer look at each function:  

#### **1️⃣ Payments for Resources**  
AKT is used as a primary payment method in the Akash decentralized marketplace, where users rent cloud computing resources from providers. The price is determined by supply and demand, making cloud services more affordable and transparent.  

#### **2️⃣ Staking and Rewards**  
AKT holders can stake their tokens by delegating them to validators, who process transactions and maintain the network. In return, delegators earn rewards, and validators are incentivized to participate actively in the ecosystem.  

#### **3️⃣ Governance and Decision-Making**  
AKT token holders who participate in staking can take part in on-chain governance, voting on proposals that influence network upgrades, economic parameters, and overall protocol development. This ensures a community-driven and decentralized decision-making process.  

#### **4️⃣ Liquidity and Financial Utility**  
AKT is widely used in various financial applications across the Cosmos blockchain ecosystem. Holders can provide liquidity, earn yield, and engage in decentralized trading and investment opportunities.  

Through these functions, AKT facilitates transactions, enhances decentralization, and supports the economic stability of Akash Network. 🚀  



## **How to Get AKT Tokens**  

There are two main ways to acquire AKT tokens:  

- **Through a Centralized Exchange (CEX)**  
  You can find the full list of exchanges that support AKT tokens on the official **[Akash Network website](https://akash.network/token/)**. In this guide, we’ll use **KuCoin** as an example.  

- **Through a Decentralized Exchange (DEX)**  
  The primary DEX for purchasing AKT tokens is **Osmosis**, and we will cover it as well.  


## **How to Find Your AKT Wallet Address in Keplr**  

To receive **AKT** tokens, you need to locate your wallet address in **Keplr**.  

#### **Step 1: Open Keplr Wallet**  
- Click on the **Keplr extension** in your browser.  

#### **Step 2: Select Akash Network**  
- In the search bar, type **Akash** and select it from the list of available networks.  

#### **Step 3: Copy Your Wallet Address**  
- Your unique Akash Network wallet address will be displayed at the top of the wallet interface.  
- Click **Copy Address** and save it securely.  
- Use this address when withdrawing AKT from an exchange or receiving tokens from another wallet.  



## **Buying AKT on a Centralized Exchange (KuCoin)**  

One of the simplest ways to obtain AKT is by purchasing it on a centralized exchange like **[KuCoin](https://www.kucoin.com/)**.  

#### **Step 1: Create a KuCoin Account**  
- Visit the **[KuCoin website](https://www.kucoin.com/)** and complete the registration process.  
- Complete **identity verification (KYC)** to unlock full trading and withdrawal features.  

#### **Step 2: Deposit Funds**  
- In your KuCoin account, navigate to **Funding Account → Deposit**.  
- Choose **USDT** or another cryptocurrency that can be exchanged for **AKT**.  
- Select the appropriate network for the transfer.  
- Copy the deposit address and send funds from your existing crypto wallet or another exchange.  

#### **Step 3: Buy AKT**  
- Transfer your **USDT** from the Funding Account to the Trading Account.  
- Go to **Trade → Spot Trading**.  
- Search for the **AKT/USDT** trading pair.  
- Enter the amount of AKT you want to buy and confirm the transaction.  

#### **Step 4: Withdraw AKT to Your Wallet**  
- Move your **AKT** from the Trading Account to the Funding Account.  
- Navigate to **Funding Account → Withdraw** and select **AKT**.  
- Enter your **Akash wallet address** (which you copied from the Keplr wallet).  
- In the **Network** field, select **Akash Network**.  
- Confirm the withdrawal and wait for the tokens to arrive in your wallet.  



### **Buying AKT on a Decentralized Exchange (Osmosis DEX)**  

For those who prefer a **decentralized** method, AKT can be purchased on **[Osmosis DEX](https://app.osmosis.zone/)**.  

#### **Step 1: Connect Your Wallet**  
- Open **[Osmosis](https://app.osmosis.zone/)** and click **Connect Wallet**.  

#### **Step 2: Deposit Funds to Osmosis**  
- If you don’t have **ATOM**, **USDC**, or other tokens on Osmosis, transfer some from your Keplr wallet or a centralized exchange.  
- In the **Assets** section, find the token you have in your Keplr wallet and click **Deposit**.  
- Approve the deposit transaction in your Keplr wallet.  

#### **Step 3: Swap Tokens for AKT**  
- Go to **Trade → Swap** and select the trading pair (e.g., **USDC → AKT**, **ATOM → AKT**, or other available pairs).  
- Enter the amount you want to swap and click **Swap**.  
- Confirm the transaction in your Keplr wallet.  

#### **Step 4: Withdraw AKT to the Akash Network**  
- In the **Assets** section, find **AKT** and click **Withdraw**.  
- Select **Akash Network** as the destination chain.  
- Confirm the transaction and check your Keplr wallet for the received tokens.  

---  

## **Checking Your AKT Balance in Keplr**  

Once you've received AKT, you should verify that the tokens have arrived in your wallet.  

- **Open Keplr Wallet** in your browser.  
- In the search field, enter **AKT**.  
- Your **AKT balance** will be displayed on the main screen.  

---  

## **Deposit to Your Account Using a Credit Card**  

You can also top up your account with a **credit card** to deploy applications on Akash.  

To do this, go to the [**Akash Network Console**](https://console.akash.network/)—a user-friendly deployment interface.  

### **Step 1: Register an Account**  
- Click **Sign Up** in the upper right corner.  
- Enter your **email and password**, or sign up using your Google account.  
- Confirm your registration.  

### **Step 2: Connect Your Wallet**  
- In the upper right corner, click **Connect Wallet**.  
- Select your **Keplr** wallet.  

### **Step 3: Deposit Funds**  
- Hover over your account balance in the upper right corner.  
- Click **Start Trial**.  
- In the same menu, click **Add Funds**.  
- Verify your **email address**.  
- Enter the required payment information and confirm the deposit.  

### **Step 4: Check Your Balance**  
- After a short processing time, the funds will appear in your account.  

✅ **Done!** Now you have the funds and are ready to deploy on Akash Network. 🚀  

Let’s move on to deploying your first application. We’ll use a tool you’re already familiar with—the Akash Network Console.  

But before diving in, you need to create a **certificate** to ensure security and compliance with the network’s protocols. This certificate is essential for deploying and managing workloads safely.  

---







# **3. Deploying Your First Application on Akash Network**  

Let’s move on to deploying your first application. We’ll use a tool you’re already familiar with—the **Akash Network Console**.  

But before diving in, you need to create a certificate to ensure security and compliance with the network’s protocols. This certificate is essential for deploying and managing workloads safely.  

### **Step 1: Create a Certificate**  
1. Go to the **"App Settings"** menu.  
2. Scroll down to find the **"Certificates"** section.  
3. Click **"Create Certificate"** and confirm the action in your Keplr wallet.  
4. Once confirmed, your certificate will be generated successfully.  

To deploy an application on the Akash Network, you need to prepare a **Docker image** of the application, create a **manifest file** that defines the required resources, and submit this information to the network to enable provider selection. After the agreement is confirmed, your application will be deployed automatically on the allocated resources.  

### **Step 2: Deploying a Simple Next.js “Hello World” App**  
To help you understand how the process works, we’ll deploy a simple **Next.js “Hello World”** app. A ready-made template is available, making it easy to get started.  

#### **Finding the Template**  
1. Click **"Get Started"** at the top, next to your balance.  
2. In the first step, the system checks if you have sufficient funds for deployment (**0.5 AKT** or **5 USDT**).  
   - This section also provides a link to the official **Akash Network Discord server** and brief instructions on funding your account.  
3. If you have enough funds, click **"Next"** to proceed.  



### **Step 3: Understanding Docker Requirements**  
1. The next section informs you that a **Docker container image** is required for deployment.  
2. You’ll find links to:  
   - The official **Docker documentation**.  
   - A list of all ready-to-use templates for Akash.  
3. After reviewing this information, click **"Next"**.  

### **Step 4: Deploying the App**  
1. In the final step, you’ll be offered to deploy a **simple Next.js web app**.  
   - You can view the app’s code via a link to **GitHub**.  
2. Once you’ve reviewed the information, click **"Deploy"**.  



### **Step 5: Reviewing the YAML File**  
1. You’ll be redirected to a page displaying the **YAML file** for your deployment.  
   - This file contains a detailed **SDL configuration** with comments explaining each section.  
2. Carefully review the file, then click **"Create Deployment"**.  


### **Step 6: Choosing a Provider**  
1. After confirming the deployment, the system will search for a provider that can meet your resource requirements.  
2. Choose a provider based on:  
   - **Price**  
   - **Uptime**  
   - **Audit status**  
   - **Region**  
3. Check the box next to your chosen provider and click **"Accept Bid"**.  
   - The deployment process will start automatically on the selected provider's resources.  

  

### **Step 7: Monitoring Deployment**  
1. Go to the **"Logs"** tab to monitor the deployment progress.  
2. In the **"Leases"** tab, you’ll find the **URI** for your app.  



### **Congratulations! 🎉**  
Your application is now successfully deployed on Akash Network! 🚀  



### **Additional Options**  
- You can **close, rename, or redeploy** your app at any time by clicking the **three dots** next to the deployment name.  
- To increase the funds allocated to the deployment, click **"Add Funds"**.  



You’ve now learned how to start your journey with **Akash Network**. Stay tuned for the next lessons, where we’ll dive deeper into the platform’s capabilities! 🚀  
=======
In the next step, we will show you how to acquire AKT tokens to start deploying applications. 🚀
>>>>>>> 8f03a062e8c984d97f5c4d0dec05e78bdaa4fcb2
