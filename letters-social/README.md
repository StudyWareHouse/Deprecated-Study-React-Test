# [Letters Social](https://ifelse.io/book)

> Study Environment: Node 8.17.0

Master: [![CircleCI](https://circleci.com/gh/react-in-action/letters-social.svg?style=svg)](https://circleci.com/gh/react-in-action/letters-social)

## Welcome!

If you're here, you're probably reading [_React in Action_](https://ifelse.io/book) by, well, me ( [@markthethomas](https://github.com/markthethomas)) 😀! I hope you're enjoying learning about React so far. If you have any questions or thoughts, feel free to reach out to me @markthethomas ( [blog](https://ifelse.io), [twitter](https://twitter.com/markthethomas), [github](https://github.com/markthethomas)) pretty much anywhere. Below are some helpful links to chapters, documentation, the running application, and so on.

## Links

- [**Buy**](https://ifelse.io/book): Buy _React in Action_ and get started today!
- [**App**](https://social.react.sh): Example application that you'll build in _React in Action_.
- [**Docs**](https://docs.react.sh): Documentation for the application source code generated using ESDoc. It's not perfect, but you can use it to get a quick overview of the sample application.
- [**Guide to the React Ecosystem**](https://ifelse.io/2018/07/04/a-guide-to-the-react-ecosystem/): As part of _React in Action_, I've put together a guide to the React ecosystem. The goal of the guide is to help you get your feet when navigating the many different communities, online and otherwise, that comprise the React ecosystem.
- [**Forum**](https://forums.manning.com/forums/react-in-action): The book forum is a great place to ask questions about the book
- [**Site**](https://ifelse.io): I try to write often at my personal blog, <a href="https://ifelse.io" target="_blank" rel="noopener noreferrer">If Else</a>. Check it out if you're interested in React, JavaScript, UI engineering, or random programming tidbits!
- [**Twitter**](https://twitter.com/markthethomas): Have a question about the book? Feel free to tweet at me or DM me and I'll get back to you!
- <b><a href="mailto:hello@ifelse.io">Email</a></b>: You can also feel free to send me an email and I'll do my absolute best to get back to you
- [**Issues**](https://github.com/react-in-action/letters-social/issues/new): Feel free to open any issues w/ questions or proposed changes here

## Chapter branches

- (Chapters 1-2 can be found in the book and use online code samples from [CodeSandbox](https://codesandbox.io))
- [Chapter 4](https://github.com/react-in-action/letters-social/tree/chapter-4)
- [Chapters 5 & 6](https://github.com/react-in-action/letters-social/tree/chapter-5-6)
- [Chapters 7 & 8](https://github.com/react-in-action/letters-social/tree/chapter-7-8)
- [Chapter 9](https://github.com/react-in-action/letters-social/tree/chapter-9)
- [Chapters 10 & 11](https://github.com/react-in-action/letters-social/tree/chapter-10-11)
- [Chapter 12](https://github.com/react-in-action/letters-social/tree/chapter-12)

## Tooling

- [React](https://reactjs.org): of course!
- [Redux](https://redux.js.org): for state management
- [Webpack](https://webpack.js.org/): Incredible asset bundler
- [JSON server](https://github.com/typicode/json-server): used for local dev and to run the demo site at [social.react.sh](https://social.react.sh)

## What you'll build

Letters Social, a social networking app that leverages React, Redux, and even gets you using more interesting techniques like server-side rendering!

[![React in Action by Mark Thomas](https://cdn.ifelse.io/images/letters-social-screencap.png)](https://ifelse.io/book)

## React Mental Model

- 컴포넌트는 상태와 속성을 이용해 데이터를 다룬다.
- 컴포넌트는 자바스크립트 클래스이기 때문에 이벤트에 반응하기 위한 생명주기 메서드들은 물론 다른 작업을 처리하기 위한 사용자 정의 클래스 메서드를 선언할 수 있다.
- 보통의 DOM 요소와 마찬가지로 리액트 컴포넌트 내에서도 클릭이나 입력값의 변경 등과 같은 이벤트를 리스닝할 수 있다.
- (form 요소와 같은) 부모 컴포넌트는 자식 컴포넌트의 속성으로 콜백 메서드를 전달해서 컴포넌트 간에 통신을 지원할 수 있다.
