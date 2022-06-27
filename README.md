# v3-shop

vue3商城后台管理系统

## 一、项目介绍

## 二、创建vite项目和配置

### 2.1 创建vite项目并安装vscode插件

```cmd
npm init vite@latest <project-name> -- --template vue
```

### 2.2 引入ElementPlus和基本使用

- 安装`element-plus`

```cmd
npm install element-plus --save
```

- 在`mian.js`中集成`element-plus`

```javascript
import { createApp } from 'vue'
import ElementPlus from 'element-plus'
import 'element-plus/dist/index.css'
import App from './App.vue'

const app = createApp(App)
app.use(ElementPlus)
app.mount('#app')
```

### 2.3 引入windicss工具库和配置,安装代码提示

### 2.4 windicss小案例和@apply简化代码

### 2.5 引入vue-router4

### 2.6 路由配置和404页面捕获