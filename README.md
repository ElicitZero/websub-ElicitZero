<img src="https://cdn.jsdelivr.net/gh/lhl77/repository@main/blog/20210802143449.png" alt="web"/>
<h1 align="center">珞汐の订阅转换</a></h1>
<h2 align="center">基于 <a href="https://github.com/lhl77/subweb-tsutsu" target="_blank">subweb-tsutsu</a> 项目修复</h2>
<p align="center">

## 基础配置文件

> 必须修改

- public
    - setting
        - `setting.js` ：设置主题信息
        - `setting.css` ：设置主题样式


## 高级配置文件

> 可以不修改，不影响最终效果

- public
    - `index.html` ：UA识别，高级背景等设置
- src
    - views
        - `Subconverter.vue` ：可设置subweb内容，远程配置后端配置，网页Title+订阅转换上部显示文字等

## 部署方面
 1.修复了vercel部署环境（由于vercel官方将关闭java16支持，所以兼容了Java18 参考了部分 <a href="https://github.com/youshandefeiyang/sub-web-modify" target="_blank">sub-web-modify</a> 项目的代码）<br>
 
 2.关于主题定制方面，解密并本地化了app.js,把主题处理（theme.js）保留到了本地<br>
 
 3.去除了官方项目中的远程主题内置的广告（我有强迫症而且广告失效了，原作者勿怪）<br>
 
 4.已更新sub项目部分功能（例如更多功能按钮和其包含功能）<br>

## 未实现功能
暂未完成全部css美化

修复并同步"上传自定义功能"

 ##参考项目<br>
<a href="https://github.com/youshandefeiyang/sub-web-modify" target="_blank">sub-web-modify</a> <br>
<a href="https://github.com/lhl77/subweb-tsutsu" target="_blank">subweb-tsutsu</a>
