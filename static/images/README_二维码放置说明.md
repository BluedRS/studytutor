# 📱 微信二维码图片放置说明

## 请将你的微信二维码图片放在这里

### 文件要求

- **文件名**：`wechat-qr.png`
- **格式**：PNG（推荐）或 JPG
- **尺寸**：建议 300x300px 或更大
- **大小**：< 200KB

### 如何获取微信二维码

**方法 1：微信名片二维码**
1. 打开微信 → 我 → 点击顶部头像区域
2. 进入"我的二维码"
3. 保存图片到电脑
4. 重命名为 `wechat-qr.png`
5. 放到这个目录（`static/images/`）

**方法 2：草料二维码生成**
1. 访问 https://cli.im/url
2. 输入微信号：R1015956206
3. 点击"生成二维码"
4. 下载 PNG 格式
5. 重命名为 `wechat-qr.png`
6. 放到这个目录

### 放置后效果

网站预览页面的二维码位置会自动显示你的微信二维码图片。

如果图片不显示，检查：
1. 文件名是否正确：`wechat-qr.png`
2. 文件位置是否正确：`static/images/wechat-qr.png`
3. 刷新浏览器：Cmd+R 或 Ctrl+R

---

**当前目录：**
```
/Users/ainiuma/Documents/openclaw/state/workspace/留学生商科辅导网站/static/images/
```

**放置后刷新预览：**
```
http://localhost:8080/index.html
```
