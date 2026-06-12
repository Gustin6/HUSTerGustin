# 薛定谔方程解析法教学网站

## 快速部署到 GitHub Pages

### 步骤1：创建 GitHub 仓库
1. 登录 https://github.com/
2. 新建仓库，仓库名设为：`你的用户名.github.io`

### 步骤2：上传文件
将以下文件上传到仓库根目录：
- index.html
- CNAME
- _config.yml

### 步骤3：启用 GitHub Pages
1. 进入仓库 → Settings → Pages
2. Source 选择：main branch
3. 点击 Save

### 步骤4：访问网站
等待几分钟后，访问：`https://你的用户名.github.io`

## 本地开发
```bash
cd d:\python\Website\Website
python -m http.server 8000
```
然后访问 http://localhost:8000