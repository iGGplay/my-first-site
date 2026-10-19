# my-first-site

This is a work I study to use the github

## 用 GitHub 创建并发布简单网页

`以下步骤是电脑网页端的，手机端不适用，因为有些步骤没有操作对象`

1. **创建仓库**：在 GitHub 点击右上角 **＋ → New repository**，填写仓库名称，点Create repository创建。
*注意：仓库就是存放项目文件的地方。*

2. **添加网页文件**：进入仓库，选择 **Add file → Create new file**，文件名填写 `index.html`，写入网页内容，然后点击 **Commit changes** 保存。
*注意：`index.html` 是网页入口文件；提交说明尽量写清楚修改了什么。*

3. **确认仓库可用于 Pages**：打开 **Settings → Pages**。如果看到“Upgrade or make this repository public to enable Pages”，可将仓库改为 **Public（公开）**，或升级账户方案。
*注意：公开仓库后，任何人都能查看其中的文件；不要放入密码、密钥或隐私内容。GitHub 手机 App 通常没有仓库设置页面，找不到 Settings 时用电脑浏览器操作。*

4. **设置发布来源**：在 Pages 页面选择 **Deploy from a branch**，分支选 `main`，目录选 `/(root)`，然后点击 **Save**。
*注意：`index.html` 应位于仓库最外层，也就是根目录。*

5. **打开网页**：等待 Pages 发布完成，再从 Pages 页面打开显示的网址。
*注意：首次发布可能需要等待几分钟。*

6. **更新网页**：以后编辑 `index.html` 并提交更改，等待发布完成后，网站就会显示更新后的内容。
