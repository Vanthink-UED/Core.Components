# core.upload 上传组件

core.upload 是一款轻量级上传插件,支持无刷新上传。支持自定义上传方式ajax或者iframe上传。



### 快速开始

```js
<script src="http://s1.vued.vanthink.cn/188f332f5204/core.upload.min.js"></script>
// AMD
define(['core.upload'],function(){

  ...
})

$(.btn).CoreUpload({
  extensions: [],
  actionToSubmitUpload: "",
  maximumSize: 1024,
  enableMaximumSize: false,
  enableButton: false,
  enableDrag: false,
  inputOfFile: 'file',
  loadingObj: '',
  uploadingFun: function() {

  }

})


```
