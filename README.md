# Crypto Asset Transfer Application

This application enables users to send/ receive cryptocurrency between clients and contractors. 

---

## Technologies

This project runs on python 3.7 and includes the following libraries and dependencies:

* streamlit
* os
* requests
* dotenv
* load_dotenv()
* bip44
* Wallet
* web3
* Account
* middleware
* web3.gas_strategies.time_based
* medium_gas_price_strategy

---

## Installation Guide 

To use the application you need to install the following dependencies: 

pip install streamlit
pip install web3==5.17
pip install eth-tester==0.5.0b3
pip install mnemonic
pip install bip44

## Download the Latest Version of Ganache

Follow the instructions on the Ganache download page https://trufflesuite.com/ganache/ to download and install this tool on your local machine.

### Create a Workspace

When you open Ganache, you are presented with two options for creating a workspace: Quickstart Ethereum and New Workspace Ethereum. Click Quickstart Ethereum.

<img width="693" alt="ganache" src="https://user-images.githubusercontent.com/105071493/211078928-5b2a75cc-47ce-4991-853d-b6134ae11b15.png">

## Usage 

To use this application just clone the repository and in the terminal navigate to the project folder, run the Streamlit application by using streamlit run fintech_finder.py.

You can now view your Streamlit app in your browser.

On the app you can select a fintech professional from the application interface’s drop-down menu, and then input the amount of time for which you’ll hire the worker. Click the Send Transaction button to sign and send the transaction with your Ethereum account information. To varify the transaction navigate to the Transactions section of Ganache .

## Usage Examples 

Recipient's address balance and history: 

<img width="1195" alt="Screen Shot 2022-10-30 at 4 14 02 PM" src="https://user-images.githubusercontent.com/105071493/198906907-4a8b6d88-c5fa-4cb6-b5a2-c8b1fc437cbb.png">

Transaction details:

<img width="1188" alt="Screen Shot 2022-10-30 at 4 14 58 PM" src="https://user-images.githubusercontent.com/105071493/198906958-a0029b55-867d-41cf-bb35-599fff874f8f.png">

---

## Contributors

Name: Sterling Davis 
Email: sterlingdayvis@gmail.com
LinkedIn: www.linkedin.com/in/sterlingdavis1

---

## License

MIT






