# vite를 이용한 포트폴리오 사이트 만들기

## vite를 사용하는 이유

1. 빠른 개발 속도: Vite는 빠른 개발 환경을 제공하여 코드 수정 시 즉시 반영되어 빠른 개발 및 디버깅을 가능케 합니다.

2. 빠른 빌드 속도: Vite는 빌드 시 필요한 모듈만 변경 사항을 다시 빌드하므로 전체 빌드 시간이 절약되며, 배포와 성능을 향상시킵니다.

3. ESM(ES Module) 지원: Vite는 최신 JavaScript 표준 ES Module을 지원하므로 모듈 시스템을 효율적으로 활용할 수 있습니다.

4. 다양한 플러그인 및 통합성: Vite는 다양한 플러그인 및 프레임워크와의 통합이 용이하며, 개발자들이 필요한 도구와 기능을 쉽게 확장할 수 있습니다.

[vite](https://ko.vitejs.dev/guide/)



## 구현 기능
구글 폰트



## 트러블 슈팅
<details>
<summary>git 업로드 버그</summary>
- 403 에러(GitHub 리포지토리에 대한 권한 부족 및 권한 문제)<br>
1. git remote set-url origin https://kiwowki@github.com/kiwowki/vite-project.git (참고: https://beagle-dev.tistory.com/244)<br>
2. 자격 증명 관리자에서 권한 이름 변경하기
</details>
<details>
<summary>git 초기 세팅</summary>
- node_modules 설치<br>
-> npm i
</details>
#vite-project