
# :video_game APNS 
-----
**xAPNS** is a Web Tool which let you send dummy Push Notifications to your iOS Device. 

## Hosted
http://api.greensyntax.co.in/apnsPHP/

## Objective
So, If you have evred worked on Push Notification, then it's always difficult to test the code wheather Push Notifications are coming or not. So, xAPNS will let you do that. What you need in order to test the Push Notifcations, 
* APNS Token
* *.pem certificate 

## Features
[x] Woks for both Development and Distribution Certificate
[x] Plain Text Push Messages
[x] Customize Push Message as per your need

## How to Genrate PEM from p12 Certificate
1. First, you need to drag APNS **p12 Certificate** (if you're not aware of these)
2. Then, convert p12 certificate into **pem** file. And, open your **Terminal**
```
openssl pkcs12 -in pushcert.p12 -out pushcert.pem -nodes -clcerts
```
Here, pushcert.p12 is the name of p12 file. Your's might be different. And, I'm assuming you're in the same 

## Report Bug
If you have any issue with the app, please report an Issue.


