# task002
js学习：
由于脚本会阻塞页面其他资源的下载，因此推荐将所有<script>标签尽可能放到<body>标签的底部，以尽量减少对整个页面下载的影响。例如清单 3
清单 3 推荐的代码放置位置示例：
<html>
<head>
    <title>Source Example</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <p>Hello world!</p>

    <!-- Example of efficient script positioning -->
    <script type="text/javascript" src="script1.js"></script>
    <script type="text/javascript" src="script2.js"></script>
    <script type="text/javascript" src="script3.js"></script>
</body>
</html>
