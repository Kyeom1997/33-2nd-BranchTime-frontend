# 프로젝트 소개

![branchTime](https://user-images.githubusercontent.com/78855917/174509054-5953ae67-b0ed-4ccc-84fd-3b8d53bcee83.png)

## 클론코딩 사이트
브런치(https://brunch.co.kr/)

## 작업 기간
2022.06.07 ~ 2022. 06. 17

## 팀명
브랜치타임(Branch Time)

## 팀원 소개

| 개발 분야  | 팀원 명                        |
| ---------- | ------------------------------ |
| 프론트엔드 | 김형겸, 박슬기, 박주영, 신윤지 |
| 백엔드     | 김민정, 임한구                 |

## 기술 스택
FrontEnd - HTML/CSS, JavaScript, React.js , React-Router, React-Router-DOM, Styled-components

BackEnd - Django, Postman

## 프론트 엔드 업무 파트
**김형겸 - 메인 페이지, 검색, 소셜 로그인** <br>
박슬기 - Nav, 글 쓰기 페이지 <br>
박주영 - 글 목록 페이지, 글 상세 페이지 <br>
신윤지 - 마이 페이지, Book Animation <br>

## 협업 도구
trello
<img width="1408" alt="image" src="https://user-images.githubusercontent.com/78855917/174509234-78bd5d3d-fa05-4839-bd50-228029d04063.png">
![image](https://user-images.githubusercontent.com/78855917/174509248-7e516817-abb7-4d33-a312-d6e3a59f5ea6.png)


## Coding Convention

1. 들여쓰기는 tab, 혹은 공백 문자 2개를 사용한다.
2. 변수와 함수, className 명명 규칙은 `Camel Case`를 사용한다.
3. 값이 변하지 않는 변수는 const를, 값이 변하는 변수는 let을 사용하여 선언하고 var는 절대로 사용하지 않는다.
4. 함수 선언시 arrow function`(() => {})` 위주로 사용한다.
5. 주석은 코드 설명보다는 수정 사항이나 미구현 사항을 기재할 때 사용하기로 한다.
6. 함수 네이밍 규칙은 해당 함수의 동작을 앞에, 동작이 적용될 태그를 뒤에 위치하게 작명한다. (ex) handleInput)
7. component의 전체를 감싸는 최상단 태그의 className은 컴포넌트 이름으로 명명한다. (ex) product, productlist)
8. 인라인 스타일링은 지양한다.



## 브랜치타임 주요 기능 소개


## 작업한 부분

**Main**
```
- React-slick을 통한 메인 페이지 Carousel 구현 및 리렌더링시마다 랜덤 데이터로 재배열
- useSearchParams를 사용하여 추천 작가리스트 버튼 클릭시마다 query parameter 변경하여 다른 데이터 fetch
```

**footer**

<img width="1717" alt="image" src="https://user-images.githubusercontent.com/78855917/174509607-6b83a237-cc7a-44b3-8f13-cc6bc5221475.png">

**Search**

```
-  백엔드에서 글과 작가 전체 데이터를 fetch해온 뒤, 검색 value 값을 include하는 데이터들만 filter 메소드를 통해 재반환
-  path parameter를 활용하여 글 제목 클릭 시 해당 글의 상세 페이지로, 작가 이름 클릭 시 해당 작가의 상세 페이지로 이동하도록 구현
```


**회원가입/로그인**
```
- OAuth를 통한 Kakao API 소셜 로그인 구현
- .env 파일을 통해 client_id와 redirect_uri 보안 처리
```
---


## 시연영상

**Login**
<br>
![ezgif-2-79bca24642](https://user-images.githubusercontent.com/78855917/174511731-15f028f2-eb42-4211-9886-fc3bb8523165.gif)
<br>

**Main Carousel**
<br>
![ezgif-2-3243a49863](https://user-images.githubusercontent.com/78855917/174511916-6ee15b98-44b7-4b60-b956-a1cd0d949046.gif)
<br>

**Writer List Filtering**
<br>
![ezgif-2-d2c95f9493](https://user-images.githubusercontent.com/78855917/174512029-a7e14693-28f5-4d88-ac51-01e4f1c5efce.gif)
<br>

**Profile Edit**
<br>
![ezgif-2-1b836a84a8](https://user-images.githubusercontent.com/78855917/174512211-fe90bc35-1316-4a72-bdf1-3db6fd2cfac7.gif)
<br>

**Post Detail**
<br>
![ezgif-2-1f456bae0a (1)](https://user-images.githubusercontent.com/78855917/174512486-d3105971-6080-4a5d-81ef-0ca78b771753.gif)
<br>





## 느낀점
