# -Beakjoon-
### [백준/Baekjoon/C언어] 11816번 : 8진수, 10진수, 16진수


https://www.acmicpc.net/problem/11816


#### 문제
정수 X가 주어진다. 정수 X는 항상 8진수, 10진수, 16진수 중에 하나이다.
8진수인 경우에는 수의 앞에 0이 주어지고, 16진수인 경우에는 0x가 주어진다.
X를 10진수로 바꿔서 출력하는 프로그램을 작성하시오.


#### 입력
첫째 줄에 X가 주어진다. X는 10진수로 바꿨을 때, 1,000,000보다 작거나 같은 자연수이다. 16진수인 경우 알파벳은 소문자로만 이루어져 있다.



#### 코드

'''c

#include <stdio.h>
int main()
{
    int a;
    scanf("%i", &a);
    printf("%d", a);
    return 0;
}

'''
->아니 이거 왜 코드 안올려지니?


#### 결과
![image](https://user-images.githubusercontent.com/96537605/157071361-8d7674de-9109-4617-909d-df731cdb0dcb.png)



#### 풀이
 **'%i'** 로 scanf를 받게 되면, **10진수, 8진수, 16진수 상관 없이 모두 입력받을 수 있다.** 따라서 '%i'로 입력받은 뒤, %d로 10진수 정수를 출력했다.

#### 소감?
학교에서 %i 배웠더니 바로 풀려서 신기하다
*C %[^\n] 이것도 실습해보고 싶당
