# 拼音汉字笔顺展示

一个优雅的 Web 应用，通过拼音输入汉字，动态展示汉字的书写笔顺。

## 功能特点

- 🔤 **拼音输入** - 大号输入框，轻松输入拼音
- ✍️ **笔顺动画** - 模拟真实书写过程，一笔一划动态展示
- 📝 **拼音标注** - 自动显示带声调的拼音
- 📚 **组词展示** - 提供 1-2 个常用词语作为参考

## 使用方法

1. 在输入框中输入汉字的拼音（如 `han`、`shi`）
2. 按下回车键
3. 欣赏汉字的笔顺动画
4. 点击「重播笔顺」可再次观看
5. 点击「显示全字」可查看完整汉字

## 快速开始

### 本地运行

直接在浏览器中打开 `index.html` 文件即可使用。

### 在线访问

部署到 GitHub Pages 后，访问：`https://你的用户名.github.io/仓库名/`

## 部署到 GitHub Pages

### 方法一：直接上传（推荐新手）

1. 在 GitHub 创建新仓库（如 `hanzi-writer`）
2. 将 `index.html` 文件上传到仓库根目录
3. 进入仓库 **Settings** → **Pages**
4. Source 选择 `main` 分支，`/ (root)` 文件夹
5. 点击 Save，等待部署完成
6. 访问 `https://你的用户名.github.io/仓库名/`

### 方法二：使用 Git 命令行

```bash
# 克隆仓库
git clone https://github.com/你的用户名/hanzi-writer.git
cd hanzi-writer

# 添加文件
git add index.html
git commit -m "Add hanzi writer app"

# 推送
git push origin main

# 然后在 GitHub 仓库 Settings → Pages 中启用
```

## 技术栈

- HTML5 + CSS3
- JavaScript (原生)
- [Hanzi Writer](https://hanziwriter.org/) - 汉字笔顺动画库

## 支持的汉字

目前数据库包含 300+ 常用汉字，包括：

- 数字：一、二、三、四、五、六、七、八、九、十
- 人体：手、头、眼、口、耳、脚、走、跑、站、坐、吃、喝、睡、笑、哭
- 自然：天、地、日、月、星、山、水、火、风、雨、雪、花、草、树、林、森
- 颜色：红、蓝、绿、黄、白、黑
- 家庭：爸、妈、爷、奶、哥、妹、弟、哥
- 食物：饭、面、包、饺、鱼、鸡、蛋、苹果、米
- 动物：狗、猫、兔、牛、羊、猪、马、鸟、鱼
- 学习：书、笔、纸、本、课、字、汉、语、文、英、体、美、音、乐
- 生活：衣、裤、鞋、帽、包、床、桌、灯、窗、门
- 地点：家、学校、医院、公园、公司
- 交通：车、火车、汽车、飞机

## 贡献

欢迎提交 Issue 和 Pull Request！

## License

MIT License
