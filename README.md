# Telegram-Scraper-Adder-Complete
this version of python script will help you to add members to your telegram group without having any problems all instructions are given below please perform them step by step 100% working procedure by DareDevilKinng.

this method is created only for education purposes only.

-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*
                                             STEP BY STEP PROCEDURE 
*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-


# Telegram-Scraper & Adder


NOTE : these commands are for android devices. All Android devices are supported.



PROCEDURE:-


$ apt update && upgrade


$ pkg install python


$ pkg install python -y


$ pkg install git -y


$ pkg install -y git python
 

$ git clone https://github.com/cancerlethal/Telegram-Scraper-Adder-Complete.git


$ cd Telegram-Scraper-Adder-Complete

$ ls



Install requierments

$ python3 setup.py -i



To setup configration file ( API ID, API HASH )

$ python3 setup.py -c



To Genrate User Data

$ python3 scraper.py

( members.csv is default if you changed name use it )



Send Bulk sms To Scrpped data

$ python3 smsbot.py members.csv



Add users to your group

$ python3 groupadd.py members.csv



Update Tool

$ python3 setup.py -u

