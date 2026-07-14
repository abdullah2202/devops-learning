# Bandit Levels and Answers

## Level 1
### Password 
- 6y2kwnwK6grgvwvpvLaa2T1cpFEKOhNR

### Commands
- pwd, ls, cat

## Level 2
### Password
- 
- PK8fYLZg2hnHSz83plBL1iEPKdD3QToB

### Commands
- cd, cat

## Level 3
### Password
- 7ZZ2LFrykP2zEyvBl4m3clcL7tGYJPME

### Commands
- pwd, cs, cat

## Level 4
### Password
- xzTXq1rDJQVVAzdv5cHq1TQytTWufAMq

###Commands
- ls, ls -a, cat

## Level 5
### Password
- 6C7h9GD8M6ai5nr7wo1RonrzFjj9yIrG

### Commands
- ls -la, cat, file ./*

## Level 6
### Password
- pXa26xhMWaC2SvDotA4r9EgZkulOeSBW

### Commands
- ls, du -b -a | grep 1033, cat

## Level 7
### Password 
- Bmnnvf82KzQlfxgAI2d1zYbr1u9pr3E3

## Commands
- ls, find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null

## Level 8
### Password
- VR1ljMayciFxbnUokuQmJFw6QC9VKtub

### Commands
- ls -l, cat data.txt | grep millionth

## Level 9
### Password
- EjmOSvuAu7sGAHqHVcBDPirRe9T03kxl

### Commands
- sort data.txt | uniq -u

## Level 10
### Password
- B0s2khmbT9u0geKuOoVGW3JZKhndE3BG

### Commands
- ls -l, strings data.txt | grep ===

## Level 11
### Password
- pYfOY6HwUsDj5rL9UvyhU7MCmv8vN5Ro

### Commands
- ls -l, base64 -d data.txt

## Level 12
### Password 
- GROozWPO8QyN0mGrjUkID0WCYkZiQxrN

## Commands
- cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'

## Level 13
### Password 
- qQYQiHOBPR8zR61qxYqX45quvihF2uzk

### Commands
- mktemp, tar, gzip, bzip2, mv, cp

## Level 14

### Password
- aaWecNkG4FhxJQxz07uiwzVP6bJiYS65

### Commands
- scp, ssh -i sshkey.private

## Level 15
### Password
- pbLYuZtTg4MgaqfJx8jbA9gKKGqM68A7

### Commands
- nc localhost 30000

## Level 16
### Password
- kS0Hf0u5HiXFwKMKFqXvPdOTNGGa0X8V

### Commands
- openssl s_client

## Level 17
### Password
- SSH Key

### Commands
- openssl s_client -connect localhost:31790 -ign_eof


## Level 18 
### Password
- OQxXZjELndr90zuhOTDYBEomI0SZITXI

### Commands
- diff passwords.old passwords.new

## Level 19
### Password
- 

### Commands
- 
