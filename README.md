# Look At My Eyes Support

Look At My Eyes 的纯静态介绍、技术支持和隐私政策网站，供 GitHub Pages 发布。无需构建工具、后端或外部 API。

## 本地预览

直接在浏览器中打开 `index.html`。页面间使用相对路径，`support.html` 和 `privacy.html` 也可单独打开。

## 发布前必须完成

1. 确认支持邮箱 `56202033@qq.com` 可以正常接收并处理用户来信。
2. 对照即将上传的 iOS App，确认隐私政策与 App Store Connect 中的 App 隐私问卷一致。若后来加入服务器、统计、账户或其他数据处理，先更新本政策。
3. 确认 App 图标 `assets/app-icon.png` 的使用权及内容适合对外发布。

## 发布到 GitHub Pages

本地目录已经是 Git 仓库，且 `origin` 指向 `https://github.com/hanyu040304/look-at-my-eyes-support.git`。确认 GitHub 上的仓库存在后，在终端运行：

```sh
cd /Users/hanyu/Desktop/look-at-my-eyes-support
git add .
git commit -m "Add support contact and Pages URLs"
git push origin main
```

若远程仓库尚未创建，先在 GitHub 登录 `hanyu040304`，新建公开仓库 `look-at-my-eyes-support`，不要自动添加 README 等文件，然后执行上述命令。在仓库 `Settings → Pages` 中选择 `Deploy from a branch`、`main`、`/ (root)` 并保存，等待 Pages 发布完成。

预期网址：

| App Store Connect 字段 | 网址 |
| --- | --- |
| 营销网址 | `https://hanyu040304.github.io/look-at-my-eyes-support/` |
| 技术支持网址 | `https://hanyu040304.github.io/look-at-my-eyes-support/support.html` |
| 隐私政策网址 | `https://hanyu040304.github.io/look-at-my-eyes-support/privacy.html` |

先用无痕窗口打开三个网址检查可访问性，再填入 App Store Connect。
