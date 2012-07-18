[![ueditor](http://www.ueditorbbs.com/template/qing/image/logo.png)](http://ueditor.baidu.com/)

ueditor-for-yii
===============


editor是由百度web前端研发部开发的所见即所得富文本web编辑器，开源基于BSD协议。


Quick start
-----------

Clone the repo, `git clone git@github.com:windsdeng/ueditor-for-yii.git`, or [download the latest release](https://github.com/windsdeng/ueditor-for-yii/zipball/master).

Usage 
-----------

把ueditor插件放到 extensions/
在相应的Html(View) 调用

```
<?php
    $this->widget('ext.ueditor.Ueditor',
            array(
                'getId'=>'Post_content',
                'UEDITOR_HOME_URL'=>"/",
                'options'=>'toolbars:[["fontfamily","fontsize",
                "forecolor","bold","italic","strikethrough","|",
"insertunorderedlist","insertorderedlist","blockquote","|",
"link","unlink","highlightcode","|","undo","redo","source"]],
                    wordCount:false,
                    elementPathEnabled:false,
                    imagePath:"/attachment/ueditor/",
                    ',
            ));
?>
```

Bug tracker
-----------

Have a bug? Please create an issue here on GitHub! Also, when filing please make sure you're familiar with [necolas's guidelines](https://github.com/necolas/issue-guidelines). thanks! <3

https://github.com/windsdeng/ueditor-for-yii/issues

http://www.ueditorbbs.com/forum.php?mod=forumdisplay&fid=2


UEditor - Demo
-----------

http://ueditor.baidu.com/website/onlinedemo.html

UEditor - Help
-----------

http://ueditor.baidu.com/website/helper.html


UEditor Document
-----------

http://ueditor.baidu.com/website/document.html

UEditor Changelog
-----------

http://ueditor.baidu.com/website/changelog.html

