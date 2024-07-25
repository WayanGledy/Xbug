before executing these commands in termux... extract the bot file in ur internal storage.

apt update
apt upgrade
pkg update && pkg upgrade
pkg install bash
pkg install libwebp
pkg install git -y
pkg install nodejs -y 
pkg install ffmpeg -y 
pkg install wget
pkg install imagemagick -y
pkg install yarn
termux-setup-storage
cd /sdcard
cd cheemsbot14
yarn install
npm start
