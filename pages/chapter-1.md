![Rokoko Scene](/assets/rokoko_chap1.png)

# Chapter 1 (Rokoko Setup)

## Rokoko Suit Setup

When setting up the Rokoko motion capture suits the YouTube setup series made by Rokoko will cover all the general setup instructions for getting started with the suits. All you need to do is download Rokoko Studio from their website and create an account. 


{% video %}https://youtube.com/playlist?list=PL0nPCZDbYnms3zt1-A1cmf-S1fGyS6Rc3{% endvideo %}

{% youtube src="https://youtu.be/KW_qS-nwbbs" %}{% endyoutube %}




Although this covers most of the setup, I will point out a few key factors that are either mentioned in the video only briefly or not at all. Firstly, the motion capture suits use 3 different sensors to be able to work properly which one can be very sensitive to outside forces. This would be the magnetometer which can be easily influenced by magnetic interference caused by metal beams being in walls, technology near the suit, and finally of course magnets. The studio space is an extremely poor recording space for these suits with extreme levels of magnetic interference that degrade the quality of recordings. To check if a room is workable space for the suits, download an EMF reader on your phone which will give you general reading. You should be looking for a room that reads generally 450mG's or lower but can check online with Rokoko to see if this has changed. 

Second, firewall issues when connecting to your Wi-Fi router (no internet over this Wi-Fi). If you're having connection issues where your Wi-Fi settings are getting accepted in Rokoko Studio, but the suit still isn't showing up on the Wi-Fi then check your firewall settings. Your firewall settings should approve these lines of what are in the images below for it to connect properly to Rokoko Studio. If it still isn't connecting to Rokoko Studio even when approving it through the firewall, turn off all connection that is to the internet and try turning off your firewall and windows security to see if it connects with them off. Make sure your computer isn't connected to the internet because your computer will have no security up during this troubleshooting process.

![Hidden Firewall Changes](/assets/firewall1.png)
![Rokoko Studio Firewall](/assets/firewall2.png)

Lastly, damaged sensors or bootloader error with it not applying firmware to sensors. If the sensors on the suit do not light up at all or blinking red on the suit and in Rokoko Studio, then there is a good chance the sensors have died. There are only two backup sensors, one for each suit, which you can replace but please be careful when replacing them as they're not the most durable material. If the sensors are not showing up in Rokoko Studio but are blinking green, then you most likely are running into a bootloader issue. For this you will need to contact Rokoko Studio support for them to send you a file that can release the sensors from the bootloader issue. I have already run into this issue with both suits and fixed them with the file which the support team said would fix the issue forever but thought I should still bring it up in this documentation.

Rokoko support is based in Europe so take into consideration that they mostly operate from 10pm-11am EST. You can submit a ticket during their off hours, but the responses will only come around those times. If you're using the suits for a project and are having issues, contact support quickly if you can't figure it out in a couple of hours. They're extremely helpful and can even hop on a call with you to troubleshoot any issues you're having.
