# FastMail
fastmail, free and fast custom temporary email
<img src="https://img.shields.io/badge/made%20with-python-blue.svg?style=flat-square" alt="made with python">
## Screenshot
<img src="https://github.com/Mrp1r4t3/FastMail/blob/main/IMG_20230709_132216.jpg" width="60%" height="70%">
#

## Termux Installation
1. `pkg install git -y`
2. `pkg install python python-pip -y`
3. `pip install requests`
4. `cd $HOME`
5. `git clone https://github.com/Mrp1r4t3/FastMail`

## Usage
1. `cd FastMail`

Help:
`python fastmail.py --help`
##
Run normally:
`python fastmail.py`
##
Load tempmail from saved file:
`python fastmail.py -f <email data file>`
##
Delete tempmail:
`python fastmail.py -d <email data file>`

