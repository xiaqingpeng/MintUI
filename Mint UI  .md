##  Mint UI 使用
1. 使用Vue-cli 工具搭建好脚手架工具
2. 安装Mint UI   npm i mint-ui -S  || (yarn add mint-ui -S)
3.  安装css加载器 
    npm install  style-loader  css-loader  --save-dev ||
    yarn add  style-loader  css-loader  --save-dev
4. 在main.js中写入
    import Vue from 'vue'
    import MintUI from 'mint-ui'
    import 'mint-ui/lib/style.css'
    import App from './App.vue'

    Vue.use(MintUI)


