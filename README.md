# 弹跳球工坊 BounceCode Workshop

## 🚀 快速部署指南

### 方法一：GitHub Pages（推荐，免费）

1. **创建 GitHub 账号**（如果没有）
   - 访问 https://github.com 注册

2. **创建新仓库**
   - 点击右上角 "+" → "New repository"
   - 仓库名填：`bounce-workshop` 或任意名称
   - 选择 "Public"（公开）
   - 点击 "Create repository"

3. **上传文件**
   - 在仓库页面点击 "uploading an existing file"
   - 把以下文件都拖进去上传：
     - `index.html`
     - `trc20-qr.jpg` （你的TRC20二维码）
     - `erc20-qr.jpg` （你的ERC20二维码）
   - 点击 "Commit changes"

4. **启用 GitHub Pages**
   - 仓库页面 → Settings → Pages
   - Source 选择 "Deploy from a branch"
   - Branch 选择 "main" → "/ (root)"
   - 点击 "Save"

5. **访问你的网站**
   - 等待 1-2 分钟部署
   - 访问：`https://你的用户名.github.io/bounce-workshop/`

---

### 方法二：Vercel（免费，更快）

1. 访问 https://vercel.com
2. 用 GitHub 登录
3. 点击 "New Project"
4. 导入你的仓库
5. 一键部署
6. 获得免费域名：`xxx.vercel.app`

---

### 方法三：Netlify（免费）

1. 访问 https://netlify.com
2. 拖拽整个文件夹到首页
3. 立即获得网址

---

## 📁 需要上传的文件

```
bounce-workshop/
├── index.html        # 网页主文件
├── trc20-qr.jpg      # TRC20 收款二维码 (从 C:\Users\Administrator\Desktop\TRC20.jpg 复制)
└── erc20-qr.jpg      # ERC20 收款二维码 (从 D:\1\ERC20.jpg 复制)
```

### 复制二维码文件

打开命令提示符或PowerShell，运行：

```powershell
# 复制TRC20二维码
copy "C:\Users\Administrator\Desktop\TRC20.jpg" "C:\Users\Administrator\.qclaw\workspace\bounce-workshop\trc20-qr.jpg"

# 复制ERC20二维码
copy "D:\1\ERC20.jpg" "C:\Users\Administrator\.qclaw\workspace\bounce-workshop\erc20-qr.jpg"
```

或者手动复制：
1. 打开 `C:\Users\Administrator\Desktop\TRC20.jpg`
2. 复制到 `C:\Users\Administrator\.qclaw\workspace\bounce-workshop\`
3. 重命名为 `trc20-qr.jpg`
4. 同样操作 ERC20.jpg

---

## ✅ 已配置信息

| 项目 | 内容 |
|------|------|
| TRC20 地址 | TWWTcEYQDNdPwMupesjgeAajUAgq76CXKh |
| ERC20 地址 | 0x36dedc4d220eb67c5ba5a8f3aa5eda9d91c9aa13 |
| 网站名称 | 弹跳球工坊 |

---

## ⚙️ 如需修改

### 修改联系邮箱
找到这行代码，改成你的邮箱：
```html
<a href="mailto:your-email@example.com" class="contact-email">your-email@example.com</a>
```

### 修改产品价格
找到对应的 `product-price` 和 `onclick="openModal(..., 价格)"` 两处都要改。

### 修改产品信息
修改产品卡片中的：
- 产品名称
- 产品描述
- 标签

---

## 📱 功能特点

✅ 响应式设计（手机/平板/电脑都能看）
✅ 6个真实弹跳球动画演示（Canvas实现）
✅ USDT 双网络支付（TRC20 + ERC20）
✅ 网络切换按钮
✅ 一键复制钱包地址
✅ 深色科技风格
✅ 无需后端，纯静态部署
✅ 完全免费托管

---

## ❓ 常见问题

**Q: 二维码不显示？**
A: 确保 `trc20-qr.jpg` 和 `erc20-qr.jpg` 与 `index.html` 在同一目录。

**Q: 如何修改价格？**
A: 找到对应的 `product-price` 和 `onclick="openModal(..., 价格)"` 两处都要改。

**Q: 如何测试？**
A: 直接双击 `index.html` 在浏览器预览。

---

## 📞 需要帮助？

如果你在部署过程中遇到问题，随时问我！

---

祝你的弹跳球代码大卖！🚀💰
