# 스케줄

--- 
# 제목1

## 제목2

### 제목3

#### 제목4

##### 제목5

###### 제목6

### BlockQuote
> This is a first blockquote
>
> > This is a second blockquot
>
> This is a first blockquote    

### 목록 (LIST)
#### 1) 순서가 있는 목록
1. 목록1  
     1. 목록 1-1   
     2. 목록 1-2
2. 목록2
     1. 목록2_1
     2. 목록2_2
3. 목록3
4. 목록4

#### 2) 순서가 없는 목록
- 목록1
    - 목록1_1
    - 목록1_2
- 목록2
    - 목록2_1
    - 목록2_2
- 목록3

### 표만들기

- |(vetical val) : 테이블 표현
- : 정렬
- (---)헤더와 셀 구분

|이름|주소|전화번호|
|:--:|:--:|:--:|
|홍길동|서울시|02-1234-23456|
|여진구|경기도|031-2523-5233|

### 코드(code)
#### 1) 인라인 코드(inline code)
- 백틱(\`)으로 강조할 내용을 감싼다.
repository 에서 프로젝트의 설명을 부여해줄때
`REDME.md`을 사용한다.

#### 2) 블럭코드 (block code)
- 백틱(\`) 3개로 html, css, java등 코드를 작성할때 사용한다.

    ```java
    public static void main (String[] args) {
        System.out.println("Hello Java");
    }
    ```

### 글자 강조
**굵은 글씨**  
*이텔릭*  
_이텔릭_  
~~취소선~~  
<u>밑줄</u>  

### 링크 (Links)
[naver](https://www.naver.com/)  
[link](a.txt)  

다음 홈페이지 : <https://www.daum.net/>

### 이미지(images)
![갱얼쥐](https://cdn.imweb.me/upload/S201910012ff964777e0e3/62f9a36ea3cea.jpg)

![갱얼쥐2](https://img.khan.co.kr/news/2019/11/29/l_2019112901003607500286631.jpg)

![갱얼쥐3](images/pasted_image_0.png)
[![갱얼쥐4](images/img.jpg)](https://www.naver.com)

### 원시 HTML (Raw HTML>)
<img src ='images/pasted_image_0.png' alt='dog'>


###무료 템플릿 사이트  
구글 검색창에 bootstrap template 검색
https://startbootstrap.com/themes


git hub에 실제로 올릴 파일이 아닌 경우
.gitignore에 파일 이름.파일형식 작성 해두면됨