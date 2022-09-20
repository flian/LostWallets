# LostWallets

![wallet.dat](https://user-images.githubusercontent.com/82582647/190867530-275ae6ad-eb78-43f1-9600-f5628739ed05.png)</br>
**Find password get 50% balance**</br>

## How to search for a password
Download the latest version of hashcat [**here**](https://github.com/hashcat/hashcat/releases)</br>
An example of using masks in hashcat is [**here**](https://cheatsheet.haax.fr/passcracking-hashfiles/hashcat_cheatsheet/)</br>
The hashes of the passwords [**here**](https://github.com/phrutis/LostWallets/blob/main/README.md#heshes-table)</br>

## Examples:</br>
Run: ```hashcat.exe -m 11300 -a 3 hash.txt ?a?a?a?a?a?a?a?a -D 2 -w 3 -o FOUND.txt```</br>
Run: ```hashcat.exe -m 11300 -a 7 --increment hash.txt -1 ?l?d ?l?l?l?l?1?1?1?1 prefix.txt -D 2 -w 3 -o FOUND.txt```</br>
Run: ```hashcat.exe -m 11300 -a 1 hash.txt WORDLIST.txt WORDLIST2.txt -D 2 -w 3 -S -o FOUND.txt```</br>
Run: ```hashcat.exe -m 11300 -a 3 --increment --increment-min=3 --increment-max=7 hash.txt ?a?a?a?a?a?a?a -D 2 -w 3 -o FOUND.txt```</br>
Use your password search prefixes by mask or [dictionaries](https://www.weakpass.com/wordlist)</br>

If you manage to find the password, write to me in telegram ```phrutis```</br>
Do not write me questions, look for answers on the [forum](https://hashcat.net/forum/)</br>

- [**wallet.dat - Addresses Table**](https://github.com/phrutis/LostWallets/blob/main/Others/wallet.dat-addresses.md)
- [**wallet.dat - HASHES Table**](https://github.com/phrutis/LostWallets/blob/main/Others/wallet.dat-addresses.md)
- [**wallet.dat - Password Hints**](https://github.com/phrutis/LostWallets/blob/main/Others/Hints.txt)
- [**Fake wallet.dat**](https://github.com/phrutis/LostWallets/tree/main/fake-wallets)</br>
- [**Frequently asked Questions**](https://github.com/phrutis/LostWallets#frequently-asked-questions)

You can search by yourself if you find the password you will get 50%</br>
Or you can take part in a collective search<hr>

# How to participate in a collective search:
If you have a GPU and are willing to search 24/7. If not, you can rent it at [**vast.ai**](https://vast.ai/console/create/)</br>


Join telegram group [**LostWallets**](https://t.me/+uJsWbjsN-485YTUy)</br>
[**Write your empty BTC address, get a voucher to connect to the server**](https://t.me/+uJsWbjsN-485YTUy)

Hunter address [**table**](https://github.com/phrutis/LostWallets/blob/main/Others/Table.md)

Server Hashtopolis [walletdatuss.work](http://walletdatuss.work/)</br>
Work task and statistics:</br>
Login: ```hunter```</br>
Password: ```demo```</br>

## Connecting a GPU card from [**vast.ai**](https://vast.ai/console/create/)

Step by Step [Instruction](https://github.com/phrutis/LostWallets/blob/main/Others/manual%20hashtopolis%20vast.pdf)

```
xasser/hashtopolis_agent_vastai:latest

cd htpclient
python3 hashtopolis.zip --url http://walletdatuss.work/api/server.php --voucher (your voucher example: CBt9iiIZ)
```

## Windows 
Download [Python](https://www.python.org/downloads/)</br>
When installing the program, check the patch in Windows</br>
We press Start, we write ```cmd```, we press the left key and drag it to the desktop.</br>
We launch the cmd shortcut on the desktop, a window opens.</br>
We enter the commands:</br>
```py -m pip install --upgrade pip```</br>

```pip install requests```</br>

```pip install psutil```</br>

Download agent [hashtopolis.zip](http://walletdatuss.work/agents.php?download=1)

Create a CAT folder, copy hashtopolis.zip into it</br>
Go to the CAT folder, right-click on the folder, properties.</br>
Copy the path to the archive example: C:\Users\User\Downloads\CAT</br>
In the console window, enter the command:</br>
```cd C:\Users\User\Downloads\CAT```</br>

```py .\hashtopolis.zip```</br>
Please enter the url to the API of your Hashtopolis installation:</br>
```http://walletdatuss.work/api/server.php```</br>
No token found! Please enter a voucher to register your agent:</br>
Your voucher example: ```CBt9iiIZ```</br>
Successfully registered!

Add to the group [**LostWallets**](https://t.me/+uJsWbjsN-485YTUy), report your empty BTC address, an agent will be assigned to you.</br>
If you have any questions about connecting, please contact the group

## Linux

```
sudo apt update
sudo apt-get update
sudo apt install git
sudo apt -y install nvidia-opencl-dev
sudo apt-get install python3-pip
python3 -m pip install psutil
pip3 install requests
sudo apt-get install links
```

Download agent [hashtopolis.zip](http://walletdatuss.work/agents.php?download=1)

```py hashtopolis.zip```</br>
Please enter the url to the API of your Hashtopolis installation:</br>
```http://walletdatuss.work/api/server.php```</br>
No token found! Please enter a voucher to register your agent:</br>
Your voucher example: ```CBt9iiIZ```</br>
Successfully registered!

Add to the group [**LostWallets**](https://t.me/+uJsWbjsN-485YTUy), report your empty BTC address, an agent will be assigned to you.</br>
If you have any questions about connecting, please contact the group

## The advantage of collective search:
You will not go through combinations that have already been completed.</br>
Many lone hunters very often make mistakes.</br>
The server controls all ranges and issues new ones.</br>
You do not need to select the correct masks, hashes and more.</br>
If the password is found, all participants will win and receive coins.

## The terms of participation:
25% - Received by the partner (whose hash is in the table)</br>
 5% - Organizers</br>
70% - is divided among all participants in % of ranges covered.</br>

For example, you searched for 3 days and stopped.</br>
The password was picked up in 3-6 months from a wallet of 500 BTC.</br>
The sum of 70% of the find of 350 BTC is divided by the number of combinations passed.</br>
You will be paid % for your completed segment.</br>
The more combinations you have completed, the higher your %</br>
Make sure your address is in the [**table**](https://github.com/phrutis/LostWallets/blob/main/Others/Table.md).</br>
In a collective search, everyone wins.</br>
Enough coins for everyone
<hr>


## Frequently asked Questions
**Are your wallets real?**</br>

99% - YES</br>
Wallets were maximally checked for validity.</br>
Coins were sent to some dubious wallets for verification.</br>
There is no way to verify wallet.dat is 100%</br>
This can only be done if the correct password is entered.<hr>

**How do you have so many wallets?**</br>

Jacks were presented to me by various hunters for 25% of the amount of the find.</br>
Hunters received wallet.dat by exchanging with other hunters.<hr>

**If I find. What are the guarantees of paying me 50% ?**</br>

If you find the hash password.</br>
Write to me in telegram ```phrutis```</br>
After agreeing, and receiving your BTC address from you.</br>
Sending coins to 3 addresses will be prepared.</br>
Your address is 50% 1......?</br>
Partner address 25% (btc address from table)</br>
My address is 25% bc1qh2mvnf5fujg93mwl8pe688yucaw9sflmwsukz9</br>

A password will be required to confirm the transfer.</br>
I give you the id of a [**Anydesk**](https://anydesk.com) (Windows remote desktop) running bitcoin core.</br>
You connect, you see the active bitcoin core what and where it is sent. </br>
Check your address, enter your password and click send transfer.</br>
So there will be a guarantee and security for all participants.</br>
The characters are hidden in the input window.</br>
An example of a screenshot of entering a password</br>
![pass](https://user-images.githubusercontent.com/82582647/171959020-8192f5ad-6d3c-4295-af77-8fe348769853.png)
<hr>

**I have an old wallet.dat (not from a table) want 25%**</br>

You can contact me in telegram ```phrutis```</br>
Provide me with the old wallet.dat</br>
After verification, it will be added to the table with your btc address.</br>
If hunters find password you will get 25%<hr>

**I have a wallet.dat with the same hex, there is a different amount, it's empty, it's a fake?**</br>

You may have an older version of wallet.dat</br>
There is a newer one in the challenge.</br>
In a later version, the user could add a new address and receive coins on it.</br>
The old version of wallet.dat does not have this address.</br>
Or vice versa.<hr>


**Sell me all your wallets**</br>

I don't sell or buy wallet.dat</br>
And I do not advise you to buy.<hr>

