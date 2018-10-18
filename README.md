# hello-world
want to find out what is really important for me.

Okay,let's see how many new words I get so far:

workflow “工作流程”， repository “资源库”， branch “分支”, commit “提交”， pull requests “合并请求”， essentials “要素”， install “安装”， the command line “命令行”， readme “自述文件”，default “系统默认值”， diagram “图表”， feature “特性”， initialize “初始化”， snapshot “快照”， associated “关联的”， capture “捕捉”.

prosper 成功 
width 宽度
px 像素
lorem ipsum 占位乱文 
inline style 内联样式
<h2 style="color blue"> Cat Photo App </h2>

CSS  Cascading Styles Sheets 层叠样式表 在CSS中类选择器属性应添加.
<style>
  选择器{属性名称：属性值;} 
  h2{color:red;} 元素选择器属性
  .blue-text{color:blue;} 类选择器属性
</style>
应用在h2中：
<h2 class="blue-text"></h2>


<style>
  p{font-size：16px;} 字体大小
</style>  


<style>
  p{font-family：Helverica，Sans-serif;} 字体类型 自动降级
</style>  

href  Hypertext Reference 超文本引用 超链接
src  Standard Requirement Code 标准要求代码

用link标签来引入谷歌Lobster字体 将以下链接粘贴到代码编辑器顶部
<link href="https://fonts.gdgdocs.org/css?family=Lobster" rel="stylesheet" type="text/css">
<style>
  h2{font-family：Lobster;} 
</style>

<img src="图片位置">

alt text 替代文本  每一张图片都应该有一张替代文本
<img src="图片位置" alt text>

修改图片大小：
<style>
  .smaller-image:{
  width:100px;
  }
</style>

CSS边框的属性有：style,color,width,height
<style>
  .thick-green-border{
    border-style: solid;
    border-color: green;
    border-width: 5px;
</style>

border-radius: 10px； 边框圆角  可以添加到.thick-green-border  也可以添加到 .smaller-image
border-radius:50%;   用px为方框 用%为圆框

a  anchor 锚点元素  既可以链接到外部地址实现页面跳转，也可以链接到当前页面的某部分实现内部导航功能
anchor text 锚点文本
<a href="http://..."> ANCHOR TEXT </a>

nesting 嵌套 把a元素属性的值替换为#（别名hash符号）将其变为一个固定链接
<a href="#"><img src="images/relaxing-cat.jpg" alt text="an orange cat lying on back"></a>

unordered lists 无序列表
<ul>
  <li>TEXT1</li>
  <li>TEXT2</li>
  <li>TEXT3</li>
</ul>

ordered lists 有序列表
<ol> 
  <li>TEXT1</li>
  <li>TEXT2</li>
  <li>TEXT3</li>
</ol>

text input 文本输入框
required 用户不填写输入框无法提交表单
placeholder text 占位符  用户在输入框内输入任何东西之前放置在输入框中的预定义文本
<input type="text" required placeholder text="...">

URL Uniform Resource Locator 统一资源定位符
给form元素添加一个action属性 构建可以跟服务器交互的Web表单(form)
action属性的值指定了表单提交到服务器的地址。
<form action="/url-where-you-want-to-submit-form-data"></form>

添加submit按钮：
<button type="submit"> submit</button>

radio button 单选按钮
label 标签
name 指定
每一个单选按钮/复选按钮都应该嵌套在它自己的label(标签)元素中。
所有关联的单选按钮/复选按钮应该使用相同的name属性。
在input元素中添加属性checked设置默认被选中。
<label><input type="radio" name="indoor-outdoor" checked> Indoor</label>

checkbox 多选按钮
<label><input type="checkbox" name="personality" checked> Loving</label>

div division 层元素 盛装其他元素的通用容器
所以可以利用CSS的继承关系把div上的CSS传递给它所有子元素。
<div><h1>CAT</h1>
     <p>CATCAT</p>
</div>

设置div的背景颜色：
<style>
  .green-background{
    background-color:green;
  }
</style>
<div class="green background">...
</div>

ID属性（HTML）,唯一的，不要给一个以上的元素设置相同的id属性
<h2 id="cat-photo-app">

ID选择器
<style>
  #cat-photo-form{
    background-color:green;
  }
</style>
