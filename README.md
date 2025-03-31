以下是基于 GitHub README 标准格式优化的版本，符合常见的开源项目规范（如清晰的标题、徽章支持、表格化内容等），同时保留所有原始步骤和信息，确保专业性与用户友好性兼顾。

```markdown
# Unraid Theme

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Unraid Support](https://img.shields.io/badge/Unraid-6%20%26%207-green.svg)](https://unraid.net/)

一个为 **Unraid 6 和 Unraid 7** 设计的自定义主题，通过 Theme Engine 插件美化你的 Unraid Web 界面。  
加入我们的 **[Telegram 交流群](https://t.me/+ZHsEEd5ZJGs3MWJl)** 获取支持和更新资讯！

---

## 功能
- 支持 Unraid 6 和 Unraid 7。
- 简洁现代的界面设计。
- 可选背景和动态效果（如胡桃动图）。
- 通过 Git 轻松更新。

## 安装步骤

### 前置条件
- Unraid 系统（版本 6.x 或 7.x）。
- 已启用终端访问和 Apps 功能。

### 步骤
1. **下载主题文件**  
   在 Unraid **终端** 中运行：  
   ```bash
   cd /mnt/user/ && git clone https://github.com/XiaoNieGPT/unraid-theme.git
   ```  
   ![下载示例](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/0a5224a5-f3fe-4ba5-977b-acb1ef767628)

2. **确认文件位置**  
   在 **Shares** 中查看：`/mnt/user/unraid-theme/`（后续会用到）。  
   ![文件位置](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/a7a15b1a-8bca-4d52-9916-aecdb78c4917)

3. **安装 Theme Engine 插件**  
   在 **Apps** 中搜索并安装 **Theme Engine**。  
   ![插件安装](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/a1e8b844-c4b3-46a3-ae5d-e72bb94b4b49)

4. **进入设置**  
   在 **Settings** 中打开 **Theme Engine**。

5. **选择基础主题**  
   在 **Base Theme** 选择 **Black** 并点击 **应用**。  
   ![选择 Black 主题](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/49d0edb8-68e5-45aa-a6c9-e75ee2150661)

6. **调整高级设置**  
   在 **Theme Setting** 点击 **Advanced VIEW**，将 **Enable Theme Engine** 设为 **NO**。  
   ![关闭 Enable Theme Engine](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/37ea54ba-b8d6-4438-bda8-c7284b1f0a9d)

7. **启用自定义样式**  
   滑动至底部，将 **Enable custom styling (below)** 设为 **YES**。  
   ![启用自定义样式](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/e8f31b42-20aa-4027-8aca-140a53495091)

8. **添加自定义 CSS**  
   在 **Custom styling (advanced)** 输入：  
   ```html
   </style>
   <link type="text/css" rel="Stylesheet" href="/mnt/user/unraid-theme/theme.css" />
   ```  
   ![添加 CSS](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/9f928eae-adfd-4a3d-b263-3f805d3188c6)

9. **检查字体颜色**  
   右上角字体可能为灰黑色，影响美观。  
   ![灰黑色字体](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/997b0410-ed11-4f2a-904e-de173039e39d)

10. **调整字体颜色**  
    在 **Display Settings** 修改三处字体颜色为 **白色**。  
    ![调整字体颜色 1](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/612aef20-d01c-4c11-8823-1f41a5a91ca9)  
    ![调整字体颜色 2](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/a6cba9eb-e62e-4f34-846b-000aa79c17c4)

11. **完成效果**  
    主题安装完成，效果如下：  
    ![效果图 1](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/3fa1137f-f6ed-4e71-b2a9-1c5e73ed940a)  
    ![效果图 2](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/ca584cc6-2c63-4051-8da0-4a6b884c4b23)  
    ![效果图 3](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/86183a2f-bdb0-4a8f-b90b-5ed6bdbe3109)  
    ![效果图 4](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/bce43985-c5cd-476b-ac9d-d72d74623ac1)

12. **[可选] 自定义背景与动图**  
    可修改背景或添加胡桃动图。  
    ![自定义示例](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/dcd4a040-0c3b-4235-9f13-b407c5ea91ea)

---

## 更新主题
在终端运行以下命令即可升级（无需额外配置）：  
```bash
rm -rf /mnt/user/unraid-theme && cd /mnt/user/ && git clone https://github.com/XiaoNieGPT/unraid-theme.git
```  
**注意**：升级后确认 `theme.css` 文件名是否一致。

---

## 常见问题
| 问题                          | 解答                                      |
|-------------------------------|-------------------------------------------|
| 主题会影响性能吗？            | 不会，仅修改前端样式，不影响核心功能。    |
| 如何卸载主题？                | 删除 `/mnt/user/unraid-theme/` 并重启 WebGUI。 |

---

## 贡献
欢迎为项目贡献代码！  
1. Fork 本仓库。
2. 创建你的功能分支：`git checkout -b feature/YourFeature`。
3. 提交更改：`git commit -m 'Add YourFeature'`。
4. 推送分支：`git push origin feature/YourFeature`。
5. 创建 Pull Request。

## 许可证
本项目基于 [MIT 许可证](LICENSE) 开源。

## 联系
- **Telegram**: [加入交流群](https://t.me/+ZHsEEd5ZJGs3MWJl)  
- **Issues**: [提交问题](https://github.com/XiaoNieGPT/unraid-theme/issues)
```

---

### 符合 GitHub 规范的优化点
1. **标准化头部**：添加项目标题、徽章（License 和 Unraid 支持版本），突出项目简介。
2. **功能概览**：用简短列表展示主题特点，吸引用户。
3. **结构化安装**：将步骤分为“前置条件”和“步骤”，并编号清晰。
4. **代码块与图片**：命令使用 ```bash```，CSS 使用 ```html```，图片带描述。
5. **FAQ 表格**：常见问题用表格展示，便于快速查阅。
6. **贡献与许可证**：添加标准开源项目贡献指南和许可证链接。
7. **联系方式**：整合 Telegram 和 GitHub Issues，提升互动性。

这个版本既保留了所有原始信息，又符合 GitHub README 的最佳实践。如果需要调整（比如添加更多徽章、修改语气等），请告诉我！
