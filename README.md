# 厕所总部的网站
[![Deploy to Aliyun](https://github.com/ToiletMC/toiletmc.net/actions/workflows/deploy.yml/badge.svg)](https://github.com/ToiletMC/toiletmc.net/actions/workflows/deploy.yml)

网站构建使用 [Docusaurus 2](https://docusaurus.io/zh-CN/)，一个现代化的静态网站生成器。浏览我们的站点：[toiletmc.net](https://toiletmc.net)

## ❓ 如何贡献

小白教程：
1. 将本仓库 fork 到自己的 github 账号并下载文件到本地
2. 在文件夹内运行命令 `npm run start`
3. 编辑文件，浏览器转到 `localhost:3000` 实时预览页面
4. 完成所有编辑工作后运行 `npm run build`，测试是否构建通过
5. 将文件上传到自己仓库，然后向本仓库提交 pr

上面的步骤不一定全都要做，你也可以根据自己的经验来操作。

## ⚙️ 工作流程

当检测到 main 分支文件变化时，Github Action 会自动构建网站并完成部署。
