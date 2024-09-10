# 마크다운
## 마크다운의 정의
-  마크다운이란 텍스트 기반의 마크업언어
-  2004년 존그루버에 의해 만들어졌다
## 마크다운의 장점
-  **간결**
-  **별도의 도구**없이 작성가능
-  **다양한 형태**로 변환이 가능
-  *텍스트(Text)*로 저장되기 때문에 **용량이 적어** 보관이 용이
-  텍스트파일이기 때문에 *버전관리시스템*을 이용하여 **변경이력을 관리**가능
-  지원하는 프로그램과 플랫폼이 다양
## 마크다운의 단점
- 표준X
- 표준이 없기 때문에 도구에 따라서 변환방식이나 생성물다름.
- 모든 HTML 마크업을 대신X.
## 사용법
헤더Headers

큰제목:문서 제목
==========
작은제목:문서 부제목
------------
#글머리  
##최  
###대  
####6  
#####개까지  
######가능  
> 이것은 블럭 인용 문자
> > 이것은 두번째
> > > 이것은 세번째
1. 첫번째 말
2. 두번째 말
3. 세번째 말
-순서 상관없음  
    +이것도  
        *이것도  
여기서도 들여쓰기중요:  
    이런식으로
```public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("How to write code");
  }
}
```
***
* * *
*****
- - -
---------------------------------------
모두 수직선 만들기  
링크
[link keyword][id]

[id]: URL "Optional Title here"

// code
Link: [Google][googlelink]

[googlelink]: https://google.com "Go google"
강조들  
*single asterisks*  
_single underscores_  
**double asterisks** 
__double underscores__  
~~cancelline~~  
줄바꿈은 마지막 뛰어쓰기 2번  
`이것은 백틱 1번`  
``이것은 백틱 두번``  
```이것은  백틱  세번```  
