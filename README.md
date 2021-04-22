# Cloud-E-TeamStudy

## 📣 소개 
- 클라우드 컴퓨팅 E 조 팀 협업을 위한 주기적인 학습을 위한 저장소 입니다. 

## 🙋 팀원소개 

**윤우상(Ywoosang)**

- 매주 팀원들이 학습할 유투브 동영상을 선별 및 과제를 만듭니다.
- 프론트엔드, 백엔드개발 및 컨테이너 기반 배포환경을 구축합니다.
- AWS 서비스들에 대해 학습하고 배운지식을 팀원들과 공유합니다.


**김국진(neverparadise)**







## 📝 스터디 방식
- 기본적인 자바스크립트 언어 학습이 완료되었다는 가정 하에 진행합니다.  
- 매 주차별 개인 할당 과제가 나가며 시청할 유투브 링크가 있습니다.

## 📑 문서구조 
개인폴더 내부에는 개인별 학습내용을 커밋합니다. 
```sh  
├─Week
│  ├─ 개인폴더1
│  ├─ 개인폴더2
│  ├─ 개인폴더3
│  ├─학습 리뷰 (README.md) 
```


## Week 1

### 학습 과제

#### 학습목표
박스 예제를 통해 통해 DOM 제어와 class 토글에 대해 이해합니다.  
#### 구현 조건
아래 정의된 html 과 css 를 기본적으로 이용하되, 필요시 태그에 별도 class, id 등을 부여할 수 있습니다.  
1. 박스 숨기기를 클릭하면 박스가 사라집니다.  
2. 박스 나타내기를 클릭하면 박스가 나타납니다.  
3. 문구바꾸기를 클릭하면 클릭한 시점 사용자 입력란(input) 에 입력한 값으로 박스 안 텍스트가 바뀝니다.  
4. 클래스 토글을 이용해 박스색을 변경합니다. 색 바꾸기를 클릭할때마다 파란색, 빨간색, 검은색 순으로 박스 색이 바꿉니다.   
```
ex) black(기본) -> blue -> red -> black -> blue -> red ... 
```


```html
<!-- box.html -->
<input type="text"> 
<div class="box">박스입니다.</div>
<button type="button">박스 숨기기</button>
<button type="button">박스 나타내기</button>
<button type="button">문구 바꾸기</button>
<button type="button">색 바꾸기</button>
```

```css
/*   box.css  */
.box{
    width: 5rem;
    height: 5rem;
    color: white;
    background-color:black; 
}
.blue{
    background-color: dodgerblue;
}
.red{
    background-color:crimson;
}
```
 

```js
// box.js
/*
여기에 코드를 작성합니다.
*/
```

### 학습 동영상 :  
- DOM 학습  
https://www.youtube.com/watch?v=wiozYyXQEVk

- 바닐라 자바스크립트로 TODO 리스트 구현하기  
https://www.youtube.com/watch?v=Ttf3CEsEwMQ


## Week 2

- 이메일 형식을 준수해야 하며 
- 닉네임은 3자 이상 
```html
<!-- form.html -->
<form name="f" ...>
    이메일: <input type="text" name="email">
    닉네임: <input type="text" name="nickname">
    비밀번호: <input type="password" name="password">
    <button type="submit">로그인</button>
</form>
```

```js
// form.js
/*
여기에 코드를 작성합니다.
*/
```


### 학습 동영상 :  

- 자바스크립트를 이용한 간단한 폼 검증 방법  
https://www.youtube.com/watch?v=In0nB0ABaUk&t=289s  

 


