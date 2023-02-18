# clone
实现Javascript引用类型数据的深拷贝功能

## 使用者指南
通过npm下载安装代码

```bash
$ npm install xxxx
```

使用Node.js环境
```js
var {clone} = require('xxxx');
clone({a:1});
```

如果使用webpack等环境
```js
import {clone} from 'xxxx';
clone({a:1})
```

## 贡献者指南
首次运行需要先安装依赖
```bash
$ npm install
```

一键打包生成生产代码
```bash
$ npm run build
```

运行单元测试
```bash
$ npm test
```
# 待办清单

- [x] 完成基本的clone函数
- [ ] 支持大数据拷贝
- [ ] 支持保留引用关系