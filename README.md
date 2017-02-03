JavaFX 8 GUI 프로그램 만들기
====

## Perface
본 가이드는 JavaFX 8 라이브러리를 이용해서 윈도우/웹/임베디드 장비에서 GUI 프로그램을     
작성하기 위한 기본적인 사항을 간단하고 빠르게 설명하는 문서입니다.

`JavaFX`는 Java언어의 차세대 그래픽사용자인터페이스 프레임워크입니다.(GUI)    
JavaFX는 풍부하고, 강력하며, 유연한 프레임워크이며, 또한 아주 쉽게 사용할 수 있는      
구조로 되어있습니다. 만약 이전에 AWT/Swing 프레임워크를 이용해서 프로그램을     
개발해본적이 있는 사용자라면 `JavaFX`를 이용해서 프로그램을 개발하는 것이 얼마나      
쉬운것 인지를 느끼게 되실 것입니다.    

본 가이드에서는 `JavaFX 8`버전을 기준으로 모두 코드가 작성됩니다.  간단한 역사에    
대해서는 JavaFX 2.0까지는 `JavaFX Script`라는 스크립팅언어로 작성했습니다.       
하지만, JDK 7u4 부터는 순수한 `Java`언어로 작성할 수 있도록 변경되었으며,       
현재는 `JDK`과 버전번호를 맞추기 위해서 `JDK 8 / JavaFX 8` 버전으로 되었습니다.     

또한, `JDK/JRE`에 `JavaFX`가 이미 포함(Bundle)되어서 배포되므로, 앞으로의     
자바프로그램에서 GUI부분은 `JavaFX`로 처리하게 됨을 의미하며,  별도의 Frameworks나      
유틸리티를 설치하지 않아도, 작동하게 되는 장점이 있습니다.     

본 가이드는 **Java Programmer**들이 보기 편하도록 작성되었으며, 기타 언어를      
사용하는 사용자에게는 다른 가이드를 참고하시기 바랍니다.       
또한 자바언어에 대한 기본적인 지식만을 요구합니다. 초보자나 전문가 모두가 읽을 수       
있도록 구성하였습니다.  CSS(Cascading Style Sheet) / FXML을 사용하지 않습니다.      
단지, `Java Code`로만 작성하도록 하겠습니다.   `CSS/FXML`은 **JavaFX8**의       
강력한 기능이지만, 기본적인 사항을 학습하신다면 간단히 적용해서 사용하실 수 있습니다.        


총 9개의 섹션을 통해서 `JavaFX`에 대해서 설명하며, 간략한 구성은 다음과 같습니다. 

```
Subject | Description
:---|:---
1. JavaFX Fundamentals | JavaFX의 기초
2. Introducing Events and Controls | 이벤트 및 컨트롤
3. Exploring JavaFX Controls, Part One | 컨트롤 파트1
4. Exploring JavaFX Controls, Part Two | 컨트롤 파트2
5. Work with Images, Fonts, and Layouts | 이미지, 폰트, 레이아웃
6. Effects and Transforms  | 이펙트와 변형
7. Animation   | 애니메이션
8. Explore Menus  | 메뉴
9. Charts, WebView, and Canvass | 차트, 웹뷰, 캔바스
```

본 가이드를 마치신 후에는 좀더 전문적인 주제를 정해서 설명하도록       
하겠습니다.    


  
![](https://github.com/xenostream/GoWebProgramming/blob/master/images/My.jpg)

[XenoStream](http://www.xenostream.com) 
######201@ powered by [PilJin.Kwon](mailto://piljin.kwon@gmail.com)

