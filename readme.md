# elementui 框架拓展

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

2022 年 9 月 7 日 17:32:37

echo "# elementui-expand" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/wcodeplus/elementui-expand.git
git push -u origin main
