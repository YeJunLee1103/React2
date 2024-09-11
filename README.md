# 3주차 강의
## 0911 수업 내용
---

렌더링(Rendering)
- 파일로 이뤄진 자료들을 완성된 웹페이지 화면에 그려주는데 그 과정을 돕는 것이 바로 렌더링 엔진

렌더링 전략
- Static Site Generation (SSG)
- Server-Side Rendering (SSR)
- Incremental Static Regeneraion (ISR)
- Clien Side Rendering (CSR)

서버 사이드 렌더링
- 생소할  수도 있지만 웹 페이지를 제공하는 가장 흔한 방법
- APM을 이용하는 일반적인 웹 페이지 생성
- 여기에 자바스크립트 코드가 적재되면 동적으로 페이지 내용을 렌더링
- Next.js도 이와 같이 동적으로 페이지를 렌더링
- 스크립트 코드를 넣어서 동적으로 처리하게 되면 하이드레이션이라고 함