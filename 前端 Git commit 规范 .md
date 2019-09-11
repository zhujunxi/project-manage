# 前端 Git commit 规范

## commit 提交规范

Commit message

```bash
<type>: <subject>
<body>
```

### header

- type: 用于说明 commit 的类别，只允许使用下面 7 个标识。

  - feat：新功能（feature）
  - fix：修补 bug
  - docs：文档（documentation）
  - style： 格式（不影响代码运行的变动）
  - refactor：重构（即不是新增功能，也不是修改 bug 的代码变动）
  - test：增加测试
  - chore：构建过程或辅助工具的变动
  - perf: 性能优化
  - revert: revert 之前的 commit
  - build 或 release: 构建或发布版本
  - safe: 修复安全问题

- subject: 提交目的的简短描述, 动词开头, 避免出现 `<feat> 更新代码` 等无意义 commit 信息

- body: commit 的详细描述，如无必要可省略
