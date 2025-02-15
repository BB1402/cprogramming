# cprogramming

C언어 프로그래밍 


<hr/>


# 코드 기본 구성
+ 전처리기
+ main

```c
#include <stdio.h>

int main()
{
   printf("C programming");
   return 0;
}
```


<hr/>

# printf
> stdio.h에서 제공해주는 C언어의 대표적인 문장 출력용 기능(함수)입니다.<br>
> 일반적으로는 printf("작성하고 싶은 문장");을 작성해 사용합니다.

예시)
```c
int main()
{
   printf("Good day to Study!");
   return 0;
}
```

<hr/>

+서식 지정자
|지정자 명칭|설명|
|-----|-----|
|%d|정수에 대한 지정자|
|%f|실수에 대한 지정자|
|%c|문자에 대한 지정자|

+이스케이프 시퀀스
|\영단어 소문자|설명|
|-----|-----|
|\n|Enter 키|
|\t|Tab 키|
|\"|"에 대한 표현|
|\'|'에 대한 표현|

+데이터 표현법(리터럴(literal))
//리터럴은 c언어에서 데이터를 표기하는 방법이며 , 값을 그대로 입력한 것을 의미합니다.
|종류|작성 방법|
|-----|-----|
|정수|그대로 기입(예: 10)|
|실수|마지막에 f(예: 10.0f)|
|문자|작은따옴표 안에 작성(예: 'a')|
|문장|큰따옴표 안에 작성(예: "apple")|
