## vue 搭建环境复习
* 安装node.js  下载地址(http://www.runoob.com/nodejs/nodejs-install-setup.html)
> 安装完成之后检查 cmd 裏面輸入 node -v
* 基于node.js,利用淘宝npm镜像安装相关依赖
 > 安装淘宝镜像  在cmd里直接输入：npm install -g cnpm --registry=https://registry.npm.taobao.org

* 安装全局vue-cli脚手架
> 在cmd里 
>> 输入：cnpm install -g vue-cli
> 检查是否安装成功
>> 输入：vue，回车，若出现vue信息说明表示成功
* 创建项目
> 在cmd里输入：vue init webpack vue_test(项目文件夹名)，回车，等待一小会儿
>> 出现ESlint 的时候选择输入N  （有些不需要安装）
* 安装 node依赖 
> 进入文件夹项目
>> 在cmd里  1).输入：cd vue_test（项目名），回车，进入到具体项目文件夹
            2).输入：cnpm install，回车，等待
            
* 回到项目文件夹，多了一个node_modules文件夹（该文件里的内容就是之前安装的依赖）
* 运行项目
> cnpm run dev 或者 npm run dev
