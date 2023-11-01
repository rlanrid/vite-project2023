# vite를 이용한 포트폴리오 사이트 만들기

## vite를 사용하는 이유
Vite를 사용하는 주요 이유는 개발 환경의 빠른 반영, 최적화된 빌드, 작은 번들 크기, 다양한 언어 및 프레임워크 지원, 그리고 다양한 확장 가능한 플러그인을 통해 개발자들에게 뛰어난 개발 경험을 제공하기 위함입니다.
[vite](https://ko.vitejs.dev/guide)


## 구현 기능


## 트러블 슈팅
<details>
<summary>git 업로드 버그</summary>
원인 : 해당 주소에 대한 권한이 없기 떄문에 발생한다. 

해결방법 : git remote set-url origin https://github-username@github.com/github-username/github-repository-name.git
</details>

<details>
<summary>git 업로드 버그</summary>
원인 : git 프로세스가 동작중일 때 다른 git 프로세스가 실행되는 것을 막아두기 위해서 index.lock이라는 파일을 만들어서 보호를 하기 떄문에 발생한다. 

해결방법 : del ./.git/index.lock
</details>