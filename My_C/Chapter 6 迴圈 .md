
### for 迴圈
```
for (初始算式 ; 條件算式 ; 控制算式){
  迴圈動作
}
```

# 6-1 從 1 加到 100 , 1+2+ ... +99+100

```
#include <stdio.h>
#include <stdlib.h>

int main(){
	
    int i , sum = 0 ; //宣告 迴圈變數 i , 總和 初值 為0 
	
    for (i = 1 ; i <= 100 ; i++){ //設定i的初值為1,跑100次for迴圈 
		
       sum = sum + i ; //sum 累加 
		
       printf("sum的值 %d\n",sum); //輸出結果 
		
    }
	
    system("pause");
    return 0 ;
	
}
```
### 執行結果
```
sum的值 1
sum的值 3
......
sum的值 4950
sum的值 5050
```

# 6-2 從 1 加到 100 的所有奇數 , 1+3+5+ ... +99 

```
#include <stdio.h>
#include <stdlib.h>

int main(){
	
    int i , sum = 0 ; //宣告 迴圈變數 i , 總和 初值 為0 
	
    for (i = 1 ; i <= 100 ; i=i+2){ //設定i的初值為1,跑100次for迴圈 
		
       sum = sum + i ; //sum 累加 
		
       printf("sum的值 %d\n",sum); //輸出結果 
		
    }
	
    system("pause");
    return 0 ;
	
}
```
### 執行結果
```
sum的值 1
sum的值 4
......
sum的值 2401
sum的值 2500
```

### 巢狀 for 迴圈
```
for (初始算式 1 ; 條件算式 1 ; 控制算式 1){
    for (初始算式 2 ; 條件算式 2 ; 控制算式 2){
        迴圈動作
    }
}
```
# 6-3 

```

```
### 執行結果
```

```
