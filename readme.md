<!--
 * @Description: 
 * @Version: 0.1.0
 * @Author: AiDongYang
 * @Date: 2021-01-13 17:24:47
 * @LastEditors: AiDongYang
 * @LastEditTime: 2021-01-13 17:38:09
-->
webpack 打包工具

压缩代码 JS 混淆代码

浏览器不支持

ES6 ES7 ES8... 语法特征


First Step

三大件

webpack
webpack-cli
webpack-dev-server


Second Step

处理JS -> ES6 ES7 ES8 装饰器
六大件

<!-- 转换ES6 -->
babel-loader@7 默认安装第八个版本 会和babel-core冲突 所以安装7
babel-core
babel-preset-env

<!-- 转换ES7 ES8 -->
babel-plugin-transform-runtime
babel-plugin-transform-decorators ->转换装饰器
babel-plugin-transform-decorators-legacy


Third Step

四大件
<!-- 处理 sass -> css -> styke -->
sass-loader
node-sass
css-loader

postcss-loader autoprefixer(插件 配合使用)

style-loader 如果不使用内联可以使用(mini-css-webpack-plugin)压缩单独文件

Forth Step
<!-- 处理模板 -->
处理ejs tpl ...自定义后缀 进行配置

ejs-loader


Fifth Step
<!-- 处理HTML -->

html-webpack-plugin


