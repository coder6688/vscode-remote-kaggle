# Local development and remote run on kaggle
Step 1: Generate SSH Keys
ssh-keygen -t rsa -b 4096 -C "kaggle_remote_ssh" -f ~/.ssh/kaggle_rsa

Step 2: Add new SSH Key in Github settings -> SSH and GPC keys -> new SSH key
```
cat ~/.ssh/kaggle_rsa.pub
```

example:
```
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQDY8u05p+ERWY8SIyJYryyenQfi6CEj3NqqOPxHKgk9eLg9wyTgHkggqICJ7dl1Bn4cB69hDsOU9z3tIJOXXC9fl6SFwcK/d9QN0Ilh5aGecl8UUkXQaEOdc0J1rVjYmVBF39jMg4+Mf5HQLk13WNAq2yefEIl2rsJp2ePBEyoYHLI3jtCa7Gk+i/lP8lV2zvYJKRQUxkFyqYNiKE50xjGMH76f20TLeMlzx0EOOWZrmShRDW8bkNuIxJqKfIvpT1+J2cI04ccnKwe4Js3sHbhnuLpjxn15GjcZVSxjLAgZvNKqgvLcbTkYMTlYbIhlkaaaQYc46u8Z3l6FO/PlxAldzuwPGkEXPIqCoknnMB/wsmPbx3RmFGrLHV9bMznxuxhJ/fvKYwJ44YyIVagIvdSUpwUDDbvHijLLfn25C8vircOwBZHaRWmi87FEEUqBw5Y8xm4Ryvwgs3UEBIU4GXptfqAcwShSbsB61WQWhKVaN6XO9t4T80hymrTet2Meowf2gqQSvG5wBqGojVUj/vxqfW2AbTEtpH/RR6Roqw1aHJ1cbatp0XwibtWR/kcPThoANikpsOvE29YL74/UBYIExMjJg/PGkPp/kXIWvDPDeFCDomgBw+eoc7X/wNGq5kXgX/cJk1QsXWonoqg0ps7ZsvhHWvRKzU2lUzTsNQ1XzQ== kaggle_remote_ssh
```

## Local development
1. install virtual environment
* install or select python 3.8.5 as virtual environment

2. create jupyter notebook
