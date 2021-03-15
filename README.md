### 왜 typescript를 사용하는가?
___

<br>

-   자바스크립트가 갖고 있지 않은 규칙들을 갖고 있다.

-   자바스크립트가 유명한건 엄격한 규칙이 없기 때문이고, 사용하기 쉽고, 우리가 원하는 방향으로 수정하기도 편하기 때문이다.

-   그러나 이것이 큰 프로젝트를 한다거나, 팀으로 일한다거나, 버그를 최소화하고 싶을 때 위의 장점은 단점이 된다.

-   이것이 typescript가 탄생한 배경이다. superset of JavaScript

- 언어가 예측 가능하고, 읽기 쉬운 코드 등 자바스크립트를 더 잘 사용할 수 있게 한다. 

<br>

### Setting Typescript up
___

<br>

✔ typescript를 global로 설치해야 tsc 명령어 동작

<br>

✔ script 설정

<br>

    "scripts": {
        "start": "node index.js",
        "prestart": "tsc"
    }


index.js를 실행하기 전에 ts 파일을 컴파일해야하므로 `prestart` 명령어를 이용해 `start` 전에  `tsc`가 되도록 설정

<br>

🤷‍♀️ Node.js는 Typescript를 이해하지 못하기 때문에 일반적인 Javascript 코드로 컴파일하는 작업이 필요하다.