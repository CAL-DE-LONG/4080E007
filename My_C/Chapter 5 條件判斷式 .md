# 5-1 判斷 kpi 是否達成 與 年資是否在一年內

### if 條件判斷
```
if (條件算式){
  動作程式
}
```

### 程式設計
```
#include <stdio.h>
#include <stdlib.h>

int main(void){
	
    float salary = 2220.56 ; //薪水金額
    float kpi = 1.5 ;        //kpi 達成率 150%
    float bonus ;            //宣告 獎金 變數
    float seniority = 0.9 ;  //年資0.9年 
	
    if (kpi >= 0.85 && seniority < 1){
	
        bonus = salary * kpi * kpi * kpi + 2000 ;
        printf("年資未滿 1 年優秀員工 , 恭喜獲得 kpi 獎金為 %6.2f \n",bonus);
        
    }
	
    if (kpi >= 0.85 && seniority >= 1){
	
        bonus = salary * kpi * kpi * kpi ;
        printf("恭喜獲得 kpi 獎金為 %6.2f \n",bonus);
		
    }
    
    printf("祝新年快樂\n");
	
    system("pause");
    return 0;	
	
} 
```
	
# 5-2 判斷杯數是否達到打折標準

### if-else 條件判斷
```
if (條件算式){
  動作程式 1
}
else{
  動作程式 2
}
```

### 程式設計
```

```

### if-else if 條件判斷
```
if (條件算式 1){
  動作程式 1
}
else if (條件算式 2) {
  動作程式 2
}
else if (條件算式 3) {
  動作程式 3
}
--------------------------
依情況而定，可做省略。

else{
  最後動作程式
}

```
