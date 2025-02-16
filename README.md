# React 공부 및 기록용입니다.

## 25.02.12

- React를 사용하려면 가장 먼저 script에 import해야함

- React의 장점 중 하나는 유저에게 보여질 내용을 제어(Control)할 수 있다는게 장점인거 같음

- JSX는 js(JavaScript)를 확장한 문법임

- JSX에서는 **컴포넌트의 첫글자는 대문자로 써야함**. 만약 소문자라면 React랑 JSX에서는 html태그로 바라봄

## 25.02.16

- React.useState 는 컴포넌트의 상태를 간편하게 생성하고 업데이트 해주는 도구라고 함
  > state 생성과 동시에 가져야할 초기값을 useState 함수에 인자로 넣어주면 state와 setState를 두가지 요소를 배열 형태로 리턴해준다.
  >
  > > ex) const [state, setState] = useState(초기값);
