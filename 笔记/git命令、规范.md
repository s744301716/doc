# git命令、规范

## 📌 常见的提交类型（type）

| 类型         | 说明              |
| ---------- | --------------- |
| `feat`     | 新功能（Feature）    |
| `fix`      | 修复 bug          |
| `refactor` | 重构（不影响功能的代码优化）  |
| `style`    | 样式调整（空格、缩进、格式等） |
| `docs`     | 文档修改            |
| `test`     | 测试相关（新增测试、修改测试） |
| `chore`    | 构建过程或辅助工具的变动    |
| `perf`     | 性能优化            |
| `ci`       | CI配置相关变更        |
| `revert`   | 回滚某次提交          |
| `merge`    | 合并分支            |
## 写错分支解决
```ruby 
	git stash
	git checkout master
	git stash pop
```
