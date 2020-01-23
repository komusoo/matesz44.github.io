# Kojo_No_Mai
> Prunus Incisa "Kojo No Mai" is the Japanese name for a dwarf or bonsai cherry. Although small things can be precious it is not a good idea to use them in cryptography ... cause usually with a small key it is easier to break the encryption, right?

- We got a file [kojonomai.txt](kojonomai.txt)

# Start it
## RsaCtfTool
`python RsaCtfTool.py --publickey pubkey.pub --private` and we got the private key [file](privkey.priv)`
```
-----BEGIN RSA PRIVATE KEY-----
MGQCAQACEQDkqWSwe1VxO4mQO9mE0vOVAgMBAAECEQDdv/jJvZHK0CDDfXs8vASB
AgkA6nTNPNoXOLkCCQD5rEi0wt8rvQIJANrmxP0MzuOZAgkAy4+dA8vyWt0CCA7U
J3WkWZCx
-----END RSA PRIVATE KEY-----
```
- Then we have to **base64 decode** every other line to outfiles like `echo -n "XnZvSmNqZqz+N5LL+ec6XA==" | base64 -d > ki_1`
- We have ***ki_1-8*** and we can now decrypt them one by one with *openssl*  
`openssl rsautl -decrypt -in ki_1 -out dec_1 -inkey privkey.priv`
- Then we got ***dec_1-8***
- We have to *cat* them together
```
cat dec_*
H-c0n{1aa36c2eb49a2f427e57c715bda839e6}
```
# WE GOT IT YAAAY
