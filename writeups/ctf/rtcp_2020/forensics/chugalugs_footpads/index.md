# [cd ../](../../index.md)
# Chugalugs_Footpads

## Description
>

## Files
[left.jpg](left.jpg) and [right.jpg](right.jpg)

# Start
- Its a stego challenge
- We have 2 imgs
	- Left is a lilbit weird
- We need to spot the difference!!

## Converting imgs to hex
- We have to convert them to hex to be able to spot the difference  

```
xxd left.jpg > left.hex
xxd right.jpg > right.hex
```

- Now we have the hexes
- Open them in vimdiff  

```
vimdiff left.hex right.hex
```

- Write down the letter differences in left.jpg and we will get the flag

# G0tch4 baby
```
rtcp{Th3ze_^r3_n0TcH4nC1a5}
```
