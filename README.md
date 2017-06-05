[toc]
# 蓝鲸官网文档管理

## 文档规范

本文档旨在降低工作成本和规范蓝鲸官网所有对外文档的基本格式及风格。蓝鲸文档书写语法为 Markdown，详细语法请参考 [Google](https://www.google.com.hk/?gws_rd=cr,ssl#newwindow=1&safe=strict&q=markdown)。

注：本标准参考 腾讯云对外发布标准规范 和 阿里云文档规范

<table><tbody>
<tr>
<td>
总体方针</td>
<td>	以解决用户问题为目标，注重场景化。<br>遵循 5W1H 分析法：<br>
（What）这是什么产品？<br>
（Who）针对哪些客户群体？<br>
（Why）我为什么要使用这个产品？这个产品解决什么问题？<br>
（When+Where）使用产品的具体场景是什么？<br>
（How）怎么使用这个产品？<br><br>

* 分清读者对象，按不同的类型、不同层次的读者，决定怎样适应他们的需要。
</td>
</tr>
<tr>
<td>
流程
</td>
<td>
参考《腾讯云文档发布流程》
</td>
</tr>
<tr>
<td>
文档结构	
</td><td>根据统一的内容框架（请参考《产品介绍页基本规范》、《产品文档页基本规范》、《API文档基本规范》）进行内容补充
</td>
</tr>
<tr >
<td rowspan="2">基本方法论</td>
<td>关注一致性、准确性（上下文、文字、标点符号与图片）<br><br>
把可能使用的名词、缩略语都在文首列出，避免文档中出现从未见过的名词。注意标点的正确使用，截图中出现的文字与说明需保持强一致性。<br><br>
例子：云服务器（又称CVM、CVM实例、云服务器实例、云主机）
</td>
<tr><td>清晰、易读<br><br>
关注文档结构，构建易读的索引。<br><br>
多使用图、表，增强易懂性。同时注意图表的清晰度，规范统一的图表风格
</td></tr>
</tbody>
</table>

### 1.标题/列表规范

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

### 2.特殊表达及标点规范

<table>
  <tbody>
  <tr>
    <th> 特殊表达</th>
    <th> 表达方式</th>
    <th> 说明</th>
  </tr>
  <tr>
    <td>强调</td>
    <td>	粗体+前后空格	</td>
    <td>非普通文字和短语或重要文字和短语的特殊标记。<br/>您可以 <b>这样</b> 使用强调。</td>
  </tr>
  <tr>
    <td>正文中的参数、表达式或代码</td>
    <td>	内联代码	</td>
    <td>必须使用内联代码标识正文中的参数、表达式或代码。Markdown语法为 ``<br><br><img src="https://mccdn.qcloud.com/static/img/f9dbb700441f7a407727eb9c6d20a4e8/image.png"></td>
  </tr>
  <tr>
    <td>代码块</td>
    <td>	文档中出现的完整代码	</td>
    <td>与正文分开，使用代码块标识。Markdown语法为``` ```<br><br><img src="https://mccdn.qcloud.com/static/img/05b2ea78c32e165af2922b3a9da54464/image.png"></td>
  </tr>
  <tr>
    <td>界面标志</td>
    <td>	【中文方括号】	</td>
    <td>标识 UI 上的指定内容以便识别。<br><br>在【云服务器】选项卡中，点击【新建】按钮。</td>
  </tr>
  <tr>
    <td>交叉引用/外链</td>
    <td>	超链接</td>
    <td>多使用超链接进行文档间关系的建立。<br><br>产品文档中引用的链接地址请统一直接拷贝磐石产品文档中的相对路径，/document/product/ +数字路径，例如/document/product/213/6090。</td>
  </tr>
  <tr>
    <td>互斥参数</td>
    <td>	(圆括号 | 和 | 竖 | 线)</td>
    <td>代码中，分割线表示必须从中选择一个选项的选项集。<br><br>% data = hdfread (start | stride | edge)</td>
  </tr>
  <tr>
    <td>可选参数</td>
    <td>	[英文方括号]</td>
    <td>代码中，方括号表示完全可选的命令或参数。<br><br>ssh [-l, -q] root@10.10.10.10</td>
  </tr>
  <tr>
    <td>变量</td>
    <td>	<箭头括号></td>
    <td>代码中，箭头括号表示必须替换为有效值的变量。<br><br>mount /dev/vdb1 %<%your-mountpoint></td>
  </tr>
</tbody>
</table>

### 3.文档风格规范

### 4.示例

## 文档发布流程

## 注意事项
