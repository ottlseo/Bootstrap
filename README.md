# Bootstrap
### 20.06.14   
웹 개발 부트스트랩 공부 시작

### 20.09.26 ~
성향테스트 페이지 수정중 다시 공부..   
https://www.youtube.com/watch?v=HKtD3d9C69U&list=PLMWJA4FwmYz0_Lkeafmikle2Mpzt4lqIl

- - -
### Bootstrap 이란?   
: 반응형 웹사이트 프레임워크.   
Ex) 사이즈를 줄이면 화면 배치도 반응형으로 줄어듦   
기본적인 HTML에는 없는 기능을, 부트스트랩에서 제공함, 약간의 코드를 첨부함으로써 기능을 구현할 수 있음. = 오픈소스   
참고. https://getbootstrap.kr/docs/4.5/examples/    
"부트스트랩 > 예제"에 예제 코드가 많아서 직접 실행해 볼 수 있다.   

### 반응형 디자인 웹페이지에 적용하기 *(== Scaffolding)*

### 1. CSS 이용

* Grid / table   
화면을 12등분하여 Grid Layout을 적용   
```
<div class="row">
  <div class="col-xs-6-col-sm-4">.col-xs-6 .col-sm-4</div>
  <div class="col-xs-6-col-sm-4">.col-xs-6 .col-sm-4</div>
  <div class="clearfix visible-xs-block"></div>
  <div class="col-xs-6-col-sm-4">.col-xs-6 .col-sm-4</div>
</div>
```
* 입력 form 생성 --pass
* 버튼 - 크기/모양 다양하게 바꾸기
 ```
 <a class="btn btn-default" href="#" role="button">Link</a>
 <button class="btn btn-default" type="submit">Button</button>
 <input class="btn btn-default" type="button" value="Input">
 <input class="btn btn-default" type="submit" value="submit">
 ```
 * 반응형 이미지 삽입하기
 ```<img src="..." class="img-responsive" alt="Responsive image">```
     
 
 ### 2. 컴포넌트 이용
 * 드롭다운
 * Navbar (Toggle navigation)
