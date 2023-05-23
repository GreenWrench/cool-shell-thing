# shell
(i made it txt just because)
I design this for only Debian/Ubuntu users (I will update this soon though)
If you want to download this, there are a couple steps you need to do first.

Step 1
copy and paste the following into your terminal:

sudo apt install sl
sudo apt install fortune
sudo apt install neofetch
sudo apt install cowsay
sudo apt install xcowsay
sudo apt install telnet
sudo apt install lolcat
sudo apt install figlet
sudo apt install toilet
sudo apt install libaa-bin
sudo apt install nano

Step 2
download the zip in this respository.

Step 3
Assuming you have terminal set up, go to your files and you should a thing named Linux.
Drag and drop every single file you just downloaded and put them in there.

step 4
type nano ~/.bashrc
don't delete the code that's already there. Instead, type under it.

Paste this: 

figlet -cl "                farty fart yuh"
echo "-----------------------------------------------------------------------------------------------"
echo "
"
neofetch
echo "
"
lolcat stinkier.txt 
echo "
"
curl https://wttr.in/(ENTER CITY HERE but do not put spaces. examples, newyork)?0
date
echo "
"
echo "fortune of the day:"
echo "
"
fortune
echo "
"
lolcat stinky.txt
echo "
"
Step 5
do ctrl+X to get out and you should be ready to go

if you notice, where it says curl, type your city. It will display the weather.
And of course you can edit this to whatever you want.

Search up a youtube tutorial if you dont have the terminal set up.

Also if you want to run ./ip.sh then first you have to do this:

chmod +x ./ip.sh
this allows you to run ./ip.sh
