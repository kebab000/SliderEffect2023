# ✍️ JAVASCRIPT : SLIDE EFFECT

![slide01](https://raw.githubusercontent.com/kebab000/SliderEffect2023/main/img/sliderEffect.png)

<br><br>

> View Site : https://kebab000.github.io/web2023/javascript/slider/sliderEffect01.html

<br><br>

## 소개

자바스크립트를 활용하여 슬라이드 이펙트를 구현한 웹 페이지를 소개합니다. 이 슬라이드 이펙트는 사용자가 웹 페이지를 스크롤하거나 버튼을 클릭할 때 발동됩니다. 슬라이드가 활성화되면 이전 내용은 서서히 사라지고, 새로운 내용이 부드럽게 나타납니다. 또한, 자동으로 이미지가 전환되도록 자동 재생 기능을 추가하여 사용자의 상호 작용 없이도 멋진 이미지 슬라이드 쇼를 즐길 수 있습니다.
이 이펙트를 통해 javascript의 메서드 (setInterval, setTimeOut, 반복문)과 GSAP, jQuery를 학습하였습니다.
<br><br>

## 사용 스택과 메서드
* HTML: HTML 언어를 사용하여 웹 페이지의 구조와 콘텐츠를 정의합니다.
* CSS: CSS(Cascading Style Sheets)를 사용하여 웹 페이지의 스타일을 지정합니다.
* JavaScript:
  * setInterval() : setInterval 함수를 사용하여 일정한 간격으로 슬라이드를 변경하는 기능을 구현합니다.
  * setTimeout() : setTimeout 함수는 일정 시간 후에 콜백 함수를 실행하는 메서드입니다.
  * document.querySelector(selector) : 선택자를 사용하여 각각의 DOM 요소를 가져옵니다.
  * querySelectorAll(selector) : 선택자(selector)에 해당하는 모든 요소들을 가져옵니다.
  * classList.add() : DOM 요소의 클래스 리스트에 새로운 클래스를 추가합니다.
  * classList.remove() : DOM 요소의 클래스 리스트에서 지정된 클래스를 제거합니다.
  * forEach(callback): 배열의 각 요소에 대해 주어진 콜백 함수를 실행합니다. 
* GSAP(GreenSock Animation Platform): GSAP 라이브러리를 사용하여 애니메이션 효과를 부여합니다. gsap.to 메서드를 사용하여 슬라이더의 투명도를 변경하여 이미지를 부드럽게 전환합니다.
<br><br>

## 구현 내역
* 페이드 아웃 슬라이드
* 좌,우 / 상,하 슬라이드 (연속적)
* 닷버튼 슬라이드
* 썸네일 슬라이드