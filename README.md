# 暑期实训日志
[TOC]



## 前言（实训安排）

### 一、主讲人
#### 吴志军（英才科技）
#### QQ：44786501
#### 电话：18810120821（微信同号）
### 二、实训目标
#### 1. 掌握公司项目开发流程、步骤
##### A.信息化全国排名第一（薪资）
a. 公司岗位多（传统公司、互联网公司）
b. 薪资全国排名第一
##### B.有哪些公司
1. 太多了！ 北京科蓝（上市）、厦门易联众、杭州创业慧康等 不同的软件公司，做的行业不尽相同；银行业、证券、保险、国电、交通、新能源、医保、社保、医疗
2. 英才科技主要项目：物联网智慧养殖、教育信息化
##### C.*公司项目开发流程及对应的工作岗位
1. 招投标  岗位：商务（销售、售前工程师）
2. 签合同
3. 建立项目组（项目经理、高级开发工程师、中级开发、初级开发）
4. 需求调研与分析  岗位：需求分析工程师 
5. 数据库设计   岗位：DBA
6. 架构设计     岗位：架构师
7. 详细设计     岗位：系统分析师或系统分析员
8. *开发（编程）
9. 测试  岗位：测试经理、测试工程师、用例工程师
10. 部署实施   岗位：实施工程师
11. 验收       甲方验收，乙方是软件开发公司
12. 维护  岗位：技术支持或运维工程师
#### 2.学会工程化开发工具的使用
#### 3.学会项目前端开发技术
#### 4.*开发《UOLab联合开放实验室管理系统》原型（项目为王）
### 三、考核方式
#### 1. 出勤成绩
#### 2. 每日提交成绩
#### 3. 项目完成情况
### 四、时间安排
1. 7月份12日~17日，19日~22日，共十天
2. 假期完成《UOLab联合开放实验室管理系统》原型
3. 开学线下总结、验收
### 五、训练技术
1. 开发工具：HBuilder
2. 浏览器：Chrome
3. HTML技术
4. CSS技术
5. *BootStrap技术
6. JavaScript技术
7. *jQuery技术
### 六、训练方式
1. 观看直播，边学边练
2. 回放强化，课后任务
## Day01
### 问题总结
#### 1.改变字体、字号及颜色
```html
   <font face="字体"size="字号"color="颜色"></font>
```
#### 2.表单项目的对齐(表格布局)
```html
   <table>
   <!--tr为行，th为表头，td为单元格-->
   <tr></tr><th></th><td></td>
   </table>
```
#### 3.输入的提示信息
```html
   <input place="">
```
#### 4.链接
```html
   <a href="网址">链接名</a>
```
#### 5.图片
```html
   <img src="图片"/>
```
#### 6.单元格内文字对齐方式
```html
   <td align="对齐方式">
```
#### 7.HTML是否区分大小写
否
#### 8.设置文本框最大值
```html
   <input type="text"maxlength="最大长度">
```
### 一、Markdown学习
#### 1. Markdown是什么？
   软件工程师标配文档撰写工具。
   它有自己的语法，但非常简单。
   浏览器可识别。
#### 2. 什么时候用？
   写专业文档；github或gitee；日常笔记、总结、写书。
### 二、HTML介绍（5W1H学习法）
#### 1. HTML是什么？（What）
   中文全称：超文本标记语言
   最新版本：HTML5（简称H5）
   执行者：浏览器（5大主流浏览器：Chrome、Firefox、Opera、Safari、Edge）
   即刻停止使用360、QQ等浏览器（早已实施，继续坚持）
#### 2. 为什么使用HTML？（Why）
   制作Web项目界面必须品。
#### 3. HTML的使用者是谁？（Who）
   Web前端开发工程师、后端开发人员、用户界面设计（USER Inference——UI，包括软件界面美化、网页美工）
#### 4. 何时使用HTML？（When）
   开发项目。
#### 5. 何处使用HTML？（Where）
   网页元素及搭建网页结构。
#### 6. 如何使用HTML？（How）
   在培训课程中学习，于项目实战中使用。
### 三、HTML标准
   HTML标准由W3C（国际万维网组织）制定的国际标准。
### 四、HTML表单开发【*********】
#### 1.表单
```html
   <form></form>
```
#### 2.文本框
```html
   <input type="text">
```
#### 3.密码框
```html
   <input type="password">
```
#### 4.单选按钮
```html
   <input type="radio"name="gender">
```
#### 5.下拉选择
```html
   <select>
   <option></option>
   </select>
```
#### 6.复选框
```html
   <input type="checkbox">
```
#### 7.文本域
```html
   <textarea rows=""cols=""></textarea>
```
#### 8.文件上传
```html
   <input type="file">
```
#### 9.提交按钮
```html
   <input type="submit"value="提交">
```
#### 10.重置按钮
```html
   <input type="reset"value="重置">
```
#### 11.跳转网页
```html
   <form action="">
```
### *注意*
#### 1.通过多次练习达到永久记忆。
#### 2.理解性记忆。
#### 3.善用工具。
### /课后任务/
#### 12306注册表单雏形
## Day02
### 问题总结
#### 1.HTMl只能做网页结构，不区分大小写，由浏览器执行
#### 2.开发重点：表单、表格、列表、图片、超链接、iframe
#### 3.达标：写出2中内容
#### 4.开发人员的用途：项目大纲
### 一、HTML表格
```html
   <table border="框宽"align="对齐方式">
     <tr>
       <td align=""></td>
       <td colspan="合并单元格数">
     </tr>
   </table>
```
### 二、HTML超链接
1. 链接对象：自制网页，外部网站
2. 语法
```html
   <a href=""></a>
```
### 三、HTML图片
1. 语法
```html
   <img width="宽度px"height"高度px"src="图片"/>
```
2. 链接图
```html
   <a href=""><img width="宽度px"height"高度px"src="图片"/></a>
```
### 四、HTML列表
1. 有序列表
```html
   <ol>
     <li>列表项</li>
   </ol>
```
2. 无序列表
```html
   <ul>
     <li>列表项</li>
   </ul>
```
### 五、HTML标题
共6级，h1~h6
```html
   <h1>1级标题</h1>
   <h2>2级标题</h2>
   <h3>3级标题</h3>
```
### 六、HTML段落和块（自动换行）
```html
   <p>段落</p>
   <div>块</div>
```
### 七、HTML提示和标签（不换行）
```html
   <span>提示</span>
   <lable>标签</lable>
```
### 八、HTML颜色
1. 表示
颜色名，颜色值（#16进制数）
2. 调配
RGB（Red，Green，Blue）
3. 语法
```html
   <body bgcolor=""></body>
```
*注意*
1. 公司中专做网页的工作岗位是什么嘛？网页美工、UI工程师。
2. 我们只需完善其完成的雏形所需实现的功能，而不是去完整地制作整个网页及网站。
3. 学习是为了能看懂其制作雏形的原理。
### 九、HTML字符实体
```html
   &特定名;文字
```
eg.
```html
   &nbsp; 空格(面试题) &gt; 大于号 &yen; ￥
```
*注意*
1. HTMl是W3C的标准，但不是强制标准，每个浏览器对其支持程度不尽相同，且语法较为宽松，由浏览器执行。
### 十、HTML框架
```html
   <iframe width=""height=""src="网址">
```
*注意*
1. 不要用于非法用途。
### 高频面试题：post与get的区别
1. post方式提交数据，表单数据在地址栏不显示，较为安全，且数据量大小不限
2. get方式提交数据，表单数据将显示于地址栏，风险较大，最大数据量为2K
## Day03
### 问题总结
#### 1.做CSS要有耐心，不断调试
#### 2.部署自制的网页
1）开发自己的网页
2）购买云主机Linux系统（阿里云主机），获得一个IP地址
3）上传网页到阿里云主机（此时可通过IP访问）
4）百度搜索域名注册，注册自己的域名；域名在工信部备案，取得备案号；绑定域名与IP，
### 一、CSS是什么
1. 中文全称：层叠式样式表，简称为样式。
2. 制定者：W3C，最新版CSS3
3. 执行者：浏览器
4. 作用：美化网页（HTML不具备美化网页的功能）
### 二、CSS选择器（*****）
1. 标记选择器
2. id选择器
3. class选择器
### 三、CSS代码放置位置
1. 页内样式：head之间，用style标记
2. 行内样式：标记的style属性中，优先级最高
3. 外部样式：放在独立的.css文件中
### 四、开发常用样式
1. 背景样式（background—color）
2. 文本样式
文字对齐方式（text—align）
文字下划线（text—decoration:underline）
文字删除线（text—decoration:line—through），医用HIS系统
删除下划线（text—decoration:none）
3. 字体样式
字体（font—family）
字号（font—size）
网页上的文字默认是16px：在工程上一般为12px或14px
4. 链接样式（a:hover）
5. 表格样式
表格线（table,tr,td{border:*px;solid/*dotted*/black}）
边框折叠（table{border—collapse：collapse}）
文字居中（table{text-align:center}）
6. 边框样式*
圆角（border—radius）
*补充
密码条
```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>密码强度条</title>
		<style>
			#first
			{
				background-color: red;
				width: 80px;
				height: 20px;
			}
			#second,#third
			{
				background-color: darkgray;
				width: 80px;
				height: 20px;
			}
		</style>
	</head>
	<body>
		<table align="center">
			<td><hr id="first"></td>
			<td><hr id="second"></td>
			<td><hr id="third"></td>
		</table>
	</body>
</html>

```
### 五. CSS盒子模型
1. 与网页布局密切相关
2. 美工必须精通
3. 开发工程师理解并会用
4. 重要：外边距margin，内边距padding，各有上下左右
顶部外边距（margin—top）
左部外边距（margin—left）
……
顶部内边距（padding—top）
……
居中（margin:0 auto;）
### 六、登陆网页
1. CSS盒子模型
2. HTMl表单元素
## Day04
### 问题总结
1. CSS尺寸单位：像素，百分比
#### 一、CSS显示
1. display
1）隐藏图片
a.隐藏图片
b.隐藏块
2. visibility
*区别*
display(none)隐藏后释放区域，visibility(hidden)隐藏后区域保留
#### 二、CSS浮动
1. 网页美工必须精通
2. 主要用于：网页布局（CSS+DIV）
#### 三、
#### 四、
#### 五、
#### 六、