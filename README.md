# React_counter
리액트를 이용해 +/- 버튼을 구현해 보았습니다.

![React_counter](https://user-images.githubusercontent.com/61913417/108501697-07e60080-72f5-11eb-9c74-1fc8e6cf50b7.gif)

## 공부
creat-react-app 설치!
> npm install -g creat-react-app
npx creat-react-app [폴더명]

useState
> const [num, setNum] = useState(0);
--> num이 현재 상태 값, setNum이 변경할 값을 넣어주는 곳, useState는 초기값 설정!

```
<button onClick={onIncrease}>+1</button>
```
> 버튼 클릭 시 함수를 불러 올 때 onIncrease()로 불러오게 되면 버튼이 클릭 될 때가 아니라 페이지가 로드될 때 바로 실행된다. 따라서 버튼이 클릭 될 때 함수가 작동하게 하고 싶다면 괄호를 뺀 onIncrease를 써줘야 된다.
