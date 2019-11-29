# 定義常數
```
#define 常數名稱 常數值
```

# 2-1 計算圓周長
```
#include <stdio.h>
#include <stdlib.h>

#define R  5.0      //定義 半徑 
#define PI 3.14159  //定義 圓周率常數 

int main(void){
	
	printf("圓周長 = %f\n",2 * PI * R) ; //計算半徑為5.0的圓周長 
	
	system("pause"); //保留畫面 
	return 0;        //程式結束 回傳 0 
	
} 
```
### 執行結果
```
圓周長 = 31.415900
```

# 2-2 顯示手搖飲的售價
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
	int Signature_Milk_Tea = 40 ; //宣告 招牌奶茶變數並指定初值 
	int Pearl_milk_tea = 45 ;     //宣告 珍珠奶茶變數並指定初值 
	
	int cup_Signature_Milk_Tea = 1 ; //招牌奶茶的杯數初值為 1杯 
	int cup_Pearl_milk_tea = 1 ;     //珍珠奶茶的杯數初值為 1杯 
	
	printf("招牌奶茶 %d 杯 %d 元\n",cup_Signature_Milk_Tea,Signature_Milk_Tea);
	printf("珍珠奶茶 %d 杯 %d 元\n",cup_Pearl_milk_tea,Pearl_milk_tea);
	
	system("pause"); //停留畫面 
	return 0;        //程式結束 回傳 0 
} 
```
### 執行結果
```
招牌奶茶 1 杯 40 元
珍珠奶茶 1 杯 45 元
```

# 2-3
