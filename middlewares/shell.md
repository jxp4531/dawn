---
group: middleware
name: shell
title: 执行脚本
---

## shell 中件间

这是一个执行 shell 的中件间，只有一个 `script` 选项，示例

```yml
dev:
  - name: shell
    script:
      - echo 你好
```

提示：执行 shell 时的当前工作目录就是「当前项目根目录」