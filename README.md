# 个人博客网站

这是一个使用Hugo框架搭建的个人博客网站。

## 项目结构

```
.
├── categories/     # 博客分类目录
├── css/           # 样式文件
├── en/            # 英文版本内容
├── fonts/         # 字体文件
├── icons/         # 网站图标
├── images/        # 图片资源
├── page/          # 页面模板
├── posts/         # 博客文章
│   ├── myfirstblog/
│   ├── mysecondblog/
│   └── mythirdblog/
└── tags/          # 博客标签
```

## 技术特点

- 基于Hugo静态网站生成器
- 响应式设计，支持移动端访问
- 支持暗色/亮色主题切换
- 集成社交媒体分享功能
- SEO优化
- 多语言支持（中文/英文）

## 本地开发

1. 安装Hugo
   ```bash
   # Windows
   choco install hugo -confirm
   
   # macOS
   brew install hugo
   ```

2. 克隆项目
   ```bash
   git clone [项目地址]
   cd [项目目录]
   ```

3. 启动本地服务器
   ```bash
   hugo server -D
   ```

4. 访问 `http://localhost:1313` 查看网站

## 部署

1. 生成静态文件
   ```bash
   hugo
   ```

2. 部署到GitHub Pages
   - 将生成的`public`目录内容推送到GitHub仓库
   - 在仓库设置中启用GitHub Pages

## 博客写作

1. 创建新文章
   ```bash
   hugo new posts/文章名称/index.md
   ```

2. 编辑文章
   - 使用Markdown格式编写
   - 支持图片、代码块等富文本内容
   - 可以添加标签和分类

## 主题定制

- 样式文件位于`css`目录
- 图标资源位于`icons`目录
- 字体文件位于`fonts`目录

## 许可证

[MIT License](LICENSE)