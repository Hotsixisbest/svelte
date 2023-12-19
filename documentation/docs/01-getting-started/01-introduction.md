---
title: 소개
---

Svelte 참조 문서에 오신 것을 환영합니다! 이 문서는 이미 Svelte에 익숙한 분들이나 사용법을 더 배우고 싶은 분들을 위한 자료로써 계획되었습니다.

(아직) Svelte에 대해 익숙하시지 않다면, 이 문서를 참고하기 전에 [상호작용 튜토리얼](https://learn.svelte.dev)이나 [예시](/examples)를 방문해 보시는 것이 좋겠습니다. 또한 [REPL](/repl)을 사용해 온라인에서 Svelte를 사용해보실 수 있습니다. 아니면 더 완전한 기능을 가진 환경을 원하신다면 [StackBlitz](https://sveltekit.new)에서 Svelte를 사용해보실 수 있습니다.

## 새 프로젝트를 시작하기

Svelte team의 공식 애플리케이션 프레임워크인 [SvelteKit](https://kit.svelte.dev/)을 사용하시는 걸 추천드립니다:

```
npm create svelte@latest myapp
cd myapp
npm install
npm run dev
```

SvelteKit은 [Svelte 컴파일러](https://www.npmjs.com/package/svelte)를 호출하여 여러분의 `.svelte` 파일들을 DOM을 생성하는 `.js` 파일과 스타일을 꾸미는 `.css` 파일로 변환하는 일을 처리할 것입니다. 또한 Sveltekit은 개발 서버, 라우팅, 배포, SSR 지원 등과 같은 여러분이 웹 애플리케이션을 개발하는 데 필요한 모든 다른 기능들을 제공합니다. [SvelteKit](https://kit.svelte.dev/)은 여러분의 코드를 빌드하는 데에 [Vite](https://vitejs.dev/)를 사용합니다.

### Sveltekit의 대안

여러분이 만약 Sveltekit을 사용하고 싶지 않으시다면, Vite(Sveltekit이 없는)를 이용해 `npm create vite@latest`를 실행하고 `svelte` 옵션을 선택하여 Svelte를 사용할 수 있습니다. 이 경우에, `npm run build`는 HTML과 JS, CSS 파일들을 `dist` 폴더 안에 생성합니다. 대부분의 경우에 여러분들은 [라우팅 라이브러리](/faq#is-there-a-router)을 선택해야 할 것입니다.

또는, Svelte 컴파일을 처리하기 위한 [모든 메이저 웹 번들러들을 위한 플러그인들](https://sveltesociety.dev/tools#bundling)이 있습니다 - 이는 HTML에 넣을 수 있는 `.js`와 `.css` 파일들을 생성합니다 - 하지만 대부분은 SSR을 처리하지 않을 것입니다.

## 에디터와 도구

Svelte 팀은 [VS Code 확장](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode)을 유지보수할 수 있고 또한 다양한 [에디터들](https://sveltesociety.dev/tools#editor-support)과 도구들도 있습니다.

## 도움 요청하기

[Discord 채널](https://svelte.dev/chat)에서 질문하는 것을 부끄러워 하지 마세요! 또한 [Stack Overflow](https://stackoverflow.com/questions/tagged/svelte)에서도 해답을 찾을 수 있을 겁니다.