# even.h
a single header C library to easily determine if a number is even<br>
<br>
there is surely no other way of doing this :)<br>

---

## Why????????
for the funny<br>

## How????????
like this!<br>
```c
// define this in only one file
#define EVEN_IMPLEMENTATION
#include "even.h"

int main(int argc, char** argv) {
	if(isEven(2)) {
		printf("2 is even :)\n");
	} else {
		printf("HOW\n");
		return 1;
	}
	return 0;
}
```

## Who????????
<https://kittrz.gay/>

## Why does it only go up to 65535?
I would've gone up to UINT32\_MAX but the file would've taken up ~162 GB, and UINT64\_MAX would probably take up about 600 **exabytes**.<br>
really the only thing stopping me from using the UINT32\_MAX one is github's file size limit (which is I think 2 GB for a free account).<br>

## Has this been done before?
probably!<br>

