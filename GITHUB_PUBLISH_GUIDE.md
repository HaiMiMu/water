# 🚀 卡皮巴拉喝水小助手 — GitHub Pages 发布指南（小白版）

> **目标**：把你的使用说明页面变成一个在线网址，朋友打开浏览器就能看见
> 
> **网址格式**：`https://你的用户名.github.io/capybara-water-reminder/`

---

## 第一步：注册 GitHub 账号（免费，2分钟）

### 1.1 打开注册页面

打开浏览器，访问：
```
https://github.com/signup
```

### 1.2 填写信息

你会看到 4 个步骤：

| 步骤 | 填写内容 | 示例 |
|------|---------|------|
| 1 | 输入邮箱地址（用你常用的邮箱） | `yourname@qq.com` |
| 2 | 创建密码（至少 8 位，包含大小写和数字） | `Capybara2024!` |
| 3 | 创建用户名（就是你的网址前缀，建议简短） | `zhangsan` 或 `capybara2024` |
| 4 | 回答问题（验证你不是机器人） | 按图片选择 |

> 💡 **用户名很重要！** 你的网址就是 `https://用户名.github.io/...`，建议用字母+数字，不要太长

### 1.3 验证邮箱

1. 注册完成后，GitHub 会发一封邮件到你填的邮箱
2. 打开邮箱，找到 GitHub 发来的邮件，点击 **Verify email address**（验证邮箱地址）
3. 验证完成，账号就可以用了！

---

## 第二步：创建仓库（1分钟）

### 2.1 登录 GitHub

1. 打开 https://github.com
2. 点击右上角 **Sign in**（登录）
3. 输入你的用户名/邮箱和密码

### 2.2 创建新仓库

1. 登录后，点击页面右上角 **+** 号按钮
2. 在下拉菜单中选择 **New repository**（新建仓库）

   ![点击右上角的 + 号，然后选 New repository]

3. 在新页面填写：

   **Repository name**（仓库名称）：
   ```
   capybara-water-reminder
   ```
   > 💡 建议用这个英文名，不要用中文，因为 GitHub 的中文仓库名有时会出问题

   **Description**（描述，可选）：
   ```
   卡皮巴拉喝水小助手 - 桌面提醒工具
   ```

   **选择 Public**（公开）：
   - 点选 **Public**（这是免费的）
   - 不要选 Private（私有仓库需要付费）

   **勾选 Add a README file**：
   - 勾选这个选项（会默认创建一个 README 文件，方便后续操作）

4. 点击页面底部的绿色按钮 **Create repository**（创建仓库）

---

## 第三步：上传文件（3分钟）

### 3.1 准备要上传的文件

你需要上传这些文件（都在 `water-reminder-gh-pages` 文件夹里）：

- `index.html` — 使用说明网页
- `capybara-water-reminder.exe` — 程序文件（43MB，上传可能需要等一下）
- `screenshot-main1.png` — 截图
- `screenshot-main2.png` — 截图
- `screenshot-main3.png` — 截图
- `screenshot-calendar.png` — 截图
- `screenshot-detail.png` — 截图
- `screenshot-reminder.png` — 截图
- `README.md` — 仓库说明（可选，已经有默认的了）

### 3.2 开始上传

1. 在仓库页面，点击 **Add file**（添加文件）按钮
2. 选择 **Upload files**（上传文件）

   ![点击 Add file → Upload files]

3. 你会看到一个拖放区域，写着：
   ```
   Drag files here to add them to your repository
   或者 click to choose your files
   ```

4. **打开文件资源管理器**，找到这个文件夹：
   ```
   C:\Users\10270\Documents\kimi\workspace\water-reminder-gh-pages\
   ```

5. **选中所有文件**（按 Ctrl+A 全选），然后**拖到 GitHub 网页的上传区域**

6. 等待文件上传（注意：
   - 小的图片文件几秒钟就传完了
   - 大的 `capybara-water-reminder.exe`（43MB）可能需要 1-2 分钟，耐心等待）

7. 所有文件都显示在列表里后，在页面底部找到 **Commit changes**（提交更改）

8. 在第一个框里输入：
   ```
   Initial upload
   ```
   （这是提交说明，告诉你这次做了什么，随便写什么都可以）

9. 点击 **Commit changes**（提交更改）按钮

   ![点击绿色的 Commit changes 按钮]

10. 上传完成！你会回到仓库主页，看到所有文件都在列表里。

---

## 第四步：启用 GitHub Pages（最关键！3分钟）

### 4.1 进入设置页面

1. 在仓库页面，找到顶部一排菜单：
   - **Code**（代码）
   - **Issues**（问题）
   - **Pull requests**（拉取请求）
   - **Actions**（操作）
   - **Projects**（项目）
   - **Wiki**（百科）
   - **Security**（安全）
   - **Insights**（洞察）
   - **Settings**（设置） ← 点这个！

2. 点击 **Settings**（设置）

   ![点击顶部菜单的 Settings]

### 4.2 找到 Pages 设置

1. 进入 Settings 页面后，左侧有一列菜单
2. 往下滚动左侧菜单，找到 **Pages**（如果没有看到，继续往下找）

   ![左侧菜单往下找，找到 Pages]

3. 点击 **Pages**

### 4.3 启用 GitHub Pages

在 **Source**（源）部分，你会看到两个下拉框：

- 第一个下拉框：
  - 选择 **Deploy from a branch**（从分支部署）← 这个一般是默认的
  
- 第二个下拉框（Branch）：
  - 选择 **main**（或 master，取决于你创建的仓库）
  
- 第三个下拉框（Folder）：
  - 选择 **/(root)**（根目录）

然后点击 **Save**（保存）按钮

   ![选择 main 分支和 /(root) 目录，然后点 Save]

### 4.4 等待部署

1. 点击 Save 后，页面会刷新
2. 在页面顶部会出现一条提示：
   ```
   Your site is ready to be published at https://你的用户名.github.io/capybara-water-reminder/
   ```
   或者
   ```
   GitHub Pages source saved. Your site is being built.
   ```

3. **等待 1-5 分钟**（GitHub 在后台部署你的网站）

4. 刷新页面，如果看到网址变成绿色的：
   ```
   ✅ Your site is published at https://你的用户名.github.io/capybara-water-reminder/
   ```
   就说明成功了！

> ⏰ **如果超过 5 分钟还没变绿**，不要着急，多刷新几次，GitHub 有时候慢一点。

---

## 第五步：验证网站（2分钟）

### 5.1 打开网址

1. 点击 Settings → Pages 页面里显示的网址，或者手动输入：
   ```
   https://你的用户名.github.io/capybara-water-reminder/
   ```
   例如：`https://zhangsan.github.io/capybara-water-reminder/`

2. 等待页面加载

### 5.2 检查内容

确认能看到以下所有内容：
- [ ] 标题：🦫 卡皮巴拉喝水小助手
- [ ] 下载按钮：立即下载
- [ ] 功能介绍卡片（8个或10个）
- [ ] 系统要求
- [ ] 使用指南（步骤列表）
- [ ] 界面预览（6张截图）
- [ ] 常见问题
- [ ] 技术实现说明
- [ ] 项目结构

### 5.3 测试下载按钮

点击页面上的 **立即下载** 按钮，确认：
- 浏览器开始下载 `capybara-water-reminder.exe` 文件
- 或者弹出一个下载提示

> ⚠️ **如果下载按钮点了没反应**：可能是因为 GitHub Pages 对大文件下载有限制。这是正常的，解决方法是：把 EXE 放到 GitHub Releases 里下载（见下面的进阶部分）。

---

## 第六步：分享给朋友！🎉

现在你可以把网址分享给任何人：

```
https://你的用户名.github.io/capybara-water-reminder/
```

朋友只需要：
1. 在浏览器里打开这个网址
2. 点击 **立即下载**
3. 下载完成后双击运行

---

## 常见问题（FAQ）

### Q1: 网址打不开，显示 404 错误？

**原因**：
- GitHub Pages 还没部署完（刚保存后需要等 1-5 分钟）
- 仓库名称和网址不匹配

**解决方法**：
1. 确认仓库名称是 `capybara-water-reminder`（和你输入的网址一致）
2. 确认 Settings → Pages 里选择了 **main** 分支和 **/(root)**
3. 等待 5 分钟后再刷新
4. 如果还是不行，检查仓库里有没有 `index.html` 文件（文件名必须完全匹配，不能是 Index.html 或 index.HTML）

### Q2: 页面打开了，但截图显示不出来？

**原因**：截图文件名和 HTML 里的不一致，或者截图没上传到仓库

**解决方法**：
1. 在仓库页面检查根目录下是否有这些文件：
   - `screenshot-main1.png`
   - `screenshot-main2.png`
   - `screenshot-main3.png`
   - `screenshot-calendar.png`
   - `screenshot-detail.png`
   - `screenshot-reminder.png`

2. 如果缺少某个截图，重新上传（见下面的"如何更新文件"）

3. 检查文件名是否完全一致（区分大小写！）

### Q3: 下载按钮点了没反应，或者下载的文件打不开？

**原因**：GitHub Pages 对 43MB 的 EXE 文件下载支持不太好

**解决方法（推荐）**：用 GitHub Releases 分发 EXE

#### 如何用 GitHub Releases 分发 EXE（更稳定）

1. 在仓库页面，点击右侧的 **Releases**（如果没有看到，先点击 **Code** 标签）

2. 点击 **Create a new release**（创建新发布）

3. 填写发布信息：
   - **Choose a tag**（标签）：点击输入框，输入 `v1.0`，然后点击 **Create new tag: v1.0**
   - **Release title**（发布标题）：`卡皮巴拉喝水小助手 v1.0`
   - **Describe this release**（描述）：`第一个正式版本`

4. 上传 EXE 文件：
   - 页面底部有个区域写着 **Attach binaries by dropping them here or selecting them.**
   - 把 `capybara-water-reminder.exe` 文件拖到那里
   - 或者点击 **selecting them** 选择文件

5. 点击页面底部的 **Publish release**（发布）

6. 发布完成后，会得到一个下载链接：
   ```
   https://github.com/你的用户名/capybara-water-reminder/releases/download/v1.0/capybara-water-reminder.exe
   ```

7. 把这个链接复制下来，修改 `index.html` 文件里的下载按钮：
   - 在仓库页面点击 `index.html`
   - 点击右上角铅笔图标 ✏️（Edit this file）
   - 找到这一行：
     ```html
     <a href="capybara-water-reminder.exe" class="download-btn">立即下载</a>
     ```
   - 改成：
     ```html
     <a href="https://github.com/你的用户名/capybara-water-reminder/releases/download/v1.0/capybara-water-reminder.exe" class="download-btn">立即下载</a>
     ```
   - 页面底部填写 Commit 信息：`Update download link`
   - 点击 **Commit changes**

8. 等待 1-2 分钟，刷新你的 Pages 网址，测试下载按钮

> 💡 **推荐的做法**：Pages 用来展示网页（HTML + 截图），Releases 用来分发 EXE。这样既美观又稳定！

### Q4: 如何更新文件？（比如修改了说明或换了截图）

**方法**：
1. 在仓库页面找到要修改的文件
2. 点击文件名进入文件页面
3. 点击右上角 ✏️ 铅笔图标（Edit this file）
4. 修改内容（如果是 HTML，可以直接在网页里编辑）
5. 页面底部填写 Commit 信息，比如：`Update screenshots`
6. 点击 **Commit changes**
7. 等待 1-2 分钟，GitHub Pages 会自动更新

### Q5: 用户名可以改吗？

可以，但改了之后网址也会变。建议一开始就想好用户名。

修改方法：
1. 点击右上角头像 → **Settings**
2. 左侧选择 **Account**
3. 点击 **Change username**

---

## 总结

| 步骤 | 操作 | 时间 |
|------|------|------|
| 1 | 注册 GitHub 账号 | 2分钟 |
| 2 | 创建仓库 `capybara-water-reminder` | 1分钟 |
| 3 | 上传所有文件（拖拽） | 3-5分钟 |
| 4 | 启用 GitHub Pages（Settings → Pages） | 1分钟 |
| 5 | 等待部署 | 1-5分钟 |
| 6 | 验证网址和下载 | 2分钟 |
| **合计** | | **10-16分钟** |

完成后你就拥有一个永久免费的在线展示页面！🦫

---

## 需要帮助的截图位置说明

如果你在 GitHub 网页上找不到某个按钮，以下是关键按钮的位置描述：

- **右上角的 + 号**：在 GitHub 页面最顶部黑色/白色导航栏的右侧
- **Settings**：在仓库页面顶部一排标签的最右边
- **Pages**：在 Settings 页面左侧菜单的下方（可能需要滚动才能看到）
- **Add file → Upload files**：在仓库代码列表页面的右上方
- **Commit changes**：在上传文件页面的底部，绿色按钮

如果还是找不到，告诉我你在哪个步骤卡住了，我可以给你更具体的指引！
