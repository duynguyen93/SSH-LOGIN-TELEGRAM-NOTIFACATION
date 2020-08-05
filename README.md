# Send Telegram Notification On SSH Login

### Requirement
- install `jq`,`git` to read JSON file format

##### On Ubuntu
> apt-get -y install jq git
>

##### On Centos
> yum install epel-release -y && yum install jq git -y
>

### Create Telegram Bot, Get TokenID, ChatID:
- Go to see: [How To Create Telegram Bot] (https://github.com/duynguyen93/GET-TELEGRAM-TOKENID-CHATID)


### Install and Config Script
Clone or download source to /opt/ folder:

> - git clone https://github.com/duynguyen93/ssh-login-telegram-notification.git
- cd ssh-login-telegram-notification && cp -r ssh-login-telegram-notification.sh /etc/profile.d/
- chmod +x /etc/profile.d/ssh-login-telegram-notification.sh
- Change your TokenID, ChatID in: `/etc/profile.d/ssh-login-telegram-notification.sh`
>

