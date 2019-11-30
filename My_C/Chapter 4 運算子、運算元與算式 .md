# 4-1 計算 鈔票 與 硬幣
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    int Milk_tea = 35 ;        //奶茶        35元 
    int black_tea = 20;        //紅茶        20元 
    int Cappuccino = 50 ;      //卡布奇諾    50元 
    int Coffee_latte = 80 ;	   //咖啡拿鐵    80元 
    int Pearl_milk_tea = 45 ;  //珍珠奶茶    45元 
    int Winter_melon_tea = 30 ;//冬瓜茶      30元 
    int Pudding_milk_tea = 60 ;//布丁奶茶    60元 
    int Alishan_Iced_Tea = 100;//阿里山冰茶 100元 
	
    int total ; //總額 
    int temp1 ; //商數 
    int temp2 ; //餘數 
	
    total = Milk_tea * 5 + black_tea * 10 + Cappuccino * 5 	+ Coffee_latte * 1 + Pearl_milk_tea * 5 + Winter_melon_tea * 2
          + Pudding_milk_tea * 3 + Alishan_Iced_Tea * 1 ;
    printf("總共花費： %d 元\n",total);
	
    temp1 = total /1000 ; //除以1000 , 計算要用到幾張千元紙鈔 
    temp2 = total %1000 ; //餘額 
    printf("需要 1000元 紙鈔 %d 張\n",temp1);
	
    temp1 = temp2 /100 ; //除以100 , 計算要用到幾張百元紙鈔  
    temp2 = temp2 %100 ; //餘額 
    printf("需要  100元 紙鈔 %d 張\n",temp1);
	
    temp1 = temp2 /10 ; //除以10 , 計算要用到幾張十元硬幣  
    temp2 = temp2 %10 ; //餘額 都是一元硬幣 
    printf("需要   10元 紙鈔 %d 張\n",temp1);  
    printf("需要    1元 紙鈔 %d 張\n",temp2);
	
    system("pause");
    return 0;	
	
} 
```
### 執行結果
```
總共花費： 1270 元
需要 1000元 紙鈔 1 張
需要  100元 紙鈔 2 張
需要   10元 紙鈔 7 張
需要    1元 紙鈔 0 張
```

# 4-2 









