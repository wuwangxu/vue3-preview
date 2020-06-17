# vue3-preview

> 提前体验 vue.js3.0  目前 vue3.0 命名为 vue-next



## 环境（体验方式）

目前有三种体验方式

### vue-cli

1. 初始化项目并安装依赖

   ```bash
   > vue create vue3-demo-cli
   # 添加 vue-next 依赖
   > vue add vue-next
   ```

2. 修改 main.js 的 createApp 函数

   ```javascript
   -  createApp({
   -    render: function (h) { return h(App) },
   -  }).mount('#app')
   
   +  createApp(App).mount('#app')
   ```

   

### webpack

 [Vue 代码仓库](https://github.com/vuejs/vue-next-webpack-preview)

```bash
git clone https://github.com/vuejs/vue-next-webpack-preview

npm install
```



### 