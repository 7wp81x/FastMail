# FastMail
Fastmail, free and fast custom temporary email
<img src="https://img.shields.io/badge/made%20with-python-blue.svg?style=flat-square" alt="made with python">
## Screenshot
<img src="https://github.com/Mrp1r4t3/FastMail/blob/main/IMG_20230709_132216.jpg" width="100%" height="100%">

## Termux Installation

```
pkg install git python python-pip -y
pip install requests
cd $HOME
git clone https://github.com/Mrp1r4t3/FastMail
cd FastMail
```
<br>

## Usage

**Help**:<br>
```
python fastmail.py --help
```
**Run normally**:<br>
```
python fastmail.py
```
**Load tempmail from saved file**:<br>
```
python fastmail.py -f <email data file>
```
**Delete tempmail from saved file**:<br>
```
python fastmail.py -d <email data file>
```

