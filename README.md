# [cyberdBot](http://t.me/cyberdbot)
Telegram bot for [cyberd](http://github.com/cybercongress/cyberd/) node status data and upload content to IPFS
## Install
Install [IPFS node](https://docs-beta.ipfs.io/install/command-line-quick-start/)  
Install [cyberd node](https://cybercongress.ai/docs/cyberd/run_validator/)  
Clone repository:
```bash 
git clone https://github.com/Snedashkovsky/cyberdBot
```
Add your Telegram Bot Token into `start_bot.sh`
## Run
```bash  
./start_bot.sh  m|main|s|scheduler  [d|dev]

Using:
   m|main - Main Bot
   s|scheduler - Monitoring Scheduler
   [d|dev] - Development Mode
```
