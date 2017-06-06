
# 蓝鲸官网文档管理系统准则

[toc]

本文档旨在降低工作成本和规范蓝鲸官网所有对外文档的基本格式及风格。蓝鲸文档书写语法为 Markdown，更多请参考 [Google](https://www.google.com.hk/?gws_rd=cr,ssl#newwindow=1&safe=strict&q=markdown)。

注：本标准参考 [腾讯云对外发布标准规范]()、 [阿里云文档规范]() 和 [AWS文档惯例](http://docs.aws.amazon.com/zh_cn/general/latest/gr/docconventions.html)。

<table><tbody>
<tr>
<td>总体方针</td>
<td>以解决用户问题为目标，注重场景化。<br>遵循 5W1H 分析法：<br>（What）这是什么产品？<br>（Who）针对哪些客户群体？<br>（Why）我为什么要使用这个产品？这个产品解决什么问题？<br>（When+Where）使用产品的具体场景是什么？<br>（How）怎么使用这个产品？<br></td>
</tr>
<tr>
<td>发布流程</td>
<td>参考 <a href="#publish">发布流程</a></td>
</tr>
<tr>
<td>文档结构	</td>
<td>根据统一的内容框架进行内容补充</td>
</tr>
<tr>
<td rowspan="2">基本方法论</td>
<td>关注一致性、准确性（上下文、文字、标点符号与图片）<br><br>把可能使用的名词、缩略语都在文首列出，避免文档中出现从未<br>见过的名词。注意标点的正确使用，截图中出现的文字与说明需<br>保持强一致性。<br><br>
例子：蓝鲸集成平台，又称蓝鲸 PaaS</td>
<tr>
<td>清晰、易读<br><br>关注文档结构，构建易读的索引。<br><br>多使用图、表，增强易懂性。同时注意图表的清晰度，规范统一<br>的图表风格</td>
</tr>
</tbody>
</table>

## 文档规范
<a id="doc"></a>

### 标题/列表规范

文档标题有形如下的格式规范，目录从一级开始，最多可到第三级。（三级以上的标题不符合常规阅读需求，请拆分或使用标题内的列表进行相应处理）

<table>
  <tbody>
  <tr>
    <th> 标题层级</th>
    <th> 显示样式</th>
    <th> Markdown 语法</th>
  </tr>
  <tr>
    <td> 第一级标题</td>
    <td> ## 第一级标题</td>
    <td> Markdown 请注意采用二级‘##’语法，对应 HTML 标签为 h2</td>
  </tr>
  <tr>
    <td> 第二级标题</td>
    <td> ### 第二级标题</td>
    <td> Markdown 请注意采用三级‘###’语法，对应 HTML 标签为 h3</td>
  </tr>
  <tr>
    <td> 第三级标题</td>
    <td> #### 第三级标题</td>
    <td> Markdown 请注意采用四级‘####’语法，对应 HTML 标签为 h4</td>
  </tr>
  </tbody>
</table>

内容列表有形如下的格式规范：

<table>
  <tbody>
  <tr>
    <th> 列表层级</th>
    <th> 显示样式</th>
  </tr>
  <tr>
    <td> 正文第一级列表</td>
    <td> 1. 列表项一<br>2. 列表项二	</td>
   
  </tr>
  <tr>
    <td> 列表中的第二级列表</td>
    <td> 1. 列表项一<br><br>这是一段说明<br><br>1) 二级列表项一<br>  2) 二级列表项二	</td>
  </tr>
  <tr>
    <td> 二级列表中的第三级列表</td>
    <td> 1. 列表项一<br><br>这是一段说明<br><br>1) 二级列表项一<br><br>这是另一段说明<br><br>A. 三级列表项1<br>B.  三级列表项2<br><br>2) 二级列表项二</td>
  </tr>
  </tbody>
</table>

### 特殊表达规范

<table>
  <tbody>
  <tr>
    <th>特殊表达</th>
    <th>表达方式</th>
    <th>说明</th>
  </tr>
  <tr>
    <td>强调</td>
    <td>粗体+前后空格	</td>
    <td>非普通文字和短语或重要文字和短语的特殊<br/>标记。您可以 <b>这样</b> 使用强调。</td>
  </tr>
  <tr>
    <td>正文中的参数、<br>表达式或代码</td>
    <td>内联代码	</td>
    <td>必须使用内联代码标识正文中的参数、表达<br/>式或代码。Markdown<br/>语法为 ``<br><br><img src="https://mccdn.qcloud.com/static/img/f9dbb700441f7a407727eb9c6d20a4e8/image.png"></td>
  </tr>
  <tr>
    <td>代码块</td>
    <td>文档中出现的<br>完整代码	</td>
    <td>与正文分开，使用代码块标识。Markdown 语法为``` ```<br><br><img src="https://mccdn.qcloud.com/static/img/05b2ea78c32e165af2922b3a9da54464/image.png"></td>
  </tr>
  <tr>
    <td>界面标志</td>
    <td>【中文方括号】</td>
    <td>标识 UI 上的指定内容以便识别。<br><br>在【作业执行】下拉菜单中，点击【快速脚<br>本执行】按钮。</td>
  </tr>
  <tr>
    <td>交叉引用/外链</td>
    <td>超链接</td>
    <td>多使用超链接进行文档间关系的建立。<br><br>产品文档中引用的链接地址请直接使用绝对<br>路径，并设置为在新窗口中打开链接。<br><br>[link](url){:target="_blank"}</td>
  </tr>
  <tr>
    <td>互斥参数</td>
    <td>(a | b | c | d)</td>
    <td>代码中，分割线表示必须从中选择一个选项<br>的选项集。<br><br>% data = hdfread (start | stride | edge)</td>
  </tr>
  <tr>
    <td>可选参数</td>
    <td>	[英文方括号]</td>
    <td>代码中，方括号表示完全可选的命令或参数。<br><br>ssh [-l, -q] root@10.10.10.10</td>
  </tr>
  <tr>
    <td>变量</td>
    <td>	<箭头括号></td>
    <td>代码中，箭头括号表示必须替换为有效值的<br>变量。<br><br>mount /dev/vdb1 %<%your-mountpoint></td>
  </tr>
</tbody>
</table>

### 文档风格规范

#### 文案风格
1. 一定多检查，确保没有错别字。即使是流行语中的谐音错别字也不要使用，比如”墙裂”、”童鞋”、“程序猿”等。
2. 段落之间使用一个空行隔开。段落开头 **不要** 留出空白字符。
3. 请把对表达意思没有明显作用的字、词、句删除，在不影响表达效果的前提下把文案长度减到最短。
4. 避免口语，使用规范的书面语。例子：避免使用“么”、“喔”、“挂掉”等口语词汇。
5. 尽量避免中英文混杂。
6. 请一定注意“的”、“地”、“得”的用法。
7. 第一人称：推荐使用“蓝鲸”、“我们”，不推荐使用“小编”、“笔者”。
8. 避免多介词的复合长句。注意句子成分要齐全。
9. 产品名称一致性，产品名称要跟官网首页导航保持一致，不可随意书写。
10. 内容顺序，各类列表中的排序，需要符合惯例，不可随意排列，应跟官网首页导航顺序保持一致。
11. 命名合理性，概念命名，要通俗易懂，最好不要有歧义。

#### 中文、英文、数字混排时空格的使用

1. 中英文之间需要增加空格，如：包管理 SaaS，它采用了类似 Git 的版本管理理念。
2. 中文与数字之间需要增加空格，如：企业标准版拥有 7*24 小时的专属服务。
3. 数字与单位之间需要增加空格，如：0-100 台服务需要的系统配置至少是 4 核 8 G，/data 盘至少 50 G。
4. 中文符号与其他字符之间不加空格，如：蓝鲸智云日志检索产品是为了解决运维场景中查询日志难的问题而推出的一款 SaaS，基于业界主流的……
5. 链接之间需要增加空格，如：蓝鲸文档书写语法为 Markdown，更多请参考 [Google]()。

#### 标点符号相关

1. 只有中文或中英文混排中，一律使用中文 / 全角标点。
2. 中英文混排中如果出现整句英文，则在这句英文中使用英文 / 半角标点。
3. 省略号：请使用”……“标准用法，不要使用”。。。“。
4. 感叹号：请勿使用”！！“。尽量避免使用”！“。请先冷静下来再坐电脑前敲键盘。
5. 波浪号：请勿在文章内使用“~”，活泼地卖萌有很多其他的表达方式。

#### 名词的正确用法

1. 专有名词大小写，如：GitHub，而不是 github、Github 或者 GITHUB。
2. 使用正确的缩写，如：JavaScript、HTML5，而不是Js、h5。

### 示例

*本示例仅供参考此规范中部分条款的使用说明，不保证其对客观事实的描述正确性。*
![](https://raw.githubusercontent.com/shpdnkti/bkFramework/master/example.png)


## 发布规范


### 环境说明

#### 代码托管

蓝鲸官网文档系统，采用 Jekyll + Nginx 方案部署在腾讯云。文档管理托管在公有云版蓝鲸 PaaS 的 SVN 上。

```
SVN地址：https://svn.o.qcloud.com/1253778563/doc/trunk

SVN账户：1792298853

SVN密码：bO6Ddr3401
```

#### Jekyll运行环境

如果需要经常更新文档，请本地搭建一套运行环境，避免提交到线上测试。具体细节，请移步 SVN 下 trunk/docs/tools/windows-jekyll-install.md。

### 文档说明

#### 文档更新目录

允许更新的 SVN 目录

1. trunk/docs/demo/static
2. trunk/docs/demo/_posts

新建目录，请使用英文目录名。

static 文件夹存放静态文件，比如图片，引用路径 ../static/images/test/test.png。 建议使用压缩工具 [TinyPNG](http://www.tinypng.com), 将图片压缩再引用。 理论上是可以将其他文件，比如视频，pdf 等文件放入其中，但是为了减小服务器带宽压力，建议使用 CDN 存放，文档中引用链接。

\_posts 文件夹存放文档内容，仅 md 文件。_posts 中的内容将全部被发布到线上，请不要将无关文件提交到 \_posts 文件。草稿请放在 trunk/docs/demo/_data 目录下。

#### 文档格式

发布文档，请使用 Markdown 格式文件。

#### 文档命名

文件命名格式：[year]-[month]-[day]-[englishName].md

1. year 四位数字，比如 1000，建议按照既有顺延。

2. month 两位有效月份，比如 01。

3. day 两位有效日期，比如 02，建议仅取值 01-28。

4. englishName 英文文档名，比如 bkDevenglishName，建议带上分类信息，不要使用 index，about 等敏感词汇。

#### 文档 ID 说明

假设文件名为：1234-23-21-testName.md

文件的 ID 为：342321

文件 ID 是一个六位数字：年份的后两位 + 月 + 日

**请确保文件 ID 唯一。**

#### 文档的显示顺序

为了能通过文件名，直观地看到排序结果。 **文档顺序是文件名中日期的逆序**，比如 1000 年在 1001 年前面。

如果有需要调整文档的顺序，可以通过调整年份的前两位大小。

#### 文档内容

文档的前几行一定要定义 meta，比如：

```
---
layout: post
title: 蓝鲸文档发布指引
category: bkDev
keywords: FAQ
tag: [FAQ, bkMan]
---
```

其中，layout 的值一定要为 post，category 可选项有：

1. bkProd，产品文档
2. bkDev，新手入门
3. bkESB，ESB文档
4. bkAPI，API文档
5. bkRule，开发规范
6. bkTips，流程指引	
7. bkSolu，解决方案	
8. bkRes，资源下载	
9. bkFAQ，FAQ

> 如果不是新手入门、ESB 文档、API 文档分类文档，请去掉 tag 中的 bkMan。如果 category 属于新手入门，ESB 文档，API 文档之一，请在 tag 了中新增 bkMan，将其增加到【开发指南】

### 实践建议

* 建议在本地搭建 Jekyll 环境

* 使用英文文件名，命名带上分类信息

* 尽量完善文件的 meta 信息，比如 keywords、tag

* 根据项目在 \_posts 中新建文件夹存放文档

* 根据项目在 static 中新建文件夹存放静态文件

* SVN 更新文档要写注释

* h2, h3 标签会生成目录，请合理使用


## 发布流程
<a id="publish"></a>

### 权限确认

发布文档之前，请确认取得 herazhang 的授权。

### 线上发布

#### 测试环境

SVN 提交文档之后，测试环境每五分钟发布一次。访问地址，http://test.bk.tencent.com/document/, hosts 配置： `10.229.158.41 test.bk.tencent.com`。

#### 正式环境

在确定测试环境 OK 之后，请联系 hera 和 shaowen 发布到正式环境。访问地址，http://bk.tencent.com/document/




 
## 注意事项

1. 内容编辑/审核请遵循 [文档规范](#doc) 及 [语法](https://www.google.com.hk/?gws_rd=cr,ssl#newwindow=1&safe=strict&q=markdown) 
2. 已发布的文章不能删除，以免文章删除引起相关页面链接无法访问。
