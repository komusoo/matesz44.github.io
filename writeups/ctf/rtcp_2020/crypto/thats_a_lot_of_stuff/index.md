# [cd ../](../../index.md)
# That's a Lot of Stuff . . .
## Description
> Do you want some numbers? Here, take these numbers. I don't need them anyways. I have too many numbers at home, so go on, take them. *Shoves numbers towards the computer screen*  
> 31 34 33 20 31 35 36 20 31 32 32 20 31 35 32 20 31 34 33 20 31 31 30 20 31 36 34 20 31 35 32 20 31 31 35 20 31 30 37 20 36 35 20 36 32 20 31 31 35 20 36 33 20 31 31 32 20 31 37 32 20 31 31 35 20 31 32 34 20 31 30 32 20 31 36 35 20 31 34 33 20 36 31 20 37 31 20 31 35 30 20 31 34 33 20 31 35 32 20 31 31 36 20 31 34 36 20 31 31 36 20 31 30 36 20 37 31 20 31 35 32 20 31 31 35 20 31 30 34 20 31 30 32 20 31 31 35 20 31 33 30 20 36 32 20 31 31 35 20 36 30 20 31 34 34 20 31 31 30 20 31 31 36 20 37 31

# Start
- That seems like hex so open [cyberchef](https://gchq.github.io/CyberChef/) and paste in and select from hex
- Now we can see some 3 char numbers <- THATS `octal`
- Apply a `from octal` decryption and we got a little mess
- Probably some base. Lets try `from base64`
![flag](flag.png)

# Got the flag
```
rtcp{c0nv3rs10ns_ar3_4_c00L_c4ts}
```