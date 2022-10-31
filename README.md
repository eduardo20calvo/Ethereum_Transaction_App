# Ethereum Transaction App

In this project, a web application called "KryptoJobs2Go" was created in the Ethereum Blockchain using the Ganache test network in order for individuals to fictitiously hire a fintech professional. 

There is a list of 4 fintech professionals named Lane, Ash, Jo and Kendall. Each of these candidates have their own ethereum account address, job rating and hourly rate per ether.

Two python files were created. One named crypto_wallet, contains the functions needed to approriately create a crypto wallet using Python. The other named krypto_jobs contains the code for the customer interface of the "KryptoJobs2Go" web application through streamlit. 

A test was made by selecting Jo as the fintech professional. Below is a screenshot from Ganache of the ethereum wallet used to send funds and pay Jo for her work (Hourly rate was 0.19 ETH, and was hired for 40 hours for a total transaction of 7.6 ETH)

![Ganache Snip 1](https://user-images.githubusercontent.com/104874384/198918482-716ff6e6-7558-4630-bc54-5c6507800040.png)

Below you would also find the transaction details displaying information such as the user's ethereum wallet and the wallet address the funds were sent to.

![Ganache Snip 2](https://user-images.githubusercontent.com/104874384/198918521-4c7e40a8-5783-45be-b43c-bfc10142e7ab.png)

![Ganache Snip 3](https://user-images.githubusercontent.com/104874384/198918540-2284c1a0-c8f7-44c6-8e5c-066480873305.png)

As you can see, 7.6 ETH was sent to the recipients address, confirming the total rate from the web application.
