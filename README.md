  
# 🔮🚀 PancakeSwap Prediction AI Bot v1.1.0

![PancakeSwap-Logo](/img/logo.jpg?raw=true)

PancakeSwap Prediction Bot with AI-Generated Recommendations.

## ⭐Please consider giving a **star**.



## 🐰⚡ Installation

Download and Install Node here:
https://nodejs.org/en/download/

Then run the following commands in terminal:

1. ``git clone https://github.com/Beatthehouse/pancakeswap-prediction-ai-bot`` 
2. ``cd pancakeswap-prediction-ai-bot``
3. ``npm i``

![enter image description here](/img/setup.jpg?raw=true)




## ⚙️ Setup

1. Open the **.env** file with any code/text editor and add your private key like so:
```
PRIVATE_KEY=0x00000000000000000000000000000000000000000000000000000000
```
3. Open the **bot.js** file and setup the following variables:
```
BET_AMOUNT: 5, // Amount of each bet (In USD)
DAILY_GOAL: 20, // Total profit you are aiming to earn (In USD)
```
4. Start the bot using `npm start` or `yarn start`
5. 🔮 Enjoy!

### 🔓 How to convert seed phrase to Private Key
A lot of wallets don't provide you the private key, but just the **seed phrase** ( 12 words ). So here you will learn how to convert that to a private key:
1. Enter [Here](https://youtu.be/eAXdLEZFbiw) and follow the instructions. Website used is [this one](https://iancoleman.io/bip39/).

![Winning rate](/img/rate.jpg?raw=true)


## 🤖📈 Strategy

Boost Your Trading Success with Our AI-Powered PancakeSwap Prediction Bot!
- Our bot takes a series of recommendations from Trading View and processes them along with the betting trends of other users. After the algorithm has completed, it makes a prediction on whether to bet **🟢UP** or **🔴DOWN**.
- Through testing approximately 300 rounds, we were able to achieve a **~70% win rate**. Of course, results may vary based on various factors, but we have consistently made $20-$70 daily with just $3 bets.
- Before each round, the bot will check if you have sufficient balance in your wallet and if you have reached your daily profit goal. 
- It will also save a daily history in the **/history** directory.
- Please note that after consecutive losses, there is a higher statistical probability of winning in the next round.
- In the ``THRESHOLD`` property of the ``GLOBAL_CONFIG`` variable in **bot.js**, you can configure the minimum level of certainty required for the bot to make a bet. The default is set to 50, meaning the bot will only bet if it has at least 50% certainty in its prediction. You can increase this threshold (between 50-100) to only bet when the bot is more confident in its prediction.
- It is recommended to have **at least 10-50 times** the amount of your bet to average a sufficient number of rounds.

💰You can check the history of rounds and claim rewards here: https://pancakeswap.finance/prediction

## ✔️ To Do 

 - [x] USD Based bet 
 - [x] Show real time profit 
 - [x] Show real time win rate 
 - [x] Daily goal profit 
 - [x] Improved algorithm 🔥
 - [x] AI Driven bot 🔥
 - [x] Stop Loss
 - [x] Simplify settings 
 - [ ] Auto collect winnings 


## 👁️ Disclaimers

**Please be aware of clones**

 👷**Use it at your own risk.** 
 If you are going to bet, please do it with money that you are willing to lose. And please try to bet with a low amount to gradually generate profit.
