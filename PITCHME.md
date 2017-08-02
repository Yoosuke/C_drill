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
コンソールに出力される結果を次の枠の中に書きなさい。
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
コンソールに出力される結果を次の枠の中に書きなさい。
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
コンソールに出力される結果を次の枠の中に書きなさい。
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
コンソールに出力される結果を次の枠の中に書きなさい。
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
コンソールに出力される結果を次の枠の中に書きなさい。
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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

```
>
```
---
### 10進数,8進数,16進数
```
#include <stdio.h>

int main(void){

  printf("10進数：%d,%d,%d\n",1,10,100);
  printf("8進数：%d,%d,%d\n",01,08,0144);
  printf("16進数：%d,%d,%d\n",0x1,0x10,0x64);

  return 0;
}
```
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。
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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
  printf("5桁：%dです。\n", );
  printf("3桁：%dです。\n", );
  printf("1桁：%dです。\n\n", );
//桁揃えた場合
  printf("5桁：%5dです。\n", );
  printf("3桁：%5dです。\n", );
  printf("1桁：%5dです。\n", );

  return 0;
}
```
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

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
コンソールに出力される結果を次の枠の中に書きなさい。

```
123 456
入力された数値は＝＞
```
---
### 確認問題１　次のプログラムのバグを直しなさい。
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
コンソールに出力される結果

```
最小値と最大値を入力しなさい｡
100 200
計算結果＝＞ 15150
```
---
### 条件判断
