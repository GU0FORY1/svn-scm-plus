# Subversion source control plus

Add the selection of commit type messages based on svn-scm

# Prerequisites

> **Note**: This extension leverages your machine's SVN installation,\
> so you need to [install SVN](https://subversion.apache.org) first.


## Settings
New setting items

<!--begin-settings-->
```js
{
  "svn.commit.messageTypes": [
          {
              "label": "feat",
              "detail": "新的功能特性"
          },
          {
              "label": "fix",
              "detail": "bug 修复"
          },
          {
              "label": "docs",
              "detail": "文档内容修改，新增"
          },
          {
              "label": "style",
              "detail": "代码格式，风格的改动"
          },
          {
              "label": "perf",
              "detail": "性能优化"
          },
          {
              "label": "refactor",
              "detail": "代码重构"
          },
          {
              "label": "test",
              "detail": "测试相关"
          },
          {
              "label": "chore",
              "detail": "构建过程或辅助工具的变动"
          },
          {
              "label": "revert",
              "detail": "回退"
          },
          {
              "label": "build",
              "detail": "打包"
          },
          {
              "label": "other",
              "detail": "other:其他"
          }
      ]
}
```
<!--end-settings-->
