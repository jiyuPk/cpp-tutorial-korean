# Chapter 1 C++의 기초


이번 챕터에서는 C++의 기초 키워드, 개념, 문법에 대해서 다룹니다.
우선 C++를 배우기 위해선 

## 1.1 C++
C++는 컴파일 언어 입니다. 컴파일러가 소스 파일에서 목적 파일을 만들고 링커가 목적 파일들을 병합하는 과정을 거쳐야만 실행가능한 프로그램을 만들 수 있습니다.

## 1.2 Hello, World!
```cpp
// Hello, World!를 출력하는 프로그램.
#include <iostream>

int main()
{
  std::cout << "Hello, World!" std::endl;
}
```
이 소스코드를 실행하면 Hello, World!를 출력합니다.
첫 번째 줄의 이중슬래시 //은 주석을 의미합니다. 주석은 사람이 읽는 메세지로 컴파일러는 주석을 무시합니다.
```cpp
/* 주석은 이렇게도
사용할 수 있습니다
*/
```
