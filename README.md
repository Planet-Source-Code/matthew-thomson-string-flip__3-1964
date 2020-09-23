<div align="center">

## String Flip


</div>

### Description

Just a small program to flip a string
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Matthew Thomson](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/matthew-thomson.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |C, C\+\+ \(general\), Microsoft Visual C\+\+
**Category**       |[Strings](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/strings__3-26.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/matthew-thomson-string-flip__3-1964/archive/master.zip)





### Source Code

```
// stringflip.c : Defines the entry point for the console application.
//
#include "stdafx.h" //C users delete this line
#include<string.h>
#include<stdio.h>
#include<conio.h>
void main()
{
	char name[25]; char backwards[25];
	int j, i, k;
	printf("Please enter your name > ");
	gets(name);
	j = i = strlen(name);
	for(k = 0; k <= j-1; k++)
	{
		backwards[k] = name[i-1];
		i--;
	}//end for
	backwards[k] = '\0';
	printf(backwards);
	printf("\n");
}//end main
```

