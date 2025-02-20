# Bilibili 评论爬虫和词频统计工具

## 简介
该项目是一个 Bilibili 评论爬虫和词频统计工具，能够从指定视频中获取评论，并对评论内容进行分词和词频统计。工具支持将评论和词频结果保存到 Excel 和 TXT 文件中。  
本项目仅用于交流学习，请勿用于其他用途！！！ 

---

## 功能
- **获取视频评论**：通过视频链接获取评论内容及评论者性别。
- **保存数据**：
  - 将视频信息（视频名和 URL）保存到 Excel 文件。
  - 将评论和性别保存到 Excel 文件。
  - 将评论内容保存为 TXT 文件。
- **词频统计**：
  - 对评论内容进行中文分词，并计算词频。
  - 去除停用词，按词频排序，并将结果保存为 TXT 文件。

---

## 环境要求
- Python 3.x
- 需要以下 Python 库：
  - `jieba`
  - `pandas`
  - `requests`
  - `beautifulsoup4`
  - `openpyxl`
  - `xlwt`

可以使用以下命令安装所需依赖：
```bash
pip install jieba pandas requests beautifulsoup4 openpyxl xlwt
```
---

## 使用方法
更改Cookie（Cookie非必填），然后将所需的关键词填入keyword_list中，之后运行就行（应该吧）如果需要再改其他内容。

---

## 请求支援
如果可以希望能给个喝水费：
- <img src="https://github.com/user-attachments/assets/ea80b45c-dde0-466e-ad85-e1eadd972b6b" alt="收款码" width="200" height="200">

