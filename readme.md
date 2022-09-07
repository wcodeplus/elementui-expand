# elementui 框架拓展

### 第一天

2022 年 9 月 7 日 17:46:10

- 查看 node 和 npm 的版本
  node -v 16.16.0
  npm -v 8.15.0

- 安装脚手架
  npm install -g “@vue/cli”
  vue create project

- 安装 elementui
  npm i element-ui -S
  在 main.js 中引入
  import ElementUI from 'element-ui';
  import 'element-ui/lib/theme-chalk/index.css';
  Vue.use(ElementUI);

- 运行
  npm run serve

2022 年 9 月 7 日 17:46:04

- github 新建仓库，啥都不要配置
- vscode git clone 下来
- 查看当前的 git 配置
  git config -l
- 退出
  :wq
- 设置 local 级别的权限
  git config --local user.name "wcodeplus"
  git config --local user.email "wcodeplus@163.com"
- 查看
  git config --local -l
- 提交
  git push -u origin main

2022 年 9 月 7 日 17:32:37
