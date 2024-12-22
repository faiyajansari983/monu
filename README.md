termux command for find SNI bughost
termux-setup-storage
pkg update && pkg upgrade
pkg install python
pip install -upgrade pip
pip install requests loguru multithreading bugscanner
pkg install git
git clone https://github.com/JagadBumi/subfinder
Is
cd subfinder
Is
mv subfinder ~/../usr/bin
chmod +x ~/../usr/bin/subfinder
cd /sdcard
Is
subfinder -d phonepe.com -o xyz.txt
Is
bugscanner xyz.txt
bugscanner --method GET xyz.txt --proxy 104.19.147.8 --port 80
bugscanner storage/downloads/sorted_unique_cf_5.tx
