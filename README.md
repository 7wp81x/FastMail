# FastMail
fastmail, free and fast custom temporary email

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


Run normally:
`python fastmail.py`
Load tempmail from saved file:
`python fastmail.py -f <email data file>`
Delete tempmail:
`python fastmail.py -d <email data file>`

