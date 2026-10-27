# Vicky 的个人主页

一个无需安装依赖的静态个人介绍网页，包含关于我、项目和 GitHub 联系入口，适配手机与电脑。

## 查看效果

1. 切换到 `codex/personal-introduction` 分支（合并 PR 后也可在 `main`）。
2. 点击绿色 **Code → Download ZIP**，下载并解压。
3. 双击 `index.html`，在浏览器中查看网页。

GitHub 文件页显示的是源代码，不会直接渲染网页。

## 修改内容

用文本编辑器打开 `index.html`：

- 搜索 `你好，我是 Vicky` 修改姓名和标题。
- 在 `id="about"` 所在区块修改自我介绍。
- 在 `id="projects"` 所在区块修改项目标题与链接。
- 在 `id="contact"` 所在区块修改联系入口。
- 在文件顶部的 `<style>` 中调整颜色和布局。

当前个人介绍包含明确标注的示例文字；发布前请替换为自己的内容。联系入口使用公开 GitHub 主页，不包含私人邮箱。

## 查看修改记录

- 打开 Pull requests，选择本次 PR。
- **Files changed**：查看新增和修改的内容，绿色表示新增。
- **Commits**：查看每次保存的记录。
- 确认满意后可点击 **Merge pull request → Confirm merge**，合并到主分支。

## 可选：发布到 GitHub Pages

合并 PR 后，在仓库 **Settings → Pages → Build and deployment** 中选择 **Deploy from a branch**，分支选 `main`，目录选 `/ (root)`，保存。等待部署完成后，使用 Pages 页面显示的网址访问。若仓库或组织限制了 Pages，请以 GitHub 的提示为准。

## 技术

原生 HTML 和 CSS，无 JavaScript、外部字体、追踪脚本或构建步骤。
