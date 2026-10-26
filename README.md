# Virtual Company 官方宣传网站

AI 员工 × 共享专业人才，让创新拥有一支随时就绪的团队。

## 网站内容

- 人机协同研发模式介绍
- 嵌入式 / MCU / Linux / IoT / 电机控制 / 边缘 AI / PCB 设计技术服务
- 需求 → 能力组织 → 研发验证 → 成果交付
- 未来业务方向预留
- 商务咨询电话：**17734515680**

## 技术实现

零依赖静态站点：`index.html` + `favicon.svg`，原生 CSS/JavaScript，自适应桌面与手机浏览器，支持动画减弱偏好。不依赖服务器、数据库、构建工具或付费服务。

## 本地预览

直接使用浏览器打开 `index.html` 即可。也可以使用任意静态文件服务器运行。

## GitHub Pages 发布

> 注意：当前仓库最初为 **private**。普通 GitHub Free 个人账户的私有仓库通常不能直接使用 GitHub Pages；请先确认账户和仓库发布权限，必要时将仓库设为 Public。

1. 在 GitHub 仓库点击 **Settings → Pages**。
2. 在 **Build and deployment** 中选择 **Deploy from a branch**。
3. 选择分支 `main`、目录 `/ (root)` 并点击 **Save**。
4. 发布完成后使用：**https://shengqiujin333.github.io/VirtualCompany/**

无需额外配置 GitHub Actions 工作流，推送到 `main` 后会自动更新部署。

## 修改指南

- 主视觉、页面结构和文案：修改 `index.html`
- 主题色：修改 CSS 开头的 `:root` 变量
- 电话联系方式：搜索 `17734515680`
- 未来业务板块：找到 `id="future"` 区域后添加卡片

## 说明

页面中的 AI 能力、共享员工和未来业务均以业务模式与研发方向表达；未来方向明确标为规划，不暗示已交付的具体案例或既有客户。无虚构销量、合作伙伴和资质。

© Virtual Company.
