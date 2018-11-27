# webpack4.x

关于webpack的相关知识
创建基本的webpack 4.x项目

步骤：

1.运行npm init -y快速初始化项目

2.在项目根目录创建src源代码目录和dist产品目录

3.在src目录下创建index.html

4.使用cnpm 安装webpack,运行cnpm i webpack-cli -D
    安装cnpm 全局运行 npm i cnpm -g
    
5.注意：webpack 4.x 提供了 约定大于配置的概念；目的是为了尽量减少配置文件的体积；
     。默认约定了
     。打包的入口是 ： src -> index.js
     。打包的输出文件是 ： dist -> main.js
     。 4.x 中新增了 mode 选项（为必选项），可选的值为： development 和  producion
    
    
    
    
个人总结：
在安装的过程中为了避免错误，尽可能的使用全局安装


