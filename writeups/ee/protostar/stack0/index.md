# Stack 0
```c
#include <stdlib.h>
#include <unistd.h>
#include <stdio.h>

int main(int argc, char **argv)
{
  volatile int modified;
  char buffer[64];

  modified = 0;
  gets(buffer);

  if(modified != 0) {
      printf("you have changed the 'modified' variable\n");
  } else {
      printf("Try again?\n");
  }
}
```
**It needs an input**
And we can see in the source the max is `64` *characters*.

## Fuzzin it

So we enter 64 `A` and see what happens(protip: open python and type `print 'A'*64` -> copy and paste).
- We got `Try again?`
Now enter 65!
- We got `you have changed the 'modified' variable`.
## OH boiiii we got it (:
