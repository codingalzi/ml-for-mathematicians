머신러닝의 주요 개념과 다양한 모델의 작동법을 파이썬 프로그래밍 지식이 (거의) 없는 비전공자들에게 소개합니다.
소개되는 내용은 [&lt;핸즈온 머신러닝(2판)&gt;](https://m.hanbit.co.kr/store/books/book_view.html?p_code=B7033438574)을
기본으로 참고합니다.
머신러닝 프로그래밍을 직접 하지 않는 대신 [Orange3](https://orangedatamining.com/) 앱을 이용하여 머신러닝의 주요 개념과 모델의 작동법을 전달합니다.
더불어 파이썬 프로그래밍 기초 학습 자료도 함께 제공합니다.

### 감사의 글

소중한 소스코드를 공개한 
[오렐리앙 제롱(Aur&eacute;lien G&eacute;ron)](https://github.com/ageron/handson-ml2), 
그리고 강의자료를 지원한 한빛아카데미에게 진심어린 감사를 전합니다.

### 강의소개

* 슬라이드: [[html]](./slides/mlmath00-intro.slides.html), 
    [[pdf]](./slides/mlmath00-intro-slides.pdf)

### 목차

#### 머신러닝

1. 한 눈에 보는 머신러닝
    * 슬라이드: [[html]](./slides/mlmath01.slides.html), 
    [[pdf]](./slides/mlmath01-slides.pdf)
1. 머신러닝 프로젝트 처음부터 끝까지
    * 슬라이드: [[html]](./slides/mlmath02.slides.html), 
    [[pdf]](./slides/mlmath02-slides.pdf)
    * Orange3 실습: <a href="https://raw.githubusercontent.com/codingalzi/handson-ml2/master/orange3/housing/housing.zip" download>[workflow]</a>
1. 분류
    * 슬라이드: [[html]](./slides/mlmath03.slides.html), 
    [[pdf]](./slides/mlmath03-slides.pdf)
    * Orange3 실습: <a href="https://raw.githubusercontent.com/codingalzi/handson-ml2/master/orange3/iris/iris.zip" download>[workflow]</a>
1. 로지스틱 회귀
    * 슬라이드: [[html]](./slides/mlmath04.slides.html), 
    [[pdf]](./slides/mlmath04-slides.pdf)
1. 경사하강법
    * 슬라이드: [[html]](./slides/mlmath05.slides.html), 
    [[pdf]](./slides/mlmath05-slides.pdf)
    * 주피터 노트북: [[html]](./notebooks/mlmath05.html), 
    [[colab]](https://colab.research.google.com/github/codingalzi/mle/blob/master/notebooks/mlmath05.ipynb)
1. ...

#### 파이썬 기초

1. 파이썬 기본 자료형 1부 &nbsp;
    [[html]](./notebooks/python01.html),
    [[colab]](https://colab.research.google.com/github/codingalzi/mle/blob/master/notebooks/python01.ipynb)
    - 파이썬 언어 소개, 변수, 연산, 스칼라 자료형 1편(정수, 부동소수점, 부울 값, None)
1. 파이썬 기본 자료형 2부 &nbsp;
    [[html]](./notebooks/python02.html),
    [[colab]](https://colab.research.google.com/github/codingalzi/mle/blob/master/notebooks/python02.ipynb)
    - 스칼라 자료형 2편(문자열)
1. 제어문 &nbsp;
    [[html]](./notebooks/python03.html),
    [[colab]](https://colab.research.google.com/github/codingalzi/mle/blob/master/notebooks/python03.ipynb)
    - 제어문(if 조건문, for 반복문, while 반복문), 주요 예약어(pass, continue, break)
1. 함수 &nbsp;
    [[html]](./notebooks/python04.html),
    [[colab]](https://colab.research.google.com/github/codingalzi/mle/blob/master/notebooks/python04.ipynb)
    - 함수 정의, 매개 변수와 인자, 반환값, 함수 호출, 지역/전역 변수
1. 순차 자료형 1부 &nbsp;
    [[html]](./notebooks/python05.html),
    [[colab]](https://colab.research.google.com/github/codingalzi/mle/blob/master/notebooks/python05.ipynb)
    - 리스트
1. 순차 자료형 2부 &nbsp;
    [[html]](./notebooks/python06.html),
    [[colab]](https://colab.research.google.com/github/codingalzi/mle/blob/master/notebooks/python06.ipynb)
    - 튜플(순서쌍)
1. 순차 자료형 3부 &nbsp;
    [[html]](./notebooks/python07.html),
    [[colab]](https://colab.research.google.com/github/codingalzi/mle/blob/master/notebooks/python07.ipynb)
    - 사전
1. ...

#### 파이썬 기초 프로그래밍 실습

1. 실습 1 &nbsp;
    [[html]](./practices/practice01.html),
    [[colab]](https://colab.research.google.com/github/codingalzi/mle/blob/master/practices/practice01.ipynb)
1. 실습 2 &nbsp;
    [[html]](./practices/practice02.html),
    [[colab]](https://colab.research.google.com/github/codingalzi/mle/blob/master/practices/practice02.ipynb)
1. 실습 3 &nbsp;
    [[html]](./practices/practice03.html),
    [[colab]](https://colab.research.google.com/github/codingalzi/mle/blob/master/practices/practice03.ipynb)
1. ...

**링크 활용법**

* html 버전: 읽기 전용 주피터 노트북 또는 슬라이드
* pdf: PC 용 pdf 슬라이드
* colab: 구글 코랩에서 실행 가능한 주피터 노트북
* workflow: Orange3에서 사용가능한 워크플로오와 데이터 (다운로드 전용)

### 프로그래밍 환경

#### Orange3
다운받은 워크플로우와 데이터를 Orange3 앱으로 불러오면 슬라이드에 포함된 내용을 워크플로울 따라가며 확인할 수 있습니다.
Orange3 앱의 사용법은 아래 동영상을 참조하세요.

* [생활코딩: Orange3](https://www.opentutorials.org/course/4549)

#### 파이썬
파이썬 프로그래밍은 아무런 설치과정 없이 바로 실습할 수 있는 온라인 프로그래밍 환경인 구글 코랩 사용을 추천합니다.
구글 코랩 사용법은 아래 동영상을 참조하세요.

* [구글 코랩 사용법](https://www.youtube.com/watch?v=Jb_n90gHdP0)
* [주피터 노트북 사용법](https://www.youtube.com/watch?v=4_-IIfbdR5M&list=PLRYL8FHwJMhD_Wi22JLm2VURrjt_iVX7X&index=2)

### 참고

머신러닝 내용을 파이썬으로 직접 실행하고자 한다면 동일한 내용을 전공자를 위해 다루는 아래 강좌를 참조하세요.

* [핸즈온 머신러닝 강좌](https://codingalzi.github.io/handson-ml2/)

파이썬 기초 강좌는 아래 사이트를 업데이트 하는 형식으로 제공됩니다.

* [파이썬 데이터 과학 입문](https://formal.hknu.ac.kr/Gongsu-DataSci/)
