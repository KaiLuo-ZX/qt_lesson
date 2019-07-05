##emmet 快捷输入
vscode 来自微软 , 内置了emmet 插件
- 使用css选择器来自快熟的语法
1. 类名选择器 .className
2. > 父子选
4. [] 属性选择器
.starwars-demo>img.star[src="./images/.svg"]*2
.定位
  css 布局的一种
  position:absolute; 绝对定位
  position:relateive; 相对定位 body 是最顶级的定位
  父级或一直往外查找，如果有定位元素相对最近的长度元素定位。否则添加body

配置网页自动刷新
Ctrl+ ~ 输入 node -v 回车 npm config set registry https://registry.npm.taobao.org
回车 输入 npm  install -g live-server 回车 输入  live-server --version(查看是否安装成功) 打开 Open in Terminal 输入dir 回车 输入 live-server 回车

transfrom
  变形属性 translate 移动[scale 缩放] rotate 旋转
  三维世界 perspective 视点与屏幕的距离
  transform-style： preserve3d;

npm node 的工具包管理
  live-server 静态网页提供了 web-server 热更新
  npm install -g liver-server
  js 的命令行工具 运行在服务器端
  