# Crypto Wallet
> In this project I completed a code that enables customers to send cryptocurrency payments to fintech professionals.

I created a a new  and disruptive platform called Fintech Finder. Fintech Finder is an application that customers can use to find fintech professionals from among a list of candidates, hire them, and pay them.  I integrated the Ethereum blockchain network into the application in order to enable customers to instantly pay fintech professionals whom they hire with cryptocurrency. 

I used two Python files, both of which this repository contains. The first file that I used is called ```fintech_finder.py```, it contains the code associated with the web interface of the application. The code included in this file is compatible with Streamlit library. The second file that I used is called ```crypto_wallet.py```, this file contains the Ethereum transaction functions that I have created throughout this project. By using import statements, I integrated the ```crypto_wallet.py``` Python script into the Fintech Finder interface program that is found in the ```fintech_finder.py``` file. Integrating these two files allows us to automate the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via Ethereum’s Kovan testnet.



## Technologies
```
os
requests
dotenv
bip44 
web3 
web3.auto.infura.kovan
web3.gas_strategies.time_based
streamlit 
dataclasses
typing
```

## Inside of the repository 

![inside_the_repository_crypto_wallet_19](https://user-images.githubusercontent.com/80844686/128583807-1cfb9b7f-248c-4b17-bb1b-a102bca7dfe4.jpg)

## Instalation Guide 


In order to open and run this program you have to follow these steps:

* Go to my repository in GitHub and open the repository called ```crypto_wallet_19```

* Copy the repository's link.

* Open Git Bash in your computer 

* Clone the repository by typing ```git clone``` and paste the link ```git@github.com:nestor39/crypto_wallet_19.git```.

After cloning the repository, you  must type in Git Bash the following code line: ```Streamlit run fintech_finder.py```, this code is going to direct you to a visual interface on streamlit in which you can see and test the code.

![streamlit run fintech_finder_crypto_wallet_19](https://user-images.githubusercontent.com/80844686/128583864-b2496c1f-6d41-4523-8f9a-4c7c48a9d39d.jpg)


## Results

Testing and interacting with the code and the visual interface:

https://user-images.githubusercontent.com/80844686/128583751-e610ac65-609b-4e8e-b79a-46666ed49103.mp4

Successful transfer

![transaction_success_crypto_wallet_19](https://user-images.githubusercontent.com/80844686/128583888-ff75825d-5ca8-45c4-8714-05b3bcec2e9d.jpg)

Transaction hash

![validated_transaction_hash_crypto_wallet_19](https://user-images.githubusercontent.com/80844686/128585751-26b7ac8f-0092-4d59-8bed-fa597a244692.jpg)

Transaction details

![transaction_detail_crypto_wallet_19](https://user-images.githubusercontent.com/80844686/128585841-50d627a7-df2c-405b-97f2-fa5a78cb20f5.jpg)


Sender's address balance and history

![sender_history_transaction](https://user-images.githubusercontent.com/80844686/128585664-15ecd466-ed90-4f43-9bb2-edcac1d22d43.jpg)



Recipient's address balance and history

![recipient_history_transaction_crypto_wallet_19](https://user-images.githubusercontent.com/80844686/128585668-76ccb609-c996-4c29-a189-cb117ba21290.png)



## Contributors

This project was made with helpful contribuitions from Berkeley Fintech Bootcamp members. 

This code was written by Nestor Ramirez.

email: nestorramirez3994@gmail.com

Linkedin: https://www.linkedin.com/in/nestor-ramirez-cuadro-375654209/


## License
[MIT](https://github.com/nestor39/crypto_wallet_19/blob/main/README.md)
