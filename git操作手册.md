# Git 版本控制操作手册（小白入门）

## 1. 什么是 Git？
Git 是一个免费的分布式版本控制系统，可以帮助你管理代码的历史记录，协作开发，防止代码丢失。

## 2. 安装 Git
- 访问 [Git 官网](https://git-scm.com/) 下载并安装。
- 安装完成后，右键菜单或命令行输入 `git --version` 检查是否安装成功。

## 3. 基本配置
```bash
git config --global user.name "你的名字"
git config --global user.email "你的邮箱"
```

## 4. 初始化仓库
在你的项目文件夹下：
```bash
git init
```

## 5. 查看文件状态
```bash
git status
```

## 6. 添加文件到暂存区
```bash
git add 文件名
# 添加所有文件
git add .
```

## 7. 提交更改
```bash
git commit -m "提交说明"
```

## 8. 查看提交历史
```bash
git log
```

## 9. 关联远程仓库（如 GitHub）
```bash
git remote add origin 仓库地址
```

## 10. 推送代码到远程仓库
```bash
git push -u origin master
```

## 11. 拉取远程仓库代码
```bash
git pull origin master
```

## 12. 常见问题
- **忘记 add/commit？** 先 `git add`，再 `git commit`。
- **推送失败？** 检查网络、权限或分支名。

## 13. 更多学习资源
- [廖雪峰的 Git 教程](https://www.liaoxuefeng.com/wiki/896043488029600)
- [Pro Git 电子书](https://git-scm.com/book/zh/v2)

---

> 本手册适合初学者快速上手 Git，更多高级用法请参考官方文档。
