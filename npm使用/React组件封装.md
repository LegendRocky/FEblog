# React组件的封装

先看看比较规范的组件结构

>ps:此教程适用于react组件封装，以及如何将react组件打包并发布，由于本人也是这方面的初学者，也在慢慢探索，所以周期可能会比较长，所以请耐心等候，但本教程会很详细的描述自己在开发中遇到的问题，做好笔记方便自己使用，也方便后来的初学者能够快速的了解react组件的用法，以快速的融入项目。为了能够清晰的讲解到每个环节，可能会过于拖沓，希望读者朋友们不要太过焦躁。

## 先来看看一个比较完美的组件结构（目录中的东西也是我们要完成的）
参考组件 https://github.com/react-component/pagination
目录结构如下:
```js
    assets
    examples
    src
    tests
    .editorconfig
    .eslintignore
    .gitignore
    .travis.yml
    HISTORY.md
    README.md
    index.js
    package.json
```

在写一个组件之前，现在当前目录下执行一下npm init 就会创建一个初始化的组件

那我们开始我们的组件之旅吧，今天就先把我之前常用组件封装一下