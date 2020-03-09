# [cd ../](../../index.md)
# [basics] crypto
> Can you make it through all of the encodings?  
> by balex  
> PTS: 50

## Files
[binary](binary.txt)

# Start
[cyberchef](https://gchq.github.io/CyberChef)

## binary decode
We got a little text, a hint and the next crypted text.  
[decoded_bin](decoded_bin.txt)

## Base64 decode (only the encrypted text)
We got an other text, a big hint and the chall.  

> hint: you might want to start looking up Roman people

[decoded_base64](decoded_base64.txt)

## Rot13 -> 16
It could be ceasar crypt(`ROT`)!  
Just go to cyberchef chose the `ROT13` recipe then try **changing** the *rot amount*!  
At `16` we got the text!  
[decoded_rot16](decoded_rot16.txt)

## Substitution cipher
We got the hint from the previous text so break the cipher.  
There are some solver websites i used [this](https://www.guballa.de/substitution-solver)  
[decoded_subs](decoded_subs.txt)

# Got it
```
utflag{n0w_th4ts_wh4t_i_c4ll_crypt0}
```

