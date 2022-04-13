1.包的规范(了解)
- package.json必须在包的顶层目录下
- 二进制文件应该在bin目录下
- JavaScript代码应该在lib目录下
- 文档应该在doc目录下
- 单元测试应该在test目录下
***
### 自定义本地包发布到NPM

***
- 指令执行js时传递参数
***
- npm root -g 全局包地址
```javascript
当执行myPkg指令,就会执行对应的文件
"bin":{
    "myPkg":"index.js"
}
```
***
- 进入my-pkg
- npm link -> 将本地包拷贝到全局
- my-pkg修改时, 需要重新link
***
