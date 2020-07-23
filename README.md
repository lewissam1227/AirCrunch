# AirCrunch
Pipes crunch into aircrack for easy wifi cracking


Use:
1. After download, make executable chmod +x AirCrunch2.sh
2. Run script: ./Aircrunch2.sh
3. It will tell you to press enter to continue, press enter. 
4. Next it will ask for the path to your .cap file, so find the path and input it. For example if it's on your desktop /home/username/Desktop/-01.cap
5. It will ask you to input the BSSID. This will be from when you captured the handshake, it will be the mac address of the wireless access point device. For example 82:3F:5D:6C:67:5D
6. Then it will ask for min character length. You can really save time and space here. If you know how many digits the password is, or know that it's more characters than a certain number input it here. For example, I know this password is more than 6 characters, so I'm going to put in 7. There is no point in trying all passwords below 7 characters.
7. It will then ask for max character length. Same as min length, input what you think or know could be the maximum character length for the password. If you know the exact number of characters, then min and max should be the same number. 
8. Next it will ask if you want to use all possible characters. If you don't know anything about the characters used, just hit y and enter and it will use every possible character. 
9. If you hit n and press enter it will ask you to type in what characters you want to use. If you happen to know through social engineering, typical passwords used, you can kind of guess at the characters used for a password. This helps save time. If you know it's all numbers, type in all the numbers. If you know it's all lowercase letters, type in all the lower case letters. etc...
10. Next part is what most of these crunch scripts don't offer... more parameters with patterns. For example, say you know for whatever reason that the last 4 characters of a password is 1234, but you don't know or remember the first 4 characters. You can set up a known pattern in crunch to save time. Use the @ symbol for placeholders of characters to try for any characters available,  the "," for uppercase the % for numbers, and the ^ symbol for symbols. If I know that the password is all numbers, I will iput %%%%1234 to test out those first 4 characters that I don't know. 
11. If you don't know any pattern and just want to try every possible combination, you can just hit enter. 
12. Crunch will then autopopulate a running wordlist for Aircrack and will begin cracking your password. 
13. Happy Hacking!
