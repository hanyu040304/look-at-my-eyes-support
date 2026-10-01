# Look At My Eyes Support

Look At My Eyes 的纯静态介绍、技术支持和隐私政策网站，供 GitHub Pages 发布。无需构建工具、后端或外部 API。

## 本地预览

直接在浏览器中打开 `index.html`。页面间使用相对路径，`support.html` 和 `privacy.html` 也可单独打开。

## 发布前必须完成

1. 将 `support.html` 和 `privacy.html` 中所有 `[SUPPORT_EMAIL]` 替换为真实且有人处理的支持邮箱。替换后检查实际页面，不要发布占位符。
2. 对照即将上传的 iOS App，确认隐私政策与 App Store Connect 中的 App 隐私问卷一致。若后来加入服务器、统计、账户或其他数据处理，先更新本政策。
3. 确认 App 图标 `assets/app-icon.png` 的使用权及内容适合对外发布。

## 发布到 GitHub Pages

在 GitHub 网页上新建公开仓库 `look-at-my-eyes-support`，不要勾选自动生成 README、`.gitignore` 或 License。确认当前目录内容后，在终端运行：

```sh
cd /Users/hanyu/Desktop/look-at-my-eyes-support
git init
git branch -M main
git add .
git commit -m "Create Look At My Eyes support site"
git remote add origin https://github.com/YOUR_USERNAME/look-at-my-eyes-support.git
git push -u origin main
```

将 `YOUR_USERNAME` 换成实际 GitHub 用户名。在仓库 `Settings → Pages` 中选择 `Deploy from a branch`、`main`、`/ (root)` 并保存，等待 Pages 发布完成。

预期网址：

| App Store Connect 字段 | 网址 |
| --- | --- |
| 营销网址 | `https://YOUR_USERNAME.github.io/look-at-my-eyes-support/` |
| 技术支持网址 | `https://YOUR_USERNAME.github.io/look-at-my-eyes-support/support.html` |
| 隐私政策网址 | `https://YOUR_USERNAME.github.io/look-at-my-eyes-support/privacy.html` |

将网址中的 `YOUR_USERNAME` 换成真实用户名，并先用无痕窗口打开三个网址检查可访问性，再填入 App Store Connect。
