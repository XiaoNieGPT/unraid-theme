
---

# Unraid Theme

这是一个为 **Unraid 6 和 Unraid 7** 设计的自定义主题，支持通过 Theme Engine 插件轻松美化你的 Unraid 界面。  
加入我们的 **[Telegram 交流群](https://t.me/+ZHsEEd5ZJGs3MWJl)** 获取帮助和最新资讯！

---

## 安装步骤

### 1. 下载主题文件
在 Unraid 的 **终端** 中运行以下命令：  
```bash
cd /mnt/user/ && git clone https://github.com/XiaoNieGPT/unraid-theme.git
```  
![下载示例](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/0a5224a5-f3fe-4ba5-977b-acb1ef767628)

### 2. 确认文件位置
下载完成后，在 **Shares** 中可以看到文件夹：  
- 文件路径：`/mnt/user/unraid-theme/`  
- 后续步骤会用到此路径。  
![文件位置](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/a7a15b1a-8bca-4d52-9916-aecdb78c4917)

### 3. 安装 Theme Engine 插件
在 **Apps** 页面搜索并安装 **Theme Engine** 插件。  
![插件安装](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/a1e8b844-c4b3-46a3-ae5d-e72bb94b4b49)

### 4. 打开 Theme Engine 设置
进入 **Settings（设置）**，找到并点击 **Theme Engine**。  

### 5. 设置基础主题
在 **Base Theme** 中选择 **Black 主题**，然后点击 **应用**。  
![选择 Black 主题](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/49d0edb8-68e5-45aa-a6c9-e75ee2150661)

### 6. 调整高级设置
在 **Theme Setting** 中：  
- 点击 **Advanced VIEW**。  
- 将 **Enable Theme Engine** 改为 **NO**。  
![关闭 Enable Theme Engine](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/37ea54ba-b8d6-4438-bda8-c7284b1f0a9d)

### 7. 启用自定义样式
拉到页面底部，将 **Enable custom styling (below)** 改为 **YES**。  
![启用自定义样式](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/e8f31b42-20aa-4027-8aca-140a53495091)

### 8. 添加自定义 CSS
在 **Custom styling (advanced)** 输入以下代码：  
```html
</style>
<link type="text/css" rel="Stylesheet" href="/mnt/user/unraid-theme/theme.css" />
```  
![添加 CSS](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/9f928eae-adfd-4a3d-b263-3f805d3188c6)

### 9. 检查字体颜色
此时右上角字体可能显示为灰黑色，影响美观。  
![灰黑色字体](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/997b0410-ed11-4f2a-904e-de173039e39d)

### 10. 修改字体颜色
进入 **Display Settings（显示设置）**，调整以下三处：  
- 将字体颜色改为 **白色**。  
![调整字体颜色 1](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/612aef20-d01c-4c11-8823-1f41a5a91ca9)  
![调整字体颜色 2](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/a6cba9eb-e62e-4f34-846b-000aa79c17c4)

### 11. 查看效果
主题安装完成！以下是效果预览：  
![效果图 ilàs1](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/3fa1137f-f6ed-4e71-b2a9-1c5e73ed940a)  
![效果图 2](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/ca584cc6-2c63-4051-8da0-4a6b884c4b23)  
![效果图 3](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/86183a2f-bdb0-4a8f-b90b-5ed6bdbe3109)  
![效果图 4](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/bce43985-c5cd-476b-ac9d-d72d74623ac1)

### 12. 【可选】自定义背景与动图
可根据需要修改背景或添加胡桃动图：  
![自定义示例](https://github.com/XiaoNieGPT/unraid-theme/assets/22927944/dcd4a040-0c3b-4235-9f13-b407c5ea91ea)

---

## 升级主题
要更新主题，只需在终端运行以下命令（无需额外配置）：  
```bash
rm -rf /mnt/user/unraid-theme && cd /mnt/user/ && git clone https://github.com/XiaoNieGPT/unraid-theme.git
```  
**注意**：升级后请确认 `theme.css` 文件名是否一致。

---

