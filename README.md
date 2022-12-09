# eslintdemo

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn run serve
```

### Compiles and minifies for production
```
yarn run build
```

### Run your tests
```
yarn run test
```

### Lints and fixes files
```
yarn run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
# 常用的git命令
## 查看本地代码与远程代码的区别
`git diff HEAD --`

## 丢弃本地上一次commit的本地缓存代码
`git checkout --`

## 查看提交到github的记录
`git log`

## 查看本地commit记录
`git reflog`

## 给最近的一次commit加上一个tag
`git tag '我是星期五提交的代码'`
## 对某次已经提交到github上的代码进行补救打tag
`1.git log --pretty=oneline --abbrev commit`
`2.git tag 'tag内容' commitID`

## 如何配置不提交到仓库的方法
[gitignore地址](https://github.com/github/gitignore)

