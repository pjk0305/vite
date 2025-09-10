# 사용 스택

    - vite(https://ko.vitejs.dev/) 를 사용하여 사이트를 번들링하고 관리합니다.
    - gsap(https://greensock.com/gsap) 를 이용하여 패럴랙스 효과를 줍니다.
    - lenis(https://lenis.studiofreight.com/) 를 이용하여 스므스 효과를 구현합니다.
    - netlify(https://www.netlify.com/) 를 통해 사이트를 배포합니다.
    - git(https://github.com/) 을 사용하여 파일을 관리합니다.
    - HTML, CSS 기반으로 웹사이트의 기본 레이아웃 설계하고, 웹 표준 및 웹 접근성을 준수하여 작업합니다. [ARIA(Accessible Rich Internet Applications)](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles)
    출처: https://webstoryboy.co.kr/1924 [WEBSTORYBOY:티스토리]

# 포트폴리오 사이트 만들기 시작 1일차

    vite를 이용하여 사이트를 제작 및 불필요한 요소 제거함으로써 기본 틀 잡기

    - vite를 설치합니다. 'npm create vite@latest'
    - gsap를 설치합니다. 'npm install gsap'
    - lenis를 설치합니다. 'npm install @studio-freight/lenis'
    - vite를 설치 후 환경 설정을 합니다. 'vite.config.js' 파일을 만들고 다음과 같이 작성합니다.
    '''javascript
    export default {
        root: "src"
        build:{
            outDir:"../public",
        },
    };
    
    GSAP의 중요성을 느낌

