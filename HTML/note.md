## 1.基础知识

## 全局属性

即可以给所有元素使用的属性

	* title
	* tabindex 使用tab键聚焦到这个元素，转换顺序按照tabindex的值从小到大
	* id
	* class 分设置标签分类 
	* style 设置标签样式

## 2.常用html标签

```html
<!doctype html> <!--declare the type of the document-->

<html>
    <head>
        <!-- Contains metadata about the web page
         that is not displayed on the page itself -->

        <!-- each meta label can represent one meta
         information of the web page-->
        <meta charset = "utf8"> 
        <meta name = "keywords" content = "Chat GPT">
            <!-- provide keywords for the search 
             engine,but now its influence is very poor -->

        <title>Title</title>
    </head>

    <body>
        <!-- the information in there will be displayer
         in the web page -->
        <a href = "https://www.baidu.com">a hint</a> 
            <!-- add a link with description 
             P.S. href:hyper reference
                # target = "_blank" ,new a web page
                         = "_self" ,default value,open in the current page
                # href = "link" or "tel:telephone number" or "mailto:"
                        or "relative path"
                # download = "" ,trigger the download
             -->
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Doloribus itaque nam sapiente. Corporis accusamus vel delectus odit voluptas! Nihil fugiat eius qui distinctio dignissimos consectetur sunt cumque quaerat rem dicta!</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor numquam ut enim tenetur sapiente blanditiis quaerat aperiam fugit harum eum. Distinctio cupiditate quod neque? Magni dolores harum delectus quae odio.</p>

        <img width = 100 height = "200" src = "https://www.baidu.com/favicon.ico" alt = "logo">
            <!-- show a image. When the image can't be shown,the page will show the content of "alt"-->
        
        <h1>head1</h1>
        <h2>head2</h2>

        <i>akidhaklswiduh</i> <!-- italic -->
        <u>aoiufhdcoaisdh</u> <!-- underline -->
        <b>aksidhakuwhsds</b> <!-- bold -->
        <em>akesuihfdkaus</em><!-- emphasis --> 
        <strong>akwuid</strong> 

        <hr> <!-- horizontal rule -->
        <br> <!-- line break -->

        <ul> 
            <!-- unorder list -->
            <li> list item1 </li>
            <li>
                askduhkuh
                <ol>
                    <li>aaa</li>
                    <li>bbb</li>
                </ol>
            </li>
            <li> list item2 </li>
            <li> list item3 </li>
        </ul>

        <ol>
            <!-- order list -->
            <li> list item 1 <strong>a test</strong> </li>
            <li> list item 2 </li>
            <li> list item 3 </li>
        </ol>
    </body>
<html>
```

