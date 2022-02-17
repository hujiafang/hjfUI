# 快速开始

#### 安装组件库

```bash
npm i vuedemo_hjf
```

#### 使用组件库
>在main.js中引用组件库
```javascript
//全部引入
import 'vuedemo_hjf/dist/css/index.css';
import MUI from 'vuedemo_hjf';
Vue.use(MUI);


//按需引入
import 'vuedemo_hjf/dist/css/demo.css';
import {Demo} from 'vuedemo_hjf';
Vue.use(Demo);
```
