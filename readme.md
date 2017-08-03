# PYCON KOREA YoungCoder Tutorial

2017년 PYCON US에서 진행한 영코더 프로그램의 튜토리얼은 한국어로 번역했습니다.

* 원본 : https://github.com/mechanicalgirl/young-coders-tutorial/blob/master/2017/YoungCoders_2017_beginner.key

### 번역
* 출판일 : 2017.08.07
* 번역 : 이수진, 이은애 

## 영코더 프로그램이란?
영코더 프로그램은 어린이들과 청소년들을 파이콘 컨퍼런스에 초대하여 소프트웨어란 무엇이고, 어떻게 동작하는지, 전 세계 많은 사람들에게 사랑받고 있는 프로그래밍 언어인 "파이썬"를 소개하는 일일 워크샵 프로그램입니다.

2013년 미국 파이콘에서 Katie Cunningham , Barbara Shaurette 두 선생님께서 시작한 청소년 대상 파이썬 워크샵 프로그램으로 미국을 이어, 캐나다, 유럽에서 진행되고 있습니다. 그리고 2017년 올해 처음으로 영코더 프로그램이 파이콘 코리아에서 진행됩니다.

https://us.pycon.org/2013/events/letslearnpython/

2014년 파이콘 미국에서 Katie와 Barbara 선생님이 "The Young Coder : 파이썬을 배우자"라는 주제로 발표한 동영상은 아래 링크에서 확인할 수 있습니다. 

http://pyvideo.org/video/2570/the-young-coder-lets-learn-python

참가하는 학생들은 라즈베리파이(RaspberryPI) 상에서 파이썬 프로그래밍 언어를 입력해보며 프로그래밍을 처음 배우게 됩니다. 워크샵이 끝나면 모든 참가한 학생들에게 라즈베리파이를 선물로 드립니다. 

## 왜 영코더 프로그램이 필요한가요?

프로그래밍을 배운다는 것은 컴퓨터가 어떻게 동작하는지, 그리고 IT가 세상을 어떻게 변화시켜나가는 지 이해하게 만들어줍니다.

여러분들이 모두 개발자가 될 필요는 없지만. 하지만 오늘날 프로그래밍 언어를 이해하는 것은 영어를 잘하는 것만큼 여러분들을 더 훌륭한 사람으로 만들어줄 수 있습니다.

또한 프로그래밍을 배운다는 것은 컴퓨터가 어떻게 동작하는지, 그리고 IT가 세상을 어떻게 변화시켜나가는 지 이해하게 만들어줍니다.

영어를 쓰는 사람들의 문화와 삶의 방식을 이해할 수 있게 되는 것 처럼요!

학생들은 몇 시간 동안 이 파이썬을 활용하여 컴퓨터와 대화하는 방법을 배우게 될 것입니다. 

이 모든 튜토리얼을 학습하는데 약 4시간 정도 소요됩니다. 

## 커리큘럼

아주 초급 수준의 프로그램이기 때문에 하루만에 모든 것을 학습할 수 없습니다.

프로그래밍을 전혀 몰라도 상관없습니다. 숫자, 문자, 문자열, 목록 등 파이썬의 간단한 데이터 유형을 배우는 것으로 시작합니다. 조건문,반복문 등 약간 더 어려운 것도 살펴볼 예정입니다. 마지막으로 PyGame 라이브러리를 활용한 게임을 만들어 보는 것으로 구성되어 있습니다.

마지막으로, 웹 사이트 및 간단한 게임을 만들어 보면서 프로그래밍으로 세상을 이해할 수 있는 더 넓은 시야를 갖게 될 것입니다.
 
주어진 시간보다 빨리 마친다고 생각되는 경우, 게임 코드 샘플을 추가적으로 학습할 수 있습니다.

워크샵 이후 학생들이 지속적으로 파이썬에 관심을 가지고 학습할 수 있는 자료들을 소개했습니다.

## E-BOOK 빌드


### npm 패키지 설치
```
npm install
```

### 개발서버 설치
```
npm install -g live-server
```
아래 명령어로 서버를 실행하세요.
코드 실습 (codemirror)는 서버를 실행해야 작동합니다.

```
live-server
```

아래 명령어로 빌드하세요.

```
brew install asciidoc 
brew tap caskroom/cask
```

### html 파일 생성
아래 명령어를 입력해 html 파일을 생성하세요.

```
make html
```

빌드가 완료되면 `./html/index.html`파일을 열면 온라인 책 첫 장이 나옵니다. 


## PDF 파일 생성
mactex 패키지를 설치합니다.

```
brew cask install mactex
```

`book.pdf(파일명.pdf)` 명령어를 입력해 파일을 생성하세요.

```
make book.pdf
```

* ePub :
```
make book.epub
```
* ePub에서 mobi으로 생성

```
make book.mobi
```

## Published Code Reference 
Customized code from [marijnh/Eloquent-JavaScript](https://github.com/marijnh/Eloquent-JavaScript)