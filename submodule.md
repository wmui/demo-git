https://git-scm.com/book/zh/v1/Git-%E5%B7%A5%E5%85%B7-%E5%AD%90%E6%A8%A1%E5%9D%97

### 添加子模块

```
git submodule add https://github.com/wmui/gulp-demo.git [path]
```

### clone 带有子模块的项目

```bash
# 正常克隆，这时候子模块是空的
git clone https://github.com/wmui/demo-git.git

# 初始化子项目，这时候子模块版本和demo-git一致
git submodule init
git submodule update
```

### 更新子模块

```bash
# 子模块和git仓库一样，在子模块中完成修改后，直接push

# 父模块同步最新的子模块
git submodule update --remote

```