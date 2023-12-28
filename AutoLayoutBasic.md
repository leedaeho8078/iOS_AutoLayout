# Round 1 - Auto Layout Basic

참고 자료 
* [Apple Developers Documents](https://developer.apple.com/library/archive/documentation/UserExperience/Conceptual/AutolayoutPG/index.html#//apple_ref/doc/uid/TP40010853-CH7-SW1)
  * Auto Layout Guide
  * Human Interface Guidelines for iOS
* WWDC Sessions

1. 오토레이아웃(Auto Layout)이란?
> 오토 레이아웃(Auto Layout)이란,
> 제약 조건(Constraints)에 따라  뷰 계층 구조에 있는 모든 뷰의 크기와 위치를 동적으로 지정하는 것이다

2. 제약 이란(Constraint)?

   <img width="500" alt="image" src="https://github.com/leedaeho8078/iOS_AutoLayout/assets/83402908/4f07611a-d04d-490e-90d0-423ecc291dc0"> 
  * 제약은 하나의 수식으로 표현 가능하다.
  * 파란색 뷰와 빨간색 뷰가 8포인트 만큼 떨어져 있다.
  * RedView.Leading -> 목적지(왼쪽에 나와있는건 목적지) 파란색뷰의.Trailing + 8.0만큼 떨어져 있다. 



3. Auto Layout - Attributes란?


   <img width="500" alt="image" src="https://github.com/leedaeho8078/iOS_AutoLayout/assets/83402908/15b3fdfd-1754-480f-807c-032f54b6a935">
 * 속성의 종류    

 `top`: 뷰의 탑
 
 `Width`: 뷰의 넓이

 `Height`: 뷰의 높이

 `Left or Leading` : Leading 글이 시작하는 방향(미국적 생각), Leading 사용을 권장

 `Center Y` : 뷰의 Y축
 
 `Center X` : 뷰의 x축

 `Right or Trailing` : 뷰의 오른쪽

 `Bottom`: 뷰의 아럐쪽

 `Baseline` : 글자의 밑바닥이 끝나는 지점(속성은 아니다)

4. Equations
  * 제약을 방정식으로 나타낸다.
  * 두 가지 속성(사이즈 : 높이 랑 넓이, 위치: leading, Left and Top)
  * `=` 할당은 아니다. 같은식이다 -> 라고 알려주는 것

5. 
