# Music-Lovers-Crossing  爱乐评友会 
爱乐评友会，用一个HTML和excel，创建可本地播放的专属歌单，分享它，收集别人的歌单。Music Lovers Crossing, Use a html and excel to create a personalized playlist that can be played locally, share it, and collect others' playlists.


创建、分享专属音乐歌单，管理本地音乐，在本地进行播放。
Create, share personalized music playlists, manage local music, and play it locally.
## 简介
<img width="2356" height="1175" alt="2026-03-06 20 59 26" src="https://github.com/user-attachments/assets/2a3e5a12-ccfe-435d-8ed6-928ea098c1fe" />

Music Lovers Crossing（爱乐评友会）是一个优雅的本地音乐管理网页应用，支持导入包含丰富元数据的 Excel 歌单，匹配本地音乐文件并进行播放，同时展示 AI 乐评、网友评价、艺术家介绍等详细信息。

## 功能特性


![Uploading image.png…]()

### 📁 本地音乐管理
- 支持选择本地文件夹批量导入音频文件
- 自动识别常见音频格式（MP3、WAV、FLAC、AAC、OGG 等）
- 提取并显示音乐元数据（标题、艺术家、专辑、年份、时长等）

### 📊 Excel 歌单支持
- 导入格式规范的歌单 Excel 文件
- 支持丰富的元数据字段：
  - 基本信息：文件名、标题、艺术家、唱片集、年份、时长、格式
  - 标签信息：荣誉标签、特色标签
  - 评价信息：AI 乐评、网友乐评、艺术家介绍

### 🎵 音乐播放
- 内置音频播放器，支持播放/暂停、上一首/下一首
- 显示播放进度条和当前时间/总时长
- 自动匹配本地音乐文件与 Excel 歌单

### 📝 歌曲详情
- 完整的歌曲元数据显示
- 展示荣誉标签和特色标签
- 显示 AI 乐评和网友乐评
- 展示艺术家介绍信息

### 🎨 界面设计
- 精美的暗色主题设计
- 响应式布局，适配不同屏幕尺寸
- 流畅的动画效果和交互体验

## 快速开始

### 1. 下载与部署

STEP1：将 `爱乐评有会 Music Lovers Crossing.html` 文件下载到本地，双击用浏览器（推荐 Chrome、Edge、Firefox）打开即可使用。



### 2. 准备歌单文件
STEP2：导入示例音乐元数据：红猪与吉娜唱片店的推荐歌单（可修改）.xlsx   

或者准备你自己定制的专属歌单。
包含以下表头：

| 文件名 | 标题 | 艺术家 | 唱片集 | 年份 | 时长 | 格式 | 荣誉标签 | 特色标签 | AI乐评 | 网友乐评 | 艺术家介绍 |
|--------|------|--------|--------|------|------|------|----------|----------|--------|----------|------------|

> **提示**：可以使用项目中提供的 `红猪与吉娜唱片店的推荐歌单（可修改）.xlsx` 作为模板。

### 3. 添加本地音乐

将你的音乐文件（MP3 等音频格式）放在一个文件夹中。

### 4. 开始使用

1. 点击页面上的「元数据Excel」按钮，选择准备好的歌单文件
2. 点击「添加音乐」按钮，选择存放本地音乐文件的文件夹
3. 系统会自动匹配本地音乐与歌单信息
4. 点击播放列表中的歌曲即可开始播放

## 文件说明

```
music-lovers-crossing/
├── 爱乐评有会 Music Lovers Crossing.html   # 主程序（单文件应用）
├── 红猪与吉娜唱片店的推荐歌单（可修改）.xlsx  # 示例歌单
└── 添加你的音乐文件/                          # 放置本地音乐文件的目录
```

## 技术栈

OPENWORK+AI编写

- **前端框架**：原生 HTML + CSS + JavaScript
- **音频处理**：jsmediatags（读取音乐元数据）
- **表格处理**：SheetJS / xlsx（Excel 文件读写）
- **图标**：Font Awesome 6.4
- **字体**：Google Fonts（Noto Sans SC、Cormorant Garamond）

## 注意事项

1. 本应用为单页应用，所有功能均在浏览器中运行，无需服务器部署
2. 音乐文件和 Excel 歌单需要放在本地，使用时通过浏览器选择
3. 匹配逻辑基于「文件名」或「标题+艺术家」进行精确匹配
4. 如遇兼容性问题，请使用最新版本的现代浏览器

## 许可证

MIT

---
本网页采用AI编写，非专业开发，欢迎优化提升。

网页贡献：红猪与吉娜唱片店（Porco Rosso and Gina's Record Store）
