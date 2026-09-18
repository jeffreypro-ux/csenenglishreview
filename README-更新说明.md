# Csen 英语复习站 · 更新说明

整个网站就是一个文件：**index.html**，双击即可在浏览器打开（推荐 Chrome / Edge / Safari，语音功能最全）。

## 添加一节课
打开 index.html，搜索 ★★★ 新课程粘贴在这一行的上方 ★★★，把模板复制到上方，改 id、date、title、sections 即可，新课自动显示在列表最顶部。板块类型：
- `list` 要点列表（英文放进 <span class='en'>...</span> 会自动带 🔊 发音按钮）
- `table` 中英对照表（同样支持 🔊）
- `dialog` 对话
- `tip` 老师提醒
- `homework` 作业

## 添加单词卡
在 WORDS 数据区按格式加一行：{ w:"单词", p:"音标", m:"词性 中文", e:"例句" }

## 真人录音
把 mp3 放进 audio/ 文件夹，在数据里加 audio:"audio/xxx.mp3"，网站优先播 mp3，失败自动用浏览器内置语音。

## 其他
- 声音设置（女声推荐、语速）和"已复习"进度保存在浏览器本地。
- 支持链接直达：index.html#/lesson/9
- 想放到网上：把整个文件夹传到 GitHub Pages 即可（参考 lucyenglish 的做法）。
