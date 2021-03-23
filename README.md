# Svelte_study

```
리액트는 좋다는거 다알고 사용성도 제일 높은데, 초보 입장에서 복잡하고, 뷰는 좋은 대안인데, 
스벨트가 있네!!! 더 간결해! 일단 이거구나! 스벨트 공부 하자!!!
```

- [HEROPY TECH Svelte.js Core API 완벽가이드 ](https://www.youtube.com/watch?v=dFTu4-I0cdU&list=PL5v0w59YqSue9aPueJ15phdPv6lcvWzVy&index=12)
- [Heropy Tech 블로그](https://heropy.blog/2019/09/29/svelte/)

## 1. sveltejs / template : 일반 템플릿
- [기본 템플릿](https://github.com/sveltejs/template)

- webpack 도 있으나, 일반 템플릿을 사용한다. 롤업 roll up ???

## 2. 설치
- npx, npm 설치 되어 있다! 가정!
- `npx degit sveltejs/template 프로젝트명`
- `cd 프로젝트명`
- `npm i` 
 
## 3. 시작
- `npm run dev`

## 4. 앗! 나의 실수! src/main.js 삭제 했더니 ㅎㅎ 덕분에 구조를 알아감! ㅎ
- main.js : 스벨트 파일에서 컴포넌트를 임포트하여 객체 생성! 
```
#  hmtl body 태그에 연결됨!!
const app = new App({
target: document.body,
props: {}
});

```

___

## Svelte Tutorial
- [스벨트 튜토리얼 바로가기](https://svelte.dev/tutorial/basics)
- [hatemogi 스벨트 완전정복 4시간](https://www.youtube.com/watch?v=SMatXKHgS1A&t=2784s)
1. 인트로
2. Reactivity
3. Props
4. Logic
5. Event (유툽 1:15:30 ~ 1:30:55)
    - (1) DOM events
    - (2) Inline handlers
    - (3) component events
    - (4) Event forawrding
    - (5) DOM event forwarding

6. Bindings ( ~ 2:'06:15)
    - (1) Text inputs
    - (2) Numeric inputs
    - (3) Checkbox inputs
    - (4) Group inputs
    - (5) Textarea inputs
    - (6) Select bindings
    - (7) Contenteditable bindings
    - (8) Each block bindings
    - (9) Media elements
    - (10) Dimensions
    - (11) This
    - (12) Component bindings

7. LifeCycle ( ~2:33:57)