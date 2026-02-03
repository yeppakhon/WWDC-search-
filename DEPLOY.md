# 部署指南

由于网络连接问题，自动推送失败。请在终端（Terminal）中运行以下命令来完成部署：

1. **进入云端版本目录**
   ```bash
   cd /Users/eppakhon/Desktop/wwdc-knowledge-base/cloud-version
   ```

2. **强制推送代码到 GitHub**
   （注意：这会覆盖仓库中的初始 README，这是正常的）
   ```bash
   git push -u origin main --force
   ```

3. **如果提示输入密码**
   - 请输入您的 GitHub 个人访问令牌 (Personal Access Token)
   - 或者配置 SSH Key

4. **开启 GitHub Pages**
   - 打开仓库页面: https://github.com/yeppakhon/WWDC-search-/settings/pages
   - Source 选择 `Deploy from a branch`
   - Branch 选择 `main` / `(root)`
   - 点击 Save

完成！您的网站将在几分钟后上线。
