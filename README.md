# **TrustAPT (TAPT) - APTOS Blockain for Transfer APT Tool**

## **🔍 Overview**
TrustAPT (TAPT) is a decentralized application built on the APTOS blockchain that enables users to send APT tokens securely in split group expenses.
it allows a user to create an expense, invite contributors (participants), and automatically distribute funds to a recipient once the total amount is collected all in a transparent and tamper-proof way using Move Smart contract.

## 🔗 Future Core Features

Features Description
*	**Create Expense**			-	Creator sets up the group expense and defines key details.
*	**Track Contributions**	-	Each participant’s APT contribution is tracked on-chain.
*	**Auto Settlement**			-	Once the total amount is reached, funds are sent automatically.
*	**Escrow Mechanism**		-	Funds are held temporarily by the creator’s account until settlement.
*	**Immutable Records**		-	All data is stored on-chain via Aptos smart contracts.

## 🔐 How TrustAPT Works (Flow Summary)
- User connects wallet.
- Creator creates expense (total amount, recipient, list of participants).
- Participants contribute APT using the DApp interface.
- Once fully funded, the smart contract automatically settles the payment by sending funds to the recipient.
- Expense is marked as settled and becomes immutable.
  
## 📌 Example Use Cases
- Splitting vacation costs among friends.
- Group gift purchases.
- Shared rent or utility payments.
- Event expenses (parties, meetups).

## 🧠 Built With
- Smart Contracts: Written in Move and deployed on Aptos.
- Frontend: React, Next.js with Aptos wallet integration.
- Wallets Supported: Petra, Martian.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
  
# Simple Project for the APTOS "Decentralized Splitter" https://www.figma.com/design/x26nsseAYFjYXvAKAV0W56/Figma-basics?node-id=1669-162202&t=ZpKNNHXYNCka782X-1
This is simple project and learnings for the APTOS 
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
**The purpose of this project is to enable a group of users to split expenses in a decentralized, trustless way using smart contracts on the Aptos blockchain.**
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
**Transparency:** All contributions and expense data are recorded on-chain.

**Security:** Funds are held and transferred through verified logic.

**Automation:** Once the required total amount is collected, it auto-settles by transferring the funds to the designated recipient.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------

**> git --version**

**> git clone init https://github.com/codivv/simpleproject_APTOS.git**

**> cd simpleproject_APTOS.gi**t

**> git status**

-----------------------------------------------------------------------------------------------------------------------------------------------------------------
Using WINDOWS > https://aptos.dev/en/build/cli/install-cli/install-cli-windows

**Terminal POWERSHELL**

**> Set-ExecutionPolicy RemoteSigned -Scope CurrentUser; iwr https://aptos.dev/scripts/install_cli.ps1 | iex**

-----------------------------------------------------------------------------------------------------------------------------------------------------------------
On VSCODE

> aptos init 


