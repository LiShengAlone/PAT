[^code]
```


#include<stdlib.h>
#include<windows.h>
#include<stdio.h>

int main(int argc,char* argv[])
{
	printf("请输入命令：\n");
	printf("\t1:关机\t\t2:重启");
	char a;
	scanf("%c",&a);
	switch(a)
	{
		case '1':
			printf("5秒后关机！！！");
			Sleep(1500);
			system("shutdown -s -t 5");
			break;
		case '2':
			printf("5秒后重启！！！");
			Sleep(1500);
			system("shutdown -r -t 5");
			break;
				
	}
	
	return 0;
}




```
