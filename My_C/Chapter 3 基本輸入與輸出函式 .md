# 3-1 輸出的字串被切斷
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    printf("請輸入密碼： \0 密碼是我的身分證字號\n"); //使用 \0 切斷字串 
	
    system("pause"); //停留畫面 
    return 0;  //程式結束 回傳 0 
	
} 
```
### 執行結果
```
請輸入密碼：
```

# 3-2 鍵盤輸出字元 + 16進位值
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    int ASCII ; //宣告 ASCII 碼
	
    printf("請從鍵盤輸入一個字元 , 並按 Enter 鍵 \n");
    ASCII = getchar(); //讀取鍵盤輸入的字元
	
    printf("你剛剛輸入的 ASCII 碼是：");
    putchar(ASCII);
    printf("\n%c 的 ASCII 碼是  %d\n",ASCII,ASCII);
    printf("%c 的十六進位值是 %x\n",ASCII,ASCII);
	
    system("pause");
    return 0;
    
} 
```
### 執行結果
```
請從鍵盤輸入一個字元 , 並按 Enter 鍵
W
你剛剛輸入的 ASCII 碼是：W
W 的 ASCII 碼是  87
W 的十六進位值是 57
```

# 3-3 輸入字元 , 列印組成的圖形
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    char c ; //宣告一個字元變數 
	
    printf("請輸入一個字元：");
    c = getche();
	
    printf("\n\n");
	
    printf("%c %c %c %c %c %c %c %c\n",c,c,c,c,c,c,c,c);
    printf("%c %c %c %c %c %c %c\n",c,c,c,c,c,c,c);
    printf("%c %c %c %c %c %c\n",c,c,c,c,c,c);
    printf("%c %c %c %c %c\n",c,c,c,c,c);
    printf("%c %c %c %c\n",c,c,c,c);
    printf("%c %c %c\n",c,c,c);
    printf("%c %c\n",c,c);
    printf("%c\n",c);
		
    system("pause");
    return 0;
	
} 
```
### 執行結果
```
請輸入一個字元：*

* * * * * * * *
* * * * * * *
* * * * * *
* * * * *
* * * *
* * *
* *
*
```






