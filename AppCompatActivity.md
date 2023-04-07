## AppCompatActivity 

<br>

>AppCompatActivity란?

우리는 일반적으로 액티비티를 선언할 때, Activity를 상속받아서 작성하곤 합니다. 그런데 사실, Activity는 종류가 여러가지 존재합니다. 

아래 그림과 같은 상속 구조를 가지며, 최종적으로 AppCompatActivity까지 자식을 가지고 있습니다. 

Compat이라는 이름부터 호환성을 의미하는 compatibility의 줄임말임을 유추해볼 수 있는데요.

어떤 호환성을 의미하는 것이고 어떻게 지원해준다는 걸까요?

![image](https://user-images.githubusercontent.com/84930748/230456798-1f72fb54-12db-4816-a10a-fa9dd8ce711f.png)


Android 3.0(API Level 11)부터는 기본적으로 Activity들은 Appbar로 모두 ActionBar를 가지고 있습니다. 

이런 특정 버전부터 지원되는 ActionBar를 해당 버전 이하의 버전에도 적용할 수 있도록 지원해주는 Activity가 바로 AppCompatActivity입니다

>appcompat 라이브러리
 - androidx 라이브러리에서 가장 많이 사용하는 라이브러리
 - 안드로이드 앱의 화면을 구성하는 액티비티 생성
 - API 레벨의 호환성 문제 해결
