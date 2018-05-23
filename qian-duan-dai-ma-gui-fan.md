### 前端代码规范

* [Code Guide by @AlloyTeam-materliu](https://legacy.gitbook.com/book/nowgoant/fek-awesome/edit#) 腾讯AlloyTeam团队贡献
* [JavaScript Style Guide](https://github.com/airbnb/javascript)airbnb贡献

### Prettier

* [我为什么推荐Prettier来统一代码风格](https://blog.fundebug.com/2017/10/23/format-code-use-Prettier/)

* [用 Prettier 统一团队的代码风格~](http://react-china.org/t/prettier/11498)

* [用Prettier格式化JavaScript代码](http://www.infoq.com/cn/articles/using-prettier-format-javascript-code)

* [用 ESLint 和 Prettier 写出高质量代码](https://egoist.moe/2017/12/11/write-better-code-with-eslint-and-prettier/)

* [prettier的配置选项（参数）官网直译](https://segmentfault.com/a/1190000012909159)

* [用 Prettier 美化代码](https://github.com/shaozj/blog/issues/18)



```
.prettierrc 
```

```

{
  "printWidth": 120,               // 换行字符串阈值
  "semi": true,                    // 句末加分号
  "singleQuote": true,             // 用单引号
  "trailingComma": "none",         // 最后一个对象元素加逗号
  "bracketSpacing": true,          // 对象，数组加空格
  "jsxBracketSameLine": false,     // jsx > 是否另起一行
  "arrowParens": "avoid",          // (x) => {} 是否要有小括号
  "requirePragma": false,          // 是否要注释来决定是否格式化代码
  "proseWrap": "preserve"          // 是否要换行
}
```



