# [cd ../](../../index.md)
# Treeeeee

> It appears that my cat has gotten itself stuck in a tree... It's really tall and I can't seem to reach it. Maybe you can throw a snake at the tree to find it?

> Oh, you want to know what my cat looks like? I put a picture in the hints.

## Files
[treemycatisin](treemycatisin.7z)

# Start
- Extract the zip file and we got a lotta subfolders and images in it
- We have to remove the duplicates  
I used [fdupes](https://www.tecmint.com/fdupes-find-and-delete-duplicate-files-in-linux/) to remove them.  
After that I just made a search for files.
```
find bigtree/ -type f

bigtree/P24AKQCA/I0E91C/6SF60/N02AKM/EAJCOQ6/ENP92.jpg
```

- We got the file  
Open it and u will get the flag.  
![flagfile](flagfile.png)

# G0t th4 flaG
```
rtcp{meow_sharp_pidgion_rice_tree}
```
