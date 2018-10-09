# README
Simple keylogger for linux based systems
## Setup
```console
coneill@kali-home:~$ apt-get update
coneill@kali-home:~$ apt-get install virtualenv
coneill@kali-home:~$ cd <location-of-repo>
coneill@kali-home:~$ virtualenv .
coneill@kali-home:~$ . bin/activate
coneill@kali-home:~$ pip install -r requirements.txt 
coneill@kali-home:~$ python keylogger.py
```

## Usage
```console
coneill@kali-home:~$ python keylogger.py
```
This will write the ~/Desktop/file.log by default.


