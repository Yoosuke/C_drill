## C Drill
---?code=Lesson1.c
### Lesson1
---
### main関数
```
int main(void){

  return 0;
}
```
### コメントの書き方
```
int //型
main //関数名
(void)　//(引数)
{
  // 処理を記載する場所
  return 0; //処理の最後に0を返している。
}
```
---
### #include

```
#include <stdio.h> //これの意味は？

int main(void){

  return 0;
}
```
---
### printf()

```
#include <stdio.h>

int main(void){
  printf("Hello,World!");
  retrun 0;
}
```
１．コンソールに出力される結果を次の枠の中に書きなさい。
```
>
```
---

### \n 改行コード

```
#include <stdio.h>

int main(void){
  printf("Hello,\n World.");
  retrun 0;
}
```
２．コンソールに出力される結果を次の枠の中に書きなさい。
```
>
```
---
### \n 改行コード　ver2

```
#include <stdio.h>

int main(void){
  printf("Hello,");
  printf("\n");
  printf("World.");
  printf("_ver.2");
  return 0;
}
```
３．コンソールに出力される結果を次の枠の中に書きなさい。
```
>
```
---
### 数値の表示方法

```
#include <stdio.h>

int main(void){
  printf("1+1=%d",1+1);
  return 0;
}
```
４．コンソールに出力される結果を次の枠の中に書きなさい。
```
>
```
---
### 改行付きの数値の表示方法

```
#include <stdio.h>

int main(void){
  printf("1+1=%d\n",1+1);
  printf("1+2=%d\n",1+2);
  retrun 0;
}
```
５．コンソールに出力される結果を次の枠の中に書きなさい。
```
>
```
---
### 数値と数字の違い
```
#include <stdio.h>

int main(void){
  printf("1+1=\n");
  printf("%d+%d=%d\n",1,1,1+1);
  return 0;
}
```
６．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
### 数値と数字の違い Ver2
```
#include <stdio.h>

int main(void){
  printf("1234\n");
  printf("%d\n",1234);
  return 0;
}
```
７．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
### 四則演算子 +

```
#include <stdio.h>

int main(void){

  printf("%d\n",3+3);

  return 0;
}
```
８．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
### 四則演算子 -

```
#include <stdio.h>

int main(void){

  printf("%d\n",3-3);

  return 0;
}
```
９．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
### 四則演算子 *

```
#include <stdio.h>

int main(void){

  printf("%d\n",3*3);

  return 0;
}
```
１０．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
### 四則演算子 /

```
#include <stdio.h>

int main(void){

  printf("%d\n",3/3);

  return 0;
}
```
１１．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
### 四則演算子 %　割り算の余り

```
#include <stdio.h>

int main(void){

  printf("%d\n",10%3);

  return 0;
}
```
１２．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
### 複雑な式
```
#include <stdio.h>

int main(void){

  printf("%d\n",(1+100) * 100 / 2);

  return 0;
}
```
１３．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
### 整数と実数
```
#include <stdio.h>

int main(void){

  printf("整数：%d,%d,%d,%d\n",-1,0,1,100);
  printf("実数：%f,%f,%f,%f\n",-1.0,0.0,1.0,100.0);
  return 0;
}
```
１４．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
### 10進数,8進数,16進数
```
#include <stdio.h>

int main(void){

  printf("10進数：%d,%d,%d\n",1,10,100);
  printf("8進数：%d,%d,%d\n",01,12,0144);
  printf("16進数：%d,%d,%d\n",0x1,0x10,0x64);

  return 0;
}
```
１５．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
### 変数の宣言

```
#include <stdio.h>

int main(void){
  int i;　//変数の宣言

  return 0;
}
```
１６．コンソールに出力される結果を次の枠の中に書きなさい。
```
>
```
---
### 変数の代入
```
#include <stdio.h>

int main(void){
  int i ;
  i = 2;
  printf("1+1=%d\n",i);
  return 0;
}
```
１７．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
### 変数の初期化
```
#include <stdio.h>

int main(void){
  int i = 2;
  printf("1+1=%d\n",i);
  return 0;
}
```
１８．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
### 変数の計算
```
#include <stdio.h>

int main(void){
  int i = 2, x = 4;
  printf("1+1=%d\n", i+x);
  return 0;
}
```
１９．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
###　変数の代入演算 +=
```
#include <stdio.h>

int main(void){
  int i = 10;
  i += 20;
  printf("%d\n", i);
  return 0;
}
```
２０．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
###　変数の代入演算 -=
```
#include <stdio.h>

int main(void){
  int i = 10;
  i -= 20;
  printf("%d\n", i);
  return 0;
}
```
２１．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
###　変数の代入演算 ＊=

```
#include <stdio.h>

int main(void){
  int i = 10;
  i *= 20;
  printf("%d\n", i);
  return 0;
}
```
２２．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
###　変数の代入演算 /=

```
#include <stdio.h>

int main(void){
  int i = 10;
  i /= 20;
  printf("%d\n", i);
  return 0;
}
```
２３．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
###　変数の代入演算 %=

```
#include <stdio.h>

int main(void){
  int i = 10;
  i %= 20;
  printf("%d\n", i);
  return 0;
}
```
２４．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
###　インクリメント

```
#include <stdio.h>

int main(void){
  int i = 10;
  i++;
  printf("%d\n", i);
  return 0;
}
```
２５．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
###　デクリメント

```
#include <stdio.h>

int main(void){
  int i = 10;
  i--;
  printf("%d\n", i);
  return 0;
}
```
２６．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
###　変数の種類　実数

```
#include <stdio.h>

int main(void){
  double d = 15;
  printf("%f\n", d);
  return 0;
}
```
２７．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
###　実数と整数の計算

```
#include <stdio.h>

int main(void){
  double d = 1.08;
  int i = 100;
  printf("%f\n", i * d);
  return 0;
}
```
２８．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
###　キャスト変換

```
#include <stdio.h>

int main(void){
  double d = 1.08;
  int i = 100;
  printf("%d\n", (int)(i * d));
  return 0;
}
```
２９．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
###　桁を揃えた出力

```
#include <stdio.h>

int main(void){
  int i5,i3,i1;
  i5 = 12345; i3 = 123; i1 = 1;
  printf("5桁：%dです。\n",i5 );
  printf("3桁：%dです。\n",i3 );
  printf("1桁：%dです。\n\n",i1 );
//桁揃えた場合
  printf("5桁：%5dです。\n",i5 );
  printf("3桁：%5dです。\n",i3 );
  printf("1桁：%5dです。\n",i1 );

  return 0;
}
```
３０．コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
### 入力関数scanf
```
#include <stdio.h>

int main(void){
  int input;
  scanf("%d\n",&input);
  printf("入力された数値は＝＞%d\n", input);

  return 0;
}
```
３１．コンソールに出力される結果を次の枠の中に書きなさい。

```
100
入力された数値は＝＞
```
---
### scanfで実数の入力
```
#include <stdio.h>

int main(void){
  double input;
  scanf("%lf\n",&input);
  printf("入力された実数値は＝＞%f\n", input);

  return 0;
}
```
３２．コンソールに出力される結果を次の枠の中に書きなさい。

```
123.456
入力された数値は＝＞
```
---
### scanfで複数の入力
```
#include <stdio.h>

int main(void){
  int input1,input2;
  scanf("%d%d\n",&input1,&input2);
  printf("入力された実数値は＝＞%d,%d\n", input1,input2);

  return 0;
}
```
３３．コンソールに出力される結果を次の枠の中に書きなさい。

```
123 456
入力された数値は＝＞
```
---
### 1)バグを直しなさい。
```
#include <stdio.h>

int main(void){
  int min,max,sum;

  printf("最小値と最大値を入力しなさい。\n")
  scanf("%d%d\n",&min,&max);

  sum = (min + max) * (max-min+1) / 2;

  printf("計算結果＝＞%d\n",   );

  return 0;
}
```
３４．結果

```
最小値と最大値を入力しなさい｡
100 200
計算結果＝＞ 15150
```
---
### 条件判断 (真)
```
#include <stdio.h>

int main(void){
  int data = 1;
  if (data) printf("結果＝＞%d\n",data);
  return 0;
}
```
３５．コンソールに出力される結果

```
結果＝＞
```
---
### 条件判断 (偽)
```
#include <stdio.h>

int main(void){
  int data = 0;
  if (data) printf("結果＝＞%d\n",data);
  return 0;
}
```
３６．コンソールに出力される結果

```
>
```
---
### 条件判断 比較演算子 ==
```
#include <stdio.h>

int main(void){
  int data ;
  scanf("%d\n",&data);
  if (data == 1) printf("1を入力しました\n");
  return 0;
}
```
３７．次の結果を表示する為の条件は？

```
>
1を入力しました
```
---
### 条件判断 比較演算子 !=
```
#include <stdio.h>

int main(void){
  int data ;
  scanf("%d\n",&data);
  if (data != 1) printf("1以外を入力しました\n");
  return 0;
}
```
３８．次の結果を表示する為の条件は？

```
>
1以外を入力しました
```
---
### 関係演算子
関係演算子の説明を完成させなさい。

記号　:　真になる　：　偽になる <br>
- == : 左辺と右辺が同値の場合　：左辺と右辺の値が違う場合
```
３９．!=
４０．<
４１．>
４２．<=
４３．>=
```
---
### 論理演算子
論理演算子の説明を完成させなさい。

- 記号：意味：真になる：偽になる

- && :かつ（ＡＮＤ）：右と左の条件が両方真の場合：右と左のどちらかでも異なる場合
- ４４．||：または（OR）：
- ４５．!：否定（ＮＯＴ）：

---
### if else
４６．次のプログラムを完成させなさい。
```
#include <stdio.h>

int main(void){
  int data ;
  if (data   1) {
    printf("1を入力しました\n");
  } else {
    printf("1を入力しませんでした\n");
  }
  return 0;
}
```
---
### elseif
４７．次のプログラムを完成させなさい。
```
#include <stdio.h>

int main(void){
  int old ;
  scanf("%d",&old);
  if (old <= 3) {
    printf("幼児\n");
  } else   (old <= 12){
    printf("子供\n");
  } else {
    printf("大人\n");
  }
  return 0;
}
```
---
### switch
４８．次のプログラムを完成させなさい。
```
#include <stdio.h>

int main(void){
  int input ;
  printf("1,2,3,4の何れかを入力しなさい。\n");
  scanf("%d",&input);
  switch(input){
    case 1:
      printf("1が入力されました。\n");
      break;
    case 2:
      printf("2が入力されました。\n");
      break;
    case 3:
      printf("3が入力されました。\n");
      break;
    case 4:
      printf("4が入力されました。\n");
      break;
    default:
      printf("1,2,3,4,以外が入力されました\n");
      break;
  }
  return 0;
}
```
---
### for　繰り返し
４９．出力される表示を書きなさい。
```
#include <stdio.h>

int main(void){
  int i ;
  for (i = 1; i <=3; i++){
    printf（"1回目\n");
  }
  return 0;
}
```
---
### for カウントアップ
50．49の問題を以下の結果が表示されるように改良しなさい。
```
1回目
2回目
3回目
```
---
### for 2次元表現
51.出力される結果を書きなさい。
```
#include <stdio.h>

int main(void){
  int i x;
  for (x = 1; x <=3; x++){
    for (i = 1; i <=3; i++){
      printf（"%d%d",i,x);
    }
    printf("\n");    
  }
  return 0;
}
```
---
### while
52.出力される結果を書きなさい。
```
#include <stdio.h>

int main(void){
  int i = 0,w = 2;

  while (w < 255){
    w *= 2;
    i++;
  }
  printf("%d回目にW=%dになります。",i,w);
}
```
---
### do while
53.出力される結果を書きなさい。
```
#include <stdio.h>

int main(void){
  int i = 0,w = 2;

  do {
    w *= 2;
    i++;
  } while (w < 2)
  printf("%d回目にW=%dになります。",i,w);
}
```
---
### 自作関数
54.出力される結果を書きなさい。
```
#include <stdio.h>

int sum(int);

int main(void){
  int max;
  printf("%dまでの合計は%dになります。",max,sum(max));
}

int sum(int max_value){
  int i = 0;
  while(i <= max_value){
    i = i + 1
  }
  return i;
}
```
---
### 複数の引数を持つ自作関数
55.出力される結果を書きなさい。
```
#include <stdio.h>

int sum(int,int);

int main(void){
  int min,max;
  printf("%dから%dまでの合計は%dになります。",min,max,sum(min,max));
}

int sum(int start,int max_value){
  int i = start;
  while(i <= max_value){
    i = i + 1
  }
  return i;
}
```
---
### ローカル変数
56.出力される結果を書きなさい。
```
#include <stdio.h>

int count(void);
int main(void){

  count();
  count();
  count();

  return 0;
}

int count(void){
  int count;
  count++;
  printf("%d\n",count);
  return count;
}
```
---
### グローバル変数
57.出力される結果を書きなさい。
```
#include <stdio.h>
int count = 0;
int count(void);

int main(void){

  count();
  count();
  count();

  return 0;
}

int count(void){
  count++;
  printf("%d\n",count);
  return count;
}
```
---
### 静的なローカル変数
58.出力される結果を書きなさい。
```
#include <stdio.h>
int count(void);

int main(void){

  count();
  count();
  count();

  return 0;
}

int count(void){
  static int count = 0;
  count++;
  printf("%d\n",count);
  return count;
}
```
---
### 配列
59.出力される結果を書きなさい。
```
#include <stdio.h>

int main(void){
  int array[4];

  array[0] =  100;
  array[1] =  10;
  array[2] = array[0] +  array[1];
  array[3] = array[2];
  printf("%d",array[3]++);

  return 0;
}

```
---
### 配列 初期値の代入
60.出力される結果を書きなさい。
```
#include <stdio.h>

int main(void){
  int array[4] = {1,2} ;

  printf("%d\n",array[0]);
  printf("%d\n",array[1]);
  printf("%d\n",array[2]);
  printf("%d\n",array[3]);

  return 0;
}

```
---
### 配列 初期値の代入
60.出力される結果を書きなさい。
```
#include <stdio.h>

int main(void){
  int array[4] = {1,2} ;

  printf("%d\n",array[0]);
  printf("%d\n",array[1]);
  printf("%d\n",array[2]);
  printf("%d\n",array[3]);

  return 0;
}

```
---
### 配列　要素数の省略
61.出力される結果を書きなさい。
```
#include <stdio.h>

int main(void){
  int array[] = {1,2,3,4} ;
  int i;

  for (i = 0; i <=3; i++){
  printf("array[%d]=%d\n",i,array[i]);    
  }
  return 0;
}
```
---
