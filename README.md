# CustomCanvas
基于油猴的Canvas客制化

Setup
1. 安装油猴
2. 安装js脚本
3. Enjoy！

实在不会就看视频
www.bilibili.com/video/BV1JHNEzUEXX/




如何清除本地数据？
控制台执行如下即可
```js
localStorage.removeItem('canvas_feat_enhance');
localStorage.removeItem('canvas_feat_profile');
localStorage.removeItem('canvas_feat_title');
localStorage.removeItem('canvas_custom_bg');
```

检测是否清除成功 控制台输入
```js
localStorage.getItem('canvas_feat_enhance');
```

如返回：
```js
null
```
则清除成功
