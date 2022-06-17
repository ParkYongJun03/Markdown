# Markdown
마크다운 뿌수기

# 제목1 - H1
## 제목2 - H2
  H2까지만 밑에 줄이 생긴다
### 제목3 - H3
#### 제목4 - H4
##### 제목5 - H5
###### 제목6 - H6

제목 텍스트 1 (##이랑 비슷한듯)
---

> 첫번째 블록
>> 두번째 블록
>>> 세번째 블록

> 첫번째 블록
>    1. 두번째 블록
>        + 세번째 블록

1. 첫번째 아이템  
    1. 하위 아이템
      4. 하위 아이템2
1. 두번째 아이템
1. 세번째 아이템

+ 첫번째 아이템
  - 1-1 아이템
  - 1-2 아이템
  - 1-3 아이템
+ 두번째 아이템
  * 2-1 아이템
  * 2-2 아이템
+ 세번째 아이템
  + 3-1 아이템
      + 3-1-1 아이템
  + 3-2 아이템


링크사용 [Title](link)

---
[Google](https://www.google.com, "Go Google")
[Email](PSJ@gmail.com, "Send Message")

자동링크사용
---
<https://www.google.com>
<PSJ@gmail.com>


// '*','_','~'기호를 이용하며, 서로 중첩해 사용할 수 있다.

*single asterisks 이텔릭체*

_single underscores 이텔릭체_

**double asterisks 볼드체**

__double underscores 볼드체__

***tripple underscores 볼드+이텔릭체***

___tripple underscores 볼드+이텔릭체___

~~cancelline 취소선~~

**~~bold cancelline 볼드+취소선~~**

<u>underline - 밑줄</u>

 `<img>` 테그를 사용해서 본문에 이미지를 삽입할 수 있습니다.
 
 ```html
  <a href="https://www.psjco.com/" target="_blank">Play The Keyboard</a>
  ```
  

  ```css
  .list > li {
  position: absolute;
  top: 40px;
  }
  ```
  

  ```java
  public class BootSpringBootApplication {
      public static void main(String[] args) {
          System.out.println("Hello, world");
      }
  }
  ```
  
  ```c
  #include <stdio.h>
int sum(int, int);
void main() {
	printf("합산하기\n");
	int total = sum(100, 30);
	printf("%d", total);
}
int sum(int a, int b) {
	return a + b;
}
```
이미지
---
![image](https://user-images.githubusercontent.com/83456300/174203988-2e14ecb2-0829-4fd0-8d50-4de022c96762.png) 
<img src="https://user-images.githubusercontent.com/83456300/174203988-2e14ecb2-0829-4fd0-8d50-4de022c96762.png" width="400px"></img>

<img src="https://user-images.githubusercontent.com/83456300/174203988-2e14ecb2-0829-4fd0-8d50-4de022c96762.png" width="100px"></img>
