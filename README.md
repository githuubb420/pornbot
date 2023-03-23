
<b>
<a href="https://heroku.com/deploy?template=https://github.com/githuubb420/pornbot"><img src="https://img.shields.io/badge/DEPLOY ON HEROKU-Canary?style=badge&logo=heroku"width="310" height="50"/></a>
</b>



sudo apt update && apt upgrade -y
sudo apt install git curl python3-pip ffmpeg -y
pip3 install -U pip
git clone https://github.com/DARKWEBREBEL/PORN-HUB # clone the repo.
cd PornHub
pip3 install -U -r requirements.txt
cp sample.env .env # use vim to edit ENVs
vim .env # fill up the ENVs (Steps: press i to enter in insert mode then edit the file. Press Esc to exit the editing mode then type :wq! and press Enter key to save the file).
python3 -m PornHub # run the bot.


