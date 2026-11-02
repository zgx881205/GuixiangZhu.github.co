# Guixiang Zhu 的个人主页

基于 [HugoBlox Academic CV](https://hugoblox.com/templates/academic-cv) 的中文个人主页，保留模板的个人简介组件、响应式布局、深浅色主题和站内搜索。

**主页：<https://zgx881205.github.io/GuixiangZhu.github.co/>**

## 修改个人资料

| 内容 | 文件 |
| --- | --- |
| 姓名、简介、教育经历、社交链接 | `data/authors/me.yaml` |
| 头像 | `assets/media/authors/me.png` |
| 首页区块 | `content/_index.md` |
| 导航 | `config/_default/menus.yaml` |
| 网站名称、介绍、主题 | `config/_default/params.yaml` |
| 网站地址与默认语言 | `config/_default/hugo.yaml`、`config/_default/languages.yaml` |

首页目前使用 GitHub 公开姓名和头像。模板中的虚构人物、学历、论文和工作经历不在网站上发布；示例内容保留在源码中。

仓库名 `GuixiangZhu.github.co` 对应项目网站路径 `/GuixiangZhu.github.co/`，不是独立的 `.co` 域名。GitHub Actions 构建时从 Pages 设置读取完整网站地址，确保导航、样式和搜索使用正确的路径前缀。

要启用论文、项目、文章、课程或演讲页面，先替换对应 `content/` 目录里的示例内容，再移除该目录 `_index.md` 中的 `build` 与 `cascade.build` 禁用规则，并在首页及导航添加入口。`content/experience.md` 也有独立的禁用规则。示例简历保存在 `examples/resume.pdf`，不会发布；上传自己的简历至 `static/uploads/` 后再添加下载按钮。

## 自动发布

首次设置：进入 [Settings → Pages](https://github.com/zgx881205/GuixiangZhu.github.co/settings/pages)，将 **Source** 设为 **GitHub Actions**。

此后，推送至 `main` 会自动执行 `.github/workflows/deploy.yml`：构建 Hugo、生成 Pagefind 搜索索引、上传 `public/`，再发布到 GitHub Pages。PR 仅构建校验。部署结果见 [Actions](https://github.com/zgx881205/GuixiangZhu.github.co/actions)。

构建使用 Hugo Extended **0.162.0**、Node.js **22**、pnpm **10.14.0**，依赖按 `pnpm-lock.yaml` 安装。免费配置不需要 PAT、HugoBlox 许可证或手动添加部署 secret；GitHub 为 Actions 提供临时凭证。

## 本地预览

安装与 CI 一致的 Hugo Extended、Node.js、pnpm，以及 Go 后：

```sh
pnpm install --frozen-lockfile
pnpm dev
```

生产构建及搜索索引：

```sh
pnpm build
```

如果 Go 模块直接下载受网络限制，可将 `HUGO_MODULE_PROXY` 设置为可访问的 Go 模块代理，例如 `https://proxy.golang.org,direct`。

## 认证与公开内容

网站是公开静态站点，访客无需登录。组件、请求流程、`GITHUB_TOKEN`、OIDC、凭证清理及辅助工作流权限的代码说明见 [docs/AUTHENTICATION.md](docs/AUTHENTICATION.md)。

不要把密码、令牌、私钥或未公开资料写入网站文件。`public/` 及 Pagefind 索引中的内容都能被访客读取。

模板代码的 MIT 许可证保留于 [LICENSE.md](LICENSE.md)。页脚保留 HugoBlox attribution。
