# deploy-demo-vue3
[GitHub预览](https://hgf0419.github.io/deploy-demo-vue3/)
[云服务器预览](http://116.62.129.253/deploy-demo-vue3/)

## 简介
本项目是一个vue3部署项目的演示demo，使用 GitHub Actions 自动部署到 GitHub Pages 和 云服务器。

## 部署
1. 提供deploy.cml文件
```
- 在.github/workflows 目录下创建一个deploy.yml文件,并且编写部署脚本。

- 或者点击远程仓库的 *setting面板*，点击*pages功能*，在 *Build and deployment* 处选择github actions ,最后选择静态文件模板后会在线创建一个deploy.yml文件，根据需要修改一些信息后提交。
```
2. 服务器准备
```
- nginx配置文件和启动。
- 创建对应目录，用于存放代码。
- 在云服务器上创建一个SSH密钥对，用于连接服务器。
```

3. 在项目代码仓库中设置secrets，用于存储阿里云服务器的SSH密钥。

4. 推送代码到 GitHub 仓库。

3. 等待 GitHub Actions 完成部署。

## 参考
[Vite项目部署](https://cn.vitejs.dev/guide/static-deploy)





