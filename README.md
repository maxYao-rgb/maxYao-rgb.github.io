# GitHub Pages 静态主页
这是一个零依赖的静态主页模板，可直接用于：

- 个人站点（`username.github.io`）
- 项目站点（`repo/docs` 分支目录）

## 使用方式

### 方式 A：个人站点（username.github.io）
1. 在 GitHub 新建公共仓库，名字必须是：`YOUR_USERNAME.github.io`。
2. 把本目录下所有文件上传到仓库根目录。
3. 几分钟后访问：https://YOUR_USERNAME.github.io

### 方式 B：项目站点（repo/docs）
1. 在任意仓库新建 `docs/` 目录，把本模板文件放入 `docs/`。
2. 仓库 **Settings → Pages**：
   - Source: `Deploy from a branch`
   - Branch: `main`，Folder: `/docs`
3. 保存后等几分钟，访问 `https://YOUR_USERNAME.github.io/REPO_NAME/`

> 可选：如果你使用 Jekyll，可创建 `_config.yml` 并指定主题；如果不想使用 Jekyll，可加一个 `.nojekyll` 文件。
