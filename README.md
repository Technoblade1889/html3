# html3
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML练习3-行元素与块元素</title>
</head>
<body>
    <!-- 块元素：用于创建页面主要部分，如段落、标题、列表等
     可以包含其他块级元素和行内元素
    -->
     <div></div>
     <p></p>
     <h1></h1>
     <ul></ul>
     <form></form>
     <table></table>

     <!-- 行元素：用于添加文本，例如超链接，强调文本等
      通常独占一行，分行需要额外的指令；
      不能包含块元素，但可以包含行元素；
     -->
      <span></span>
      <a></a>
      <strong></strong>
      <b></b>
      <em></em>



     <!-- 关于div和span -->
     <!-- div没有内容，只是用于编辑网页，比如标题，侧边栏，与<body>的作用类似 -->

     <div class="nav-bar"></div> <!-- 导航栏的创立-->

     <div class="content"></div><!-- 文章内容 -->

     <!-- span：框起内容以方便使用样式、CSS、或者JS行为 -->
     <span>这是第一个span标签</span>
     <span>这是第二个span标签</span>
     <hr>
     <span>链接点这里<a href="#">链接</a></span>

     <!-- 总之，div与span通常与CSS、JS一起使用，用于实现更加复杂的页面 -->
    

</body>
</html>
