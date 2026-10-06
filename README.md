# 任务清单 (Todo App)

一个轻量、简洁的任务清单应用，单文件 HTML 实现，双击即可在浏览器中使用，无需安装任何依赖。

## 功能特性

- 新建 / 编辑 / 删除任务
- 一键标记完成 / 未完成
- 支持优先级（高 / 中 / 低）
- 支持设置截止日期，逾期任务自动高亮提醒
- 按状态（全部 / 待完成 / 已完成）和优先级筛选
- 关键词搜索
- 顶部统计卡片实时显示任务数量
- 数据保存在浏览器本地（localStorage），关闭重开不丢失
- 响应式布局，移动端友好

## 使用方法

### 方式一：直接使用

1. 下载 `index.html` 文件
2. 用浏览器（Chrome / Edge / Firefox 等）双击打开
3. 开始管理你的任务

> 提示：数据存储在当前浏览器的本地存储中，换浏览器或清理浏览器缓存会导致数据丢失。

### 方式二：在线访问

通过 GitHub Pages 在线使用：https://qinghanyuan888.github.io/todo-app/

## 在线部署（GitHub Pages）

本仓库已配置 GitHub Pages，在仓库 Settings → Pages 中选择部署分支即可。

## 技术栈

- 原生 HTML / CSS / JavaScript
- 无任何第三方依赖
- localStorage 数据持久化

## 项目结构

```
todo-app/
├── index.html    # 应用本体（单文件，包含全部样式与逻辑）
└── .gitignore    # Git 忽略配置
```

## License

MIT License
