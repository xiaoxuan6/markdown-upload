## Installation

下载文件放在 `editor.md/plugins` 或 `editor/plugins` 目录下

## 使用
~~~
// 引入editormd图片粘贴上传插件，执行监听方法
editormd.loadPlugin("/{editor.md || editor}/plugins/image-handle-paste/image-handle-paste", function () {
    testEditor.imagePaste();
});
~~~
