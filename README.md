# Lockphish v3.0

**This tool is based on a tool originally created by the github user `The Linux Choice` (Who deleted his GitHub repository).**

Lockphish it's the first tool for phishing attacks on the lock screen, designed to grab Windows credentials, Android PIN and iPhone Passcode using a https link.

### Features:

#### Lockscreen phishing page for Windows, Android and iPhone
#### Auto detect device
#### Port Forwarding by Ngrok
#### IP Tracker

### Requirements:
The packages `php`, `unzip`, `wget` and a pre-existing ngrok executable(to set the authtoken) are required.

Before running the tool for the first time we need to set our authtoken for ngrok:
```
ngrok authtoken <YOUR_AUTHTOKEN>
```

### Usage:
```
git clone https://github.com/skerdibash/lockphish.git
cd lockphish
bash lockphish.sh
```
## Conclusion
This is a great phishing tool which you can use in your android system as well as pc.
Just install **Termux** and follow the usage command.

## Legal disclaimer:

Usage of Lockphish for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program.

