# PHP学习路线图

* [飞书文档查看](https://gahviotzzv.feishu.cn/mindnotes/FJQ2bssKlmaGKlneEEJcMZb2nwc#outline)
* [思维导图](https://gahviotzzv.feishu.cn/mindnotes/FJQ2bssKlmaGKlneEEJcMZb2nwc#mindmap)
![image](https://github.com/lucoo01/phproadmap/assets/10543112/8c439cae-bcd9-4671-91c5-39c238a9b771)

## 符号表
```
    ⭐️ 必学：核心知识点，经常用到。

    ✅ 建议学：重要知识点，专业人士的基石。

    ❗ 面试重点：经常出现的面试知识点。

    ❌ 可有可无：边缘区域，不是必须探索的地方。

    💬 知识描绘：知识点描述，快速理解。

    📚 学习资源：关联的学习资源。

    🎯 学习目标：阶段性目标。
```

##  一、第一阶段 - PHP 入门

```
    💬 描述：通过掌握计算机基础、前端基础和PHP基础，能够建立起坚实的编程基础，有助于更深入理解和应用PHP语言以及整个Web开发生态系统。

    📚 资源

        - PHP 教程：https://www.w3cschool.cn/php/

        - 十天学会PHP: https://www.w3cschool.cn/minicourse/play/phpinit

        - PHP 入门课程(互动课程) : https://www.w3cschool.cn/minicourse/play/phpcourse

    🎯 目标：了解和实践各语言的基础语法，并能使用开发工具来独立开发简单登录页面。

    ⭐️ 开发工具

        - 💬 描述：工欲善其事，必先利其器。

        - 浏览器

            *  ⭐️ Chrome: 备受欢迎

            *  ✅ Edge: 广泛使用

            *  ✅ Safari:  苹果设备使用

            *  ❌Firefox: 相对较少

        - 编辑器

            *  ⭐️ VSCode: 轻量强大，广受欢迎的开源编辑器。

            *  ✅ PHPStorm: 一款强大的集成开发环境（IDE），专为PHP语言开发而设计，提供丰富的功能和工具支持。

        - 在线笔记

            *  ⭐️语雀: 知识协作平台，支持团队协作和文档管理。

            *  ✅幕布: 思维导图和大纲相结合的在线协作笔记工具。

            *  石墨文档: 实时协作，简洁易用的在线文档工具。

            *  飞书文档: 与飞书集成，支持团队协作和实时编辑。

    ✅ 计算机基础

        - 💬 描述：这些基础知识对于理解计算机工作原理、软件开发和网络通信等方面都至关重要。

        - 📚 资源: 

            *  计算机基础知识: https://www.w3cschool.cn/basic/

        - 计算机硬件

            *  指计算机的物理部分，包括中央处理单元（CPU）、内存、硬盘、显示器等组件。

        - 操作系统

            *  是计算机系统的核心软件，负责管理硬件资源、提供用户界面，并执行应用程序。

        - 网络详解

            *  涉及计算机之间通过网络连接进行通信的原理、协议和技术，包括TCP/IP协议、HTTP协议等。

        - 字节和位

            *  字节是计算机存储单位，由8位二进制组成，是信息存储的基本单元。

        - 进制详解

            *  计算机中常用的进制包括二进制（base-2）、八进制（base-8）、十进制（base-10）和十六进制（base-16）。

        - 字符编码

            *  用于在计算机中表示字符的编码方式，常见的有ASCII、UTF-8等，用于将字符映射到二进制数据。

    ⭐️HTML 基础

        - 💬 描述：HTML（Hypertext Markup Language）是一种用于创建网页结构的标记语言，通过使用标签来定义文档的各个部分。

        - 📚 资源：

            *  HTML 教程: https://www.w3cschool.cn/html/

            *  HTML 手册:  https://developer.mozilla.org/zh-CN/docs/Learn/HTML

        - ⭐️常用标签

            *  盒子 div

                * 💬 描述：<div> 是一个容器元素，用于组织和布局其他 HTML 元素。它通常被用作分组元素，可用于创建页面的不同部分或布局结构，通过设置样式来控制其外观和位置。

            *  标题 h1 ~ h6

                * 💬 描述：<h1> 到 <h6> 是标题元素，用于定义标题的级别，其中 <h1> 是最高级别的标题，<h6> 是最低级别的标题。它们用于标识文档结构和重要性，并影响搜索引擎优化。

            *  段落 p

                * 💬 描述：<p> 用于定义段落，将文本组织成逻辑块。浏览器会在段落之间添加一些间距，使文本更易读。

            *  超链接 a

                * 💬 描述：<a> 用于创建超链接，允许用户点击链接跳转到其他页面、文件或资源。href 属性定义链接目标的 URL。

            *  图像 img

                * 💬 描述：<img> 用于嵌入图像到网页中。src 属性指定图像文件的路径，alt 属性提供图像的替代文本，用于无法加载图像时的显示。

            *  列表 ul / ol

                * 💬 描述：<ul> 表示无序列表，<ol> 表示有序列表。列表中的每一项由 <li> 标签表示。无序列表使用圆点、方块等作为项目标记，而有序列表使用数字或字母。

            *  表单 form

                * 💬 描述：<form> 用于创建 HTML 表单，允许用户输入数据并提交到服务器。表单包含各种输入元素，如文本框、复选框、单选按钮等，用户可以通过表单与网站进行交互。

            *  表格 table

                * 💬 描述：<table> 用于创建表格，表格由行 <tr> 和列 <td> 或表头 <th> 组成。它允许以表格形式组织和展示数据。

            *  框架 iframe

                * 💬 描述：<iframe> 用于嵌入另一个文档，可以是其他网页或媒体内容。它创建了一个内联框架，允许在当前文档中显示其他文档的内容，用于实现页面的嵌套和集成。

        - ✅ HTML5 特性

            *  语义化标签

                * HTML5引入了一系列语义化标签，如<header>、<footer>、<article>、<section>等，以更清晰地描述页面内容结构，使页面结构更具可读性和可维护性。

            *  多媒体标签

                * HTML5引入了多媒体标签，如<audio>和<video>，使在网页中嵌入音频和视频变得更加简单和标准化。

    ⭐️CSS 基础

        - 💬 描述：CSS是一种用于控制网页外观和样式的语言，通过选择器和属性为HTML元素提供美观的排版和设计。

        - 📚 资源：

            *  CSS 教程: https://www.w3cschool.cn/css/

            *  CSS 入门课程: https://www.w3cschool.cn/minicourse/play/csscourse

        - ⭐️ 基本语法

            *  选择器（Selectors）

                * 选择器是用来选择 HTML 元素的模式。可以选择元素的类型、类、ID 等。

                * 示例：p 选择所有 <p> 元素，.class 选择所有类为 "class" 的元素，#id 选择具有特定 ID 的元素。

            *  属性（Properties）

                * 每个选择器后面跟着一对大括号，内部包含一个或多个属性。

                * 示例：color、font-size、margin。

            *  值（Values）

                * 属性后面的值指定了该属性的具体设置。

                * 示例：red、16px、auto。

            *  声明块（Declaration Block）

                * 由一对大括号 {} 包裹，包含一个或多个声明。

            *  注释（Comments）

                * 使用 /* */ 来添加注释。

                * 示例：/* 这是一个注释 */。

            *  样式规则（Rules）

                * 选择器和声明块的组合形成一个样式规则。

            *  样式表（Stylesheet）

                * 包含一系列样式规则的文档，可以是内部样式表、外部样式表或嵌入式样式表。

        - ⭐️ 引入方式

            *  行内样式

                * 在HTML元素的style属性中直接嵌入CSS样式。

            *  内部样式表

                * 在HTML文档的<head>标签内使用<style>标签定义CSS样式。

            *  外部样式表

                * 将CSS代码保存在一个独立的外部文件中，并通过<link>标签引用该文件。

        - ⭐️ 选择器

            *  通用选择器（Universal Selector）

                * 用 * 表示，匹配文档中的所有元素。

                * 示例：* { margin: 0; padding: 0; } 将所有元素的边距和填充设置为零。

            *  标签选择器（Type Selector）

                * 使用HTML标签名称作为选择器，匹配相应类型的所有元素。

                * 示例：p { color: blue; } 将所有段落文本颜色设置为蓝色。

            *  ID 选择器（ID Selector）

                * 使用元素的ID属性来选择唯一的元素。

                * 示例：#header { font-size: 24px; } 选择ID为 "header" 的元素。

            *  Class 选择器（Class Selector）

                * 使用元素的class属性来选择具有相同类的元素。

                * 示例：.highlight { background-color: yellow; } 选择所有类为 "highlight" 的元素。

            *  属性选择器（Attribute Selector）

                * 通过元素的属性来选择元素。

                * 示例：input[type="text"] { border: 1px solid #ccc; } 选择所有类型为 "text" 的输入框。

            *  派生选择器（Descendant Combinator）

                * 用于选择作为某个元素后代出现的元素。

                    ~ 后代选择器（Descendant Selector）： 使用空格分隔元素，选择嵌套在另一个元素内的元素。

                        ^  示例：div p { color: green; } 选择所有段落，但只限于它们位于 <div> 元素内。

                    ~ 子元素选择器（Child Selector）： 使用 > 符号选择作为另一个元素的直接子元素的元素。

                        ^  示例：ul > li { list-style-type: square; } 选择所有作为 <ul> 直接子元素的 <li> 元素。

            *  相邻兄弟选择器（Adjacent Sibling Combinator）

                * 选择与指定元素相邻的同级元素。

                * 示例：h2 + p { font-style: italic; } 选择紧接在 <h2> 后的 <p> 元素，设置斜体样式。

            *  组合选择器（Multiple Selectors）

                * 将多个选择器组合在一起，共享相同的样式规则。

                * 示例：h1, h2, h3 { color: purple; } 将标题元素的文本颜色都设置为紫色。

            *  伪选择器（Pseudo-class and Pseudo-element Selectors）

                * 用于选择元素的特定状态或位置，例如鼠标悬停、访问链接、第一个子元素等。

                * 示例：a:hover { text-decoration: underline; } 将鼠标悬停在链接上时添加下划线。

            *  选择器优先级（Selector Specificity）

                * 用于确定哪个样式规则将被应用，基于选择器的特定性。

                * 通常，ID选择器的特定性高于类选择器，类选择器的特定性高于标签选择器。

        - ❗ 解释CSS的优先级是如何工作的？

            *  当多个样式规则应用于同一元素时，浏览器会根据以下顺序来计算优先级：

            *  重要性（Importance）：

                * !important规则具有最高的优先级。如果样式中使用了!important，则该样式将覆盖其他所有样式。

            *  内联样式（Inline Styles）：

                * 内联样式通过在HTML标签的style属性中定义，它的优先级高于其他样式规则。

            *  ID选择器（ID Selectors）：

                * ID选择器的优先级较高。使用#符号定义的选择器，如#myElement。

            *  类选择器、属性选择器和伪类（Class Selectors, Attribute Selectors, Pseudo-classes）：

                * 类选择器、属性选择器和伪类的优先级相等，较低于ID选择器。例如，.myClass、[data-attribute]、:hover。

            *  元素选择器和伪元素（Element Selectors, Pseudo-elements）：

                * 元素选择器和伪元素的优先级最低。例如，div、::before。

            *  在以上规则中，每个级别的优先级是递增的。如果多个规则属于同一级别，那么后定义的规则将覆盖先定义的规则。

        - ❗ 什么是伪类和伪元素？

            *  伪类（Pseudo-classes）：伪类用于选择元素的特定状态或位置，而不是元素本身的特性。它们以冒号（:）开头，用于为元素的不同状态或位置应用样式。

            *  一些常见的伪类包括：

                * :hover - 鼠标悬停在元素上时应用的样式。

                * :active - 鼠标点击元素但尚未释放时应用的样式。

                * :focus - 元素获得焦点时应用的样式。

                * :nth-child() - 选择某个元素的特定子元素。

            *  伪元素（Pseudo-elements）：伪元素用于选择元素的特定部分或位置，而不是整个元素。它们以两个冒号（::）开头，用于为元素的特定部分应用样式。

            *  一些常见的伪元素包括：

                * ::before - 在元素内容之前插入一个虚拟的子元素。

                * ::after - 在元素内容之后插入一个虚拟的子元素。

                * ::first-line - 选择元素的第一行文本。

                * ::first-letter - 选择元素的第一个字母。

        - ⭐️ 属性

            *  单位

                * px（Pixels）：

                    ~ 像素是屏幕上的最小单位，指定长度或宽度为像素值。

                    ~ 示例：font-size: 16px; 设置文字大小为16像素。

                * em：

                    ~ em单位是相对长度单位，相对于父元素的字体大小。

                    ~ 示例：font-size: 1.5em; 表示字体大小是父元素字体大小的1.5倍。

                * rem（Root em）：

                    ~ rem单位也是相对长度单位，相对于根元素（html）的字体大小。

                    ~ 示例：font-size: 2rem; 表示字体大小是根元素字体大小的2倍。

                * vw（Viewport Width）：

                    ~ vw单位表示相对于视口宽度的百分比，1vw 等于视口宽度的1%。

                    ~ 示例：width: 50vw; 表示宽度为视口宽度的50%。

                * vh（Viewport Height）：

                    ~ vh单位表示相对于视口高度的百分比，1vh 等于视口高度的1%。

                    ~ 示例：height: 75vh; 表示高度为视口高度的75%。

            *  字体

                * font: 综合设置字体属性，包括字体大小、字体系列、字体粗细等。

                * line-height: 设置行高，即文本行之间的垂直间距。

            *  文本

                * color: 设置文本颜色。

                * font-size: 设置字体大小。

                * font-family: 设置字体系列。

                * font-weight: 设置字体粗细。

                * text-align: 设置文本水平对齐方式。

            *  背景

                * background-color: 设置元素的背景颜色。

                * background-image: 设置元素的背景图像。

                * background-repeat: 控制背景图像的平铺方式。

                * background-position: 设置背景图像的起始位置。

                * background-size: 控制背景图像的尺寸。

            *  列表

                * list-style-type: 设置列表项前面的标志的类型（例如，实心圆点、数字等）。

                * list-style-image: 设置列表项前面的自定义图像。

                * list-style-position: 设置列表项标志的位置（内部或外部）。

            *  表格

                * border: 设置表格边框。

                * border-collapse: 控制表格边框的合并方式。

                * width: 设置表格宽度。

                * text-align: 设置表格中文本的水平对齐方式。

        - ⭐️ 文档流

            *  ⭐️标准流（Normal Flow）

                * 标准流是元素在没有浮动（float）和定位（position）的情况下所处的默认流动状态。

                * 元素按照其在HTML中的顺序垂直排列，水平方向则从左至右。

                * 块级元素会独占一行，行内元素会在同一行内水平排列。

            *  ⭐️浮动流（Float）

                * 浮动是一种脱离标准流的布局方式，允许元素在文档中左右浮动。

                * 浮动的元素不再占据标准流中的位置，其他内容会围绕着浮动元素流动。

                * 常用于实现多列布局等。

            *  ⭐️定位流（Positioning）

                * 定位是一种通过设置元素的位置属性，使其脱离标准流并相对于其包含块（通常是最近的有定位属性的祖先元素）进行定位的方式。

                * 常用的定位属性包括 position: relative;、position: absolute;、position: fixed;。

                * 绝对定位的元素脱离了标准流，不再占据正常文档流中的位置，而相对定位的元素仍占据标准流中的位置，但可以相对自身位置进行微调。

            *  ⭐️弹性流（Flex Flow）

                * 弹性流是通过使用Flexbox模型来实现的，它允许容器内的子元素根据需要自动调整大小和位置。

                * 弹性容器（Flex Container）通过设置 display: flex; 或 display: inline-flex; 来启用弹性流。

                * 子元素称为弹性项目（Flex Item），通过设置弹性项目的属性来控制其在容器内的布局。

        - ⭐️ 内联元素 / 块状元素

            *  块状元素（Block-level Elements）

                * 块状元素通常以块的形式显示，即它们会独占一行，从新的一行开始，并且可以设置宽度、高度、外边距（margin）、内边距（padding）等属性。

                * 常见的块状元素包括 <div>、<p>、<h1> 到 <h6>、<ul>、<ol>、<li>、<table> 等。

            *  内联元素（Inline Elements）

                * 内联元素在文档中不会开始新的一行，它们在水平方向上排列，直到遇到块状元素或换行符为止。内联元素的宽度和高度通常由其内容决定。

                * 常见的内联元素包括 <span>、<a>、<strong>、<em>、<img>、<br> 等。

        - ⭐️ 盒子模型

            *  content（内容区域）

                * content 是盒子模型中的实际内容区域，它包含了元素的文本、图片或其他子元素。

            *  padding（内边距）

                * padding 是内容区域与边框之间的空间，用于控制元素内部的空白区域。

            *  margin（外边距）

                * margin 是盒子模型外部的空白区域，用于控制元素与其周围元素之间的间距。

            *  border（边框

                * border 是围绕内容和内边距的线条，用于界定元素的边界。

        - ⭐️ 浮动

            *  设置浮动 float

            *  清除浮动 clear

        - ⭐️ 定位

            *  static（静态定位）

                * position: static; 是元素的默认定位方式，元素按照它们在文档中的顺序进行正常流布局。

                * 元素不会受到 top、right、bottom、left 等属性的影响。

            *  absolute（绝对定位）

                * position: absolute; 让元素相对于其最近的非静态定位祖先元素进行定位，如果没有这样的祖先元素，则相对于最初的包含块（通常是 <html> 元素）。

                * 绝对定位的元素脱离正常文档流，不占据标准流中的位置。

            *  fixed（固定定位）

                * position: fixed; 让元素相对于浏览器窗口进行定位，即使页面滚动，元素也会固定在窗口的位置。

                * 固定定位的元素同样脱离正常文档流。

            *  relative（相对定位）

                * position: relative; 让元素相对于其正常文档流中的位置进行定位，然后通过设置 top、right、bottom、left 等属性进行微调。

                * 相对定位不会脱离正常文档流，仍然占据标准流中的位置。

            *  sticky（粘性定位）

                * position: sticky; 是相对定位和固定定位的混合。元素在跨越特定阈值前是相对定位的，在跨越阈值后变为固定定位。

                * 典型用法是在滚动时元素会粘在视口的某个位置。

        - ⭐️ 层叠规则

        - ❗ BFC 和 IFC 机制

            *  BFC（块级格式上下文）：

                * 定义： BFC是一个独立的块级区域，规定了内部块级元素的布局方式，不受外部元素的影响。

                * 特性：

                    ~ 内部的块级元素垂直方向上一个接一个地放置。

                    ~ 块级元素的垂直外边距会发生重叠。

                    ~ BFC区域不会与浮动元素重叠。

                    ~ BFC可以包含浮动元素。

                    ~ BFC区域的边界会包含其所有的子元素。

                * 触发条件：

                    ~ 根元素或包含根元素的元素。

                    ~ 浮动元素（float不为none）。

                    ~ 绝对定位元素（position为absolute或fixed）。

                    ~ 行内块元素（display为inline-block）。

                    ~ 表格单元格（display为table-cell）。

                    ~ overflow的值不为visible的块元素。

            *  IFC（内联格式上下文）：

                * 定义： IFC是内联元素的一个布局上下文，规定了内联元素的排列方式，沿着一个行的方向水平放置。

                * 特性：

                    ~ 内联元素在水平方向上一个接一个地排列。

                    ~ 可以通过vertical-align属性来调整元素在行内的垂直对齐方式。

                    ~ 元素的外边距、边框、内边距在水平方向上会发生重叠。

                    ~ IFC的宽度由包含块的宽度以及元素的外边距、边框、内边距共同决定。

                * 触发条件：

                    ~ 元素的display属性为inline、inline-block、inline-table。

                    ~ 元素的position属性不为absolute、fixed。

                    ~ 元素的float属性为none。

        - CSS3

            *  ⭐️ 响应式布局

                * 媒体查询（Media Queries）

                    ~ 媒体查询是CSS3的一个重要特性，它允许根据不同的媒体条件（如屏幕宽度、设备类型等）应用不同的样式。通过在样式表中使用@media规则，可以根据需要为不同的屏幕尺寸或设备类型定义不同的样式。

                * Flex 布局

                    ~ Flex布局是一种弹性盒子模型，通过display: flex属性可以创建一个弹性容器，内部的子元素（项目）将根据需要自动排列。Flex布局提供了更灵活的布局方式，适用于构建响应式且动态的页面结构。

                * Grid 布局

                    ~ Grid布局是一种二维布局系统，通过display: grid属性可以创建一个网格容器，可以在行和列的交叉点上放置子元素。Grid布局提供了更强大的网格系统，使得设计者能够更精确地控制页面的布局。

                * 瀑布流

                    ~ 瀑布流是一种页面布局方式，将元素按照列的顺序依次排列，当一列的空间填满后，新的元素将放置在空间较小的列上。这种布局方式常用于展示图片、文章等不同高度的内容，使页面看起来更有动态感和吸引力。

            *  动画（Animations）

                * CSS3允许使用关键帧动画（keyframes）创建平滑的动画效果。通过@keyframes规则，可以定义元素在动画过程中的不同状态，然后通过animation属性将这些动画应用到元素上。

            *  过渡（Transitions）

                * 过渡是一种平滑地在不同状态之间过渡的方式。通过定义元素在不同状态下的样式，然后使用transition属性指定过渡效果的持续时间、延迟时间和过渡函数。

            *  渐变（Gradients）

                * 渐变允许在元素的背景中创建平滑的颜色过渡。CSS3提供了线性渐变（linear gradient）和径向渐变（radial gradient）两种类型。

            *  背景（Background）

                * CSS3提供了更多背景样式的选项，如背景尺寸、背景定位、多重背景等。

            *  边框（Borders）

                * CSS3增强了边框的样式和绘制能力，包括圆角边框、图像边框、盒阴影等。

            *  圆角（Border Radius）

                * 通过border-radius属性可以为元素的角添加圆角效果。

            *  字体（Fonts）

                * CSS3提供了更多的字体样式控制选项，包括字体阴影、字体拉伸、字体变换等。

            *  2D / 3D 转换（Transforms）

                * CSS3中的transform属性可以进行元素的2D和3D转换，包括平移、旋转、缩放等。

    ⭐️ PHP 基础

        - 💬 描述：PHP是一种通用开源脚本语言，特别适用于Web开发，可嵌入HTML中，支持面向对象编程和服务器端脚本执行。

        - ⭐️ 开发环境搭建

            *  💬 描述：搭建PHP开发环境通常涉及安装Web服务器（如Nginx）、PHP解释器以及配置数据库（如MySQL）等。学习阶段推荐使用Xammp、PHPstudy这类集成套件就可以了。

            *  📚 资源：

                * PHP 安装教程: https://www.w3cschool.cn/php/php-install.html

                * PHP 官方下载: https://www.php.net/downloads.php

        - ⭐️ 变量和常量

            *  在PHP中，使用$符号定义变量，而常量则使用define()函数，它们用于存储数据和值。

        - ⭐️ 数据类型

            *  PHP支持多种数据类型，包括整数、浮点数、字符串、数组、对象等。

        - ⭐️ 运算符

            *  包括算术运算符（+、-、*、/）、比较运算符（==、!=、<、>）、逻辑运算符（&&、||）等。

        - ⭐️ 流程控制

            *  包括条件语句（if、else）、循环语句（for、while）、switch语句等，用于控制程序的执行流程。

        - ⭐️ 函数

            *  使用function关键字定义函数，将代码组织成可重复使用的模块，提高代码的可维护性和复用性。

        - ⭐️ 形参和实参

            *  函数的参数分为形式参数（在函数定义中声明的参数）和实际参数（在函数调用中传递的参数）。

        - ❗ ⭐️ 变量作用域

            *  了解全局作用域和局部作用域的概念，以及使用global和static关键字来控制变量的作用域。

        - ⭐️ 系统常见函数

            *  💬 描述：PHP提供了丰富的系统函数，如字符串处理函数（strlen()、substr()）、数组函数（array_push()、count()）、文件操作函数等，用于简化常见任务的处理。

            *  字符串处理函数

                * strlen($str): 获取字符串长度。

                * strpos($haystack, $needle): 查找子字符串首次出现的位置。

                * substr($str, $start, $length): 提取字符串的子串。

            *  数组函数

                * count($array): 统计数组元素个数。

                * array_push($array, $value): 将元素压入数组末尾.

                * array_pop($array): 弹出数组最后一个元素。

            *  文件操作函数

                * file_get_contents($filename): 读取整个文件内容。

                * file_put_contents($filename, $data): 将字符串写入文件。

                * fopen($filename, $mode): 打开文件或者 URL。

    ⭐️ MySQL 基础

        - 💬 描述：MySQL是一种开源的关系型数据库管理系统，广泛用于Web应用程序的数据存储和管理。

        - 📚 资源：

            *  MySQL教程： https://www.w3cschool.cn/mysql/

            *  MySQL入门课程： https://www.w3cschool.cn/minicourse/play/mysqlcourse

            *  MySQL零基础入门： https://www.w3cschool.cn/minicourse/play/mysql_my

        - ⭐️基础 SQL 操作

            *  💬 描述：包括SELECT、INSERT、UPDATE、DELETE等基本SQL语句，用于对MySQL数据库进行数据查询、插入、更新和删除操作。

            *  📚 资源：

                * SQL教程： https://www.w3cschool.cn/sql/

                * SQL 入门微课（互动课程）：https://www.w3cschool.cn/minicourse/play/sqlcourse

        - 字符集

            *  MySQL支持多种字符集，用于定义存储在数据库中的文本数据的编码方式，常见的字符集包括UTF-8、GBK等。

        - 列类型、类属性

            *  MySQL中的列类型包括整数、浮点数、字符串等，每种类型都有不同的属性，如长度、是否允许NULL值等，用于定义表中各列的特性。

        - ✅ Navicat 使用

            *  💬 描述：Navicat是一款可视化的数据库管理工具，用于连接、管理和操作MySQL数据库，提供图形界面和便捷的操作方式。

        - ⭐️PHP 操作数据库

            *  学习使用PHP语言与MySQL数据库进行交互，包括连接数据库、执行SQL语句、处理查询结果等，用于在Web开发中实现动态数据的存取与展示。
```

 ## 第二阶段：初窥门径
 ```

    ⭐️面向对象 (OOP)

        - 💬 描述：面向对象编程是一种编程范式，它利用对象的概念，包括类和对象，以更模块化和可维护的方式组织代码。

        - 📚 资源: 

            *  PHP 面向对象教程: https://www.w3cschool.cn/php/php-oop.html

        - ⭐️类的定义

            *  类是抽象的数据类型，使用class关键字在PHP中定义。它包含属性（成员变量）和方法（函数）。

        - ❗ ⭐️类的三要素：封装、继承、多态

            *  封装（Encapsulation）： 隐藏对象的内部状态和实现细节，只暴露必要的接口。

            *  继承（Inheritance）： 允许一个类继承另一个类的属性和方法，促进代码重用和扩展。

            *  多态（Polymorphism）： 允许使用一个接口来代表不同类型，通过方法重写和接口实现实现。

        - ❗ ⭐️魔术方法

            *  💬 描述：魔术方法是PHP预定义的方法，例如__construct用于初始化，__toString用于在对象被当作字符串时调用。

            *  📚 资源: https://www.php.net/manual/zh/language.oop5.magic.php

        - ✅Trait 新特性

            *  💬 描述：Trait 是一种代码复用机制，允许在不使用继承的情况下引入新的方法。

            *  📚 资源:   https://www.php.net/traits

        - ⭐️命名空间

            *  💬 描述：命名空间解决命名冲突问题，允许组织相同名称的类、函数和常量。

            *  📚 资源: 

                * PHP 命名空间教程: https://www.w3cschool.cn/php/b298tfl0.html

    ✅面向对象扩展

        - 数据库操作类

            *  Mysqli 类: 用于操作MySQL数据库，提供了面向对象的接口，支持事务等高级功能。

            *  PDO 类: 提供了一种通用的数据库访问层，支持多种数据库（MySQL、SQLite、PostgreSQL等），并且使用预处理语句，提高了安全性。

        - 文件上传类

            *  📚 资源： https://packagist.org/packages/codeguy/upload

        - 图片处理类

            *  Intervention Image: 是一个强大的图像处理库，支持各种图像操作，如调整大小、裁剪、过滤等。

        - 验证码类

            *  Gregwar\Captcha\CaptchaBuilder: 用于生成验证码图片，并提供验证用户输入验证码的方法。

        - 分页类

            *  Pagerfanta: 是一个用于分页的库，提供了易于使用的分页器，支持各种数据源。

    ❗ PHP 设计模式

        - 💬 描述：设计模式（Design pattern）代表了最佳的实践，通常被有经验的面向对象的软件开发人员所采用。设计模式是软件开发人员在软件开发过程中面临的一般问题的解决方案。这些解决方案是众多软件开发人员经过相当长的一段时间的试验和错误总结出来的。

        - 📚 资源: 

            *  PHP设计模式教程: https://www.w3cschool.cn/phpdesignpattern/

        - ⭐️单例模式 (Singleton Pattern)

            *  概念： 单例模式确保一个类只有一个实例，并提供一个全局访问点。这通常通过将类的构造函数声明为私有，然后提供一个静态方法来获取唯一的实例来实现。

            *  场景： 适用于需要在整个应用程序中共享一个资源实例的情况，例如数据库连接、日志记录器等。

        - ✅工厂模式 (Factory Pattern)

            *  概念： 工厂模式用于创建对象，但与直接实例化对象不同，它使用一个工厂类来封装对象的创建过程。这有助于解耦客户端代码和具体类的实现，使系统更加灵活。

            *  场景： 适用于需要根据条件或配置创建不同类型对象的情况，或者希望隐藏对象创建细节的情况。

        - ✅依赖注入 (Dependency Injection)

            *  概念： 依赖注入是一种通过外部传递依赖关系的方式，而不是在类内部直接创建依赖的对象。这有助于实现松耦合，使代码更易于测试和维护。

            *  场景： 适用于需要将依赖关系从高层组件传递给低层组件，以实现可测试性和灵活性的情况。也常用于框架和库的设计中。

    ✅HTTP 协议

        - 📚 资源: 

            *  HTTP协议基础: https://www.cnblogs.com/SharkJiao/p/13977867.html

        - B/S 架构讲解

            *  B/S 架构（Browser/Server Architecture）是一种客户端-服务器体系结构，其中浏览器（客户端）和服务器之间通过网络进行通信。在 B/S 架构中，用户通过浏览器访问应用程序，而应用程序的核心功能则在服务器上执行。这种架构的优点包括跨平台性、集中式管理、易于维护等。

        - HTTP 协议

            *  HTTP（Hypertext Transfer Protocol）是一种用于传输超文本的应用层协议。它是Web通信的基础，客户端通过浏览器发送 HTTP 请求，服务器通过 HTTP 响应返回数据。HTTP 是一个无状态的协议，每个请求-响应周期都是相互独立的。

        - HTTP 请求、HTTP 响应、HTTP 状态码

            *  HTTP 请求： 由客户端发起，包含请求方法（GET、POST 等）、请求路径、协议版本、请求头部、请求体等信息。

            *  HTTP 响应： 由服务器回复客户端的请求，包含响应状态码、响应头部、响应体等信息。

            *  HTTP 状态码： 用于表示服务器对请求的处理结果。常见状态码包括 200 OK（请求成功）、404 Not Found（资源未找到）、500 Internal Server Error（服务器内部错误）等。

        - PHP 模拟 HTTP 请求

            *  PHP 可以使用 cURL 来模拟发送 HTTP 请求。这种方式允许 PHP 程序模拟浏览器的行为，与其他服务器进行通信。

        - HTTPS 协议

            *  HTTPS（Hypertext Transfer Protocol Secure）是在 HTTP 的基础上加入了安全套接字层（SSL/TLS）的协议。它通过加密传输的数据，提供更高级别的安全性，适用于敏感信息的传输，如登录凭证、支付信息等。

        - GuzzleHttp

            *  GuzzleHttp 是一个用于发送 HTTP 请求的 PHP 库。它提供了简洁的 API 接口，支持同步和异步请求，处理 cookies、重定向等功能。GuzzleHttp 常被用于在 PHP 中进行 HTTP 请求，例如与 RESTful API 通信、爬虫等场景。

    ⭐️会话处理

        - 💬 描述：会话技术用于在服务器端跟踪用户与应用程序的交互。在 PHP 中，最常见的两种会话技术是使用 Cookie 和 Session。这些技术使得服务器能够在用户访问不同页面时保持状态信息。

        - 📚 资源: 

            *  Cookie教程: https://www.w3cschool.cn/php/php-cookies.html

            *  Session教程: https://www.w3cschool.cn/php/php-sessions.html

        - ❗ Cookie 与Session 的区别

            *  Cookie

                * 存储在客户端，以文本文件形式保存在用户的计算机上。

                * 有大小限制，通常每个域名下的浏览器对 Cookie 数量和大小都有限制。

                * 可以设置过期时间，可以在客户端保留一段时间。

                * 跨页面和跨域通信时需要携带 Cookie 信息。

            *  Session

                * 存储在服务器端，客户端只保存一个 Session ID。

                * 通常没有大小限制，存储在服务器的内存或文件中。

                * 通常在用户关闭浏览器或一段时间不活动后过期。

                * 只能在服务器端访问，不会在客户端暴露真实数据。

        - Cookie

            *  Cookie 原理

                * 当服务器收到 HTTP 请求时，通过响应头 Set-Cookie 将 Cookie 信息发送给客户端。

                * 客户端在接收到响应后将 Cookie 存储在本地。

                * 在后续请求中，客户端会通过请求头中的 Cookie 字段将存储的 Cookie 信息发送给服务器。

            *  Cookie 操作

                * 设置 Cookie

                    ~ setcookie("user", "John Doe", time() + 3600, "/");

                * 读取 Cookie

                    ~ echo $_COOKIE["user"];

                * 删除 Cookie

                    ~ setcookie("user", "", time() - 3600, "/");

        - Session

            *  Session 原理

                * 当用户访问服务器时，服务器生成一个唯一的 Session ID，并将该 ID 发送给客户端。

                * 客户端将 Session ID 存储在 Cookie 中（或通过 URL 参数传递）。

                * 服务器端存储用户的数据，以 Session ID 为索引。

            *  Session 操作

                * 开始 Session

                    ~ session_start();

                * 设置 Session 变量

                    ~ $_SESSION["user"] = "John Doe";

                * 读取 Session 变量

                    ~ echo $_SESSION["user"];

                * 销毁 Session

                    ~ session_destroy();

    ❗ ✅安全

        - ✅XSS 攻击

            *  💬 描述：XSS（Cross-Site Scripting）攻击是一种 Web 攻击手段，攻击者通过注入恶意脚本代码到网页中，使得用户在浏览器中执行这些恶意脚本。这种攻击可能导致用户的敏感信息被盗取、会话劫持等问题。

            *  类型：

                * 存储型 XSS： 恶意脚本被存储在服务器端，用户访问时从服务器获取并执行。常见于留言板、评论等地方。

                * 反射型 XSS： 恶意脚本通过用户输入的数据传递给服务器，服务器返回响应时注入并执行。常见于 URL 参数、搜索框等。

                * DOM-based XSS： 恶意脚本通过修改页面的 DOM 结构来执行攻击，不涉及服务器。常见于客户端渲染的单页面应用。

            *  防御措施：

                * 对用户输入进行合法性验证和过滤。

                * 使用 Content Security Policy（CSP）限制允许加载的资源。

                * 对输出进行 HTML 转义。

        - ✅CSRF 攻击

            *  💬 描述：CSRF（Cross-Site Request Forgery）攻击是一种通过伪装用户请求的方式，实现对用户在其他站点的操作的攻击手段。攻击者借助用户的身份发起恶意请求，如修改用户密码、发表评论等。

            *  攻击原理：

                * 用户登录某网站A并获取认证 Cookie。

                * 在不知情的情况下，用户访问了攻击者的网站B。

                * 攻击者的网站B中包含恶意请求，该请求携带了用户在网站A的 Cookie。

                * 由于浏览器的同源策略，请求会带上用户在网站A的身份信息，导致服务器误以为是用户合法的请求。

            *  防御措施：

                * 使用 CSRF Token，确保请求是由合法用户发起的。

                * 检查 Referer 头，但不是完全可靠。

                * 对关键操作需要用户进行二次验证。

        - ⭐️SQL注入攻击

            *  💬 描述：SQL注入是一种常见的网络攻击手法，攻击者通过在应用程序的输入字段中插入恶意的SQL代码，从而利用数据库系统的漏洞执行非法的SQL查询。这种攻击可能导致数据泄露、数据损坏或者完全控制数据库。

            *  攻击原理：

                * 用户输入未过滤验证： 攻击者利用应用程序未对用户输入进行充分验证和过滤的漏洞，向输入字段中插入恶意的SQL代码。

                * 拼接SQL语句： 攻击者构造特殊的SQL语句，通过拼接在输入中插入的恶意代码，使数据库误以为这是合法的查询语句。

                * 执行恶意查询： 当应用程序将构造好的SQL语句发送给数据库执行时，恶意代码被执行，可能导致数据泄露、修改或删除。

            *  防御措施：

                * 参数化查询： 使用参数化的查询语句，而不是直接拼接用户输入到SQL语句中。参数化查询可以防止恶意代码的注入。

                * 输入验证和过滤： 对用户输入进行严格的验证和过滤，确保只有合法的数据被传递给数据库。不信任的输入应该被拒绝。

                * 最小权限原则： 为数据库用户分配最小必需的权限，避免赋予过高的权限，以限制攻击者在数据库中的活动范围。

                * 使用ORM框架： 对象关系映射（ORM）框架可以帮助抽象数据库访问，减少直接操作SQL的机会，从而减轻SQL注入的风险。

                * 日志记录和监控： 实施全面的日志记录，以便检测和响应潜在的SQL注入攻击。监控数据库活动可以帮助及早发现异常。

    ❗ ✅MVC 开发思想

        - 💬 描述：MVC（Model-View-Controller）是一种软件设计模式，它有助于组织和分离应用程序的代码。

        - 模型（Model）：

            *  负责处理应用程序的数据逻辑，包括数据库查询、数据验证和业务规则。

            *  与数据库交互，获取、存储和处理数据。

            *  不包含任何与用户界面相关的代码。

        - 视图（View）：

            *  负责用户界面的呈现和显示。

            *  从模型中获取数据，但不直接与数据库交互。

            *  可以包含一些简单的逻辑，但主要关注数据的显示。

        - 控制器（Controller）：

            *  接收用户的输入，通常通过URL中的参数或表单提交。

            *  根据用户的输入调用相应的模型处理数据逻辑，并选择适当的视图进行显示。

            *  处理应用程序的流程控制，将用户输入与模型和视图连接起来。

    

    ⭐️ Git 版本控制

        - 💬 描述：Git是一个分布式版本控制系统，用于追踪文件和目录的变化，支持多人协同开发。

        - 📚 资源

            *  Git 文档：https://www.w3cschool.cn/git/

            *  Git 基础课程：https://www.w3cschool.cn/minicourse/play/gitcourse

            *  Git 练习网站：https://learngitbranching.js.org/?locale=zh_CN

        - ⭐️常用命令

            *  初始化仓库

                * git init: 在当前目录初始化一个新的Git仓库。

            *  克隆仓库

                * git clone <仓库URL>: 从远程仓库克隆代码到本地。

            *  基本配置

                * git config --global user.name "Your Name": 设置全局用户名。

                * git config --global user.email "your.email@example.com": 设置全局用户邮箱。

            *  添加和提交

                * git add <文件名>: 将文件添加到暂存区。

                * git commit -m "提交信息": 提交暂存区的文件到版本库。

            *  查看状态

                * git status: 查看工作区、暂存区和版本库的状态。

            *  查看提交历史

                * git log: 查看提交历史。

                * git log --oneline: 以一行的形式查看提交历史。

            *  分支操作

                * git branch: 查看本地分支。

                * git branch <分支名>: 创建新分支。

                * git checkout <分支名>: 切换到指定分支。

                * git merge <分支名>: 将指定分支合并到当前分支。

            *  远程仓库

                * git remote add origin <仓库URL>: 关联本地仓库与远程仓库。

                * git push -u origin <分支名>: 推送本地分支到远程仓库。

                * git pull origin <分支名>: 拉取远程仓库的更新。

            *  撤销和修改

                * git reset HEAD <文件名>: 从暂存区撤销文件。

                * git checkout -- <文件名>: 丢弃工作区的修改。

            *  标签

                * git tag <标签名>: 创建标签。

                * git tag -a <标签名> -m "标签说明": 创建带注释的标签。
```
 ## 第三阶段：深入前端
 ```

     ⭐️Javascript

        - 💬 描述：JavaScript是一种用于网页开发的高级脚本语言，能够使网页实现动态交互和响应用户操作。

        - 📚 资源：

            *  JavaScript 教程: https://www.w3cschool.cn/javascript/

            *  JavaScript实战:https://www.w3cschool.cn/codecamp/newList/javascriptbase 

            *  JavaScript手册: https://developer.mozilla.org/zh-CN/docs/Web/JavaScript

        - ⭐️ 基本语法

            *  变量声明： 使用 var, let, 或 const 关键字声明变量。

            *  数据类型： JavaScript 包括基本的数据类型，如数字、字符串、布尔值，以及复杂的数据类型，如数组和对象。

            *  运算符： 包括算术运算符（+、-、*、/）、比较运算符（==、!=、>、<）、逻辑运算符（&&、||、!）等。

            *  条件语句： 使用 if、else if 和 else 来进行条件判断。

            *  循环语句： 使用 for、while 或 do-while 进行循环。

            *  函数： 使用 function 关键字定义函数。

            *  数组和对象： JavaScript 支持数组和对象，它们是用于存储和组织数据的重要数据结构。

            *  事件处理： 在网页开发中，常常使用事件处理来响应用户的交互。例如，通过添加事件监听器来处理按钮点击事件。

        - ⭐️ 数据类型

            *  值类型

                * ✅number: 数字类型，包括整数和浮点数。

                * ✅string: 字符串类型，用于表示文本。

                * ✅boolean: 布尔类型，表示 true 或 false。

                * ❗ ✅null: 表示空值或不存在的对象。

                * ❗ ✅undefined: 表示未定义的值。

                * bigint: 大整数类型，用于表示超过 Number.MAX_SAFE_INTEGER 范围的整数。

                * symbol: 符号类型，用于创建唯一的标识符。

            *  ⭐️引用类型

                * ✅对象 Object

                * ✅数组 Array

                * ✅函数 Function

        - ✅ 数据类型转换

            *  了解更多: https://github.com/lucoo01/frontend/blob/main/JavaScript/JavaScript%20%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B%E8%BD%AC%E6%8D%A2.md

        - ✅ 函数

            *  ⭐️ 概念

            *  ⭐️ 自定义函数

            *  调用方式

                * ⭐️ 全局调用

                * 构造函数调用

                * ⭐️ 函数方法调用

                * apply

                * call

            *  ✅❗ 闭包

                * 基本概念

                * 面试题

                    ~ 解释什么是闭包？

                    ~ 闭包的作用是什么？

                    ~ 闭包与作用域链有何关系？

                    ~ 解释柯里化的概念，并提供一个使用闭包实现柯里化的例子。

        - ✅ 对象

            *  概念

            *  常用对象

                * 数字 Number

                * 字符串 String 对象

                * 日期 Date 对象

                * 数组 Array

                * 布尔 Boolean

                * 算数 Math

            *  ❗ ⭐️this

            *  ❗ ⭐️原型链和继承

            *  自定义对象

        - ✅❗ 作用域（作用域链）

        - ✅ BOM API

        - ⭐️ DOM API

        - ⭐️ JSON

        - ⭐️ Ajax

        - ⭐️事件

            *  💬 描述：事件是指用户在页面上执行的操作，如点击按钮、输入文本、移动鼠标等。在JavaScript中，可以通过事件来触发相应的函数或执行特定的代码，以实现对用户交互的响应。

            *  常见事件：

                * click： 鼠标点击事件，通常与按钮或链接相关。

                * mouseover / mouseout： 鼠标悬停和离开事件，用于在鼠标经过或离开元素时触发。

                * keydown / keyup： 键盘按下和释放事件，用于捕获键盘输入。

                * submit： 表单提交事件，当用户提交表单时触发。

                * change： 输入框值改变事件，用于捕获用户输入的变化。

                * load： 页面加载事件，当页面完全加载时触发。

                * resize： 窗口大小改变事件，当浏览器窗口大小改变时触发。

            *  事件模型：

                * 💬 描述：事件模型描述了事件在传播和处理过程中的行为。在JavaScript中，有两种主要的事件模型：

                * 冒泡事件模型（Bubbling）： 事件从最内层的元素开始传播，逐级向外传递到最外层元素。大多数事件都采用冒泡模型。

                * 捕获事件模型（Capturing）： 事件从最外层元素开始传播，逐级向内传递到最内层元素。捕获模型在事件到达实际目标之前捕获它。

    ✅ ES6+ 特性

        - 💬 描述：新引入的 JavaScript 语法特性。

        - 📚 资源：ES6 入门教程 https://es6.ruanyifeng.com/

        - ⭐️let 和 const

            *  let 和 const 是用于声明变量的关键字。

            *  let 允许声明一个变量，并且它的作用域是块级的（在花括号 {} 内有效）。

            *  const 用于声明一个常量，其值在声明后不能被修改。

        - 变量解构赋值

            *  可以通过解构赋值语法从数组或对象中提取值，并赋给变量。

            *  例如：const [a, b] = [1, 2]; 将数组 [1, 2] 中的值分别赋给变量 a 和 b。

        - 对象扩展和新增方法

            *  对象扩展允许通过简洁的语法向对象中添加新属性。

            *  新增方法可以使用函数简写的方式将函数添加到对象中。

        - Symbol

            *  Symbol 是一种新的原始数据类型，用于创建唯一的标识符。

            *  每个通过 Symbol 创建的值都是唯一的，不会与其他任何值相等。

        - Set 和 Map 数据结构

            *  Set 是一种集合数据结构，它只存储唯一值，不允许重复。

            *  Map 是一种键值对的集合，其中键和值可以是任何数据类型。

        - ⭐️❗Promise & async / await 异步编程

            *  Promise 是一种处理异步操作的对象，表示一个可能会在未来完成的事件。

            *  async/await 是用于处理异步代码的语法糖，使得异步代码看起来更像同步代码。

        - Generator 函数异步编程

            *  Generator 函数是一种特殊的函数，可以通过 yield 暂停执行并在需要时恢复。

            *  与 async/await 类似，Generator 函数也用于处理异步代码，但它提供了更灵活的控制流。

    ✅jQuery

        - 💬 描述：jQuery是一个快速、轻量级、跨浏览器的JavaScript库，简化了DOM操作、事件处理、动画效果等任务，使Web开发更便捷。

        - 📚 资源：

            *  jQuery 入门课程(互动课): https://www.w3cschool.cn/minicourse/play/jquerycourse

            *  jQuery 入门实战(实战课):  https://www.w3cschool.cn/codecamp/newList/jquery_learn

    ✅Ajax

        - 📚 资源：

            *  Ajax + JSON 入门课程: https://www.w3cschool.cn/minicourse/play/ajaxcourse

        - 同步和异步

            *  同步（Synchronous）： 操作是按顺序执行的，一个操作完成后才能开始下一个。同步操作可能会导致页面被阻塞，用户需要等待操作完成。

            *  异步（Asynchronous）： 操作是同时进行的，不需要等待上一个操作完成。Ajax通常是异步的，允许在后台发送请求并在继续执行其他操作的同时处理响应。

        - ❗ 跨域

            *  跨域指的是在不同域名、端口或协议之间进行网络请求。由于浏览器的同源策略，Ajax请求默认是受限制的。可以通过CORS（跨域资源共享）等机制来解决跨域问题。

        - ⭐️axios

            *  Axios是一个基于Promise的HTTP客户端，用于浏览器和Node.js。它可以用于发送异步请求，并提供了简洁的API和强大的拦截器功能。

        - fetch

            *  Fetch是浏览器提供的用于进行网络请求的API，它使用Promise对象处理异步操作。与XMLHttpRequest相比，Fetch提供更简洁和强大的接口。

    ⭐️Vue

        - 💬 描述：Vue是一套用于构建用户界面的渐进式JavaScript框架，通过声明式渲染和组件化开发提供了简洁而灵活的前端开发方式。

        - 📚 资源：

            *  Vue2入门课程: https://www.w3cschool.cn/minicourse/play/vuecourse

            *  Vue.js三天学习实战教程: https://www.w3cschool.cn/minicourse/play/hjhvue

            *  Vue.js 电商后台管理系统:https://www.w3cschool.cn/minicourse/play/txyvue3dshtglxt

            *  Vue 3.0 新特性全面解析: https://www.w3cschool.cn/minicourse/play/txyvue3

        - Vue实例

            *  了解如何创建Vue实例，掌握实例的生命周期和常用选项。

        - 模板语法

            *  学习Vue的模板语法，包括插值、指令、事件处理等，以便有效地操作DOM。

        - 数据绑定

            *  理解Vue的双向数据绑定机制，学会如何将数据绑定到模板，以及如何响应数据的变化。

        - 组件

            *  掌握Vue组件的创建、传递数据、事件通信，以及组件的生命周期，这是Vue中重要的模块化开发概念。

        - 指令

            *  熟悉常用指令如v-if、v-for、v-bind、v-on等，它们在模板中提供了丰富的功能。

        - 计算属性和观察者

            *  学会使用计算属性处理复杂逻辑，以及观察者来监听数据变化执行自定义操作。

        - 路由（Vue Router）

            *  学会使用Vue Router进行前端路由管理，实现单页面应用（SPA）的导航。

        - 状态管理（Vuex）

            *  了解Vuex的概念，学会在大型应用中集中管理状态，以保持组件间的数据一致性。
```
 ## 第四阶段：工具&框架
 ```

     ⭐️Composer

        - 💬 描述：Composer是一款用于PHP依赖管理的工具，它允许你声明项目所需的依赖关系，并通过简单的命令将它们安装到项目中。Composer使用composer.json文件来定义项目的依赖关系，同时它还能自动加载这些依赖项中的类。

        - 📚 资源：

            *  Composer 教程: https://www.w3cschool.cn/composer/

        - PSR 规范

            *  💬 描述：PSR（PHP Standard Recommendation）是PHP-FIG（PHP Framework Interop Group）制定的一组规范，旨在促进PHP生态系统中各种框架和项目之间的互操作性。这些规范定义了编码风格、自动加载、日志接口等方面的标准，以确保PHP项目在不同框架之间更加一致和可互操作。

        - 安装和基本使用

            *  php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"

            *  php composer-setup.php

            *  php -r "unlink('composer-setup.php');"

        - composer.json

            *  💬 描述：composer.json是Composer的配置文件，其中包含项目的元数据和依赖项定义。该文件通常包括项目名称、版本、作者信息以及需要安装的依赖项列表。

        - 类库管理详解

            *  Composer通过composer.json中的require部分定义项目的依赖关系。依赖关系可以是PHP库、框架或其他项目。Composer会自动下载并安装这些依赖项，同时生成一个vendor目录，其中包含了所有依赖项的代码。你可以通过Composer提供的自动加载机制轻松地在项目中使用这些类库。

    ⭐️ThinkPHP 框架

        - 💬 描述：ThinkPHP 是一个遵循MVC设计模式的轻量级开源PHP框架，广泛用于简化和加速Web应用开发。

        - 📚 资源：

            *  ThinkPHP8官方文档: https://doc.thinkphp.cn/v8_0/preface.html

            *  ThinkPHP6零基础入门教程: https://www.w3cschool.cn/minicourse/play/thinkphp6

            *  ThinkPHP6微信JSAPI支付: https://www.w3cschool.cn/minicourse/play/qkuzy

            *  Thinkphp 进阶与实战: https://www.w3cschool.cn/minicourse/play/think

        - 请求流程

            *  📚 资源：https://doc.thinkphp.cn/v8_0/request_flow.html

        - 路由

            *  📚 资源：https://doc.thinkphp.cn/v8_0/route.html

        - 控制器

            *  📚 资源： https://doc.thinkphp.cn/v8_0/controller.html

        - 视图

            *  📚 资源：https://doc.thinkphp.cn/v8_0/view.html

        - 模型

            *  📚 资源： https://doc.thinkphp.cn/v8_0/orm.html

        - 验证

            *  📚 资源： https://doc.thinkphp.cn/v8_0/validate.html

        - 扩展库

            *  📚 资源：https://doc.thinkphp.cn/v8_0/extend_library.html

    ✅RESTFUL 架构

        - 💬 描述：RESTful架构是一种基于HTTP协议的网络应用程序设计风格，它利用HTTP动词（如GET、POST、PUT、DELETE）来操作资源的表示，以实现高效、可扩展和灵活的接口设计。

        - RESTful API 设计六要素

            *  资源路径(URI)

            *  HTTP动词(Method)

            *  过滤信息(query-string)

            *  状态码(Status-code)

            *  错误信息(Error)

            *  返回结果(Result)

        - 编写 API 接口文档

            *  💬 描述：API文档是开发者之间沟通如何使用API的桥梁，应该清晰、完整、易懂。可以使用工具如Swagger或Postman可以更容易地创建、维护和测试API文档。

        - JWT 技术

            *  💬 描述：JWT（JSON Web Token）是一种用于在网络上安全地传输信息的开放标准（RFC 7519）。它通过使用 JSON 对象在各方之间安全地传输信息，这些信息可以被验证和信任。JWT通常用于在用户和服务之间传递身份验证信息，以确保用户在访问受保护的资源时能够被正确地识别和授权。
```
 ## 第五阶段：大型项目架构
```
    ✅Nginx

        - 💬 描述：Nginx是一款高性能的开源Web服务器和反向代理服务器，以及用于负载均衡、缓存和作为应用服务器的通用HTTP服务器。

        - 📚 资源：

            *  Nginx 入门指南: https://www.w3cschool.cn/nginx/

            *  Nginx快速入门指南: https://www.w3cschool.cn/minicourse/play/nginx_my

        - 基础配置： Nginx的基本配置和结构，包括nginx.conf文件的各个部分。

        - 虚拟主机： 如何配置和管理虚拟主机，处理多个域名或站点的情况。

        - Location块： 理解location块的作用，学会使用不同的匹配规则。

        - 反向代理： 配置Nginx作为反向代理，将请求转发到后端服务器。

        - 负载均衡： 学习如何配置Nginx进行负载均衡，分发请求到多个服务器。

        - SSL/TLS配置： 如何配置Nginx以支持安全的HTTPS连接，包括证书的配置。

        - 日志和错误处理： 理解Nginx的日志文件，以及如何配置错误页面和处理错误码。

        - 缓存和压缩： 如何配置Nginx进行静态资源缓存和压缩。

        - 安全性配置： 学会配置Nginx的安全性，包括限制访问、防范攻击等。

        - 性能调优： 了解Nginx的性能调优策略，包括调整工作进程、连接池等参数。

    ⭐️Redis

        - 💬 描述：Redis是一个基于内存的开源数据存储系统，支持多种数据结构（如字符串、哈希表、列表、集合、有序集合），用于缓存、数据库和消息队列等场景，具有高性能、持久性、分布式支持等特点。

        - 📚 资源：

            *  Redis快速入门课程: https://www.w3cschool.cn/minicourse/play/redis_mym

            *  Redis 教程: https://www.w3cschool.cn/redis/

        - 数据类型： 理解Redis支持的不同数据类型，如字符串、哈希表、列表、集合和有序集合。

        - 基本操作： 掌握常见的数据操作命令，包括读写数据、删除数据、查询数据等。

        - 持久化： 了解Redis的持久化机制，包括RDB快照和AOF日志，以确保数据的持久性。

        - 主从复制： 学会配置Redis主从复制，实现数据的备份和高可用性。

        - 哨兵模式： 了解哨兵模式，用于监控和自动故障转移。

        - 分区： 学习如何配置Redis分区，以支持更大规模的数据集和并发请求。

        - 事务： 了解Redis的事务机制，通过MULTI、EXEC、DISCARD等命令实现事务操作。

        - 发布订阅： 学习Redis的发布订阅模式，实现消息的广播和订阅。

        - 性能优化： 掌握一些性能优化的技巧，如合理使用数据结构、设置合适的内存策略等。

        - 安全性： 学会配置Redis的安全性，包括密码认证、网络访问控制等。

        - 监控和日志： 了解如何监控Redis的运行状态，以及如何分析和处理日志信息。

        - 客户端： 学习如何使用不同语言的客户端库与Redis进行交互。

    ✅Mongodb

        - 💬 描述：MongoDB是一个开源的NoSQL数据库管理系统，以文档导向的方式存储数据，支持复杂的数据结构，具有灵活的模式设计、横向可扩展性和适用于大规模数据存储与查询的特性。

        - 📚 资源：

            *  MongoDB 教程: https://www.w3cschool.cn/mongodb/

            *  MongoDB入门与案例分析: https://www.w3cschool.cn/minicourse/play/mongodb_my

        - 数据模型： 理解MongoDB的文档导向数据模型，包括嵌套文档和数组的使用。

        - CRUD操作： 掌握MongoDB的基本操作，包括插入（Create）、查询（Read）、更新（Update）、删除（Delete）等。

        - 索引和性能优化： 学习如何创建索引以提高查询性能，了解性能优化的一些常见策略。

        - 聚合框架： 掌握MongoDB的聚合框架，用于复杂数据处理和分析。

        - 复制和故障转移： 学会配置MongoDB的复制集，实现数据的备份和高可用性。

        - 分片： 了解MongoDB的分片机制，支持大规模数据集的水平扩展。

        - 安全性： 学习如何配置MongoDB的认证、授权和其他安全设置。

        - 备份和恢复： 了解如何进行MongoDB的备份和恢复操作，确保数据的可靠性。

        - 驱动程序和客户端： 使用不同语言的MongoDB驱动程序与MongoDB进行交互。

        - 日志和监控： 了解MongoDB的日志记录功能和监控工具，以便追踪系统状态。

        - 地理空间查询： 如果涉及地理信息，了解MongoDB的地理空间查询功能。

        - 文档验证： 学会使用文档验证功能，确保数据符合预定义的模式。

    ❗ ⭐️MySQL 优化

        - 📚 资源：

            *  MySQL从入门到精通: https://www.w3cschool.cn/minicourse/play/mysql2_my

        - 数据类型优化： 选择合适的数据类型以节省存储空间和提高查询性能，例如使用INT代替VARCHAR存储数字。

        - 三范式： 数据库设计中的三范式（1NF、2NF、3NF）有助于提高数据的一致性、减少冗余和提高查询性能。

        - ❗ 存储引擎： MySQL支持多种存储引擎，如InnoDB、MyISAM等，选择合适的存储引擎根据应用需求和特性进行优化。

        - ❗ 索引操作： 使用索引加速查询操作，但要避免过多或不必要的索引，以减少写操作的开销。

        - 索引分类： 分为单列索引和复合索引，选择合适的索引类型取决于查询需求和数据特点。

        - 索引结构： MySQL的索引结构包括B-tree、Hash索引等，了解不同索引结构的优缺点有助于选择适当的索引。

        - 执行计划： 通过EXPLAIN语句查看查询执行计划，优化查询语句以减少资源消耗。

        - 主从复制： 配置MySQL主从复制以实现数据备份、读写分离和提高系统可用性。

        - 读写分离： 将读操作分发到多个服务器，减轻主服务器压力，提高系统性能。

        - Mycat使用： Mycat是一个开源的MySQL数据库中间件，支持分库分表、读写分离等特性，用于提高数据库的扩展性和性能。

    ✅搜索服务

        - Sphinx

            *  💬 描述：Sphinx是一个开源全文搜索引擎，专注于高性能、快速索引和检索大规模文本数据，支持分布式搜索和多种编程语言的客户端。

        - ElasticSearch

            *  💬 描述：Elasticsearch是一个开源的分布式搜索和分析引擎，基于Lucene构建，提供强大的全文搜索、实时数据分析和可视化等功能。

    ✅Laravel

        - 💬 描述：Laravel是一款优雅而富有表达力的PHP Web应用框架，提供便捷的语法和丰富的功能，用于简化开发过程并构建高效、可维护的现代Web应用。

        - 📚 资源：

            *  Laravel 10 中文文档 : https://learnku.com/docs/laravel/10.x

            *  Laravel 中文教程: https://www.w3cschool.cn/laravel_8/

            *  Laravel入门到项目实战: https://www.w3cschool.cn/minicourse/play/phpinit_3

            *  Laravel入门到实战: https://www.w3cschool.cn/minicourse/play/laravelpre

            *  基于Laravel框架的API实战: https://www.w3cschool.cn/minicourse/play/phpinit_5

        - 路由

            *  📚 资源：https://learnku.com/docs/laravel/10.x/routing/14845

        - 中间件

            *  📚 资源：https://learnku.com/docs/laravel/10.x/middleware/14846

        - 控制器

            *  📚 资源：https://learnku.com/docs/laravel/10.x/controllers/14848

        - 请求

            *  📚 资源：https://learnku.com/docs/laravel/10.x/requests/14849

        - 响应

            *  📚 资源：https://learnku.com/docs/laravel/10.x/responses/14850

        - 视图

            *  📚 资源：https://learnku.com/docs/laravel/10.x/views/14851

        - Blade 模板

            *  📚 资源：https://learnku.com/docs/laravel/10.x/blade/14852

        - 表单验证

            *  📚 资源：https://learnku.com/docs/laravel/10.x/validation/14856

        - 数据库

            *  📚 资源：https://learnku.com/docs/laravel/10.x/database/14882

    ✅Linux

        - 💬 描述：Linux是一个开源的Unix-like操作系统内核，被广泛应用于服务器和嵌入式系统，以其稳定性、安全性和强大的命令行工具而闻名。它支持多用户、多任务和多线程，成为计算机领域中最重要的操作系统之一。

        - 📚 资源：

            *  Linux 入门课程: https://www.w3cschool.cn/minicourse/play/linuxcourse

            *  CentOS 8 教程: https://www.w3cschool.cn/minicourse/play/sf_centoslinux

            *  Linux极速入门: https://www.w3cschool.cn/minicourse/play/linux_my

            *  Ubuntu 乌班图 - Linux课程: https://w3cschool.cn/minicourse/play/af_ubuntu

            *  从零开始学Linux: https://www.w3cschool.cn/minicourse/play/demolinux

        - 常用命令

            *  文件和目录操作

                * ls: 列出当前目录下的文件和子目录。

                * cd <目录>: 切换到指定目录。

                * pwd: 显示当前工作目录的完整路径。

                * mkdir <目录名>: 创建新目录。

                * rm <文件名>: 删除文件。

                * rmdir <目录名>: 删除空目录。

                * cp <源文件> <目标目录>: 复制文件。

                * mv <源文件/目录> <目标目录>: 移动文件或目录。

                * cat <文件名>: 查看文件内容。

            *  文件查找

                * find <目录> -name <文件名>: 在指定目录下查找文件。

                * grep <关键词> <文件>: 在文件中查找包含关键词的行。

            *  文本编辑

                * nano <文件名>: 使用nano编辑器打开文件。

                * vi <文件名>: 使用vi编辑器打开文件。

                * 按i键进入编辑模式，按Esc键退出编辑模式，然后输入:wq保存并退出。

            *  系统信息和状态

                * uname -a: 显示系统信息。

                * top: 显示系统当前运行的进程信息。

                * df -h: 显示磁盘空间使用情况。

                * free -h: 显示内存使用情况。

            *  用户和权限管理

                * whoami: 显示当前登录的用户名。

                * passwd: 修改用户密码。

                * sudo <命令>: 以超级用户权限运行命令。

                * chmod <权限> <文件>: 修改文件权限。

            *  网络相关

                * ifconfig: 显示网络接口信息。

                * ping <目标地址>: 测试与目标地址的网络连接。

                * nslookup <域名>: 查询域名对应的IP地址。

                * netstat -an: 显示网络统计信息。

            *  压缩和解压

                * tar -czvf <压缩文件名.tar.gz> <目录>: 压缩目录。

                * tar -xzvf <压缩文件名.tar.gz>: 解压缩文件。

            *  进程管理

                * ps aux: 显示当前运行的所有进程。

                * kill <进程ID>: 结束指定进程。

        - 宝塔使用

            *  💬 描述：宝塔（Baota）是一款免费开源的服务器管理面板，提供简单易用的图形界面，用于快速搭建、部署和管理Web服务器，支持多种应用环境和插件扩展。

            *  📚 资源：

                * 宝塔下载安装:https://www.bt.cn/new/download.html

                * 宝塔教程: https://www.bt.cn/bbs/thread-79460-1-1.html
```
 ## 第六阶段：更进一步
 ```

    ⭐️Swoole

        - 💬 描述：Swoole是一个高性能的PHP扩展，提供异步、协程和并发编程的支持，使PHP开发者能够轻松构建高性能、多进程的网络应用，如Web服务器、WebSocket服务器等。其协程模型和异步IO特性能显著提升应用性能和并发处理能力。

        - 📚 资源：

            *  Swoole 教程: https://www.w3cschool.cn/swoole/

        - Swoole基础： 了解Swoole的基本概念、架构和特性，包括异步、协程、事件驱动等。

        - 安装和配置： 学会安装Swoole扩展，并了解Swoole的基本配置选项。

        - 异步编程： 掌握Swoole的异步编程模型，使用Swoole提供的异步API实现非阻塞的网络应用。

        - 协程： 了解Swoole的协程模型，学习如何使用协程实现同步的代码逻辑，提高并发处理能力。

        - Swoole服务器： 学会构建基于Swoole的服务器，如Web服务器、WebSocket服务器等。

        - 协程MySQL/Redis： 使用Swoole提供的协程MySQL和协程Redis，实现异步非阻塞的数据库操作。

        - 定时器： 使用Swoole的定时器功能，实现定时任务和周期性操作。

        - 进程管理： 了解Swoole的进程管理能力，包括多进程、进程间通信等。

        - 事件驱动： 学习Swoole的事件驱动机制，处理各种网络事件和任务。

        - WebSocket： 使用Swoole构建WebSocket服务器，实现实时双向通信。

        - Task投递： 学会使用Swoole的Task功能，实现异步任务投递和处理。

        - Swoole Coroutine HTTP Client： 使用Swoole协程HTTP客户端，实现异步的HTTP请求。

        - 性能调优： 了解Swoole的性能调优策略，包括调整Worker数量、使用共享内存等。

        - Swoole生态： 探索Swoole的生态系统，了解与Swoole配套使用的各种组件和框架。

    ✅Docker

        - 💬 描述：Docker是一个开源的容器化平台，允许开发者将应用及其依赖项打包成轻量、可移植的容器，并在任何环境中运行。它通过容器技术实现了应用程序的隔离、封装和快速部署，提高了开发、测试和部署的效率。

        - 📚 资源：

            *  Docker 入门课程: https://www.w3cschool.cn/minicourse/play/dockerc

            *  Docker基础入门: https://www.w3cschool.cn/minicourse/play/docker_txy

            *  后端技能树【Linux+Docker+Git】: https://www.w3cschool.cn/minicourse/play/xbldg

            *  Docker 教程: https://www.w3cschool.cn/docker/

        - 基本概念： 了解Docker的基本概念，如容器、镜像、仓库等。

        - 安装和配置： 学会在不同操作系统上安装和配置Docker引擎。

        - Docker镜像： 理解Docker镜像的概念，学会构建、推送、拉取和管理镜像。

        - 容器操作： 掌握容器的基本操作，包括创建、启动、停止、删除容器等。

        - Dockerfile： 学会使用Dockerfile编写容器构建配置，实现自动化镜像构建。

        - 数据管理： 了解Docker容器中数据的持久化和管理方法。

        - Docker Compose： 学习使用Docker Compose定义和管理多容器应用。

        - 网络： 理解Docker网络的概念，学会创建自定义网络和连接容器。

        - Docker Swarm： 了解Docker Swarm，学会使用Swarm进行容器编排和集群管理。

        - 安全性： 学习Docker安全性最佳实践，包括容器隔离、用户权限等。

        - 监控和日志： 学习如何监控Docker容器的运行状态和收集日志信息。

        - Docker Registry： 了解Docker Registry，学会搭建私有镜像仓库。

        - 容器编排工具： 掌握其他容器编排工具，如Kubernetes等，以深入了解容器化的集群管理。

        - 实际应用： 将学到的知识应用到实际项目中，构建和部署容器化应用。

    ❌Node.js

        - 💬 描述：Node.js是一个基于Chrome V8引擎的开源JavaScript运行时环境，用于构建高性能、可伸缩的网络应用，具备非阻塞I/O和事件驱动的特性，广泛用于服务器端开发。它使得使用JavaScript语言的开发者能够在前端和后端都使用同一种语言，实现全栈JavaScript开发。

        - 📚 资源：

            *  Node.js 入门课程: https://www.w3cschool.cn/minicourse/play/orbls

            *  Node.js快速入门: https://www.w3cschool.cn/minicourse/play/txynodejs

            *  零基础入门Node.JS: https://www.w3cschool.cn/minicourse/play/leoclassndjs

            *  KOA.JS快学快用50讲: https://www.w3cschool.cn/minicourse/play/leoclasskoa

            *  Node.js 教程: https://www.w3cschool.cn/nodejs/

        - Node.js基础： 了解Node.js的核心模块、事件循环、非阻塞I/O等基础概念。

        - 模块系统： 学习如何使用模块化系统，了解require和module.exports等概念。

        - NPM（Node包管理器）： 掌握NPM的使用，能够安装、管理和发布Node.js包。

        - Express框架： 学会使用Express构建Web应用，了解路由、中间件等概念。

        - 异步编程： 理解Node.js的异步编程模型，使用回调函数、Promise、Async/Await等方式处理异步操作。

        - 事件驱动： 熟悉Node.js的事件驱动机制，了解事件监听器和触发器的使用。

        - 文件系统操作： 学习使用Node.js进行文件和目录的读写、操作。

        - 数据库连接： 掌握使用Node.js连接数据库，如MongoDB、MySQL等，了解数据库操作的异步特性。

        - RESTful API设计： 学会设计和实现RESTful API，使用Express框架进行路由控制。

        - WebSockets： 了解使用Node.js构建实时应用，使用WebSockets进行双向通信。

        - 安全性： 学习如何确保Node.js应用的安全性，防范常见的安全漏洞。

        - 测试和调试： 学习使用测试框架（如Mocha、Jest）进行单元测试，并掌握调试技巧。

        - 部署和性能优化： 了解Node.js应用的部署方式，学习性能优化的策略，包括代码优化、缓存等。
```
## PHP最佳实践
```
 PHP 之道: https://laravel-china.github.io/php-the-right-way/

 PHP资源库: https://github.com/ziadoz/awesome-php

 后端开发者路线图: https://roadmap.sh/backend
```
