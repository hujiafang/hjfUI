# vuedemo_hjf学习组件库

### 快速开始

#### 1.安装组件库

```bash
npm i vuedemo_hjf
```

#### 2.引用组件库
```javascript
// 全部引入
import 'vuedemo/dist/css/index.css';
import  MUI from 'vuedemo';
Vue.use(MUI);


// 按需引用
import 'vuedemo/dist/css/demo.css';
import {Demo} from 'vuedemo';
Vue.use(Demo);
```