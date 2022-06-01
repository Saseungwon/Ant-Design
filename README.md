## Ant Design

만들어져있는 디자인을 편하게 사용할 수 있음

- 다운로드

```bash
npm i antd
npm i --save @ant-design/icons    // 아이콘만
```

```js
import logo from "./logo.svg";
import "./App.css";
import { Calendar } from "antd";

function App() {
  return (
    <div className="App">
      <header className="App-header">
        <img src={logo} className="App-logo" alt="logo" />
        <p>
          <GithubOutlined />
        </p>
        <Calendar />;
      </header>
    </div>
  );
}

export default App;
```

### 그리드 활용해서 레이아웃 쉽게 잡기

https://ant.design/components/grid/
