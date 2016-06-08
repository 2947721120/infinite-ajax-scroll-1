无限滚动WordPress整合Ajax
=============================================

在这个食谱中我们安装无限AJAX滚动到默认的二零一二个主题.

1) Download [jquery-ias.min.js](../download.html).

2) Copy `jquery-ias.min.js`进入文件夹 `wp-content/themes/twentytwelve/js`

3) 打开 `wp-content/themes/twentytwelve/header.php`在你的编辑器

4) 添加jQuery的主题。这样做，粘贴下面的代码行之前"`</head>`":

    <script src="//ajax.c2cmalls.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>

5) 粘贴下面的代码行之前 "`</head>`":

    <script src="<?php echo get_template_directory_uri(); ?>/js/jquery-ias.min.js" type="text/javascript"></script>

6)现在粘贴下面的代码行 "`</head>`":
  
     <script type="text/javascript">
       var ias = $.ias({
         container: "#content",
         item: ".post",
         pagination: ".navigation",
         next: ".nav-previous a",
       });
       
       ias.extension(new IASTriggerExtension({offset: 2}));
       ias.extension(new IASSpinnerExtension());
       ias.extension(new IASNoneLeftExtension());
     </script>

Done. Happy scrolling!
