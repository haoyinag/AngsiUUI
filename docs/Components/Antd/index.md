# 说明

避免日常开发过多的相同代码的复制粘贴等问题，把相关组件抽离封装，提升效率的同时尽量让代码更美观、高效。

## 注意点

1. 组件的`UI`尽量仅仅依赖`antd`，当前依赖版本是`"antd":"^4.4.3"`。
2. 组件的封装内部尽可能纯净，尽量少业务逻辑。
3. 组件内部必须有注释。