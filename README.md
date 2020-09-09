# Telegram-Scraper-Adder-Complete
this version of python script will help you to add members to your telegram group without having any problems all instructions are given below please perform them step by step by DareDevilKinng

this method is created only for education purposes only.

-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*
                                             STEP BY STEP PROCEDURE 
*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-


# Telegram-Scraper & Adder

PROCEDURE:-

$ pkg install -y git python
$ ls


$ git clone https://github.com/cancerlethal/Telegram-Scraper-Adder-Complete.git
$ ls


$ cd Telegram-Scraper-Adder-Complete
$ ls


Install requierments
$ python3 setup.py -i
$ ls


To setup configration file ( apiID, apiHASH )
$ python3 setup.py -c
$ ls


To Genrate User Data
$ python3 scraper.py
$ls
( members.csv is default if you changed name use it )


Send Bulk sms To Scrpped data
$ python3 smsbot.py members.csv
$ ls


add users to your group
$ python3 groupadd.py members.csv
$ ls


Update Tool
$ python3 setup.py -u
$ ls
