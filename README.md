PHP2RSS
usage:
```
include_once("rss.class.php");
$RSS= new RSS("name","url","description","RSS_icon");
$RSS->AddItem("title","url","description","sendtime");
$RSS->Display();
```



PHP 生成 RSS 的类
使用方法：
```
include_once("rss.class.php");
$RSS= new RSS("名称","地址","描述","RSS频道图标");
$RSS->AddItem("标题","地址","摘要","发布日期");
$RSS->Display();
```
