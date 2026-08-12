
## Gitbub/Gitee 是什么
公开的存文件的地方。可以收藏、分享、讨论、协作。


## 一、基本操作


1. 仓库信息

![图片](./images/00/仓库.png)

2. 获取代码：

```cmd
$ git clone https://github.com/supperluu/Hi-Agent.git
Cloning into 'Hi-Agent'...
fatal: unable to access 'https://github.com/supperluu/Hi-Agent.git/': SSL peer c
ertificate or SSH remote key was not OK


$ git clone http://github.com/supperluu/Hi-Agent.git
Cloning into 'Hi-Agent'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

```

3. 推送代码
在changes列表点击+ 号，文件到 Staged Changes 区域，输入提交信息，依次点击Commit,push



## 获取项目
### 1. 闲逛模式
#### 1.1 手动搜索

输入'\\' 斜杠，快速唤起搜索框

中文搜不到换成英文试试
想要应用，用app
替代方案或者替代品，用alternative

|目的|限定符 (Qualifier)|语法示例|说明|
|---|---|---|---|
|关键词定位|in:name</br>in:description</br>in:readme|微服务 in:name,description|指定在项目名、描述或README文件中搜索关键词，可组合使用。|
|按热度筛选|stars:</br>forks:|stars:>1000</br>stars:500..2000</br>微服务 stars:>1000 forks:>200|使用 >、< 或 .. 范围语法筛选Star或Fork数量。|
|按语言筛选|language:|language:python|精确查找特定编程语言的项目。|
|按时间筛选|created:</br>pushed:|created:>2024-01-01|查找在特定日期之后创建或更新过的项目。|
|排除结果|- (减号)|微服务 -demo|从搜索结果中排除包含特定关键词的项目。|
|Awesome 系列|awesome|awesome machine learning|在关键词前加上 awesome，寻找社区整理的同一主题**优质**资源合集。|
|roadmap 系列|roadmap|machine learning roadmap|在关键词后加上 roadmap，寻找社区整理的同一主题**优质**学习路线/发展路径。|
|文件查找器|t 键|在仓库内按 t 键|快速查找和浏览当前仓库内的所有文件。|
#### 1.2 热门搜索 

Topics(主题) == 话题标签
Trending(趋势)== 官网推荐榜,选择语言，编程语言及时间范围
Collections(集合) == 官网推荐榜
![图片](./images/00/热门趋势.png)
点击入口

![图片](./images/00/explore入口.png)
![图片](./images/00/platform入口.png)


### 2. 工具辅助

#### 2.1 GitHub CLI
GitHub CLI (gh skill)：在GitHub命令行工具（CLI）2.90.0及以上版本中，新增了 gh skill 命令
``` cmd
# windows 安装命令
winget install --id GitHub.cli

# 查看版本 安装后需要重新开cmd窗口
gh --version
```

#### 2.2 GitHub Copilot
直接问助手
![图片](./images/00/copilot.png)