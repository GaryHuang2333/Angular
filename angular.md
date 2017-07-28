# Angular Note 
- refer to (http://doc.oschina.net/book-angular)(666)

# HTML5 Intruduction
- table + tab 可自动补全
# CSS3 Intruduction
- 1 sass -  CSS扩展语言
- 2.1 类选择器(.class_name{})
- 2.2 标签选择器(tag_name{})
- 2.3 id选择器(#id_name{} )
- 3 盒模型padding, margin
- 4.1 后代选择器(div p)
- 4.2 子元素选择器(div>p)
- 4.3 相邻兄弟选择器(div+p)
- 4.4 普通兄弟选择器(div~p)
# Javascript Intrudoction
-调试 console.log()
-

# Git Intrudoction
- git clone http://.....
- download git project:
1. create folder
2. git clone https://github.com/ryanemax/ng-lazyload-starter
（实战项目
https://github.com/ryanemax/ng-admin）
3. into folder 
npm install
4.

5. ng serve(build and deploy to web)
6. git push    -u origin master
- *git log 

#angular structure
- app-root



# 第三节：界面布局及响应式规范讲解(new)!!!
(代码格式化插件 ctrl + D ???)
- 响应式网格视图通常是 12 列，宽度为100%，在浏览器窗口大小调整时会自动伸缩。
- 调色板 material design plate<br/>
  https://www.materialpalette.com/blue/cyan
- svg 背景(下载svg)<br/>
  http://qrohlf.com/trianglify-generator/
- 只滚动特定div模块而非全页
   
  
  
# JSON
  -kjson.com 检验工具

# 作业
  -MDN array排序
  
#
https://github.com/f58xxy/ng-admin/blob/master/src/pages/home/home-page/home-page.component.ts




---------------------
day2

# Angular
- 装饰器 @Component
@Component({
  selector: 'app-root',
  templateUrl: './app.component.html',
  styleUrls: ['./app.component.css']
})

- 指令 directive
```
<tr *ngFor="let app of apps">
```

- 管道 pipe
 过滤数据
 ```
  <td>{{user.name|uppercase}}</td>
  <td>{{user.name|uppercase}}</td>
 ```

 
#作业

#New模块
- ng g module student
- ng g component ./student/student-list --module student
- ng g component ./student/student-edit --module student
- ng g component ./student/student-item --module student
- 拖动文件夹， 在vscode改路径，文件名，module名
- *ctl-p 查找模块
-


