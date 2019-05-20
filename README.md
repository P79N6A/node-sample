# node系列学习记录

## 安装node代码提示工具typings
```
tnpm i typings -g
```

## 在根目录使用
```
typings init
```

## 新建文件.typingsrc，新增内网代理
```
proxy=http://dev-proxy.oa.com:8080
rejectUnauthorized=false
```

## 安装node定义文件
```
typings install dt~node --global --save
```
