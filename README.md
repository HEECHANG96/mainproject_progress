# mainproject_progress

- Figma
 - [ ] [Figma 링크](https://www.figma.com/file/Hals1rmN2TKl0AMwazbSSc/SEB_%EB%A9%94%EC%9D%B8%ED%94%8C%EC%A0%9D?type=design&node-id=0-1&mode=design&t=L3CFX8joEtamLaRg-0)

---
- Login Form
 - [ ] React.ChangeEvent<HTMLInputElement>
   - HTML 입력 요소에 대한 변경 이벤트를 나타내는 TypeScript 유형
   - 구체적으로 <input> 요소를 대상으로 하며 입력 값이 변경될 때 전달되는 이벤트 개체에 대한 유형 정보를 제공
 - [ ] Oauth Google Login
   - https://github.com/MomenSherif/react-oauth#googlelogin
   - https://react-oauth.vercel.app/
   - [간단한 구현 및 설명](https://stack94.tistory.com/entry/React-%EA%B5%AC%EA%B8%80-%EB%A1%9C%EA%B7%B8%EC%9D%B8Google-Login-%EB%A6%AC%EC%95%A1%ED%8A%B8React%EC%97%90%EC%84%9C-%EA%B5%AC%ED%98%84%ED%95%B4%EB%B3%B4%EC%9E%90)
   - clientId를 .env 파일에서 가져오지를 못함 => 해결 O => npm install dotenv => REACT_APP_GOOGLE_CLIENT_ID=0000000000 => const clientId: string | undefined = process.env.REACT_APP_GOOGLE_CLIENT_ID;
 - [ ] [CSS 참고 영상](https://www.youtube.com/watch?v=dWfpp-0riYA) 
---
 - CSS
  - [ ] box-shadow
    - [예시와 적용된 모습이 잘 나와있음](https://blog.logrocket.com/three-ways-style-css-box-shadow-effects/)
  - [ ] 투명도
    - [opacity](https://codingbroker.tistory.com/58)
---
  - Git
   - [ ] commit
     - [push하지 않은 commit 확인](https://blog.outsider.ne.kr/820)
     - [commit 취소](https://velog.io/@falling_star3/GitHub-git-add-git-commit-git-push-%EC%B7%A8%EC%86%8C%EB%B3%80%EA%B2%BD%EB%8D%AE%EC%96%B4%EC%93%B0%EA%B8%B0)
     - git reset HEAD^(가장 최신 커밋 1개 취소)
